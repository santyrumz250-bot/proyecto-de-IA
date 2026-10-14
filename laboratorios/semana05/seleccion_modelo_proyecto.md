# Selección de modelo generativo para el proyecto Sistema de IA para costos y presupuestos de obra

**Materia:** Inteligencia Artificial Aplicada — Semana 5  
**Fecha de pruebas:** 13 de octubre de 2026  
**Naturaleza de los datos:** mediciones reales aportadas mediante capturas de pantalla.

## Modelos evaluados

Se probó experimentalmente **Gemini 3 Flash Preview**, a través de Google AI Studio. ChatGPT se utilizó como apoyo para preparar documentos, transcribir, organizar y analizar las pruebas, sin someterlo a los mismos experimentos. No hay datos verificables de pruebas de DeepSeek u otros modelos en esta entrega; por tanto, **no se afirma que Gemini supere a esas alternativas**.

## Evidencia de tokens

El documento ficticio de referencia de arquitectura contiene **16,723 caracteres y 3,101 tokens** en el tokenizador web de OpenAI, opción GPT-5.x & O1/O3. Las frases de prueba (definiciones arquitectónicas) no equivalen a ensayos de exactitud de presupuestos. La frase corta en español tuvo 62 caracteres y 9 tokens (**6.89 caracteres/token**); en inglés tuvo 53 caracteres y 7 tokens (**7.57 caracteres/token**). El párrafo de arquitectura en español registró 735 caracteres y 121 tokens (**6.07**); en inglés, 715 caracteres y 115 tokens (**6.22**). El inglés consumió menos tokens en ambas muestras; la diferencia no debe generalizarse a todos los textos.

**Implicación:** medir documentos extensos, reservar tokens para instrucciones y respuestas, y validar el costo según el tokenizador del modelo que se use realmente; el tokenizador OpenAI es una referencia, no un conteo equivalente garantizado para Gemini.

## Evidencia de temperatura

Con el mismo prompt, tres chats independientes en cada condición y Gemini 3 Flash Preview:

| Temperatura | Palabras distintas (3 respuestas) | Respuestas idénticas |
|---:|---:|---:|
| 0 | 27 | 0 |
| 0.7 | 26 | 0 |
| 1.5 | 32 | 0 |

Se propone **temperatura 0 para tareas de precisión**, principalmente por reducir aleatoriedad, aunque en las tres ejecuciones las respuestas no fueron idénticas. Para **generar ideas y nombres**, temperatura **1.5**, ya que obtuvo el vocabulario más variado (32 términos distintos), sin errores manifiestos en la muestra. Las herramientas de Google Search estaban activadas durante las pruebas de temperatura, por lo que la variación no puede atribuirse exclusivamente a este parámetro.

## Evidencia de contexto

El código ficticio **AZUL-7342** se recuperó correctamente con **1, 2, 4 y 8 copias** del documento. Los contadores de AI Studio indicaron **3,655; 6,812; 12,884 y 25,458 tokens** de conversación, respectivamente. La interfaz no rechazó el texto. Estos ensayos usaron un documento ficticio de arquitectura, no cotizaciones reales, por lo que la decisión sigue siendo provisional. Con una sola copia, también lo identificó cuando estaba al **inicio (3,338 tokens), mitad (3,655) y final (3,496)**. **No se observó pérdida de información ni se estableció el límite máximo de contexto.**

Si se asumen cuatro páginas equivalentes para el documento de referencia, 3,101/4 = **775.25 tokens por página** y en 32,000 tokens cabrían teóricamente **41.28 páginas equivalentes**. La estimación no deja espacio para instrucciones, respuesta, metadatos o variaciones de tokenización y no garantiza recuperación perfecta. Para uso real conviene segmentar documentos y citar secciones verificables.

## Decisión

**Modelo provisional elegido:** Gemini 3 Flash Preview, porque es el único comprobado empíricamente en esta práctica y logró 7/7 recuperaciones correctas de código (cuatro longitudes y tres posiciones, con la prueba intermedia utilizada en ambos análisis). Se debe comparar después con otros modelos bajo el mismo conjunto de pruebas.

**Configuración sugerida:** temperatura 0 para la extracción y revisión documental; 1.5 solo para lluvia de ideas, sin tratar sus propuestas como especificaciones técnicas.

**Datos y privacidad (semana 4):** utilizar documentos ficticios o públicos y evitar subir datos personales, planos confidenciales, credenciales o documentos sin autorización. Validar cada afirmación técnica con el reglamento oficial y una revisión humana profesional.

## Declaración de uso de IA

ChatGPT ayudó a elaborar los documentos ficticios, organizar el método, transcribir respuestas, calcular indicadores, redactar el reporte y preparar los archivos. Todas las observaciones atribuidas a Gemini y al tokenizador provienen de capturas reales proporcionadas por la persona que efectuó las pruebas. No se fabricaron capturas ni se reportaron fallos que no ocurrieron.
