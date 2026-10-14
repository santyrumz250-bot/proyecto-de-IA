# Laboratorio 5 — tokens, temperatura y contexto

**Estado:** Los ejercicios 1, 2, 3, 4 y 5 están redactados con resultados observados; la captura de pantalla de la carpeta final de GitHub se obtiene después de subirla.

Archivos principales:
- `reporte_semana05_APA7.pdf` y `.docx`: entrega académica completa con capturas.
- `resultados_semana05.xlsx`: datos numéricos, tablas y control de evidencia.
- `documento_prueba_contexto.txt`: prueba de la aguja AZUL-7342.
- `seleccion_modelo_proyecto.md`: avance de selección de modelo.
- `capturas/`: imágenes originales enviadas por el estudiante.

Resumen de resultados:
- Documento de referencia: 3,101 tokens (OpenAI Tokenizer) y 16,723 caracteres.
- Temperatura 0 / 0.7 / 1.5: 27 / 26 / 32 palabras distintas entre tres respuestas.
- Contexto con 1 / 2 / 4 / 8 copias: recuperación correcta en todos los casos; hasta 25,458 tokens mostrados en AI Studio.
- Código al inicio, mitad y final: correcto en todos los casos.

**Límite:** No se observó pérdida de información ni rechazo, por lo que no se puede afirmar dónde está el máximo de la ventana. La referencia de 32,000 tokens es hipotética y se utiliza solo en la reflexión.

**GitHub:** mensaje de commit solicitado: `Semana 5: experimentos de tokens, temperatura y contexto`.
