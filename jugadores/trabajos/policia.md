---
description: Policía (LSPD, Sheriff y FIB): servicio, equipo, detenciones, multas, vehículos y comisarías.
---

# Policía

La policía de BandolerosRP tiene varios departamentos (LSPD, Sheriff del condado de Blaine y FIB). Todo se hace
**de servicio** (ficha en la comisaría) y lo que puede hacer cada agente depende de su **rango**.

## En la comisaría

Apunta (ojo de interacción) a cada punto de tu comisaría:

| Punto | Para qué sirve |
| --- | --- |
| **Fichar** | Entrar o salir de servicio. Funciona también fuera de servicio. |
| **Armería** | Dejar armas, munición y accesorios. Con **Coger equipo** te llevas gratis el material de tu rango. |
| **Almacén** | Almacén del departamento (en algunas comisarías, uno para cada agente). |
| **Tienda** | Material con precio y rango mínimo. |
| **Caja fuerte** | Solo dinero del departamento. |
| **Gestión** | Para el jefe: contratar, rangos, sueldos y cuenta del departamento. |

Salvo Fichar, todos piden estar **de servicio** y tener el **rango** que haya puesto el departamento. Si no puedes usar
uno, al apuntarle te sale **«¿Por qué no puedo usarlo?»** con lo que te falta.

{% hint style="info" %}
Para entrar en la policía, habla con un mando del departamento. Contratar, ascender y despedir lo hace el jefe desde
la tableta (botón **Plantilla**).
{% endhint %}

## Rangos del LSPD

De menor a mayor:

| Rango | Qué añade |
| --- | --- |
| Cadete | Tableta, avisos, búsquedas, informes propios, multas, pruebas, radar, conos y vallas |
| Oficial I · Oficial II · Oficial III · Oficial III+ | Órdenes de busca y captura, encarcelar, pinchos, unidad canina y cámaras de seguridad |
| Detective I · Detective II · Detective III | Lo mismo que un Oficial |
| Sargento I · Sargento II | Gestionar avisos y unidades, licencias, cámaras corporales de otros agentes y tablón de anuncios |
| Teniente I · Teniente II | Informes de otros, código penal, condenas, borrar pruebas y gestionar la plantilla |
| Capitán | Jefe del departamento: puede hacer todo, contratar, ascender y despedir |

## La tableta (MDT)

Se abre con la **tableta policial** del inventario, con `/mdt` o desde el menú **F6**. Tiene buscador en todas las
listas (sin importar mayúsculas ni tildes).

| Sección | Para qué sirve |
|---|---|
| **Inicio** | Resumen del servicio: avisos activos, unidades y personas o vehículos en busca y captura |
| **Avisos** | Avisos de entorno (`/entorno`), de la recepción y automáticos (disparos, robos de coches, atracos, peleas…). Aceptar, rechazar, notas y cerrar |
| **Mapa** | Mapa con avisos y unidades |
| **Unidades** | Compañeros de servicio, su estado (10-8, 10-6, 10-7…) y su indicativo |
| **Ciudadanos** | Ficha: foto, datos, licencias, notas, multas, informes, antecedentes, vehículos y armas registradas |
| **Vehículos** | Busca por matrícula (también parcial): dueño, robado, BOLO y notas |
| **Busca y captura** | Órdenes de búsqueda de personas, BOLO de vehículos y vehículos denunciados como robados |
| **Multas** | Todas las multas puestas, pendientes y pagadas |
| **Código penal** | El **código penal español completo** (unos 260 artículos con su número real: Código Penal, Ley de Tráfico, Ley de Seguridad Ciudadana y otras infracciones), cada uno con su multa en euros reales, los meses de condena (la pena mínima real, 1 mes = 1 minuto) y la pena real completa. Con buscador por artículo, código o capítulo |
| **Informes** | Informes con implicados, agentes, vehículos, pruebas y etiquetas |
| **Pruebas** y **Laboratorio** | Casos, taquillas de pruebas y análisis de las bolsas de pruebas |
| **Prisión** | Quién cumple condena ahora y el historial |
| **Agentes** | Plantilla con placa, indicativo, horas de servicio y medallas |
| **Tablón** | Anuncios internos del departamento |
| **Cámaras** | Cámaras de seguridad y cámaras corporales de los compañeros |

## Menú F6 (trabajo de calle)

Con **F6** de servicio se abre el menú policial, con buscador y por categorías. Muchas acciones también salen
apuntando con **Alt** (ox_target) a la persona o al vehículo.

- **Persona:** esposar o poner bridas, quitar, escoltar, cachear, decomisar, identificar (y dar o retirar
  licencias, según rango), multar con el código penal, encarcelar y pruebas rápidas: residuos de disparo,
  alcoholemia y drogas. El **etilómetro** va directo desde el F6 (no hace falta llevar ningún objeto): da los g/l
  de alcohol en sangre y si pasa del límite para conducir (0,5 g/l). El alcohol baja solo con el tiempo.
- **Vehículo:** información y dueño, comprobar matrícula, meter y sacar detenidos, forzar la cerradura, registrar
  maletero y guantera, cepo (se ve puesto en la rueda y el vehículo no puede arrancar hasta que se quite) y llevar
  al depósito. En los coches de la policía, **Pegatinas y extras**.
- **Objetos:** conos, vallas y bandas de pinchos.
- **Unidad:** perro K9, un **malinois** (seguir, sentado, quieto, subir al coche, buscar en personas o vehículos y
  atacar). Marca cualquier droga de la ciudad (también semillas, plantas y ladrillos) y las armas. Para que ataque o
  busque, apunta con el ojo a la persona o al vehículo («K9: atacar», «K9: buscar…»). Además: radar del vehículo,
  cámara del helicóptero y **luces y sirenas**.
- **Herramientas:** tableta, botón de pánico, cámara corporal, megáfono y facturas.

## Vehículos de servicio

Los vehículos de la policía se sacan **de servicio** en los garajes del LSPD. No son tuyos: al terminar se guardan
y no se pueden vender. Cuantos más rangos, más vehículos:

| Rango mínimo | Vehículos | Dónde |
|---|---|---|
| Cadete | Buffalo, Fugitive, Sentinel, Scout y Minimus (traslado de detenidos) | Garaje de Mission Row |
| Oficial I | Alamo, Canis y Bison (pick-up) | Garaje de Mission Row |
| Oficial I | Lancha Predator | Embarcadero LSPD de Puerto del Sol |
| Oficial II | Motos BF400 (campo) y Shinobi | Garaje de Mission Row |
| Oficial III | Helicóptero Conada | Helipuerto de la azotea de Mission Row |
| Oficial III+ | Interceptores Coquette D5 y Vigero ZX | Garaje de Mission Row |
| Detective I | Komoda (camuflado) | Garaje de Mission Row |
| Sargento I | Yosemite 2500 (supervisor) | Garaje de Mission Row |

**Pegatinas y extras:** desde el F6 (**Vehículo → Pegatinas y extras**) o apuntando con **Alt** al coche. Puedes
cambiar el diseño (pegatina), poner o quitar los **extras** (barras, rejillas, equipo…) y las **piezas de la unidad**
(indicativo del techo, supervisor…). Lo ven todos.

**Luces y sirenas:** funcionan en todos los vehículos de emergencia, también en los que no traen sonido de sirena,
y todos oyen lo mismo. Conduciendo de servicio:

| Tecla | Qué hace |
|---|---|
| **Q** | Encender o apagar las luces (al apagarlas se apaga también la sirena) |
| **Z** | Sirena sí/no (enciende las luces si estaban apagadas) |
| **R** | Cambiar el tono: Wail, Yelp, Priority y Hi-Lo |
| **E** (mantener) | Bocina de emergencia |

También desde el F6 (**Unidad → Luces y sirenas**). Las cuatro teclas se cambian en Ajustes → Asignación de teclas →
FiveM.

## Teclas y comandos de policía

| Tecla / comando | Qué hace |
|---|---|
| **F6** | Menú policial (de servicio) |
| `/mdt` | Abrir la tableta |
| **F7** | Radar del vehículo (en un vehículo de emergencia) o cámara del helicóptero (en el helicóptero) |
| **F9** | Bloquear la lectura del radar |
| **H** (corriendo) | Placaje |
| **← / →** | Avisos anteriores y siguientes en el aviso de pantalla |
| **↑** | Aceptar el aviso que se ve |
| **↓** | Ampliar el aviso |
| `/k9` | Sacar o guardar el perro |

En la cámara del helicóptero: **rueda** zoom, **clic derecho** cambia la visión (normal, nocturna, térmica),
**clic izquierdo** o **Espacio** fija un vehículo y lee su matrícula, **G** enciende el foco y **Retroceso** sale.

El **botón de pánico** y la **radio** no tienen tecla por defecto: puedes ponérsela en Ajustes → Teclas → FiveM.

## Radio

La **radio** del inventario abre el walkie. Las frecuencias 1 a 7 son de la policía (centrales y tácticas de cada
departamento y canales conjuntos, el 7 también con emergencias); el resto son públicas.

## Multas y prisión

- Las multas llegan al ciudadano a **`/facturas`** y se pagan con su cuenta; el dinero va al departamento.
- **1 mes de condena = 1 minuto conectado** dentro de la prisión de Bolingbroke. Solo cuenta estando conectado.
- Al entrar en prisión se retiran los objetos ilegales; los legales se devuelven al salir.
- En prisión hay trabajos que rebajan la condena y comedor. Escaparse avisa a la policía.

## Para cualquier ciudadano

| Comando / tecla | Qué hace |
|---|---|
| `/entorno qué ocurre` | Aviso de entorno: anónimo, la policía ve una zona aproximada y no el punto exacto (p. ej. `/entorno se oyen gritos en un callejón`) |
| `/condena` | Ver cuánto te queda de condena |
| `/soltarse` o **J** | Intentar soltarte estando esposado o con bridas (minijuego; puede fallar) |

En la **recepción** de la comisaría puedes poner una denuncia o pedir que venga un agente.

{% hint style="warning" %}
El **kit de limpieza** borra las pruebas de tu alrededor (casquillos, sangre, huellas). La policía puede encontrar
pruebas con la linterna y analizarlas en el laboratorio.
{% endhint %}
