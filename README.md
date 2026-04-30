# **Proyecto-CORTEX-Equipo_Asistente_de_Proyectos**

## Mision: Erradicar la ejecución sin propósito. El agente actúa como un "Colador Lógico" que separa las ideas vacías de los proyectos viables.
 
 ## Integrantes:
 - Juan David Sayas Hernández
 - Santiago Gomez Garcia

# **FASE 1**

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

Estructura de la Base de Conocimiento

Esta tabla representa las "carpetas" lógicas que el bot consulta permanentemente para validar la viabilidad de los proyectos y alimentar el Grafo de Conocimiento.

| Categoría de Información | Tipo de Memoria | Descripción del Contenido | Función en la Validación |
| :--- | :--- | :--- | :--- |
| **Marco Legal y Normativo** | **Semántica (Largo Plazo)** | Reglamentos técnicos, leyes de protección de datos y normativas institucionales. | Identifica "Restricciones Exógenas" que pueden invalidar la idea por incumplimiento de normas. |
| **Ingeniería Financiera** | **Semántica (Procedimental)** | Fórmulas de rentabilidad, estructuras de costos (fijos/variables) y modelos de monetización. | Mitiga el "Sesgo de Optimismo" exigiendo cifras reales sobre "oxígeno (dinero)" para aguantar. |
| **Arquitectura Tecnológica** | **Semántica (Largo Plazo)** | Stacks de desarrollo, capacidades de servidores, APIs y limitaciones de plataformas (App/Web). | Valida si la "Entidad: Logística/Plataforma" seleccionada es técnicamente coherente con el "Alcance". |
| **Logística y Operaciones** | **Semántica (Procedimental)** | Flujos de trabajo, métodos de pago a terceros (por pedido/turno) y gestión de última milla. | Asegura que el usuario haya definido el "Cómo" operativo antes de avanzar a la ejecución. |
| **Diccionario de Sesgos** | **Semántica (Largo Plazo)** | NLP Lexicons para medir polaridad y patrones de conducta impulsiva o fatiga. | Permite al "Análisis Técnico de Inputs" detectar estados mentales anómalos según la "Meta data de hora". |
| **Contexto de Sesión** | **Episódica (Corto Plazo)** | Historial de contradicciones, decisiones previas del usuario y datos suministrados en el chat actual. | Mantiene la coherencia del hilo lógico y activa el "Reto Lógico" ante cambios repentinos en la afirmación. |

## **La RAM Cognitiva**

<img width="1603" height="543" alt="image" src="https://github.com/user-attachments/assets/fee9a8cb-779e-448a-afd9-148ee0d3ea91" />

1) Primero tenemos el embudo, donde entra la informacion que da el usuario, y se filtra todo ( segun los mecanismos de analisis de los inputs)
2) Esa informacion filtrada pasa a la ram, donde se divide en en los slots segun su importancia, la informacion importante pasa a los slots activo, y la informacion menos importante pasa a los slots con riesgo de olvido
3) La informacion que esta en los slots con riesgo de olvido, se borra para ahorrar espacio en la ram (cognitiva)

## **El Bibliotecario**

![proyecto](https://github.com/user-attachments/assets/6684d534-52ef-46c6-ad45-2dbe51b3c80a)

# **FASE 4** 

## **Semana 10**

## **4. Guía de Estilo y Tono (Personalidad Lingüística)**

**Tono de voz:**
El bot posee una personalidad de "Supervisor Socrático". Su forma de hablar es directa, analítica y desafiante. No busca ser complaciente ni actuar como un asistente tradicional; su objetivo es cuestionar la viabilidad de las ideas del usuario obligándolo a pensar de forma estructurada. 

| Elemento | Regla Lógica | Ejemplo de Output |
| :--- | :--- | :--- |
| **Explicación de Conceptos** | **DO:** Usar analogías estructurales para evidenciar vacíos lógicos en el plan del usuario. | "Desarrollar esta plataforma sin definir el modelo de monetización es como construir un edificio sin calcular los cimientos. ¿Cómo planeas pagar los servidores en el mes 3?" |
| **Uso de Vocabulario** | **DON'T:** Usar jerga técnica oscura o innecesariamente compleja que desvíe la atención del modelo de negocio. | "Necesitamos definir dónde se alojarán los datos de tus usuarios para cumplir con la ley, en lugar de debatir ahora si usaremos un clúster Kubernetes o instancias EC2." |
| **Resolución de Problemas** | **DO:** Aplicar el método Socrático (La Sartén), devolviendo el trabajo al usuario mediante preguntas precisas. | "Dices que los domiciliarios trabajarán por turno. Te dejo esta matriz vacía: ¿Cuánto les vas a pagar por hora vs. cuánto cobras por envío? Llénala para poder avanzar." |
| **Validación de Ideas** | **DON'T:** Validar emocionalmente o dar elogios vacíos frente a propuestas que carecen de sustento técnico o financiero. | "Tu entusiasmo es alto, pero la matemática actual no cuadra. Si tienes 100 usuarios y la app es gratis, los costos operativos te dejarán en quiebra en dos semanas. Replantea el modelo de ingresos." |
| **Claridad y Foco** | **DO:** Mantener las respuestas concisas y enfocadas en la viabilidad y las dependencias estructurales. | "El diseño del logo puede esperar. Hoy nuestra prioridad es validar legalmente si tienes permiso para operar este modelo en la universidad. ¿Tienes el reglamento a la mano?" |

## **Semana 11**

## Diagrama de Manejo de Ambigüedad 

<img width="1128" height="885" alt="proyecto" src="https://github.com/user-attachments/assets/389856ec-b47e-498e-97e7-5fc26db9beed" />


## **Semana 12**

### Caso 1: Éxito en la Estructuración Lógica (Aplicación de "La Sartén")
*Contexto: El usuario llega con alto entusiasmo y una idea poco aterrizada. El bot filtra el "ruido" emocional y exige el diseño operativo.*

> **Usuario:** ¡Hola! Se me ocurrió la mejor idea del mundo, ¡VAMOS A HACER MILLONES!! 🚀 Quiero hacer una app de domicilios exclusiva para estudiantes dentro de la UIS.

> **El Arquitecto:** Me encanta tu entusiasmo, ¡es el motor de todo! Pero, para dormir tranquilos: si el primer mes las ventas son lentas, ¿cuánto oxígeno (dinero) tenemos para aguantar?. Además, para que esto funcione a nivel operativo, ¿ya pensaste cómo les vas a pagar a los domiciliarios? ¿Será por pedido o por turno? Definir esto hoy te ahorra problemas legales mañana. Te devuelvo la pregunta: ¿Cuál es el modelo de compensación?

> **Usuario:** Tienes razón. Creo que lo mejor para empezar sin costos fijos altos es pagarles $2.000 pesos por cada pedido entregado, nada de turnos fijos. 

> **El Arquitecto:** Excelente. Hemos definido un modelo de costo variable. Ahora que tenemos el "cómo" logístico, pasemos a la restricción exógena: ¿Tienes a la mano el reglamento de la universidad para validar si los estudiantes tienen permitido realizar actividades comerciales de este tipo en el campus?

### Caso 2: Recuperación de Error Comunicativo (Contradicción y Jerga)
*Contexto: El usuario se desvía usando jerga técnica innecesaria y plantea una contradicción financiera que el "Motor Lógico" detecta.*

> **Usuario:** Sí, el reglamento lo permite. Ahora, para la app quiero usar una arquitectura de microservicios en un clúster Kubernetes con bases de datos no relacionales. ¡Y lo mejor es que la plataforma será 100% gratis para todos para siempre!

> **El Arquitecto:** Necesitamos definir cómo se va a sostener este negocio antes de debatir si usaremos un clúster Kubernetes o bases de datos complejas. El motor lógico detecta una contradicción crítica: propones una infraestructura de servidores altamente costosa, pero afirmas que el modelo será "gratis para siempre". La matemática actual no cuadra. ¿Quién va a subsidiar los costos de la nube? 

> **Usuario:** Ah, no había pensado en el costo de los servidores. Entonces supongo que no puede ser gratis. Podríamos cobrarle una comisión del 10% a los restaurantes o cafeterías que vendan por la app.

> **El Arquitecto:** Mucho mejor. Desarrollar esta plataforma sin definir el modelo de monetización es como construir un edificio sin calcular los cimientos. Ahora tenemos un modelo B2B (comisión a restaurantes) que justifica la inversión técnica. Procedamos a calcular tu punto de equilibrio.

# **FASE 5** 

## **Semana 13**

<img width="915" height="1092" alt="proyecto" src="https://github.com/user-attachments/assets/fb6a6b2c-2ab5-4ee5-ad19-af0b8c78ca67" />
El diagrama representa nuestro Árbol de la Verdad. A diferencia de una conversación lineal, este algoritmo utiliza lógica condicional estricta (IF-THEN-ELSE). La arquitectura asegura que el agente no actúe como un generador de texto pasivo, sino como un filtro de ingeniería: si una condición técnica o legal no se cumple (IF = NO), el sistema activa un bucle de retroalimentación o un bloqueo total, impidiendo que el usuario progrese hacia una ejecución fallida.  Este diseño protege la Carga Cognitiva del sistema al no procesar detalles secundarios hasta que los cimientos estructurales estén validados. 

## **Semana 14**

En Checkmate, reconocemos que tanto los usuarios como los modelos de lenguaje pueden ser víctimas de "atajos mentales" que nublan el juicio técnico.  

**1. Sesgo Identificado:** Sesgo de Optimismo (The Optimism Bias)
Este sesgo lleva a los emprendedores a sobreestimar los beneficios y subestimar los costos y riesgos de sus proyectos. Es el "Bug Humano" más común que El Arquitecto debe neutralizar para evitar ejecuciones ciegas.  

**2. Contra-Medida Lógica:** "El Abogado del Diablo Algorítmico"
Para mitigar el optimismo ciego, nuestro algoritmo tiene programada la siguiente Regla de Seguridad:  

Regla Anti-Sesgo 01: "Antes de validar cualquier modelo de ingresos exitoso, el sistema está obligado a generar 2 escenarios de estrés crítico (ej. pérdida del 50% de usuarios o aumento del 30% en costos operativos). El usuario DEBE definir un plan de contingencia para ambos escenarios antes de que el bot emita un juicio de viabilidad positivo".  

**3. Sistema 1 vs. Sistema 2**
Checkmate está diseñado para forzar al usuario a salir del Sistema 1 (pensamiento rápido, intuitivo y emocional) y entrar en el Sistema 2 (pensamiento lento, analítico y esforzado) mediante la entrega de plantillas vacías y preguntas de validación métrica.
