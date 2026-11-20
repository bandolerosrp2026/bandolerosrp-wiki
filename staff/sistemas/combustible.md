# Combustible y gasolineras

Panel: `/gestiongasolineras` (Administrador).

## Gasolineras

Lista con buscador y filtros. Por cada gasolinera:

- Crear, editar y borrar; **centro y radio**.
- **Oficina** (donde se compra y gestiona) y **punto de descarga** del reparto.
- **Surtidores** y **cargadores eléctricos** colocados en el mundo.
- Tipos que vende, **precio fijo** opcional, capacidad y existencias.
- Si está **a la venta** y su precio.
- **Dueño**: asignar por ID o quitarlo.

Para colocar puntos se usa la tecla **E** (no hay nada que apuntar).

{% hint style="warning" %}
Las 27 gasolineras iniciales **no tienen colocados** la oficina ni el punto de descarga: la oficina funciona desde
el surtidor y la descarga en el centro. Colócalos con el panel.
{% endhint %}

## Economía

- **Precios base** por tipo de combustible.
- **Mercado**: se mueve cada 30 min (entre ×0,85 y ×1,25). Botones *mover ahora* y *reiniciar*. Desde la consola:
  `mercadocombustible [paso]`.
- **Consumo** global y por clase de vehículo.
- **Ajustes por modelo** (tipo de combustible, consumo, depósito) con buscador.

Aeronaves y barcos tienen consumo 0 hasta que se creen gasolineras de aeródromo o puerto (con queroseno) y se les
suba el consumo aquí.

## Reparto

- Posición del **depósito de reparto** (por defecto en los muelles de Elysian Island).
- **Pedidos abiertos** (se pueden cancelar).
- Fianza del camión 2.500 $. Si nadie recoge un pedido (45 min los de dueños, 90 min los públicos) lo entrega la
  empresa con un 8 % de recargo al dueño.

## Negocio (gasolineras de jugadores)

- Máx. 2 por persona.
- El dueño pone precios entre el 80 % y el 160 % del mercado y compra al 62 % (mayorista).
- Al vender recupera el 60 % del precio más la caja.

## Combustible equivocado

Lo arregla un **mecánico de servicio** con «Vaciar depósito». La mezcla se guarda por matrícula (sigue al
guardar y sacar del garaje).

## Registro

`/gestiongasolineras` → **Registro**, con búsqueda.
