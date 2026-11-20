# Trabajos

Creador: `/creartrabajos` (también `/gestiontrabajos`). Rango **Administrador**.

Todo se crea, edita y borra **en el juego, sin reiniciar**.

## Lista de trabajos

Con buscador. Marcas:

- **Propio**: creado desde el creador.
- **Editado**: un trabajo de serie modificado. Se guarda el original y se puede **Restaurar**.
- **jobs.lua**: de serie, sin tocar.

El trabajo «desempleado» está protegido.

## Pestañas

| Pestaña | Qué se configura |
|---|---|
| **General** | Nombre visible, identificador (no cambia), tipo (policía, emergencias, mecánico, negocio), entrar de servicio al conectarse, cobrar fuera de servicio |
| **Rangos** | Número, nombre, sueldo, **Jefe** (personal y sueldos) y **Cuenta** (acceso a la cuenta de empresa). Si borras un rango, sus empleados bajan al rango inferior |
| **Puntos** | Los 12 tipos de punto (abajo), con acceso por rango, «solo de servicio», radio, marcador, blip, NPC y objeto |
| **Acciones** | Qué puede hacer el trabajo sobre otras personas y desde qué rango |
| **Personal** | Añadir por ID o citizenid, cambiar rango, quitar |
| **Integraciones** | Cuenta de empresa, garajes con flota, vestuarios y uniformes, taller |
| **Registro** | 60 días de historial |
| **Exportar / Importar** | Copiar un trabajo entero (rangos, acciones y puntos) como texto |

## Tipos de punto

Fichar · Gestión (jefe) · Almacén · Armería (solo armas, munición y accesorios) · Caja fuerte (solo dinero) ·
Tienda (rango mínimo por artículo) · Mesa de fabricación · Recolección · Procesado · Compraventa ·
Teletransporte (ida y vuelta, con vehículo opcional) · Decorado.

**Puntos públicos**: los mismos tipos sin trabajo (salvo Fichar y Gestión), para cualquiera.

### Colocar un punto

Fantasma en el mundo: **E** guarda, **Q / R** giran, **↑ / ↓** radio, **Retroceso** cancela. Luego se puede ir,
activar/desactivar, duplicar, editar o borrar.

## Acciones disponibles

Esposar, escoltar, cachear, meter/sacar del vehículo, facturar/multar, ver identidad, licencias (ver, dar y
retirar), dueño del vehículo, mandar al depósito (policial), curar, reanimar y colocar objetos. Siempre **de
servicio**.

## Qué no hace el creador

- Garajes → `/creargaraje` (el creador los lista y abre el editor).
- Vestuarios y uniformes → `/creartienda` / `/gestiontiendas`.
- El taller → `/gestiontalleres` (aquí solo rangos, sueldos y acciones del trabajo mecánico).

## Facturas

Las facturas se cobran de la cuenta corriente del jugador a la cuenta de empresa. Nunca se cobran dos veces. Si
el servidor se cae a mitad de un pago, al arrancar vuelven a «pendiente».
