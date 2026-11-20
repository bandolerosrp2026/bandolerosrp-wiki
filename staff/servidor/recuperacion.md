# Recuperar problemas de jugadores

## «Mi coche ha desaparecido»

1. `/inspeccionarvehiculo MATRÍCULA`.
2. Si sale **No localizado**: el dueño lo recupera en cualquier depósito por 150 $. O, si no fue culpa suya
   (fallo del servidor), inspección → **Guardar en el garaje** elegido, con motivo.

## Coche duplicado o atascado

Inspección → **Retirar entidad** (motivo obligatorio). El sistema ya borra solo las copias duplicadas que detecta.

## Estado incoherente (figura guardado pero está en la calle)

Inspección → **Guardar en el garaje** + **Retirar la entidad**.

## Vehículo con retención que no se puede sacar

Inspección → **Levantar retención** (si procede: las policiales las debería levantar la policía en rol).

## Cobro de garaje que no se resolvió

Si se cayó el servidor a mitad de un cobro, el sistema confirma o devuelve solo al arrancar. Los que quedan sin
resolver hay que revisarlos a mano (avisar al propietario): no se crea ni se quita dinero a ciegas.

## Tatuajes perdidos o cobrados sin aplicar

`/gestiontatuajes` → **Diagnóstico** (operaciones sin resolver) y **Jugadores** (añadir el tatuaje con motivo).

## Ropa o pelo mal

1. Que el jugador haga `/reloadskin`.
2. Si no basta: `/reloadskin id`.
3. Si sigue mal: `/skin id` y arreglarlo a mano.

## Llaves

- Le falta la llave de su propio coche: `/crearllaves id` junto al coche.
- Alguien tiene una llave que no debería: inspección del vehículo → llaves → retirar. Copias de sesión:
  `/quitarllaves id`.

## Dinero perdido por un fallo

Comprobar primero el **registro** del sistema (banco, garaje, taller, gasolinera) y los movimientos de su cuenta.
Solo un **Administrador** puede devolver dinero (ficha → Dinero), siempre con el motivo en el reporte.

## Jugador atascado (bajo el mapa, en un interior…)

Ficha → **Traer** o ir con él y **Devolver**. Si está muerto y no reaparece: **Revivir**.
