# Garajes y depósitos

Todo con rango **Administrador**.

## Comandos

| Comando | Qué hace |
|---|---|
| `/creargaraje` | Editor con un garaje nuevo |
| `/gestiongarajes` | Panel: buscar, filtrar, crear, editar, duplicar, ir, activar/desactivar, eliminar, inspeccionar |
| `/inspeccionarvehiculo [matrícula]` | Inspección del vehículo cercano o por matrícula |
| `/depositar [motivo]` | Manda al depósito administrativo el vehículo más cercano (si no es de nadie, lo retira) |
| `/admincar [id]` | El vehículo en el que vas pasa a ser tuyo o del jugador indicado (pide confirmación si ya era de otro) |

## Crear o editar un garaje

Pestañas del editor:

| Pestaña | Qué se configura |
|---|---|
| General | Nombre, identificador, tipo (público, privado, empresa, banda, depósito), tipos de vehículo, activo |
| Acceso | Trabajos o bandas con rango mínimo, «de servicio», compartido; dueños y autorizados de los privados |
| Puntos | Punto de acceso (NPC), punto de guardado y puntos de salida |
| Capacidad y tarifas | Plazas, tarifa por sacar, traslados, tarifas del depósito |
| Mapa | Blip |
| Flota | Vehículos de servicio (empresa/banda): modelo, nombre y rango mínimo |

### Colocar los puntos en el mundo

- **Punto de acceso**: NPC fantasma delante de ti. **Q / R** giran, **↑ / ↓** cambian el radio, **E** confirma.
- **Punto de guardado**: círculo en tu posición (o la del vehículo si vas dentro). **↑ / ↓** radio.
- **Puntos de salida**: vehículo fantasma delante. El círculo se vuelve coral si el sitio está ocupado. **E**
  añade (puedes poner varios seguidos), **Retroceso** termina.
- **Ver en el mundo**: marca todos los puntos del garaje. **Mover todo el garaje**: desplaza todos los puntos a la vez.

Al guardar, el garaje aparece **para todos sin reiniciar**.

### Borrar un garaje

El panel enseña cuántos vehículos tiene (guardados, depositados, fuera). Eliges a qué garaje moverlos y escribes
el identificador para confirmar. **Si algún vehículo no se puede mover, no se borra nada.** Nunca se borra un
vehículo.

## Depósito

| Tipo | Tarifa | Quién libera las retenciones |
|---|---|---|
| Municipal | 500 $ | — |
| Policial | 1.500 $ (va a la cuenta de la policía) | Policía de servicio |
| Administrativo | 0 $ | Staff |

Por tipo de vehículo la tarifa mínima sube (motos 250, camiones 1.200, helicópteros 4.000, aviones 6.000,
barcos 2.000). Policía y EMS de servicio no pagan. Los «no localizados» se recuperan por 150 $.

Ningún jugador puede mandar un vehículo al depósito desde su juego: solo `/depositar`, la inspección o los
sistemas de servidor (policía).

## La inspección de vehículos

`/inspeccionarvehiculo` enseña el estado real del vehículo (base de datos y mundo), su dueño, las llaves
compartidas, el expediente del depósito y el registro. Desde ahí, **siempre con motivo**:

- Guardarlo en un garaje.
- Retirar la entidad del mundo.
- Trasladarlo.
- Levantar una retención.
- Revisar o retirar llaves compartidas.

Ver también [Recuperar problemas de jugadores](../servidor/recuperacion.md).
