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

| Nombre                            | Código       |
|-----------------------------------|--------------|
| Sebastian Cachis Gonzales           | u202210846     |
| Adriano Sebastian Cruz Palomino     | u202210697     |
| Amner Levi Llamo Sanchez           | u20221c376     |
| Marcelo Fabian Garro Vega           | u20201c410     |
| Lucio Heli Yen Cerna          | u202213143     |

### Abril del 2025
</div>

<div align="justify">

### Registro de versiones del informe

| Versión   | Fecha       | Autor      | Descripción |
|-----------|-------------|------------|-------------|
| 1.0       | 05/04/2025 | Adriano Cruz | Creación de la estructura del informe |
| 1.0       | 06/04/2025 | Sebastian Cachis | Desarrollo de todo el capítulo I |

### Project Report Collaboration Insights

**TB1**  
Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:

| Integrante                            | Tareas Designadas       |
|-----------------------------------|--------------------------|
| Sebastian Cachis           | Desarrollo de todo el capítulo I                |
| [Nombre del integrante]           | [Tareas]                |
| ...                               | ...                     |

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
| Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software | [Nombre del integrante]<br><b>TB1</b><br>[Descripción de acciones realizadas]<br><br>[Nombre del integrante]<br><b>TB1</b><br>[Descripción de acciones realizadas] | <b>TB1</b><br> [Conclusiones del equipo sobre el criterio específico] |
| Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales | [Nombre del integrante]<br><b>TB1</b><br>[Descripción de acciones realizadas]<br><br>[Nombre del integrante]<br><b>TB1</b><br>[Descripción de acciones realizadas] | <b>TB1</b><br> [Conclusiones del equipo sobre el criterio específico] |


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

|                                                                                                                                                                                                          Descripción de los perfiles de los integrantes del equipo                                                                                                                                                                                                           |                                                              Foto del integrante                                                              |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------:|
| |   <img src="Assets/teamMembersPhotos/"/>   |
|Mi nombre es **Amner Levi Llamo Sánchez**, soy estudiante del séptimo ciclo de ingeniería de software en la UPC. Me gusta jugar fútbol y videojuegos, por eso estoy constantemente investigando sobre nuevas tecnologías. Soy responsable con los trabajos que se me asignan; además soy tolerante y me adapto a las circunstancias del equipo.|<img src='../Assets/teamMembersPhotos/amnerLlamo.png' width="100" height="100"/>|
|Mi nombre es **Sebastian Nicolas Cachis Gonzales**, soy estudiante de séptimo ciclo de ingeniería de software en la UPC. Me considero una persona proactiva, organizada, meticulosa y muy enfocada en mis estudios, tanto grupales como individuales. Tengo facilidad para entender y ejemplificar los distintos temas que vemos, teniendo soltura para explicar. | <img src='../Assets/teamMembersPhotos/sebastianCachis.png'/> |
|Mi nombre es **Adriano Sebastian Cruz Palomino**, tengo 20 años, soy alumno de Ingeniería de Software en la UPC, actualmente estoy cursando el 7mo ciclo. Soy una persona curiosa, responsable, y comprometida con mis estudios, siempre busco aprender más y mejorar mis habilidades.| <img src='../Assets/teamMembersPhotos/AdrianoCruz.png/'/> |
|Mi nombre es **Lucio Heli Yen Cerna**, soy estudiante del séptimo ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona proactiva y organizada que se esmera en construir productos de calidad innovadores. Me apasiona mucho trabajar en equipo, debatir y compartir una misma motivación debido a que siento que aprendo de mis propios compañeros y mejoro como profesional. Por otro lado, mis hobbies son el gimnasio, la música y los videojuegos los cuáles me permiten llevar un estilo de vida balanceado y saludable.  | <img src='../Assets/teamMembersPhotos/lucioyen.png' alt = "Foto de perfil de Lucio Yen" width = 100 height = 100> |

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


|Nombre entrevistado|Augusto Granados|
|-|-|
|Edad|20 años|
|Departamento|Lima, Lima|
|<img src="../Assets/interviewsPhotos/augustogranados.png">|Augusto Granados no cuenta con el pasar del tiempo, la necesidad de conocer herramientas y métodos estadísticos son muy importantes para poder seguir con su carrera una vez ya egresado. Como el saber programación para la manipulación de datos estadísticos. El contar con una aplicación que le permita intercambiar conocimientos de forma gratuita es de mucha ayuda y factible para quienes no posean con los recursos, pero si tengan la intención de querer seguir aprendiendo y cuente algo que ofrecer |
|Duración entrevista: 00:00-09:27    |URL: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210846_upc_edu_pe/EUu1idGzQANCuxR4aUX4dLEBM9jZrfD_o_Am6yvitXcUpQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sVtiCe]|
| Nombre entrevistado | Walter Cachay |
| Edad                | 21 años       |
| Departamento        | Surco, Lima   |
| <img src="../Assets/interviewsPhotos/waltherCachay.png"> |Walter Cachay es un estudiante de 21 años cursando el séptimo ciclo de ingeniería mecatrónica, motivado a utilizar una plataforma de intercambio de servicios sin dinero principalmente por razones económicas. Considera que este modelo podría promover un mejor nivel de enseñanza y aprendizaje tanto nacional como mundialmente, permitiéndole ofrecer sus conocimientos a cambio de aprender de otros. Está dispuesto a enseñar programación básica y avanzada, matemáticas relacionadas con su carrera, y como hobby, enseñar a tocar la trompeta. Las principales barreras que identifica para acceder a servicios profesionales son los costos de suscripciones en plataformas y aplicaciones, especialmente para clases de idiomas como el inglés, que son importantes para mejorar su currículum y son requeridas por la universidad. Para evaluar la confianza en una plataforma, considera fundamentales los comentarios, reseñas y sistemas de calificación.Walter busca alternativas económicas con frecuencia, aproximadamente dos o tres veces por semana, comparando precios y buscando promociones o descuentos para estudiantes. Le interesaría aprender francés, diseño web, economía y profundizar sus conocimientos en programación y automatización. Considera que intercambiar tiempo y habilidades es una idea muy interesante que promueve la ayuda mutua entre personas de distintos lugares. Las características que valora en una plataforma incluyen facilidad de uso, diseño atractivo, sistema de búsqueda eficiente, reseñas visibles y la posibilidad de comunicación directa con los proveedores de servicios. Cree que una plataforma como SwapService podría contribuir significativamente a su desarrollo personal y profesional, permitiéndole acceder a conocimientos y desarrollar habilidades que de otra manera serían inaccesibles por limitaciones económicas, además de descubrir nuevas habilidades que aún no conoce. |
| Duración entrevista 00:00-08:15  | URL            [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EdMQe7U_565KqVCIYAcidt4BNohwZtyNYGp-bDuZQzAV_g?e=wuiJe6] |

***Jóvenes Emprendedores o Freelancers***
|Nombre entrevistado|William Sánchez|
|-|-|
|Edad|24 años|
|Departamento|Lima, Lima|
|<img src="../Assets/interviewsPhotos/williamSanchez.png">|William Sánchez, emprendedor de 24 años especializado en networking, busca utilizar una plataforma de intercambio de servicios sin dinero para optimizar recursos y establecer relaciones profesionales basadas en valor real. Ofrece servicios de estrategias digitales de marketing, consultoría de e-commerce, optimización de negocios y diseño UX/UI. Como emprendedor inicial con presupuesto limitado, enfrenta barreras para acceder a asesoría legal, contabilidad especializada y software, valorando en plataformas de intercambio los sistemas de verificación sólidos, portafolios demostrables y garantías en caso de disputas. Para valorar sus servicios en intercambios no monetarios, considera el tiempo invertido, su tarifa habitual y el valor potencial del servicio que recibe. Le interesaría intercambiar por servicios de copyrighting, SEO, asesoría contable y fiscal para aumentar la productividad de su negocio. Durante periodos de baja demanda, mejora su portafolio, trabaja en proyectos personales y refuerza su networking. De una plataforma como Swap Service espera acceder a servicios profesionales que normalmente no podría costear, expandir su red de contactos y aplicar sus habilidades en diversos contextos para enriquecer su experiencia profesional.|
|Duración entrevista: 00:00-06:38    |URL: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/ETZgkPk0OI1ApIxTCPOS9DkBtVWBa6BQq6cUHcMqI2qyyQ?e=WiaaWG]|

### 2.2.3. Análisis de entrevistas

***Jóvenes Universitarios y Recién Egresados***

La mayoria de los entrevistados ven con buenos ojos la idea de intercambiar habilidades como una solución viable y accesible. Este grupo señala que, debido a sus limitados recursos económicos, se ven constantemente en la necesidad de buscar alternativas que les permitan seguir formándose sin realizar grandes gastos. En ese sentido, Swap Service les parece una propuesta interesante, tanto para adquirir nuevos conocimientos como para compartir lo que ya saben.

Entre los servicios que estarían dispuestos a ofrecer, destacan clases de programación, asesorías en matemáticas y enseñanzas musicales como tocar la trompeta. Sin embargo, también reconocen ciertas barreras que actualmente enfrentan, como el alto costo de cursos, suscripciones a plataformas educativas que no pueden pagar y la presión constante por mejorar su perfil profesional para insertarse en el mercado laboral.

En relación a la confianza en la plataforma, todos coinciden en que sería importante contar con un sistema de calificaciones, comentarios y reseñas, que les permita sentirse más seguros al momento de intercambiar servicios. Varios entrevistados también mencionan que suelen buscar alternativas económicas como promociones para estudiantes o el intercambio de favores entre amigos, lo que refuerza la lógica del trueque como un modelo atractivo y realista.

Finalmente, se evidenció un alto interés por aprender cosas nuevas, tales como idiomas, diseño web, economía, y programación aplicada al análisis de datos.

***Jóvenes Emprendedores o Freelancers***

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
## 3.3. Product Backlog
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
