# Operación del servidor

Esta página es para quien tenga acceso a la consola del servidor (propietario y administradores técnicos).

## Regla de oro

{% hint style="danger" %}
**No reinicies el servidor si hay jugadores conectados.** Reinicia solo el recurso que haga falta desde la consola.
{% endhint %}

Para saber si hay alguien: `http://127.0.0.1:30130/players.json` desde la máquina del servidor (lista vacía =
nadie).

## Comandos de consola

| Comando | Cuándo |
|---|---|
| `refresh` | Después de añadir un recurso nuevo |
| `ensure nombre_recurso` | Reiniciar un recurso (por ejemplo `ensure bandoleros_hud`) |

Al reiniciar un recurso con una interfaz abierta, esa interfaz se cierra para quien la tuviera abierta. Los
sistemas propios están preparados para reiniciarse en caliente.

| Recurso | Notas al reiniciarlo |
|---|---|
| `ox_target` | Hay que reiniciar después los recursos que registran opciones (o reiniciar sin jugadores) |
| `bandoleros_banking` | Cierra los bancos abiertos |
| `ox_inventory` | Mejor sin gente |
| `illenium-appearance` | Mejor en el próximo reinicio: recarga la apariencia de todos |

## Arrancar el servidor

- `start-dev.bat` (ventana propia) o `start-txadmin.bat` (panel txAdmin en el puerto 40130).
- Puertos: **30130** juego y **40130** txAdmin.

## Copias de seguridad

Base de datos:

```
mariadb-dump -u root bandoleros_v2 > backup.sql
```

## Recursos de terceros

Ningún recurso de fuera entra sin pasar por el análisis de seguridad del proyecto y su registro. Nada de recursos
filtrados ni ofuscados.

## Archivos que nunca se comparten

`secrets.cfg` (licencia, webhooks) y `admins.cfg` (administradores). No se suben a Git ni se pegan en Discord.
