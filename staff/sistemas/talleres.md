# Talleres mecánicos

Todo con rango **Administrador** (permiso de administración de talleres). Ser jefe o dueño del taller **no** da
acceso a este panel.

## Comandos

| Comando | Qué hace |
|---|---|
| `/creartaller` · `/gestiontalleres` | Panel de talleres |
| `/elevador` | Colocar, girar y retirar elevadores |
| `/mecanicoprueba pieza\|averia\|temp\|aceite\|km\|estres\|ecu\|reparar\|estado` | Herramientas de prueba sobre el coche cercano |
| `/mecanicoprueba objetivo` | Diagnóstico completo del coche cercano en la consola F8: por qué no sale una opción, qué tareas tiene, el elevador y el primer bloqueo |

## El panel `/gestiontalleres`

| Sección | Qué se configura |
|---|---|
| Talleres | Tarjetas con estado (operativo, incompleto, pendiente de configurar, desactivado), búsqueda y filtros |
| Resumen | Vista general del taller |
| Configuración | Datos generales |
| Puntos y zonas | Almacenes, facturación, boxes de reparación, almacén pesado, cabina de pintura… |
| Elevadores | Nombrar los elevadores de la zona y asociarlos a un box |
| Servicios | Tuneo, mantenimiento, motores, ECU, diagnosis, dinamómetro, pintura, reparaciones; «reparar solo dentro de un box» |
| Permisos | Rangos mínimos propios para cada acción |
| Economía | Comisión del taller (0-50 %), mano de obra ×0,5-×3, precio del tuneo ×0,5-×3 |
| Apariencia | Nombre, icono, color, título en el menú de interacción, descripción y blip |
| Registro y actividad | Historial del panel |

Los cambios de Configuración, Servicios, Permisos, Economía y Apariencia van a un **borrador**: «Guardar cambios» o
«Descartar cambios». Los puntos se guardan al momento. Borrar un taller exige escribir su identificador.

### Editor 3D de puntos

**← / →** giran, **↑ / ↓** altura (±3 m), **rueda** radio de las zonas, **Mayús** ajuste fino, **E** confirmar,
**Retroceso** cancelar. «Previsualizar» gira la cámara alrededor del punto.

Cada punto de almacén es un almacén independiente que abren todos los mecánicos del trabajo.

## Elevadores

- Únicos elevadores del servidor. Se colocan con `/elevador` en bahías libres (necesitan 3,7 m de ancho y 3,2 m de
  alto). Los elevadores que vienen dibujados en el mapa del taller no funcionan.
- Dentro de un taller solo los manejan sus mecánicos de servicio; con alguien debajo no bajan.

## Rangos por defecto del mecánico

| Acción | Rango mínimo |
|---|---|
| Servicio, presupuestos, entregas, leer ECU, facturar, almacén | 0 |
| Tuneo | 1 |
| Motores, escribir ECU, montar centralitas, pedir piezas | 2 |
| Recuperar ECU, finanzas | 3 |
| Devoluciones | 4 |

Se pueden cambiar por taller en **Permisos**.

## Cobros en revisión

Si un cobro del taller da una respuesta dudosa del banco, queda **en revisión del staff** y no se repite solo.
Revisarlo antes de devolver nada a mano.
