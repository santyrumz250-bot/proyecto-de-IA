# Iteración 4 · Anterior más ejemplo

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

| **Campo** | **Valor** |
| --- | --- |
| Uso | Estudio personal para una persona adulta (sin atención a público, en planta baja de vivienda). |
| Superficie | 12 m² útiles interiores (4 × 3 m; altura libre de 2.60 m). |
| Ventilación | Natural mediante ventana practicable directa al patio abierto. |
| Iluminación | Mixta: natural directa a través de la ventana al patio y artificial existente mediante luminaria en el techo. |
| Normativa aplicable | NO ESPECIFICADO (se ubica en Aguascalientes, México, sujeta al Código de Ordenamiento Territorial, Desarrollo Urbano y Vivienda local y reglamentación municipal aplicable, pero sin documentación acreditada). |
| Información faltante | Dimensiones de la ventana (área efectiva de ventilación e iluminación), orientación cardinal, niveles lumínicos actuales y documentación legal/técnica del inmueble para validar cumplimiento de normatividad local. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Están los seis campos obligatorios. |
| C2 Formato | 2/2 | Una tabla de dos columnas, Campo y Valor, seis filas en el orden pedido y sin texto exterior. |
| C3 Incertidumbre | 2/2 | Conserva medidas expresas y cálculo de superficie; no inventa dimensiones de ventana ni niveles de luz. Marca normativa como NO ESPECIFICADO por falta de documentación y no certifica cumplimiento. |
| Total | 6/6 | Primera respuesta de estas pruebas recibida con las dos columnas exactas en el texto pegado. |

## Entrada 2

### Texto de entrada

Quiero un espacio para trabajar desde casa y atender videollamadas.
Lo utilizaría yo solo, pero todavía no elijo qué habitación adaptar.
No sé cuántos metros tiene ni cuál es la altura disponible.
Quiero que sea cómodo y tenga buena luz durante el día.
No he revisado si tiene ventanas ni qué instalaciones existen.
Tampoco he definido en qué inmueble o municipio se realizará.

### Respuesta transcrita de Gemini

| **Campo** | **Valor** |
| --- | --- |
| Uso | Espacio de trabajo individual desde casa (home office) y atención de videollamadas. |
| Superficie | NO ESPECIFICADO. |
| Ventilación | NO ESPECIFICADO. |
| Iluminación | Deseo de buena luz natural durante el día (condiciones técnicas e instalaciones no especificadas). |
| Normativa aplicable | NO ESPECIFICADO. |
| Información faltante | Habitación seleccionada, dimensiones (largo, ancho y altura disponible / superficie en m²), presencia y características de ventanas (ventilación/luz natural), instalaciones eléctricas y de datos existentes, e inmueble y municipio/jurisdicción del proyecto para determinar la normativa aplicable. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Los seis campos están presentes, incluidos los marcados como desconocidos. |
| C2 Formato | 2/2 | Una tabla Campo y Valor de dos columnas, con las seis filas en el orden requerido y sin texto exterior. |
| C3 Incertidumbre | 2/2 | No inventa superficie, ventanas ni normativa. Distingue el deseo de iluminación diurna de la existencia de condiciones físicas para lograrla y enumera los datos pendientes. |
| Total | 6/6 | Cumple los tres criterios sobre la transcripción recibida. |

## Entrada 3

### Texto de entrada

Quiero convertir un cuarto de mi vivienda en un taller de dibujo para cuatro personas.
Creo que mide 3 por 3 metros, aunque en otro croquis aparece 4 por 3 metros.
Digo que no tiene ventanas, pero el croquis marca una ventana hacia el patio.
Quiero aprovechar la luz natural sin abrir ni modificar vanos.
También necesito que funcione por la noche con iluminación artificial.
No sé cuál croquis está actualizado ni tengo documentos normativos del inmueble.

### Respuesta transcrita de Gemini

| **Campo** | **Valor** |
| --- | --- |
| Uso | Taller de dibujo doméstico para 4 personas. |
| Superficie | 9 m² (3 × 3 m) o 12 m² (4 × 3 m), según croquis en contradicción (requiere verificación en sitio). |
| Ventilación | NO ESPECIFICADO (contradicción entre versión verbal sin ventanas y croquis con ventana hacia el patio; requiere verificación). |
| Iluminación | Mixta: aprovechamiento de luz natural existente sin modificar vanos (sujeto a confirmar ventana al patio) e iluminación artificial para uso nocturno (niveles y luminarias no definidos). |
| Normativa aplicable | NO ESPECIFICADO. |
| Información faltante | Dimensiones reales del espacio (levantamiento en sitio para resolver 3 × 3 m vs. 4 × 3 m); verificación física de existencia, medidas y operatividad de la ventana al patio; requerimientos técnicos de iluminación artificial (luxes para dibujo y temperatura de color); ubicación geográfica/jurisdicción del inmueble y documentación normativa aplicable. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Los seis campos están presentes. |
| C2 Formato | 2/2 | Tabla de dos columnas con seis filas en el orden establecido, sin texto exterior. |
| C3 Incertidumbre | 2/2 | Conserva ambas superficies y la contradicción de la ventana. Condiciona la luz natural a comprobarla; no inventa luminarias, niveles de luz ni normativa. |
| Total | 6/6 | Cumple la rúbrica sobre el texto recibido. |

