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

| Nombre: Ybañez Esquerre, Miguel Angel | <img src="imgs/team/miguel.jpg" alt="Miguel" title="Foto de Miguel" width="520"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U20201B298|                               |
| **Carrera:** Ingeniería de Software    |                               |
| **Habilidades:** Miguel Ángel Ybañez Esquerre – Estudiante de 23 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, capacidad analítica y enfoque práctico para resolver problemas. Apasionado por el desarrollo web y los agentes de inteligencia artificial, con experiencia en desarrollo de videojuegos en Unity y realidad virtual con Meta Quest. Siempre en búsqueda de explorar nuevas tecnologías y llevar las ideas a soluciones reales. |                               |

| Nombre: Oblitas Davila, Mariano Moises | <img src="imgs/team/mariano.png" alt="Mariano" title="Foto de Mariano" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202310222  |                               |
| **Carrera:** Ingeniería de Software |                               |
| **Habilidades:** Estudiante de 20 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, eficacia y capacidad para resolver problemas de manera racional. Apasionado por la programación y el desarrollo de software, busco constantemente innovar y aprender nuevas tecnologías. |          |

| Nombre: Qqueso Rodriguez, Britney Delhy| <img src="imgs/team/britney.jpg" alt="Britney" title="Foto de Britney" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U20211G671      |                               |
| **Carrera:** Ingeniería de Software     |                               |
| **Habilidades:** Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona autodidacta, creativa, organizada y responsable. Me comprometo a contribuir al equipo con mis conocimientos y habilidades, apoyar en todo lo necesario y aprender en el proceso. |        |

| Nombre: Zúñiga Murillo, Diego Sebastián    | <img src="imgs/team/diego.jpg" alt="Diego" title="Foto de Diego" width="320"/> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------- |
| **Código:** U202310636  |   |
| **Carrera:** Ingeniería de Software   |   |
| **Habilidades:** Mi nombre es Diego Sebastián Zúñiga Murillo, tengo 21 años y actualmente curso el séptimo ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona puntual, participativa y responsable, con una fuerte pasión por la tecnología y el aprendizaje constante. En mi tiempo libre disfruto de escuchar música, lo que me ayuda a relajarme y mantener el equilibrio entre mis estudios y mi vida personal. Como estudiante, me comprometo a aportar activamente en el desarrollo de este proyecto, contribuyendo con creatividad, iniciativa y habilidades de liderazgo. Confío en que, trabajando en equipo y manteniendo una comunicación constante, lograremos resultados destacados que reflejan nuestro esfuerzo y compromiso. |   |

| Nombre: Martel Zevallos, Gabriel Aristóteles  | <img src="imgs/team/gabriel.jpg" alt="Gabriel" title="Foto de Gabriel" width="320"/> |
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

**Problem Statement 1 – Adultos mayores con tratamientos crónicos**

Nuestro entorno evidencia que los adultos mayores con tratamientos farmacológicos crónicos enfrentan dificultades significativas para cumplir sus esquemas de medicación de manera autónoma en el hogar. Los olvidos de dosis, la confusión entre medicamentos y horarios, y la falta de herramientas accesibles que consideren sus limitaciones visuales, auditivas o cognitivas generan una baja adherencia terapéutica. Hemos observado que los pastilleros convencionales no ofrecen recordatorios activos, no diferencian compartimentos de forma clara ni supervisan condiciones de conservación del medicamento. ¿Cómo podríamos ofrecer a los adultos mayores un sistema de recordatorio y organización de medicamentos que sea accesible, multimodal y fácil de usar, de modo que mejoren su adherencia al tratamiento sin depender exclusivamente de un cuidador?

**Problem Statement 2 – Familiares y cuidadores**

Nuestro entorno evidencia que los familiares y cuidadores de adultos mayores polimedicados carecen de visibilidad oportuna sobre el cumplimiento de la medicación y el estado de los compartimentos del pastillero. Esto les impide intervenir a tiempo ante una dosis omitida, un compartimento vacío o condiciones ambientales inadecuadas de almacenamiento. Hemos observado que las soluciones tradicionales no proveen trazabilidad digital ni mecanismos de notificación remota, lo que obliga al cuidador a depender de la supervisión presencial. ¿Cómo podríamos brindar a familiares y cuidadores un canal de seguimiento remoto, confiable y en tiempo real, que les permita acompañar el tratamiento del adulto mayor sin necesidad de estar físicamente presentes?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creemos que nuestros usuarios necesitan un dispositivo físico que les recuerde de forma clara y accesible cuándo tomar cada medicamento, combinando alertas de voz, luz LED y confirmación mediante botones.
2. Estas necesidades se pueden resolver con un pastillero inteligente de cinco compartimentos integrado a una aplicación de configuración y monitoreo.
3. Nuestros clientes iniciales serán familiares o cuidadores de adultos mayores polimedicados que buscan una herramienta confiable para apoyar la adherencia al tratamiento en el hogar.
4. El valor principal que un cliente quiere de nuestro producto es la tranquilidad de saber que su familiar recibe recordatorios oportunos y que el estado del tratamiento puede supervisarse de forma remota.
5. El cliente también puede obtener beneficios adicionales como alertas de condiciones ambientales inadecuadas (temperatura y humedad), avisos de recarga de compartimentos y notificaciones de fin de tratamiento.
6. Vamos a adquirir la mayoría de nuestros clientes mediante redes sociales orientadas a cuidadores, alianzas con farmacias y recomendaciones en comunidades de salud del adulto mayor.
7. Haremos dinero a través de la venta del dispositivo Dosys como producto premium y, eventualmente, mediante suscripciones para funcionalidades avanzadas de monitoreo y reportes.
8. Nuestra competencia principal serán pastilleros genéricos sin tecnología, aplicaciones móviles de recordatorio de medicamentos y dispensadores automatizados de alto costo.
9. Los venceremos gracias a la combinación de hardware accesible con recordatorio multimodal (voz, luz, botón), monitoreo ambiental integrado y una experiencia de configuración simple desde la aplicación.
10. Nuestro mayor riesgo es que los adultos mayores no adopten el dispositivo por resistencia al uso de tecnología o que los cuidadores no perciban suficiente valor diferencial frente a soluciones más simples.
11. Resolveremos esto mediante un diseño centrado en la accesibilidad, pruebas de usabilidad con usuarios reales del segmento objetivo y una experiencia de primer uso guiada y asistida.

**User Assumptions:**

1. **¿Quién es el usuario?** Adultos mayores de 60 años o más con tratamientos farmacológicos crónicos, y sus familiares o cuidadores que participan en la supervisión del tratamiento.
2. **¿Dónde encaja nuestro producto en su vida?** En la rutina diaria del hogar, específicamente en los momentos asociados a la toma de medicamentos (mañana, tarde, noche).
3. **¿Qué problemas resuelve nuestro producto?** Olvidos de dosis, confusión entre medicamentos y horarios, falta de visibilidad del cuidador sobre el cumplimiento, y almacenamiento en condiciones ambientales inadecuadas.
4. **¿Cuándo y cómo se usa nuestro producto?** El adulto mayor interactúa con el dispositivo físico cuando recibe un recordatorio (voz + LED) y confirma o repite la alerta con botones. El cuidador usa la aplicación para configurar tratamientos, revisar el estado de cumplimiento y recibir notificaciones.
5. **¿Qué características son importantes?** Recordatorio por voz con mensaje claro, iluminación LED por compartimento, botones físicos grandes y accesibles, monitoreo de temperatura y humedad, alertas de recarga y fin de tratamiento, y notificaciones remotas para el cuidador.
6. **¿Cómo debe verse y comportarse nuestro producto?** El dispositivo debe tener un diseño limpio, con compartimentos claramente diferenciados, botones de tamaño adecuado y una interfaz de voz comprensible. La aplicación debe ser visualmente simple, con tipografía legible, navegación intuitiva y flujos de configuración guiados paso a paso.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 1:**

Creemos que lograremos una mejora en la adherencia a la medicación de adultos mayores con tratamientos crónicos si los adultos mayores con polimedicación obtienen recordatorios oportunos y accesibles para cada dosis con un pastillero inteligente que combine alertas de voz, iluminación LED por compartimento y confirmación mediante botones físicos.
Sabremos que hemos tenido éxito cuando al menos el 80% de las dosis programadas sean confirmadas a tiempo por los usuarios durante el primer mes de uso del dispositivo.

**Hypothesis Statement 2:**

Creemos que reduciremos la ansiedad y la carga de supervisión de los familiares y cuidadores si los cuidadores de adultos mayores polimedicados obtienen visibilidad remota y en tiempo real del cumplimiento de la medicación con una aplicación que envíe notificaciones de dosis confirmadas, dosis omitidas y estado de los compartimentos.
Sabremos que hemos tenido éxito cuando más del 70% de los cuidadores reporte una disminución percibida en su nivel de preocupación respecto al cumplimiento de la medicación de su familiar.

**Hypothesis Statement 3:**

Creemos que prevendremos el deterioro de medicamentos almacenados en el hogar si los usuarios de Dosys obtienen alertas tempranas sobre condiciones ambientales inadecuadas con sensores de temperatura y humedad integrados en el dispositivo que notifiquen cuando los valores excedan los rangos recomendados de conservación.
Sabremos que hemos tenido éxito cuando el 100% de las alertas ambientales se emitan antes de que las condiciones del entorno superen los umbrales críticos de conservación durante al menos 30 días consecutivos de uso.

**Hypothesis Statement 4:**

Creemos que mejoraremos la continuidad del tratamiento sin interrupciones por falta de medicamento si los cuidadores y adultos mayores obtienen avisos anticipados de recarga y compra de medicamentos con un sistema que calcule, a partir de la configuración del tratamiento, cuándo un compartimento quedará vacío y cuándo debe adquirirse más medicamento.
Sabremos que hemos tenido éxito cuando menos del 10% de los usuarios reporte haber quedado sin medicamento disponible en algún compartimento durante el primer trimestre de uso.

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas (v2) de Jeff Gothelf integra en una sola vista el problema de negocio, los resultados esperados, los usuarios, los beneficios, las soluciones propuestas, las hipótesis y el experimento de validación para la suposición más riesgosa. A continuación se presenta el canvas elaborado para Dosys, construido a partir de los Business Assumptions, User Assumptions e Hypothesis Statements definidos en las secciones previas.

<img src="imgs/lean-ux/lean_ux_canvas.png" alt="Lean UX Canvas v2 - Dosys" title="Lean UX Canvas de Dosys" width="1000"/>

**Interpretación del canvas:**

- **Problema de negocio (Box 1):** Existe una oportunidad clara en el mercado peruano por la ausencia de soluciones integrales de gestión de medicamentos adaptadas al adulto mayor. Los competidores internacionales no están disponibles localmente o resultan costosos.
- **Resultados esperados (Box 2):** Las métricas clave combinan indicadores de adherencia (80% de dosis confirmadas), retención (70% a 3 meses) y comerciales (200 unidades en el primer año).
- **Usuarios (Box 3):** Se prioriza al cuidador familiar (S2) como canal de adquisición, ya que es el decisor de compra, mientras que el adulto mayor (S1) es el usuario final del hardware.
- **Beneficios de usuario (Box 4):** Se segmentan los beneficios por persona, reflejando que Dosys debe resolver dos experiencias distintas simultáneamente (autonomía para Rosa, tranquilidad remota para Carlos).
- **Soluciones (Box 5):** Se listan las funcionalidades clave del dispositivo y la aplicación que se vinculan directamente con cada beneficio esperado.
- **Hipótesis (Box 6):** Cinco hipótesis que integran las Business Outcomes, Users, User Outcomes y Solutions de los cuadros anteriores.
- **Aprendizaje prioritario (Box 7):** La suposición más riesgosa identificada es la adopción y aceptación del dispositivo por parte del adulto mayor, por su alto impacto en la viabilidad del producto y su alta incertidumbre.
- **Experimento de validación (Box 8):** Se propone un MVP de un solo compartimento para probar la interacción multimodal con 8-10 adultos mayores antes de invertir en el desarrollo completo del producto.

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

Los competidores que hemos identificado para Dosys son soluciones tecnológicas orientadas a la gestión y recordatorio de medicamentos. Aunque no existe en el mercado peruano un producto que combine pastillero inteligente con monitoreo ambiental IoT y accesibilidad multimodal como lo hace Dosys, sí existen productos internacionales con funcionalidades similares que representan competencia directa e indirecta.

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="6" style="text-align:center;">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">Para identificar las ventajas competitivas de Dosys y definir estrategias efectivas frente a soluciones existentes en el mercado de gestión inteligente de medicamentos para adultos mayores.</td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td style="text-align:center;"><strong>Dosys</strong></td>
    <td style="text-align:center;"><strong>Hero Health</strong></td>
    <td style="text-align:center;"><strong>MedMinder</strong></td>
    <td style="text-align:center;"><strong>Pillsy</strong></td>
  </tr>
  <tr>
    <td rowspan="2"><strong>Perfil</strong></td>
    <td>Overview</td>
    <td>Dosys es un pastillero inteligente premium de cinco compartimentos con recordatorio por voz, iluminación LED, confirmación por botón físico y monitoreo de temperatura y humedad. Integra una aplicación para configurar tratamientos, gestionar horarios y recibir notificaciones remotas. Diseñado específicamente para adultos mayores en el contexto peruano.</td>
    <td>Hero Health es un dispensador automático de medicamentos con capacidad para múltiples pastillas. Dispensa la dosis correcta en el momento programado, envía alertas al cuidador y ofrece una app de seguimiento. Enfocado en el mercado estadounidense con un modelo de suscripción mensual.</td>
    <td>MedMinder es un pastillero inteligente con compartimentos que se iluminan y emiten sonido cuando corresponde una toma. Si la dosis no se toma, envía alertas automáticas a familiares o cuidadores por llamada, texto o email. Ofrece modelos con bloqueo de compartimentos para mayor seguridad.</td>
    <td>Pillsy es una tapa inteligente que se coloca sobre frascos de medicamentos estándar. Detecta cuándo se abre el frasco, registra la toma y envía recordatorios al usuario mediante una aplicación móvil. Su enfoque es simple y no invasivo, orientado a usuarios con tratamientos de un solo medicamento.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td>Ofrece una solución integral que combina recordatorio multimodal (voz, luz LED, botón físico), monitoreo ambiental IoT para conservación de medicamentos, alertas de recarga y fin de tratamiento, y una aplicación accesible para configuración y seguimiento remoto. Diseñado con enfoque en accesibilidad para adultos mayores.</td>
    <td>Ofrece dispensación automática precisa que elimina errores de selección del medicamento. El dispositivo prepara la dosis exacta, lo que reduce la intervención del usuario. Incluye seguimiento detallado y alertas para cuidadores remotos.</td>
    <td>Ofrece un sistema de alertas escalonadas que contacta al cuidador si la dosis no se toma, incluyendo llamadas telefónicas. Los modelos con bloqueo de compartimentos previenen la toma accidental de dosis incorrectas, lo que añade una capa de seguridad.</td>
    <td>Ofrece una solución no invasiva y económica que se adapta a los frascos de medicamento existentes. No requiere reorganizar los medicamentos en un dispositivo nuevo, lo que facilita la adopción por parte de usuarios que prefieren cambios mínimos en su rutina.</td>
  </tr>
  <tr>
    <td rowspan="2"><strong>Perfil de Marketing</strong></td>
    <td>Mercado Objetivo</td>
    <td>Adultos mayores de 60 años o más con tratamientos crónicos en el Perú, y sus familiares o cuidadores que buscan una herramienta accesible para apoyar la adherencia al tratamiento en el hogar. Enfoque en el contexto latinoamericano con soporte en español.</td>
    <td>Adultos mayores y personas con polifarmacia en Estados Unidos, junto con sus cuidadores y familiares. Se orienta a usuarios que requieren dispensación automatizada y están dispuestos a pagar una suscripción mensual por el servicio.</td>
    <td>Adultos mayores con deterioro cognitivo o condiciones crónicas en Estados Unidos y Canadá. También se dirige a residencias de cuidado y profesionales de salud que buscan herramientas de monitoreo remoto de adherencia.</td>
    <td>Usuarios adultos de todas las edades con tratamientos de uno o pocos medicamentos en Estados Unidos. Enfocado en personas con estilo de vida activo que buscan un recordatorio simple sin necesidad de un dispositivo especializado complejo.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>●Alianzas con farmacias y cadenas de salud locales para promocionar el dispositivo entre adultos mayores y cuidadores.<br/><br/>●Marketing en redes sociales dirigido a familiares de adultos mayores, mostrando casos de uso y testimonios.<br/><br/>●Presencia en ferias de salud, envejecimiento activo y tecnología IoT en Perú y Latinoamérica.<br/><br/>●Campañas educativas sobre adherencia terapéutica y conservación de medicamentos en el hogar.</td>
    <td>●Publicidad digital en Estados Unidos con campañas en Google Ads y redes sociales orientadas a cuidadores.<br/><br/>●Alianzas con profesionales de salud y farmacias que recomiendan el dispositivo.<br/><br/>●Contenido educativo sobre gestión de medicamentos en su blog y redes sociales.<br/><br/>●Programa de referidos para usuarios existentes.</td>
    <td>●Marketing directo a residencias de cuidado y profesionales de salud.<br/><br/>●Publicidad en medios especializados en salud y envejecimiento.<br/><br/>●Presencia en conferencias y ferias de tecnología para el cuidado de adultos mayores.<br/><br/>●Email marketing personalizado dirigido a cuidadores familiares.</td>
    <td>●Marketing digital enfocado en simplicidad y estilo de vida saludable.<br/><br/>●Presencia en redes sociales con enfoque en bienestar y autocuidado.<br/><br/>●Colaboraciones con influencers de salud y bienestar.<br/><br/>●Distribución a través de Amazon y farmacias online.</td>
  </tr>
  <tr>
    <td rowspan="3"><strong>Perfil de productos</strong></td>
    <td>Productos &amp; Servicios</td>
    <td>●Pastillero inteligente de cinco compartimentos con LED, altavoz de voz y botones físicos.<br/><br/>●Sensor de temperatura y humedad integrado para monitoreo de condiciones de conservación.<br/><br/>●Aplicación para configurar tratamientos, horarios, alertas de recarga y notificaciones remotas al cuidador.<br/><br/>●Alertas de fin de tratamiento y recordatorio de compra de medicamento.</td>
    <td>●Dispensador automático de medicamentos con capacidad para múltiples pastillas.<br/><br/>●Aplicación de seguimiento con historial de tomas y alertas para cuidadores.<br/><br/>●Servicio de suscripción mensual que incluye soporte técnico y reposición de piezas.<br/><br/>●Integración con sistemas de salud para reportes de adherencia.</td>
    <td>●Pastillero inteligente con compartimentos iluminados y alertas sonoras.<br/><br/>●Modelos con bloqueo automático de compartimentos para prevenir errores.<br/><br/>●Sistema de alertas escalonadas: notificación, llamada y mensaje al cuidador.<br/><br/>●Portal web para monitoreo remoto por parte de familiares y profesionales de salud.</td>
    <td>●Tapa inteligente con sensor de apertura para frascos de medicamentos.<br/><br/>●Aplicación móvil con recordatorios, historial de tomas y reportes.<br/><br/>●Sincronización con Apple Health y Google Fit.<br/><br/>●Diseño compacto y portátil que no requiere reorganizar medicamentos.</td>
  </tr>
  <tr>
    <td>Precios &amp; Costos</td>
    <td>●Venta del dispositivo como producto premium a precio accesible para el mercado peruano.<br/><br/>●Sin suscripción obligatoria para funcionalidades básicas.<br/><br/>●Posibilidad de plan de suscripción opcional para reportes avanzados y funcionalidades adicionales de monitoreo.</td>
    <td>●Dispositivo proporcionado sin costo inicial.<br/><br/>●Suscripción mensual de aproximadamente $29.99 USD que incluye el servicio completo.<br/><br/>●Modelo de ingreso recurrente basado en suscripción.</td>
    <td>●Dispositivo con precio de compra entre $39.99 y $69.99 USD según el modelo.<br/><br/>●Suscripción mensual de $19.99 a $39.99 USD para el servicio de alertas y monitoreo remoto.<br/><br/>●Planes diferenciados según nivel de funcionalidades.</td>
    <td>●Tapa inteligente con precio de compra de aproximadamente $9.99 a $14.99 USD por unidad.<br/><br/>●Aplicación gratuita con funcionalidades básicas.<br/><br/>●Sin modelo de suscripción, costo único por dispositivo.</td>
  </tr>
  <tr>
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td>●<strong>Aplicación móvil</strong> para Android e iOS para configuración y monitoreo.<br/><br/>●Venta del dispositivo a través de tienda online propia y alianzas con farmacias.<br/><br/>●<strong>Landing page</strong> informativa con opción de compra directa.</td>
    <td>●<strong>Plataforma web</strong> para registro y gestión de suscripción.<br/><br/>●<strong>Aplicación móvil</strong> para Android e iOS con todas las funcionalidades de seguimiento.<br/><br/>●Distribución directa al consumidor a través de su sitio web.</td>
    <td>●<strong>Plataforma web</strong> con portal de monitoreo para cuidadores.<br/><br/>●<strong>Aplicación móvil</strong> para Android e iOS.<br/><br/>●Distribución a través de su sitio web, farmacias y proveedores de salud.</td>
    <td>●<strong>Aplicación móvil</strong> para Android e iOS.<br/><br/>●Venta a través de Amazon, farmacias online y su sitio web.<br/><br/>●Distribución directa al consumidor.</td>
  </tr>
  <tr>
    <td rowspan="4"><strong>Análisis SWOT</strong></td>
    <td>Fortalezas</td>
    <td>●Combinación única de recordatorio multimodal (voz, LED, botón) con monitoreo ambiental IoT.<br/><br/>●Diseño centrado en accesibilidad para adultos mayores con limitaciones visuales, auditivas o motoras.<br/><br/>●Enfoque en el mercado peruano y latinoamericano con soporte nativo en español.<br/><br/>●Sin dependencia de suscripción obligatoria, lo que reduce la barrera de entrada.</td>
    <td>●Dispensación automática que elimina errores humanos en la selección del medicamento.<br/><br/>●Modelo de suscripción sin costo inicial del dispositivo, lo que facilita la adopción.<br/><br/>●Amplia capacidad de almacenamiento de múltiples medicamentos.<br/><br/>●Marca consolidada en el mercado estadounidense.</td>
    <td>●Sistema de alertas escalonadas con múltiples canales de contacto al cuidador.<br/><br/>●Modelos con bloqueo de compartimentos para mayor seguridad en pacientes con deterioro cognitivo.<br/><br/>●Presencia establecida en el sector de salud y residencias de cuidado.<br/><br/>●Portal web robusto para monitoreo profesional.</td>
    <td>●Solución económica y no invasiva que se adapta a frascos existentes.<br/><br/>●Diseño compacto y portátil, ideal para usuarios activos.<br/><br/>●Bajo costo de adquisición sin suscripción.<br/><br/>●Integración con plataformas de salud como Apple Health y Google Fit.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>●Producto en etapa de desarrollo, sin base de usuarios consolidada ni reconocimiento de marca.<br/><br/>●Limitado a cinco compartimentos, lo que puede ser insuficiente para pacientes con alta polifarmacia.<br/><br/>●Recursos limitados como startup universitaria frente a competidores internacionales con mayor financiamiento.<br/><br/>●Dependencia de conectividad para funcionalidades de monitoreo remoto.</td>
    <td>●Costo mensual de suscripción que puede resultar elevado a largo plazo.<br/><br/>●Dispositivo de gran tamaño que ocupa espacio considerable.<br/><br/>●Disponibilidad limitada al mercado estadounidense.<br/><br/>●Dependencia total del modelo de suscripción: sin pago, sin servicio.</td>
    <td>●Costo combinado de dispositivo más suscripción que puede ser prohibitivo para muchos usuarios.<br/><br/>●Interfaz y experiencia de usuario percibida como anticuada frente a competidores más modernos.<br/><br/>●Disponibilidad limitada a Estados Unidos y Canadá.<br/><br/>●Requiere reorganizar todos los medicamentos en el dispositivo.</td>
    <td>●Solo monitorea apertura del frasco, no confirma la ingesta real del medicamento.<br/><br/>●Limitado a un medicamento por tapa, lo que es impráctico para polifarmacia.<br/><br/>●Sin alertas multimodales (solo notificación en app).<br/><br/>●No ofrece monitoreo ambiental ni funcionalidades de conservación.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>●Crecimiento sostenido de la población adulta mayor en Perú con alta carga de comorbilidad.<br/><br/>●Ausencia de soluciones IoT accesibles para gestión de medicamentos en el mercado peruano y latinoamericano.<br/><br/>●Posibilidad de alianzas con el sector salud, farmacias y programas gubernamentales de atención al adulto mayor.<br/><br/>●Expansión a otros mercados de Latinoamérica con necesidades similares.</td>
    <td>●Expansión a mercados internacionales fuera de Estados Unidos.<br/><br/>●Incorporación de inteligencia artificial para predicción de patrones de adherencia.<br/><br/>●Alianzas con aseguradoras que subsidien el costo de suscripción.<br/><br/>●Integración con telemedicina y sistemas de salud digital.</td>
    <td>●Modernización de la interfaz y experiencia de usuario.<br/><br/>●Expansión a mercados latinoamericanos y europeos.<br/><br/>●Incorporación de sensores adicionales para monitoreo de salud.<br/><br/>●Alianzas con sistemas de salud pública para programas de adherencia.</td>
    <td>●Desarrollo de tapas con sensores más avanzados que detecten cantidad de pastillas.<br/><br/>●Expansión del producto a paquetes multi-tapa para polifarmacia.<br/><br/>●Integración con plataformas de telemedicina.<br/><br/>●Entrada a mercados emergentes con precio competitivo.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>●Competencia directa e indirecta con soluciones internacionales consolidadas que podrían ingresar al mercado peruano.<br/><br/>●Riesgo de desconfianza inicial por parte de adultos mayores hacia dispositivos tecnológicos.<br/><br/>●Posibles barreras económicas del segmento objetivo para adquirir un producto premium.<br/><br/>●Dificultad para retener usuarios si no se genera valor continuo más allá del recordatorio básico.</td>
    <td>●Saturación del mercado de dispensadores automáticos en Estados Unidos.<br/><br/>●Riesgo de cancelación de suscripciones por usuarios que perciben el costo como elevado.<br/><br/>●Competencia de aplicaciones gratuitas de recordatorio de medicamentos.<br/><br/>●Regulaciones sanitarias que podrían limitar funcionalidades.</td>
    <td>●Competencia de soluciones más modernas y económicas.<br/><br/>●Disminución de la demanda por parte de residencias que adopten soluciones automatizadas más avanzadas.<br/><br/>●Incremento de costos de suscripción que aleje a usuarios individuales.<br/><br/>●Plataformas emergentes con mejor experiencia de usuario.</td>
    <td>●Competencia de smartwatches y wearables con funciones de recordatorio de medicamentos.<br/><br/>●Limitación del modelo de producto único sin ingresos recurrentes.<br/><br/>●Riesgo de obsolescencia frente a soluciones más integrales.<br/><br/>●Dificultad para competir en precio con aplicaciones gratuitas.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Dosys aplicará una estrategia de diferenciación enfocada en la accesibilidad, la integración IoT y la cercanía cultural con el mercado peruano y latinoamericano. Frente a los competidores internacionales del mercado de gestión inteligente de medicamentos, Dosys se posiciona como una solución accesible, integral y adaptada al contexto local, conectando a adultos mayores con una experiencia de uso simple y multimodal que las soluciones importadas no ofrecen.

Su valor diferencial se sustenta en tres pilares: (1) recordatorio multimodal mediante voz, LED y botones físicos diseñados para usuarios con limitaciones sensoriales o cognitivas; (2) monitoreo ambiental IoT con sensores de temperatura y humedad que supervisan la conservación de los medicamentos; y (3) un modelo de negocio sin suscripción obligatoria que reduce la barrera de entrada frente a competidores como Hero Health o MedMinder.

**Estrategias clave:**

- **Diferenciación por accesibilidad:** Mientras que competidores como Pillsy dependen exclusivamente de notificaciones en app, Dosys combina alertas físicas (voz, luz, botón) que no requieren uso de smartphone por parte del adulto mayor, reduciendo la brecha tecnológica.
- **Liderazgo en costos accesibles:** Frente al modelo de suscripción de Hero Health (~$29.99/mes) y los costos combinados de MedMinder (dispositivo + suscripción), Dosys ofrece un producto premium de compra única con funcionalidades completas sin pagos recurrentes obligatorios.
- **Enfoque regional:** Aprovechar la ausencia de soluciones especializadas en Perú y Latinoamérica, ofreciendo soporte nativo en español, alianzas con farmacias locales y adaptación a las condiciones y necesidades del adulto mayor peruano.
- **Valor agregado IoT:** Ninguno de los competidores analizados integra monitoreo de condiciones ambientales de conservación del medicamento. Esta funcionalidad diferencial permite a Dosys posicionarse como la única solución que no solo recuerda la toma, sino que también protege la calidad del medicamento.
- **Mitigación de amenazas:** Para contrarrestar la resistencia tecnológica del adulto mayor, Dosys implementará una experiencia de primer uso guiada, un diseño físico intuitivo con compartimentos claramente diferenciados y pruebas de usabilidad directas con usuarios del segmento objetivo.

## 2.2. Entrevistas

### 2.2.1. Diseño de Entrevistas

**Segmento objetivo 1: Adultos mayores con tratamientos farmacológicos crónicos**

¿Cual es tu nombre completo?

¿Cual es tu edad?

¿En donde vives?

¿Vives solo, con familiares o con un cuidador?

¿Cuántos medicamentos sueles tomar al día?

¿Cómo organizas actualmente tus medicamentos en casa?

¿Qué tan difícil te resulta recordar la hora correcta para tomar cada medicamento?

¿Te ha pasado que olvidas una dosis o confundes un medicamento con otro?

¿Qué tipo de ayuda usas actualmente para recordar tus medicamentos, si es que usas alguna?

¿Te ayudaría que un dispositivo te avise con voz y luz qué compartimento debes abrir?

¿Te sería cómodo confirmar con un botón físico que ya tomaste la pastilla?

¿Te parecería útil que el dispositivo avise si la temperatura o la humedad podrían afectar tus medicamentos?

**Segmento objetivo 2: Familiares y cuidadores de adultos mayores polimedicados**

¿Cuál es tu nombre completo?

¿Cuál es tu edad?

¿En dónde vives y a qué te dedicas actualmente?

¿Qué relación tienes con la persona adulta mayor a la que apoyas (hijo/a, pareja, cuidador profesional, otro)?

¿Vives con ella o la acompañas a distancia? ¿Con qué frecuencia la visitas o te comunicas?

¿Cuántos medicamentos distintos toma al día la persona bajo tu cuidado?

¿Quién organiza y prepara habitualmente sus medicamentos: tú, ella misma u otra persona?

¿Cómo haces actualmente para asegurarte de que tome sus medicamentos a la hora correcta?

¿Te ha tocado enterarte de que olvidó una dosis o tomó un medicamento equivocado? ¿Cómo lo supiste?

¿Qué tan preocupado/a te sientes respecto al cumplimiento del tratamiento cuando no estás presente?

¿Usas actualmente alguna aplicación, alarma o herramienta para hacer seguimiento a sus medicamentos?

¿Te resultaría útil recibir notificaciones en tu celular cuando la persona tome (o no tome) su medicamento?

¿Te gustaría poder configurar los horarios y dosis del tratamiento desde una aplicación móvil, aunque estés lejos?

¿Qué tan valioso sería para ti acceder a un historial de tomas y reportes que puedas compartir con el médico?

¿Estarías dispuesto/a a pagar por un dispositivo que te permita supervisar remotamente el cumplimiento del tratamiento? ¿En qué rango de precio?

¿Qué es lo más importante para ti al momento de elegir una solución de este tipo: precio, facilidad de uso, confiabilidad de las alertas u otra cosa?

### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas

A partir del análisis de los segmentos objetivo definidos en la sección 1.3, se elaboraron dos User Personas que representan los perfiles principales de usuario de Dosys: el adulto mayor polimedicado (usuario final del dispositivo) y el cuidador familiar (usuario principal de la aplicación y habitualmente el decisor de compra). Ambas personas fueron construidas con la herramienta UXPressia.

**User Persona 1 — Rosa Jiménez Vargas (Adulto Mayor Polimedicado)**

<img src="imgs/personas/user_persona_rosa_jimenez.png" alt="User Persona 1 - Rosa Jiménez Vargas" title="Adulto Mayor Polimedicado" width="800"/>

Rosa representa al segmento S1: adultos mayores de 60 años o más con tratamientos farmacológicos crónicos que interactúan directamente con el hardware del pastillero Dosys. Sus objetivos, motivaciones y frustraciones guían las decisiones de accesibilidad física del dispositivo (recordatorio multimodal por voz, LED y botones).

**User Persona 2 — Carlos Mendoza Ríos (Cuidador Familiar)**

<img src="imgs/personas/user_persona_carlos_mendoza.png" alt="User Persona 2 - Carlos Mendoza Ríos" title="Cuidador Familiar" width="800"/>

Carlos representa al segmento S2: familiares y cuidadores de adultos mayores polimedicados que configuran los tratamientos, supervisan el cumplimiento remoto y reciben alertas a través de la aplicación móvil. Sus necesidades orientan el diseño de la experiencia digital, las notificaciones y el monitoreo remoto.

### 2.3.2. User Task Matrix

La siguiente matriz identifica las tareas que los segmentos objetivo de Dosys realizan actualmente en relación con la gestión de medicamentos, independientemente de la existencia del producto. Se evalúa la frecuencia (Alta, Media, Baja) y la importancia (Alta, Media, Baja) de cada tarea para cada segmento.

Los segmentos considerados son:
- **Segmento 1 (S1):** Adultos mayores con tratamientos farmacológicos crónicos.
- **Segmento 2 (S2):** Familiares y cuidadores de adultos mayores polimedicados.

<table>
  <tr>
    <th rowspan="2">Tarea</th>
    <th colspan="2" style="text-align:center;">Adulto Mayor (S1)</th>
    <th colspan="2" style="text-align:center;">Cuidador / Familiar (S2)</th>
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
  <tr>
    <td>Recordar qué medicamento tomar en cada horario</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Identificar el medicamento correcto entre varios disponibles</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Tomar la dosis en el horario indicado</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Organizar los medicamentos en un pastillero o contenedor</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Verificar que se tomó la dosis correspondiente</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Supervisar el cumplimiento del tratamiento del familiar</td>
    <td>Baja</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Revisar si hay medicamento suficiente para los próximos días</td>
    <td>Media</td>
    <td>Media</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Comprar o reponer medicamentos antes de que se agoten</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Almacenar los medicamentos en condiciones adecuadas (temperatura, humedad)</td>
    <td>Baja</td>
    <td>Media</td>
    <td>Baja</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Consultar el horario o esquema del tratamiento</td>
    <td>Media</td>
    <td>Media</td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Comunicar al cuidador si olvidó o retrasó una dosis</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Registrar o actualizar los medicamentos y horarios tras una consulta médica</td>
    <td>Baja</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Limpiar o vaciar compartimentos al finalizar un tratamiento</td>
    <td>Baja</td>
    <td>Media</td>
    <td>Baja</td>
    <td>Media</td>
  </tr>
</table>

**Tareas con mayor relevancia para ambos segmentos:**

Las tareas que presentan alta frecuencia y alta importancia en ambos segmentos son las que Dosys prioriza en su propuesta de valor:

- **Recordar qué medicamento tomar en cada horario:** Es la tarea más crítica y frecuente. Dosys la aborda mediante el recordatorio multimodal (voz + LED + botón).
- **Tomar la dosis en el horario indicado:** Directamente vinculada a la adherencia terapéutica. Dosys facilita esta tarea con alertas programadas y confirmación física.
- **Verificar que se tomó la dosis correspondiente:** Es de alta importancia para el cuidador. Dosys la resuelve con el registro de confirmaciones y notificaciones remotas de dosis omitidas.
- **Organizar los medicamentos en un pastillero:** Tarea que recae principalmente en el cuidador. Dosys la simplifica con cinco compartimentos diferenciados y configuración guiada desde la aplicación.

### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

A partir de las User Personas definidas en la sección 2.3.1, se elaboraron dos Empathy Maps con la herramienta UXPressia para profundizar en las experiencias, pensamientos, emociones y comportamientos de cada segmento objetivo en su estado actual (AS-IS), es decir, antes de adoptar una solución como Dosys. Estos mapas permiten identificar los dolores reales que justifican la propuesta de valor y las ganancias esperadas que Dosys debe entregar.

**Empathy Map 1 — Rosa Jiménez Vargas (Adulto Mayor Polimedicado)**

<img src="imgs/empathy-maps/empathy_map_rosa_jimenez.png" alt="Empathy Map - Rosa Jiménez Vargas" title="Empathy Map del Adulto Mayor Polimedicado" width="900"/>

El empathy map de Rosa revela una experiencia marcada por la ansiedad ante los olvidos, el miedo a equivocarse con medicamentos similares y la tensión entre su deseo de mantenerse independiente y la necesidad creciente de apoyo familiar. Sus dolores principales —olvidos frecuentes, dificultades visuales y auditivas, pérdida de control sobre su salud— validan directamente la necesidad del recordatorio multimodal (voz, LED, botón físico) planteado en el Hypothesis Statement 1.

**Empathy Map 2 — Carlos Mendoza Ríos (Cuidador Familiar)**

<img src="imgs/empathy-maps/empathy_map_carlos_mendoza.png" alt="Empathy Map - Carlos Mendoza Ríos" title="Empathy Map del Cuidador Familiar" width="900"/>

El empathy map de Carlos expone la carga mental del cuidador remoto: preocupación constante durante su jornada laboral, culpa por no estar físicamente presente y frustración con las soluciones actuales del mercado. Sus ganancias esperadas —monitoreo remoto en tiempo real, alertas inmediatas, coordinación familiar compartida— sustentan las funcionalidades de la aplicación móvil de Dosys y validan los Hypothesis Statements 2, 3 y 4 relacionados con visibilidad remota, monitoreo ambiental y avisos de recarga.

**Hallazgos clave del contraste entre ambos empathy maps:**

- Rosa experimenta *soledad y pérdida de autonomía*, mientras Carlos siente *carga mental y culpa por la distancia*. Dosys debe resolver ambos dolores simultáneamente mediante la combinación hardware + aplicación.
- Los canales por los que escuchan información son distintos: Rosa consume medios tradicionales (radio, TV, vecinas), mientras Carlos utiliza canales digitales (redes sociales, podcasts, colegas). Esto valida la estrategia de marketing dual definida en el análisis competitivo.
- Los dolores identificados en ambos empathy maps se alinean directamente con los cuatro Hypothesis Statements del Lean UX, confirmando que las hipótesis del producto apuntan a necesidades reales y no a suposiciones del equipo.

## 2.4. Big Picture EventStorming
## 2.5. Ubiquitous Language

El siguiente glosario define los términos clave utilizados de manera consistente por todo el equipo de desarrollo de Dosys, tanto en la comunicación interna como en el código fuente, la documentación y la interfaz del producto. Su propósito es eliminar ambigüedades entre los dominios de salud, IoT y cuidado del adulto mayor.

| Término (EN) | Término (ES) | Definición |
| :---- | :---- | :---- |
| **Medication** | Medicamento | Fármaco recetado o de uso regular que el adulto mayor debe tomar según un esquema terapéutico definido. Cada medicamento se registra en el sistema con nombre, dosis, frecuencia y duración del tratamiento. |
| **Compartment** | Compartimento | Cada una de las cinco divisiones físicas del pastillero Dosys donde se almacena un medicamento específico. Un compartimento se asocia a un único medicamento dentro de un tratamiento activo. |
| **Treatment** | Tratamiento | Conjunto de reglas que define qué medicamento tomar, en qué compartimento se encuentra, a qué hora corresponde cada dosis, durante cuántos días y con qué frecuencia. Es configurado por el cuidador o el propio usuario desde la aplicación. |
| **Dose** | Dosis | Unidad mínima de toma de un medicamento en un momento específico del día. Cada dosis tiene un horario programado y está vinculada a un compartimento del dispositivo. |
| **Reminder** | Recordatorio | Evento que se activa cuando llega el horario programado de una dosis. Se manifiesta de forma multimodal: reproducción de un mensaje de voz, encendido del LED del compartimento correspondiente y habilitación del botón de confirmación. |
| **Confirmation** | Confirmación | Acción realizada por el adulto mayor al presionar el botón físico del compartimento correspondiente tras recibir un recordatorio, indicando que ha tomado la dosis. |
| **Snooze** | Repetición de alerta | Acción realizada por el adulto mayor al presionar el botón de repetir, lo que pospone el recordatorio por un intervalo de tiempo definido antes de volver a emitir la alerta. |
| **Missed Dose** | Dosis omitida | Dosis que no fue confirmada dentro del período de tiempo permitido después del recordatorio. Genera una notificación al cuidador a través de la aplicación. |
| **Caregiver** | Cuidador | Persona responsable de supervisar y apoyar el tratamiento del adulto mayor. Puede ser un familiar, un cuidador profesional o cualquier persona designada. Utiliza la aplicación para configurar tratamientos, recibir notificaciones y monitorear el cumplimiento. |
| **Patient** | Paciente | Adulto mayor que utiliza el dispositivo Dosys para recibir recordatorios y confirmar la toma de sus medicamentos. Interactúa principalmente con el hardware del pastillero. |
| **Device** | Dispositivo | El pastillero inteligente Dosys como unidad de hardware. Incluye los cinco compartimentos, LEDs, altavoz, botones físicos y los sensores de temperatura y humedad. Cada dispositivo se vincula a una cuenta de usuario en la aplicación. |
| **Environmental Monitoring** | Monitoreo ambiental | Funcionalidad del dispositivo que mide continuamente la temperatura y humedad del entorno donde se almacenan los medicamentos mediante sensores integrados, con el fin de detectar condiciones que puedan comprometer su conservación. |
| **Environmental Alert** | Alerta ambiental | Notificación generada cuando los sensores del dispositivo detectan que la temperatura o humedad del entorno excede los umbrales recomendados para la conservación segura de medicamentos. |
| **Refill Alert** | Alerta de recarga | Notificación que indica que un compartimento está próximo a quedarse sin medicamento, calculada a partir de la cantidad registrada y la frecuencia de toma configurada en el tratamiento. |
| **Purchase Reminder** | Aviso de compra | Notificación anticipada que sugiere al cuidador o usuario adquirir más unidades de un medicamento antes de que se agote la reserva en el compartimento. |
| **End-of-Treatment Alert** | Alerta de fin de tratamiento | Notificación que indica que un tratamiento ha llegado a su fecha de finalización programada y que el compartimento correspondiente debe ser vaciado o limpiado. |
| **Adherence** | Adherencia | Grado en que el paciente cumple con el esquema de medicación programado. Se mide a través del porcentaje de dosis confirmadas respecto al total de dosis programadas en un período determinado. |
| **Polypharmacy** | Polifarmacia | Condición en la que el paciente debe tomar múltiples medicamentos de manera simultánea o en distintos horarios del día, lo que incrementa la complejidad del tratamiento y el riesgo de errores. |
| **Multimodal Reminder** | Recordatorio multimodal | Estrategia de alerta que combina múltiples canales sensoriales (voz, luz LED, vibración o botón físico) para maximizar la probabilidad de que el adulto mayor perciba y responda al recordatorio. |
| **Bounded Context** | Contexto delimitado | División lógica del sistema en dominios independientes con responsabilidades bien definidas. En Dosys se identifican tres contextos: Access (gestión de usuarios y autenticación), Medication (gestión de tratamientos y dosis) y Device (gestión del hardware y sensores IoT). |
| **LED Indicator** | Indicador LED | Luz individual asociada a cada compartimento del dispositivo que se enciende cuando corresponde tomar el medicamento almacenado en ese compartimento, facilitando la identificación visual. |
| **Voice Alert** | Alerta por voz | Mensaje de audio reproducido por el altavoz del dispositivo que indica al paciente qué medicamento tomar en el momento del recordatorio programado. |

# Capítulo III: Requirements Specification

## 3.1. User Stories

<table border="1">
  <thead>
    <tr>
      <th>Epic/Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP01</td>
      <td>Presencia Digital y Captación</td>
      <td colspan="3">El sistema debe proporcionar una plataforma web informativa para dar a conocer la solución Dosys.</td>
    </tr>
    <tr>
      <td>US01</td>
      <td>Información del Producto</td>
      <td>Como visitante de la Landing Page, quiero visualizar las características principales de Dosys, para entender los beneficios del pastillero inteligente.</td>
      <td>Given que el visitante se encuentra en la página de inicio, When navega por la sección de características, Then visualiza información sobre recordatorios de voz, LEDs y monitoreo ambiental.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Formulario de Contacto</td>
      <td>Como visitante interesado, quiero enviar mis datos a través de un formulario, para recibir asesoría personalizada sobre el producto.</td>
      <td>Given que el visitante completa los campos obligatorios, When solicita el envío de la información, Then el sistema confirma la recepción exitosa del mensaje.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>EP02</td>
      <td>Gestión de Accesos (Contexto Access)</td>
      <td colspan="3">El sistema debe permitir la administración segura de cuentas de usuario y la vinculación de dispositivos.</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Registro de Cuidador</td>
      <td>Como cuidador, quiero crear una cuenta en la aplicación, para empezar a gestionar el tratamiento de mi familiar.</td>
      <td>Given que el usuario no tiene una cuenta, When ingresa un correo electrónico válido y una contraseña segura, Then el sistema crea el perfil y envía un correo de verificación.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS01</td>
      <td>API de Autenticación</td>
      <td>Como Developer, quiero implementar un endpoint de login, para validar las credenciales de los usuarios mediante JWT.</td>
      <td>Given un request POST con credenciales válidas, When el servicio procesa la solicitud, Then el servidor responde con un status 200 y un token de acceso.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Vinculación IoT</td>
      <td>Como cuidador, quiero vincular el pastillero físico mediante un código identificador, para que la app pueda enviar configuraciones al hardware.</td>
      <td>Given que el dispositivo está encendido, When el usuario registra el ID único en la app, Then el sistema establece una conexión lógica entre la cuenta y el hardware.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>EP03</td>
      <td>Gestión de Tratamientos (Contexto Medication)</td>
      <td colspan="3">El sistema debe administrar los horarios, dosis y asignación de compartimentos de medicamentos.</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Registro de Medicina</td>
      <td>Como cuidador, quiero registrar un nuevo medicamento en el sistema, para tenerlo disponible en la configuración del tratamiento.</td>
      <td>Given que el cuidador conoce el nombre del fármaco, When ingresa el nombre y la presentación, Then el sistema guarda la medicina en el catálogo personal.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Programación de Dosis</td>
      <td>Como cuidador, quiero definir la hora y frecuencia de una toma, para que el paciente reciba los recordatorios oportunamente.</td>
      <td>Given un medicamento seleccionado, When el usuario asigna un horario (ej. 08:00 AM) y una frecuencia, Then el sistema genera el calendario de tomas correspondiente.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Asignación de Compartimento</td>
      <td>Como cuidador, quiero asignar un medicamento a uno de los 5 compartimentos físicos, para que el LED correcto se encienda durante la toma.</td>
      <td>Given un tratamiento activo, When el usuario selecciona un número de compartimento (1 al 5), Then el sistema vincula físicamente la medicina con esa sección del pastillero.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>TS02</td>
      <td>API de Sincronización de Calendario</td>
      <td>Como Developer, quiero un endpoint que entregue el calendario de tomas al dispositivo, para que el hardware funcione de forma offline.</td>
      <td>Given una solicitud GET desde el dispositivo identificado, When existen cambios en el tratamiento, Then el servicio retorna un JSON con el cronograma actualizado de 24 horas.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Consulta de Adherencia</td>
      <td>Como cuidador, quiero ver un historial de dosis tomadas y omitidas, para monitorear el cumplimiento del tratamiento.</td>
      <td>Given que existen registros de tomas previas, When el usuario consulta el reporte semanal, Then el sistema muestra el porcentaje de cumplimiento sobre el total programado.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>EP04</td>
      <td>Interacción con Hardware (Contexto Device)</td>
      <td colspan="3">El sistema debe gestionar las alertas físicas y los datos recolectados por los sensores IoT.</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Alerta Multimodal</td>
      <td>Como paciente, quiero escuchar un mensaje de voz y ver una luz LED cuando sea hora de mi medicina, para identificar qué debo tomar sin confusión.</td>
      <td>Given que se alcanza la hora programada para una dosis, When el reloj interno coincide con el horario, Then el dispositivo reproduce el audio y enciende el LED del compartimento asignado.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Confirmación de Toma</td>
      <td>Como paciente, quiero presionar un botón físico tras ingerir la pastilla, para que el sistema registre mi cumplimiento.</td>
      <td>Given que una alerta está activa, When el paciente presiona el botón del compartimento, Then el LED se apaga y el dispositivo registra la confirmación de la dosis.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Monitoreo de Humedad</td>
      <td>Como cuidador, quiero recibir una alerta si la humedad del ambiente sube, para evitar que las pastillas se degraden.</td>
      <td>Given que el sensor de humedad detecta un valor superior al 65%, When el sistema procesa el dato, Then se envía una notificación push de advertencia al smartphone del cuidador.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Alerta de Temperatura</td>
      <td>Como cuidador, quiero ser notificado si el pastillero está expuesto a calor excesivo, para cambiarlo de lugar y proteger los fármacos.</td>
      <td>Given que la temperatura registrada supera los 30°C, When el dispositivo reporta el dato, Then el sistema genera una alerta ambiental crítica.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>Ingesta de Datos de Sensores</td>
      <td>Como Developer, quiero un endpoint que reciba datos de telemetría (temp/hum), para almacenar el histórico ambiental del dispositivo.</td>
      <td>Given un request POST con datos de sensores y timestamp, When la firma del dispositivo es válida, Then el servicio persiste la información y retorna un status 201.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Alerta de Recarga</td>
      <td>Como cuidador, quiero un aviso cuando queden pocas pastillas en un compartimento, para reponer el stock a tiempo.</td>
      <td>Given que el número de dosis confirmadas reduce el stock a 3 unidades, When se procesa la última confirmación, Then el sistema notifica la necesidad de recarga.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Posponer Alerta (Snooze)</td>
      <td>Como paciente, quiero silenciar la alarma por 5 minutos, para tomar la medicina después si estoy ocupado en ese instante.</td>
      <td>Given que la alerta está sonando, When el paciente presiona el botón de repetición, Then el audio se detiene y se reactiva automáticamente tras 5 minutos.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Ajuste de Volumen</td>
      <td>Como cuidador, quiero regular el volumen del pastillero desde la app, para adaptarlo a la capacidad auditiva del paciente.</td>
      <td>Given que el dispositivo está online, When el usuario modifica el nivel de volumen en la aplicación, Then el hardware actualiza su configuración de salida de audio inmediatamente.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Sección de Beneficios (Landing)</td>
      <td>Como visitante del segmento "Cuidadores", quiero leer testimonios y casos de éxito, para confiar en la eficacia de Dosys.</td>
      <td>Given que el visitante navega hacia la sección de testimonios, When interactúa con los elementos de la página, Then visualiza experiencias reales de otros usuarios.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Registro de Alergias</td>
      <td>Como cuidador, quiero documentar alergias en el perfil del paciente, para tener una referencia rápida en caso de emergencia médica.</td>
      <td>Given que el perfil del paciente está activo, When el usuario añade una sustancia a la lista de alergias, Then el sistema actualiza la ficha médica digital.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>Health Check del Dispositivo</td>
      <td>Como Developer, quiero implementar un "Heartbeat", para saber si el dispositivo ha perdido conexión a internet.</td>
      <td>Given que el dispositivo no envía señales por más de 10 minutos, When el servicio de monitoreo detecta la inactividad, Then marca el estado del hardware como "Offline" en la base de datos.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Notificación Offline</td>
      <td>Como cuidador, quiero saber si el pastillero pierde conexión, para verificar si mi familiar está recibiendo las alertas adecuadamente.</td>
      <td>Given que el estado del dispositivo cambia a "Offline", When se detecta la pérdida de señal, Then el sistema envía una alerta de "Desconexión" al cuidador.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Fin de Tratamiento</td>
      <td>Como cuidador, quiero una alerta cuando un tratamiento finaliza, para limpiar el compartimento y dejarlo disponible.</td>
      <td>Given que se ha alcanzado la fecha final programada, When se cumple el último horario de toma, Then el sistema notifica que el compartimento debe ser vaciado.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Visualización de Precio (Landing)</td>
      <td>Como visitante, quiero conocer los planes de adquisición del producto, para evaluar la compra según mi presupuesto.</td>
      <td>Given que el visitante accede a la sección de precios, When selecciona un modelo de dispositivo, Then visualiza el costo único y los servicios incluidos.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>TS05</td>
      <td>API de Notificaciones Push</td>
      <td>Como Developer, quiero integrar un servicio de mensajería (Firebase), para despachar alertas en tiempo real a los dispositivos móviles.</td>
      <td>Given un evento crítico (dosis omitida o alerta ambiental), When el bus de eventos detecta el mensaje, Then el servicio envía el payload al token del dispositivo móvil correspondiente.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Recuperación de Contraseña</td>
      <td>Como cuidador, quiero solicitar un enlace de cambio de clave, para recuperar el acceso si olvido mis credenciales.</td>
      <td>Given que el usuario ingresa su correo en la sección de olvido de clave, When solicita el restablecimiento, Then el sistema envía un token temporal de un solo uso por email.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Reporte de Temperatura (App)</td>
      <td>Como cuidador, quiero ver un gráfico de la temperatura del pastillero de las últimas 24 horas, para asegurar que el ambiente es estable.</td>
      <td>Given que existen datos de telemetría, When el usuario abre la pestaña de "Ambiente", Then el sistema genera una gráfica con las fluctuaciones térmicas registradas.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Soporte Técnico (Landing)</td>
      <td>Como visitante con dudas técnicas, quiero acceder a una sección de Preguntas Frecuentes (FAQ), para resolver problemas comunes de instalación.</td>
      <td>Given que el visitante ingresa al pie de página, When selecciona el enlace de Soporte, Then visualiza una lista de soluciones a problemas técnicos frecuentes.</td>
      <td>EP01</td>
    </tr>
  </tbody>
</table>

## 3.2. Impact Mapping
## 3.3. Product Backlog

<table border="1">
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story Id</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>US01</td><td>Información del Producto</td><td>Como visitante de la Landing Page, quiero visualizar las características de Dosys, para entender los beneficios del producto.</td><td>2</td></tr>
    <tr><td>2</td><td>US16</td><td>Sección de Beneficios</td><td>Como cuidador visitante, quiero leer testimonios y casos de éxito, para confiar en la eficacia de la solución.</td><td>3</td></tr>
    <tr><td>3</td><td>US20</td><td>Visualización de Precio</td><td>Como visitante, quiero conocer los planes de adquisición, para evaluar la compra según mi presupuesto.</td><td>1</td></tr>
    <tr><td>4</td><td>US02</td><td>Formulario de Contacto</td><td>Como visitante interesado, quiero enviar mis datos, para recibir asesoría personalizada.</td><td>2</td></tr>
    <tr><td>5</td><td>US09</td><td>Alerta Multimodal</td><td>Como paciente, quiero escuchar un mensaje de voz y ver un LED, para identificar mi medicina sin confusión.</td><td>8</td></tr>
    <tr><td>6</td><td>US10</td><td>Confirmación de Toma</td><td>Como paciente, quiero presionar un botón físico tras ingerir la pastilla, para registrar mi cumplimiento.</td><td>5</td></tr>
    <tr><td>7</td><td>US05</td><td>Registro de Medicina</td><td>Como cuidador, quiero registrar un fármaco en el sistema, para tenerlo disponible en la configuración.</td><td>3</td></tr>
    <tr><td>8</td><td>US06</td><td>Programación de Dosis</td><td>Como cuidador, quiero definir la hora y frecuencia de una toma, para que el paciente reciba recordatorios.</td><td>5</td></tr>
    <tr><td>9</td><td>US07</td><td>Asignación de Compartimento</td><td>Como cuidador, quiero asignar una medicina a un compartimento físico (1-5), para vincular el hardware.</td><td>3</td></tr>
    <tr><td>10</td><td>US11</td><td>Monitoreo de Humedad</td><td>Como cuidador, quiero alertas si la humedad sube, para evitar que las pastillas se degraden.</td><td>5</td></tr>
    <tr><td>11</td><td>US12</td><td>Alerta de Temperatura</td><td>Como cuidador, quiero avisos si hay calor excesivo, para proteger la integridad química de los fármacos.</td><td>5</td></tr>
    <tr><td>12</td><td>US13</td><td>Alerta de Recarga</td><td>Como cuidador, quiero un aviso cuando queden pocas pastillas, para reponer el stock a tiempo.</td><td>3</td></tr>
    <tr><td>13</td><td>US14</td><td>Posponer Alerta (Snooze)</td><td>Como paciente, quiero silenciar la alarma por 5 minutos, para tomar la medicina después si estoy ocupado.</td><td>3</td></tr>
    <tr><td>14</td><td>US08</td><td>Consulta de Adherencia</td><td>Como cuidador, quiero ver un historial de dosis, para monitorear el cumplimiento del familiar.</td><td>5</td></tr>
    <tr><td>15</td><td>US22</td><td>Reporte de Temperatura</td><td>Como cuidador, quiero ver un gráfico térmico de las últimas 24h, para asegurar que el ambiente es estable.</td><td>5</td></tr>
    <tr><td>16</td><td>US15</td><td>Ajuste de Volumen</td><td>Como cuidador, quiero regular el volumen del pastillero desde la app, para adaptarlo a la audición del paciente.</td><td>2</td></tr>
    <tr><td>17</td><td>US19</td><td>Fin de Tratamiento</td><td>Como cuidador, quiero una alerta cuando el tratamiento termina, para limpiar el compartimento.</td><td>2</td></tr>
    <tr><td>18</td><td>US03</td><td>Registro de Cuidador</td><td>Como cuidador, quiero crear una cuenta, para empezar a gestionar el dispositivo.</td><td>3</td></tr>
    <tr><td>19</td><td>US04</td><td>Vinculación IoT</td><td>Como cuidador, quiero vincular el hardware mediante ID único, para que la app controle el pastillero.</td><td>5</td></tr>
    <tr><td>20</td><td>US21</td><td>Recuperación de Contraseña</td><td>Como cuidador, quiero solicitar un enlace de cambio de clave, para recuperar mi acceso.</td><td>2</td></tr>
    <tr><td>21</td><td>US17</td><td>Registro de Alergias</td><td>Como cuidador, quiero documentar alergias en el perfil, para tener una referencia en emergencias.</td><td>1</td></tr>
    <tr><td>22</td><td>US18</td><td>Notificación Offline</td><td>Como cuidador, quiero saber si el pastillero pierde conexión, para verificar el estado del sistema.</td><td>3</td></tr>
    <tr><td>23</td><td>US23</td><td>Soporte Técnico (FAQ)</td><td>Como visitante con dudas, quiero acceder a preguntas frecuentes, para resolver problemas de instalación.</td><td>2</td></tr>
  </tbody>
</table>

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming

En esta sección se presenta el modelado detallado del dominio de **Dosys** mediante la técnica de **Design-Level EventStorming**. El objetivo de esta sesión, que tuvo una duración aproximada de 2 horas , fue identificar con precisión los eventos de dominio, comandos y actores que rigen los procesos críticos de la solución IoT.

Se exploraron tres flujos principales: la configuración inicial del tratamiento por el cuidador, el ciclo de vida de los recordatorios de dosis (incluyendo confirmaciones y omisiones) y el monitoreo preventivo de condiciones ambientales a través de sensores integrados.

<div align="center">
  <img src="./imgs/EventStorm 2.png" alt="Design-Level EventStorming Dosys" style="display: block; margin: 0 auto; max-width: 100%; height: auto;">
  <p><i>Enlace de LucidChart: https://lucid.app/lucidchart/20e81f45-c84d-4f8e-9b12-497449d56f40/edit?viewport_loc=1151%2C-3591%2C5338%2C6595%2C0_0&invitationId=inv_31eb482c-fdb4-41c2-9e05-561a08de57ad</i></p>
</div>

#### 4.1.1.1. Candidate Context Discovery

A partir del dominio modelado en el **EventStorm**, el equipo realizó el descubrimiento de los contextos candidatos para descomponer el sistema en límites manejables. Para esta identificación, se aplicaron técnicas como la búsqueda de eventos pivote y la priorización de áreas de mayor valor para el negocio.

Como resultado de esta sesión colaborativa, se definieron tres **Bounded Contexts** principales para **Dosys**: **Access**, encargado de la autenticación; **Medication**, que gestiona la lógica de tratamientos; y **Device**, responsable del control del hardware IoT. A continuación, se presenta la evidencia de los límites identificados sobre el mapa de eventos.

<div align="center">
  <img src="./imgs/EventStorm 1.png" alt="Candidate Context Discovery Dosys" style="display: block; margin: 0 auto; max-width: 100%; height: auto;">
  <p><i>Enlace de LucidChart: https://lucid.app/lucidchart/20e81f45-c84d-4f8e-9b12-497449d56f40/edit?viewport_loc=1151%2C-3591%2C5338%2C6595%2C0_0&invitationId=inv_31eb482c-fdb4-41c2-9e05-561a08de57ad</i></p>
</div>

#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram
#### 4.1.3.2. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams
#### 4.1.3.3. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

La siguiente estructura se ajusta al capítulo **Tactical-Level Domain-Driven Design** del enunciado, considerando que la solución completa está conformada por **RESTful API**, **Edge API** y **Embedded Applications**, y que el diseño táctico debe reflejar los containers involucrados en cada bounded context. 

### 4.2.1. Bounded Context: Access

El bounded context **Access** representa el proceso de registro, autenticación y autorización básica dentro de la solución Dosys.
Su propósito es aislar la gestión de usuarios y accesos del resto del dominio, evitando mezclar reglas de seguridad con reglas de medicación o de operación del dispositivo.

#### 4.2.1.1. Domain Layer

El **Domain Layer** encapsula la lógica principal del acceso al sistema. Incluye la entidad raíz **User**, la gestión de tokens y la relación de acceso entre usuarios y dispositivos.

**Aggregates**

|    Nombre    |        Categoría        |                                                              Descripción                                                              |
| :----------: | :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
|     User     | Entity (Aggregate Root) | Representa a un usuario autenticado del sistema Dosys. Contiene la identidad básica, el correo electrónico y la contraseña protegida. |
| RefreshToken |          Entity         |                 Representa un token de refresco asociado a un usuario autenticado. Permite mantener sesiones seguras.                 |
| DeviceAccess |          Entity         |                          Representa la relación entre un usuario y un dispositivo Dosys al que tiene acceso.                          |

**Value Objects**

|    Nombre    |   Categoría  |                      Descripción                      |
| :----------: | :----------: | :---------------------------------------------------: |
| EmailAddress | Value Object | Encapsula y valida el correo electrónico del usuario. |
| PasswordHash | Value Object |     Representa la contraseña cifrada del usuario.     |

**Enumerations**

|   Nombre   |      Valores     |                      Descripción                     |
| :--------: | :--------------: | :--------------------------------------------------: |
| AccessRole | OWNER, CAREGIVER | Define el rol del usuario respecto a un dispositivo. |

**Attributes**

**User**

| Nombre       | Tipo de dato | Visibilidad | Descripción                              |
| ------------ | ------------ | ----------- | ---------------------------------------- |
| id           | UUID         | Private     | Identificador único del usuario.         |
| fullName     | String       | Private     | Nombre completo del usuario.             |
| email        | EmailAddress | Private     | Correo electrónico validado del usuario. |
| passwordHash | PasswordHash | Private     | Contraseña cifrada del usuario.          |
| isActive     | Boolean      | Private     | Indica si la cuenta se encuentra activa. |
| createdAt    | DateTime     | Private     | Fecha de creación del usuario.           |

**RefreshToken**

| Nombre    | Tipo de dato | Visibilidad | Descripción                            |
| --------- | ------------ | ----------- | -------------------------------------- |
| id        | UUID         | Private     | Identificador único del token.         |
| userId    | UUID         | Private     | Usuario propietario del token.         |
| token     | String       | Private     | Valor del token de refresco.           |
| expiresAt | DateTime     | Private     | Fecha y hora de expiración.            |
| revokedAt | DateTime?    | Private     | Fecha y hora de revocación, si aplica. |

**DeviceAccess**

| Nombre    | Tipo de dato | Visibilidad | Descripción                                             |
| --------- | ------------ | ----------- | ------------------------------------------------------- |
| id        | UUID         | Private     | Identificador único del acceso.                         |
| userId    | UUID         | Private     | Usuario que posee el acceso.                            |
| deviceId  | UUID         | Private     | Dispositivo Dosys asociado.                             |
| role      | AccessRole   | Private     | Rol del usuario respecto al dispositivo.                |
| isActive  | Boolean      | Private     | Indica si el acceso al dispositivo se encuentra activo. |
| grantedAt | DateTime     | Private     | Fecha en que se concedió el acceso.                     |
| revokedAt | DateTime?    | Private     | Fecha en que se revocó el acceso, si aplica.            |

**Methods**

**User**

| Nombre                                | Tipo de retorno | Visibilidad | Descripción                                                    |
| ------------------------------------- | --------------- | ----------- | -------------------------------------------------------------- |
| User(...) (constructor)               | User            | Public      | Inicializa un usuario con nombre, correo y contraseña cifrada. |
| activate()                            | Void            | Public      | Activa la cuenta del usuario.                                  |
| deactivate()                          | Void            | Public      | Desactiva la cuenta del usuario.                               |
| changePassword(newHash: PasswordHash) | Void            | Public      | Reemplaza la contraseña cifrada por una nueva.                 |

**RefreshToken**

| Nombre                          | Tipo de retorno | Visibilidad | Descripción                            |
| ------------------------------- | --------------- | ----------- | -------------------------------------- |
| RefreshToken(...) (constructor) | RefreshToken    | Public      | Inicializa un nuevo token de refresco. |
| revoke(at: DateTime)            | Void            | Public      | Revoca el token.                       |
| isActive()                      | Boolean         | Public      | Indica si el token sigue activo.       |

**DeviceAccess**

| Nombre                          | Tipo de retorno | Visibilidad | Descripción                                                        |
| ------------------------------- | --------------- | ----------- | ------------------------------------------------------------------ |
| DeviceAccess(...) (constructor) | DeviceAccess    | Public      | Crea una relación de acceso entre usuario y dispositivo.           |
| grant(at: DateTime)             | Void            | Public      | Marca el acceso como activo y actualiza la fecha de concesión.     |
| revoke(at: DateTime)            | Void            | Public      | Revoca el acceso al dispositivo y registra la fecha de revocación. |

**Repositories and Domain Services**

|         Nombre         |         Categoría        |                        Descripción                        |
| :--------------------: | :----------------------: | :-------------------------------------------------------: |
|     UserRepository     |   Repository Interface   |         Abstracción para persistencia de usuarios.        |
| RefreshTokenRepository |   Repository Interface   |      Abstracción para persistencia de refresh tokens.     |
| DeviceAccessRepository |   Repository Interface   | Abstracción para persistencia de accesos por dispositivo. |
|      TokenService      | Domain Service Interface |    Abstracción para generación y validación de tokens.    |
|     PasswordHasher     | Domain Service Interface |     Abstracción para hash y validación de contraseñas.    |

#### 4.2.1.2. Interface Layer

La **Interface Layer** expone las operaciones de acceso mediante la **REST API**.
Se encarga de recibir solicitudes desde las aplicaciones web y móvil, validar el formato de entrada y delegar la lógica al **Application Layer**.

|        Nombre        |     Categoría     |                                            Descripción                                            |
| :------------------: | :---------------: | :-----------------------------------------------------------------------------------------------: |
|   AccessController   |     Controller    | Controlador que expone operaciones de registro, autenticación y consulta del usuario autenticado. |
| AuthExceptionHandler | Exception Handler |               Traductor de errores de autenticación a respuestas HTTP consistentes.               |

**Attributes**

| Nombre               | Tipo de dato          | Visibilidad | Descripción                                                               |
| -------------------- | --------------------- | ----------- | ------------------------------------------------------------------------- |
| accessCommandService | IAccessCommandService | Private     | Servicio de comandos para operaciones de registro e inicio de sesión.     |
| accessQueryService   | IAccessQueryService   | Private     | Servicio de consultas para recuperar información del usuario autenticado. |

**Endpoints**

| Ruta                    | Método | Descripción                                                                       |
| ----------------------- | ------ | --------------------------------------------------------------------------------- |
| /api/v1/access/register | POST   | Registra un nuevo usuario en el sistema.                                          |
| /api/v1/access/login    | POST   | Autentica un usuario y devuelve los tokens de sesión.                             |
| /api/v1/access/me       | GET    | Devuelve la información básica del usuario autenticado y su dispositivo asociado. |

**Request DTOs**

| Nombre             | Descripción                                                                               |
| ------------------ | ----------------------------------------------------------------------------------------- |
| RegisterRequestDto | Contiene los datos necesarios para registrar un usuario: `{ fullName, email, password }`. |
| LoginRequestDto    | Contiene las credenciales para autenticación: `{ email, password }`.                      |

**Response DTOs**

| Nombre                 | Descripción                                                                   |
| ---------------------- | ----------------------------------------------------------------------------- |
| AccessTokenResponseDto | Representa el resultado de login: `{ accessToken, refreshToken, expiresAt }`. |
| UserProfileResponseDto | Representa al usuario autenticado: `{ id, fullName, email, deviceId }`.       |

#### 4.2.1.3. Application Layer

Esta capa coordina los casos de uso del bounded context **Access**, orquestando el dominio y la infraestructura sin contener lógica técnica de bajo nivel.

|          Nombre          | Categoría |                 Implementa                 |                                   Descripción                                  |
| :----------------------: | :-------: | :----------------------------------------: | :----------------------------------------------------------------------------: |
| AccessApplicationService |  Service  | IAccessCommandService, IAccessQueryService | Orquesta el registro de usuarios, autenticación y consulta del usuario actual. |

#### **Dependencies**

| Nombre                 | Tipo de objeto         | Visibilidad | Descripción                                       |
| ---------------------- | ---------------------- | ----------- | ------------------------------------------------- |
| userRepository         | UserRepository         | Private     | Permite consultar y persistir usuarios.           |
| refreshTokenRepository | RefreshTokenRepository | Private     | Permite registrar y recuperar refresh tokens.     |
| deviceAccessRepository | DeviceAccessRepository | Private     | Permite vincular usuarios con dispositivos.       |
| tokenService           | TokenService           | Private     | Genera y valida access tokens y refresh tokens.   |
| passwordHasher         | PasswordHasher         | Private     | Realiza hash y validación de contraseñas.         |
| unitOfWork             | UnitOfWork             | Private     | Maneja confirmación transaccional de operaciones. |

#### **Methods**

| Nombre                                  | Tipo de retorno        | Visibilidad | Descripción                                                                |
| --------------------------------------- | ---------------------- | ----------- | -------------------------------------------------------------------------- |
| registerUser(fullName, email, password) | UserProfileResponseDto | Public      | Registra un nuevo usuario y crea la identidad base en el sistema.          |
| loginUser(email, password)              | AccessTokenResponseDto | Public      | Autentica al usuario y emite sus tokens de sesión.                         |
| getCurrentUser(userId)                  | UserProfileResponseDto | Public      | Obtiene la información del usuario autenticado y su acceso al dispositivo. |

#### 4.2.1.4. Infrastructure Layer

Incluye implementaciones concretas para persistencia, seguridad y generación de tokens.

**Repositories and Services**

|           Nombre          |        Categoría       |       Implementa       |                                Descripción                                |
| :-----------------------: | :--------------------: | :--------------------: | :-----------------------------------------------------------------------: |
|     UserRepositorySql     |       Repository       |     UserRepository     | Implementación para persistencia de usuarios en base de datos relacional. |
| RefreshTokenRepositorySql |       Repository       | RefreshTokenRepository |            Implementación para persistencia de refresh tokens.            |
| DeviceAccessRepositorySql |       Repository       | DeviceAccessRepository |        Implementación para persistencia de accesos por dispositivo.       |
|      JwtTokenService      | Infrastructure Service |      TokenService      |                  Genera y valida JWT para autenticación.                  |
|    BcryptPasswordHasher   | Infrastructure Service |     PasswordHasher     |        Implementación para hash y validación segura de contraseñas.       |

#### **Funcionalidades clave**

* Registrar nuevos usuarios.
* Autenticar credenciales y emitir tokens.
* Consultar el usuario autenticado.
* Persistir accesos entre usuarios y dispositivos.

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

![Access Component Level Diagram](imgs/bounded-contexts/access-component-level-diagram.png)

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

![Access Domain Layer Class Diagram](imgs/bounded-contexts/access-domain-layer-class-diagram.png)

##### 4.2.1.6.2. Bounded Context Database Design Diagram

![Access Database Design Diagram](imgs/bounded-contexts/access-database-design-diagram.png)

---

### 4.2.2. Bounded Context: Medication

El bounded context **Medication** representa la gestión principal del negocio de Dosys.
Su responsabilidad es administrar los contenedores del pastillero, los medicamentos asociados a cada contenedor, sus horarios, el historial de cumplimiento de tomas y la visualización del estado ambiental que consulta el usuario en las aplicaciones Web y Mobile.

La raíz agregada del contexto se mantiene en **MedicationContainer** porque la configuración del negocio se realiza contenedor por contenedor, y cada horario siempre se asocia a un único contenedor. Los cambios de `configVersion` del dispositivo no forman parte de una invariante del agregado, sino de un proceso de coordinación del **Application Layer** que notifica al bounded context **Device** que la configuración operativa debe resincronizarse.

#### 4.2.2.1. Domain Layer

El **Domain Layer** encapsula la lógica principal de medicación y adherencia.
Incluye el agregado raíz **MedicationContainer**, las reglas para horarios, el registro de cumplimiento y los modelos de lectura con los que Web y Mobile consultan el estado ambiental previamente sincronizado desde el bounded context **Device**.

**Aggregates**

|        Nombre       |        Categoría        |                                                              Descripción                                                             |
| :-----------------: | :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------: |
| MedicationContainer | Entity (Aggregate Root) | Representa un contenedor físico del pastillero y su configuración lógica, incluyendo el medicamento asociado y la cantidad restante. |
|  MedicationSchedule |          Entity         |                                   Representa un horario configurado para un contenedor específico.                                   |
|     IntakeRecord    |          Entity         |                                Representa un registro de cumplimiento asociado a una toma programada.                                |

**Read Models**

|         Nombre         |      Categoría      |                                                Descripción                                               |
| :--------------------: | :-----------------: | :------------------------------------------------------------------------------------------------------: |
|   EnvironmentSnapshot  | Entity (Read Model) | Representa la última lectura ambiental sincronizada desde el bounded context Device para un dispositivo. |
| EnvironmentReadingView | Entity (Read Model) |         Representa una lectura ambiental histórica disponible para consulta en las aplicaciones.         |

**Value Objects**

|      Nombre     |   Categoría  |                                 Descripción                                |
| :-------------: | :----------: | :------------------------------------------------------------------------: |
| ContainerNumber | Value Object | Encapsula el número de contenedor válido dentro del rango del dispositivo. |
|    DailyTime    | Value Object |                Representa la hora exacta de un recordatorio.               |
|    DaysOfWeek   | Value Object |                 Representa los días activos de un horario.                 |
|   PillQuantity  | Value Object |                Encapsula la cantidad restante de pastillas.                |

**Enumerations**

|         Nombre        |    Valores    |                               Descripción                               |
| :-------------------: | :-----------: | :---------------------------------------------------------------------: |
|    AdherenceStatus    | TAKEN, MISSED |        Define el estado del cumplimiento de una toma programada.        |
| EnvironmentRiskStatus |  NORMAL, RISK | Define el estado de riesgo de una lectura ambiental visible al usuario. |

**Attributes**

**MedicationContainer**

| Nombre          | Tipo de dato    | Visibilidad | Descripción                                       |
| --------------- | --------------- | ----------- | ------------------------------------------------- |
| id              | UUID            | Private     | Identificador único del contenedor lógico.        |
| deviceId        | UUID            | Private     | Dispositivo Dosys al que pertenece el contenedor. |
| containerNumber | ContainerNumber | Private     | Número de contenedor dentro del dispositivo.      |
| medicationName  | String          | Private     | Nombre del medicamento asignado.                  |
| dosageLabel     | String          | Private     | Descripción breve de dosis o uso.                 |
| remainingPills  | PillQuantity    | Private     | Cantidad restante de pastillas.                   |
| isEnabled       | Boolean         | Private     | Indica si el contenedor está habilitado.          |
| updatedAt       | DateTime        | Private     | Última actualización del contenedor.              |

**MedicationSchedule**

| Nombre          | Tipo de dato    | Visibilidad | Descripción                               |
| --------------- | --------------- | ----------- | ----------------------------------------- |
| id              | UUID            | Private     | Identificador único del horario.          |
| deviceId        | UUID            | Private     | Dispositivo asociado.                     |
| containerNumber | ContainerNumber | Private     | Contenedor al que pertenece el horario.   |
| time            | DailyTime       | Private     | Hora de activación del recordatorio.      |
| daysOfWeek      | DaysOfWeek      | Private     | Días en los que se repite el horario.     |
| isActive        | Boolean         | Private     | Indica si el horario se encuentra activo. |
| createdAt       | DateTime        | Private     | Fecha de creación del horario.            |

**IntakeRecord**

| Nombre          | Tipo de dato    | Visibilidad | Descripción                                   |
| --------------- | --------------- | ----------- | --------------------------------------------- |
| id              | UUID            | Private     | Identificador único del registro de toma.     |
| deviceId        | UUID            | Private     | Dispositivo asociado.                         |
| scheduleId      | UUID            | Private     | Horario programado relacionado.               |
| containerNumber | ContainerNumber | Private     | Contenedor correspondiente.                   |
| scheduledAt     | DateTime        | Private     | Fecha y hora programada de la toma.           |
| confirmedAt     | DateTime?       | Private     | Fecha y hora real de confirmación, si existe. |
| status          | AdherenceStatus | Private     | Estado de cumplimiento de la toma.            |

**EnvironmentSnapshot**

| Nombre      | Tipo de dato          | Visibilidad | Descripción                                        |
| ----------- | --------------------- | ----------- | -------------------------------------------------- |
| deviceId    | UUID                  | Private     | Dispositivo al que corresponde la última lectura.  |
| temperature | Decimal               | Private     | Última temperatura sincronizada desde Device.      |
| humidity    | Decimal               | Private     | Última humedad sincronizada desde Device.          |
| recordedAt  | DateTime              | Private     | Fecha y hora de la lectura más reciente.           |
| riskStatus  | EnvironmentRiskStatus | Private     | Estado de riesgo calculado para la última lectura. |

**EnvironmentReadingView**

| Nombre      | Tipo de dato          | Visibilidad | Descripción                                  |
| ----------- | --------------------- | ----------- | -------------------------------------------- |
| id          | UUID                  | Private     | Identificador único de la lectura histórica. |
| deviceId    | UUID                  | Private     | Dispositivo asociado.                        |
| temperature | Decimal               | Private     | Temperatura sincronizada desde Device.       |
| humidity    | Decimal               | Private     | Humedad sincronizada desde Device.           |
| recordedAt  | DateTime              | Private     | Fecha y hora de la lectura histórica.        |
| riskStatus  | EnvironmentRiskStatus | Private     | Estado de riesgo asociado a la lectura.      |

**Methods**

**MedicationContainer**

| Nombre                                         | Tipo de retorno     | Visibilidad | Descripción                                           |
| ---------------------------------------------- | ------------------- | ----------- | ----------------------------------------------------- |
| MedicationContainer(...) (constructor)         | MedicationContainer | Public      | Inicializa un contenedor con la configuración básica. |
| updateMedication(name: String, dosage: String) | Void                | Public      | Actualiza el medicamento y su descripción.            |
| updateRemainingPills(quantity: PillQuantity)   | Void                | Public      | Actualiza la cantidad restante de pastillas.          |
| enable()                                       | Void                | Public      | Habilita el contenedor.                               |
| disable()                                      | Void                | Public      | Deshabilita el contenedor.                            |

**MedicationSchedule**

| Nombre                                        | Tipo de retorno    | Visibilidad | Descripción                                     |
| --------------------------------------------- | ------------------ | ----------- | ----------------------------------------------- |
| MedicationSchedule(...) (constructor)         | MedicationSchedule | Public      | Inicializa un horario asociado a un contenedor. |
| activate()                                    | Void               | Public      | Activa el horario.                              |
| deactivate()                                  | Void               | Public      | Desactiva el horario.                           |
| reschedule(time: DailyTime, days: DaysOfWeek) | Void               | Public      | Reconfigura la hora y días del horario.         |

**IntakeRecord**

| Nombre                          | Tipo de retorno | Visibilidad | Descripción                          |
| ------------------------------- | --------------- | ----------- | ------------------------------------ |
| IntakeRecord(...) (constructor) | IntakeRecord    | Public      | Crea un registro de toma programada. |
| markTaken(at: DateTime)         | Void            | Public      | Marca la toma como cumplida.         |
| markMissed()                    | Void            | Public      | Marca la toma como incumplida.       |

**EnvironmentSnapshot**

| Nombre                                                                                                          | Tipo de retorno | Visibilidad | Descripción                                                                                            |
| --------------------------------------------------------------------------------------------------------------- | --------------- | ----------- | ------------------------------------------------------------------------------------------------------ |
| replaceLatest(temperature: Decimal, humidity: Decimal, recordedAt: DateTime, riskStatus: EnvironmentRiskStatus) | Void            | Public      | Reemplaza la última lectura visible del dispositivo con el dato previamente sincronizado desde Device. |

**Repositories**

|              Nombre              |       Categoría      |                                               Descripción                                               |
| :------------------------------: | :------------------: | :-----------------------------------------------------------------------------------------------------: |
|   MedicationContainerRepository  | Repository Interface |                              Abstracción para persistencia de contenedores.                             |
|   MedicationScheduleRepository   | Repository Interface |                                Abstracción para persistencia de horarios.                               |
|      IntakeRecordRepository      | Repository Interface |                           Abstracción para persistencia de registros de toma.                           |
|   EnvironmentSnapshotRepository  | Repository Interface |                  Abstracción para persistencia de la última lectura ambiental visible.                  |
| EnvironmentReadingViewRepository | Repository Interface | Abstracción para persistencia y consulta de lecturas ambientales históricas sincronizadas desde Device. |

#### 4.2.2.2. Interface Layer

La **Interface Layer** expone las operaciones del bounded context **Medication** mediante la **REST API**.
Se encarga de recibir solicitudes externas, validar datos y delegar la lógica de negocio al **Application Layer**.

|        Nombre        |  Categoría |                                                              Descripción                                                              |
| :------------------: | :--------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
| MedicationController | Controller | Controlador que expone operaciones de configuración de contenedores, horarios, consulta de cumplimiento y visualización del ambiente. |

**Attributes**

| Nombre                   | Tipo de dato              | Visibilidad | Descripción                                                                      |
| ------------------------ | ------------------------- | ----------- | -------------------------------------------------------------------------------- |
| medicationQueryService   | IMedicationQueryService   | Private     | Servicio de consulta para contenedores, horarios, adherencia y estado ambiental. |
| medicationCommandService | IMedicationCommandService | Private     | Servicio de comandos para creación y actualización de contenedores y horarios.   |

**Endpoints**

| Ruta                                                               | Método | Descripción                                                                                         |
| ------------------------------------------------------------------ | ------ | --------------------------------------------------------------------------------------------------- |
| /api/v1/medication/devices/{deviceId}/containers                   | GET    | Lista la configuración actual de los contenedores del dispositivo.                                  |
| /api/v1/medication/devices/{deviceId}/containers/{containerNumber} | PUT    | Crea o actualiza la configuración de un contenedor.                                                 |
| /api/v1/medication/devices/{deviceId}/schedules                    | GET    | Lista todos los horarios configurados para el dispositivo.                                          |
| /api/v1/medication/devices/{deviceId}/schedules                    | POST   | Crea un nuevo horario para un contenedor.                                                           |
| /api/v1/medication/devices/{deviceId}/schedules/{scheduleId}       | PUT    | Actualiza un horario existente.                                                                     |
| /api/v1/medication/devices/{deviceId}/schedules/{scheduleId}       | DELETE | Elimina un horario existente.                                                                       |
| /api/v1/medication/devices/{deviceId}/adherence/calendar           | GET    | Devuelve la vista mensual del cumplimiento de tomas.                                                |
| /api/v1/medication/devices/{deviceId}/environment/latest           | GET    | Devuelve la última lectura ambiental sincronizada desde Device y visible en las aplicaciones.       |
| /api/v1/medication/devices/{deviceId}/environment/history          | GET    | Devuelve el historial de lecturas ambientales sincronizadas desde Device dentro del rango indicado. |

**Request DTOs**

| Nombre                    | Descripción                                                                                                                |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| UpsertContainerRequestDto | Contiene los datos necesarios para configurar un contenedor: `{ medicationName, dosageLabel, remainingPills, isEnabled }`. |
| CreateScheduleRequestDto  | Contiene los datos necesarios para crear un horario: `{ containerNumber, time, daysOfWeek, isActive }`.                    |
| UpdateScheduleRequestDto  | Contiene los datos necesarios para actualizar un horario: `{ containerNumber, time, daysOfWeek, isActive }`.               |

**Response DTOs**

| Nombre                            | Descripción                                                                                                                        |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| MedicationContainerResponseDto    | Representa un contenedor configurado: `{ id, deviceId, containerNumber, medicationName, dosageLabel, remainingPills, isEnabled }`. |
| MedicationScheduleResponseDto     | Representa un horario configurado: `{ id, containerNumber, time, daysOfWeek, isActive }`.                                          |
| AdherenceCalendarResponseDto      | Representa una vista mensual de cumplimiento con los registros agrupados por fecha y horario.                                      |
| EnvironmentLatestResponseDto      | Representa la última lectura ambiental visible: `{ deviceId, temperature, humidity, recordedAt, riskStatus }`.                     |
| EnvironmentHistoryItemResponseDto | Representa una lectura ambiental histórica: `{ id, temperature, humidity, recordedAt, riskStatus }`.                               |

#### 4.2.2.3. Application Layer

Esta capa coordina la lógica de negocio entre el dominio, la infraestructura y los casos de uso expuestos por el bounded context **Medication**.

|            Nombre            | Categoría |                     Implementa                     |                                                                     Descripción                                                                     |
| :--------------------------: | :-------: | :------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| MedicationApplicationService |  Service  | IMedicationCommandService, IMedicationQueryService | Orquesta la configuración de contenedores, horarios, consulta del historial de cumplimiento y visualización del ambiente sincronizado desde Device. |

#### **Dependencies**

| Nombre                           | Tipo de objeto                   | Visibilidad | Descripción                                                                                         |
| -------------------------------- | -------------------------------- | ----------- | --------------------------------------------------------------------------------------------------- |
| medicationContainerRepository    | MedicationContainerRepository    | Private     | Accede a la persistencia de contenedores.                                                           |
| medicationScheduleRepository     | MedicationScheduleRepository     | Private     | Accede a la persistencia de horarios.                                                               |
| intakeRecordRepository           | IntakeRecordRepository           | Private     | Permite consultar y registrar cumplimiento de tomas.                                                |
| environmentSnapshotRepository    | EnvironmentSnapshotRepository    | Private     | Permite consultar la última lectura ambiental visible.                                              |
| environmentReadingViewRepository | EnvironmentReadingViewRepository | Private     | Permite consultar el historial de lecturas ambientales sincronizadas desde Device.                  |
| unitOfWork                       | UnitOfWork                       | Private     | Maneja confirmación transaccional de operaciones.                                                   |
| configVersionPublisher           | ConfigVersionPublisher           | Private     | Marca que la configuración del dispositivo fue modificada para sincronización posterior con Device. |

#### **Methods**

| Nombre                                                                                             | Tipo de retorno                         | Visibilidad | Descripción                                                                                                       |
| -------------------------------------------------------------------------------------------------- | --------------------------------------- | ----------- | ----------------------------------------------------------------------------------------------------------------- |
| getContainers(deviceId)                                                                            | List<MedicationContainerResponseDto>    | Public      | Obtiene la configuración actual de los contenedores del dispositivo.                                              |
| upsertContainer(deviceId, containerNumber, medicationName, dosageLabel, remainingPills, isEnabled) | MedicationContainerResponseDto          | Public      | Crea o actualiza la configuración de un contenedor.                                                               |
| getSchedules(deviceId)                                                                             | List<MedicationScheduleResponseDto>     | Public      | Lista los horarios configurados para un dispositivo.                                                              |
| createSchedule(deviceId, containerNumber, time, daysOfWeek, isActive)                              | MedicationScheduleResponseDto           | Public      | Crea un nuevo horario para un contenedor.                                                                         |
| updateSchedule(deviceId, scheduleId, containerNumber, time, daysOfWeek, isActive)                  | MedicationScheduleResponseDto           | Public      | Actualiza un horario existente.                                                                                   |
| deleteSchedule(deviceId, scheduleId)                                                               | Void                                    | Public      | Elimina un horario configurado.                                                                                   |
| getAdherenceCalendar(deviceId, month)                                                              | AdherenceCalendarResponseDto            | Public      | Devuelve la vista mensual del cumplimiento de tomas.                                                              |
| getLatestEnvironment(deviceId)                                                                     | EnvironmentLatestResponseDto            | Public      | Devuelve la última lectura ambiental previamente sincronizada desde Device.                                       |
| getEnvironmentHistory(deviceId, from, to)                                                          | List<EnvironmentHistoryItemResponseDto> | Public      | Devuelve el historial de lecturas ambientales previamente sincronizadas desde Device dentro del rango consultado. |

#### 4.2.2.4. Infrastructure Layer

Incluye implementaciones concretas para acceso a datos y soporte a sincronización de configuración.

**Repositories and Services**

|                Nombre               |        Categoría       |            Implementa            |                                                 Descripción                                                |
| :---------------------------------: | :--------------------: | :------------------------------: | :--------------------------------------------------------------------------------------------------------: |
|   MedicationContainerRepositorySql  |       Repository       |   MedicationContainerRepository  |                Implementación para persistencia de contenedores en base de datos relacional.               |
|   MedicationScheduleRepositorySql   |       Repository       |   MedicationScheduleRepository   |                                Implementación para persistencia de horarios.                               |
|      IntakeRecordRepositorySql      |       Repository       |      IntakeRecordRepository      |                       Implementación para persistencia de registros de cumplimiento.                       |
|   EnvironmentSnapshotRepositorySql  |       Repository       |   EnvironmentSnapshotRepository  |             Implementación para persistencia de la última lectura ambiental visible al usuario.            |
| EnvironmentReadingViewRepositorySql |       Repository       | EnvironmentReadingViewRepository | Implementación para persistencia y consulta de lecturas ambientales históricas sincronizadas desde Device. |
|        ConfigVersionPublisher       | Infrastructure Service |                 —                |        Servicio que incrementa o publica cambios de configuración para resincronización con Device.        |

#### **Funcionalidades clave**

* Crear y actualizar la configuración de los 5 contenedores.
* Crear, modificar y eliminar horarios de medicación.
* Consultar el historial de cumplimiento de tomas.
* Consultar la última lectura ambiental visible y el historial de lecturas previamente sincronizadas desde Device.
* Marcar cambios de configuración para sincronización con el bounded context Device.

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

![Medication Component Level Diagram](imgs/bounded-contexts/medication-component-level-diagram.png)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

![Medication Domain Layer Class Diagram](imgs/bounded-contexts/medication-domain-layer-class-diagram.png)

##### 4.2.2.6.2. Bounded Context Database Design Diagram

![Medication Database Design Diagram](imgs/bounded-contexts/medication-database-design-diagram.png)

---

### 4.2.3. Bounded Context: Device

El bounded context **Device** representa la operación técnica del pastillero inteligente Dosys.
Este bounded context abarca tres containers de la solución:

* la **REST API** como fuente oficial de verdad y punto de consolidación definitivo,
* la **Edge API** como capa operativa que cachea, transforma y sincroniza,
* y la **Embedded Application** como runtime del dispositivo que consume configuración y reporta eventos.

Su propósito es administrar la configuración operativa del dispositivo, la telemetría ambiental, los eventos de confirmación de tomas, la autenticación del dispositivo y la sincronización entre la **Embedded Application**, la **Edge API** y la **REST API**.

#### 4.2.3.1. Domain Layer

El **Domain Layer** encapsula la lógica principal relacionada con el dispositivo, su configuración runtime, su identidad técnica y los eventos operativos generados por el hardware.

**Aggregates**

|            Nombre           |        Categoría        |                                                                Descripción                                                                |
| :-------------------------: | :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|        DeviceProfile        | Entity (Aggregate Root) | Representa al dispositivo Dosys como entidad operativa dentro del sistema. Incluye su identidad técnica y su credencial de autenticación. |
| DeviceConfigurationSnapshot |          Entity         |                             Representa la configuración operativa compilada que el dispositivo debe consumir.                             |
|      EnvironmentReading     |          Entity         |                                             Representa una lectura ambiental del sensor SHT3X.                                            |
|      DeviceIntakeEvent      |          Entity         |                                 Representa un evento de confirmación de toma generado por el botón físico.                                |
|          StockEvent         |          Entity         |                           Representa un evento de actualización de stock restante reportado por el dispositivo.                           |
|       DeviceHeartbeat       |          Entity         |                                          Representa el estado técnico periódico del dispositivo.                                          |

**Value Objects**

|        Nombre        |   Categoría  |                                             Descripción                                             |
| :------------------: | :----------: | :-------------------------------------------------------------------------------------------------: |
|   TemperatureValue   | Value Object |                       Encapsula el valor de temperatura medido por el sensor.                       |
|     HumidityValue    | Value Object |                         Encapsula el valor de humedad medido por el sensor.                         |
| ConfigurationVersion | Value Object |               Representa la versión vigente de configuración runtime del dispositivo.               |
|     DeviceKeyHash    | Value Object | Representa la credencial cifrada del dispositivo utilizada para autenticar solicitudes al Edge API. |

**Enumerations**

|       Nombre      |         Valores         |                              Descripción                             |
| :---------------: | :---------------------: | :------------------------------------------------------------------: |
|     SyncStatus    | PENDING, SYNCED, FAILED |  Define el estado de sincronización de un evento hacia la REST API.  |
| IntakeEventStatus |      TAKEN, MISSED      | Define el estado funcional de una toma reportada por el dispositivo. |

**Attributes**

**DeviceProfile**

| Nombre        | Tipo de dato         | Visibilidad | Descripción                                                                         |
| ------------- | -------------------- | ----------- | ----------------------------------------------------------------------------------- |
| id            | UUID                 | Private     | Identificador único del dispositivo.                                                |
| serialNumber  | String               | Private     | Identificador físico o serial del dispositivo.                                      |
| deviceKeyHash | DeviceKeyHash        | Private     | Credencial cifrada del dispositivo utilizada para autenticación frente al Edge API. |
| configVersion | ConfigurationVersion | Private     | Versión de configuración actualmente aplicada.                                      |
| isEnabled     | Boolean              | Private     | Indica si el dispositivo se encuentra habilitado para operar.                       |
| lastSeenAt    | DateTime?            | Private     | Última fecha en que el dispositivo reportó actividad.                               |
| status        | String               | Private     | Estado operativo actual del dispositivo.                                            |

**DeviceConfigurationSnapshot**

| Nombre               | Tipo de dato         | Visibilidad | Descripción                                    |
| -------------------- | -------------------- | ----------- | ---------------------------------------------- |
| id                   | UUID                 | Private     | Identificador del snapshot de configuración.   |
| deviceId             | UUID                 | Private     | Dispositivo al que pertenece la configuración. |
| configVersion        | ConfigurationVersion | Private     | Versión de configuración generada.             |
| timezone             | String               | Private     | Zona horaria utilizada por el dispositivo.     |
| humidityThreshold    | Decimal              | Private     | Umbral de humedad permitido.                   |
| temperatureThreshold | Decimal              | Private     | Umbral de temperatura permitido.               |

**EnvironmentReading**

| Nombre      | Tipo de dato     | Visibilidad | Descripción                                 |
| ----------- | ---------------- | ----------- | ------------------------------------------- |
| id          | UUID             | Private     | Identificador único de la lectura.          |
| deviceId    | UUID             | Private     | Dispositivo asociado.                       |
| temperature | TemperatureValue | Private     | Valor de temperatura registrado.            |
| humidity    | HumidityValue    | Private     | Valor de humedad registrado.                |
| recordedAt  | DateTime         | Private     | Fecha y hora de la lectura.                 |
| syncStatus  | SyncStatus       | Private     | Estado de sincronización hacia la REST API. |

**DeviceIntakeEvent**

| Nombre          | Tipo de dato      | Visibilidad | Descripción                                                    |
| --------------- | ----------------- | ----------- | -------------------------------------------------------------- |
| id              | UUID              | Private     | Identificador único del evento.                                |
| deviceId        | UUID              | Private     | Dispositivo asociado.                                          |
| scheduleId      | UUID              | Private     | Horario recurrente asociado al evento.                         |
| containerNumber | Integer           | Private     | Contenedor involucrado en la toma.                             |
| scheduledAt     | DateTime          | Private     | Fecha y hora programada de la ocurrencia concreta del horario. |
| confirmedAt     | DateTime          | Private     | Fecha y hora en que el usuario confirmó la toma.               |
| status          | IntakeEventStatus | Private     | Estado funcional de la toma reportada por el dispositivo.      |
| syncStatus      | SyncStatus        | Private     | Estado de sincronización hacia la REST API.                    |

**StockEvent**

| Nombre          | Tipo de dato | Visibilidad | Descripción                             |
| --------------- | ------------ | ----------- | --------------------------------------- |
| id              | UUID         | Private     | Identificador único del evento.         |
| deviceId        | UUID         | Private     | Dispositivo asociado.                   |
| containerNumber | Integer      | Private     | Contenedor al que corresponde el stock. |
| remainingPills  | Integer      | Private     | Cantidad restante reportada.            |
| recordedAt      | DateTime     | Private     | Fecha y hora del evento.                |
| syncStatus      | SyncStatus   | Private     | Estado de sincronización.               |

**DeviceHeartbeat**

| Nombre        | Tipo de dato | Visibilidad | Descripción                                    |
| ------------- | ------------ | ----------- | ---------------------------------------------- |
| id            | UUID         | Private     | Identificador único del heartbeat.             |
| deviceId      | UUID         | Private     | Dispositivo asociado.                          |
| rtcTime       | DateTime     | Private     | Hora leída desde el RTC DS3231.                |
| wifiConnected | Boolean      | Private     | Indica si el dispositivo tiene conectividad.   |
| deviceStatus  | String       | Private     | Estado operativo reportado por el dispositivo. |
| recordedAt    | DateTime     | Private     | Fecha y hora del heartbeat.                    |
| syncStatus    | SyncStatus   | Private     | Estado de sincronización.                      |

**Methods**

**DeviceProfile**

| Nombre                                             | Tipo de retorno | Visibilidad | Descripción                                                          |
| -------------------------------------------------- | --------------- | ----------- | -------------------------------------------------------------------- |
| DeviceProfile(...) (constructor)                   | DeviceProfile   | Public      | Inicializa el perfil operativo del dispositivo.                      |
| updateConfigVersion(version: ConfigurationVersion) | Void            | Public      | Actualiza la versión de configuración aplicada.                      |
| updateHeartbeat(at: DateTime, status: String)      | Void            | Public      | Actualiza el estado operativo y la última actividad del dispositivo. |
| rotateDeviceKey(newHash: DeviceKeyHash)            | Void            | Public      | Reemplaza la credencial cifrada del dispositivo.                     |
| enable()                                           | Void            | Public      | Habilita el dispositivo para operar.                                 |
| disable()                                          | Void            | Public      | Deshabilita el dispositivo.                                          |

**DeviceConfigurationSnapshot**

| Nombre                                               | Tipo de retorno             | Visibilidad | Descripción                               |
| ---------------------------------------------------- | --------------------------- | ----------- | ----------------------------------------- |
| DeviceConfigurationSnapshot(...) (constructor)       | DeviceConfigurationSnapshot | Public      | Inicializa un snapshot de configuración.  |
| replaceWithNewVersion(version: ConfigurationVersion) | Void                        | Public      | Reemplaza la versión actual del snapshot. |

**EnvironmentReading**

| Nombre                                | Tipo de retorno    | Visibilidad | Descripción                         |
| ------------------------------------- | ------------------ | ----------- | ----------------------------------- |
| EnvironmentReading(...) (constructor) | EnvironmentReading | Public      | Inicializa una lectura ambiental.   |
| markSynced()                          | Void               | Public      | Marca la lectura como sincronizada. |

**DeviceIntakeEvent**

| Nombre                               | Tipo de retorno   | Visibilidad | Descripción                                   |
| ------------------------------------ | ----------------- | ----------- | --------------------------------------------- |
| DeviceIntakeEvent(...) (constructor) | DeviceIntakeEvent | Public      | Inicializa un evento de confirmación de toma. |
| markSynced()                         | Void              | Public      | Marca el evento como sincronizado.            |

**StockEvent**

| Nombre                        | Tipo de retorno | Visibilidad | Descripción                             |
| ----------------------------- | --------------- | ----------- | --------------------------------------- |
| StockEvent(...) (constructor) | StockEvent      | Public      | Inicializa un evento de stock restante. |
| markSynced()                  | Void            | Public      | Marca el evento como sincronizado.      |

**DeviceHeartbeat**

| Nombre                             | Tipo de retorno | Visibilidad | Descripción                              |
| ---------------------------------- | --------------- | ----------- | ---------------------------------------- |
| DeviceHeartbeat(...) (constructor) | DeviceHeartbeat | Public      | Inicializa un heartbeat del dispositivo. |
| markSynced()                       | Void            | Public      | Marca el heartbeat como sincronizado.    |

**Repositories**

|                 Nombre                |       Categoría      |                                    Descripción                                    |
| :-----------------------------------: | :------------------: | :-------------------------------------------------------------------------------: |
|        DeviceProfileRepository        | Repository Interface |  Abstracción para persistencia de perfil del dispositivo y su identidad técnica.  |
| DeviceConfigurationSnapshotRepository | Repository Interface |       Abstracción para persistencia del snapshot de configuración operativa.      |
|      EnvironmentReadingRepository     | Repository Interface | Abstracción para persistencia de lecturas ambientales del bounded context Device. |
|      DeviceIntakeEventRepository      | Repository Interface |  Abstracción para persistencia de eventos de toma reportados por el dispositivo.  |
|          StockEventRepository         | Repository Interface |            Abstracción para persistencia de eventos de stock restante.            |
|       DeviceHeartbeatRepository       | Repository Interface |                    Abstracción para persistencia de heartbeats.                   |
|         PendingSyncRepository         | Repository Interface |   Abstracción para persistencia de eventos pendientes de sincronización en Edge.  |

#### 4.2.3.2. Interface Layer

La **Interface Layer** expone las operaciones del bounded context **Device** en los tres containers que forman parte de su implementación: la **REST API** interna, la **Edge API** y la **Embedded Application**.

##### **REST API (internal)**

La parte interna de la **REST API** expone el contrato de sincronización entre la **Edge API** y la fuente oficial de verdad del sistema.
Estos endpoints no son consumidos por el usuario final. Son consumidos únicamente por la **Edge API** para sincronizar configuración y eventos definitivos.

|        Nombre        |  Categoría |                                           Descripción                                          |
| :------------------: | :--------: | :--------------------------------------------------------------------------------------------: |
| DeviceSyncController | Controller | Controlador interno de la REST API que expone operaciones de sincronización entre Edge y REST. |

**Attributes**

| Nombre                   | Tipo de dato              | Visibilidad | Descripción                                                        |
| ------------------------ | ------------------------- | ----------- | ------------------------------------------------------------------ |
| deviceRestCommandService | IDeviceRestCommandService | Private     | Servicio de comandos para consolidar eventos provenientes de Edge. |
| deviceRestQueryService   | IDeviceRestQueryService   | Private     | Servicio de consultas para devolver configuración runtime oficial. |

**Endpoints**

| Ruta                                                    | Método | Descripción                                                              |
| ------------------------------------------------------- | ------ | ------------------------------------------------------------------------ |
| /api/v1/device/internal/{deviceId}/runtime-config       | GET    | Devuelve la configuración runtime oficial y consolidada del dispositivo. |
| /api/v1/device/internal/{deviceId}/intake-events        | POST   | Consolida de forma definitiva un evento de toma recibido desde Edge.     |
| /api/v1/device/internal/{deviceId}/environment-readings | POST   | Consolida de forma definitiva una lectura ambiental recibida desde Edge. |
| /api/v1/device/internal/{deviceId}/stock-events         | POST   | Consolida de forma definitiva un evento de stock recibido desde Edge.    |
| /api/v1/device/internal/{deviceId}/heartbeats           | POST   | Consolida de forma definitiva un heartbeat recibido desde Edge.          |

**Request DTOs**

| Nombre                               | Descripción                                                                                      |
| ------------------------------------ | ------------------------------------------------------------------------------------------------ |
| InternalDeviceIntakeEventRequestDto  | Contiene un evento de toma: `{ scheduleId, containerNumber, scheduledAt, confirmedAt, status }`. |
| InternalEnvironmentReadingRequestDto | Contiene una lectura ambiental: `{ temperature, humidity, recordedAt }`.                         |
| InternalStockEventRequestDto         | Contiene un evento de stock: `{ containerNumber, remainingPills, recordedAt }`.                  |
| InternalDeviceHeartbeatRequestDto    | Contiene un heartbeat: `{ rtcTime, wifiConnected, deviceStatus, recordedAt }`.                   |

**Response DTOs**

| Nombre                           | Descripción                                                                                                                                                 |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| InternalRuntimeConfigResponseDto | Representa la configuración runtime oficial: `{ deviceId, configVersion, timezone, humidityThreshold, temperatureThreshold, containers, activeSchedules }`. |
| InternalAcceptedSyncResponseDto  | Representa la aceptación de un evento consolidado: `{ accepted, eventId, syncStatus }`.                                                                     |

##### **Edge API**

La parte de **Edge API** expone el contrato operativo que consume el dispositivo.
El dispositivo no envía `deviceId` por ruta. En todas las solicitudes a `/edge/v1/device/*` debe enviar una credencial técnica, por ejemplo `X-Device-Key`, y la Edge API resuelve el `deviceId` a partir de esa credencial antes de delegar la lógica al **Application Layer**.

|      Nombre      |    Categoría   |                                                         Descripción                                                         |
| :--------------: | :------------: | :-------------------------------------------------------------------------------------------------------------------------: |
| DeviceController |   Controller   |         Controlador de la Edge API que expone configuración runtime, telemetría, eventos de toma, stock y heartbeat.        |
| DeviceAuthFilter | Request Filter | Componente que valida `X-Device-Key`, resuelve `deviceId` y rechaza solicitudes de dispositivos inválidos o deshabilitados. |

**Attributes**

| Nombre               | Tipo de dato              | Visibilidad | Descripción                                                               |
| -------------------- | ------------------------- | ----------- | ------------------------------------------------------------------------- |
| deviceCommandService | IDeviceEdgeCommandService | Private     | Servicio de comandos para registrar telemetría y eventos del dispositivo. |
| deviceQueryService   | IDeviceEdgeQueryService   | Private     | Servicio de consultas para configuración runtime del dispositivo.         |

**Endpoints**

| Ruta                                 | Método | Descripción                                                                                 |
| ------------------------------------ | ------ | ------------------------------------------------------------------------------------------- |
| /edge/v1/device/config               | GET    | Devuelve la configuración operativa vigente que debe consumir el dispositivo autenticado.   |
| /edge/v1/device/environment-readings | POST   | Registra una lectura de temperatura y humedad reportada por el dispositivo autenticado.     |
| /edge/v1/device/intake-events        | POST   | Registra la confirmación de una toma desde el botón físico para el dispositivo autenticado. |
| /edge/v1/device/stock-events         | POST   | Registra el stock restante reportado por el dispositivo autenticado.                        |
| /edge/v1/device/heartbeats           | POST   | Registra el estado técnico periódico del dispositivo autenticado.                           |

**Request DTOs**

| Nombre                       | Descripción                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------ |
| EnvironmentReadingRequestDto | Contiene una lectura ambiental: `{ temperature, humidity, recordedAt }`.                         |
| DeviceIntakeEventRequestDto  | Contiene un evento de toma: `{ scheduleId, containerNumber, scheduledAt, confirmedAt, status }`. |
| StockEventRequestDto         | Contiene un evento de stock: `{ containerNumber, remainingPills, recordedAt }`.                  |
| DeviceHeartbeatRequestDto    | Contiene un heartbeat del dispositivo: `{ rtcTime, wifiConnected, deviceStatus, recordedAt }`.   |

**Response DTOs**

| Nombre                         | Descripción                                                                                                                                                                                |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DeviceRuntimeConfigResponseDto | Representa la configuración operativa entregada al dispositivo autenticado: `{ deviceId, configVersion, timezone, humidityThreshold, temperatureThreshold, containers, activeSchedules }`. |
| AcceptedEventResponseDto       | Representa la aceptación de un evento recibido: `{ accepted, localEventId, syncStatus }`.                                                                                                  |

##### **Embedded Application**

La parte de **Embedded Application** contiene los consumidores y adaptadores que permiten que el firmware del ESP32 interactúe con la Edge API y con los componentes físicos del dispositivo.

|     Nombre     | Categoría |                                  Descripción                                  |
| :------------: | :-------: | :---------------------------------------------------------------------------: |
|  EdgeApiClient |  Consumer | Cliente HTTP utilizado por la Embedded Application para consumir la Edge API. |
|  SensorReader  |  Consumer |   Consumidor que obtiene datos de los sensores para reportarlos al Edge API.  |
| ButtonListener |  Consumer |    Consumidor que detecta confirmaciones de toma y las reporta al Edge API.   |
|    RtcReader   |  Consumer |   Consumidor que obtiene la hora desde el RTC para ejecutar alertas locales.  |

#### 4.2.3.3. Application Layer

Esta capa coordina la lógica de negocio entre el dominio operativo del dispositivo, la persistencia local de Edge, la consolidación en la **REST API** y la ejecución del runtime embebido.

##### **REST API (internal)**

La parte interna de la **REST API** consolida los datos definitivos del dispositivo.
Aquí la REST API actúa como fuente oficial de verdad. La Edge API no decide el estado final del sistema; solo cachea, transforma y sincroniza.

|            Nombre            | Categoría |                     Implementa                     |                                                        Descripción                                                       |
| :--------------------------: | :-------: | :------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: |
| DeviceRestApplicationService |  Service  | IDeviceRestCommandService, IDeviceRestQueryService | Orquesta la construcción de configuración runtime oficial y la consolidación definitiva de eventos provenientes de Edge. |

#### **Dependencies**

| Nombre                                | Tipo de objeto                        | Visibilidad | Descripción                                                                                               |
| ------------------------------------- | ------------------------------------- | ----------- | --------------------------------------------------------------------------------------------------------- |
| deviceProfileRepository               | DeviceProfileRepository               | Private     | Accede al perfil técnico del dispositivo.                                                                 |
| deviceConfigurationSnapshotRepository | DeviceConfigurationSnapshotRepository | Private     | Accede a snapshots oficiales de configuración runtime.                                                    |
| environmentReadingRepository          | EnvironmentReadingRepository          | Private     | Permite persistir lecturas ambientales definitivas.                                                       |
| deviceIntakeEventRepository           | DeviceIntakeEventRepository           | Private     | Permite persistir eventos de toma definitivos.                                                            |
| stockEventRepository                  | StockEventRepository                  | Private     | Permite persistir eventos de stock definitivos.                                                           |
| deviceHeartbeatRepository             | DeviceHeartbeatRepository             | Private     | Permite persistir heartbeats definitivos.                                                                 |
| runtimeConfigAssembler                | RuntimeConfigAssembler                | Private     | Construye la configuración runtime oficial a partir de la configuración de negocio vigente.               |
| environmentProjectionUpdater          | EnvironmentProjectionUpdater          | Private     | Actualiza las proyecciones visibles por el bounded context Medication.                                    |
| adherenceProjectionUpdater            | AdherenceProjectionUpdater            | Private     | Actualiza los registros de cumplimiento visibles por Medication a partir de eventos de toma consolidados. |
| stockProjectionUpdater                | StockProjectionUpdater                | Private     | Actualiza el stock visible desde el modelo de negocio.                                                    |
| unitOfWork                            | UnitOfWork                            | Private     | Maneja confirmación transaccional en la REST API.                                                         |

#### **Methods**

| Nombre                                                                                       | Tipo de retorno                  | Visibilidad | Descripción                                                                                                                       |
| -------------------------------------------------------------------------------------------- | -------------------------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------- |
| getRuntimeConfig(deviceId)                                                                   | InternalRuntimeConfigResponseDto | Public      | Devuelve la configuración runtime oficial del dispositivo.                                                                        |
| registerIntakeEvent(deviceId, scheduleId, containerNumber, scheduledAt, confirmedAt, status) | InternalAcceptedSyncResponseDto  | Public      | Consolida definitivamente un evento de toma proveniente de Edge y actualiza la proyección de adherencia consumida por Medication. |
| registerEnvironmentReading(deviceId, temperature, humidity, recordedAt)                      | InternalAcceptedSyncResponseDto  | Public      | Consolida definitivamente una lectura ambiental proveniente de Edge y actualiza las proyecciones visibles por Medication.         |
| registerStockEvent(deviceId, containerNumber, remainingPills, recordedAt)                    | InternalAcceptedSyncResponseDto  | Public      | Consolida definitivamente un evento de stock proveniente de Edge y actualiza el stock visible en el modelo de negocio.            |
| registerHeartbeat(deviceId, rtcTime, wifiConnected, deviceStatus, recordedAt)                | InternalAcceptedSyncResponseDto  | Public      | Consolida definitivamente el estado técnico del dispositivo.                                                                      |

##### **Edge API**

La parte de **Edge API** actúa como capa operativa del dispositivo.
Su responsabilidad es autenticar el dispositivo, resolver `deviceId`, cachear configuración, persistir temporalmente eventos en SQLite y sincronizarlos con la **REST API**.

|            Nombre            | Categoría |                     Implementa                     |                                                             Descripción                                                             |
| :--------------------------: | :-------: | :------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
| DeviceEdgeApplicationService |  Service  | IDeviceEdgeCommandService, IDeviceEdgeQueryService | Orquesta la entrega de configuración runtime, registro de telemetría y sincronización de eventos del dispositivo hacia la REST API. |

#### **Dependencies**

| Nombre                                | Tipo de objeto                        | Visibilidad | Descripción                                                            |
| ------------------------------------- | ------------------------------------- | ----------- | ---------------------------------------------------------------------- |
| deviceProfileRepository               | DeviceProfileRepository               | Private     | Accede al perfil operativo y snapshots del dispositivo en Edge.        |
| deviceConfigurationSnapshotRepository | DeviceConfigurationSnapshotRepository | Private     | Accede a la configuración cacheada del dispositivo en Edge.            |
| pendingSyncRepository                 | PendingSyncRepository                 | Private     | Accede a eventos pendientes de sincronización.                         |
| deviceCredentialResolver              | DeviceCredentialResolver              | Private     | Resuelve `deviceId` a partir de la credencial técnica del dispositivo. |
| runtimeConfigRestClient               | RuntimeConfigRestClient               | Private     | Recupera la configuración oficial desde la REST API.                   |
| restSyncClient                        | RestSyncClient                        | Private     | Sincroniza eventos almacenados localmente con la REST API.             |
| unitOfWork                            | UnitOfWork                            | Private     | Maneja confirmación transaccional en SQLite.                           |

#### **Methods**

| Nombre                                                                                        | Tipo de retorno                | Visibilidad | Descripción                                                                                                                                |
| --------------------------------------------------------------------------------------------- | ------------------------------ | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| getRuntimeConfig(deviceKey)                                                                   | DeviceRuntimeConfigResponseDto | Public      | Valida la credencial técnica, resuelve `deviceId`, refresca caché si es necesario y devuelve la configuración runtime vigente.             |
| registerEnvironmentReading(deviceKey, temperature, humidity, recordedAt)                      | AcceptedEventResponseDto       | Public      | Valida la credencial técnica, resuelve `deviceId`, registra una lectura ambiental y la deja pendiente o sincronizada según disponibilidad. |
| registerIntakeEvent(deviceKey, scheduleId, containerNumber, scheduledAt, confirmedAt, status) | AcceptedEventResponseDto       | Public      | Valida la credencial técnica, resuelve `deviceId`, registra un evento de toma y lo sincroniza con la REST API.                             |
| registerStockEvent(deviceKey, containerNumber, remainingPills, recordedAt)                    | AcceptedEventResponseDto       | Public      | Valida la credencial técnica, resuelve `deviceId`, registra un evento de stock restante y lo sincroniza con la REST API.                   |
| registerHeartbeat(deviceKey, rtcTime, wifiConnected, deviceStatus, recordedAt)                | AcceptedEventResponseDto       | Public      | Valida la credencial técnica, resuelve `deviceId` y registra el estado técnico del dispositivo.                                            |
| syncPendingEvents(deviceId)                                                                   | Void                           | Public      | Reintenta la sincronización de eventos pendientes hacia la REST API.                                                                       |

##### **Embedded Application**

La parte de **Embedded Application** ejecuta las alertas locales del pastillero y reporta datos al Edge.
El firmware no es la fuente oficial de verdad. Solo consume configuración runtime y envía eventos operativos.

|            Nombre           | Categoría |                                                    Descripción                                                   |
| :-------------------------: | :-------: | :--------------------------------------------------------------------------------------------------------------: |
| ConfigurationRefreshService |  Service  | Solicita periódicamente la configuración runtime al Edge API y actualiza la configuración local del dispositivo. |
|    AlertExecutionService    |  Service  |  Evalúa la hora actual del RTC contra los horarios activos y ejecuta las alertas locales mediante LEDs y audio.  |
|  TelemetryReportingService  |  Service  |                          Lee temperatura y humedad y reporta la telemetría al Edge API.                          |
|  ButtonConfirmationService  |  Service  |                Detecta la confirmación física del usuario y reporta el evento de toma al Edge API.               |

#### **Dependencies**

| Nombre           | Tipo de objeto   | Visibilidad | Descripción                                                           |
| ---------------- | ---------------- | ----------- | --------------------------------------------------------------------- |
| edgeApiClient    | EdgeApiClient    | Private     | Cliente HTTP utilizado para consumir la Edge API.                     |
| localConfigStore | LocalConfigStore | Private     | Almacena localmente la configuración runtime vigente del dispositivo. |
| sht3xDriver      | Sht3xDriver      | Private     | Adaptador para lectura del sensor de temperatura y humedad.           |
| ds3231Driver     | Ds3231Driver     | Private     | Adaptador para lectura del RTC.                                       |
| dfPlayerDriver   | DfPlayerDriver   | Private     | Adaptador para reproducción de audio por voz.                         |
| ledController    | LedController    | Private     | Adaptador para control de LEDs de contenedores.                       |
| buttonDriver     | ButtonDriver     | Private     | Adaptador para lectura del botón físico.                              |

#### **Methods**

| Nombre                                                                           | Tipo de retorno | Visibilidad | Descripción                                                                                  |
| -------------------------------------------------------------------------------- | --------------- | ----------- | -------------------------------------------------------------------------------------------- |
| refreshRuntimeConfig()                                                           | Void            | Public      | Solicita la configuración runtime vigente al Edge API y la guarda localmente.                |
| executeAlerts()                                                                  | Void            | Public      | Evalúa la hora actual y dispara la alerta del contenedor correspondiente cuando corresponde. |
| reportEnvironmentReading()                                                       | Void            | Public      | Lee temperatura y humedad y reporta la lectura al Edge API.                                  |
| reportIntakeEvent(scheduleId, containerNumber, scheduledAt, confirmedAt, status) | Void            | Public      | Reporta al Edge API la ocurrencia concreta de una toma programada.                           |
| reportHeartbeat()                                                                | Void            | Public      | Reporta el estado técnico del dispositivo al Edge API.                                       |

#### 4.2.3.4. Infrastructure Layer

Incluye implementaciones concretas para persistencia y sincronización en la **REST API**, persistencia local y cache en la **Edge API**, y adaptadores físicos en la **Embedded Application**.

##### **REST API (internal)**

**Repositories and Services**

|                  Nombre                  |        Categoría       |               Implementa              |                                         Descripción                                         |
| :--------------------------------------: | :--------------------: | :-----------------------------------: | :-----------------------------------------------------------------------------------------: |
|        DeviceProfileRepositorySql        |       Repository       |        DeviceProfileRepository        |     Implementación para persistencia del perfil técnico del dispositivo en la REST API.     |
| DeviceConfigurationSnapshotRepositorySql |       Repository       | DeviceConfigurationSnapshotRepository |                Implementación para persistencia del snapshot runtime oficial.               |
|      EnvironmentReadingRepositorySql     |       Repository       |      EnvironmentReadingRepository     |             Implementación para persistencia definitiva de lecturas ambientales.            |
|      DeviceIntakeEventRepositorySql      |       Repository       |      DeviceIntakeEventRepository      |               Implementación para persistencia definitiva de eventos de toma.               |
|          StockEventRepositorySql         |       Repository       |          StockEventRepository         |               Implementación para persistencia definitiva de eventos de stock.              |
|       DeviceHeartbeatRepositorySql       |       Repository       |       DeviceHeartbeatRepository       |                  Implementación para persistencia definitiva de heartbeats.                 |
|          RuntimeConfigAssembler          | Infrastructure Service |                   —                   | Construye la configuración runtime oficial a partir de la configuración vigente de negocio. |
|       EnvironmentProjectionUpdater       | Infrastructure Service |                   —                   |                Actualiza las proyecciones de ambiente visibles en Medication.               |
|        AdherenceProjectionUpdater        | Infrastructure Service |                   —                   |                Actualiza la proyección de cumplimiento visible en Medication.               |
|          StockProjectionUpdater          | Infrastructure Service |                   —                   |                    Actualiza el stock visible desde el modelo de negocio.                   |

##### **Edge API**

**Repositories and Services**

|                    Nombre                   |        Categoría       |               Implementa              |                                          Descripción                                          |
| :-----------------------------------------: | :--------------------: | :-----------------------------------: | :-------------------------------------------------------------------------------------------: |
|        DeviceProfileRepositorySqlite        |       Repository       |        DeviceProfileRepository        |             Implementación para persistencia de perfil del dispositivo en SQLite.             |
| DeviceConfigurationSnapshotRepositorySqlite |       Repository       | DeviceConfigurationSnapshotRepository |                Implementación para persistencia del snapshot runtime en SQLite.               |
|         PendingSyncRepositorySqlite         |       Repository       |         PendingSyncRepository         |           Implementación para persistencia de eventos pendientes de sincronización.           |
|           DeviceCredentialResolver          | Infrastructure Service |                   —                   | Valida `X-Device-Key`, resuelve `deviceId` y rechaza dispositivos inválidos o deshabilitados. |
|           RuntimeConfigRestClient           | Infrastructure Service |                   —                   |             Cliente HTTP para obtener la configuración oficial desde la REST API.             |
|                RestSyncClient               | Infrastructure Service |                   —                   |             Cliente HTTP para sincronizar eventos locales con la REST API interna.            |

##### **Embedded Application**

**Drivers and Consumers**

|      Nombre      |        Categoría        | Implementa |                                Descripción                                |
| :--------------: | :---------------------: | :--------: | :-----------------------------------------------------------------------: |
|   EdgeApiClient  | Infrastructure Consumer |      —     | Cliente HTTP usado por la Embedded Application para consumir la Edge API. |
| LocalConfigStore |   Infrastructure Store  |      —     |       Persistencia local mínima de la configuración runtime vigente.      |
|    Sht3xDriver   |          Driver         |      —     |        Adaptador para lectura del sensor de temperatura y humedad.        |
|   Ds3231Driver   |          Driver         |      —     |                      Adaptador para lectura del RTC.                      |
|  DfPlayerDriver  |          Driver         |      —     |               Adaptador para reproducción de audio por voz.               |
|   LedController  |          Driver         |      —     |              Adaptador para control de LEDs de contenedores.              |
|   ButtonDriver   |          Driver         |      —     |                  Adaptador para lectura del botón físico.                 |

#### **Funcionalidades clave**

* Exponer en la **REST API** la configuración runtime oficial y los endpoints internos de consolidación definitiva.
* Exponer en la **Edge API** una capa operativa autenticada por credencial técnica del dispositivo.
* Entregar configuración operativa simplificada al ESP32.
* Registrar telemetría ambiental enviada por el dispositivo.
* Registrar eventos de toma confirmada desde el botón físico incluyendo `scheduledAt` y `status`.
* Registrar stock restante reportado por el dispositivo.
* Registrar heartbeats del dispositivo.
* Mantener persistencia local en SQLite y sincronización con la REST API.
* Mantener explícita la diferencia entre **REST API** como fuente oficial de verdad, **Edge API** como capa operativa y **Embedded Application** como consumidor y reportador de eventos.

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

![Device REST Internal Component Level Diagram](imgs/bounded-contexts/device-rest-component-level-diagram.png)

![Device Edge Component Level Diagram](imgs/bounded-contexts/device-edge-component-level-diagram.png)

![Device Embedded Component Level Diagram](imgs/bounded-contexts/device-embedded-component-level-diagram.png)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

![Device Domain Layer Class Diagram](imgs/bounded-contexts/device-domain-layer-class-diagram.png)

##### 4.2.3.6.2. Bounded Context Database Design Diagram

![Device Database Design Diagram](imgs/bounded-contexts/device-database-design-diagram.png)

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
