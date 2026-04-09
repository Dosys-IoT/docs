<div style="margin-top: 140px;"></div>

<div align="center">
  <img src="./imgs/upc-logo.png" alt="Logo de UPC" width="120" />
</div>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<p align="center">Ingeniería de Software</p>
<p align="center">Periodo 2610</p>
<p align="center">1ASI0572 | Desarrollo de Soluciones IoT</p>
<p align="center"><strong>NRC:</strong> 6770</p>
<p align="center"><strong>Docente:</strong> Javier Antonio Prudencio Vidal</p>


# <p align="center">Informe del Trabajo Final</p>
<p align="center"><strong>Startup:</strong> Dosys</p>
<p align="center"><strong>Producto:</strong> Dosys</p>

### Integrantes:

| Código | Nombres y Apellidos |
|----------------------|--------|
| U202121584<br/>U202310222<br/>U20211G671<br/>U20201b298<br/>U202310636 | Martel Zevallos, Gabriel Aristóteles<br/>Oblitas Davila, Mariano Moises<br/>Qqueso Rodriguez, Britney Delhy<br/>Ybañez Esquerre, Miguel Angel<br/>Zúñiga Murillo, Diego Sebastián |
<p align="center"><strong>Abril 2026</strong></p>

<div style="page-break-before: always;"></div>

# Registro de versiones del informe
| Versión | Fecha | Autores | Descripción |
| :---- | :---- | :---- | :---- |
| AV1 | 18/09/2026 | Miguel Ybañez Mariano Oblitas Britney Qqueso Diego Soto Gabriel Martel | Carátula, Registro de Versiones del Informe, Project Report Collaboration Insights, Contenido, Student Outcome, Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Solution Software Design, avance de Conclusiones, Bibliografía y Anexos |
| TB1 | 10/10/2026 | Miguel Ybañez Mariano Oblitas Britney Qqueso Diego Soto Gabriel Martel | Versión corregida y mejorada de lo anterior, actualización de Registro de Versiones del Informe, Project Report Collaboration Insights y Student Outcome, implementación y despliegue de la primera versión del Landing Page y Frontend Web Applications, además de Capítulo V: Solution UI/UX Design y Capítulo VI: Product Implementation, Validation & Deployment con 6.1 y 6.2.1 Sprint 1, más Conclusiones, Bibliografía y Anexos |
| AV2 | 14/11/2026 | Miguel Ybañez Mariano Oblitas Britney Qqueso Diego Soto Gabriel Martel | Versión actualizada y mejorada de entregables previos, nueva versión desplegada del Landing Page y Web Applications, primera versión de otras aplicaciones del alcance, además de 6.2.2 Sprint 2, 6.3 Validation Interviews, 6.4 Video About-the-Product, más Conclusiones, Bibliografía y Anexos |
| TB2 | 02/12/2026 | Miguel Ybañez Mariano Oblitas Britney Qqueso Diego Soto Gabriel Martel | Versión final y corregida de todo el informe, actualización de Registro de Versiones del Informe, Project Report Collaboration Insights y Student Outcome, versión final desplegada de las aplicaciones del alcance, inclusión de todos los capítulos y evidencias del cierre del ciclo de vida del proyecto, además de 6.2.3 Sprint 3, Conclusiones, Bibliografía y Anexos |

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 5: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

**Student Outcome**

| Criterio específico | Acciones realizadas | Conclusiones |
| ----- | ----- | ----- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** |  |  |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** |  |  |

# Tabla de Contenidos

* [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
* [Project Report Collaboration Insights](#project-report-collaboration-insights)
* [Contenido](#contenido)
* [Student Outcome](#student-outcome)

* [Capítulo I: Introducción](#capítulo-i-introducción)

  * [1.1. Startup Profile](#11-startup-profile)

    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

  * [1.2. Solution Profile](#12-solution-profile)

    * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    * [1.2.2. Lean UX Process](#122-lean-ux-process)

      * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)

  * [1.3. Segmentos objetivo](#13-segmentos-objetivo)

* [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

  * [2.1. Competidores](#21-competidores)

    * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)

  * [2.2. Entrevistas](#22-entrevistas)

    * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)

  * [2.3. Needfinding](#23-needfinding)

    * [2.3.1. User Personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    * [2.3.4. Empathy Mapping](#234-empathy-mapping)

  * [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
  * [2.5. Ubiquitous Language](#25-ubiquitous-language)

* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

  * [3.1. User Stories](#31-user-stories)
  * [3.2. Impact Mapping](#32-impact-mapping)
  * [3.3. Product Backlog](#33-product-backlog)

* [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)

  * [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)

    * [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)

      * [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      * [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      * [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)

    * [4.1.2. Context Mapping](#412-context-mapping)

    * [4.1.3. Software Architecture](#413-software-architecture)

      * [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      * [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      * [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
      * [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)

  * [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)

    * [4.2.1. Bounded Context: Access](#421-bounded-context-access)
      * [4.2.1.1. Domain Layer](#4211-domain-layer)
      * [4.2.1.2. Interface Layer](#4212-interface-layer)
      * [4.2.1.3. Application Layer](#4213-application-layer)
      * [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      * [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      * [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        * [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        * [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)

    * [4.2.2. Bounded Context: Medication](#422-bounded-context-medication)
      * [4.2.2.1. Domain Layer](#4221-domain-layer)
      * [4.2.2.2. Interface Layer](#4222-interface-layer)
      * [4.2.2.3. Application Layer](#4223-application-layer)
      * [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
      * [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      * [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
        * [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
        * [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)

    * [4.2.3. Bounded Context: Device](#423-bounded-context-device)
      * [4.2.3.1. Domain Layer](#4231-domain-layer)
      * [4.2.3.2. Interface Layer](#4232-interface-layer)
      * [4.2.3.3. Application Layer](#4233-application-layer)
      * [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
      * [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      * [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
        * [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
        * [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)

* [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)

  * [5.1. Style Guidelines](#51-style-guidelines)

    * [5.1.1. General Style Guidelines](#511-general-style-guidelines)
    * [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)

  * [5.2. Information Architecture](#52-information-architecture)

    * [5.2.1. Organization Systems](#521-organization-systems)
    * [5.2.2. Labeling Systems](#522-labeling-systems)
    * [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    * [5.2.4. Searching Systems](#524-searching-systems)
    * [5.2.5. Navigation Systems](#525-navigation-systems)

  * [5.3. Landing Page UI Design](#53-landing-page-ui-design)

    * [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
    * [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)

  * [5.4. Applications UX/UI Design](#54-applications-uxui-design)

    * [5.4.1. Applications Wireframes](#541-applications-wireframes)
    * [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
    * [5.4.2. Applications Mock-ups](#542-applications-mock-ups)
    * [5.4.3. Applications User Flow Diagrams](#543-applications-user-flow-diagrams)

  * [5.5. Applications Prototyping](#55-applications-prototyping)
  * [5.6. IoT Device Design](#56-iot-device-design)

* [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)

  * [6.1. Software Configuration Management](#61-software-configuration-management)

    * [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    * [6.1.2. Source Code Management](#612-source-code-management)
    * [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
    * [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)

  * [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)

    * [6.2.X. Sprint n](#62x-sprint-n)

      * [6.2.X.1. Sprint Planning n](#62x1-sprint-planning-n)
      * [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
      * [6.2.X.3. Sprint Backlog n](#62x3-sprint-backlog-n)
      * [6.2.X.4. Development Evidence for Sprint Review](#62x4-development-evidence-for-sprint-review)
      * [6.2.X.5. Testing Suite Evidence for Sprint Review](#62x5-testing-suite-evidence-for-sprint-review)
      * [6.2.X.6. Execution Evidence for Sprint Review](#62x6-execution-evidence-for-sprint-review)
      * [6.2.X.7. Services Documentation Evidence for Sprint Review](#62x7-services-documentation-evidence-for-sprint-review)
      * [6.2.X.8. Software Deployment Evidence for Sprint Review](#62x8-software-deployment-evidence-for-sprint-review)
      * [6.2.X.9. Team Collaboration Insights during Sprint](#62x9-team-collaboration-insights-during-sprint)

  * [6.3. Validation Interviews](#63-validation-interviews)

    * [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
    * [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
    * [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)

  * [6.4. Video About-the-Product](#64-video-about-the-product)

* [Conclusiones](#conclusiones)

  * [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  * [Video About-the-Team](#video-about-the-team)

* [Bibliografía](#bibliografía)
* [Anexos](#anexos)

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos Dosys, una startup conformada por estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con el desarrollo de soluciones tecnológicas orientadas al bienestar, la autonomía y la calidad de vida de las personas adultas mayores.

Nuestra misión es diseñar una solución IoT accesible y confiable que ayude a organizar tratamientos farmacológicos, reducir olvidos en la toma de medicamentos y mejorar el seguimiento cotidiano de rutinas de medicación en el hogar, integrando hardware, software y monitoreo de condiciones ambientales.

Nuestra visión es convertirnos en una propuesta referente en el ámbito de la asistencia tecnológica para el cuidado domiciliario de adultos mayores en el Perú, ofreciendo un producto que combine usabilidad, prevención, acompañamiento familiar y monitoreo inteligente bajo una experiencia simple, clara y segura.

Nuestro producto principal es Dosys, un pastillero inteligente premium de cinco compartimentos, diseñado para administrar hasta cinco medicamentos distintos. El sistema permite configurar tratamientos desde una aplicación, asignar medicamentos a compartimentos específicos, definir horarios, duración del tratamiento y reglas de alerta. Cuando corresponde una toma, el dispositivo reproduce un recordatorio por voz, enciende el LED del compartimento asignado y permite al usuario confirmar la toma o repetir la alerta mediante botones físicos.

Además del recordatorio programado, Dosys supervisa la temperatura y humedad del entorno donde se almacenan los medicamentos, con el fin de advertir condiciones que puedan comprometer su adecuada conservación. La solución también contempla alertas para recarga de compartimentos, aviso de compra de medicamento y notificación para vaciar o limpiar compartimentos al finalizar un tratamiento, todo ello en función de la configuración registrada previamente por el usuario o su cuidador.

Dosys no busca reemplazar la supervisión médica ni verificar la ingesta real del medicamento. Su propuesta de valor se centra en reducir errores cotidianos de organización, mejorar la adherencia al tratamiento mediante recordatorios físicos y digitales, y ofrecer un apoyo tecnológico práctico para el cuidado en casa.

### 1.1.2. Perfiles de integrantes del equipo

| Nombre: Ybañez Esquerre, Miguel Angel | <img src="imgs/Miguel.jpg" alt="Miguel" title="Foto de Miguel" width="520"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U20201B298|                               |
| **Carrera:** Ingeniería de Software    |                               |
| **Habilidades:** Miguel Ángel Ybañez Esquerre – Estudiante de 23 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, capacidad analítica y enfoque práctico para resolver problemas. Apasionado por el desarrollo web y los agentes de inteligencia artificial, con experiencia en desarrollo de videojuegos en Unity y realidad virtual con Meta Quest. Siempre en búsqueda de explorar nuevas tecnologías y llevar las ideas a soluciones reales. |                               |

| Nombre: Oblitas Davila, Mariano Moises | <img src="imgs/Mariano.png" alt="Mariano" title="Foto de Mariano" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202310222  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Estudiante de 20 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, eficacia y capacidad para resolver problemas de manera racional. Apasionado por la programación y el desarrollo de software, busco constantemente innovar y aprender nuevas tecnologías. |          |

| Nombre: Qqueso Rodriguez, Britney Delhy| <img src="imgs/Britney.jpg" alt="Britney" title="Foto de Britney" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U20211G671      |                               |
| **Carrera:** Ingeniería de Software     |                               |
| **Habilidades:** Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona autodidacta, creativa, organizada y responsable. Me comprometo a contribuir al equipo con mis conocimientos y habilidades, apoyar en todo lo necesario y aprender en el proceso. |        |

| Nombre: Zúñiga Murillo, Diego Sebastián    | <img src="imgs/Diego.jpg" alt="Diego" title="Foto de Diego" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202310636  |   |
| **Carrera:** Ingeniería de Software   |   |
| **Habilidades:** Mi nombre es Diego Sebastián Zúñiga Murillo, tengo 21 años y actualmente curso el séptimo ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona puntual, participativa y responsable, con una fuerte pasión por la tecnología y el aprendizaje constante. En mi tiempo libre disfruto de escuchar música, lo que me ayuda a relajarme y mantener el equilibrio entre mis estudios y mi vida personal. Como estudiante, me comprometo a aportar activamente en el desarrollo de este proyecto, contribuyendo con creatividad, iniciativa y habilidades de liderazgo. Confío en que, trabajando en equipo y manteniendo una comunicación constante, lograremos resultados destacados que reflejan nuestro esfuerzo y compromiso. |   |

| Nombre: Martel Zevallos, Gabriel Aristóteles  | <img src="imgs/Gabriel.jpg" alt="Gabriel" title="Foto de Gabriel" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202121584
|     |
| **Carrera:** Ingeniería de Software |       |
| **Habilidades:** Integrante del equipo Dosys. Participa en las actividades de investigación, análisis y construcción de la solución IoT, contribuyendo al trabajo colaborativo del proyecto. |      |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

##### **¿Cuál es el problema?**

La gestión de medicamentos en personas adultas mayores constituye un problema relevante de salud y de uso cotidiano. En el Perú, las personas de 60 y más años representan el 14,1% de la población, y 59,7% de este grupo presenta al menos una comorbilidad; entre las más frecuentes se encuentran la hipertensión arterial y la diabetes mellitus. En paralelo, la OMS ha señalado que, en enfermedades crónicas, la adherencia a tratamientos de largo plazo promedia apenas 50% en países desarrollados, y suele ser menor en contextos con más barreras de acceso y seguimiento. En ese escenario, los adultos mayores que deben cumplir esquemas farmacológicos diarios enfrentan olvidos, confusión entre medicamentos, dificultad para seguir horarios y riesgo de almacenamiento inadecuado en el hogar. (Instituto Nacional de Estadística e Informática [INEI], 2024; World Health Organization [WHO], 2003).

##### **¿Cuándo ocurre el problema?**

El problema ocurre principalmente durante tratamientos crónicos y prolongados, especialmente cuando una persona debe tomar varios medicamentos al día, en horarios distintos, o durante semanas o meses continuos. Esta situación se vuelve más crítica cuando existen cambios cognitivos propios del envejecimiento, disminución de la memoria operativa, dificultades visuales o menor destreza manual. La literatura sobre accesibilidad para usuarios mayores muestra que el envejecimiento afecta visión, motricidad fina, audición y capacidad de concentración, factores que inciden directamente en la correcta interacción con recordatorios, envases y rutinas digitales o físicas. (W3C Web Accessibility Initiative, 2025).

##### **¿Dónde ocurre el problema?**

La problemática ocurre sobre todo en el entorno doméstico, que es donde la mayoría de adultos mayores almacena y administra su medicación. Allí aparecen dos riesgos simultáneos: por un lado, la complejidad del tratamiento; por otro, las condiciones del ambiente. MedlinePlus advierte que el calor, la humedad, el aire y la luz pueden dañar medicamentos, y recomienda almacenarlos en lugares frescos y secos; además, señala que el baño no es un lugar adecuado por la humedad y el calor. Esto justifica que una solución como Dosys no solo recuerde la toma, sino que también supervise condiciones básicas de conservación del medicamento. (U.S. National Library of Medicine, n.d.).

##### **¿A quién afecta el problema?**

El problema afecta de forma directa a adultos mayores que viven con una o varias enfermedades crónicas y que deben seguir tratamientos farmacológicos continuos. También afecta a familiares y cuidadores, quienes frecuentemente asumen la supervisión de horarios, recargas y reposición de medicamentos. De manera indirecta, impacta al sistema de salud, porque la no adherencia se asocia con peores resultados clínicos, más hospitalizaciones y mayores costos de atención. En Perú, además, parte importante de esta población presenta discapacidad o limitaciones funcionales, lo que incrementa la necesidad de soluciones accesibles y simples de usar. (INEI, 2023, 2024; Walsh et al., 2019).

##### **¿Por qué sucede el problema?**

El problema sucede por una combinación de factores: polifarmacia, complejidad de los esquemas terapéuticos, olvidos, barreras físicas o cognitivas, y herramientas insuficientes para el seguimiento cotidiano. La polifarmacia es altamente prevalente en adultos mayores y se asocia con consecuencias clínicas adversas, interacciones medicamentosas, errores y mayor complejidad de manejo. A ello se suma que muchas soluciones tradicionales, como pastilleros genéricos sin alarma ni apoyo contextual, no ofrecen trazabilidad, no diferencian bien eventos de toma y no consideran condiciones ambientales ni necesidades de accesibilidad. (Pazan & Wehling, 2021; W3C Web Accessibility Initiative, 2025).

##### **¿Cómo sucede el problema?**

En la práctica, el problema se manifiesta cuando la persona olvida una dosis, la retrasa, la duplica o confunde compartimentos y horarios. También ocurre cuando un cuidador no tiene visibilidad clara de qué medicamento correspondía tomar o cuándo debe reponerse un compartimento. La evidencia disponible muestra que los recordatorios electrónicos y los dispositivos de empaque o dispensación con soporte electrónico pueden mejorar la adherencia, especialmente cuando el problema central incluye el olvido y la organización cotidiana de la medicación. Esto respalda la lógica funcional de Dosys como dispositivo híbrido de recordatorio por voz, alerta visual, confirmación física y configuración digital. (Vervloet et al., 2012; Checchi et al., 2014).

##### **¿Cuán grande es el impacto de este problema?**

El impacto es alto en términos clínicos, familiares y operativos. Una revisión sistemática y metaanálisis en población envejecida encontró que la no adherencia a la medicación se asocia significativamente con mayor hospitalización por todas las causas, y que una buena adherencia se relaciona con una reducción del riesgo de mortalidad a largo plazo. Además, revisiones más recientes sobre consecuencias clínicas y económicas muestran que la no adherencia suele empeorar resultados de salud y elevar costos sanitarios. En el caso peruano, el crecimiento sostenido de la población adulta mayor y su alta carga de comorbilidad convierten este problema en una oportunidad clara para soluciones preventivas, domiciliarias y centradas en la usabilidad. (Walsh et al., 2019; Cutler et al., 2025; INEI, 2024).

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

*Pendiente de desarrollo en la siguiente etapa del proyecto.*

#### 1.2.2.2. Lean UX Assumptions

*Pendiente de desarrollo en la siguiente etapa del proyecto.*

#### 1.2.2.3. Lean UX Hypothesis Statements

*Pendiente de desarrollo en la siguiente etapa del proyecto.*

#### 1.2.2.4. Lean UX Canvas

*Pendiente de desarrollo en la siguiente etapa del proyecto.*

## 1.3. Segmentos objetivo
#### **Adultos mayores con tratamientos farmacológicos crónicos**

Este es el segmento objetivo principal de Dosys. Incluye a personas de *60 años o más* que requieren tomar medicamentos de manera recurrente para controlar una o varias enfermedades crónicas, y que necesitan apoyo para recordar horarios, identificar compartimentos, confirmar tomas y mantener una rutina más organizada dentro del hogar. En Perú, este grupo crece de forma sostenida y presenta una elevada carga de comorbilidad, lo que incrementa la necesidad de herramientas prácticas para apoyar la adherencia terapéutica. (INEI, 2024).

Características:

* Requieren tratamientos continuos o de larga duración.
* Pueden tomar varios medicamentos al día o en distintos horarios.
* Valoran interacciones simples, visibles y fáciles de comprender.
* Pueden presentar dificultades visuales, auditivas, motoras o de memoria que afectan el seguimiento del tratamiento.
* Se benefician de recordatorios multimodales, como voz, luz y botones físicos. (W3C Web Accessibility Initiative, 2025).

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming
## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming
#### 4.1.1.1. Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram
#### 4.1.3.2. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams
#### 4.1.3.3. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: Access
#### 4.2.1.1. Domain Layer
#### 4.2.1.2. Interface Layer
#### 4.2.1.3. Application Layer
#### 4.2.1.4. Infrastructure Layer
#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.1.6.2. Bounded Context Database Design Diagram

### 4.2.2. Bounded Context: Medication
#### 4.2.2.1. Domain Layer
#### 4.2.2.2. Interface Layer
#### 4.2.2.3. Application Layer
#### 4.2.2.4. Infrastructure Layer
#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.2.6.2. Bounded Context Database Design Diagram

### 4.2.3. Bounded Context: Device
#### 4.2.3.1. Domain Layer
#### 4.2.3.2. Interface Layer
#### 4.2.3.3. Application Layer
#### 4.2.3.4. Infrastructure Layer
#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.3.6.2. Bounded Context Database Design Diagram

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines
### 5.1.1. General Style Guidelines
### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture
### 5.2.1. Organization Systems
### 5.2.2. Labeling Systems
### 5.2.3. SEO Tags and Meta Tags
### 5.2.4. Searching Systems
### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design
### 5.3.1. Landing Page Wireframe
### 5.3.2. Landing Page Mock-up

## 5.4. Applications UX/UI Design
### 5.4.1. Applications Wireframes
### 5.4.2. Applications Wireflow Diagrams
### 5.4.2. Applications Mock-ups
### 5.4.3. Applications User Flow Diagrams

## 5.5. Applications Prototyping
## 5.6. IoT Device Design

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration
### 6.1.2. Source Code Management
### 6.1.3. Source Code Style Guide & Conventions
### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.X. Sprint n
#### 6.2.X.1. Sprint Planning n
#### 6.2.X.2. Aspect Leaders and Collaborators
#### 6.2.X.3. Sprint Backlog n
#### 6.2.X.4. Development Evidence for Sprint Review
#### 6.2.X.5. Testing Suite Evidence for Sprint Review
#### 6.2.X.6. Execution Evidence for Sprint Review
#### 6.2.X.7. Services Documentation Evidence for Sprint Review
#### 6.2.X.8. Software Deployment Evidence for Sprint Review
#### 6.2.X.9. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews
### 6.3.1. Diseño de Entrevistas
### 6.3.2. Registro de Entrevistas
### 6.3.3. Evaluaciones según heurísticas

## 6.4. Video About-the-Product

# Conclusiones

## Conclusiones y recomendaciones
## Video About-the-Team

# Bibliografía

# Anexos