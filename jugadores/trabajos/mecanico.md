---
description: Mecánico: reparar pieza a pieza con elevador y herramientas, piezas, mejoras y facturas.
---

# Mecánico

El trabajo de mecánico es **físico**: las reparaciones se hacen pieza a pieza en el coche, con elevador,
herramientas y repuestos reales del almacén.

## Lo que necesitas

- Ser mecánico y estar **de servicio** en un taller.
- La **tableta de mecánico** (objeto o `/tabletmecanico`).
- Piezas y herramientas en el almacén del taller. Las herramientas se desgastan con el uso.

## La tableta

Desde la tableta llevas todo el taller:

- **Órdenes de trabajo**: abrir una orden para el coche de un cliente, revisarlo, diagnosticarlo y hacer el
  **presupuesto** línea a línea.
- **Diagnosis**: estado de cada pieza y códigos de avería (OBD).
- **Tareas**: lo que hay que hacer en cada vehículo.
- **Pedidos**: comprar piezas, herramientas y motores con la cuenta del taller (según rango).
- **Gestión** del trabajo (jefes).

## Flujo de una reparación

1. **Orden** → revisión → diagnosis → **presupuesto**.
2. El cliente **acepta o rechaza cada línea** en su `/taller`. En coches de clientes solo puedes trabajar en lo que
   esté **aprobado**.
3. **Empezar trabajos**: cada línea aprobada se convierte en un trabajo físico.
4. Haz cada paso en el coche: aparecen en el menú de interacción (**Alt**) sobre la parte exacta (cada rueda, vano
   motor, bajos, puerta…). Si el elevador tapa el punto, usa **E** estando justo en el sitio.
5. La **tarjeta de trabajo** (a la derecha de la pantalla) te dice en qué paso estás, la altura que necesita el
   elevador, las herramientas y materiales que llevas y lo siguiente que tienes que hacer.
6. Cuando todo está hecho: verificación, cobro y entrega.

**X** cancela el paso en curso.

## Elevadores

- Se manejan con **Alt** en la unidad de potencia del elevador. Tres alturas: **baja**, **cintura** y **alta**.
- Bajos del coche → elevador en **alta**. Ruedas → **baja** o **cintura** (en alta no llegas).
- Dentro de un taller solo los usan los mecánicos de servicio de ese taller, y **no baja si hay alguien debajo**.
- `/sonidos` ajusta el volumen de los elevadores.

## Lo que puede hacer un taller

- **Mantenimiento**: aceite, filtros, bujías, refrigerante, frenos, suspensión, neumáticos (cada uno por
  separado), embrague, batería…
- **Averías** y **cambio de motor** (con grúa, en 6 fases).
- **Tuneo**: rendimiento, estética, pintura y vinilos (cabina de pintura: **Alt** sobre el punto de pintura del taller).
- **ECU**: Stages 0-3, mapas ECO / DAILY / SPORT, cambio Comfort / Sport / Race, banco de potencia y pruebas.
- **Nitro**.
- **Vaciar el depósito** cuando alguien echa el combustible equivocado.
- **Almacén**: ver stock, comprar piezas/motores, **jefe: Vaciar almacén** (desde /jefe → Almacén, borra todo).

## Rangos y experiencia

Tu **rango** decide qué puedes hacer (por ejemplo, el tuneo, los motores, escribir la centralita o hacer
devoluciones exigen rangos más altos). La **experiencia** que ganas trabajando no da permisos, pero desbloquea
trabajos difíciles como el cambio de motor.

De menor a mayor:

| Rango | Qué añade |
| --- | --- |
| Novato | Diagnosticar, mantenimiento, reparar y montar piezas, presupuestos, entregar el vehículo, leer la centralita, facturas y almacén del taller |
| Aprendiz | Presupuestos de tuneo |
| Mecánico | Cambios de motor, escribir mapas y Stage, desmontar e instalar centralitas y pedir piezas con el dinero del taller |
| Encargado | Recuperar centralitas bloqueadas y ver las finanzas del taller |
| Jefe | Jefe del taller: devoluciones, contratar, ascender, despedir y cuenta de empresa |
