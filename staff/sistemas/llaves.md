# Llaves y robo de vehículos

## Comandos

| Comando | Rango | Qué hace |
|---|---|---|
| `/crearllaves [id]` | Administrador | Llaves del vehículo cercano para alguien (o para ti) |
| `/quitarllaves id` | Administrador | Quita la copia de llave del vehículo cercano |

Las llaves guardadas (permanentes y temporales) se revisan y retiran desde la **inspección de vehículos**
(`/inspeccionarvehiculo`).

## Tipos de llave

| Tipo | Origen | Dura |
|---|---|---|
| Dueño | Dueño del vehículo (o flota) | Siempre |
| Permanente | La da el dueño desde el llavero | Hasta que la retire o cambie el dueño |
| Temporal | Igual, de 15 min a 24 h | Hasta su hora (sobrevive a reinicios) |
| Trabajo | Por modelo o clase de vehículo del trabajo | Mientras tenga el trabajo |
| Sesión (copia) | Robo, puente, NPC, `/darllaves`, alquileres… | Mientras exista el vehículo |

Máximo 6 personas con llave compartida por vehículo. Al cambiar de dueño se borran todas las llaves compartidas.

## Cómo funcionan los robos (confidencial)

{% hint style="danger" %}
No compartas estas cifras con los jugadores.
{% endhint %}

| Mecánica | Detalle |
|---|---|
| **Ganzúa** (forzar / puentear) | Minijuego según la clase. Se rompe un 40 % (normal) o un 20 % (avanzada). Salta la alarma el 80 % de las veces |
| **Buscar llaves** (H) | 20-40 s, 50 % de éxito (configurable por vehículo) |
| **Coches de la ciudad** | 75 % cerrados. Con el motor en marcha, se quedan las llaves. Conductor muerto: 2,5 s para cogerlas |
| **A punta de pistola** | Menos de 5 m, arma de fuego, 7,5 s. Éxito: pistola 50 %, subfusil 75 %, fusil o escopeta 90 % |
| **No robables** | Militares y trenes |

**Avisos a la policía** (forzar, puentear, buscar, robo): 75 % de día, 50 % de noche (01:00-06:00), con 10 s de
espera por jugador. Llegan a los agentes de servicio como aviso de policía con un punto temporal en el mapa. El
dueño, si está conectado, también recibe aviso.

Cada robo lo **valida el servidor**: el objeto, la distancia, el vehículo y el tiempo mínimo. Si alguien termina
un robo «demasiado rápido», el servidor lo rechaza.

## Registro

Se guardan 60 días: compartir, retirar, robos, búsquedas, copias y cambios de dueño. Se ve en la inspección del
vehículo.
