<div align="center">

# Universidad Peruana de Ciencias Aplicadas

### INFORME DEL TRABAJO 1 (TB1)

<img src="../Assets/Logo-UPC.png">

**Curso:** Diseño de Experimentos de Ingeniería de Software

**Sección:** 1ASI0732

**Profesor:** Julio Manuel Noriega Melendez

**Carrera:** Nombre de la carrera

**Ciclo:** 2025-01

**Startup:** Netvia

**Producto:** SwapService

### Integrantes:

| Nombre                          | Código     |
| ------------------------------- | ---------- |
| Sebastian Cachis Gonzales       | u202210846 |
| Adriano Sebastian Cruz Palomino | u202210697 |
| Amner Levi Llamo Sanchez        | u20221c376 |
| Marcelo Fabian Garro Vega       | u20201c410 |
| Lucio Heli Yen Cerna            | u202213143 |

### Abril del 2025

</div>

<div align="justify">

### Registro de versiones del informe

| Versión | Fecha      | Autor            | Descripción                           |
| ------- | ---------- | ---------------- | ------------------------------------- |
| 1.0     | 05/04/2025 | Adriano Cruz     | Creación de la estructura del informe |
| 1.0     | 06/04/2025 | Sebastian Cachis | Desarrollo de todo el capítulo I      |

### Project Report Collaboration Insights

**TB1**  
Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:

| Integrante              | Tareas Designadas                |
| ----------------------- | -------------------------------- |
| Sebastian Cachis        | Desarrollo de todo el capítulo I |
| [Nombre del integrante] | [Tareas]                         |
| ...                     | ...                              |

Evidencias del Insights Contributos de los commits del informe:

</div>

![image](imagen)

# Tabla de Contenidos

### [Student Outcome](#outcome)

### [Capítulo I: Introducción](#capitulo-i-introduccion)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capitulo-ii-requirements-elicitation--analysis)

- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capitulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Product Backlog](#33-product-backlog)
- [3.4. Impact Mapping](#34-impact-mapping)

### [Capítulo IV: Product Design](#capitulo-iv-product-design)

- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
    - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
    - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
  - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
  - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
  - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
  - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
- [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
  - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
  - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
- [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
  - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
  - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
  - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
  - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
- [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
- [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
  - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
  - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
  - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
- [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
  - [4.9.1. Class Diagrams](#491-class-diagrams)
  - [4.9.2. Class Dictionary](#492-class-dictionary)
- [4.10. Database Design](#410-database-design)
  - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)

### [Capítulo V: Product Implementation](#capitulo-v-product-implementation)

- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Product Implementation & Deployment](#52-product-implementation--deployment)
  - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
  - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
  - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
  - [5.2.4. Implemented Native-Mobile Application Evidence](#524-implemented-native-mobile-application-evidence)
  - [5.2.5. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-andor-serverless-backend-evidence)
  - [5.2.6. RESTful API documentation](#526-restful-api-documentation)
  - [5.2.7. Team Collaboration Insights](#527-team-collaboration-insights)
- [5.3. Video About-the-Product](#53-video-about-the-product)

- [Conclusiones, Bibliografía y Anexos](#conclusiones-bibliografía-y-anexos)

<h1 id="outcome">Student Outcome</h1>

### Student Outcome

| Criterio específico | Acciones Realizadas | Conclusiones |
|---------------------|----------------------|--------------|
| Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software | Sebastian Nicolas Cachis Gonzales<br><b>TB1</b><br>Para esta entrega desarrolle el capitulo 1, hice entrevistas y tambien los diseños para la landingPage<br><br>[Nombre del integrante]<br><b>TB1</b><br>[Descripción de acciones realizadas] | <b>TB1</b><br> Designamos tareas a cada integrante para optimizar el tiempo de trabajo |
| Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales | Sebastian Nicolas Cachis Gonzales <br><b>TB1</b><br>Esto me ha permito tener una mejor vision de los limites y objetivos de nuestro proyecto asi como conocer las inquietudes de nuestros segmentos objetvios<br><br>[Nombre del integrante]<br><b>TB1</b><br>[Descripción de acciones realizadas] | <b>TB1</b><br> Hemos enfocado las habilidades de cada integrante en las areas de desarrollo que mejor dominen para una mejor linea de trabajo |


<h1 id="capitulo-i-introduccion">Capítulo I: Introducción</h1>

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Netvia es una startup tecnológica orientada a diseñar soluciones digitales inteligentes que transformen la manera en que las personas interactúan con los servicios urbanos en el mundo moderno. Fundada por un equipo multidisciplinario con enfoque en innovación, desarrollo escalable y experiencia de usuario, Netvia se posiciona como un agente disruptivo en el sector Tech4UrbanLife (tecnología para la vida urbana), creando plataformas que combinan accesibilidad, eficiencia y sostenibilidad.

Nuestro propósito como empresa es identificar necesidades reales de la vida cotidiana y resolverlas mediante productos tecnológicos que puedan escalar globalmente sin perder el enfoque local. Apostamos por modelos centrados en el usuario, arquitectura modular, y un profundo compromiso con la usabilidad y la confiabilidad de nuestros productos.

Creemos que la tecnología debe estar al servicio de las personas, facilitando experiencias seguras, intuitivas y transparentes. Bajo esta visión, nace nuestro producto principal: SwapService, una aplicación web y mobile diseñada para permitir el trueque de bienes, conocimientos y servicios entre individuos, impulsando una red confiable de usuarios con intereses compartidos.

En Netvia, trabajamos con pasión, creatividad y enfoque ágil para ofrecer productos que generen impacto social, fomenten el desarrollo sostenible y transformen la forma en que las personas interactúan en el entorno digital.

## Misión

Facilitar el intercambio equitativo de habilidades y servicios entre personas, empoderando a las comunidades para crear valor compartido sin intermediación monetaria, promoviendo así una economía colaborativa basada en el talento y las conexiones humanas.

## Visión

Ser la plataforma líder global en intercambio de servicios peer-to-peer, transformando la manera en que las personas intercambian valor, fomentando una sociedad más colaborativa donde el acceso a servicios y conocimientos no esté limitado por restricciones económicas sino potenciado por el talento colectivo de la comunidad.

### 1.1.2. Perfiles de integrantes del equipo

|                                                                                                                                                                                                                                             Descripción de los perfiles de los integrantes del equipo                                                                                                                                                                                                                                              |                                                Foto del integrante                                                |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------: |
|                                                                                                                                Mi nombre es Soy un estudiante de 22 años con interés en el desarrollo web y móvil. Disfruto aprender nuevas tecnologías y colaborar en proyectos donde pueda aportar con mis conocimientos. Me motiva compartir experiencias con otros y crecer junto a mi equipo en cada desafío.                                                                                                                                 |                            <img src="../Assets/teamMembersPhotos/marcelo-perfil.png"/>                            |
|                                                                                                  Mi nombre es **Amner Levi Llamo Sánchez**, soy estudiante del séptimo ciclo de ingeniería de software en la UPC. Me gusta jugar fútbol y videojuegos, por eso estoy constantemente investigando sobre nuevas tecnologías. Soy responsable con los trabajos que se me asignan; además soy tolerante y me adapto a las circunstancias del equipo.                                                                                                   |                 <img src='../Assets/teamMembersPhotos/amnerLlamo.png' width="100" height="100"/>                  |
|                                                                                         Mi nombre es **Sebastian Nicolas Cachis Gonzales**, soy estudiante de séptimo ciclo de ingeniería de software en la UPC. Me considero una persona proactiva, organizada, meticulosa y muy enfocada en mis estudios, tanto grupales como individuales. Tengo facilidad para entender y ejemplificar los distintos temas que vemos, teniendo soltura para explicar.                                                                                          |                           <img src='../Assets/teamMembersPhotos/sebastianCachis.png'/>                            |
|                                                                                                                               Mi nombre es **Adriano Sebastian Cruz Palomino**, tengo 20 años, soy alumno de Ingeniería de Software en la UPC, actualmente estoy cursando el 7mo ciclo. Soy una persona curiosa, responsable, y comprometida con mis estudios, siempre busco aprender más y mejorar mis habilidades.                                                                                                                               |                             <img src='../Assets/teamMembersPhotos/AdrianoCruz.png/'/>                             |
| Mi nombre es **Lucio Heli Yen Cerna**, soy estudiante del séptimo ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona proactiva y organizada que se esmera en construir productos de calidad innovadores. Me apasiona mucho trabajar en equipo, debatir y compartir una misma motivación debido a que siento que aprendo de mis propios compañeros y mejoro como profesional. Por otro lado, mis hobbies son el gimnasio, la música y los videojuegos los cuáles me permiten llevar un estilo de vida balanceado y saludable. | <img src='../Assets/teamMembersPhotos/lucioyen.png' alt = "Foto de perfil de Lucio Yen" width = 100 height = 100> |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

En la actualidad, nos enfrentamos a diversos desafíos socioeconómicos que afectan directamente a la forma en que las personas acceden a servicios y conocimientos:

## Contexto actual

- **Desigualdad económica creciente**: El acceso a servicios profesionales y conocimientos especializados está condicionado por la capacidad económica, creando brechas significativas entre diferentes segmentos de la población.

- **Talento infrautilizado**: Muchas personas poseen habilidades valiosas que no pueden monetizar efectivamente en el mercado laboral tradicional, o que quedan sin aprovecharse por falta de oportunidades.

- **Economía hiperconsumista**: El modelo económico predominante incentiva el consumo continuo y la acumulación, generando problemas de sostenibilidad ambiental y social.

- **Fragmentación comunitaria**: La industrialización y digitalización han debilitado los lazos comunitarios tradicionales donde el intercambio de favores y habilidades era una práctica común.

## Problemáticas específicas

1. **Barrera económica para acceder a servicios**: Muchas personas no pueden permitirse contratar servicios profesionales que necesitan, mientras que quienes ofrecen estos servicios enfrentan periodos de inactividad.

2. **Falta de reconocimiento de habilidades no convencionales**: El sistema económico actual reconoce y valora principalmente habilidades estandarizadas y certificadas formalmente, dejando de lado otras capacidades valiosas.

3. **Ausencia de plataformas efectivas**: Las soluciones existentes para el intercambio de servicios suelen ser:

   - Demasiado locales y de alcance limitado
   - Carentes de sistemas de confianza robustos
   - Sin mecanismos efectivos para equiparar el valor de diferentes servicios
   - Con interfaces poco intuitivas que dificultan las conexiones eficientes

4. **Dependencia excesiva del dinero como único medio de intercambio**: Esta dependencia limita las posibilidades de intercambio cuando hay escasez de recursos monetarios, aun cuando existe abundancia de talentos y tiempo disponible.

SwapService surge como respuesta a estas problemáticas, buscando crear un ecosistema donde el valor se genere y comparta a través del intercambio directo de habilidades y servicios, democratizando el acceso a estos recursos y fortaleciendo el tejido social comunitario.

### 1.2.2. Lean UX Process

El desarrollo de SwapService sigue la metodología Lean UX, que combina el pensamiento Lean Startup con el diseño centrado en el usuario. Este enfoque nos permite validar rápidamente nuestras hipótesis de valor y crear soluciones adaptadas a las necesidades reales de los usuarios con el mínimo de recursos.

## Principios Lean UX aplicados a SwapService

- **Enfoque en los problemas, no en las características**: Priorizamos entender profundamente los problemas de los usuarios antes de diseñar soluciones.
- **Iteraciones pequeñas y rápidas**: Desarrollamos MVP (Producto Mínimo Viable) que podemos poner a prueba rápidamente.
- **Validación continua**: Cada decisión de diseño y desarrollo se valida con usuarios reales.
- **Colaboración multidisciplinaria**: Equipos integrados por diseñadores, desarrolladores y stakeholders.
- **Medición de resultados**: Definimos métricas claras para evaluar el éxito de cada iteración.

### 1.2.2.1. Lean UX Problem Statements

Los Problem Statements nos permiten definir claramente los problemas que buscamos resolver, centrándonos en las necesidades de los usuarios y no en características específicas del producto.

## Problem Statement 1: Acceso a servicios

**Hemos observado que** personas con recursos económicos limitados **tienen dificultades para** acceder a servicios profesionales que necesitan (como clases particulares, asesoría legal básica, diseño gráfico, etc.), **lo que provoca** que renuncien a estos servicios o busquen alternativas subóptimas, **afectando** su desarrollo personal y profesional.

## Problem Statement 2: Aprovechamiento de habilidades

**Hemos observado que** profesionales y personas con habilidades específicas **tienen dificultades para** encontrar canales donde ofrecer sus servicios cuando enfrentan periodos de baja demanda o cuando sus habilidades no son fácilmente monetizables, **lo que provoca** desaprovechamiento de talentos y periodos de inactividad, **afectando** sus oportunidades de desarrollo y networking.

## Problem Statement 3: Confianza en intercambios

**Hemos observado que** las personas interesadas en intercambios no monetarios **tienen dificultades para** establecer relaciones de confianza con desconocidos y para acordar el valor equivalente de servicios diferentes, **lo que provoca** que muchos intercambios potenciales no se materialicen, **afectando** la viabilidad de las economías colaborativas.

## Problem Statement 4: Comunidad y conexión

**Hemos observado que** individuos en entornos urbanos modernos **tienen dificultades para** establecer conexiones significativas basadas en el intercambio de valor con su comunidad más cercana, **lo que provoca** aislamiento y falta de apoyo mutuo, **afectando** la cohesión social y la resiliencia comunitaria.

### 1.2.2.2. Lean UX Assumptions

Las asunciones nos permiten explicitar las creencias que tenemos sobre nuestros usuarios, sus necesidades y el valor que nuestra solución puede aportar.

## Asunciones sobre los usuarios

1. Creemos que nuestros usuarios principales son:

   - Profesionales independientes con periodos de disponibilidad variable
   - Estudiantes y jóvenes profesionales con habilidades pero recursos limitados
   - Personas con habilidades no convencionales difíciles de monetizar
   - Individuos interesados en economías alternativas y consumo responsable

2. Creemos que los usuarios valoran:

   - Acceder a servicios que de otro modo no podrían permitirse
   - La posibilidad de aplicar sus habilidades y conocimientos
   - Experiencias de conexión humana significativas
   - Alternativas al modelo económico tradicional

3. Creemos que los principales problemas de los usuarios son:
   - Falta de recursos económicos para acceder a ciertos servicios
   - Dificultad para encontrar personas que valoren sus habilidades específicas
   - Establecer confianza en intercambios fuera de los canales convencionales
   - Cuantificar el valor de servicios dispares para realizar intercambios justos

## Asunciones sobre la solución

1. Creemos que una plataforma digital facilitará conexiones eficientes entre personas con necesidades y habilidades complementarias.

2. Creemos que un sistema de valoración y reseñas resolverá gran parte del problema de confianza entre desconocidos.

3. Creemos que el establecimiento de categorías y estándares de tiempo ayudará a equiparar el valor de diferentes servicios.

4. Creemos que la experiencia de usuario debe priorizar:
   - Facilidad para describir habilidades y necesidades
   - Sistemas de búsqueda inteligente para sugerir coincidencias potenciales
   - Herramientas de comunicación integradas
   - Mecanismos de verificación y construcción de reputación

## Asunciones sobre el valor para el negocio

1. Creemos que podremos sostener la plataforma mediante:

   - Un modelo freemium con funcionalidades avanzadas de pago
   - Alianzas con entidades educativas y municipalidades interesadas en fomentar economías colaborativas
   - Datos anónimos sobre tendencias de intercambio de servicios

2. Creemos que el crecimiento ocurrirá principalmente a través de:
   - Marketing boca a boca entre usuarios satisfechos
   - Construcción de comunidades locales activas
   - Alianzas estratégicas con organizaciones afines

### 1.2.2.3. Lean UX Hypothesis Statements

Las hipótesis conectan nuestras asunciones con resultados medibles, permitiéndonos validar o refutar nuestras creencias en cada iteración.

## Hipótesis 1: Registro y onboarding

**Creemos que** un proceso de registro que permita a los usuarios categorizar detalladamente sus habilidades y necesidades **ayudará a** los usuarios a encontrar coincidencias relevantes **lo que mediremos** por el porcentaje de usuarios que completan al menos un intercambio en los primeros 30 días tras su registro.

## Hipótesis 2: Sistema de reputación

**Creemos que** implementar un sistema de verificación de identidad y reseñas detalladas **ayudará a** incrementar la confianza entre usuarios **lo que mediremos** por la tasa de intercambios exitosos completados vs. intercambios inicialmente propuestos, y por las evaluaciones positivas de la experiencia.

## Hipótesis 3: Valoración de servicios

**Creemos que** establecer un sistema basado en tiempo y categorización de complejidad para equiparar diferentes servicios **ayudará a** los usuarios a acordar intercambios percibidos como justos por ambas partes **lo que mediremos** por la satisfacción reportada tras el intercambio y la tasa de disputas por inequidad.

## Hipótesis 4: Búsqueda inteligente

**Creemos que** un algoritmo de coincidencia que sugiera proactivamente intercambios potenciales basados en las habilidades y necesidades declaradas **ayudará a** aumentar el número de intercambios realizados **lo que mediremos** por la tasa de adopción de sugerencias automáticas vs. búsquedas manuales.

## Hipótesis 5: Comunidades locales

**Creemos que** fomentar intercambios geográficamente cercanos con funcionalidades específicas **ayudará a** crear comunidades más cohesionadas y aumentará la retención de usuarios **lo que mediremos** por la frecuencia de uso y la tasa de intercambios repetidos entre los mismos usuarios.

## Hipótesis 6: Gamificación

**Creemos que** implementar elementos de gamificación como insignias por habilidades verificadas y reconocimientos por intercambios exitosos **ayudará a** aumentar el compromiso de los usuarios **lo que mediremos** por la frecuencia de visitas a la plataforma y la participación activa en la comunidad.

### 1.2.2.4. Lean UX Canvas

<img src='../Assets/LeanUXCanva.png'/>

## 1.3. Segmentos objetivo

SwapService está dirigido a dos segmentos principales de usuarios que comparten un interés en el intercambio de bienes, conocimientos y servicios, aunque cada grupo presenta características, motivaciones y necesidades distintas según su contexto.

El primer segmento está compuesto por jóvenes universitarios y recién egresados, usualmente entre los 18 y 28 años, que viven en entornos urbanos o zonas cercanas a centros de estudio. Este grupo tiene un alto dominio del entorno digital, utiliza frecuentemente aplicaciones móviles y redes sociales, y cuenta con un presupuesto limitado, lo que los lleva a buscar alternativas económicas para adquirir productos o servicios. Además de intercambiar objetos físicos como ropa, libros o accesorios, estos usuarios también encuentran valor en compartir conocimientos prácticos, como tutorías, ayuda con tareas, o asesorías básicas en tecnología y diseño. Valoran la sostenibilidad, el ahorro y la pertenencia a comunidades colaborativas, y ven en el trueque de conocimientos una forma enriquecedora de aportar y aprender.

El segundo segmento está conformado por adultos jóvenes emprendedores o freelancers, con edades entre 25 y 40 años, que gestionan de forma independiente sus recursos y actividades profesionales. Son personas que buscan intercambiar sus habilidades o productos por otros servicios útiles, como asesorías, diseño, reparación de equipos, marketing, entre otros. En este segmento, el interés en el intercambio de conocimientos y servicios es aún más estratégico: ven en SwapService una oportunidad para ampliar su red profesional, potenciar colaboraciones y acceder a soluciones sin requerir inversión económica directa. Su motivación principal es aprovechar al máximo sus talentos y recursos, mientras crean relaciones de valor dentro de una comunidad dinámica y confiable.

<h1 id="capitulo-ii-requirements-elicitation--analysis">Capítulo II: Requirements Elicitation & Analysis</h1>

## 2.1. Competidores

### 2.1.1. Análisis competitivo

El mercado de plataformas de intercambio de servicios es dinámico y diverso, con varias soluciones que facilitan la conexión entre personas para compartir habilidades y tareas. A continuación, se describen algunas de las plataformas más destacadas en este ámbito.

1. Timebucks
   Timebucks es una plataforma que permite a los usuarios ganar dinero realizando pequeñas tareas en línea, como completar encuestas, ver videos y probar aplicaciones. Ofrece una variedad de tareas accesibles para una amplia audiencia, aunque algunas pueden tener un valor muy bajo.

2. Simbi
   Simbi es una plataforma de intercambio de servicios que permite a los usuarios ofrecer y recibir servicios sin intercambio de dinero, utilizando un sistema de créditos llamado "simbi". Promueve un modelo de economía colaborativa y fomenta la creación de una comunidad de usuarios que valoran el intercambio de habilidades.

3. TaskRabbit
   TaskRabbit conecta a personas que necesitan ayuda con tareas diarias con "Taskers" dispuestos a realizar esas tareas por una tarifa. Ofrece una amplia gama de servicios y facilita la confianza a través de mecanismos de verificación y reseñas, aunque depende del intercambio de dinero y cobra comisiones por los servicios.

### 2.1.2. Estrategias y tácticas frente a competidores

<table> <tr> <th colspan="6" valign="top">Competitive Analysis Landscape</th> </tr> <tr> <td colspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td> <td colspan="4" valign="top">Un análisis competitivo ayuda a identificar oportunidades y mejorar su propuesta de valor para mantenerse relevante en el mercado.</td> </tr> <tr> <td colspan="2" valign="top"></td> <td valign="top">SwapService</td> <td valign="top">Timebucks</td> <td valign="top">Simbi</td> <td valign="top">TaskRabbit</td> </tr> <tr> <td rowspan="2" valign="top">Perfil</td> <td valign="top">Overview</td> <td valign="top">Plataforma de intercambio de servicios sin dinero, fomentando una economía colaborativa.</td> <td valign="top">Plataforma de tareas en línea remuneradas.</td> <td valign="top">Intercambio de servicios basado en créditos sin dinero.</td> <td valign="top">Conecta personas que necesitan ayuda con tareas diarias con "Taskers" por una tarifa.</td> </tr> <tr> <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td> <td valign="top">Acceso a servicios sin barreras económicas y fortalecimiento de la comunidad.</td> <td valign="top">Diversidad de tareas accesibles para ganar dinero.</td> <td valign="top">Intercambio de habilidades sin necesidad de dinero.</td> <td valign="top">Facilidad para encontrar ayuda con tareas diarias.</td> </tr> <tr> <td rowspan="2" valign="top">Perfil de Marketing</td> <td valign="top">Mercado objetivo</td> <td valign="top">Jóvenes universitarios y profesionales independientes.</td> <td valign="top">Usuarios de internet buscando ingresos adicionales.</td> <td valign="top">Personas interesadas en economías colaborativas.</td> <td valign="top">Personas que necesitan ayuda con tareas diarias.</td> </tr> <tr> <td valign="top">Estrategias de marketing</td> <td valign="top">Marketing digital y boca a boca.</td> <td valign="top">Publicidad en línea y redes sociales.</td> <td valign="top">Marketing de contenido y comunidades en línea.</td> <td valign="top">Publicidad local y asociaciones con empresas.</td> </tr> <tr> <td rowspan="3" valign="top">Perfil de Producto</td> <td valign="top">Productos & Servicios</td> <td valign="top">Intercambio de servicios y habilidades.</td> <td valign="top">Tareas en línea remuneradas.</td> <td valign="top">Intercambio de servicios basado en créditos.</td> <td valign="top">Servicios de tareas diarias.</td> </tr> <tr> <td valign="top">Precios & Costos</td> <td valign="top">Sin costo monetario, basado en intercambio.</td> <td valign="top">Pagos por tarea completada.</td> <td valign="top">Sin costo monetario, basado en créditos.</td> <td valign="top">Tarifas por servicio más comisiones.</td> </tr> <tr> <td valign="top">Canales de distribución (Web y/o Móvil)</td> <td valign="top">Aplicación móvil y web.</td> <td valign="top">Aplicación móvil y web.</td> <td valign="top">Aplicación móvil y web.</td> <td valign="top">Aplicación móvil y web.</td> </tr> <tr> <td rowspan="4" valign="top">Análisis SWOT</td> <td valign="top">Fortalezas</td> <td valign="top">Fomento de comunidad y sostenibilidad.</td> <td valign="top">Diversidad de tareas y accesibilidad.</td> <td valign="top">Modelo de intercambio sin dinero.</td> <td valign="top">Facilidad de uso y confianza.</td> </tr> <tr> <td valign="top">Debilidades</td> <td valign="top">Dependencia de la adopción comunitaria.</td> <td valign="top">Valor bajo de algunas tareas.</td> <td valign="top">Confusión potencial con el sistema de créditos.</td> <td valign="top">Dependencia del dinero y comisiones.</td> </tr> <tr> <td valign="top">Oportunidades</td> <td valign="top">Expansión a nuevos mercados y comunidades.</td> <td valign="top">Diversificación de tareas y aumento de valor.</td> <td valign="top">Crecimiento en economías colaborativas.</td> <td valign="top">Expansión de servicios y alianzas.</td> </tr> <tr> <td valign="top">Amenazas</td> <td valign="top">Competencia creciente y cambios en preferencias de usuarios.</td> <td valign="top">Competencia en el mercado de tareas en línea.</td> <td valign="top">Competencia y adopción limitada.</td> <td valign="top">Competencia y dependencia de la economía tradicional.</td> </tr> </table>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Para obtener una comprensión profunda de las necesidades y expectativas de los usuarios potenciales de SwapService, se diseñarán entrevistas estructuradas con preguntas específicas para diferentes segmentos de usuarios. A continuación, se presentan las preguntas para cada grupo:

**Preguntas Generales**

- ¿Qué te motiva a utilizar una plataforma de intercambio de servicios sin dinero?
- ¿Qué tipo de servicios o habilidades estarías dispuesto a ofrecer en una plataforma como SwapService?
- ¿Qué barreras encuentras actualmente para acceder a servicios profesionales que necesitas?
- ¿Cómo evalúas la confianza y seguridad en una plataforma de intercambio de servicios?

**Preguntas para Jóvenes Universitarios y Recién Egresados**

- ¿Con qué frecuencia buscas alternativas económicas para acceder a servicios o productos?
- ¿Qué tipo de servicios o conocimientos te gustaría intercambiar con otros estudiantes o profesionales?
- ¿Cómo te sientes acerca de la idea de intercambiar tiempo y habilidades en lugar de dinero?
- ¿Qué características consideras importantes en una plataforma que facilite el intercambio de servicios entre estudiantes?
- ¿Cómo crees que una plataforma como SwapService podría ayudarte en tu desarrollo personal y profesional?

**Preguntas para Jóvenes Emprendedores o Freelancers**

- ¿Qué desafíos enfrentas actualmente en la monetización de tus habilidades o servicios?
- ¿Cómo gestionas los periodos de baja demanda en tu trabajo freelance?
- ¿Qué tipo de servicios o habilidades te gustaría intercambiar con otros profesionales independientes?
- ¿Cómo evalúas el valor de tus servicios cuando consideras un intercambio no monetario?
- ¿Qué beneficios esperas obtener al participar en una comunidad de intercambio de servicios como SwapService?

### 2.2.2. Registro de entrevistas

| Nombre entrevistado                                        | Augusto Granados                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edad                                                       | 20 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Departamento                                               | Lima, Lima                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| <img src="../Assets/interviewsPhotos/augustogranados.png"> | Augusto Granados no cuenta con el pasar del tiempo, la necesidad de conocer herramientas y métodos estadísticos son muy importantes para poder seguir con su carrera una vez ya egresado. Como el saber programación para la manipulación de datos estadísticos. El contar con una aplicación que le permita intercambiar conocimientos de forma gratuita es de mucha ayuda y factible para quienes no posean con los recursos, pero si tengan la intención de querer seguir aprendiendo y cuente algo que ofrecer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Duración entrevista: 00:00-09:27                           | URL: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210846_upc_edu_pe/EUu1idGzQANCuxR4aUX4dLEBM9jZrfD_o_Am6yvitXcUpQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sVtiCe]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Nombre entrevistado                                        | Walter Cachay                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Edad                                                       | 21 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Departamento                                               | Surco, Lima                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| <img src="../Assets/interviewsPhotos/waltherCachay.png">   | Walter Cachay es un estudiante de 21 años cursando el séptimo ciclo de ingeniería mecatrónica, motivado a utilizar una plataforma de intercambio de servicios sin dinero principalmente por razones económicas. Considera que este modelo podría promover un mejor nivel de enseñanza y aprendizaje tanto nacional como mundialmente, permitiéndole ofrecer sus conocimientos a cambio de aprender de otros. Está dispuesto a enseñar programación básica y avanzada, matemáticas relacionadas con su carrera, y como hobby, enseñar a tocar la trompeta. Las principales barreras que identifica para acceder a servicios profesionales son los costos de suscripciones en plataformas y aplicaciones, especialmente para clases de idiomas como el inglés, que son importantes para mejorar su currículum y son requeridas por la universidad. Para evaluar la confianza en una plataforma, considera fundamentales los comentarios, reseñas y sistemas de calificación.Walter busca alternativas económicas con frecuencia, aproximadamente dos o tres veces por semana, comparando precios y buscando promociones o descuentos para estudiantes. Le interesaría aprender francés, diseño web, economía y profundizar sus conocimientos en programación y automatización. Considera que intercambiar tiempo y habilidades es una idea muy interesante que promueve la ayuda mutua entre personas de distintos lugares. Las características que valora en una plataforma incluyen facilidad de uso, diseño atractivo, sistema de búsqueda eficiente, reseñas visibles y la posibilidad de comunicación directa con los proveedores de servicios. Cree que una plataforma como SwapService podría contribuir significativamente a su desarrollo personal y profesional, permitiéndole acceder a conocimientos y desarrollar habilidades que de otra manera serían inaccesibles por limitaciones económicas, además de descubrir nuevas habilidades que aún no conoce. |
| Duración entrevista 00:00-08:15                            | URL [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EdMQe7U_565KqVCIYAcidt4BNohwZtyNYGp-bDuZQzAV_g?e=wuiJe6]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |

**_Jóvenes Emprendedores o Freelancers_**
|Nombre entrevistado|William Sánchez|
|-|-|
|Edad|24 años|
|Departamento|Lima, Lima|
|<img src="../Assets/interviewsPhotos/williamSanchez.png">|William Sánchez, emprendedor de 24 años especializado en networking, busca utilizar una plataforma de intercambio de servicios sin dinero para optimizar recursos y establecer relaciones profesionales basadas en valor real. Ofrece servicios de estrategias digitales de marketing, consultoría de e-commerce, optimización de negocios y diseño UX/UI. Como emprendedor inicial con presupuesto limitado, enfrenta barreras para acceder a asesoría legal, contabilidad especializada y software, valorando en plataformas de intercambio los sistemas de verificación sólidos, portafolios demostrables y garantías en caso de disputas. Para valorar sus servicios en intercambios no monetarios, considera el tiempo invertido, su tarifa habitual y el valor potencial del servicio que recibe. Le interesaría intercambiar por servicios de copyrighting, SEO, asesoría contable y fiscal para aumentar la productividad de su negocio. Durante periodos de baja demanda, mejora su portafolio, trabaja en proyectos personales y refuerza su networking. De una plataforma como Swap Service espera acceder a servicios profesionales que normalmente no podría costear, expandir su red de contactos y aplicar sus habilidades en diversos contextos para enriquecer su experiencia profesional.|
|Duración entrevista: 00:00-06:38 |URL: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/ETZgkPk0OI1ApIxTCPOS9DkBtVWBa6BQq6cUHcMqI2qyyQ?e=WiaaWG]|

| Nombre entrevistado                                     | George Pimentel                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edad                                                    | 21 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Departamento                                            | Lima, Carabayllo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| <img src="../Assets/interviewsPhotos/georgeAliaga.png"> | George Arturo, un joven de 21 años residente en Carabayllo, se dedica al trabajo freelance ofreciendo servicios como diseño web, edición de video y manejo de redes sociales. Está interesado en plataformas de intercambio de servicios sin dinero porque le permiten acceder a asesorías que actualmente no puede costear, como las legales o contables. Valora la confianza, reputación y transparencia en este tipo de plataformas, y considera importante contar con perfiles verificados y valoraciones. En momentos de baja demanda, se capacita y busca mantenerse activo. Ve en SoftService una oportunidad para colaborar, crecer profesionalmente y acceder a servicios de forma justa y equitativa. |
| Duración entrevista: 00:00-05:33                        | URL: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ER7BSM_iwINOurP5HjvRe8IB5sN8akWzriVxbVVn4NCTMA]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

### 2.2.3. Análisis de entrevistas

**_Jóvenes Universitarios y Recién Egresados_**

La mayoria de los entrevistados ven con buenos ojos la idea de intercambiar habilidades como una solución viable y accesible. Este grupo señala que, debido a sus limitados recursos económicos, se ven constantemente en la necesidad de buscar alternativas que les permitan seguir formándose sin realizar grandes gastos. En ese sentido, Swap Service les parece una propuesta interesante, tanto para adquirir nuevos conocimientos como para compartir lo que ya saben.

Entre los servicios que estarían dispuestos a ofrecer, destacan clases de programación, asesorías en matemáticas y enseñanzas musicales como tocar la trompeta. Sin embargo, también reconocen ciertas barreras que actualmente enfrentan, como el alto costo de cursos, suscripciones a plataformas educativas que no pueden pagar y la presión constante por mejorar su perfil profesional para insertarse en el mercado laboral.

En relación a la confianza en la plataforma, todos coinciden en que sería importante contar con un sistema de calificaciones, comentarios y reseñas, que les permita sentirse más seguros al momento de intercambiar servicios. Varios entrevistados también mencionan que suelen buscar alternativas económicas como promociones para estudiantes o el intercambio de favores entre amigos, lo que refuerza la lógica del trueque como un modelo atractivo y realista.

Finalmente, se evidenció un alto interés por aprender cosas nuevas, tales como idiomas, diseño web, economía, y programación aplicada al análisis de datos.

**_Jóvenes Emprendedores o Freelancers_**

Se identificó que todos buscan formas de continuar desarrollándose profesionalmente sin depender de grandes inversiones. Para este grupo, Swap Service representa una oportunidad para acceder a servicios que normalmente no podrían costear, especialmente en etapas donde los ingresos pueden ser variables. Consideran que el intercambio de habilidades permite valorar el trabajo de cada persona de forma más equitativa y práctica.

Dentro de los servicios que estarían dispuestos a ofrecer, se mencionan áreas como marketing digital, consultoría para e-commerce, diseño UX/UI, y asesorías enfocadas en optimización de negocios. No obstante, también mencionan dificultades comunes como presupuestos ajustados, altos costos de asesoría profesional, y la incertidumbre respecto a la calidad de los servicios cuando no existen referencias previas o un portafolio verificable.

En este sentido, la necesidad de un sistema que brinde seguridad es reiterada por la mayoría. Proponen que la plataforma cuente con mecanismos de verificación de usuarios y respaldo en caso de que una parte no cumpla con lo acordado. Además, comentan que suelen aprovechar los períodos de baja demanda para mejorar su portafolio, trabajar en proyectos personales o fortalecer su presencia en redes profesionales. Otro punto importante es la dificultad que encuentran al competir con freelancers de otros países donde el costo de vida es menor, lo que influye en cómo se percibe el valor de sus servicios.

Los temas de interés para intercambiar conocimientos abarcan desde SEO, copywriting y contabilidad, hasta mentorías personalizadas enfocadas en el crecimiento de negocios. Al considerar un trueque, valoran no solo el tiempo invertido, sino también el impacto que ese servicio puede tener en su desarrollo o ahorro económico.

Finalmente, destacan que lo que más valoran de formar parte de una comunidad como Swap Service es el acceso a servicios de calidad, la posibilidad de ampliar su red de contactos y la aplicación práctica de sus conocimientos en contextos diversos.

## 2.3. Needfinding

### 2.3.1. User Personas

A continuación, se presentan los perfiles de usuario para los dos segmentos objetivo de SwapService: jóvenes universitarios y freelancers. Estos perfiles representan a individuos que buscan maximizar sus recursos y habilidades a través de una plataforma colaborativa, valorando la conexión y el intercambio de conocimientos.

### **User Persona: Usuario Joven Universitario**

<img src="../Assets/chapter2/UserPersonaCarlosLópez.png">

### **User Persona: Joven Freelancer**

<img src="../Assets/chapter2/UserPersonaMaríaFernández.png">

### 2.3.2. User Task Matrix

A continuación, se presenta el User Task Matrix para los segmentos de jóvenes universitarios y freelancers, destacando las tareas que realizan para cumplir sus objetivos en la plataforma SwapService.

### **Segmento Jovenes Universitario**

<table><tr><th rowspan="2" valign="top">Actividades</th><th colspan="2" valign="top">Carlos López</th></tr>
<tr><td valign="top">Frecuencia</td><td valign="top">Importancia</td></tr>
<tr><td valign="bottom">Buscar y ofrecer tutorías</td><td valign="bottom">Alta</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Intercambiar conocimientos prácticos</td><td valign="bottom">Alta</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Buscar colaboraciones en proyectos</td><td valign="bottom">Media</td><td valign="bottom">Media</td></tr>
<tr><td valign="bottom">Utilizar herramientas de colaboración</td><td valign="bottom">Media</td><td valign="bottom">Media</td></tr>
<tr><td valign="bottom">Participar en eventos de networking</td><td valign="bottom">Media</td><td valign="bottom">Alta</td></tr>
</table>

### **Segmento Jovenes Freelancer**

<table><tr><th rowspan="2" valign="top">Actividades</th><th colspan="2" valign="top">María Fernández</th></tr>
<tr><td valign="top">Frecuencia</td><td valign="top">Importancia</td></tr>
<tr><td valign="bottom">Buscar colaboraciones en proyectos</td><td valign="bottom">Alta</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Ofrecer servicios de diseño o asesoría</td><td valign="bottom">Alta</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Utilizar herramientas de colaboración</td><td valign="bottom">Alta</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Participar en eventos de networking</td><td valign="bottom">Alta</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Intercambiar conocimientos prácticos</td><td valign="bottom">Alta</td><td valign="bottom">Alta</td></tr>
</table>

### 2.3.3. User Journey Mapping

A continuación, se presentan los User Journey Mapping para los segmentos de jóvenes universitarios y freelancers, ilustrando sus experiencias al interactuar con SwapService.

### **Segmento Jovenes Universitario**

<img src= "../Assets/chapter2/UserJourneyMappingCarlosLópez.png">

### **Segmento Jovenes Freelancer**

<img src="../Assets/chapter2/UserJourneyMappingMaríaFernandéz.png">

### 2.3.4. Empathy Mapping

Aquí se muestran los Empathy Map para los segmentos de jóvenes universitarios y freelancers, ofreciendo una visión detallada de sus pensamientos, sentimientos y necesidades.

### **Segmento Jovenes Universitario**

<img src="../Assets/chapter2/EmpathyMapCarlosLópez.png">

### **Segmento Jovenes Freelancer**

<img src="../Assets/chapter2/EmpathyMapMaríaFernandéz.png">

### 2.3.5. As-is Scenario Mapping

# Falta

## 2.4. Ubiquitous Language

El Ubiquitous Language es un conjunto de términos y conceptos que comparten los desarrolladores y los expertos del dominio (en este caso, los usuarios de SwapService) para describir el sistema. Su objetivo es reducir la ambigüedad y facilitar la comunicación entre todos los involucrados en el proyecto. A continuación, se presenta un Ubiquitous Language inicial para SwapService:

- Swap: Término principal que define la acción de intercambiar bienes, servicios o conocimientos entre usuarios de la plataforma, sin involucrar dinero directamente.

- Servicio: Habilidad o conocimiento ofrecido por un usuario a otro a cambio de otro servicio o bien. Ejemplos incluyen clases particulares, asesoría legal, diseño gráfico, marketing, reparación de equipos, etc.

- Habilidad: Aptitud o destreza que un usuario posee y puede ofrecer como servicio en la plataforma.

- Conocimiento: Información o experiencia que un usuario comparte o intercambia con otros usuarios.

- Bien: Artículo u objeto físico que un usuario ofrece para intercambiar. Ejemplos incluyen ropa, libros, accesorios, etc.

- Intercambio: Acción de transferir un servicio, habilidad, conocimiento o bien entre dos usuarios.

- Usuario: Persona que utiliza la plataforma SwapService, ya sea para ofrecer o recibir servicios, habilidades, conocimientos o bienes.

- Perfil: Conjunto de datos que identifican a un usuario en la plataforma, incluyendo sus habilidades, servicios ofrecidos, servicios requeridos, información de contacto, etc.

- Necesidad: Requerimiento de un usuario por un servicio, habilidad, conocimiento o bien.

- Oferta: Servicio, habilidad, conocimiento o bien que un usuario pone a disposición de otros usuarios para el intercambio.

- Valoración: Proceso de evaluar la calidad de un servicio, habilidad, conocimiento o bien intercambiado.

- Reputación: Conjunto de valoraciones y comentarios que un usuario recibe por sus intercambios, que refleja su confiabilidad y calidad como proveedor o receptor.

<h1 id="capitulo-iii-requirements-specification">Capítulo III: Requirements Specification</h1>

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

**Epics**
| ID | Título | Descripción |
| ------ | ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP-001 | Landing page | Agrupa todas las funcionalidades de la landing page, incluyendo portada, beneficios, ejemplos de servicios, sección de precios, testimonios, barra de navegación, sección del equipo y footer. |
| EP-002 | Autenticación | Incluye las funcionalidades de registro, inicio de sesión, cierre de sesión y recuperación de contraseña para los usuarios. |
| EP-003 | Perfil de usuario | Permite a los usuarios personalizar sus perfiles, editar sus datos y agregar habilidades para mejorar su visibilidad. |
| EP-004 | Gestión de publicaciones | Se encarga del manejo completo de publicaciones, permitiendo crear, ver, editar y eliminar publicaciones de los usuarios. |
| EP-005 | Sistema de búsqueda | Abarca las funcionalidades de búsqueda, permitiendo filtrar servicios por categoría, búsqueda por palabras clave y la visualización de detalles de los servicios. |
| EP-006 | Proceso de intercambio | Define el flujo de intercambio entre usuarios, incluyendo el envío de propuestas, aceptación o rechazo de intercambios, cancelación de propuestas y seguimiento. |
| EP-007 | Historial de intercambios | Permite a los usuarios acceder a un historial completo de intercambios finalizados y consultar detalles de cada uno, además de dejar comentarios o reseñas. |
| EP-008 | Reviews and Ratings | Se centra en la funcionalidad de calificaciones y reseñas, permitiendo a los usuarios evaluar a otros y consultar los ratings para generar confianza. |
| EP-009 | Comunicaciones | Gestiona la funcionalidad de chat para facilitar la comunicación en tiempo real entre usuarios y coordinar detalles de intercambios. |
| EP-010 | Notificaciones | Engloba la gestión de notificaciones, alertando a los usuarios sobre nuevas propuestas, mensajes y actualizaciones en el estado de sus intercambios. |

**User Stories**
| Epic / Story ID | Título | Descripción | Relacionado con (Epic ID) | Criterios de Aceptación (Given-When-Then) |
| --------------- | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US001 | Ver portada | Como usuario, quiero ver una portada para entender de qué trata la plataforma | EP1 | 1. Dado que el usuario visita la página de inicio, cuando la página carga completamente, entonces ve la portada con título y subtítulo. <br>2. Dado que el usuario ingresa desde dispositivos diversos, cuando se carga la página, entonces la portada se adapta correctamente a cada pantalla. |
| US002 | Ver beneficios | Como usuario, quiero ver los beneficios para entender por qué me conviene | EP1 | 1. Dado que el usuario explora la landing page, cuando llega a la sección de beneficios, entonces se muestran al menos tres beneficios destacados. <br>2. Dado que el usuario consulta la sección de beneficios, cuando se presenta el contenido, entonces la información es clara y fácilmente comprensible. |
| US003 | Ver ejemplos de servicios | Como usuario, quiero ver ejemplos de servicios para imaginar su uso | EP1 | 1. Dado que el usuario accede a la sección de ejemplos, cuando la página carga, entonces se muestran al menos tres tarjetas descriptivas. <br>2. Dado que el usuario interactúa con las tarjetas, cuando selecciona una, entonces se muestra información ampliada sobre el servicio. |
| US004 | Ver precios | Como usuario, quiero ver una sección de precios para conocer los planes | EP1 | 1. Dado que el usuario busca información de precios, cuando accede a la sección, entonces se muestran los planes organizados en una tabla o listado. <br>2. Dado que el usuario compara planes, cuando revisa la sección de precios, entonces se detallan características y valores de cada plan. |
| US005 | Ver testimonios | Como usuario, quiero ver la sección de testimonios para una mayor referencia | EP1 | 1. Dado que el usuario accede a la sección de testimonios, cuando la página carga, entonces se visualizan al menos tres testimonios con nombre e imagen. <br>2. Dado que el usuario desplaza la vista, cuando revisa la sección, entonces los testimonios se muestran en un formato legible y organizado. |
| US006 | Ver barra de navegación | Como usuario, quiero contar con una barra de navegación para facilitar la búsqueda | EP1 | 1. Dado que el usuario se encuentra en cualquier sección, cuando observa la interfaz, entonces la barra de navegación es visible. <br>2. Dado que el usuario interactúa con la barra, cuando selecciona un enlace, entonces es redirigido sin errores a la sección correspondiente. |
| US007 | Ver equipo | Como usuario, quiero ver la sección del equipo para conocer su propósito o historia | EP1 | 1. Dado que el usuario quiere conocer al equipo, cuando ingresa a esa sección, entonces se muestran fotos, nombres y roles de cada miembro. <br>2. Dado que el usuario revisa la historia del equipo, cuando visualiza la sección, entonces se aprecia una breve descripción o propósito de cada integrante. |
| US008 | Ver footer | Como usuario, quiero un footer para acceder a información adicional | EP1 | 1. Dado que el usuario llega al final de la página, cuando la misma carga, entonces el footer es visible con enlaces a contacto y políticas. <br>2. Dado que el usuario explora el footer, cuando revisa su contenido, entonces la información adicional se presenta de forma organizada. |
| US009 | Registrarse | Como usuario, quiero registrarme con correo y contraseña para crear una cuenta | EP2 | 1. Dado que el usuario quiere crear una cuenta, cuando completa todos los campos requeridos, entonces se crea la cuenta y se notifica al usuario. <br>2. Dado que el usuario ingresa un correo duplicado, cuando intenta registrarse, entonces se muestra un mensaje de error pertinente. |
| US010 | Iniciar sesión | Como usuario, quiero iniciar sesión con correo y contraseña para acceder a mi cuenta | EP2 | 1. Dado que el usuario tiene una cuenta, cuando introduce credenciales correctas, entonces inicia sesión y es redirigido al dashboard. <br>2. Dado que el usuario introduce credenciales erróneas, cuando intenta iniciar sesión, entonces se muestra un mensaje de error sin permitir el acceso. |
| US011 | Cerrar sesión | Como usuario, quiero poder cerrar sesión para proteger mi información | EP2 | 1. Dado que el usuario está autenticado, cuando selecciona la opción de cerrar sesión, entonces se termina la sesión y se redirige al login. <br>2. Dado que el usuario cierra sesión, cuando intenta acceder a una sección protegida, entonces se redirige al login. |
| US012 | Recuperar contraseña | Como usuario, quiero poder recuperar mi contraseña para acceder a mi cuenta nuevamente | EP2 | 1. Dado que el usuario olvidó su contraseña, cuando ingresa su correo en el formulario de recuperación, entonces recibe un email con instrucciones. <br>2. Dado que el usuario sigue el enlace del email, cuando establece una nueva contraseña, entonces esta se actualiza correctamente. |
| US013 | Personalizar perfil | Como usuario, quiero personalizar mis datos de perfil para generar confianza en otros usuarios | EP3 | 1. Dado que el usuario desea modificar su perfil, cuando ingresa a la sección de edición, entonces puede actualizar sus datos personales. <br>2. Dado que el usuario guarda los cambios, cuando revisa su perfil, entonces se muestra una confirmación y los datos actualizados. |
| US014 | Agregar habilidades | Como usuario, quiero incluir mis habilidades en mi perfil para obtener mejores resultados en mi búsqueda | EP3 | 1. Dado que el usuario desea destacar sus capacidades, cuando agrega habilidades, entonces estas se muestran en su perfil de forma destacada. <br>2. Dado que el usuario modifica sus habilidades, cuando guarda los cambios, entonces el perfil se actualiza inmediatamente. |
| US015 | Ver publicaciones propias | Como usuario, quiero ver la lista de mis publicaciones para saber qué estoy ofreciendo y necesitando | EP4 | 1. Dado que el usuario tiene publicaciones, cuando accede a la sección correspondiente, entonces se muestra un listado completo. <br>2. Dado que el usuario actualiza una publicación, cuando revisa el listado, entonces los cambios se reflejan en tiempo real. |
| US016 | Ver detalle de publicación | Como usuario, quiero ver los detalles de mis publicaciones para verificar su contenido | EP4 | 1. Dado que el usuario selecciona una publicación, cuando accede a su detalle, entonces se muestran todos los campos de información. <br>2. Dado que la publicación contiene datos extensos, cuando el usuario revisa el detalle, entonces se muestra en un formato ampliado y legible. |
| US017 | Crear publicación | Como usuario, quiero crear una publicación para indicar el servicio que ofrezco y necesito | EP4 | 1. Dado que el usuario desea publicar un intercambio, cuando completa y envía el formulario, entonces la publicación se crea y se visualiza en la lista. <br>2. Dado que el usuario omite campos obligatorios, cuando intenta enviar, entonces se muestra un mensaje de error indicando los datos faltantes. |
| US018 | Editar publicación | Como usuario, quiero editar mis publicaciones para actualizar la información | EP4 | 1. Dado que el usuario tiene una publicación existente, cuando selecciona la opción de editar, entonces puede modificar la información. <br>2. Dado que el usuario guarda los cambios, cuando visualiza la publicación actualizada, entonces se confirma el éxito de la edición. |
| US019 | Eliminar publicación | Como usuario, quiero eliminar mis publicaciones para no ofrecer algo que no deseo | EP4 | 1. Dado que el usuario decide eliminar una publicación, cuando pulsa el botón de eliminación, entonces se solicita confirmación. <br>2. Dado que se confirma la eliminación, cuando finaliza el proceso, entonces la publicación desaparece de la lista. |
| US020 | Buscar servicios | Como usuario, quiero buscar servicios publicados por otros usuarios para encontrar oportunidades | EP5 | 1. Dado que el usuario ingresa criterios en el buscador, cuando ejecuta la búsqueda, entonces se muestran resultados relevantes. <br>2. Dado que el usuario aplica filtros, cuando estos se seleccionan, entonces la búsqueda se refina de acuerdo a los criterios establecidos. |
| US021 | Inicio con servicios relevantes | Como usuario, quiero ver en mi inicio servicios que requieran de mis habilidades para encontrar mayores oportunidades | EP5 | 1. Dado que el usuario tiene habilidades registradas, cuando ingresa al inicio, entonces se muestran servicios que coinciden con su perfil. <br>2. Dado que hay nuevos servicios, cuando el usuario revisa la sección principal, entonces éstos se destacan en función de su relevancia. |
| US022 | Filtrar por categoría | Como usuario, quiero filtrar servicios por categoría para obtener mejores resultados | EP5 | 1. Dado que el usuario selecciona un filtro de categoría, cuando se aplica, entonces sólo se muestran servicios de la categoría elegida. <br>2. Dado que el usuario cambia de categoría, cuando vuelve a realizar la búsqueda, entonces los resultados se actualizan acorde al nuevo filtro. |
| US023 | Buscar por palabras clave | Como usuario, quiero buscar servicios mediante palabras claves para obtener mejores resultados | EP5 | 1. Dado que el usuario introduce términos específicos, cuando inicia la búsqueda, entonces se muestran únicamente servicios relacionados. <br>2. Dado que el usuario ingresa términos ambiguos, cuando se realiza la búsqueda, entonces el sistema ofrece sugerencias o correcciones. |
| US024 | Ver detalle de servicio | Como usuario, quiero ver a detalle los servicios de otros usuarios para conocer la oferta y necesidad | EP5 | 1. Dado que el usuario selecciona un servicio de la lista, cuando accede a su detalle, entonces se muestran todas las especificaciones del servicio. <br>2. Dado que el usuario compara servicios, cuando revisa el detalle, entonces se destacan las características y valoraciones de cada uno. |
| US025 | Contactar a usuario | Como usuario, quiero contactar con otros usuarios para proponer un intercambio | EP6 | 1. Dado que el usuario decide proponer un intercambio, cuando envía una solicitud de contacto, entonces el destinatario recibe la propuesta. <br>2. Dado que el usuario envía una solicitud, cuando se procesa correctamente, entonces aparece una confirmación de envío. |
| US026 | Recibir propuestas | Como usuario, quiero recibir propuestas de otros usuarios interesados para ver todas las ofertas | EP6 | 1. Dado que el usuario ha publicado un servicio, cuando otros usuarios envían propuestas, entonces estas se reflejan en su bandeja de entrada. <br>2. Dado que se recibe una nueva propuesta, cuando se actualiza la lista, entonces se muestra una alerta indicando el nuevo mensaje. |
| US027 | Aceptar o rechazar propuesta | Como usuario, quiero aceptar o rechazar las propuestas de intercambio para decidir con quién colaborar | EP6 | 1. Dado que el usuario recibe una propuesta, cuando revisa los detalles, entonces tiene la opción de aceptar o rechazar mediante botones específicos. <br>2. Dado que se toma una decisión, cuando se actualiza el estado, entonces se notifica inmediatamente a la contraparte. |
| US028 | Cancelar propuesta enviada | Como usuario, quiero cancelar una propuesta de intercambio que envié para retractarme si ya no deseo realizar ese intercambio | EP6 | 1. Dado que el usuario desea cancelar una propuesta, cuando selecciona la opción de cancelar, entonces se solicita confirmación. <br>2. Dado que se confirma la cancelación, cuando se procesa, entonces la propuesta se elimina y se notifica a la parte receptora. |
| US029 | Ver intercambios pendientes | Como usuario, quiero ver una lista de intercambios pendientes para tener un recordatorio | EP6 | 1. Dado que el usuario tiene intercambios en espera, cuando accede a la sección, entonces se muestra un listado actualizado de intercambios pendientes. <br>2. Dado que el estado de un intercambio puede cambiar, cuando se actualizan los datos, entonces la lista se refresca automáticamente. |
| US030 | Ver intercambios activos | Como usuario, quiero ver una lista de intercambios activos para hacer seguimiento a los acuerdos en proceso | EP6 | 1. Dado que el usuario tiene intercambios en curso, cuando ingresa a la sección de activos, entonces se muestran todos los intercambios en estado activo. <br>2. Dado que el intercambio sufre actualizaciones, cuando se refresca la vista, entonces se refleja el estado en tiempo real. |
| US031 | Ver detalle de intercambio | Como usuario, quiero ver los detalles de cada intercambio para conocer a profundidad lo pactado | EP6 | 1. Dado que el usuario selecciona un intercambio, cuando accede a la vista detallada, entonces se muestran todos los términos y condiciones acordados. <br>2. Dado que existen documentos o información adicional, cuando el usuario lo requiere, entonces estos se muestran de forma accesible en la misma vista. |
| US032 | Marcar como completado | Como usuario, quiero marcar un intercambio como completado para finalizar formalmente cuando ambas partes hayan cumplido | EP6 | 1. Dado que ambas partes han cumplido con sus compromisos, cuando el usuario selecciona "Marcar como completado", entonces el intercambio se cierra formalmente. <br>2. Dado que se confirma la finalización, cuando se actualiza el estado, entonces se notifica a ambas partes del cierre del intercambio. |
| US033 | Ver historial de intercambios | Como usuario, quiero ver el historial de mis intercambios completados para tener un registro | EP7 | 1. Dado que el usuario desea revisar sus intercambios pasados, cuando ingresa al historial, entonces se muestra un listado ordenado cronológicamente. <br>2. Dado que el usuario selecciona un intercambio del historial, cuando visualiza los detalles, entonces se muestran toda la información asociada. |
| US034 | Ver detalle de intercambio pasado | Como usuario, quiero acceder a los detalles de un intercambio pasado para recordar qué servicios se ofrecieron y recibieron | EP7 | 1. Dado que el usuario elige un intercambio del historial, cuando accede al detalle, entonces se muestran las condiciones y servicios pactados. <br>2. Dado que el usuario revisa el historial, cuando la información se actualiza, entonces se asegura que los datos mostrados sean correctos y completos. |
| US035 | Dejar comentarios | Como usuario, quiero dejar comentarios o reseñas sobre los intercambios finalizados para compartir mi experiencia | EP7 | 1. Dado que el usuario completó un intercambio, cuando accede a la sección de comentarios, entonces dispone de un formulario para dejar su reseña. <br>2. Dado que el usuario envía su comentario, cuando se procesa, entonces el comentario se asocia y muestra en el historial del intercambio. |
| US036 | Calificar a usuarios | Como usuario, quiero calificar a otros usuarios para compartir mi experiencia sobre sus servicios | EP8 | 1. Dado que el usuario finaliza un intercambio, cuando accede a la funcionalidad de calificación, entonces puede seleccionar una calificación entre 1 y 5 estrellas. <br>2. Dado que el usuario completa la calificación, cuando confirma, entonces el sistema actualiza el promedio de calificaciones del usuario evaluado. |
| US037 | Ver calificaciones | Como usuario, quiero ver las calificaciones y comentarios de otros usuarios para determinar una mejor elección | EP8 | 1. Dado que el usuario consulta el perfil de otro, cuando se carga la sección de calificaciones, entonces se muestran todas las valoraciones previas. <br>2. Dado que se agregan nuevas calificaciones, cuando se actualiza la vista, entonces el promedio y listado se refrescan automáticamente. |
| US038 | Chat entre usuarios | Como usuario, quiero chatear con otros usuarios para coordinar detalles del intercambio | EP9 | 1. Dado que el usuario inicia un chat, cuando abre la ventana de mensajería, entonces puede enviar y recibir mensajes en tiempo real. <br>2. Dado que se envía un mensaje, cuando la comunicación es estable, entonces el mensaje se muestra inmediatamente en la conversación. |
| US039 | Recibir notificaciones | Como usuario, quiero recibir notificaciones de propuestas entrantes para no perder oportunidades | EP10 | 1. Dado que se genera una nueva propuesta, cuando el usuario tiene la sesión activa, entonces recibe una notificación inmediata. <br>2. Dado que existen múltiples alertas, cuando se agrupan, entonces el sistema muestra las notificaciones de forma clara y ordenada. |
| US040 | Desactivar notificaciones | Como usuario, quiero desactivar las notificaciones para evitar recibir alertas que no me interesan | EP10 | 1. Dado que el usuario prefiere no ser interrumpido, cuando accede a la configuración, entonces puede desactivar las notificaciones. <br>2. Dado que el usuario cambia la configuración, cuando guarda los cambios, entonces el sistema deja de enviar alertas de manera inmediata. |
| TS-01 | Endpoint de registro | Como desarrollador, necesito crear un endpoint para registrar usuarios con correo y contraseña | EP2 | 1. Dado que un developer envía una solicitud de registro con datos válidos, cuando el endpoint procesa la solicitud, entonces el usuario es registrado y se devuelve una confirmación. <br>2. Dado que un developer envía una solicitud con datos inválidos o un correo duplicado, cuando el endpoint procesa la solicitud, entonces retorna un mensaje de error indicando la falla. |
| TS-02 | Endpoint de login | Como desarrollador, necesito implementar un endpoint de login que genere un token JWT | EP2 | 1. Dado que un developer envía una solicitud de login con credenciales correctas, cuando el endpoint valida los datos, entonces genera y devuelve un token JWT. <br>2. Dado que un developer envía credenciales incorrectas, cuando el endpoint intenta autenticar, entonces retorna un mensaje de error de autenticación. |
| TS-03 | Middleware de autenticación | Como desarrollador, necesito un middleware que valide el token en rutas protegidas | EP2 | 1. Dado que un usuario intenta acceder a una ruta protegida sin token, cuando la solicitud es interceptada por el middleware, entonces se deniega el acceso. <br>2. Dado que un usuario solicita una ruta protegida con un token válido, cuando la solicitud pasa por el middleware, entonces se permite el acceso a la ruta. |
| TS-04 | Endpoint de recuperación | Como desarrollador, necesito crear un endpoint que permita la recuperación de contraseña | EP2 | 1. Dado que un developer envía una solicitud de recuperación con un correo registrado, cuando el endpoint procesa la solicitud, entonces se envía un correo con un enlace seguro de restablecimiento. <br>2. Dado que un developer envía una solicitud con un correo no existente, cuando el endpoint procesa la solicitud, entonces retorna un mensaje de error indicando que el correo no existe. |
| TS-05 | CRUD de publicaciones | Como desarrollador, necesito crear los endpoints para crear, leer, actualizar y eliminar publicaciones | EP4 | 1. Dado que un developer envía una solicitud para crear una publicación con datos válidos, cuando el endpoint procesa la solicitud, entonces la publicación se crea correctamente. <br>2. Dado que un developer envía una solicitud para editar o eliminar una publicación sin permiso, cuando el endpoint valida la solicitud, entonces retorna un error de autorización. |
| TS-06 | Búsqueda de servicios | Como desarrollador, necesito implementar endpoints de búsqueda que acepten filtros y palabras clave | EP5 | 1. Dado que un developer envía una solicitud de búsqueda con filtros válidos, cuando el endpoint procesa la solicitud, entonces retorna una lista de servicios relevantes. <br>2. Dado que un developer envía una solicitud de búsqueda sin filtros, cuando el endpoint procesa la solicitud, entonces retorna todos los servicios disponibles. |
| TS-07 | Gestión de intercambios | Como desarrollador, necesito endpoints para crear, aceptar, rechazar y completar intercambios | EP6 | 1. Dado que un developer envía una solicitud para crear un intercambio con información completa, cuando el endpoint valida la solicitud, entonces se crea el intercambio y se asigna un estado inicial. <br>2. Dado que un developer envía una solicitud para aceptar o rechazar un intercambio, cuando se valida la acción, entonces el endpoint actualiza el estado y notifica a los usuarios involucrados. |
| TS-08 | Historial de intercambios | Como desarrollador, necesito un endpoint que devuelva el historial de intercambios completados | EP7 | 1. Dado que un developer solicita el historial de intercambios para un usuario, cuando el endpoint procesa la solicitud, entonces retorna una lista ordenada cronológicamente de los intercambios completados. <br>2. Dado que un developer solicita el detalle de un intercambio pasado, cuando el endpoint procesa la solicitud, entonces retorna toda la información registrada del intercambio. |
| TS-09 | Gestión de calificaciones | Como desarrollador, necesito endpoints para calificar a un usuario y consultar sus reviews | EP8 | 1. Dado que un developer envía una solicitud para calificar a un usuario, cuando el endpoint valida la información, entonces se registra la calificación y se actualiza el promedio. <br>2. Dado que un developer solicita las calificaciones de un usuario, cuando el endpoint procesa la solicitud, entonces retorna todas las reseñas y el promedio calculado. |
| TS-10 | Sistema de notificaciones | Como desarrollador, necesito implementar la lógica para enviar notificaciones en tiempo real o mediante polling | EP10 | 1. Dado que se genera un evento (por ejemplo, una nueva propuesta), cuando el sistema procesa el evento, entonces se envía una notificación en tiempo real o mediante polling al usuario. <br>2. Dado que un developer configura la desactivación de notificaciones para un usuario, cuando se procesa la solicitud, entonces no se envían alertas futuras al usuario. |
| TS-11 | Servicio de chat | Como desarrollador, necesito implementar endpoints y soporte de sockets para habilitar el chat entre usuarios | EP9 | 1. Dado que un developer envía un mensaje de chat, cuando el endpoint procesa la solicitud, entonces el mensaje se guarda en el historial y se transmite en tiempo real. <br>2. Dado que un developer solicita el historial de mensajes entre dos usuarios, cuando el endpoint procesa la solicitud, entonces retorna todos los mensajes en orden cronológico. |

## 3.3. Product Backlog

| # Orden | User Story Id | Título                            | Descripción                                                                                                   | Story Points |
| ------- | ------------- | --------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------ |
| 1       | US001         | Ver portada                       | Como usuario, quiero ver una portada para entender de qué trata la plataforma                                 | 2            |
| 2       | US002         | Ver beneficios                    | Como usuario, quiero ver los beneficios para entender por qué me conviene                                     | 2            |
| 3       | US003         | Ver ejemplos de servicios         | Como usuario, quiero ver ejemplos de servicios para imaginar su uso                                           | 3            |
| 4       | US004         | Ver precios                       | Como usuario, quiero ver una sección de precios para conocer los planes                                       | 3            |
| 5       | US005         | Ver testimonios                   | Como usuario, quiero ver la sección de testimonios para una mayor referencia                                  | 3            |
| 6       | US006         | Ver barra de navegación           | Como usuario, quiero contar con una barra de navegación para facilitar la búsqueda                            | 2            |
| 7       | US007         | Ver equipo                        | Como usuario, quiero ver la sección del equipo para conocer su propósito o historia                           | 2            |
| 8       | US008         | Ver footer                        | Como usuario, quiero un footer para acceder a información adicional                                           | 1            |
| 9       | US009         | Registrarse                       | Como usuario, quiero registrarme con correo y contraseña para crear una cuenta                                | 3            |
| 10      | US010         | Iniciar sesión                    | Como usuario, quiero iniciar sesión con correo y contraseña para acceder a mi cuenta                          | 3            |
| 11      | US011         | Cerrar sesión                     | Como usuario, quiero poder cerrar sesión para proteger mi información                                         | 2            |
| 12      | US012         | Recuperar contraseña              | Como usuario, quiero recuperar mi contraseña para acceder a mi cuenta nuevamente                              | 3            |
| 13      | US013         | Personalizar perfil               | Como usuario, quiero personalizar mis datos de perfil para generar confianza                                  | 3            |
| 14      | US014         | Agregar habilidades               | Como usuario, quiero incluir mis habilidades en mi perfil para obtener mejores resultados                     | 3            |
| 15      | US015         | Ver publicaciones propias         | Como usuario, quiero ver la lista de mis publicaciones                                                        | 3            |
| 16      | US016         | Ver detalle de publicación        | Como usuario, quiero ver los detalles de mis publicaciones para verificar su contenido                        | 3            |
| 17      | US017         | Crear publicación                 | Como usuario, quiero crear una publicación para indicar el servicio que ofrezco y necesito                    | 5            |
| 18      | US018         | Editar publicación                | Como usuario, quiero editar mis publicaciones para actualizar la información                                  | 5            |
| 19      | US019         | Eliminar publicación              | Como usuario, quiero eliminar mis publicaciones para no ofrecer algo que no deseo                             | 3            |
| 20      | US020         | Buscar servicios                  | Como usuario, quiero buscar servicios publicados por otros usuarios                                           | 8            |
| 21      | US021         | Inicio con servicios relevantes   | Como usuario, quiero ver en mi inicio servicios que requieran de mis habilidades                              | 3            |
| 22      | US022         | Filtrar por categoría             | Como usuario, quiero filtrar servicios por categoría para obtener mejores resultados                          | 3            |
| 23      | US023         | Buscar por palabras clave         | Como usuario, quiero buscar servicios mediante palabras claves para obtener mejores resultados                | 5            |
| 24      | US024         | Ver detalle de servicio           | Como usuario, quiero ver a detalle los servicios de otros usuarios                                            | 3            |
| 25      | US025         | Contactar a usuario               | Como usuario, quiero contactar con otros usuario para proponer un intercambio                                 | 8            |
| 26      | US026         | Recibir propuestas                | Como usuario, quiero recibir propuesta de otros usuario interesados                                           | 5            |
| 27      | US027         | Aceptar o rechazar propuesta      | Como usuario, quiero aceptar o rechazar las propuestas de intercambio                                         | 5            |
| 28      | US028         | Cancelar propuesta enviada        | Como usuario, quiero cancelar una propuesta de intercambio que envié                                          | 3            |
| 29      | US029         | Ver intercambios pendientes       | Como usuario, quiero ver una lista de intercambios pendientes                                                 | 3            |
| 30      | US030         | Ver intercambios activos          | Como usuario, quiero ver una lista de intercambios activos                                                    | 3            |
| 31      | US031         | Ver detalle de intercambio        | Como usuario, quiero ver los detalles de cada intercambio                                                     | 5            |
| 32      | US032         | Marcar como completado            | Como usuario, quiero marcar un intercambio como completado                                                    | 3            |
| 33      | US033         | Ver historial de intercambios     | Como usuario, quiero ver el historial de mis intercambios completados                                         | 3            |
| 34      | US034         | Ver detalle de intercambio pasado | Como usuario, quiero acceder a los detalles de un intercambio pasado                                          | 3            |
| 35      | US035         | Dejar comentarios                 | Como usuario, quiero dejar comentarios o reseñas sobre los intercambios finalizados                           | 2            |
| 36      | US036         | Calificar a usuarios              | Como usuario, quiero calificar a otros usuarios para compartir mi experiencia                                 | 5            |
| 37      | US037         | Ver calificaciones                | Como usuario, quiero ver las calificaciones y comentarios de otros usuarios                                   | 3            |
| 38      | US038         | Chat entre usuarios               | Como usuario, quiero chatear con otros usuario para coordinar detalles del intercambio                        | 5            |
| 39      | US039         | Recibir notificaciones            | Como usuario, quiero recibir notificaciones de propuestas entrantes                                           | 3            |
| 40      | US040         | Desactivar notificaciones         | Como usuario, quiero desactivar las notificaciones para evitar recibir alertas                                | 2            |
| 41      | TS-01         | Endpoint de registro              | Como desarrollador, necesito crear un endpoint para registrar usuarios con correo y contraseña                | 5            |
| 42      | TS-02         | Endpoint de login                 | Como desarrollador, necesito implementar un endpoint de login que genere un token JWT                         | 5            |
| 43      | TS-03         | Middleware de autenticación       | Como desarrollador, necesito un middleware que valide el token en rutas protegidas                            | 3            |
| 44      | TS-04         | Endpoint de recuperación          | Como desarrollador, necesito crear un endpoint para la recuperación de contraseña                             | 3            |
| 45      | TS-05         | CRUD de publicaciones             | Como desarrollador, necesito crear los endpoints para crear, leer, actualizar y eliminar publicaciones        | 5            |
| 46      | TS-06         | Búsqueda de servicios             | Como desarrollador, necesito implementar endpoints de búsqueda con filtros y palabras clave                   | 5            |
| 47      | TS-07         | Gestión de intercambios           | Como desarrollador, necesito endpoints para crear, aceptar, rechazar y completar intercambios                 | 5            |
| 48      | TS-08         | Historial de intercambios         | Como desarrollador, necesito un endpoint que devuelva el historial de intercambios completados                | 5            |
| 49      | TS-09         | Gestión de calificaciones         | Como desarrollador, necesito endpoints para calificar a usuarios y consultar reviews                          | 5            |
| 50      | TS-10         | Sistema de notificaciones         | Como desarrollador, necesito implementar la lógica para enviar notificaciones en tiempo real o por polling    | 8            |
| 51      | TS-11         | Servicio de chat                  | Como desarrollador, necesito implementar endpoints y soporte de sockets para habilitar el chat entre usuarios | 8            |

## 3.4. Impact Mapping

<h1 id="capitulo-iv-product-design">Capítulo IV: Product Design</h1>

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

### 4.1.3. Mobile Style Guidelines

### 4.1.3.1. iOS Mobile Style Guidelines

### 4.1.3.2. Android Mobile Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

### 4.4.2. Mobile Applications Wireflow Diagrams

### 4.4.3. Mobile Applications Mock-ups

### 4.4.4. Mobile Applications User Flow Diagrams

## 4.5. Mobile Applications Prototyping

### 4.5.1. Android Mobile Applications Prototyping

### 4.5.2. iOS Mobile Applications Prototyping

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes

### 4.6.2. Web Applications Wireflow Diagrams

### 4.6.3. Web Applications Mock-ups

### 4.6.4. Web Applications User Flow Diagrams

## 4.7. Web Applications Prototyping

## 4.8. Domain-Driven Software Architecture

### 4.8.1. Software Architecture Context Diagram

### 4.8.2. Software Architecture Container Diagrams

### 4.8.3. Software Architecture Components Diagrams

## 4.9. Software Object-Oriented Design

### 4.9.1. Class Diagrams

### 4.9.2. Class Dictionary

## 4.10. Database Design

### 4.10.1. Relational/Non-Relational Database Diagram

<h1 id="capitulo-v-product-implementation">Capítulo V: Product Implementation</h1>

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

### 5.2.2. Implemented Landing Page Evidence

### 5.2.3. Implemented Frontend-Web Application Evidence

### 5.2.4. Implemented Native-Mobile Application Evidence

### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

### 5.2.6. RESTful API documentation

### 5.2.7. Team Collaboration Insights

## 5.3. Video About-the-Product

# Conclusiones, Bibliografía y Anexos
