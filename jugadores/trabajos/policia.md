# Policía

La policía de BandolerosRP tiene varios departamentos (LSPD, Sheriff del condado de Blaine y FIB). Todo se hace
**de servicio** (ficha en la comisaría) y lo que puede hacer cada agente depende de su **rango**.

{% hint style="info" %}
Para entrar en la policía, habla con un mando del departamento. Contratar, ascender y despedir lo hace el jefe desde
la tableta (botón **Plantilla**).
{% endhint %}

## La tableta (MDT)

Se abre con la **tableta policial** del inventario, con `/mdt` o desde el menú **F6**. Tiene buscador en todas las
listas (sin importar mayúsculas ni tildes).

| Sección | Para qué sirve |
|---|---|
| **Inicio** | Resumen del servicio: avisos activos, unidades y personas o vehículos en busca y captura |
| **Avisos** | Avisos del 112 y automáticos (disparos, robos de coches, atracos, peleas…). Aceptar, rechazar, notas y cerrar |
| **Mapa** | Mapa con avisos y unidades |
| **Unidades** | Compañeros de servicio, su estado (10-8, 10-6, 10-7…) y su indicativo |
| **Ciudadanos** | Ficha: foto, datos, licencias, notas, multas, informes, antecedentes, vehículos y armas registradas |
| **Vehículos** | Busca por matrícula (también parcial): dueño, robado, BOLO y notas |
| **Busca y captura** | Órdenes de búsqueda de personas, BOLO de vehículos y vehículos denunciados como robados |
| **Multas** | Todas las multas puestas, pendientes y pagadas |
| **Código penal** | Artículos con su multa y meses de condena |
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
  alcoholemia y drogas.
- **Vehículo:** información y dueño, comprobar matrícula, meter y sacar detenidos, forzar la cerradura, registrar
  maletero y guantera, cepo y llevar al depósito.
- **Objetos:** conos, vallas y bandas de pinchos.
- **Unidad:** perro K9 (seguir, sentado, quieto, subir al coche, buscar en personas o vehículos, atacar), radar del
  vehículo y cámara del helicóptero.
- **Herramientas:** tableta, botón de pánico, cámara corporal, megáfono y facturas.

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
| `/112 motivo` | Llamar a emergencias con tu ubicación |
| `/entorno qué ocurre` | Aviso de entorno: anónimo, la policía ve una zona aproximada y no el punto exacto (p. ej. `/entorno se oyen gritos en un callejón`) |
| `/condena` | Ver cuánto te queda de condena |
| `/soltarse` o **J** | Intentar soltarte estando esposado o con bridas (minijuego; puede fallar) |

En la **recepción** de la comisaría puedes poner una denuncia o pedir que venga un agente.

{% hint style="warning" %}
El **kit de limpieza** borra las pruebas de tu alrededor (casquillos, sangre, huellas). La policía puede encontrar
pruebas con la linterna y analizarlas en el laboratorio.
{% endhint %}
