---
description: EMS: atender heridos, reanimar, camilla y ambulancia, hospital y material médico.
---

# EMS (servicio médico)

Los médicos atienden a los heridos en la calle y en el hospital, los reaniman, los llevan en camilla y en ambulancia
y les recetan silla de ruedas o muletas. Todo lo que hacen queda en el **historial médico** del paciente.

Para trabajar de médico hay que **entrar de servicio** (punto de fichar del hospital). Fuera de servicio no recibes
avisos ni puedes diagnosticar.

## Rangos del EMS

De menor a mayor:

| Rango | Qué añade |
| --- | --- |
| Enfermero | Material básico del almacén: vendas, gasas, torniquete, analgésicos, férulas, collarín, botiquín, camilla, silla de ruedas y muletas |
| Médico | Material avanzado: sutura, pinzas, suero, sangre, morfina, adrenalina, sedante y desfibrilador |
| Jefe de zona | Lo mismo que un Médico |
| Cirujano | Lo mismo que un Médico |
| Cirujano jefe | Jefe del EMS: gestión del trabajo, contratar, ascender, despedir y cuenta de empresa |

## Menú y tableta

- **F6** (`/menutrabajo`): menú del EMS con la tableta, diagnosticar al más cercano, pedir refuerzos, tus heridas,
  facturas y, si eres jefe, la gestión del trabajo.
- **`/tabletaems`** (puedes asignarle una tecla): tableta del EMS. Pestañas:
  - **Avisos**: los `/auxilio` y los heridos que piden ayuda, en directo. **Atender** te marca la ruta y avisa al
    paciente de que vas; **Cerrar** lo quita.
  - **Pacientes**: buscar a cualquier ciudadano (aunque nunca haya pasado por el EMS) y abrir su expediente:
    - **Historial**: todo lo que le ha hecho el EMS, con notas.
    - **Ficha clínica**: grupo sanguíneo, alergias, enfermedades, medicación habitual, contacto de emergencia y
      observaciones.
    - **Pruebas** y **Citas** de ese paciente.
  - **Citas**: hoy, próximas, pasadas o todas. **Nueva cita** con paciente, fecha y hora, motivo, lugar y médico; si
    el paciente está conectado le llega el aviso. Márcalas como **Atendida**, **No vino** o **Cancelada**.
  - **Pruebas**: todas las analíticas, toxicologías y radiografías con sus resultados (lo que sale de lo normal, en
    rojo). También puedes **apuntar una prueba a mano**.
  - **Asegurados**, **De servicio** y **Tarifas**.
- Todas las listas tienen buscador.

## Con el ojo (Alt) sobre una persona

| Opción | Cuándo |
|---|---|
| **Diagnosticar y curar** | Siempre: abre su diagnóstico con las heridas y las curas |
| **Reanimar (desfibrilador)** | Está en el suelo |
| **Hacer RCP** | Está en el suelo (sin material; no siempre funciona) |
| **Estabilizar (botiquín)** | Está en el suelo |
| **Hacer pruebas médicas** | Analítica de sangre, toxicología o radiografía con su estado real |
| **Comprobar el pulso** | Cualquiera, si está en el suelo |

**Pruebas médicas**: la **analítica** mide la hemoglobina, el lactato, la glucosa y el alcohol según la sangre que
haya perdido y lo que sangra; la primera le pone el **grupo sanguíneo** en la ficha. La **toxicología** detecta el
alcohol y las drogas que lleve encima, y la **radiografía**, las fracturas y las balas que sigan dentro. Los
resultados se guardan en la tableta (**Pruebas**) y en su historial.

## Diagnóstico

Apunta con **Alt** a una persona → **Diagnosticar y curar**. Ves:

- El cuerpo por zonas con la gravedad de cada herida y lo que sangra.
- **Constantes**: pulso, tensión, saturación, sangrado, dolor, consciencia y sangre.
- Cada herida con los objetos que llevas que sirven para ella. Pulsas y se hace la cura (con animación).
- **Medicación y transfusión**: morfina, adrenalina, suero, bolsa de sangre, botiquín, sedante, analgésicos.
- **Reanimación**: desfibrilador (inconscientes y heridos graves), **RCP** (sin material, no siempre funciona) y
  **Estabilizar** con un botiquín (heridos graves).
- **Facturar** (con el descuento del seguro ya calculado) y **Receta de movilidad** (muletas o silla de ruedas
  durante unos minutos; **Alta** para quitarla).

### Orden de las curas

| Herida | Qué hacer |
|---|---|
| Bala | **Pinzas** para sacarla (sangra un poco más) → **gasa** → **kit de sutura** |
| Corte | **Venda** o **gasa**; **torniquete** si es en brazo o pierna y sangra mucho; **sutura** para cerrarla |
| Fractura | **Férula** (brazos y piernas) o **collarín** (cabeza y torso) |
| Contusión | **Bolsa de hielo** (y collarín si es en la cabeza) |
| Quemadura | **Crema para quemaduras** |
| Poca sangre | **Suero salino** o **bolsa de sangre** |

{% hint style="info" %}
Para reanimar con desfibrilador, el paciente **no puede sangrar mucho**: primero corta el sangrado. Al reanimar con
desfibrilador cobras una prima de la cuenta del EMS.
{% endhint %}

Al usar el desfibrilador verás el **LIFEPAK 15** en el suelo junto al paciente, y al hacer RCP, el **LUCAS**.

## Vehículos del EMS

Se sacan en el garaje del EMS (de servicio), según tu rango:

| Vehículo | Desde |
|---|---|
| Ambulancia | Enfermero |
| Toyota Tacoma (pick-up de apoyo) | Enfermero |
| Ford Explorer (intervención rápida) | Médico |
| Chevrolet Silverado (rescate) | Médico |
| Ford Expedition (supervisor) | Jefe de zona |
| Chevrolet Tahoe (jefatura) | Cirujano |

Todos llevan luces y sirena, y de todos se puede **sacar la camilla**.

## Camilla, silla de ruedas y muletas

- **Camilla**: sácala de la ambulancia (apunta al vehículo → **Sacar la camilla**) o úsala desde el inventario.
  Apuntando a la camilla: **Empujar**, **Subir al paciente**, **Bajarlo**, **Meter en la ambulancia** y **Guardar**.
  **X** suelta la camilla.
- **Silla de ruedas** y **muletas**: se usan desde el inventario o las pone la receta.

## Hospital

- **Camas**: apunta a una cama para **tumbar al paciente**, diagnosticarlo o **darle el alta**.
- **Almacén del EMS** (punto del hospital): material médico según tu rango.
- **Ordenador**: abre la tableta.
- Si hay médicos de servicio, la **recepción** no atiende sola: avisa al EMS y te toca ir.
