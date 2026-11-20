# Wiki de BandolerosRP V2

Documentación para GitBook, en dos espacios separados:

| Carpeta | Espacio de GitBook | Público |
|---|---|---|
| `jugadores/` | Wiki de jugadores | Sí: cualquiera con el enlace |
| `staff/` | Manual del staff | **No**: solo el equipo (comandos de admin, sanciones, detalles de los sistemas de robo) |

Cada carpeta tiene su `.gitbook.yaml`, `README.md` (portada) y `SUMMARY.md` (índice de la barra lateral).

## Conectar con GitBook

1. Sube **solo la carpeta `wiki/`** a un repositorio **privado** de GitHub (no el proyecto entero: lleva
   código, configuración y datos del servidor). Por ejemplo `bandolerosrp-wiki`.
2. En GitBook crea dos espacios: «BandolerosRP — Jugadores» y «BandolerosRP — Staff».
3. En cada espacio: **Configure → GitHub Sync** → elige el repositorio, rama `main` y como
   *project directory* `jugadores` o `staff`.
4. Espacio de jugadores: publícalo (Share → Publish to the web). Espacio de staff: déjalo privado e invita al
   equipo, o publícalo con enlace no listado si tu plan de GitBook no permite invitados.

Al cambiar un `.md` aquí y hacer `push`, GitBook se actualiza solo (y al revés: lo que se edite en GitBook vuelve
al repositorio como commit).

## Mantenerla al día

- La fuente técnica sigue siendo `docs/` del proyecto. Esta wiki es la versión para personas: qué hace cada
  cosa y cómo se usa, sin código.
- Cuando cambie un sistema (tecla, comando, precio, permiso) hay que actualizar su página aquí también.
- Los textos van en español de España y con tono de rol serio (REGLA 10).
- Avisos de GitBook: `{% hint style="info|warning|danger|success" %} … {% endhint %}`.
