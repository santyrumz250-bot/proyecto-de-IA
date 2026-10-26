# Iteración 2 · Rol y contexto

Respuestas reales según transcripciones aportadas por el estudiante desde Gemini. Versión exacta y capturas pendientes de verificar. No se han sustituido respuestas por los ejemplos ilustrativos previos.

## Prompt completo

```text
Eres arquitecto de apoyo en programación de espacios. Tu lector es el equipo de anteproyecto, que necesita una ficha clara para conversar con el cliente.

Contexto: la entrada proviene de un cliente sin conocimientos técnicos. La ficha debe cubrir uso, superficie, ventilación, iluminación, normativa aplicable e información faltante. Se utiliza para un anteproyecto, no para certificar cumplimiento. No hay una norma ni una jurisdicción predeterminadas.

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

## Ficha de Programación y Requerimientos de Espacio

* **Proyecto:** Adaptación de habitación a estudio personal
* **Ubicación:** Aguascalientes, Ags., México (Planta baja, residencial)
* **Destinatario:** Equipo de Anteproyecto / Entrevista con cliente

---

### 1. Datos Generales y Uso del Espacio

* **Uso principal:** Estudio y trabajo personal / oficina en casa para un adulto.
* **Intensidad de uso y aforo:** 1 usuario permanente; sin atención a clientes ni recepción de público externo.
* **Alcance de obra:** Adecuación interior ligera (interiorismo, mobiliario e instalaciones). No contempla demolición ni modificación de muros estructurales.
* **Zonificación básica:** Zona de escritorio/trabajo concentrado, zona de librero/almacenamiento y posible rincón de lectura o descanso secundario.

---

### 2. Dimensiones y Parámetros Espaciales

* **Dimensiones libres interiores:** 4.00 m × 3.00 m.
* **Área neta útil:** 12.00 m² (amplitud adecuada para estudio individual; el estándar mínimo de habitabilidad suele rondar entre 7.00 m² y 9.00 m²).
* **Altura libre interior:** 2.60 m.
* **Volumen de aire:** 31.20 m³ (óptimo para confort higrotérmico y renovación de aire).

---

### 3. Ventilación y Confort Térmico

* **Estado actual:** Ventana practicable con ventilación natural directa hacia un patio abierto.
* **Evaluación previa:** El contacto directo con el patio garantiza tiro de aire natural. En el clima semiárido templado de Aguascalientes, la ventilación hacia patio ayuda a refrescar en verano si se controla la ganancia solar directa.
* **Criterio de anteproyecto:**
* Verificar área libre de apertura (habitualmente se busca al menos el 5% del área útil: $\ge 0.60\text{ m}^2$ efectivos).
* Evaluar necesidad de ventilación cruzada indirecta a través de la puerta interior hacia pasillos/estancias.



---

### 4. Iluminación

* **Iluminación natural:**
* Entrada directa por la ventana orientada al patio.
* Criterio: Verificar área acristalada (referencia habitual de confort: al menos el 10%–15% del área útil: $1.20\text{ m}^2$ a $1.80\text{ m}^2$).
* Considerar control solar (persianas traslúcidas/blackout) para evitar deslumbramientos sobre pantallas de trabajo.


* **Iluminación artificial:**
* **Existente:** 1 centro de luz general en plafón.
* **Requerimiento funcional:** La luz cenital única genera sombras directas sobre el plano de trabajo. Se debe plantear iluminación por capas: general difusa (300 lux), tarea puntual sobre escritorio (500 lux) y luz perimetral/ambiente cálida.



---

### 5. Marco Normativo de Referencia (Criterios Guía)

> *Nota: No existe trámite de licencia estructural al no intervenir muros, pero los siguientes ordenamientos sirven como parámetro de habitabilidad y buenas prácticas para la propuesta:*

* **Código de Ordenamiento Territorial, Desarrollo Urbano y Vivienda para el Estado de Aguascalientes (COTEDUVI):** Parámetros locales sobre dimensiones mínimas de recámaras/despachos, alturas libres ($\ge 2.40\text{ m}$, cumplido con 2.60 m) y porcentajes de vanos.
* **Reglamento de Construcciones del Municipio de Aguascalientes:** Criterios de ventilación e iluminación hacia patios interiores o posteriores.
* **NOM-025-STPS / NOM-001-SEDE:** Niveles recomendados de iluminación para trabajo de oficina visual prolongado e instalaciones eléctricas seguras para equipo de cómputo.

---

### 6. Información Faltante para la Conversación con el Cliente

| Tema | Pregunta / Aspecto a indagar | Relevancia en diseño |
| --- | --- | --- |
| **Orientación solar** | ¿Hacia qué punto cardinal abre la ventana (norte, sur, este, poniente)? | Definir ubicación del escritorio para evitar reflejos y seleccionar protección solar. |
| **Equipamiento técnico** | ¿Cuántos monitores, computadoras, impresoras u otros aparatos usará? | Cálculo de carga eléctrica y número/altura de contactos regulados. |
| **Instalaciones existentes** | ¿Dónde están ubicados los contactos eléctricos, apagadores y tomas de red? | Evaluar si se requieren canalizaciones o regatas menores sin tocar estructura. |
| **Vínculo con el patio** | ¿El vano es ventana alta o puerta-ventana con acceso peatonal al patio? | Determinar circulaciones interiores y posibles interferencias de paso. |
| **Acústica y privacidad** | ¿Se realizarán videollamadas constantes o grabaciones de audio? | Considerar sellos acústicos en puerta/ventana y absorción en muros/alfombras. |
| **Almacenamiento** | ¿Requiere archiveros cerrados, libreros abiertos o solo una mesa libre? | Dimensionamiento de carpinterías fijas vs. mobiliario exento. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Los seis campos están desarrollados. La presencia de contenido normativo cuenta para cobertura, sin certificar su corrección. |
| C2 Formato | 0/2 | Usa apartados y una tabla auxiliar de tres columnas, sin ficha Campo y Valor de dos columnas. |
| C3 Incertidumbre | 1/2 | Solicita información adicional, pero garantiza tiro de aire, califica el volumen como óptimo y afirma una exención de trámite y cumplimiento de altura sin verificación documental o ambiental. |
| Total | 3/6 | El contexto mejora la cobertura; no elimina por sí solo las conclusiones no sustentadas. |

## Entrada 2

### Texto de entrada

Quiero un espacio para trabajar desde casa y atender videollamadas.
Lo utilizaría yo solo, pero todavía no elijo qué habitación adaptar.
No sé cuántos metros tiene ni cuál es la altura disponible.
Quiero que sea cómodo y tenga buena luz durante el día.
No he revisado si tiene ventanas ni qué instalaciones existen.
Tampoco he definido en qué inmueble o municipio se realizará.

### Respuesta transcrita de Gemini

# Ficha de Programación Arquitectónica: Espacio de Home Office

---

### 1. Uso y Caracterización del Espacio

* **Uso principal:** Oficina en casa (teletrabajo individual) y set para videollamadas.
* **Ocupación:** 1 persona de manera continua; sin atención a visitantes externos.
* **Actividades clave:**
* Trabajo en escritorio frente a pantalla(s).
* Videoconferencias y llamadas de voz (requiere control acústico y visual de fondo).
* Almacenamiento básico de papelería, archivo menor y equipos tecnológicos.


* **Equipamiento base estimado:** Escritorio de trabajo, silla ergonómica, monitor(es), ordenador, iluminación auxiliar de apoyo, espacio de guardado y eventual superficie para impresora o periféricos.

---

### 2. Dimensiones y Superficie (Estimaciones para Anteproyecto)

* **Superficie útil recomendada:**
* **Mínima funcional:** $6.00\text{ m}^2$ a $7.50\text{ m}^2$ (espacio para escritorio, silla con radio de giro libre y circulación básica de acceso).
* **Óptima/Confort:** $9.00\text{ m}^2$ a $12.00\text{ m}^2$ (permite mobiliario de almacenamiento auxiliar, espacio de fondo despejado para cámara y flexibilidad distributiva).


* **Altura libre recomendada:** Mínimo funcional de $2.30\text{ m}$ a $2.40\text{ m}$; recomendable $\ge 2.50\text{ m}$ para confort térmico y adecuada dispersión lumínica.

---

### 3. Ventilación

* **Natural:**
* Se recomienda prever apertura operable equivalente al menos al **5% – 10%** de la superficie en planta para renovación pasiva de aire.
* Cruce o circulación de aire para evitar concentración de calor emitido por equipos informáticos.


* **Mecánica / Climatización:**
* Previsión para aire acondicionado (tipo split) o ventilación mecánica silenciosa; el nivel sonoro del sistema no debe interferir con micrófonos en videollamadas ($< 35\text{ dBA}$).



---

### 4. Iluminación

* **Natural:**
* Orientación preferente indirecta (norte o este en el hemisferio norte) para evitar sobrecalentamiento y deslumbramientos en pantallas.
* Área de acristalamiento recomendada: **10% – 15%** de la superficie útil.
* Requisito de control solar/sombreamiento (estores técnicos, cortinas traslúcidas) para evitar contraluz directo frente a la cámara web o reflejos sobre monitores.


* **Artificial:**
* **Iluminación general:** 150 a 300 lux, temperatura de color neutra o cálida-neutra ($3500\text{ K} - 4000\text{ K}$).
* **Iluminación puntual de trabajo:** 500 lux en plano de escritorio (luminaria focal directa sin destello).
* **Iluminación frontal difusa para videollamadas:** Evitar luz cenital directa (sombras duras en el rostro); disponer de punto de iluminación frontal indirecta hacia el usuario.



---

### 5. Marco Normativo de Referencia (A título orientativo)

Al no existir jurisdicción ni inmueble definidos, se tomarán como base las buenas prácticas de habitabilidad estándar:

* **Habitabilidad y edificación:** Criterios generales de reglamentos locales de construcción (dimensiones mínimas de recintos habitables, ventilación e iluminación natural en porcentaje de superficie útil).
* **Ergonomía y salud ocupacional:** Criterios tipo ISO 9241 o directrices de seguridad laboral para pantallas de visualización (distancias visuales, alturas de plano de trabajo, niveles de confort lumínico de 500 lux en plano de apoyo).
* **Acústica:** Recomendaciones de aislamiento básico entre particiones interiores ($R'_w \ge 40\text{ dB}$ deseable) para aislar ruidos domésticos durante reuniones.

---

### 6. Información Faltante y Requerimientos a Definir con el Cliente

| Categoría | Información Requerida | Impacto en el Anteproyecto |
| --- | --- | --- |
| **Ubicación e Inmueble** | Municipio/ciudad y tipo de edificio (vivienda unifamiliar, departamento en altura, etc.). | Determina normativa aplicable, orientación solar, clima y posibilidades de reforma. |
| **Espacio Existente** | Levantamiento arquitectónico: planta, cotas perimetrales y altura libre exacta de la habitación elegida. | Validación de encaje dimensional y capacidad distributiva real. |
| **Huecos y Fachada** | Presencia, posición y tamaño de ventanas existentes; tipo de carpintería y acristalamiento. | Define la estrategia de iluminación natural, aislamiento acústico exterior y ventilación. |
| **Instalaciones Actuales** | Ubicación de tomas de corriente, puntos de red (ethernet/router), cuadro eléctrico y previsión de climatización. | Afecta la distribución del escritorio (evitar cableado visto) y define si se requiere obra en instalaciones. |
| **Condicionantes Acústicos** | Adyacencia a zonas ruidosas de la casa (calles transitadas, cocina, sala de estar, patios técnicos). | Define necesidad de trasdosados acústicos o puertas macizas para videollamadas sin interrupción. |
| **Estética y Encuadre** | Intención de fondo para videollamadas (muro liso, estantería decorativa, panelado acústico). | Define la orientación focal del usuario frente a la cámara respecto a la puerta y ventana. |

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Aborda los seis campos: uso, superficie, ventilación, iluminación, normativa e información faltante. |
| C2 Formato | 0/2 | Apartados y tabla auxiliar de tres columnas; no entrega una tabla Campo y Valor de dos columnas. |
| C3 Incertidumbre | 2/2 | Declara que jurisdicción e inmueble no están definidos y solicita las condiciones reales de dimensiones, ventanas e instalaciones. Las superficies y alturas están rotuladas como recomendaciones. No certifica cumplimiento de un inmueble concreto. |
| Total | 4/6 | El puntaje evalúa la gestión de datos disponibles, no la validación técnica de las recomendaciones. |

## Entrada 3

### Texto de entrada

Quiero convertir un cuarto de mi vivienda en un taller de dibujo para cuatro personas.
Creo que mide 3 por 3 metros, aunque en otro croquis aparece 4 por 3 metros.
Digo que no tiene ventanas, pero el croquis marca una ventana hacia el patio.
Quiero aprovechar la luz natural sin abrir ni modificar vanos.
También necesito que funcione por la noche con iluminación artificial.
No sé cuál croquis está actualizado ni tengo documentos normativos del inmueble.

### Respuesta transcrita de Gemini

# Ficha de Programación Arquitectónica | Taller de Dibujo

Documento preliminar de síntesis y requerimientos para la reunión de alineación con el cliente (fase de anteproyecto).

---

### 1. Definición y Uso del Espacio

* **Uso principal:** Taller de dibujo técnico/artístico para 4 puestos de trabajo simultáneos.
* **Perfil de ocupación:** 4 personas sentadas o de pie frente a mesas/restiradores de trabajo, más espacio de almacenaje de material (papel, tableros, útiles) y circulaciones mínimas.
* **Régimen de uso:** Mixto (diurno con aprovechamiento pasivo y nocturno bajo iluminación artificial).

---

### 2. Superficie y Dimensionamiento

| Escenario | Dimensiones | Área Útil | Viabilidad para 4 Puestos |
| --- | --- | --- | --- |
| **Opción A (Croquis 1)** | 3.00 × 3.00 m | 9.00 m² | **Crítica / No viable.** Permite apenas 2.25 m²/persona; no deja espacio para restiradores estándar (min. 1.00 × 0.70 m), sillas y pasillos de 0.80 m. |
| **Opción B (Croquis 2)** | 4.00 × 3.00 m | 12.00 m² | **Ajustada pero factible.** Ofrece 3.00 m²/persona. Exige una modulación compacta (mesas en batería central o perimetral compartida). |

---

### 3. Confort Lumínico

#### Iluminación Natural (Diurna)

* **Condición de partida:** Aprovechamiento estricto de vanos existentes; no se permite demolición ni apertura de nuevos huecos.
* **Estrategia anteproyecto:**
* Si se confirma la ventana hacia el patio: orientar los puestos de modo que la luz entre lateralmente al usuario (evitando sombras directas sobre el plano de dibujo y deslumbramiento frontal).
* Evaluar el plano de trabajo respecto al vano para evitar reflejos especulares sobre láminas y pantallas auxiliares.
* Colores claros en paramentos interiores (paredes y techos con reflectancia mayor al 70–80%) para maximizar la difusión de la luz disponible.



#### Iluminación Artificial (Nocturna)

* **Nivel de iluminancia objetivo:** 500 a 750 lux sobre el plano de trabajo (estándar recomendado para tareas de dibujo fino y detalle).
* **Calidad de luz:**
* **CRI / IRC:** ≥ 90 (reproducción cromática fiel para tintas, pigmentos y matices).
* **Temperatura de color:** Neutra (4000 K) o balanceada regulable (3500–4000 K) para evitar distorsión de color y fatiga visual.
* **Esquema propuesto:** Luz difusa de fondo (antideslumbrante) combinada con luminarias direccionales regulables (brazo articulado) por puesto.



---

### 4. Ventilación y Calidad del Aire Interior

* **Ventilación natural:**
* Si el vano existe: verificar que el área libre de apertura represente al menos el 5% al 10% de la superficie del piso.
* Si el recinto resulta ciego: se requerirá implementar ventilación mecánica o forzada (extracción/inyección) para garantizar renovación continua de aire (mínimo 6 a 8 renovaciones/hora por acumulación de CO₂ de 4 ocupantes y eventual uso de solventes/fijadores).



---

### 5. Criterios Normativos de Referencia (Base Genérica)

Dado que no existe jurisdicción local definida, se consideran las siguientes pautas de buenas prácticas arquitectónicas:

* **Área mínima por puesto técnico:** 2.50 a 3.50 m² por usuario en talleres compartidos.
* **Nivel lumínico para tareas visuales severas:** 500 lux promedio general, con refuerzo focalizado.
* **Circulación de evacuación:** Paso libre mínimo de 0.80 a 0.90 m hacia la puerta de salida.

---

### 6. Información Faltante y Temas a Resolver con el Cliente

1. **Levantamiento físico in situ:**
* Medición real de muros, diagonales y altura libre de piso a techo.
* Confirmación concluyente de la existencia, ubicación y medidas del vano hacia el patio (antepecho, dintel, ancho).


2. **Dimensiones y tipo de mobiliario deseado:**
* ¿Trabajarán sobre mesas fijas, restiradores inclinables o caballetes?
* ¿Se requieren muebles de guardado (planeras horizontales, estanterías, cajoneras)?


3. **Instalación eléctrica actual:**
* Posición y cantidad de tomas de corriente y puntos de luz existentes en techo y muros.
* Capacidad del circuito para soportar iluminación puntual y equipos de apoyo (tabletas, lámparas, cómputo).

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Desarrolla los seis campos: uso, superficies alternativas, ventilación, iluminación, referencias normativas e información faltante. |
| C2 Formato | 0/2 | Usa apartados y una matriz de cuatro columnas; no entrega la ficha de dos columnas Campo y Valor. |
| C3 Incertidumbre | 1/2 | Conserva ambas medidas y pide verificar la ventana, pero dictamina no viabilidad para 9 m² y factibilidad para 12 m² sin comprobar distribución y mobiliario. También presenta umbrales técnicos como mínimos sin documentar su aplicabilidad. |
| Total | 3/6 | Reconoce contradicciones, aunque mantiene conclusiones con más certeza que la información disponible. |

