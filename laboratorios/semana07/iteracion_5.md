# Iteración 5 · Anterior más análisis

Respuestas reales según transcripciones aportadas por el estudiante desde Gemini. Versión exacta y capturas pendientes de verificar. No se han sustituido respuestas por los ejemplos ilustrativos previos.

## Prompt completo

```text
Eres arquitecto de apoyo en programación de espacios. Tu lector es el equipo de anteproyecto, que necesita una ficha clara para conversar con el cliente.

Contexto: la entrada proviene de un cliente sin conocimientos técnicos. La ficha debe cubrir uso, superficie, ventilación, iluminación, normativa aplicable e información faltante. Se utiliza para un anteproyecto, no para certificar cumplimiento. No hay una norma ni una jurisdicción predeterminadas.

Formato de salida: responde únicamente con una tabla Markdown de dos columnas, Campo y Valor, y estas seis filas en este orden: Uso; Superficie; Ventilación; Iluminación; Normativa aplicable; Información faltante. No escribas texto fuera de la tabla. Si no puedes determinar un dato a partir de la entrada, escribe NO ESPECIFICADO y enumera lo que falta en Información faltante. Cuando haya contradicciones, conserva las alternativas y pide verificación. No afirmes cumplimiento normativo sin documentación.

Ejemplo de entrada: "Quiero una bodega doméstica para guardar cajas. Mide 2 por 2 metros. No he revisado ventanas, lámparas ni normativa."
Ejemplo de salida:
| Campo | Valor |
|---|---|
| Uso | Bodega doméstica para guardar cajas. |
| Superficie | 4 m² (2 × 2 m). |
| Ventilación | NO ESPECIFICADO. |
| Iluminación | NO ESPECIFICADO. |
| Normativa aplicable | NO ESPECIFICADO. |
| Información faltante | Ventanas, iluminación, ubicación del inmueble y documentación normativa. |

Cambio de salida para esta versión: antes de la tabla, presenta una sección Análisis con exactamente tres viñetas breves: información explícita, inferencias comprobables y datos no determinables. Presenta solo una síntesis de evidencias y cálculos, sin razonamiento interno extenso. Después incluye la tabla. Esta instrucción sustituye exclusivamente la regla anterior que prohibía texto fuera de la tabla.

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

Análisis

- **Información explícita:** Estudio personal para un adulto en planta baja (vivienda en Aguascalientes, México) sin atención a público ni modificación de muros; dimensiones interiores libres de 4 × 3 m con 2.60 m de altura; ventana practicable a patio abierto; luz natural por ventana y lámpara de techo existente; carece de documentación normativa.

- **Inferencias comprobables:** Superficie útil de 12 m² ($4 \times 3\text{ m}$) y volumen de 31.2 m³ ($12 \times 2.60\text{ m}$); ventilación e iluminación naturales existentes a través del patio exterior; la normativa aplicable de referencia corresponde al Código Municipal / Reglamento de Construcciones de Aguascalientes, México.

- **Datos no determinables:** Dimensiones exactas y porcentaje de apertura de la ventana (para verificar coeficientes reglamentarios de iluminación/ventilación natural), niveles de iluminancia artificial (lúmenes/luxes de la lámpara existente) y planos o licencias del inmueble.

| **Campo** | **Valor** |
| --- | --- |
| Uso | Estudio personal para una persona adulta (sin atención a público, dentro de vivienda). |
| Superficie | 12 m² (4 × 3 m libres interiores; altura libre de 2.60 m; volumen de 31.2 m³). |
| Ventilación | Natural mediante ventana practicable comunicada directamente a patio abierto. |
| Iluminación | Mixta: natural por ventana a patio abierto y artificial mediante lámpara de techo preexistente. |
| Normativa aplicable | Reglamento de Construcciones del Municipio de Aguascalientes, Ags., México (referencia local sujeta a cotejo documental). |
| Información faltante | Dimensiones/área efectiva de la ventana, niveles de iluminación artificial de la luminaria actual y planos o licencias del inmueble para validar cumplimiento normativo. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Incluye los seis campos obligatorios y las tres viñetas solicitadas. |
| C2 Formato | 1/2 | La tabla tiene dos columnas y seis filas, pero el análisis previo queda fuera de la tabla. La rúbrica conserva el contrato de producción original; no se penaliza como incumplimiento de la nueva instrucción. |
| C3 Incertidumbre | 1/2 | Reconoce datos desconocidos, pero sitúa la identificación de normativa aplicable entre las inferencias comprobables sin aportar verificación. El cálculo de superficie y volumen sí deriva de la entrada; la referencia normativa no tiene ese mismo respaldo. La salvedad posterior en la tabla no elimina la certeza expresada en el análisis. |
| Total | 4/6 | Se evalúa la respuesta completa, incluido el análisis, no solo la tabla final. |

## Entrada 2

### Texto de entrada

Quiero un espacio para trabajar desde casa y atender videollamadas.
Lo utilizaría yo solo, pero todavía no elijo qué habitación adaptar.
No sé cuántos metros tiene ni cuál es la altura disponible.
Quiero que sea cómodo y tenga buena luz durante el día.
No he revisado si tiene ventanas ni qué instalaciones existen.
Tampoco he definido en qué inmueble o municipio se realizará.

### Respuesta transcrita de Gemini

Análisis

- **Información explícita:** Espacio de trabajo individual en casa para atender videollamadas; requiere comodidad y buena luz diurna; sin habitación definida, medidas, altura, ventanas, instalaciones, inmueble ni municipio elegidos.

- **Inferencias comprobables:** Uso tipológico asimilable a estudio o despacho doméstico para una persona; demanda de confort acústico/visual para videollamadas y potencial requerimiento de iluminación natural y tomas de corriente/red.

- **Datos no determinables:** Superficie y altura útiles, condiciones de ventilación natural/mecánica, luminarias e instalaciones existentes, ubicación geográfica y normativa aplicable.

| **Campo** | **Valor** |
| --- | --- |
| Uso | Despacho / espacio para trabajo individual desde casa y atención de videollamadas (un solo usuario). |
| Superficie | NO ESPECIFICADO. |
| Ventilación | NO ESPECIFICADO. |
| Iluminación | Buena luz durante el día (sin especificación de ventanas, orientación o iluminación artificial). |
| Normativa aplicable | NO ESPECIFICADO. |
| Información faltante | Habitación seleccionada, dimensiones (largo, ancho y altura), ventanas y ventilación existente, instalaciones eléctricas/datos, e inmueble y municipio (jurisdicción para normativa local). |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Incluye los seis campos y las tres viñetas de análisis. |
| C2 Formato | 1/2 | Hay tabla de dos columnas y seis filas, pero el análisis está fuera de la tabla, lo que no satisface el contrato de producción original de la rúbrica. Cumple la nueva instrucción de versión 5. |
| C3 Incertidumbre | 2/2 | No atribuye medidas, ventanas ni instalaciones existentes. Reconoce la normativa como no determinable y expresa los requisitos de acondicionamiento como necesidades o posibilidades, no como condiciones físicas confirmadas. |
| Total | 5/6 | El único descuento corresponde al formato de producción fijado desde el inicio. |

## Entrada 3

### Texto de entrada

Quiero convertir un cuarto de mi vivienda en un taller de dibujo para cuatro personas.
Creo que mide 3 por 3 metros, aunque en otro croquis aparece 4 por 3 metros.
Digo que no tiene ventanas, pero el croquis marca una ventana hacia el patio.
Quiero aprovechar la luz natural sin abrir ni modificar vanos.
También necesito que funcione por la noche con iluminación artificial.
No sé cuál croquis está actualizado ni tengo documentos normativos del inmueble.

### Respuesta transcrita de Gemini

Análisis

- **Información explícita:** Adaptación de cuarto de vivienda a taller de dibujo para 4 personas; uso diurno aprovechando luz natural sin modificar vanos y nocturno con luz artificial; contradicción dimensional (3 × 3 m vs. 4 × 3 m) y contradicción de vano (afirma sin ventanas vs. croquis con ventana a patio); sin certeza de vigencia de croquis ni documentos normativos.

- **Inferencias comprobables:** Superficie alternativa de 9 m² (2,25 m²/persona) o 12 m² (3 m²/persona); requerimiento de alto confort visual para dibujo; la viabilidad de luz natural diurna sin abrir vanos depende estrictamente de confirmar si existe la ventana a patio.

- **Datos no determinables:** Dimensiones y superficie definitivas, existencia real de la ventana y condiciones efectivas de ventilación/iluminación natural, especificaciones de iluminación artificial, ubicación geográfica y normativa aplicable.

| **Campo** | **Valor** |
| --- | --- |
| Uso | Taller de dibujo para cuatro personas en cuarto de vivienda existente. |
| Superficie | 9 m² (3 × 3 m) o 12 m² (4 × 3 m) según croquis contradictorios; requiere verificación. |
| Ventilación | Sin ventanas según declaración del cliente / Ventana hacia patio según croquis; requiere verificación. |
| Iluminación | Aprovechamiento de luz natural existente sin abrir vanos nuevos (sujeto a confirmar ventana) e iluminación artificial para uso nocturno. |
| Normativa aplicable | NO ESPECIFICADO. |
| Información faltante | Levantamiento dimensional definitivo (3 × 3 m vs. 4 × 3 m), verificación física de existencia/dimensiones de ventana a patio, datos de instalación eléctrica para iluminación nocturna, y ubicación/documentación legal para normativa local. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Los seis campos y las tres viñetas están presentes. |
| C2 Formato | 1/2 | El análisis queda fuera de la tabla según el contrato original de producción, aunque cumple la nueva instrucción de versión 5. La tabla sí tiene las dos columnas y las seis filas solicitadas. |
| C3 Incertidumbre | 2/2 | Conserva superficies alternativas y contradicción de ventana, solicita verificación y no determina normativa ni dimensiones definitivas. No emite un dictamen general de viabilidad para cuatro usuarios. |
| Total | 5/6 | Concluye las 18 respuestas de las seis versiones. |


## Repetición posterior de la entrada 2

Se documentó una ejecución adicional mediante dos fotografías, con 5/6. Se conserva por separado en repeticion_iteracion5_entrada2.md y no sustituye la respuesta original ni modifica el total de esta iteración.
