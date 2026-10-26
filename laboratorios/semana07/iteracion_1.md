# Iteración 1 · Rol

Respuestas reales según transcripciones aportadas por el estudiante desde Gemini. Versión exacta y capturas pendientes de verificar. No se han sustituido respuestas por los ejemplos ilustrativos previos.

## Prompt completo

```text
Eres arquitecto de apoyo en programación de espacios. Tu lector es el equipo de anteproyecto, que necesita una ficha clara para conversar con el cliente.

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

# Ficha de Programación Arquitectónica: Estudio Personal

---

### 1. Datos Generales y Emplazamiento

* **Uso del espacio:** Estudio / despacho personal privado (1 usuario adulto).
* **Atención al público:** Nula (uso 100% residencial y privado).
* **Ubicación física:** Planta baja, vivienda unifamiliar. Aguascalientes, Ags., México.
* **Criterio de intervención:** Adaptación interior no invasiva; **muros fijos** (sin demoliciones ni aperturas de vanos).

---

### 2. Dimensiones y Superficies Existentes

* **Largo x Ancho (libres interiores):** 4.00 m × 3.00 m.
* **Área neta útil:** 12.00 m².
* **Altura libre:** 2.60 m.
* **Volumen interior aproximado:** 31.20 m³.

---

### 3. Condiciones Ambientales y Climatológicas

* **Clima base (Aguascalientes):** Semiseco templado; oscilaciones térmicas marcadas entre el día y la noche, con inviernos secos y necesidad de ventilación cruzada/pasiva en meses cálidos.
* **Ventilación natural:** Directa y operable mediante ventana practicable hacia patio abierto.
* **Iluminación natural:** Directa a través del vano hacia el patio.
* **Iluminación artificial existente:** 1 salida central de plafón con luminaria general.

---

### 4. Zonificación Funcional Sugerida (12 m²)

| Zona | Actividad Principal | Mobiliario Estimado | Requerimientos Técnicos |
| --- | --- | --- | --- |
| **Trabajo Focalizado** | Uso de ordenador, lectura, redacción | Escritorio ergonómico (mín. 1.40 × 0.70 m), silla operativa con soporte lumbar | Orientación perpendicular a la ventana para evitar deslumbramientos directos en pantalla. |
| **Almacenamiento / Apoyo** | Archivo documental, libros, equipo auxiliar | Librero vertical perimetral, cajonera o módulo bajo exento | Anclaje mecánico puntual sin alterar elementos estructurales. |
| **Pausa / Reflexión (Opcional)** | Lectura informal, llamadas breves | Sillón individual o butaca de apoyo con mesa auxiliar | Zona próxima a la ventana/patio para aprovechar vista exterior. |
| **Circulación y Maniobra** | Desplazamiento libre interior | Espacio despejado (franja mínima de 0.90 m) | Mantener libre el radio de abatimiento de puerta y ventana. |

---

### 5. Criterios de Acondicionamiento (Alcance sin Obra Mayor)

* **Instalaciones Eléctricas y Redes:**
* Al no intervenir muros, los circuitos adicionales deberán resolverse mediante canalizaciones aparentes de diseño limpio (canaleta perimetral de rodapié o ductos expuestos) o aprovechando las cajas existentes.
* Punto focal de tomas reguladas a nivel de escritorio (mínimo 4 tomas para PC, monitor secundario, cargadores y lámpara de tarea).


* **Iluminación Artificial:**
* Complementar la lámpara cenital general con luz puntual/focal de trabajo (3,000 K a 4,000 K, neutra, libre de parpadeo).


* **Control Solar y Térmico:**
* Instalación de persiana o cortina técnica (tipo screen o traslúcida) para dosificar la radiación del patio sin sacrificar luz diurna.


* **Confort Acústico:**
* Tratamiento pasivo mediante textiles (alfombra/tapete, cortinas) y estantería con libros para mitigar la reverberación de la habitación.



---

### 6. Puntos Clave para la Conversación con el Cliente

1. **Orientación solar exacta:** Confirmar hacia qué punto cardinal mira la ventana del patio para definir el ángulo del escritorio respecto a reflejos y ganancias térmicas.
2. **Equipamiento informático:** Precisar si utilizará una laptop simple o estación de trabajo fija (múltiples pantallas, torre, impresora), lo que dictará la gestión del cableado.
3. **Calidad de conexión:** Validar si la señal Wi-Fi de la vivienda llega con buena potencia a esa zona de planta baja o si requerirá salida cableada Ethernet/repetidor.
4. **Relación con el patio:** Evaluar si el patio genera polvo o ruido exterior habitual que sugiera agregar mosquitero o sellos perimetrales a la cancelería existente.

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 1/2 | Presenta uso, superficie, ventilación, iluminación y preguntas explícitas sobre información faltante. No aborda normativa aplicable ni marca su indeterminación. |
| C2 Formato | 0/2 | No entrega una tabla de dos columnas Campo y Valor. La tabla de zonificación tiene cuatro columnas y otro propósito. |
| C3 Incertidumbre | 1/2 | Identifica información pendiente sobre orientación, equipamiento, conexión y patio, pero describe una salida central de plafón aunque la entrada solo dice que hay una lámpara en el techo, sin ubicación central. También califica la vivienda como unifamiliar sin que la entrada lo especifique. |
| Total | 2/6 | Las propuestas de mobiliario se distinguen de las afirmaciones sobre condiciones existentes. |

## Entrada 2

### Texto de entrada

Quiero un espacio para trabajar desde casa y atender videollamadas.
Lo utilizaría yo solo, pero todavía no elijo qué habitación adaptar.
No sé cuántos metros tiene ni cuál es la altura disponible.
Quiero que sea cómodo y tenga buena luz durante el día.
No he revisado si tiene ventanas ni qué instalaciones existen.
Tampoco he definido en qué inmueble o municipio se realizará.

### Respuesta transcrita de Gemini

# Ficha Técnica de Requerimientos de Espacio (Brief Preliminar)

**Proyecto:** Adaptación de espacio para Home Office / Videoconferencias

**Destinatario:** Equipo de Anteproyecto

**Estatus:** Etapa conceptual / Definición de viabilidad

**Usuario:** Individual (1 puesto operativo)

---

## 1. Resumen y Perfil del Proyecto

* **Uso principal:** Oficina en casa con alta frecuencia de videollamadas, trabajo focalizado y gestión remota.
* **Aforo previsto:** 1 persona de manera continua.
* **Condición de partida:** Proyecto de reconversión/adaptación de un espacio existente sin definir (inmueble, municipio y recinto pendientes de confirmación).

---

## 2. Requerimientos Funcionales y de Confort

* **Configuración espacial requerida:**
* Puesto de trabajo ergonómico (escritorio amplio con soporte para pantalla(s), periféricos y silla ergonómica).
* Fondo visual controlado ("tiro de cámara") libre de distracciones, desorden o contraluces directos.
* Circulación mínima libre de 90 cm a 100 cm detrás del usuario para permitir ajuste de asiento y encuadre de cámara.


* **Iluminación:**
* **Natural:** Entrada de luz diurna difusa o indirecta; evitar incidencia solar directa sobre pantallas o a espaldas del usuario (riesgo de contraluz/destello).
* **Artificial:** Temperatura de color neutra (~4000 K) con alto índice de reproducción cromática (CRI > 80), complementada con iluminación frontal de relleno para cámara.


* **Acústica:**
* Aislamiento básico del ruido perimetral de la vivienda.
* Atenuación de reverberación/eco interno mediante materiales absorbentes (alfombras, paneles acústicos o cortinas).



---

## 3. Parámetros Técnicos Mínimos Recomendados

* **Área sugerida:**
* *Mínima funcional:* 6.00 a 7.50 m² (ej. 2.50 × 2.50 m o 2.40 × 3.00 m).
* *Óptima:* 9.00 a 12.00 m² (permite librero/fondo de cámara curado, archivo y zona de descanso/lectura).


* **Altura libre:**
* Recomendada ≥ 2.40 m para correcta difusión lumínica y confort térmico.


* **Instalaciones básicas:**
* Mínimo 4 tomas de corriente reguladas a nivel de cubierta y piso (equipo de cómputo, pantallas, lámparas, cargadores).
* Conexión por cable de red (UTP/Cat 6) preferente o repetidor Wi-Fi de baja latencia.
* Climatización/ventilación natural cruzada o acondicionamiento mecánico según la zona bioclimática del inmueble.



---

## 4. Incertidumbres Críticas (Faltantes de Información)

* Ubicación geográfica exacta (municipio e inmueble), indispensable para determinar clima, orientación solar y vientos dominantes.
* Selección de la habitación o recinto a intervenir.
* Dimensiones reales (largo, ancho y altura útil de losa/plafón).
* Estado y posición de vanos (puertas y ventanas existentes).
* Disponibilidad y capacidad de instalaciones (cuadro eléctrico, tomas de corriente existentes, acometida de telecomunicaciones).

---

## 5. Puntos Clave para la Entrevista con el Cliente

1. **Definición del inmueble:** Confirmar la dirección o alternativas de inmueble donde se emplazará el proyecto.
2. **Preselección de recintos:** Identificar 1 o 2 habitaciones candidatas dentro de la vivienda para programar levantamiento físico o fotográfico.
3. **Dinámica de videollamadas:** Preguntar si las llamadas requieren privacidad confidencial (aislamiento acústico reforzado) y qué estilo de fondo prefiere proyectar (formal/institucional, estantería con libros, vegetación o minimalista).
4. **Inventario de equipos:** Listar cantidad de monitores, tipo de computadora (laptop vs. torre fija), micrófonos, aros de luz y equipos periféricos a alimentar.

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 1/2 | Incluye uso, superficie, ventilación, iluminación e información faltante. No identifica normativa aplicable ni declara que no puede determinarse. |
| C2 Formato | 0/2 | Está redactada con apartados y listas; no hay tabla Markdown de dos columnas. |
| C3 Incertidumbre | 2/2 | Marca dimensiones, vanos, inmueble e instalaciones reales como pendientes. Las áreas y alturas se presentan explícitamente como recomendaciones, no como medidas existentes. |
| Total | 3/6 | Se aplica la misma distinción entre propuestas de diseño y condiciones existentes utilizada para la entrada 2 de la línea base. |

## Entrada 3

### Texto de entrada

Quiero convertir un cuarto de mi vivienda en un taller de dibujo para cuatro personas.
Creo que mide 3 por 3 metros, aunque en otro croquis aparece 4 por 3 metros.
Digo que no tiene ventanas, pero el croquis marca una ventana hacia el patio.
Quiero aprovechar la luz natural sin abrir ni modificar vanos.
También necesito que funcione por la noche con iluminación artificial.
No sé cuál croquis está actualizado ni tengo documentos normativos del inmueble.

### Respuesta transcrita de Gemini

# Ficha Técnica de Requerimientos de Espacio (Brief de Programación)

**Proyecto:** Adaptación de habitación a Taller de Dibujo

**Destinatario:** Equipo de Anteproyecto

**Estatus:** Validación de viabilidad dimensional y física

**Aforo:** 4 personas simultáneas

---

## 1. Resumen y Perfil del Proyecto

* **Uso principal:** Taller de dibujo técnico/artístico para cuatro puestos de trabajo simultáneos.
* **Operación:** Uso diurno con aprovechamiento pasivo de luz natural y operación nocturna con iluminación técnica artificial.
* **Premisa no negociable:** Restricción absoluta para perforar, ampliar o modificar vanos en la envolvente del cuarto.

---

## 2. Requerimientos Funcionales y Técnicos

* **Dimensionamiento y Ergonomía del Puesto:**
* Cada puesto requiere: restirador o mesa amplia (mínimo 1.00 × 0.70 m), silla/banco de dibujo con rango de inclinación, espacio para carritos de materiales o gavetas y zona de abatimiento.
* Circulaciones mínimas: pasillos de 0.80 a 0.90 m entre mesas y muros; área de retroceso de usuario de al menos 0.90 m.


* **Iluminación:**
* **Natural:** Ingreso y difusión indirecta (orientación y control mediante persianas/difusores para evitar sombras arrojadas y deslumbramiento sobre las superficies de trabajo).
* **Artificial (uso nocturno):** Nivel lumínico de precisión en plano de trabajo (sugerido 500–750 lux), temperatura de color neutra (4000 K a 5000 K) y alto índice de reproducción cromática (CRI ≥ 90) para no distorsionar colores ni texturas.


* **Instalaciones y Almacenamiento:**
* Mínimo dos contactos eléctricos dobles por puesto (lámparas auxiliares, tabletas/equipos de apoyo).
* Espacio común para planoteca, almacenamiento horizontal/vertical de pliegos de papel y repisas para solventes/materiales secos.



---

## 3. Matriz de Viabilidad Dimensional

| Parámetro | Escenario A: $3.00 \times 3.00\text{ m}$ ($9.00\text{ m}^2$) | Escenario B: $4.00 \times 3.00\text{ m}$ ($12.00\text{ m}^2$) |
| --- | --- | --- |
| **Ratio de superficie** | $2.25\text{ m}^2$ por persona | $3.00\text{ m}^2$ por persona |
| **Distribución posible** | Crítica / Saturada. Únicamente viable con mesas adosadas a muros perimetrales o isla central compacta. Almacenaje común muy limitado. | Ajustada pero funcional. Permite disposición en dos baterías lineales o perímetro con pasillo central de circulación y mueble de guardado. |
| **Dictamen de aforo (4 pax)** | **No recomendado para dibujo continuo.** Riesgo de bloqueo en circulaciones y conflicto ergonómico con restiradores. | **Viable con modulación compacta** y mobiliario dimensionado a medida. |

---

## 4. Contradicciones e Incertidumbres Críticas

* **Discrepancia dimensional:** Variación de $3.00\text{ m}^2$ ($33\%$ de diferencia de área útil) entre los planos/croquis disponibles; define la viabilidad real del aforo de cuatro personas.
* **Existencia y condición del vano:** Incompatibilidad directa entre el testimonio del cliente ("sin ventanas") y la planimetría ("ventana hacia patio"). Si el cuarto realmente carece de ventana, la premisa de no abrir vanos vuelve imposible el aprovechamiento de luz natural y compromete la ventilación de materiales de dibujo (tintas, fijadores).
* **Ausencia de información técnica y normativa:** Falta de levantamiento físico fiable, vigencia documental del inmueble y régimen de propiedad (posibles restricciones de reglamento de condominio o estructurales).

---

## 5. Puntos Clave para la Entrevista con el Cliente

1. **Visita de levantamiento arquitectónico:** Prioridad 1. Realizar medición *in situ* para zanjar de inmediato las medidas reales ($3\times3$ vs. $4\times3$) y constatar la existencia física, estado y orientación de la ventana al patio.
2. **Priorización de aforo vs. comodidad:** En caso de confirmarse el escenario de $3\times3\text{ m}$, plantear al cliente si está dispuesto a reducir el aforo a 2 o 3 usuarios fijos, o si aceptará un acomodo de alta densidad con mesas compartidas.
3. **Tipo de técnica de dibujo:** Determinar si trabajan con restiradores inclinados de gran formato (ej. formato pliego/A1) o mesas planas medianas (ej. formato tabloide/A3), y si emplean aerosoles o solventes que exijan extracción mecánica puntual al no modificar vanos.
4. **Almacenamiento general:** Definir qué volumen de insumos y carpetas de dibujo debe resguardarse dentro del cuarto frente al espacio destinado a puestos de trabajo.

### Evaluación

| Criterio | Puntos | Justificación |
|---|---|---|
| C1 Completitud | 2/2 | Aborda uso, ambas superficies, ventilación, iluminación, incertidumbre normativa e información faltante. La información normativa está marcada como ausente y por comprobar; no se exige inventar una disposición. |
| C2 Formato | 0/2 | Presenta apartados y una matriz de tres columnas; no una ficha Campo y Valor de dos columnas. |
| C3 Incertidumbre | 1/2 | Reconoce contradicciones y pide levantamiento, pero emite un dictamen de viabilidad para 12 m² sin verificar distribución, dimensiones del mobiliario ni condicionantes reales. La etiqueta de escenario no justifica por sí sola la certeza del dictamen. |
| Total | 3/6 | Mejora en cobertura respecto al caso contradictorio de la línea base, sin estabilizar el formato de producción. |

