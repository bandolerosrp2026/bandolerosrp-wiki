# Tiendas de ropa y uniformes

Todo con rango **Administrador**.

## Comandos

| Comando | Qué hace |
|---|---|
| `/creartienda` | Panel directamente en «Nueva tienda» |
| `/gestiontiendas` | Tiendas (buscar, filtrar, editar, duplicar, ir, activar, eliminar) y **Uniformes** |
| `/skin [id]` | Editor completo de apariencia (modelo, genética, rasgos, ropa), gratis. Avisa a los dos y queda registrado |
| `/reloadskin [id]` | Recarga la apariencia guardada de otro jugador |

## Crear una tienda

1. `/creartienda` → nombre y tipo: ropa, premium, accesorios, vestuario privado o vestuario de trabajo.
2. Interacción: NPC (elige el modelo), marcador o zona, y su radio.
3. **Establecer ubicación**: aparece el NPC fantasma. Colócate, **Q / R** giran, **E** confirma, **Retroceso**
   cancela.
4. **Probador** (opcional): donde se coloca al jugador al abrir la tienda. Mismo sistema.
5. Blip, acceso por trabajo y rango mínimo, precios por categoría, multiplicador, descuento y prendas concretas
   (precio propio, gratis, premium ×2 u oculta).
6. **Guardar**: aparece para todos al momento.

## Precios

`precio = (precio de la prenda, o de la categoría en la tienda, o precio base) × multiplicador (× premium) ×
(100 − descuento) %`. Se calcula siempre en el servidor.

## Uniformes

1. Vístete con el uniforme.
2. `/gestiontiendas` → **Uniformes** → nuevo: se guarda la ropa que llevas.
3. Asócialo a un trabajo y rango mínimo.
4. Solo aparece en tiendas de tipo **Vestuario de trabajo**, para ese trabajo y rango.

## Normas

- Las tiendas de ropa son las de este sistema. Las barberías y el cirujano son del sistema de apariencia y no se
  gestionan aquí.
- Hay prendas de los packs de ropa que se ven invisibles: están **bloqueadas** y no salen en las tiendas.
