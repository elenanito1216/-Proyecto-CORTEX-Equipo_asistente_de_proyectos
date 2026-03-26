# **Proyecto-CORTEX-Equipo_Asistente_de_Proyectos**

## Mision: Erradicar la ejecución sin propósito. El agente actúa como un "Colador Lógico" que separa las ideas vacías de los proyectos viables.
 
 ## Integrantes:
 - Juan David Sayas Hernández
 - Santiago Gomez Garcia

## **1.PERFIL DEL AGENTE**
![proyecto (1)](https://github.com/user-attachments/assets/df86c4ea-f64d-4bd5-a33b-a0a5572129f6)

## **2.RADAR COGNITIVO**
![proyecto  2](https://github.com/user-attachments/assets/ae8ad751-eb05-47f2-8c92-f2c7c1aff5a3)

nuestro asistente se fundamenta en una jerarquía de procesos cognitivos donde el Pensamiento y el Razonamiento (10/10) actúan como el motor central para ejecutar el análisis de dependencias lógicas. Estos procesos se nutren de una Memoria (10/10) semántica y episódica que sostiene el grafo de conocimiento, permitiendo que la IA no solo almacene datos, sino que comprenda las relaciones estructurales entre ellos. Para que esta arquitectura sea funcional, el Procesamiento Lingüístico (9/10) traduce la intención del usuario, mientras que la Atención (8/10) y la Percepción (8/10) filtran los componentes críticos de la idea, ignorando el ruido superficial para centrarse en los vacíos del proyecto. Esta integración de la Cognición (8/10) permite que el sistema mantenga una visión sistémica del desarrollo, apoyándose en un Aprendizaje (7/10) contextual que adapta la lógica de ingeniería a cada caso específico. Finalmente, la Motivación y la Emoción (4/10) se mantienen en una prioridad baja, interviniendo únicamente para regular la interacción humana y evitar la frustración, asegurando que el rigor técnico del razonamiento prevalezca siempre sobre la complacencia emocional.

# **FASE 2**

## **3.BRAINSTORMING**
![proyecto](https://github.com/user-attachments/assets/a7d3bec0-7f94-4e3e-9944-14ead6a7f659)

## **4. FLUJO DE PROCESAMIENTO**
![proyecto 2](https://github.com/user-attachments/assets/e4b93b08-68ed-40e6-8a98-5d6ec0bdae9b)

## **2.Arquitectura de Atención con las reglas lógicas definidas.**

Este módulo formaliza el proceso de "ATENCION" listado entre los procesos cognitivos fundamentales del sistema. Su función es actuar como un filtro inteligente entre los "INPUTS (CRUDOS)" y el núcleo de procesamiento, asegurando una "Atención Selectiva" óptima y protegiendo al modelo de una "Carga Cognitiva" excesiva. Ejecuta el "Análisis Técnico de Inputs" para pasar de la simple sensación a la percepción estructurada.

**Definición de "Ruido"**
Para optimizar los recursos, el Gatekeeper identifica y suprime activamente los siguientes elementos considerados "Ruido":

**Texto de Relleno:** Saludos excesivos, despedidas, y frases de transición que no contienen entidades clave (Sujeto, Objeto, Locación) o un "Intent" claro (informar, crear, consultar).

**Adjetivación Excesiva No Técnica:** Palabras subjetivas de alto impacto emocional (ej: "maravilloso", "terrible", "millones!!") que no definen variables técnicas del proyecto.

**Metadata No Anómala:** Datos de contexto (como la hora) que caen dentro de patrones normales de operación y no indican desviaciones cognitivas como "Impulsividad o fatiga".

**Elementos Decorativos en Archivos:** Gráficos, layouts, o texto no funcional identificados por el "Layout Analysis" en PDFs o Excel que no representan cláusulas, restricciones o variables técnicas directas.

**Reglas de Atención**
Las siguientes reglas determinan cómo el Gatekeeper prioriza la información y gestiona la carga de trabajo:

**Regla de Economía de Carga (Saturación de Texto):** Si un mensaje de "TEXTO CRUDO" excede las 500 palabras, el mecanismo de atención aplicará automáticamente "Semantic Chunking" para priorizar exclusivamente los sustantivos clave extraídos por "Named Entity Recognition" y la última frase del mensaje para determinar el "Intent" final.

**Regla de Priorización de Entidades Clave:** El filtro de atención asignará la máxima puntuación de procesamiento a las entidades identificadas como directores técnicos del proyecto (ej: "plataforma", "logística", "alcance"), deprioritizando el contexto narrativo circundante.

**Regla de Activación por Anomalía Temporal:** El "Temporal Pattern Analysis" solo alertará al Gatekeeper si detecta una anomalía crítica en el ciclo de trabajo (ej: creación a las "03:45 AM"). En caso de detección, se incrementará la atención sobre posibles sesgos cognitivos en el mensaje.

**Regla de Filtrado Semántico de Archivos:** Para "Archivos (pdfs, presupuestos, etc.)", el Gatekeeper ignorará cualquier chunk de datos que no esté explícitamente indexado por el "Layout Analysis" como una "Restricción Exógena" o variable técnica.

**Regla de Gestión de Sesgo (Polaridad de Tono/Emojis):** Al procesar "Tono de Voz / Emojis", el Gatekeeper utilizará "NLP Lexicons" para cuantificar la polaridad. Si la polaridad positiva es extrema y no está respaldada por datos técnicos, la atención se enfocará en buscar datos que mitiguen un posible "Sesgo de Optimismo". Si no se detecta polaridad significativa, este input se trata como ruido de baja prioridad.

# **FASE 3**

## **3. Arquitectura de Memoria**

### 🗄️ Estructura de la Base de Conocimiento (Memoria Semántica)

Esta tabla representa las "carpetas" lógicas que el bot consulta permanentemente para validar la viabilidad de los proyectos y alimentar el Grafo de Conocimiento.

| Categoría de Memoria | Descripción del Contenido | Ejemplo de Datos Indexados | Función en la Validación |
| :--- | :--- | :--- | :--- |
| **Marco Legal y Normativo** | Reglamentos y restricciones legales vigentes. | Reglamento de Ventas UIS, Habeas Data, Normas de Sanidad. | Identifica "Restricciones Exógenas" que pueden detener el avance del proyecto. |
| **Ingeniería Financiera** | Fórmulas y modelos de sostenibilidad económica. | CAC (Costo de Adquisición), LTV, Punto de Equilibrio. | Detecta "Sesgos de Optimismo" al contrastar la idea con la realidad financiera. |
| **Arquitectura Tecnológica** | Catálogo de herramientas y stacks de desarrollo. | AWS, Firebase, Flutter, APIs de Geolocalización. | Valida si la "Entidad: Plataforma" elegida es técnicamente coherente con el alcance. |
| **Logística y Operaciones** | Modelos de flujo de trabajo y gestión de recursos. | Gestión de última milla, Algoritmos de despacho, Tipos de pago. | Verifica la coherencia operativa (ej. "¿Cómo les vas a pagar a los domiciliarios?"). |
| **Psicología y Sesgos** | Diccionarios de polaridad y patrones conductuales. | NLP Lexicons, Lista de Sesgos Cognitivos, Indicadores de Fatiga. | Permite al "Análisis Técnico de Inputs" detectar estados de impulsividad o exceso de confianza. |
| **Benchmarks de Mercado** | Datos de referencia y modelos de monetización. | Estructuras de costos de competencia, tasas de conversión estándar. | Sirve de base para que el bot exija definiciones claras sobre la ventaja competitiva. |
