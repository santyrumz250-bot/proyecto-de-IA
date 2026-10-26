# Portafolio de prompts

## 25 de octubre de 2026 Semana 7

Tarea: convertir relatos de clientes en fichas de requerimientos arquitectónicos. Modelo declarado por el estudiante: Gemini, versión no indicada. Evaluación asistida por ChatGPT sobre las transcripciones recibidas.

| Iteración | Técnica | C1 máximo 6 | C2 máximo 6 | C3 máximo 6 | Total máximo 18 |
|---|---|---|---|---|---|
| 0 | Línea base | 1 | 0 | 3 | 4 |
| 1 | Rol | 4 | 0 | 4 | 8 |
| 2 | Rol y contexto | 6 | 0 | 4 | 10 |
| 3 | Anterior más formato | 6 | 6 | 6 | 18 |
| 4 | Anterior más ejemplo | 6 | 6 | 6 | 18 |
| 5 | Anterior más análisis | 6 | 3 | 5 | 14 |

Se adopta la versión 4 por su 18/18 confirmado en las transcripciones. Robustez con sala de lectura y ventana fija: 6/6. La versión 3 empata con 18/18 tras cotejar sus fotografías originales. Se conserva la versión 4 porque su robustez ya se evaluó con la cuarta entrada; el ejemplo no produjo una mejora de puntaje observable.

Plantilla: [plantilla_prompt_v1.md](../semana07/plantilla_prompt_v1.md). Incluye variables {ROL}, {LECTOR}, {ETAPA_PROYECTO} y {ENTRADA}, instrucciones y límites.

El ejemplo few-shot fue redactado con asistencia de IA, sin acreditación de autoría independiente. Se recibieron fotografías de una repetición identificada de versión 5 entrada 2 y evidencia complementaria; las evidencias obligatorias están incorporadas al reporte. No se certifica normativa ni calidad constructiva de las fichas.

Nota de procedencia: al revisar el repositorio no existía la carpeta semana06 ni portafolio_prompts.md. Este archivo inicia el registro disponible con la entrada de semana 7; no reconstruye ni atribuye trabajo de semana 6 que no se proporcionó.
