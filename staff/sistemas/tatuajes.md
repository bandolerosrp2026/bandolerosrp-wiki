# Estudios de tatuajes

Todo con rango **Administrador**.

## Comandos

| Comando | Qué hace |
|---|---|
| `/creartatuajes` | Editor de un estudio nuevo |
| `/gestiontatuajes` | Estudios, catálogo, jugadores, eventos y diagnóstico |

## Configurar un estudio

Nombre, tipo, activo, ventas del NPC, multiplicador de precio, % del láser, **horario** (hora del servidor),
punto de atención, NPC (modelo y posición; **Q / R** giran), silla o punto del cliente (sentado o de pie),
**cámara de la sesión** (cámara libre: WASD, ratón y rueda), blip, catálogo (todo o una lista, zonas, solo
temporales), acceso (para privados: trabajos, bandas o personajes) y **propietario**.

| Tipo | Precio |
|---|---|
| Público | Normal |
| Premium | ×1,35, con exclusivos |
| Privado | Acceso restringido |
| Empresa | Negocio de un jugador |
| Exclusivo | ×1,6, solo exclusivos |

Hay 6 estudios de fábrica en los locales de tatuajes de GTA: sus posiciones son aproximadas, revisarlas con el
editor.

## Catálogo

- 743 diseños de GTA Online. Hay 302 diseños de torso que salen en «Torso (sin precisar)»: se pueden reasignar a su
  zona real uno a uno desde **Catálogo** (con «Probar en mí»).
- Precio editable por diseño.

## Jugadores

`/gestiontatuajes` → **Jugadores**: añadir o quitar tatuajes a un personaje (queda en el registro). Útil para
devolver un tatuaje perdido.

## Diagnóstico

- Operaciones de cobro **sin resolver** tras una caída del servidor: revisarlas aquí.
- Diseños que ya no existen en el catálogo y diseños addon cuyo overlay no existe en el juego.

## Diseños propios (addon)

Subir una imagen **no** crea un tatuaje: GTA necesita la textura en un recurso de streaming. Lo hace el
desarrollador del servidor; después se registra el diseño en **Catálogo → Registrar diseño addon** con «Verificar
en el motor».

## Negocios

Al poner un **propietario**, el estudio usa una cuenta de empresa en el banco (se crea sola). El propietario
gestiona empleados, rangos (comisión máx. 50 %, descuento máx. 30 %), catálogo, precios y finanzas desde la
tableta del estudio.
