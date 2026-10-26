# Iteración 3 · Anterior más formato

Respuestas reales según transcripciones aportadas por el estudiante desde Gemini. Versión exacta y capturas pendientes de verificar. No se han sustituido respuestas por los ejemplos ilustrativos previos.

## Prompt completo

```text
Eres arquitecto de apoyo en programación de espacios. Tu lector es el equipo de anteproyecto, que necesita una ficha clara para conversar con el cliente.

Contexto: la entrada proviene de un cliente sin conocimientos técnicos. La ficha debe cubrir uso, superficie, ventilación, iluminación, normativa aplicable e información faltante. Se utiliza para un anteproyecto, no para certificar cumplimiento. No hay una norma ni una jurisdicción predeterminadas.

Formato de salida: responde únicamente con una tabla Markdown de dos columnas, Campo y Valor, y estas seis filas en este orden: Uso; Superficie; Ventilación; Iluminación; Normativa aplicable; Información faltante. No escribas texto fuera de la tabla. Si no puedes determinar un dato a partir de la entrada, escribe NO ESPECIFICADO y enumera lo que falta en Información faltante. Cuando haya contradicciones, conserva las alternativas y pide verificación. No afirmes cumplimiento normativo sin documentación.

Haz la ficha de requerimientos de este espacio:

{ENTRADA}
```

## Entrada 1

### Texto de entrada

Quiero adaptar una habitación como estudio personal para una persona adulta.
La habitación está en la planta baja de mi vivienda en Aguascalientes, México.
Mide 4 por 3 metros libres interiores y tiene una altura de 2.60 metros.
Tiene una ventana practicable que comunica directamente con el patio abierto.
Recibe luz natural por esa ventana y ya cuenta con una lámpara en el techo.
No atenderé público ni modificaré muros; no cuento con documentación normativa.

### Respuesta transcrita de Gemini

| **Campo** | **Valor** | | | | | |
| --- | --- | --- | --- | --- | --- | --- |
| Uso | Estudio personal para una persona adulta (sin atención a público), ubicado en planta baja de una vivienda preexistente. No se prevén modificaciones a muros. | | | | | |
| Superficie | 12.00 m² libres interiores (4.00 m × 3.00 m), con una altura libre interior de 2.60 m (volumen: 31.20 m³). | | | | | |
| Ventilación | Natural mediante ventana practicable que comunica directamente a patio exterior abierto. Área efectiva de ventilación: NO ESPECIFICADO. | | | | | |
| Iluminación | Mixta: natural directa a través de ventana orientada a patio abierto; artificial existente mediante lámpara de techo. Niveles de iluminancia y dimensiones de ventana: NO ESPECIFICADO. | | | | | |
| Normativa aplicable | Código Municipal de Aguascalientes / Normativa local de edificación aplicable para espacios habitables en el Municipio de Aguascalientes, México (sujeta a revisión y verificación, sin documentación aportada por el cliente). | | | | | |
| Información faltante | 1. Dimensiones de la ventana (área de iluminación y superficie de ventilación útil/abrible) para cotejo de porcentajes reglamentarios respecto al piso.<br><br> | 2. Orientación de la ventana y dimensiones del patio para estimar asoleamiento y confort térmico. | <br><br> | 3. Especificaciones del punto de luz existente (tipo de lámpara, potencia, luxes estimados) y ubicación/cantidad de contactos eléctricos para equipo de trabajo. | <br><br> | 4. Requerimientos de confort térmico y acústico (necesidad de climatización artificial, aislamiento ante ruidos del patio). |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Están los seis campos, aunque Información faltante queda fragmentada entre columnas. |
| C2 Formato | 1/2 provisional | El texto recibido tiene una tabla con siete columnas en lugar de dos. Se trata como tabla parcial, según el nivel de un punto de la rúbrica; no equivale a la ausencia de ficha de las versiones anteriores. |
| C3 Incertidumbre | 2/2 | Mantiene dimensiones y cálculos derivados, marca áreas de ventana y niveles de luz como desconocidos y condiciona la referencia normativa a revisión. No afirma cumplimiento. |
| Total | 5/6 provisional | C2 depende de cotejar el formato original mediante captura. |

C2 y total provisionales por columnas adicionales en el texto copiado; pendiente cotejar una captura de la misma respuesta original. No repetir la ejecución para sustituirla.

## Entrada 2

### Texto de entrada

Quiero un espacio para trabajar desde casa y atender videollamadas.
Lo utilizaría yo solo, pero todavía no elijo qué habitación adaptar.
No sé cuántos metros tiene ni cuál es la altura disponible.
Quiero que sea cómodo y tenga buena luz durante el día.
No he revisado si tiene ventanas ni qué instalaciones existen.
Tampoco he definido en qué inmueble o municipio se realizará.

### Respuesta transcrita de Gemini

| **Campo** | **Valor** | | | | | | | |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Uso | Oficina en casa / espacio de teletrabajo individual para una persona, con requerimiento para realizar y atender videollamadas. | | | | | | | |
| Superficie | NO ESPECIFICADO | | | | | | | |
| Ventilación | NO ESPECIFICADO | | | | | | | |
| Iluminación | Buena luz durante el día (requerimiento de iluminación natural y/o diurna adecuado para confort y videollamadas; condiciones técnicas no especificadas). | | | | | | | |
| Normativa aplicable | NO ESPECIFICADO | | | | | | | |
| Información faltante | 1. Selección y levantamiento físico de la habitación (dimensiones en planta, metros cuadrados y altura disponible libre).<br><br> | 2. Existencia, ubicación, orientación y dimensiones de vanos (ventanas para ventilación e iluminación natural). | <br><br> | 3. Estado de instalaciones existentes (eléctricas, contactos para equipo, iluminación artificial y conectividad/red para videollamadas). | <br><br> | 4. Requerimientos de confort acústico y privacidad para la atención de videollamadas. | <br><br> | 5. Ubicación exacta del inmueble (municipio y jurisdicción local) para determinar el reglamento de construcción y la normativa técnica aplicable. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Los seis campos están presentes. Los valores desconocidos siguen contando como campos completos. |
| C2 Formato | 1/2 provisional | Se recibe una tabla de nueve columnas en lugar de dos. La estructura es parcial, con Información faltante repartida en columnas adicionales. |
| C3 Incertidumbre | 2/2 | Marca superficie, ventilación y normativa como NO ESPECIFICADO. Presenta la iluminación diurna como deseo del cliente y aclara que las condiciones técnicas no están especificadas. Solicita los datos físicos y de ubicación necesarios. |
| Total | 5/6 provisional | Únicamente C2 queda pendiente de verificar con la salida original. |

C2 y total provisionales por columnas adicionales en el texto copiado; pendiente cotejar una captura de la misma respuesta original. No repetir la ejecución para sustituirla.

## Entrada 3

### Texto de entrada

Quiero convertir un cuarto de mi vivienda en un taller de dibujo para cuatro personas.
Creo que mide 3 por 3 metros, aunque en otro croquis aparece 4 por 3 metros.
Digo que no tiene ventanas, pero el croquis marca una ventana hacia el patio.
Quiero aprovechar la luz natural sin abrir ni modificar vanos.
También necesito que funcione por la noche con iluminación artificial.
No sé cuál croquis está actualizado ni tengo documentos normativos del inmueble.

### Respuesta transcrita de Gemini

| **Campo** | **Valor** | | | | | | | | | |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Uso | Taller de dibujo para cuatro personas (adaptación de habitación en vivienda existente). | | | | | | | | | |
| Superficie | En contradicción: alternativa A de 9 m² (3.00 m × 3.00 m) vs. alternativa B de 12 m² (4.00 m × 3.00 m). Requiere verificación física. | | | | | | | | | |
| Ventilación | En contradicción: el cliente declara ausencia de ventanas, pero el croquis indica una ventana hacia el patio. Requiere verificación de existencia, operatividad y capacidad de ventilación natural. | | | | | | | | | |
| Iluminación | Mixta. Natural: diurna supeditada a vanos existentes sin modificaciones (condicionada a la verificación de la ventana hacia el patio). Artificial: requerida para uso nocturno con niveles aptos para dibujo. | | | | | | | | | |
| Normativa aplicable | NO ESPECIFICADO. No se dispone de ubicación, jurisdicción, reglamentación local de edificación ni documentación técnica/legal del inmueble. | | | | | | | | | |
| Información faltante | 1. Levantamiento dimensional en sitio para definir dimensiones reales (3×3 m o 4×3 m).<br><br> | 2. Verificación de la ventana hacia el patio (existencia, dimensiones, operatividad para luz y ventilación). | <br><br> | 3. Identificación del croquis o plano actualizado. | <br><br> | 4. Ubicación y jurisdicción para determinar el código o reglamento de construcción aplicable. | <br><br> | 5. Capacidad y estado de la instalación eléctrica para iluminación artificial y puestos de trabajo. | <br><br> | 6. Requerimientos de mobiliario y espacio de trabajo por dibujante para validar aforo de 4 personas. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Los seis campos están presentes. |
| C2 Formato | 1/2 provisional | El texto recibido tiene once columnas en vez de dos. Existe una ficha tabular parcial; el origen del problema no se ha verificado. |
| C3 Incertidumbre | 2/2 | Conserva ambas superficies, identifica la contradicción sobre la ventana y condiciona la luz natural a verificarla. No inventa normativa y deja la validación de aforo pendiente de información de mobiliario. |
| Total | 5/6 provisional | C2 se resolverá mediante captura de la misma respuesta original, sin repetir la ejecución. |

C2 y total provisionales por columnas adicionales en el texto copiado; pendiente cotejar una captura de la misma respuesta original. No repetir la ejecución para sustituirla.

