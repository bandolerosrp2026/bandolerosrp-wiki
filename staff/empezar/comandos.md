# Todos los comandos de staff

Casi todo se hace desde el panel (INSERT). Estos son los comandos que existen además. Los de los jugadores están
en la wiki de jugadores.

## Panel y equipo

| Comando | Rango | Qué hace |
|---|---|---|
| `/menustaff` · `/admin` | Soporte | Abrir el panel |
| `/staff texto` · `/st` | Soporte | Chat del staff |
| `/mp id texto` | Soporte | Mensaje privado a un jugador |
| `/silenciarchat id minutos` | Soporte | Silenciar el chat de un jugador (se mantiene si reconecta) |
| `/desilenciarchat id` | Soporte | Quitar el silencio |
| `/aviso texto` | Administrador | Aviso a todo el servidor |
| `/limpiartodo` | Administrador | Borrar el chat de todos |

## Personajes

| Comando | Rango | Qué hace |
|---|---|---|
| `/full [id]` | Administrador | Revivir y llenar vida, chaleco, hambre y sed (sin id: a ti) |
| `/skin [id]` | Administrador | Editor completo de apariencia, gratis (sin id: a ti) |
| `/reloadskin [id]` | Administrador (con id) | Recargar la apariencia guardada de otro jugador |
| `/logout` | Administrador | Volver a la selección de personaje (uno mismo) |
| `/deletechar` | Administrador | Borrar el personaje de otro jugador |

## Vehículos y garajes

| Comando | Rango | Qué hace |
|---|---|---|
| `/creargaraje` | Administrador | Editor de garaje nuevo |
| `/gestiongarajes` | Administrador | Panel de garajes |
| `/inspeccionarvehiculo [matrícula]` | Administrador | Inspección del vehículo cercano o por matrícula |
| `/depositar [motivo]` | Administrador | Mandar al depósito administrativo el vehículo más cercano |
| `/admincar [id]` | Administrador | El vehículo en el que vas pasa a ser tuyo o del jugador indicado |
| `/crearllaves [id]` | Administrador | Llaves del vehículo cercano para alguien (o para ti) |
| `/quitarllaves id` | Administrador | Quitar la copia de llave del vehículo cercano |

## Sistemas

| Comando | Rango | Qué hace |
|---|---|---|
| `/bancocongelar IBAN` | Administrador | Congelar una cuenta |
| `/bancodescongelar IBAN` | Administrador | Descongelar una cuenta |
| `/bancosaldo IBAN\|trabajo\|banda` | Administrador | Ver el saldo de una cuenta |
| `/gestiongasolineras` | Administrador | Panel de gasolineras, economía y reparto |
| `/creartrabajos` · `/gestiontrabajos` | Administrador | Creador de trabajos |
| `/creartaller` · `/gestiontalleres` | Administrador | Panel de talleres |
| `/elevador` | Administrador | Colocar o retirar elevadores |
| `/mecanicoprueba …` | Administrador | Herramientas de prueba del mecánico |
| `/creartienda` · `/gestiontiendas` | Administrador | Tiendas de ropa y uniformes |
| `/creartatuajes` · `/gestiontatuajes` | Administrador | Estudios de tatuajes |
| `/probarnotis [tipo]` | Administrador | Probar las notificaciones |
| `/targettest` | Administrador | Escenario de pruebas del menú de interacción (solo en desarrollo) |

## Consola del servidor

| Comando | Qué hace |
|---|---|
| `ensure recurso` | Reiniciar un recurso |
| `refresh` | Leer recursos nuevos |
| `mercadocombustible [paso]` | Mover el mercado del combustible |
