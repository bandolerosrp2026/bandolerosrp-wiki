# Wiki de BandolerosRP V2

Wiki para **jugadores**, publicada con GitBook: https://bandolerosrp.gitbook.io/bandolerosrp-docs

| Carpeta | Qué es |
|---|---|
| `jugadores/` | El espacio de GitBook: `gitbook-docs.yaml` (sitio), `.gitbook.yaml`, `README.md` (portada) y `SUMMARY.md` (índice) |

Se sincroniza desde el repositorio privado `bandolerosrp2026/bandolerosrp-wiki` (rama `main`, project directory
`jugadores`). En `gitbook-docs.yaml` no se cambia la `key` del espacio: GitBook lo sustituiría por uno vacío.

## Mantenerla al día (REGLA 33)

- Cada script nuevo o cambio que vean los jugadores (comandos, teclas, funciones, precios) se documenta aquí y se
  publica con `node tools/publish-wiki.mjs "mensaje"` (`--dry` para ver qué subiría).
- Solo contenido para jugadores: nada de comandos de staff, probabilidades de robo ni detalles internos.
- `tools/check-project.mjs` falla si un comando de jugador de un script propio no aparece aquí.
- La fuente técnica sigue siendo `docs/` del proyecto.
- Español de España y tono de rol serio (REGLA 10). Avisos de GitBook:
  `{% hint style="info|warning|danger|success" %} … {% endhint %}`.
