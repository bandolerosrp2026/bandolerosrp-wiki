# Personajes

## Reglas del servidor

- **Un personaje por jugador.** Solo el propietario puede autorizar más personajes para una licencia concreta.
- **Aparición en el último sitio**: no hay selector de ubicación. Un personaje nuevo aparece en el Ayuntamiento.
- **Sin servicio médico**: al morir se reaparece en el mismo sitio a los 10 s.

## Creación de personaje

El servidor valida la identidad antes de crear el personaje:

- Nombre 2-24 letras (máx. 2 palabras), apellidos 2-32 (máx. 3 palabras), edad 18-90.
- Palabras prohibidas en el nombre (admin, staff, moderador, policía, bandoleros, qbox, fivem…).
- No puede repetirse un nombre completo.

Si en el registro aparece un aviso `bandoleros_identity:audit`, alguien ha creado un personaje **sin pasar por
la interfaz** (posible cliente modificado): revisarlo.

## Tareas habituales

| Tarea | Cómo | Rango |
|---|---|---|
| Revivir y llenar vida, chaleco, hambre y sed | `/full [id]` o ficha → Revivir | Administrador / Soporte (revivir) |
| Cambiar el nombre del personaje | Ficha → Nombre | Administrador |
| Editar la apariencia | Ficha → Apariencia o `/skin id` | Administrador |
| Recargar la apariencia de alguien | `/reloadskin id` | Administrador |
| Cambiar trabajo o banda | Ficha → Trabajo / Banda | Administrador |
| Borrar el personaje de otro jugador | `/deletechar` | Administrador |
| Volver tú a la selección de personaje | `/logout` | Administrador |

{% hint style="warning" %}
Borrar un personaje borra también sus datos asociados (apariencia, atuendos…) y no se puede deshacer.
Confírmalo antes con el jugador y con un administrador.
{% endhint %}
