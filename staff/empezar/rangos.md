# Rangos y permisos

Hay tres rangos, cada uno incluye todo lo del anterior:

**Administrador** ⊃ **Moderador** ⊃ **Soporte**

## Qué puede hacer cada rango

| Rango | Puede |
|---|---|
| **Soporte** | Abrir el panel, servicio, reportes, chat del staff, mensajes privados, silenciar el chat, avisar, revivir, ir hasta un jugador, ver coordenadas |
| **Moderador** | Todo lo de Soporte + traer y devolver, observar, capturas de pantalla, congelar, expulsar, ver y vaciar inventarios, noclip, invisible, nombres e ID, jugadores en el mapa, visión nocturna y térmica, revivir alrededor, ver el registro y las sanciones, subir a su coche, reparar y borrar vehículos |
| **Administrador** | Todo lo de Moderador + sancionar y quitar sanciones, matar, dinero, trabajo y banda, objetos y armas, apariencia, mundo (routing bucket), nombre del personaje, inmortal, munición infinita, cambiar de modelo, herramientas de desarrollo, generar/tunear/cambiar matrícula/regalar vehículos, limpiar el mapa, clima, hora, avisos globales, acciones globales, gestionar rangos, súper salto, correr rápido, borrar apuntando, **acciones troll** y **todos los editores de sistemas** (garajes, tiendas, trabajos, talleres, gasolineras, tatuajes, banco) |

## Reglas de jerarquía

- No puedes avisar, expulsar, sancionar, congelar, matar, silenciar ni vaciar el inventario de alguien de **tu mismo
  rango o superior**.
- No puedes dar un rango **por encima del tuyo**.
- Si el servidor tiene activado *requireDuty*, hay que estar **de servicio** para usar el panel.

## Dar o quitar rangos

**Desde el juego (Administrador):** Panel → **Equipo** → Dar rango (por ID de jugador o por licencia). Se guarda y se
aplica cada vez que esa persona entra.

**Fijo en el servidor (propietario):** una línea en `server-data/admins.cfg` (archivo privado, no se sube a Git):

```
add_principal identifier.license2:XXXXXXXXXXXXXXXX group.admin
```

## Permisos sueltos

Se puede dar un permiso concreto sin subir de rango. Ejemplo, dejar sancionar a los moderadores:

```
add_ace group.mod bandoleros.admin.ban allow
```

{% hint style="info" %}
Las acciones del panel que reutilizan comandos de otros sistemas (apariencia, silenciar, mensajes, aviso, clima,
hora, regalar coche) necesitan además el permiso de ese comando.
{% endhint %}
