# Plantilla de ficha de requerimientos arquitectónicos v1

Basada en la iteración 4, adoptada por su puntuación confirmada de 18/18 y robustez de 6/6.

## Plantilla

```text
Eres {ROL}. Tu lector es {LECTOR}, que necesita una ficha clara para conversar con el cliente.

Contexto: la entrada proviene de un cliente sin conocimientos técnicos. La ficha debe cubrir uso, superficie, ventilación, iluminación, normativa aplicable e información faltante. Se utiliza para {ETAPA_PROYECTO}, no para certificar cumplimiento. No hay una norma ni una jurisdicción predeterminadas.

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

## Instrucciones de uso

- {ROL}: arquitecto de apoyo en programación de espacios, u otro rol pertinente.
- {LECTOR}: destinatario real; por ejemplo, equipo de anteproyecto.
- {ETAPA_PROYECTO}: un anteproyecto u otra fase declarada.
- {ENTRADA}: relato del cliente; conservar medidas, ausencias y contradicciones sin corregirlas antes de procesarlas.

Mantener las dos columnas y seis filas. No sustituir desconocimiento por medidas orientativas. La ubicación, cuando exista, forma parte de {ENTRADA}; no presupone una norma aplicable ni cumplimiento. Mantener el ejemplo fijo para comparar resultados; si se modifica, repetir la validación.

## Modelo y evidencia

Gemini, según el usuario. Versión exacta, parámetros y fechas de ejecución no indicados. Se registraron tres respuestas por versión y una entrada reservada, aportadas como transcripciones. La apertura independiente de conversaciones se instruyó, pero no se verificó con capturas. Versión 4: C1=6, C2=6, C3=6; total 18/18. Robustez: 6/6. Evaluación asistida por ChatGPT.

## Limitaciones

Los criterios no acreditan suficiencia ambiental ni cumplimiento normativo. No sustituyen medición, documentos o revisión profesional. El ejemplo fue preparado con IA y no se acredita autoría independiente del estudiante como solicita la guía. La versión 3 también obtuvo 18/18 después del cotejo fotográfico. Se conserva la versión 4 porque es la que cuenta con robustez documentada; no se atribuye al ejemplo una mejora de puntaje. Una ejecución por caso y una sola prueba reservada no miden variabilidad ni generalización amplia.

## Evidencia posterior

Se recibió una fotografía de la robustez y dos de una repetición de versión 5 entrada 2. La interfaz de esas imágenes muestra Flash, sin versión numérica. No se altera la puntuación del conjunto principal por esta observación adicional.
