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

**Producto:** HomeyPark

### Integrantes:

| Nombre                          | Código     |
| ------------------------------- | ---------- |
| Sebastian Cachis Gonzales       | u202210846 |
| Adriano Sebastian Cruz Palomino | u202210697 |
| Amner Levi Llamo Sanchez        | u20221c376 |
| Marcelo Fabian Garro Vega       | u20201c410 |
| Lucio Heli Yen Cerna            | u202213143 |

### Mayo del 2025

</div>

<div align="justify">

### Registro de versiones del informe

| Versión | Fecha      | Autor            | Descripción                           |
| ------- | ---------- | ---------------- | ------------------------------------- |
| 1.0     | 05/04/2025 | Adriano Cruz     | Creación de la estructura del informe |
| 1.1     | 06/04/2025 | Sebastian Cachis | Desarrollo del capítulo I             |
| 1.2     | 06/04/2025 | Sebastian Cachis | Desarrollo del capítulo V             |
| 1.3     | 19/04/2025 | Adriano Cruz     | Desarrollo del capítulo IV            |
| 1.4     | 07/04/2025 | Amner Llamo      | Desarrollo del capítulo II            |
| 1.5     | 22/04/2025 | Marcelo Garro    | Desarrollo del capítulo II            |
| 1.6     | 24/04/2025 | Lucio Yen        | Desarrollo del capítulo IV            |

### Project Report Collaboration Insights

**TB1**    
Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:

<img src="../Assets/insights-1.png">
<img src="../Assets/insights-2.png">

**TP1**   
Para el desarrollo del informe perteneciente a la entrega TP1, se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:

<img src="../Assets/insights-3.png">
<img src="../Assets/insights-4.png">

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
  - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio-saas)
  - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
  - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
  - [5.2.7. RESTful API documentation](#527-restful-api-documentation)
  - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
- [5.3. Video About-the-Product](#53-video-about-the-product)

### [Capítulo VI: Product Verification & Validation](#capitulo-vi-product-verification--validation)

- [6.1. Testing Suites & Validation](#61-testing-suites--validation)
  - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
  - [6.1.2. Core Integration Tests](#612-core-integration-tests)
  - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
  - [6.1.4. Core System Tests](#614-core-system-tests)

### [Capítulo VII: DevOps Practices](#capitulo-vii-devops-practices)

- [7.1. Continuous Integration](#71-continuous-integration)
  - [7.1.1. Tools and Practices](#711-tools-and-practices)
  - [7.1.2. Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
- [7.2. Continuous Delivery](#72-continuous-delivery)
  - [7.2.1. Tools and Practices](#721-tools-and-practices)
  - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
- [7.3. Continuous Deployment](#73-continuous-deployment)
  - [7.3.1. Tools and Practices](#731-tools-and-practices)
  - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)


- [Conclusiones, Bibliografía y Anexos](#conclusiones-bibliografía-y-anexos)

<h1 id="outcome">Student Outcome</h1>

### Student Outcome

| Criterio específico                                                                                                                                    | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Conclusiones                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software                                                                  | Sebastian Nicolas Cachis Gonzales<br><b>TB1</b><br>Para esta entrega desarrollé el capítulo 1, hice entrevistas y también los diseños para la landing page.<br><b>TP1</b><br>Participé en la refactorización del backend y llevé a cabo pruebas unitarias e integrales para asegurar el correcto funcionamiento y calidad del sistema.<br><br>Amner Levi Llamo Sánchez<br><b>TB1</b><br>En el análisis competitivo, evalué las prácticas éticas de las soluciones existentes y documenté aquellas que debemos adoptar o mejorar en HomeyPark.<br><b>TP1</b><br>Apoyé en la refactorización del backend y ejecuté pruebas unitarias e integrales siguiendo criterios de calidad y responsabilidad profesional.<br><br>Marcelo Garro<br><b>TB1</b><br>Planifiqué y recopilé requisitos del proyecto en base a análisis previos de nuestro segmento objetivo para satisfacer sus necesidades y demandas.<br><b>TP1</b><br>Me encargué de la refactorización del frontend y verifiqué su funcionamiento mediante pruebas funcionales que garanticen una experiencia amigable y coherente.<br><br>Adriano Sebastian Cruz Palomino<br><b>TB1</b><br>Me encargué del desarrollo de los diagramas de arquitectura del sistema utilizando el modelo C4, asegurando que la estructura técnica promoviera una implementación ética, segura y comprensible para todos los stakeholders.<br><b>TP1</b><br>Implementé pruebas unitarias e integrales, y configuré flujos de CI/CD en el backend para reforzar las prácticas DevOps y garantizar un desarrollo continuo y controlado.<br><br>Lucio Heli Yen Cerna<br><b>TB1</b><br>Me encargué del desarrollo de los style guidelines tanto para la landing page, aplicativo móvil en Android e iOS, y en la plataforma web, asegurando un diseño ético, de fácil entendimiento y para todos los usuarios.<br><b>TP1</b><br>Llevé a cabo la refactorización de la aplicación móvil, orientando el diseño hacia una mejor accesibilidad y usabilidad para todos los usuarios.<br><br> | <b>TB1</b><br>Designamos tareas a cada integrante para optimizar el tiempo de trabajo.<br><b>TP1</b><br>Dividimos las responsabilidades considerando las fortalezas de cada miembro, logrando una ejecución ordenada, ética y eficaz del proyecto. |
| Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales | Sebastian Nicolas Cachis Gonzales<br><b>TB1</b><br>Esto me ha permitido tener una mejor visión de los límites y objetivos de nuestro proyecto, así como conocer las inquietudes de nuestros segmentos objetivos.<br><b>TP1</b><br>Al realizar las pruebas y refactorizar el backend, comprendí cómo estas tareas contribuyen a construir soluciones que respondan adecuadamente a las necesidades del entorno urbano y tecnológico.<br><br>Amner Levi Llamo Sánchez<br><b>TB1</b><br>Analicé el impacto potencial de HomeyPark en el contexto urbano, evaluando cómo la plataforma podría afectar la movilidad, el uso eficiente de espacios y la economía local.<br><b>TP1</b><br>Durante el proceso técnico, evalué cómo los cambios en la estructura del backend pueden repercutir directamente en la escalabilidad, seguridad y adaptabilidad del sistema frente a diversos contextos sociales.<br><br>Marcelo Garro<br><b>TB1</b><br>Planificando el proyecto, obtuve una perspectiva más clara sobre los alcances y objetivos del proyecto, así como un mayor entendimiento de las inquietudes y expectativas de nuestros segmentos objetivo.<br><b>TP1</b><br>A través de la mejora del frontend, pude observar cómo una buena interfaz puede facilitar la inclusión tecnológica y aportar valor en distintos entornos sociales y económicos.<br><br>Adriano Sebastian Cruz Palomino<br><b>TB1</b><br>Al definir la arquitectura C4, consideré cómo cada componente afectaría a nivel de escalabilidad, costos operativos y su adecuación a contextos urbanos sostenibles, para que la solución pueda adaptarse a diferentes realidades sociales y económicas.<br><b>TP1</b><br>Al configurar los procesos de integración continua y realizar pruebas, pude confirmar que una arquitectura sólida favorece no solo la eficiencia del sistema, sino también su sostenibilidad y adaptabilidad a largo plazo.<br><br>Lucio Heli Yen Cerna<br><b>TB1</b><br>Diseñando el proyecto, pude entender de forma más clara la perspectiva que necesitan nuestros segmentos objetivos para que este proyecto tenga un impacto positivo en su rutina diaria.<br><b>TP1</b><br>Gracias a la refactorización de la app móvil, comprendí cómo decisiones de diseño bien pensadas pueden tener un efecto positivo en la vida diaria de nuestros usuarios y en su interacción con la tecnología.<br><br> | <b>TB1</b><br>Hemos enfocado las habilidades de cada integrante en las áreas de desarrollo que mejor dominen para una mejor línea de trabajo.<br><b>TP1</b><br>Reflexionamos sobre cómo cada mejora técnica tiene implicancias reales en el entorno social y urbano, y buscamos que nuestras decisiones promuevan una solución que responda a dichas realidades. |




<h1 id="capitulo-i-introduccion">Capítulo I: Introducción</h1>

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestro equipo Netvia ha sido creado con el propósito de solucionar la preocupación por la
escasez de espacios de estacionamiento en entornos urbanos. La congestión del tráfico y la ineficiente
búsqueda de estacionamientos genera una gran frustración para el conductor. HomeyPark propone
revolucionar la forma en que las personas encuentran y utilizan espacios de estacionamiento.
Desarrollaremos una aplicación que ofrecerá una interfaz intuitiva, permitiendo a los usuarios buscar,
reservar y pagar por estacionamientos de manera sencilla y rápida.

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

En la actualidad, la congestión vehicular ha ido en aumento debido al crecimiento constante de la
población y al incremento del uso de vehículos. Este problema se ve agravado por la ineficiencia en la
búsqueda de espacios de estacionamiento, lo que ha generado una experiencia frustrante para los
conductores a nivel mundial. A su vez, aquellos que poseen espacios de estacionamiento sin utilizar en
áreas urbanas se enfrentan al desafío de no contar con una plataforma eficaz para rentabilizar estos
recursos.

**What?**

Nuestro startup ha identificado como problemática principal la escasez de espacios de estacionamiento
en entornos urbanos y la complejidad que representa actualmente encontrar un lugar para estacionar.
Esto se debe a la elevada demanda de vehículos para las actividades cotidianas.

**When?**

Esta preocupación ha ido en aumento a lo largo del tiempo, ya que las ciudades han visto crecer su
población, lo que ha resultado en un mayor número de vehículos en circulación. En los últimos años, la
congestión del tráfico y la dificultad para encontrar estacionamiento se han vuelto problemas más
urgentes.

**Where?**

El problema se presenta principalmente en áreas urbanas densamente pobladas a nivel global, donde el
espacio es limitado y la demanda de estacionamiento es alta.

**Who?**

Los conductores son los principales afectados por este problema, ya que se enfrentan a dificultades
para encontrar estacionamientos convenientes. Además, los propietarios de espacios de
estacionamiento se ven en desventaja frente a grandes empresas del sector, lo que complica la
promoción y alquiler de sus servicios.

**Why?**

La causa principal radica en la insuficiencia de espacios de estacionamiento disponibles en áreas
urbanas, lo que intensifica la congestión vehicular y dificulta que los conductores encuentren un lugar
para estacionar en el momento oportuno.

**How?**

El problema ocurre cuando la congestión del tráfico, combinada con la falta de espacios de
estacionamiento, impide que la población pueda estacionar de manera eficiente y conveniente.

**How much?**

Este problema afecta de manera notable a Lima, la capital, donde según un estudio realizado por la
ONG Luz Ámbar en 2016, existe una carencia de aproximadamente 45,000 espacios de
estacionamiento en cinco distritos. Sin embargo, esta cifra es insuficiente en comparación con la
cantidad de vehículos en la ciudad, que alcanza aproximadamente 1 millón 800,000 unidades. Esta
discrepancia entre la cantidad de vehículos y la disponibilidad de estacionamientos contribuye
significativamente a la congestión vehicular y al desafío constante de encontrar un lugar adecuado para
estacionar.

### 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

El desarrollo de HomeyPark sigue la metodología Lean UX, que combina el pensamiento Lean Startup con el diseño centrado en el usuario. Este enfoque nos permite validar rápidamente nuestras hipótesis de valor y crear soluciones adaptadas a las necesidades reales de los usuarios con el mínimo de recursos.

**Problem Statement 1: Usuarios de parking**

En la actualidad, muchos ciudadanos de las zonas urbanas del Perú requieren de un vehículo
motorizado para realizar tramos largos de viaje. Debido a su alta demanda, el diario “El Comercio”
(2024) revela que el 51% de conductores de la ciudad de Lima consideran necesario incrementar la
cantidad de espacios para estacionar.

Hemos encontrado que los conductores presentan dificultades para encontrar espacios de
estacionamiento disponibles, tomando un aproximado de 10 horas totales al mes para conseguir uno.

¿Cómo podemos buscar o proporcionar más espacios de estacionamiento para los usuarios de forma
eficiente y rápida para sus vehículos motorizados?

**Problem Statement 2: Anfitriones**

Nuestra aplicación permitirá a los usuarios poder promocionar sus garajes para obtener una fuente de
ingresos adicional sin interrupción en sus actividades del día a día. Esto favorecerá a las comunidades
para la reducción de la congestión vehicular.

Hemos encontrado que muchos propietarios no están dispuestos a ofrecer su garaje en alquiler debido
al anonimato de los clientes, lo cual genera una sensación de inseguridad en estas entidades.

¿Cómo podemos implementar un sistema de seguridad que vele por la integridad, bienes y bienes
inmobiliarios de nuestros usuarios de la aplicación?

### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

1. Creo que mis usuarios necesitan una mejor opción de encontrar estacionamientos y, de ser
   posible, reservarlos.

2. Estas necesidades se pueden resolver con una aplicación móvil que les permita a los
   conductores reservar en los garajes de la ciudad, debido a que la mayoría del tiempo se
   encuentran disponibles.

3. Mis clientes iniciales son las personas que cuenten con un vehículo y que tengan dificultades
   de encontrar algún estacionamiento disponible.

4. El valor #1 que el cliente requiere de mi servicio es encontrar y reservar espacios para
   estacionar en un corto periodo de tiempo de forma segura.

5. Voy a adquirir a mis clientes a través de estrategias de marketing en diversas redes sociales,
   mostrando todos los beneficios que da nuestra aplicación móvil.

6. Mi competencia en el mercado serán las empresas que se dedican a ofrecer sus servicios de
   estacionamiento.

7. Los venceremos debido a que ofrecemos a los usuarios poder generar ingresos de manera
   pasiva al rentar sus garajes como estacionamiento.

8. Mis mayores riesgos del producto es no encontrar una manera de brindar seguridad a los
   conductores como a los propietarios de los garajes.

9. Resolveremos esto con la incorporación de un sistema que se encargue de validar los
   parámetros de seguridad de los conductores y los garajes en alquiler para ofrecer una mejor
   seguridad al público.

**User Assumptions**

_Usuarios de parking_

**¿Quién es el usuario?** Conductores que en su día a día necesitan encontrar estacionamiento para sus
vehículos.

**¿Dónde encaja nuestro servicio?** Nuestro servicio encaja tanto para su trabajo como para sus
actividades diarias.

**¿Qué problema tiene nuestro servicio y cómo se resuelve?** El problema es sobre la posible
inseguridad del usuario al alquilar en una cochera de cualquier persona desconocida. Se puede resolver
mediante un sistema de filtros que garanticen al usuario la seguridad de la cochera y contar con bases
legales para la publicación del producto.

**¿Cuándo y cómo es usado nuestro producto?** Nuestro producto será usado mayormente cuando el
usuario necesite encontrar algún estacionamiento para realizar cualquier actividad. La aplicación móvil
se podrá usar como un sistema de búsqueda y reserva de cocheras.

_Anfitriones_

**¿Quién es el usuario?** Personas con garajes que desean poner en alquiler para generar ingresos.

**¿Dónde encaja nuestro servicio?** Nuestro servicio encaja en su vida porque pueden poner en alquiler
sus garajes mientras realizan cualquier actividad.

**¿Qué problema tiene nuestro servicio y cómo se resuelve?** El problema será el proceso para poder
registrar sus cocheras, debido a que puede llegar a ser confuso o tedioso para el anfitrión. Lo podemos
resolver mediante capacitación sobre el proceso de filtros para facilitar al usuario el registro.

**¿Cuándo y cómo es usado nuestro producto?** Nuestra aplicación es usada principalmente cuando el
anfitrión dispone de cualquier garaje disponible que desee poner en alquiler para generar ingresos.
Nuestro producto es usado como un gestor de cocheras sobre reservas, estados, recibos, etc.

### 1.2.2.3. Lean UX Hypothesis Statements

1. Creemos que la función de reservar cocheras facilitará al usuario conseguir un espacio para
   estacionamiento. Sabremos que tendremos éxito cuando la mayoría de los usuarios demoren
   en conseguir estacionamiento en un plazo máximo de 5 minutos.

2. Creemos que la implementación del mapa de Google Maps permitirá al usuario una mejor
   búsqueda de cocheras. Sabremos que estaremos en lo cierto cuando el 100% de nuestros
   usuarios no presentan dificultades para encontrar cocheras.

3. Creemos que proporcionar al usuario registrar sus cocheras aumentará la cantidad de
   estacionamientos. Sabremos que estaremos en lo cierto cuando el índice de escasez de
   estacionamientos se reduzca en un 20%.

4. Creemos que implementar un sistema de notificaciones alertará a los usuarios sobre la
   disponibilidad de las cocheras. Sabremos que tendremos éxito cuando al menos el 80% de los
   usuarios aprovechen estas alertas para asegurar un espacio de estacionamiento.

### 1.2.2.4. Lean UX Canvas

<img src='../Assets/LeanUXCanva.png'/>

## 1.3. Segmentos objetivo

Nuestro segmento objetivo está compuesto por dos usuarios:

**Usuarios de parking:** Persona que busca alguna solución para su necesidad que es buscar un
estacionamiento en entornos urbanos para su vehículo

**Anfitrión:** Propietario de una vivienda que cuente con una cochera privada que busque sacar
provecho de forma efectiva.

<h1 id="capitulo-ii-requirements-elicitation--analysis">Capítulo II: Requirements Elicitation & Analysis</h1>

## 2.1. Competidores

### 2.1.1. Análisis competitivo

Nuestros competidores principalmente vendrían a ser otras aplicaciones que se encargan del servicio
de estacionamiento por celular. Algunos de nuestros competidores potenciales vendrían a ser:

1. EasyPark: Es una app popular que permite a los usuarios encontrar y pagar por
   estacionamientos en diversas ciudades. EasyPark se integra con sistemas de estacionamiento
   inteligente, ofreciendo información en tiempo real sobre la disponibilidad de espacios, y cuenta
   con opciones de pago automatizado y reconocimiento de placas. La app también permite
   reservar espacios con anticipación y está disponible en varios países, facilitando la movilidad
   urbana a nivel internacional.

2. Parkopedia: Esta aplicación ofrece una amplia base de datos de estacionamientos, incluyendo
   garajes privados y públicos. Parkopedia también proporciona predicciones sobre la
   disponibilidad de espacios y se integra con sistemas de navegación en vehículos. Además,
   ofrece información detallada sobre tarifas y horarios, lo que ayuda a los usuarios a tomar
   decisiones más informadas al buscar estacionamiento. Su cobertura incluye más de 15,000
   ciudades en todo el mundo.

3. Wayleadr: Se centra en la optimización de espacios de estacionamiento en áreas urbanas y
   corporativas. Ofrece características como reservas anticipadas y gestión de estacionamiento
   para empresas, utilizando geolocalización para mejorar la eficiencia. También permite a las
   empresas monitorear y gestionar sus plazas de estacionamiento, reduciendo costos operativos y
   mejorando la experiencia de los empleados. Wayleadr ha sido adoptada por importantes
   corporaciones globales para optimizar el uso de sus instalaciones.

### 2.1.2. Estrategias y tácticas frente a competidores

<table> <tr> <th colspan="6" valign="top">Competitive Analysis Landscape</th> </tr> <tr> <td colspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td> <td colspan="4" valign="top">Un análisis competitivo ayuda a identificar oportunidades y mejorar su propuesta de valor para mantenerse relevante en el mercado.</td> </tr> <tr> <td colspan="2" valign="top"></td> <td valign="top">HomeyPark</td> <td valign="top">EasyPark</td> <td valign="top">Parkopedia</td> <td valign="top">Wayleadr</td> </tr> <tr> <td rowspan="2" valign="top">Perfil</td> <td valign="top">Overview</td> <td valign="top">Una aplicación que conecta conductores con garajes privados disponibles, permitiéndoles reservar espacios de estacionamiento fácilmente. </td> <td valign="top">Una app popular que ayuda a encontrar, reservar y pagar estacionamientos fácilmente. </td> <td valign="top">Una base de datos global que ofrece información detallada sobre estacionamientos y disponibilidad.</td> <td valign="top">Una solución para optimizar y gestionar estacionamientos en entornos corporativos y urbanos.</td> </tr> <tr> <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td> <td valign="top">Ofrece a los conductores la posibilidad de encontrar y reservar estacionamientos en garajes privados en tiempo real, reduciendo la congestión vehicular y proporcionando una fuente de ingresosadicional para los propietarios de garajes.</td> <td valign="top">Ofrece a los usuarios una experiencia sin fricciones para encontrar, reservar y pagar por estacionamientos, todo a través de una integración avanzada con sistemas de navegación y pagos automatizados.</td> <td valign="top">Proporciona a los usuarios información completa y en tiempo real sobre disponibilidad y tarifas de estacionamiento en miles de ciudades, ayudándolos a tomar decisiones informadas rápidamente.</td> <td valign="top">Facilita la gestión eficiente de espacios de estacionamiento en entornos corporativos, mejorando la experiencia del usuario y optimizando los recursos de las empresas.</td> </tr> <tr> <td rowspan="2" valign="top">Perfil de Marketing</td> <td valign="top">Mercado objetivo</td> <td valign="top">Conductores<br> Propietarios de garajes</td> <td valign="top"> 
Conductores urbanos<br> Viajeros frecuentes</td> <td valign="top">Conductores<br> Empresas de navegación vehicular </td> <td valign="top">Empresas con estacionamientos<br> Corporaciones </td> </tr> <tr> <td valign="top">Estrategias de marketing</td> <td valign="top">Marketing en redes sociales, marketing de contenido</td> <td valign="top">Marketing en redes sociales, marketing de contenido</td> <td valign="top">Marketing en redes sociales, marketing de contenido</td> <td valign="top">Marketing en redes sociales, marketing de contenido</td> </tr> <tr> <td rowspan="3" valign="top">Perfil de Producto</td> <td valign="top">Productos & Servicios</td> <td valign="top">Reserva de garajes a través de la app, integración con Google Maps para la localización de espacios, y un sistema de seguridad para transacciones.</td> <td valign="top">App de reserva de estacionamiento, pagos automatizados, y notificaciones de disponibilidad en tiempo real.</td> <td valign="top">Base de datos de estacionamientos, predicciones de disponibilidad, e integración con sistemas de navegación.</td> <td valign="top">Gestión de estacionamientos corporativos, reservas anticipadas, y análisis de uso de espacios.</td> </tr> <tr> <td valign="top">Precios & Costos</td> <td valign="top">El precio varía según el servicio que adquiere el usuario.</td> <td valign="top">El precio varía según el servicio que adquiere el usuario.</td> <td valign="top">El precio varía según el servicio que adquiere el usuario.</td> <td valign="top">El precio varía según el servicio que adquiere el usuario.</td> </tr> <tr> <td valign="top">Canales de distribución (Web y/o Móvil)</td> <td valign="top">Aplicación móvil y web.</td> <td valign="top">Aplicación móvil y web.</td> <td valign="top">Aplicación móvil y web.</td> <td valign="top">Aplicación móvil y web.</td> </tr> <tr> <td rowspan="4" valign="top">Análisis SWOT</td> <td valign="top">Fortalezas</td> <td valign="top">Proporciona una solución innovadora parala falta de estacionamientos en áreas urbanas al aprovechar los garajes privados, lo que también beneficia a las comunidades locales.</td> <td valign="top">Amplia adopción y fácil integración con sistemas de pago y navegación, lo que facilita su uso en diversas ciudades.</td> <td valign="top">Ofrece la base de datos de estacionamientos más extensa y detallada a nivel global, con información en tiempo real.</td> <td valign="top">Especialización en la optimización de estacionamientos corporativos, lo que mejora la eficiencia y reduce costos para empresas.</td> </tr> <tr> <td valign="top">Debilidades</td> <td valign="top">La seguridad tanto para los conductores como para los propietarios de garajes puede ser una preocupación, lo que podría afectar la adopción.</td> <td valign="top">Puede enfrentar dificultades en regiones donde la infraestructura de estacionamiento inteligente es limitada.</td> <td valign="top">Su dependencia de datos de terceros puede afectar la precisión y actualización de la información. </td> <td valign="top">Está más centrada en mercados corporativos, lo que limita su alcance para el usuario promedio.</td> </tr> <tr> <td valign="top">Oportunidades</td> <td valign="top">Expansión a nuevas ciudades y la posibilidad de integrar tecnologías avanzadas de seguridad y autenticación para aumentar la confianza de los usuarios.</td> <td valign="top">Expandir su servicio a más ciudades y regiones que aún no cuentan con soluciones avanzadas de estacionamiento.</td> <td valign="top">Integrar tecnologías avanzadas como inteligencia artificial para mejorar la precisión de las predicciones de disponibilidad de estacionamiento.</td> <td valign="top">Ampliar su oferta para incluir soluciones de estacionamiento para pequeños negocios y complejos residenciales.</td> </tr> <tr> <td valign="top">Amenazas</td> <td valign="top">Competencia de aplicaciones similares que podrían ofrecer características de seguridad o precios más competitivos, así como la posible resistencia de los usuarios a confiar en garajes privados.</td> <td valign="top">La creciente competencia de nuevas aplicaciones de estacionamiento con funcionalidades más avanzadas podría reducir su cuota de mercado.</td> <td valign="top">Los cambios en las regulaciones de datos y privacidad pueden limitar el acceso a la información necesaria para mantener su base de datos actualizada.</td> <td valign="top">La dependencia de un nicho específico como el mercado corporativo puede limitar su crecimiento frente a soluciones más generalistas.</td> </tr> </table>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Para obtener una comprensión profunda de las necesidades y expectativas de los usuarios potenciales de HomeyPark, se diseñarán entrevistas estructuradas con preguntas específicas para diferentes segmentos de usuarios. A continuación, se presentan las preguntas para cada grupo:

**Preguntas Generales**

- ¿Cuál es su nombre y apellido completo?
- ¿Cuál es su edad?
- ¿En qué distrito o lugar reside?
- ¿Cuál es su ocupación?

**Preguntas para el usuario de Parking**

- ¿Con qué tipo de vehículo dispone? ¿Carro ligero, camioneta o moto?
- ¿Con qué frecuencia usa su(s) vehículo(s)?
- Hoy en día, es complicado encontrar un estacionamiento disponible. ¿Cuál cree que es la razón por la que sucede esto?
- ¿Cuáles serían las horas donde es más difícil encontrar estacionamientos?
- ¿Cuánto tiempo demora aproximadamente en encontrar estacionamiento?
- ¿Estaría dispuesto a usar como estacionamiento los garajes de las viviendas? ¿Cuáles serían sus motivos?
- ¿Cuáles serían los requisitos mínimos para asegurar la integridad del usuario y su vehículo?
- Si este servicio llega a ser seguro para sus clientes, ¿cree que sería útil para los ciudadanos de las zonas urbanas del Perú? ¿En que los beneficiaría?
- ¿Confiaría usted en una aplicación móvil que facilite la búsqueda de estos tipos de estacionamientos?

**Preguntas para el anfitrión o host**

- ¿Con cuántos garajes o cocheras cuenta en su hogar?
- ¿Cuál es el tamaño promedio de los garajes en su hogar?
- ¿En qué momentos de su día a día sus garajes se encuentran desocupados?
- ¿Cuenta con algún sistema de seguridad en su cochera?
- ¿Ha llegado a considerar la posibilidad de alquilar sus garajes en algún momento? ¿Por qué?
- ¿Cuáles serían los requisitos mínimos para asegurar la integridad del usuario y su bienes, ya sea inmobiliario o no?
- ¿Le interesaría tener una aplicación móvil que permita promocionar sus garajes como estacionamiento y generar ingresos, sin interrumpir sus actividades diarias?

### 2.2.2. Registro de entrevistas

**_Usuarios de parking_**

<table>
  <tr>
    <th colspan="2" valign="top">Registro de entrevistas</th>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Walther Cachay</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">25 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Lima, Perú</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/waltherCachay.png"></b></td>
    <td valign="top">
      Walter Cachay, un estudiante de ingeniería mecatrónica de 25 años, enfrenta dificultades diarias para encontrar estacionamiento con su auto en Lima, especialmente en horas punta, llegando a tardar hasta una hora y media en zonas como Surco o cerca de su universidad, e incluso una o dos horas en el centro, una situación que atribuye al aumento del parque automotor. Aunque reacio inicialmente a usar garajes de viviendas por seguridad y comodidad, consideraría esta opción si existieran garantías como comprobantes de empresa, reglas claras y vigilancia 24/7. Walter ve una aplicación para buscar estacionamiento como un avance muy positivo para ahorrar tiempo, combustible y encontrar lugares disponibles de manera eficiente, siempre y cuando garantice la seguridad del vehículo mediante un sistema de recomendaciones y ubicaciones confiables.
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-06:00</td>
    <td valign="top"><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EUWwVDeGIMxOirf7aLw_VKoBfkh-Q-X3iBSyjW7t8n4CoA?e=czxNW6" target="_blank">https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EUWwVDeGIMxOirf7aLw_VKoBfkh-Q-X3iBSyjW7t8n4CoA?e=czxNW6</a></td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Augusto Granados</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">20 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Lima Magdalena</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/augustogranados.png"></b></td>
    <td valign="top">
      DescripcAugusto Granados es un joven que cuentan con un carro, pero se le dificulta la posibilidad de encontrar espacio donde puede dejarlo en lugares por los que transita, no comenta que puede tener ocasiones en las que no logra encontrar uno hasta por casi 20 minutos, siento esto una gran pérdida de tiempo para él. El contar con una aplicación que le permita saber en qué lugares cercanos a donde el este le sería de gran ayuda. Otro aspecto para destacar fue que menciono el que poder valorar estos espacios y conocer sus tamaños serian cruciales para el usuario que busca reservar uno de esos espacios. ayuda a que lo poseedores de un parqueo se hagan de una buena reputación y la gente pueda confiar en que puede dejar ahí sus vehículos.ión
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-08:57</td>
    <td valign="top"> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210846_upc_edu_pe/EfwuXreiPk9Ak-akWrpZIvUBYeZe630_bahsL-sYD3QmHw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=KgTQuh " target="_blank">https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210846_upc_edu_pe/EfwuXreiPk9Ak-akWrpZIvUBYeZe630_bahsL-sYD3QmHw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=KgTQuh </a></td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Edu Arturo Antayhua</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">23 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Lima, San Miguel</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/eduAntayhua.png"></b></td>
    <td valign="top">
      El entrevistado usa su vehículo con frecuencia y enfrenta dificultades para encontrar estacionamiento, especialmente en horas pico. Señala que la congestión vehicular en Lima es un factor clave y que puede tardar hasta 25 minutos en hallar un espacio. Ve con buenos ojos la idea de una app web o móvil que permita alquilar cocheras de viviendas, siempre que garantice seguridad. Considera que esta solución sería útil para zonas urbanas, al ofrecer alternativas más accesibles, cercanas y seguras.
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-06:03</td>
    <td valign="top"><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ESsNFhchBGJJqJu8VPApO6UB7R50E2SeGOZJGMEkrbMSbw?e=fLfDyf&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">entrevista-edu.mp4</td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Fabrizio Buleje</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">20 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Santiago de Surco</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/fabrizioBuleje.png"></b></td>
    <td valign="top">
      Descripción <br>
      Fabrizio Buleje Alfaro, de 20 años, vive en Surco y estudia Medicina en la Universidad Científica del Sur. Aunque tiene una moto, actualmente se transporta en su auto ligero, principalmente para ir a la universidad. Comenta que el tráfico en Lima y la dificultad para encontrar estacionamiento, especialmente en zonas céntricas como el Centro Cívico, son desafíos frecuentes. Está dispuesto a alquilar garajes de viviendas si le ofrecen seguridad y confianza. Además, considera útil una aplicación móvil que facilite la búsqueda de estacionamientos seguros y actualizados.
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-07:50</td>
    <td valign="top"><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210697_upc_edu_pe/ETqMzVRTXmNJoKJiOZrbD3cB8QXeMq1xaryOh3PwfP0aRQ?e=OICOHn&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">
        https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210697_upc_edu_pe/ETqMzVRTXmNJoKJiOZrbD3cB8QXeMq1xaryOh3PwfP0aRQ?e=OICOHn&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D</a>
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-08:15</td>
    <td valign="top"> URL: []</td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Nombre</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">edad años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">....</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/img.png"></b></td>
    <td valign="top">
      Descripción
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-08:15</td>
    <td valign="top"> URL: []</td>
  </tr>
</table>

**_Anfitriones_**

<table>
  <tr>
    <th colspan="2" valign="top">Registro de entrevistas</th>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Henry Sanchez</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">36 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Lima, Perú</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/henrySanchez.png"></b></td>
    <td valign="top">
      Henry Sánchez, un psicólogo de 36 años residente en San Isidro, posee dos espacios de estacionamiento en su cochera, uno de los cuales, de aproximadamente 2.5m x 5m, permanece desocupado la mayor parte del tiempo. Reconociendo la dificultad para encontrar estacionamiento en su zona, Henry ha considerado alquilar este espacio infrautilizado, pero la falta de un sistema de gestión fiable lo ha frenado. Para sentirse seguro al alquilarlo, Henry requeriría verificación de identidad y del vehículo, un sistema de calificaciones, alguna forma de garantía o seguro, términos claros, y como medida adicional, antecedentes del usuario. Muestra gran interés en una aplicación como HomeyPark que le permita monetizar este espacio de manera eficiente, segura y sin complicaciones, optimizando sus recursos y generando ingresos pasivos, y está interesado en explorar más a fondo esta oportunidad.
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-05:00</td>
    <td valign="top"><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EW40jWzkorhErF8MoKSIyEIBy-fT5CM8i_D9YgqGIxFeOA?e=g8VpYy" target="_blank">https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EW40jWzkorhErF8MoKSIyEIBy-fT5CM8i_D9YgqGIxFeOA?e=g8VpYy</a></td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Carla Cachis Gonzales</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">27 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Lima Magdalena</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/carlacachis.png"></b></td>
    <td valign="top">
      Carla Cachis es una señorita que cuenta con una propiedad con estacionamiento, pero no con un carro propio, por lo que durante la semana suele estar vacío, he incluso época que no lo usa prolongadamente. Tras contarle la propuesta de HomeyPark le pareció una idea muy buena para poder contar con ingreso extra de los que ya posee sería muy útil, además que como el estacionamiento no da acceso a su hogar no estaría poniéndose en riesgo. Algo de lo que hizo mucho énfasis fue que el usuario que buscar dejar su vehículo tiene que dejar documentación oficial que valide quien es la persona, posibles antecedentes, documentos del carro a dejar y cualquier tipo de información que asegure que este conductor no presenta ser un problema.
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-09:13</td>
    <td valign="top"><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210846_upc_edu_pe/ERvpgREHqulEm_px0TzKo0ABE-aAytpTQTglcoAfuuhAJQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=Bfzr78 Entrevista N°5: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EbiUMHvfuqtNu7hVWBK2HD8BNYoY4tEjRtNIN3tiEoemmw?e=LvikLJ" target="_blank">https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210846_upc_edu_pe/ERvpgREHqulEm_px0TzKo0ABE-aAytpTQTglcoAfuuhAJQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=Bfzr78 Entrevista N°5: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c376_upc_edu_pe/EbiUMHvfuqtNu7hVWBK2HD8BNYoY4tEjRtNIN3tiEoemmw?e=LvikLJ</a></td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Rodrigo Tornero Loayza</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">21 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Lima, Surco</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/rodrigoTornero.png"></b></td>
    <td valign="top">
      El entrevistado dispone de un garaje con espacio para un vehículo y ocasionalmente una motocicleta, el cual permanece desocupado por períodos interdiarios de aproximadamente cinco horas. Está dispuesto a alquilarlo para generar ingresos pasivos, siempre que se garantice la seguridad del inmueble y se proporcione información confiable sobre los arrendatarios. Considera atractiva la idea de una app móvil que le permita ofrecer su cochera como espacio de estacionamiento y ve en ello una forma práctica de aprovechar un recurso infrautilizado.
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-04:35</td>
    <td valign="top"> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/EeNCp6L8z-lImzB639EyMAwBXkGAeM2qeStolzxVp8vOhw?e=KLsbWk&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">entrevista-rodrigo.mp4</a></td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Carla Cruz</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">30 años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">Cusco, Cusco</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/carlacruz.png"></b></td>
    <td valign="top">
      Descripción
      Carla Jackdel Cruz Palomino, de 30 años, vive en Cusco en un edificio con cocheras por departamento. Cuenta con dos cocheras: una pequeña para autos estándar y otra más grande para camionetas. Actualmente no posee vehículo, por lo que sus cocheras suelen estar desocupadas y a veces las presta a vecinos o amistades. Los garajes tienen cámaras de seguridad y alarmas.
      Aunque no ha alquilado formalmente sus cocheras por falta de tiempo, considera que sería una buena fuente de ingreso adicional. Señala que para hacerlo se necesitaría información detallada del usuario y respeto por las normas del edificio. Finalmente, Carla estaría interesada en una aplicación móvil que le permita alquilar sus cocheras de forma práctica y sin afectar sus actividades diarias.
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-04:56</td>
    <td valign="top"><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210697_upc_edu_pe/EVkwUQwS6yRCudGFUP9lYkYBdD-sjfGGK55ZiScS9zMmfg?e=AGO7Kq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210697_upc_edu_pe/EVkwUQwS6yRCudGFUP9lYkYBdD-sjfGGK55ZiScS9zMmfg?e=AGO7Kq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D</a></td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-08:15</td>
    <td valign="top"> URL: []</td>
  </tr>
  <tr>
    <td valign="top"><b>Nombre entrevistado</b></td>
    <td valign="top">Nombre</td>
  </tr>
  <tr>
    <td valign="top"><b>Edad</b></td>
    <td valign="top">edad años</td>
  </tr>
  <tr>
    <td valign="top"><b>Departamento</b></td>
    <td valign="top">....</td>
  </tr>
  <tr>
    <td valign="top"><b><img src="../Assets/interviewsPhotos/img.png"></b></td>
    <td valign="top">
      Descripción
    </td>
  </tr>
  <tr>
    <td valign="top">Duración entrevista  00:00-08:15</td>
    <td valign="top"> URL: []</td>
  </tr>
</table>

### 2.2.3. Análisis de entrevistas

**_Segmento 1: Usuarios de parking_**

- El 100% de los entrevistados están de acuerdo que la falta o escasez de estacionamientos disponibles se debe a la alta demanda de vehículos motorizados de las zonas urbanas.

- El 100% de los entrevistados presentan dificultades para encontrar estacionamiento principalmente en los tiempos de inicio de trabajo o estudio. Como ejemplo, de 7AM a 10AM o de 2PM a 4PM.

- En la búsqueda de estacionamientos, indican tomar un aproximado de 20 a 30 minutos para conseguir un espacio disponible.

- El 100% del segmento están conformes con la idea de estacionar sus vehículos en garajes de las viviendas, siempre y cuando este cuente con medidas de seguridad.

**_Segmento 2: Anfitriones_**

- El 100% de los entrevistados mencionan estar interesados en la posibilidad de poner en alquiler su garaje como estacionamiento para afrontar el problema principal, escasez de estacionamientos, y generar ingresos adicionales.
- Un porcentaje de los entrevistados indican que sus espacios de estacionamientos suelen estar desocupados por las mañanas e incluso por las tardes, debido a sus actividades diarias.
- De acuerdo con los entrevistados, al promocionar sus servicios de garaje como estacionamiento a personas desconocidas piden conseguir acceso a la información de estos usuarios y contar con un sistema de calificación para el servicio y el cliente.

## 2.3. Needfinding

### 2.3.1. User Personas

A continuación, se presentan los perfiles de usuario para los dos segmentos objetivo de HomeyPark: conductores y anfitriones.

### **User Persona: Usuario de Parking**

<img src="../Assets/chapter2/UserPersonaLuisArturo.png">

### **User Persona: Anfitrión**

<img src="../Assets/chapter2/UserPersonaJosePerez.png">

### 2.3.2. User Task Matrix

A continuación, se presenta el User Task Matrix para los segmentos de conductores y anfitriones, destacando las tareas que realizan para cumplir sus objetivos en la plataforma HomeyPark.

### **Segmento Jovenes Universitario**

<table><tr><th rowspan="2" valign="top">Actividades</th><th colspan="2" valign="top">Luis Arturo</th></tr>
<tr><td valign="top">Frecuencia</td><td valign="top">Importancia</td></tr>
<tr><td valign="bottom">Buscar espacios de estacionamiento disponibles en tiempo real</td><td valign="bottom">Con frecuencia</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Reservar un espacio de estacionamiento</td><td valign="bottom">Con frecuencia</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Evaluar la seguridad del estacionamiento antes de reservar</td><td valign="bottom">A veces </td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Cancelar una reserva de estacionamiento</td><td valign="bottom">Rara vez</td><td valign="bottom">Media</td></tr>
<tr><td valign="bottom">Pagar el estacionamiento a través de la plataforma</td><td valign="bottom">Con frecuencia</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Calificar el servicio de estacionamiento</td><td valign="bottom">A veces</td><td valign="bottom">Media</td></tr>
<tr><td valign="bottom">Recibir alertas sobre la disponibilidad de espacios</td><td valign="bottom">Con frecuencia</td><td valign="bottom">Alta</td></tr>
</table>

### **Segmento Jovenes Freelancer**

<table><tr><th rowspan="2" valign="top">Actividades</th><th colspan="2" valign="top">Jose Perez</th></tr>
<tr><td valign="top">Frecuencia</td><td valign="top">Importancia</td></tr>
<tr><td valign="bottom">Publicar disponibilidad de su cochera en la plataforma</td><td valign="bottom">A veces</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Verificar la identidad de los usuarios que desean alquilar la 
cochera</td><td valign="bottom">A veces</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Confirmar la reserva de la cochera</td><td valign="bottom">Con frecuencia</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Recibir pagos por el alquiler de la cochera</td><td valign="bottom">Con frecuencia</td><td valign="bottom">Alta</td></tr>
<tr><td valign="bottom">Gestionar cancelaciones de reservas</td><td valign="bottom">Rara vez</td><td valign="bottom">Media</td></tr>
<tr><td valign="bottom">Comunicarse con los inquilinos a través de la plataforma</td><td valign="bottom">A veces</td><td valign="bottom">Media</td></tr>
<tr><td valign="bottom">Actualizar la información de su cochera en la plataforma</td><td valign="bottom">Rara vez</td><td valign="bottom">Media</td></tr>
</table>

### 2.3.3. User Journey Mapping

A continuación, se presentan los User Journey Mapping para los segmentos de conductores y anfitriones, ilustrando sus experiencias al interactuar con HomeyPark.

### **Segmento Usuario de Parking**

<img src= "../Assets/chapter2/UserJourneyMappingLuisArturo.png">

### **Segmento Anfitrion**

<img src="../Assets/chapter2/UserJourneyMappingJosePerez.png">

### 2.3.4. Empathy Mapping

Aquí se muestran los Empathy Map para los segmentos de jóvenes universitarios y freelancers, ofreciendo una visión detallada de sus pensamientos, sentimientos y necesidades.

### **Usuario de Parking**

<img src="../Assets/chapter2/EmpathyMapLuisArturo.png">

### **Anfitrion**

<img src="../Assets/chapter2/EmpathyMapJosePerez.png">

### 2.3.5. As-is Scenario Mapping

El As-Is Scenario Mapping describe la experiencia actual de los conductores al buscar estacionamiento y los propietarios de cocheras al intentar rentarlas. Los conductores pierden tiempo y combustible buscando espacios disponibles en zonas congestionadas, mientras que los propietarios tienen garajes con frecuencia baja o nula de uso que podrían generar ingresos adicionales. Este mapeo identifica los puntos de fricción y oportunidades de mejora que HomeyPark busca resolver, como la falta de visibilidad de espacios disponibles, inquietudes sobre seguridad y la ausencia de un sistema estructurado para conectar ambos segmentos del mercado de manera eficiente.

### **Usuario de Parking**

<img src="../Assets/scenarioMapping/as-is-scenario-usurario-parking.png">

### **Anfitrion**

<img src="../Assets/scenarioMapping/as-is-scenario-anfitrion.png">

## 2.4. Ubiquitous Language(Cambiar)

El Ubiquitous Language es un conjunto de términos y conceptos que comparten los desarrolladores y los expertos del dominio (en este caso, los usuarios de HomeyPark) para describir el sistema. Su objetivo es reducir la ambigüedad y facilitar la comunicación entre todos los involucrados en el proyecto. A continuación, se presenta un Ubiquitous Language inicial para HomeyPark:

- **Usuario de parking**: Persona que busca una solución para su necesidad de encontrar un estacionamiento en entornos urbanos para su vehículo.
- **Anfitrión**: Propietario de una vivienda que cuenta con una cochera privada y busca obtener provecho económico de ella.
- **Estacionamiento**: Espacio donde un vehículo puede ser aparcado. Dentro de la aplicación, un estacionamiento tendrá atributos como ubicación, precio, disponibilidad, tamaño, reseñas, horarios, teléfono de servicio y descripción.
- **Reserva**: Acción de asegurar un espacio de estacionamiento para un tiempo determinado. Los usuarios de parking podrán realizar reservas, y los anfitriones podrán confirmarlas.
- **Cochera privada**: Un garaje o espacio de estacionamiento perteneciente a una vivienda particular, que un anfitrión puede ofrecer en alquiler.
- **Búsqueda**: Funcionalidad que permite a los usuarios de parking encontrar estacionamientos disponibles según diferentes criterios como ubicación, precio, y disponibilidad.
- **Pago**: Proceso mediante el cual el usuario de parking abona el costo de la reserva del estacionamiento.
- **Calificación**: Sistema que permite a los usuarios de parking evaluar el servicio de estacionamiento y a los anfitriones.
- **Reseña**: Comentario o valoración escrita por un usuario sobre su experiencia con un estacionamiento o un anfitrión.

<h1 id="capitulo-iii-requirements-specification">Capítulo III: Requirements Specification</h1>

## 3.1. To-Be Scenario Mapping

A continuación, mostraremos la experiencia ideal de los usuarios al usar la aplicación HomeyPark para encontrar y reservar espacios de estacionamiento. Los conductores pueden ubicar rápidamente lugares disponibles cerca de su destino, mientras que los propietarios de cocheras pueden rentarlas de forma segura cuando no las utilizan.

### **Usuario de Parking**

<img src="../Assets/scenarioMapping/to-be-scenario-usuarios-parking.png">

### **Anfitrion**

<img src="../Assets/scenarioMapping/to-be-scenario-anfitrion.png">

## 3.2. User Stories

Las User Stories y Épicas permiten descomponer y organizar las funcionalidades del sistema desde la perspectiva del usuario. Las épicas agrupan funcionalidades clave, mientras que las user stories detallan necesidades específicas que guían el desarrollo de la aplicación.

**Epics**

| Epic ID | Nombre                      | Descripción                                                                                                   |
| ------- | --------------------------- | ------------------------------------------------------------------------------------------------------------- |
| EP1     | Landing Page                | Pantalla principal de la aplicación donde se presenta la propuesta de valor, beneficios y navegación general. |
| EP2     | Autenticación y sesión      | Funcionalidades relacionadas al registro, inicio y cierre de sesión de los usuarios.                          |
| EP3     | Gestión de estacionamientos | Visualización, búsqueda, publicación y edición de cocheras disponibles para arrendar.                         |
| EP4     | Gestión de reservas         | Permitir que los usuarios arrendatarios puedan reservar, cancelar o consultar reservas.                       |
| EP5     | Seguimiento de servicios    | Acceso a historial, servicios en curso y próximos tanto para arrendadores como arrendatarios.                 |
| EP6     | Control de reservas activas | Proceso de aprobación, finalización y validación de reservas realizadas.                                      |
| EP7     | Gestión de vehículos        | Permitir que los usuarios registren, editen o eliminen los vehículos vinculados a su cuenta.                  |
| EP8     | Perfil del usuario          | Visualización y actualización de la información personal del usuario.                                         |

**User Stories**

| Epic / Story ID | Título                                       | Descripción                                                                                                                                                                     | Relacionado con (Epic ID) | Criterios de Aceptación (Given-When-Then)                                                                                                                                                                                                                                                                     |
| --------------- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US-01           | Ver portada                                  | Como usuario, quiero ver una portada para entender de qué trata la plataforma                                                                                                   | EP1                       | 1. Dado que el usuario visita la página de inicio, cuando la página carga completamente, entonces ve la portada con título y subtítulo. <br>2. Dado que el usuario ingresa desde dispositivos diversos, cuando se carga la página, entonces la portada se adapta correctamente a cada pantalla.               |
| US-02           | Ver beneficios                               | Como usuario, quiero ver los beneficios para entender por qué me conviene                                                                                                       | EP1                       | 1. Dado que el usuario explora la landing page, cuando llega a la sección de beneficios, entonces se muestran al menos tres beneficios destacados. <br>2. Dado que el usuario consulta la sección de beneficios, cuando se presenta el contenido, entonces la información es clara y fácilmente comprensible. |
| US-03           | Ver ejemplos de servicios                    | Como usuario, quiero ver ejemplos de servicios para imaginar su uso                                                                                                             | EP1                       | 1. Dado que el usuario accede a la sección de ejemplos, cuando la página carga, entonces se muestran al menos tres tarjetas descriptivas. <br>2. Dado que el usuario interactúa con las tarjetas, cuando selecciona una, entonces se muestra información ampliada sobre el servicio.                          |
| US-04           | Ver precios                                  | Como usuario, quiero ver una sección de precios para conocer los planes                                                                                                         | EP1                       | 1. Dado que el usuario busca información de precios, cuando accede a la sección, entonces se muestran los planes organizados en una tabla o listado. <br>2. Dado que el usuario compara planes, cuando revisa la sección de precios, entonces se detallan características y valores de cada plan.             |
| US-05           | Ver testimonios                              | Como usuario, quiero ver la sección de testimonios para una mayor referencia                                                                                                    | EP1                       | 1. Dado que el usuario accede a la sección de testimonios, cuando la página carga, entonces se visualizan al menos tres testimonios con nombre e imagen. <br>2. Dado que el usuario desplaza la vista, cuando revisa la sección, entonces los testimonios se muestran en un formato legible y organizado.     |
| US-06           | Ver barra de navegación                      | Como usuario, quiero contar con una barra de navegación para facilitar la búsqueda                                                                                              | EP1                       | 1. Dado que el usuario se encuentra en cualquier sección, cuando observa la interfaz, entonces la barra de navegación es visible. <br>2. Dado que el usuario interactúa con la barra, cuando selecciona un enlace, entonces es redirigido sin errores a la sección correspondiente.                           |
| US-07           | Ver equipo                                   | Como usuario, quiero ver la sección del equipo para conocer su propósito o historia                                                                                             | EP1                       | 1. Dado que el usuario quiere conocer al equipo, cuando ingresa a esa sección, entonces se muestran fotos, nombres y roles de cada miembro. <br>2. Dado que el usuario revisa la historia del equipo, cuando visualiza la sección, entonces se aprecia una breve descripción o propósito de cada integrante.  |
| US-08           | Ver footer                                   | Como usuario, quiero un footer para acceder a información adicional                                                                                                             | EP1                       | 1. Dado que el usuario llega al final de la página, cuando la misma carga, entonces el footer es visible con enlaces a contacto y políticas. <br>2. Dado que el usuario explora el footer, cuando revisa su contenido, entonces la información adicional se presenta de forma organizada.                     |
| US-09           | Registrarse                                  | Como usuario, quiero registrarme con correo, contraseña y datos de perfil para crear una cuenta                                                                                 | EP2                       | 1. Dado que el usuario quiere crear una cuenta, cuando completa todos los campos requeridos, entonces se crea la cuenta y se notifica al usuario. 2. Dado que el usuario ingresa un correo duplicado, cuando intenta registrarse, entonces se muestra un mensaje de error pertinente.                         |
| US-10           | Iniciar sesión                               | Como usuario, quiero iniciar sesión con correo y contraseña para acceder a mi cuenta                                                                                            | EP2                       | 1. Dado que el usuario tiene una cuenta, cuando introduce credenciales correctas, entonces inicia sesión y es redirigido al dashboard. 2. Dado que el usuario introduce credenciales erróneas, cuando intenta iniciar sesión, entonces se muestra un mensaje de error sin permitir el acceso.                 |
| US-11           | Cerrar sesión                                | Como usuario, quiero poder cerrar sesión para proteger mi información                                                                                                           | EP2                       | 1. Dado que el usuario está autenticado, cuando selecciona la opción de cerrar sesión, entonces se termina la sesión y se redirige al login. 2. Dado que el usuario cierra sesión, cuando intenta acceder a una sección protegida, entonces se redirige al login.                                             |
| US-12           | Búsqueda de estacionamientos por dirección   | Como arrendatario quiero ingresar una dirección para encontrar los espacios de estacionamiento en el mapa                                                                       | EP3                       | 1. Dado que el usuario ingresa una dirección válida, cuando presiona buscar, entonces se muestran los estacionamientos disponibles en esa zona. 2. Dado que el usuario ingresa una dirección no válida, cuando presiona buscar, entonces se muestra un mensaje de error.                                      |
| US-13           | Visualizar estacionamientos en mapa          | Como arrendatario, quiero visualizar los estacionamientos en un mapa para tener una mayor referencia                                                                            | EP3                       | 1. Dado que hay estacionamientos disponibles, cuando se carga el mapa, entonces se muestran marcadores en la ubicación correspondiente. 2. Dado que no hay estacionamientos, cuando se carga el mapa, entonces se muestra un mensaje indicando que no hay resultados.                                         |
| US-14           | Ver espacios cercanos                        | Como arrendatario, quiero ver los espacios cercanos en modo de lista para ver todos los espacios en mi zona                                                                     | EP3                       | 1. Dado que el usuario permite el acceso a su ubicación, cuando entra a la sección de lista, entonces se muestran los espacios cercanos. 2. Dado que el usuario no da permisos de ubicación, cuando entra a la sección de lista, entonces se muestra una advertencia.                                         |
| US-15           | Ver detalle de estacionamiento               | Como arrendatario, quiero visualizar los detalles del estacionamiento para encontrar el mejor puesto                                                                            | EP3                       | 1. Dado que el usuario selecciona un estacionamiento, cuando se muestra el detalle, entonces debe contener la información completa: dirección, precio, horario y disponibilidad. 2. Dado que no se puede cargar el detalle, cuando el usuario selecciona, entonces se muestra un error.                       |
| US-16           | Ver calificación del estacionamiento         | Como arrendatario, quiero visualizar la calificación del estacionamiento para evitar fraudes                                                                                    | EP3                       | 1. Dado que el estacionamiento tiene calificaciones, cuando el usuario visualiza el detalle, entonces se muestra un promedio de calificaciones con comentarios. 2. Dado que no hay calificaciones, cuando se visualiza el detalle, entonces se muestra un mensaje indicando “Sin reseñas aún”.                |
| US-17           | Vista previa del lugar                       | Como arrendatario, quiero visualizar el entorno del estacionamiento para reconocer el lugar                                                                                     | EP3                       | 1. Dado que el estacionamiento tiene imágenes, cuando el usuario entra al detalle, entonces se muestran las imágenes del entorno. 2. Dado que no hay imágenes disponibles, cuando se accede al detalle, entonces se muestra un mensaje informativo.                                                           |
| US-18           | Registrar cochera                            | Como arrendador, quiero registrar mi cochera como estacionamiento para generar ingresos                                                                                         | EP3                       | 1. Dado que el arrendador llena todos los campos requeridos, cuando presiona registrar, entonces la cochera se guarda exitosamente. 2. Dado que falta información, cuando intenta registrar, entonces se muestra un mensaje de validación.                                                                    |
| US-19           | Ver mis cocheras registradas                 | Como arrendador, quiero visualizar mis cocheras registradas para gestionarlas                                                                                                   | EP3                       | 1. Dado que el arrendador tiene cocheras registradas, cuando accede a la sección, entonces se muestran en una lista con sus detalles. 2. Dado que no tiene cocheras, cuando accede, entonces se muestra un mensaje indicando que aún no ha registrado ninguna.                                                |
| US-20           | Actualizar cochera                           | Como arrendador, quiero modificar mis cocheras registradas                                                                                                                      | EP3                       | 1. Dado que el arrendador selecciona una cochera, cuando modifica los datos y guarda, entonces los cambios se actualizan correctamente. 2. Dado que no llena un campo obligatorio, cuando intenta guardar, entonces se muestra un mensaje de error.                                                           |
| US-21           | Eliminar cochera                             | Como arrendador, quiero eliminar mi cochera                                                                                                                                     | EP3                       | 1. Dado que el arrendador desea eliminar una cochera, cuando confirma la acción, entonces se elimina de la lista. 2. Dado que cancela la eliminación, cuando se le pide confirmación, entonces no se ejecuta ninguna acción.                                                                                  |
| US-22           | Solicitar reserva                            | Como arrendatario, quiero solicitar la reserva de un estacionamiento                                                                                                            | EP4                       | 1. Dado que el usuario llena la información requerida, cuando presiona reservar, entonces se envía la solicitud al arrendador. 2. Dado que la información está incompleta, cuando intenta reservar, entonces se muestra una advertencia.                                                                      |
| US-23           | Seleccionar horario de reserva               | Como arrendatario, quiero indicar el horario en la solicitud                                                                                                                    | EP4                       | 1. Dado que el usuario elige un rango de tiempo, cuando lo confirma, entonces el horario queda registrado en la reserva. 2. Dado que no selecciona un horario, cuando intenta continuar, entonces se muestra un mensaje de error.                                                                             |
| US-24           | Seleccionar vehículo para reserva            | Como arrendatario, quiero indicar el vehículo a usar                                                                                                                            | EP4                       | 1. Dado que el usuario tiene vehículos registrados, cuando selecciona uno, entonces se asocia con la reserva. 2. Dado que no tiene vehículos, cuando accede a la selección, entonces se muestra una opción para registrar uno.                                                                                |
| US-25           | Cancelar solicitud de reserva                | Como arrendatario, quiero cancelar la reserva                                                                                                                                   | EP4                       | 1. Dado que el usuario ya reservó, cuando presiona cancelar y confirma, entonces se elimina la solicitud. 2. Dado que decide no cancelar, cuando rechaza la confirmación, entonces no se realiza ninguna acción.                                                                                              |
| US-26           | Rechazar solicitud de reserva                | Como arrendador, quiero rechazar las solicitudes de reserva                                                                                                                     | EP4                       | 1. Dado que recibe una solicitud, cuando presiona rechazar y confirma, entonces el arrendatario recibe una notificación de rechazo.                                                                                                                                                                           |
| US-27           | Aprobar solicitud de reserva                 | Como arrendador, quiero aprobar las solicitudes de reserva                                                                                                                      | EP4                       | 1. Dado que recibe una solicitud, cuando presiona aprobar, entonces el arrendatario recibe la confirmación y los detalles de la reserva.                                                                                                                                                                      |
| US-28           | Ver próximas reservas                        | Como arrendatario, quiero visualizar mis próximas reservas                                                                                                                      | EP5                       | 1. Dado que el usuario tiene reservas futuras, cuando accede a la sección, entonces se muestran en orden cronológico. 2. Dado que no tiene reservas, cuando entra a la sección, entonces se muestra un mensaje informativo.                                                                                   |
| US-29           | Ver reservas en curso                        | Como arrendatario, quiero visualizar mis reservas en curso                                                                                                                      | EP5                       | 1. Dado que el usuario tiene reservas activas, cuando entra a la sección, entonces se listan las reservas con su estado. 2. Dado que no tiene reservas en curso, cuando accede, entonces se muestra un mensaje correspondiente.                                                                               |
| US-30           | Ver historial de reservas                    | Como arrendatario, quiero visualizar mi historial de reservas                                                                                                                   | EP5                       | 1. Dado que el usuario ha realizado reservas, cuando entra a historial, entonces se muestran las reservas pasadas con fecha y lugar. 2. Dado que no hay historial, se muestra un mensaje indicando que aún no ha reservado.                                                                                   |
| US-31           | Ver detalle de reserva                       | Como arrendatario, quiero visualizar el detalle de mi reserva                                                                                                                   | EP5                       | 1. Dado que el usuario selecciona una reserva, cuando se accede al detalle, entonces se muestra el horario, cochera, estado y datos del propietario.                                                                                                                                                          |
| US-32           | Ver próximos servicios                       | Como arrendador, quiero visualizar mis próximos servicios                                                                                                                       | EP5                       | 1. Dado que hay servicios próximos, cuando accede a la sección, entonces se listan con su fecha y datos del arrendatario. 2. Dado que no hay próximos servicios, se muestra un mensaje indicándolo.                                                                                                           |
| US-33           | Ver servicios en curso                       | Como arrendador, quiero visualizar mis servicios en curso                                                                                                                       | EP5                       | 1. Dado que hay reservas activas, cuando accede a la sección, entonces se muestran con los horarios y placas de los vehículos.                                                                                                                                                                                |
| US-34           | Ver historial de servicios                   | Como arrendador, quiero visualizar mi historial de servicios realizados                                                                                                         | EP5                       | 1. Dado que ha tenido reservas anteriores, cuando entra al historial, entonces se muestran las fechas, cocheras y arrendatarios.                                                                                                                                                                              |
| US-35           | Ver detalle del servicio                     | Como arrendador, quiero visualizar el detalle mi servicio                                                                                                                       | EP5                       | 1. Dado que el arrendador selecciona un servicio, cuando accede al detalle, entonces se muestra toda la información relevante del mismo.                                                                                                                                                                      |
| US-36           | Iniciar proceso de reserva                   | Como arrendador, quiero iniciar el proceso de reserva                                                                                                                           | EP6                       | 1. Dado que un arrendatario ha enviado una solicitud, cuando el arrendador la aprueba, entonces inicia el proceso y se notifica al arrendatario.                                                                                                                                                              |
| US-37           | Finalizar reserva                            | Como arrendatario, quiero dar por finalizado la reserva                                                                                                                         | EP6                       | 1. Dado que el usuario ha utilizado el estacionamiento, cuando presiona finalizar, entonces el sistema actualiza el estado a 'finalizado'.                                                                                                                                                                    |
| US-38           | Subir comprobante de pago                    | Como arrendatario, quiero subir mi comprobante de pago                                                                                                                          | EP6                       | 1. Dado que el usuario ha efectuado el pago, cuando sube el comprobante, entonces se almacena y se notifica al arrendador para su validación. 2. Dado que el comprobante no es válido, cuando se intenta subir, entonces se muestra un mensaje de error.                                                      |
| US-39           | Ver vehículos registrados                    | Como usuario, quiero ver mis vehículos registrados                                                                                                                              | EP7                       | 1. Dado que el usuario tiene vehículos registrados, cuando entra a la sección, entonces se muestran en formato de lista. 2. Dado que no tiene vehículos registrados, se muestra un mensaje indicándolo.                                                                                                       |
| US-40           | Añadir vehículo                              | Como usuario, quiero añadir mi vehículo en la aplicación                                                                                                                        | EP7                       | 1. Dado que el usuario completa los datos del vehículo, cuando presiona guardar, entonces se registra y aparece en la lista de vehículos. 2. Dado que falta un campo obligatorio, el sistema muestra un mensaje de error.                                                                                     |
| US-41           | Editar vehículo                              | Como usuario, quiero editar la información de mi vehículo                                                                                                                       | EP7                       | 1. Dado que el usuario edita los datos del vehículo, cuando guarda, entonces se actualiza correctamente.                                                                                                                                                                                                      |
| US-42           | Eliminar vehículo                            | Como usuario, quiero eliminar mi vehículo en la aplicación                                                                                                                      | EP7                       | 1. Dado que el usuario desea eliminar un vehículo, cuando confirma la acción, entonces se elimina de la lista. 2. Dado que cancela la acción, entonces no se realiza ningún cambio.                                                                                                                           |
| US-43           | Ver perfil                                   | Como usuario, quiero visualizar mi perfil                                                                                                                                       | EP8                       | 1. Dado que el usuario accede a la sección de perfil, cuando carga la vista, entonces se muestran sus datos personales actualizados.                                                                                                                                                                          |
| US-44           | Actualizar perfil                            | Como usuario, quiero editar mi perfil                                                                                                                                           | EP8                       | 1. Dado que el usuario edita sus datos, cuando guarda los cambios, entonces se actualiza la información correctamente. 2. Dado que falta algún campo obligatorio, entonces se muestra un mensaje de error.                                                                                                    |
| TS-01           | Implementar sistema de navegación            | Como desarrollador, quiero configurar un sistema de rutas nombradas para moverme entre las diferentes vistas (registro, login, listado, mapa, perfil, etc.).                    | EP2                       | 1. Dado que el usuario interactúa con botones de navegación, cuando los presiona, entonces es redirigido a la pantalla correspondiente. 2. Dado que se ingresa una ruta no válida, cuando se intenta acceder, entonces se muestra una pantalla de error manejada.                                             |
| TS-02           | Configurar control de estado global          | Como desarrollador, quiero implementar un sistema de manejo de estado para mantener sincronizados datos entre pantallas (usuario, vehículos, reservas, etc.).                   | EP2                       | 1. Dado que se actualiza un estado compartido, cuando un componente lo modifica, entonces los demás componentes reflejan el cambio. 2. Dado que se cierra sesión, cuando el usuario regresa a una vista anterior, entonces los datos deben estar limpios.                                                     |
| TS-03           | Implementar validación de formularios        | Como desarrollador, quiero agregar validaciones a los formularios (login, registro, creación de cochera) para asegurar que los datos ingresados sean correctos.                 | EP2                       | 1. Dado que el usuario completa un formulario, cuando un campo requerido está vacío, entonces se muestra un mensaje de validación. 2. Dado que todos los campos son válidos, cuando se envía el formulario, entonces continúa el proceso sin errores.                                                         |
| TS-04           | Desarrollar lógica de geolocalización        | Como desarrollador, quiero acceder a la ubicación actual del usuario para mostrar estacionamientos cercanos en tiempo real.                                                     | EP3                       | 1. Dado que el usuario permite acceso a su ubicación, cuando entra a la vista de búsqueda, entonces se obtiene su ubicación actual. 2. Dado que el usuario deniega el permiso, cuando entra a la vista, entonces se muestra un mensaje alternativo o una vista de fallback.                                   |
| TS-05           | Integrar Google Maps en la vista de búsqueda | Como desarrollador, quiero integrar un mapa para mostrar los estacionamientos disponibles según la ubicación del usuario.                                                       | EP3                       | 1. Dado que hay estacionamientos disponibles, cuando se carga el mapa, entonces se muestran los marcadores. 2. Dado que no hay estacionamientos disponibles, cuando se carga el mapa, entonces se muestra un mensaje indicándolo.                                                                             |
| TS-06           | Implementar CRUD de cocheras                 | Como desarrollador, quiero desarrollar las funciones para crear, leer, actualizar y eliminar cocheras registradas por el arrendador.                                            | EP3                       | 1. Dado que el usuario arrendador accede a la sección de cocheras, cuando añade una nueva, entonces esta se guarda correctamente. 2. Dado que edita o elimina una cochera, entonces los cambios se reflejan inmediatamente en su listado.                                                                     |
| TS-07           | Implementar CRUD de vehículos                | Como desarrollador, quiero permitir que los usuarios puedan añadir, visualizar, editar y eliminar la información de sus vehículos.                                              | EP7                       | 1. Dado que el usuario desea registrar su vehículo, cuando completa los campos obligatorios, entonces se guarda y aparece en la lista. 2. Dado que el usuario edita o elimina un vehículo, entonces el sistema refleja los cambios correctamente.                                                             |
| TS-08           | Implementar CRUD de reservas                 | Como desarrollador, quiero desarrollar la funcionalidad para que los arrendatarios puedan registrar, cancelar y consultar sus reservas, y los arrendadores puedan gestionarlas. | EP4                       | 1. Dado que el usuario crea una reserva, cuando se valida la información, entonces esta se registra en el sistema. 2. Dado que el usuario desea cancelar una reserva, cuando confirma la acción, entonces se elimina correctamente.                                                                           |
| TS-09           | CRUD de perfil de usuario                    | Como desarrollador, quiero implementar la edición y visualización del perfil del usuario para que pueda modificar sus datos personales.                                         | EP8                       | 1. Dado que el usuario accede a su perfil, cuando actualiza su información, entonces esta se guarda correctamente. 2. Dado que se dejan campos requeridos vacíos, entonces se muestra una advertencia de validación.                                                                                          |

## 3.3. Product Backlog

El Product Backlog es una lista priorizada de funcionalidades, mejoras y requerimientos que guían el desarrollo del producto. Incluye todas las épicas, user stories y technical stories, sirviendo como base para la planificación y evolución continua de la aplicación.

| Orden | ID    | Título                                       | Descripción                                                                                           | Épica | Story Points |
| :---- | :---- | :------------------------------------------- | :---------------------------------------------------------------------------------------------------- | :---- | -----------: |
| 1     | TS-05 | Integrar Google Maps en la vista de búsqueda | Como desarrollador, quiero integrar Google Maps para visualizar estacionamientos disponibles.         | EP3   |            8 |
| 2     | TS-04 | Desarrollar lógica de geolocalización        | Como desarrollador, quiero acceder a la ubicación del usuario para mostrar estacionamientos cercanos. | EP3   |            5 |
| 3     | US-13 | Visualizar estacionamientos en mapa          | Como arrendatario, quiero visualizar estacionamientos en el mapa.                                     | EP3   |            5 |
| 4     | US-12 | Búsqueda de estacionamientos por dirección   | Como arrendatario, quiero buscar por dirección para encontrar estacionamientos.                       | EP3   |            5 |
| 5     | TS-06 | Implementar CRUD de cocheras                 | Como desarrollador, quiero implementar funciones CRUD para cocheras registradas.                      | EP3   |            5 |
| 6     | US-22 | Solicitar reserva                            | Como arrendatario, quiero reservar un estacionamiento.                                                | EP4   |            5 |
| 7     | TS-08 | Implementar CRUD de reservas                 | Como desarrollador, quiero implementar la funcionalidad CRUD para reservas.                           | EP4   |            5 |
| 8     | TS-02 | Configurar control de estado global          | Como desarrollador, quiero implementar un sistema de manejo de estado para sincronizar datos.         | EP2   |            5 |
| 9     | US-15 | Ver detalle de estacionamiento               | Como arrendatario, quiero ver los detalles del estacionamiento.                                       | EP3   |            3 |
| 10    | US-23 | Seleccionar horario de reserva               | Como arrendatario, quiero seleccionar un horario para la reserva.                                     | EP4   |            3 |
| 11    | TS-01 | Implementar sistema de navegación            | Como desarrollador, quiero configurar un sistema de rutas nombradas para moverme entre vistas.        | EP2   |            3 |
| 12    | TS-03 | Implementar validación de formularios        | Como desarrollador, quiero agregar validaciones a los formularios para asegurar datos válidos.        | EP2   |            3 |
| 13    | US-09 | Registrarse                                  | Como usuario, quiero registrarme para crear una cuenta.                                               | EP2   |            3 |
| 14    | US-18 | Registrar cochera                            | Como arrendador, quiero registrar mi cochera para generar ingresos.                                   | EP3   |            3 |
| 15    | US-20 | Actualizar cochera                           | Como arrendador, quiero actualizar la información de mi cochera.                                      | EP3   |            3 |
| 16    | US-21 | Eliminar cochera                             | Como arrendador, quiero eliminar una cochera registrada.                                              | EP3   |            3 |
| 17    | TS-07 | Implementar CRUD de vehículos                | Como desarrollador, quiero desarrollar funciones CRUD para vehículos del usuario.                     | EP7   |            3 |
| 18    | TS-09 | CRUD de perfil de usuario                    | Como desarrollador, quiero permitir la edición y visualización del perfil de usuario.                 | EP8   |            3 |
| 19    | US-38 | Subir comprobante de pago                    | Como arrendatario, quiero subir el comprobante de pago.                                               | EP6   |            3 |
| 20    | US-16 | Ver calificación del estacionamiento         | Como arrendatario, quiero ver calificaciones para evitar fraudes.                                     | EP3   |            2 |
| 21    | US-24 | Seleccionar vehículo para reserva            | Como arrendatario, quiero seleccionar un vehículo para la reserva.                                    | EP4   |            2 |
| 22    | US-25 | Cancelar solicitud de reserva                | Como arrendatario, quiero cancelar una reserva solicitada.                                            | EP4   |            2 |
| 23    | US-26 | Rechazar solicitud de reserva                | Como arrendador, quiero rechazar una solicitud de reserva.                                            | EP4   |            2 |
| 24    | US-27 | Aprobar solicitud de reserva                 | Como arrendador, quiero aprobar una solicitud de reserva.                                             | EP4   |            2 |
| 25    | US-10 | Iniciar sesión                               | Como usuario, quiero iniciar sesión con mi correo y contraseña.                                       | EP2   |            2 |
| 26    | US-17 | Vista previa del lugar                       | Como arrendatario, quiero una vista previa del entorno del estacionamiento.                           | EP3   |            2 |
| 27    | US-14 | Ver espacios cercanos                        | Como arrendatario, quiero ver espacios cercanos en lista.                                             | EP3   |            2 |
| 28    | US-19 | Ver mis cocheras registradas                 | Como arrendador, quiero ver mis cocheras registradas.                                                 | EP3   |            2 |
| 29    | US-40 | Añadir vehículo                              | Como usuario, quiero añadir un vehículo.                                                              | EP7   |            2 |
| 30    | US-41 | Editar vehículo                              | Como usuario, quiero editar mi vehículo.                                                              | EP7   |            2 |
| 31    | US-42 | Eliminar vehículo                            | Como usuario, quiero eliminar un vehículo.                                                            | EP7   |            2 |
| 32    | US-44 | Actualizar perfil                            | Como usuario, quiero actualizar mi perfil.                                                            | EP8   |            2 |
| 33    | US-03 | Ver ejemplos de servicios                    | Como usuario, quiero ver ejemplos de servicios para imaginar su uso.                                  | EP1   |            2 |
| 34    | US-04 | Ver precios                                  | Como usuario, quiero ver una sección de precios para conocer los planes.                              | EP1   |            2 |
| 35    | US-28 | Ver próximas reservas                        | Como arrendatario, quiero ver mis próximas reservas.                                                  | EP5   |            2 |
| 36    | US-29 | Ver reservas en curso                        | Como arrendatario, quiero ver reservas en curso.                                                      | EP5   |            2 |
| 37    | US-30 | Ver historial de reservas                    | Como arrendatario, quiero ver el historial de mis reservas.                                           | EP5   |            2 |
| 38    | US-31 | Ver detalle de reserva                       | Como arrendatario, quiero ver el detalle de una reserva.                                              | EP5   |            2 |
| 39    | US-32 | Ver próximos servicios                       | Como arrendador, quiero ver mis próximos servicios.                                                   | EP5   |            2 |
| 40    | US-33 | Ver servicios en curso                       | Como arrendador, quiero ver servicios en curso.                                                       | EP5   |            2 |
| 41    | US-34 | Ver historial de servicios                   | Como arrendador, quiero ver historial de servicios.                                                   | EP5   |            2 |
| 42    | US-35 | Ver detalle del servicio                     | Como arrendador, quiero ver el detalle del servicio.                                                  | EP5   |            2 |
| 43    | US-36 | Iniciar proceso de reserva                   | Como arrendador, quiero iniciar el proceso de reserva.                                                | EP6   |            2 |
| 44    | US-37 | Finalizar reserva                            | Como arrendatario, quiero finalizar la reserva.                                                       | EP6   |            2 |
| 45    | US-11 | Cerrar sesión                                | Como usuario, quiero cerrar sesión para proteger mi información.                                      | EP2   |            1 |
| 46    | US-39 | Ver vehículos registrados                    | Como usuario, quiero ver mis vehículos registrados.                                                   | EP7   |            1 |
| 47    | US-43 | Ver perfil                                   | Como usuario, quiero ver mi perfil.                                                                   | EP8   |            1 |
| 48    | US-01 | Ver portada                                  | Como usuario, quiero ver una portada para entender de qué trata la plataforma.                        | EP1   |            1 |
| 49    | US-02 | Ver beneficios                               | Como usuario, quiero ver los beneficios para entender por qué me conviene.                            | EP1   |            1 |
| 50    | US-05 | Ver testimonios                              | Como usuario, quiero ver testimonios para tener referencias.                                          | EP1   |            1 |
| 51    | US-06 | Ver barra de navegación                      | Como usuario, quiero una barra de navegación para facilitar la búsqueda.                              | EP1   |            1 |
| 52    | US-07 | Ver equipo                                   | Como usuario, quiero ver al equipo para conocer su propósito.                                         | EP1   |            1 |
| 53    | US-08 | Ver footer                                   | Como usuario, quiero un footer para acceder a información adicional.                                  | EP1   |            1 |

## 3.4. Impact Mapping

El Impact Mapping es una técnica de planificación estratégica y visualización que nos ayuda a trazar el camino desde los objetivos del negocio hasta las entregas concretas. En el contexto de HomeyPark, utilizamos esta herramienta para conectar nuestros objetivos principales con los actores clave, sus comportamientos y las acciones específicas que necesitamos implementar.

### **Usuario de Parking**

![Impact Mapping Usuario de Parking](./../Assets/scenarioMapping/impact-mapping-usuario-parking.png)

### **Anfitrion**

![Impact Mapping Usuario de Parking](./../Assets/scenarioMapping/impact-mapping-anfitrion.png)

<h1 id="capitulo-iv-product-design">Capítulo IV: Product Design</h1>

## 4.1. Style Guidelines

En esta parte, presentaremos el plan de diseños, estilos y estéticas que hemos elaborado para nuestra página web y aplicativo móvil, con el objetivo de garantizar que nuestros usuarios disfruten de una interfaz amigable y fácil de utilizar. Para lograrlo, hemos optado por emplear elementos visuales que sean claramente visibles y estéticamente agradables, además de identificar una serie de restricciones para evitar incluir elementos gráficos discordantes o poco llamativos.

### 4.1.1. General Style Guidelines

**Branding:** Nuestro logo para HomeyPark presenta la silueta estilizada de un auto, representando la
facilidad y conveniencia del estacionamiento. Debajo del auto, se encuentran las letras "HomeyPark"
en una tipografía moderna y clara, que asegura legibilidad y fácil reconocimiento. Este diseño
simboliza la accesibilidad y la confiabilidad que ofrecemos a través de la aplicación, reflejando
seguridad y profesionalismo, valores fundamentales de HomeyPark.
<img src="../Assets/productDesign/styleGuidelines/HomeyPark_logo.png">

**Typography:\*** Para HomeyPark, se seleccionaron dos tipografías que trabajan en conjunto para crear
una experiencia visual moderna y accesible. La tipografía principal es Rubik, que aporta un estilo
geométrico y contemporáneo, ideal para títulos y encabezados, asegurando un impacto visual fuerte.
La tipografía secundaria es Mulish, utilizada para el cuerpo de texto y descripciones, gracias a su
diseño limpio y sencillo que mejora la legibilidad en dispositivos móviles y de escritorio. Juntas, estas
tipografías aseguran que toda la información relevante sea clara y fácil de leer para los usuarios.

<img src="../Assets/productDesign/styleGuidelines/HomeyPark_Typography.png">

**Colores:**
Los colores seleccionados para HomeyPark están diseñados para ofrecer una experiencia visualmente
agradable y coherente, al mismo tiempo que transmiten sensaciones de confianza y frescura. El tono
**#3C4E67** es un azul oscuro que aporta profesionalismo y estabilidad, mientras que el **#6CD391**, un
verde vibrante, introduce un toque de frescura y modernidad. Juntos, estos colores crean una
atmósfera de serenidad y dinamismo, reflejando los valores de accesibilidad y confianza de nuestra
marca.

<img src="../Assets/productDesign/styleGuidelines/HomeyPark_colores.png">

**Spacing:**
Hemos adoptado un espaciado base de 4px para los márgenes y el padding en todos los elementos,
garantizando una presentación consistente y bien alineada en toda la interfaz. Este enfoque
contribuye a una estructura visual limpia y ordenada, lo que facilita la navegación y mejora la
experiencia del usuario tanto en dispositivos móviles como en la web.

### 4.1.2. Web Style Guidelines

Para la versión web de HomeyPark, se ha priorizado una disposición responsiva que garantice una experiencia fluida sin importar el tamaño de la pantalla. Se utilizan diseños basados en rejillas (grid systems) que permiten adaptar los contenidos de manera flexible. Los botones presentan esquinas suavemente redondeadas (8px de radio) y efectos de hover que consisten en un ligero sombreado y cambio de color para indicar interactividad sin ser intrusivos. Los íconos empleados siguen una línea visual uniforme, con un tamaño estándar de 24px, permitiendo una rápida identificación de acciones y secciones. Además, se han incorporado transiciones suaves para cambios de estado (como desplegables o cambios de pestaña), mejorando la percepción de fluidez en la interfaz.

### 4.1.3. Mobile Style Guidelines

### 4.1.3.1. iOS Mobile Style Guidelines

En la versión para dispositivos iOS, HomeyPark adopta las convenciones de diseño propias del ecosistema Apple, como el uso de botones de navegación tipo "back" en la parte superior izquierda y el aprovechamiento del gesto de deslizamiento para retornar a pantallas anteriores. La interfaz sigue el patrón Human Interface Guidelines de Apple, lo que se refleja en la fluidez de las animaciones, la tipografía ajustada a San Francisco (cuando es posible), y la integración con funcionalidades como el modo oscuro. Los menús y ventanas emergentes presentan bordes redondeados y un fondo translúcido que se adapta al contexto visual del sistema operativo.

### 4.1.3.2. Android Mobile Style Guidelines

Para la versión Android, se siguen las Material Design Guidelines, priorizando la claridad visual, la jerarquía de información y la retroalimentación visual al usuario. Se utilizan componentes nativos como el AppBar, Floating Action Buttons (FAB), y Snackbars para acciones rápidas y notificaciones no intrusivas. La paleta de colores respeta los tonos definidos por la identidad de HomeyPark, integrándose con la interfaz del sistema. Se han optimizado las vistas para múltiples resoluciones y densidades de pantalla, garantizando una presentación coherente en diversos dispositivos Android. Además, se respeta la navegación por gestos introducida en versiones recientes del sistema.

## 4.2. Information Architecture

Centrados en el objetivo de HomeyPark, buscamos ofrecer una interfaz amigable e intuitiva que
inspire confianza y seguridad a los usuarios. Dado que nuestra plataforma facilita la búsqueda y
reserva de espacios de estacionamiento, estas características deben prevalecer en toda la experiencia
de usuario. Un componente crucial para lograrlo es la arquitectura de información, diseñada para
guiar a los usuarios a través de la plataforma de manera eficiente. A continuación, se detalla el plan
de arquitectura de información implementado en HomeyPark.

1. Página de Inicio:

**Home**

Sección que resalta el valor principal de HomeyPark, además explica brevemente cómo la plataforma
facilita el proceso de encontrar y gestionar estacionamientos. Esta sección invita a los usuarios a
explorar las ventajas de la plataforma y los anima a registrarse con el botón presente que los redirige
a la página de registro.

**Why Choose Us?**

Sección que resalta los beneficios y características clave de HomeyPark, explicando por qué los
usuarios deben elegir nuestra plataforma para encontrar estacionamiento.

**How It Works:**

Descripción clara y concisa del funcionamiento de la plataforma, explicando los pasos simples para
registrarse, buscar y reservar un lugar de estacionamiento.

**Testimonials:**

Sección que presenta opiniones y experiencias de usuarios que ya han utilizado HomeyPark,
destacando la facilidad y comodidad que ofrece la plataforma.

**Pricing:**

Información sobre los planes de precios de HomeyPark, proporcionando detalles transparentes y
claros para que los usuarios sepan lo que pueden esperar.

**Formulario de Contacto:**

Al final de la página, se incluye un formulario de contacto para que los usuarios puedan enviar
consultas o pedir asistencia.

2. Registro:

**Registro de Usuarios:**

Formulario que permite a los usuarios crear una cuenta en HomeyPark, solicitando información
básica como nombre, correo electrónico y una contraseña segura.

**Inicio de Sesión:**

Opción para que los usuarios ya registrados puedan acceder a su cuenta introduciendo su correo
electrónico y contraseña.

### 4.2.1. Organization Systems

El sistema de organización en HomeyPark está diseñado para brindar una experiencia clara y
eficiente, permitiendo a los usuarios navegar fácilmente por la plataforma. Nuestro enfoque está
centrado en facilitar el acceso a la información y las funcionalidades clave, lo que permite a los
usuarios registrarse, conocer los beneficios, y contactar rápidamente con nosotros.

1. Categorización de la Información:

- Why Choose Us?

  Presenta los beneficios clave de la plataforma para los usuarios, como facilidad de uso,
  seguridad y conveniencia.

- How It Works

  Categorizada en pasos simples para que los usuarios puedan entender rápidamente el
  funcionamiento del proceso de búsqueda y reserva de estacionamientos.

2. Filtros y Búsqueda:

- Filtros

  Aunque no se muestran opciones de búsqueda avanzadas en la landing page, los
  usuarios podrán aplicar filtros en la plataforma principal para ajustar sus
  preferencias, como ubicación y disponibilidad de espacios de estacionamiento.

### 4.2.2. Labeling Systems

Para el contenido, se ha priorizado la claridad y brevedad en los textos, enfocándonos en destacar los
beneficios clave de la plataforma para los usuarios. El diseño de botones sigue un estilo minimalista
con colores principales y bordes redondeados.

En cuanto a los íconos, se emplean elementos visuales sencillos y los colores del sistema de diseño
del equipo para facilitar la navegación y comprensión rápida.

### 4.2.3. SEO Tags and Meta Tags

Para asegurar una correcta indexación y visibilidad en los motores de búsqueda, es fundamental la implementación estratégica de SEO Tags y Meta Tags en la estructura HTML de nuestras páginas web. La siguiente imagen ilustra la configuración de estos elementos clave

<img src = "../Assets/SEO-Tags.png">

### 4.2.4. Searching Systems

El sistema de búsqueda en HomeyPark facilitará a los usuarios encontrar la información que
necesitan para utilizar la plataforma, centrándose principalmente en cómo funciona el sistema,
precios y opiniones de otros usuarios.

**Búsqueda por Características de Servicio:**

Los usuarios podrán buscar información sobre cómo funciona la plataforma, las ventajas de elegir
HomeyPark, y testimonios de usuarios.

**Búsqueda por Precio:**

Los usuarios podrán encontrar fácilmente la sección de precios para obtener información detallada
sobre las tarifas.

### 4.2.5. Navigation Systems

La navegación en HomeyPark ha sido diseñada para ser intuitiva, guiada y consistente a lo largo de toda la experiencia del usuario, tanto en la Landing Page como en las aplicaciones móviles y web. El objetivo es facilitar el cumplimiento de tareas como la búsqueda, reserva o publicación de estacionamientos, sin fricciones ni pérdidas de contexto.

**Landing Page**

En la Landing Page, se implementan elementos visuales y patrones de navegación claros que permiten a los usuarios explorar rápidamente la propuesta de valor. Se incluyen:

- Barra de navegación fija que permite moverse entre secciones como beneficios, precios, testimonios y contacto.

- Botones de acción visibles (“Regístrate”, “Reserva ahora”) que redirigen a las vistas correspondientes según el perfil del usuario.

- Scroll guiado verticalmente, con secciones jerarquizadas para facilitar la lectura secuencial del contenido.

**Aplicaciones móviles y web**

En las plataformas principales del producto, se utilizan rutas nombradas y una estructura de navegación jerárquica y contextual:

- Menú de navegación lateral o inferior (según la plataforma) para acceder rápidamente a vistas clave como Inicio, Mis reservas, Mis vehículos, Mi perfil, Buscar estacionamientos, entre otros.

- Navegación a través de botones contextuales, como "Reservar", "Ver detalles", "Editar perfil", que llevan al usuario a pantallas específicas dentro de su flujo actual.

- Integración con Google Maps que permite navegación basada en geolocalización para visualizar y seleccionar espacios cercanos.

- Uso de breadcrumbs y retrocesos claros, especialmente en la versión web, para no perder el hilo de navegación.

**Técnicas y acciones clave**

- Uso de flujos de usuario (user flows) previamente definidos para asegurar que cada perfil (guest y host) pueda alcanzar sus objetivos con el mínimo de pasos.

- Incorporación de redirecciones automáticas post-registro/login hacia los dashboards personalizados según el rol.

- Inclusión de notificaciones y alertas para guiar acciones pendientes (como confirmar reservas o completar registros).

Esta arquitectura de navegación está diseñada para minimizar la carga cognitiva, mantener a los usuarios orientados y maximizar la eficiencia en la interacción con la plataforma.

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

<img src="../Assets/productDesign/wireframes/landingPage/landingPage1.png" width= "1000">
<img src="../Assets/productDesign/wireframes/landingPage/landingPage2.png" width= "1000">
<img src="../Assets/productDesign/wireframes/landingPage/landingPage_3.png" width= "1000">
<img src="../Assets/productDesign/wireframes/landingPage/landingPage4.png" width= "1000">
<img src="../Assets/productDesign/wireframes/landingPage/landingPage5.png" width= "1000">
<img src="../Assets/productDesign/wireframes/landingPage/landingPage-abouttheproduct.png" width= "1000"><img src="../Assets/productDesign/wireframes/landingPage/landingPage6.png" width= "1000">

### 4.3.2. Landing Page Mock-up

<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-1.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-2.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-3.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-4.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-5.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-6.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-7.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-8.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-9.png" width= "1000">
<img src="../Assets/productDesign/mockups/landingPage/landingPageMockUp-10.png" width= "1000">

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-1.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-2.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-3.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-4.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-5.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-6.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-7.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-8.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-9.png" width= "350">
<img src="../Assets/productDesign/wireframes/mobile/mobileWireframe-10.png" width= "350">

### 4.4.2. Mobile Applications Wireflow Diagrams

**User goal:** El usuario se registra en la plataforma e inicia sesión en la aplicación con sus datos.

<img src="../Assets/productDesign/wireframes/mobile/mobile-wireflow-1.png" width= "1000">
Descripción: Al iniciar la aplicación, el usuario se encuentra con el apartado de registro de cuenta, 
donde podrá registrarse con su email y contraseña. Cuando le de al botón de registrarse, le mandará 
al apartado de inicio de sesión, donde podrá ingresar sus datos anteriormente añadidos y al ser las 
correctas, podrá acceder a la página principal de la plataforma. 
<br><br>

**User goal:** Usuario desea hacer la búsqueda y reserva de un espacio de estacionamiento
<img src="../Assets/productDesign/wireframes/mobile/mobile-wireflow-2.png" width= "1000">
<img src="../Assets/productDesign/wireframes/mobile/mobile-wireflow-3.png" width= "1000">
Descripción: El usuario al encontrarse en la página principal, podrá visualizar y buscar
estacionamientos de su preferencia. Al seleccionar un estacionamiento, verá el detalle de este, aquí
el usuario contará con dos opciones, ver los comentarios y calificación o seleccionar la opción de
reservar ahora. El usuario al ingresar a la sección de calificación visualizará los comentarios que ha
obtenido dicho estacionamiento, así como también la calificación en general del mismo. Por otro
lado, luego de seleccionar la opción de reservar, el estacionamiento habrá quedado apartado y podrá
revisarlo en la opción de historial del menú principal, donde también podrá cancelar su reserva o
revisar sus reservas pasadas.

### 4.4.3. Mobile Applications Mock-ups

<img src="../Assets/productDesign/mockups/mobile/mobileMockup-1.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-2.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-3.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-4.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-5.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-6.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-7.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-8.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-9.png" width= "350">
<img src="/Assets/productDesign/mockups/mobile/mobileMockup-10.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-11.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-12.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-13.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-14.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-15.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-16.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-17.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-18.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-19.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-20.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-21.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-22.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-23.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-24.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-25.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-26.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-27.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-28.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-29.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-30.png" width= "350">
<img src="../Assets/productDesign/mockups/mobile/mobileMockup-31.png" width= "350">

### 4.4.4. Mobile Applications User Flow Diagrams

**User goal:** El usuario se registra en la plataforma e inicia sesión en la aplicación con sus datos.
<img src="../Assets/productDesign/mockups/mobile/mobile-userflow-1.png" width= "1000">

Descripción: Al iniciar la aplicación, el usuario se encuentra con el apartado de registro de cuenta,
donde podrá registrarse con su email y contraseña. Cuando le de al botón de registrarse, le mandará
al apartado de inicio de sesión, donde podrá ingresar sus datos anteriormente añadidos y al ser las
correctas, podrá acceder a la página principal de la plataforma.

**User goal:** Usuario desea hacer la búsqueda y reserva de un espacio de estacionamiento
<img src="../Assets/productDesign/mockups/mobile/mobile-userflow-2.png" width= "1000">
<img src="../Assets/productDesign/mockups/mobile/mobile-userflow-3.png" width= "1000">
Descripción: El usuario al encontrarse en la página principal, podrá visualizar y buscar
estacionamientos de su preferencia. Al seleccionar un estacionamiento, verá el detalle de este, aquí
el usuario contará con dos opciones, ver los comentarios y calificación o seleccionar la opción de
reservar ahora. El usuario al ingresar a la sección de calificación visualizará los comentarios que ha
obtenido dicho estacionamiento, así como también la calificación en general del mismo. Por otro
lado, luego de seleccionar la opción de reservar, el estacionamiento habrá quedado apartado y podrá
revisarlo en la opción de historial del menú principal, donde también podrá cancelar su reserva o
revisar sus reservas pasadas.

## 4.5. Mobile Applications Prototyping

### 4.5.1. Android Mobile Applications Prototyping

<img src="../Assets/productDesign/mockups/mobile/prototype-mobile-1.png">

<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213143_upc_edu_pe/EWUZjmmplc1EqP9hCi4xBAUBhFL8yx-FMEiDc5Ub_OP53w?e=phhqcm&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">link del video del prototipo</a>

### 4.5.2. iOS Mobile Applications Prototyping

<img src="../Assets/productDesign/mockups/mobile/prototype-mobile-2.png">
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213143_upc_edu_pe/EWUZjmmplc1EqP9hCi4xBAUBhFL8yx-FMEiDc5Ub_OP53w?e=phhqcm&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">link del video del prototipo</a>

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes
<img src="../Assets/productDesign/wireframes/web/web-wireframe-1.png" width=1000>
<img src="../Assets/productDesign/wireframes/web/web-wireframe-2.png" width=1000>
<img src="../Assets/productDesign/wireframes/web/web-wireframe-3.png" width=1000>
<img src="../Assets/productDesign/wireframes/web/web-wireframe-4.png" width=1000>
<img src="../Assets/productDesign/wireframes/web/web-wireframe-5.png" width=1000>
<img src="../Assets/productDesign/wireframes/web/web-wireframe-6.png" width=1000>
<img src="../Assets/productDesign/wireframes/web/web-wireframe-7.png" width=1000>

### 4.6.2. Web Applications Wireflow Diagrams
**User goal:** El usuario se registra en la plataforma e inicia sesión en la aplicación con sus datos. 
<img src="../Assets/productDesign/wireframes/web/wireflow-web-1.png" width=1000>
Descripción: Al iniciar la aplicación, el usuario se encuentra con el apartado de registro de cuenta, 
donde podrá registrarse con su email y contraseña. Cuando le de al botón de registrarse, le mandará 
al apartado de inicio de sesión, donde podrá ingresar sus datos anteriormente añadidos y al ser las 
correctas, podrá acceder a la página principal de la plataforma. 
<br><br>

**User goal:** Usuario desea hacer la búsqueda y reserva de un espacio de estacionamiento
<img src="../Assets/productDesign/wireframes/web/wireflow-web-1.png" width=1000>
Descripción: El usuario al encontrarse en la página principal, podrá visualizar y buscar 
estacionamientos de su preferencia. Al seleccionar un estacionamiento, verá el detalle de este, aquí 
el usuario contará con dos opciones, ver los comentarios y calificación o seleccionar la opción de 
reservar ahora. El usuario al ingresar a la sección de calificación visualizará los comentarios que ha 
obtenido dicho estacionamiento, así como también la calificación en general del mismo. Por otro 
lado, luego de seleccionar la opción de reservar, el estacionamiento habrá quedado apartado y podrá 
revisarlo en la opción de historial del menú principal, donde también podrá cancelar su reserva o 
revisar sus reservas pasadas.

### 4.6.3. Web Applications Mock-ups
<img src="../Assets/productDesign/mockups/web/web-mockup-1.png" width=1000>
<img src="../Assets/productDesign/mockups/web/web-mockup-2.png" width=1000>
<img src="../Assets/productDesign/mockups/web/web-mockup-3.png" width=1000>
<img src="../Assets/productDesign/mockups/web/web-mockup-4.png" width=1000>
<img src="../Assets/productDesign/mockups/web/web-mockup-5.png" width=1000>
<img src="../Assets/productDesign/mockups/web/web-mockup-6.png" width=1000>
<img src="../Assets/productDesign/mockups/web/web-mockup-7.png" width=1000>
<img src="../Assets/productDesign/mockups/web/web-mockup-8.png" width=1000>

### 4.6.4. Web Applications User Flow Diagrams
**User goal:** El usuario se registra en la plataforma e inicia sesión en la aplicación con sus datos. 

<img src="../Assets/productDesign/mockups/web/userflow-web-1.png" width=1000>
Descripción: Al iniciar la aplicación web, el usuario se encuentra con el apartado de registro de cuenta, 
donde podrá registrarse con su email y contraseña. Cuando le de al botón de registrarse, le mandará 
al apartado de inicio de sesión, donde podrá ingresar sus datos anteriormente añadidos y al ser las 
correctas, podrá acceder a la página principal de la plataforma. 

**User goal:** Usuario desea hacer la búsqueda y reserva de un espacio de estacionamiento 
<img src="../Assets/productDesign/mockups/web/userflow-web-2.png" width=1000>
Descripción: El usuario al encontrarse en la página principal, podrá visualizar y buscar 
estacionamientos de su preferencia. Al seleccionar un estacionamiento, verá el detalle de este, aquí 
el usuario contará con dos opciones, ver los comentarios y calificación o seleccionar la opción de 
reservar ahora. El usuario al ingresar a la sección de calificación visualizará los comentarios que ha 
obtenido dicho estacionamiento, así como también la calificación en general del mismo. Por otro 
lado, luego de seleccionar la opción de reservar, el estacionamiento habrá quedado apartado y podrá 
revisarlo en la opción de historial del menú principal, donde también podrá cancelar su reserva o 
revisar sus reservas pasadas. 

## 4.7. Web Applications Prototyping

<img src="../Assets/productDesign/mockups/web/web-prototype-img.png" width=1000>
<a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213143_upc_edu_pe/EfXtNH6HbHlJr_jELYgjU_wBZ7tcQHge1PQaVbP8lUP0Gg?e=5up9mz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">link del video del prototipo</a>

## 4.8. Domain-Driven Software Architecture

### 4.8.1. Software Architecture Context Diagram

Este diagrama contextualiza el sistema HomeyPark en su entorno, mostrando cómo interactúan los actores principales (Guest y Host) con el sistema central y qué servicios externos (Google Places y Google ReCaptcha V2) son utilizados para brindar funcionalidades complementarias como geolocalización y verificación de usuarios humanos.

<img src = "../Assets/ContextDiagram.png">

### 4.8.2. Software Architecture Container Diagrams

El diagrama de contenedores descompone el sistema en sus principales contenedores de ejecución. Se ilustran los distintos frontends (Mobile App y Web Application), la lógica de backend central implementada en Spring Boot, y los sistemas de almacenamiento y servicios externos. Se enfatiza el rol de la API Application como núcleo funcional del sistema.

<img src = "../Assets/ContainerDiagram.png">

### 4.8.3. Software Architecture Components Diagrams

Este diagrama muestra la estructura interna de la API Application, organizada según Bounded Contexts definidos por el modelo de dominio. Cada contexto encapsula sus propios componentes siguiendo una Clean Architecture, donde se separan claramente las responsabilidades entre controladores, servicios de aplicación, modelos del dominio y repositorios.

Además, se implementa el patrón CQRS (Command Query Responsibility Segregation), dividiendo explícitamente la lógica de lectura (Query Services) y escritura (Command Services), lo que mejora la escalabilidad y claridad del sistema. Esta arquitectura permite una evolución modular, mayor mantenibilidad y prepara el sistema para una futura transición a microservicios si fuera necesario.

<img src = "../Assets/ComponentDiagram.png">

## 4.9. Software Object-Oriented Design

### 4.9.1. Class Diagrams

El siguiente diagrama muestra las clases principales del sistema HomeyPark, incluyendo sus atributos, métodos y relaciones. Este modelo fue construido a partir de los escenarios del dominio y la funcionalidad esperada por los usuarios del sistema.

<img src = "../Assets/ClassDiagram.png">

### 4.9.2. Class Dictionary

A continuación se presenta el diccionario de clases con los atributos, tipos y descripciones de las clases más relevantes del modelo.

### Clase Usuario

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>String</td><td>Código para el usuario</td></tr>
    <tr><td>nombre</td><td>String</td><td>Nombre del usuario</td></tr>
    <tr><td>apellido</td><td>String</td><td>Apellido del usuario</td></tr>
    <tr><td>email</td><td>String</td><td>Correo del usuario</td></tr>
    <tr><td>contrasena</td><td>String</td><td>Contraseña del usuario</td></tr>
    <tr><td>historialReservas</td><td>Reserva[]</td><td>Lista de reservas hechas por el usuario</td></tr>
  </tbody>
</table>

### Clase Preferencias

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>tema</td><td>String</td><td>Tema de visualización</td></tr>
    <tr><td>idioma</td><td>String</td><td>Idioma preferido</td></tr>
    <tr><td>estacionamientosFavoritos</td><td>Estacionamiento[]</td><td>Estacionamientos favoritos</td></tr>
  </tbody>
</table>

### Clase Vehículo

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>String</td><td>Identificador del vehículo</td></tr>
    <tr><td>placa</td><td>String</td><td>Placa del vehículo</td></tr>
    <tr><td>modelo</td><td>String</td><td>Modelo del vehículo</td></tr>
    <tr><td>marca</td><td>String</td><td>Marca del vehículo</td></tr>
  </tbody>
</table>

### Clase Guest

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>vehiculo</td><td>Vehiculo</td><td>Vehículo asignado</td></tr>
    <tr><td>reservaActiva</td><td>Reserva</td><td>Reserva actualmente activa</td></tr>
  </tbody>
</table>

### Clase Host

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>estacionamientos</td><td>Estacionamiento[]</td><td>Estacionamientos administrados</td></tr>
  </tbody>
</table>

### Clase Reserva

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>String</td><td>Identificador de la reserva</td></tr>
    <tr><td>guest</td><td>Guest</td><td>Usuario que reserva</td></tr>
    <tr><td>host</td><td>Host</td><td>Propietario del espacio</td></tr>
    <tr><td>estacionamiento</td><td>Estacionamiento</td><td>Espacio reservado</td></tr>
    <tr><td>vehiculo</td><td>Vehiculo</td><td>Vehículo asociado</td></tr>
    <tr><td>tiempoRegistrado</td><td>String</td><td>Hora de registro</td></tr>
    <tr><td>tarifaTotal</td><td>double</td><td>Costo total</td></tr>
    <tr><td>horaInicio</td><td>String</td><td>Inicio de la reserva</td></tr>
    <tr><td>horaFin</td><td>String</td><td>Fin de la reserva</td></tr>
    <tr><td>resena</td><td>String</td><td>Reseña del usuario</td></tr>
    <tr><td>calificacion</td><td>double</td><td>Puntaje otorgado</td></tr>
    <tr><td>estado</td><td>String</td><td>Estado de la reserva</td></tr>
  </tbody>
</table>

### Clase Estacionamiento

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>String</td><td>Identificador del espacio</td></tr>
    <tr><td>ubicacion</td><td>Ubicacion</td><td>Ubicación física</td></tr>
    <tr><td>ancho</td><td>double</td><td>Ancho del espacio</td></tr>
    <tr><td>largo</td><td>double</td><td>Largo del espacio</td></tr>
    <tr><td>alto</td><td>double</td><td>Altura del espacio</td></tr>
    <tr><td>maxCapacidad</td><td>int</td><td>Capacidad máxima</td></tr>
    <tr><td>capDisponible</td><td>int</td><td>Capacidad disponible</td></tr>
    <tr><td>tarifaPorHora</td><td>double</td><td>Precio por hora</td></tr>
    <tr><td>calificacionTotal</td><td>double</td><td>Promedio de calificaciones</td></tr>
    <tr><td>resenas</td><td>String[]</td><td>Lista de reseñas</td></tr>
    <tr><td>horarioInicio</td><td>String</td><td>Inicio de disponibilidad</td></tr>
    <tr><td>horarioFin</td><td>String</td><td>Fin de disponibilidad</td></tr>
    <tr><td>horarioOcupado</td><td>(inicio, fin)</td><td>Horas ocupadas</td></tr>
  </tbody>
</table>

### Clase Ubicacion

<table>
  <thead>
    <tr><th>Atributo</th><th>Tipo</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>String</td><td>Identificador de ubicación</td></tr>
    <tr><td>distrito</td><td>String</td><td>Distrito</td></tr>
    <tr><td>ciudad</td><td>String</td><td>Ciudad</td></tr>
    <tr><td>coordenadas</td><td>String[]</td><td>Latitud y longitud</td></tr>
    <tr><td>tipoDireccion</td><td>String</td><td>Tipo de vía</td></tr>
    <tr><td>numeroDireccion</td><td>String</td><td>Número del inmueble</td></tr>
    <tr><td>calle</td><td>String</td><td>Nombre de la calle</td></tr>
    <tr><td>referencia</td><td>String</td><td>Referencia adicional</td></tr>
  </tbody>
</table>

## 4.10. Database Design

### 4.10.1. Relational/Non-Relational Database Diagram

Este diagrama representa el modelo lógico relacional de HomeyPark, diseñado para reflejar las entidades clave del dominio y sus relaciones. Cada tabla está normalizada y vinculada mediante claves primarias y foráneas que garantizan la integridad referencial del sistema. La base de datos incluye entidades como Usuario, Vehiculo, Estacionamiento, Reserva, Ubicacion, Horario, Reseña y Preferencias, cada una con un propósito específico para cubrir las operaciones de registro, reserva y evaluación dentro del sistema.

<img src = "../Assets/DatabaseDiagram.png">

<h1 id="capitulo-v-product-implementation">Capítulo V: Product Implementation</h1>

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### Project management

**Discord.** Utilizamos esta aplicación como medio de comunicación para mantener una
comunicación abierta entre el equipo y debido a su facilidad de uso para realizar
llamadas, compartir pantalla y dividir por salas para una mejor organización.

**Trello.** Usamos esta herramienta de gestión de tareas por tarjetas debido a su facilidad y
mostrar visibilidad del progreso en el desarrollo de actividades del equipo por
integrantes.
**WhatsApp.** Principal medio de comunicación para mantenernos conectados por medio
de mensajes de texto, imágenes y videos. Esta herramienta es utilizada con mayor
frecuencia.

### Requirements Management

Trello. Aplicación web y/o móvil para organizar los requerimientos a llevar durantes los
sprints del proyecto. También se utiliza para realizar seguimiento de las tareas o
requerimientos de los integrantes.

### Software Development

**Android Studio.** IDE de desarrollo para aplicaciones móviles de múltiples plataformas
soportado por el equipo de Google y basado en IntelliJ IDEA.

**Figma.** Herramienta de desarrollo de interfaces para usuario (UI). Principal aplicación
para desarrollar las interfaces y vistas de nuestros productos landing page y aplicación
móvil.

**IntelliJ IDEA.** IDE de desarrollo diseñado principalmente en soluciones software
basadas en el lenguaje de programación Java. Esta herramienta la usamos para
desarrollar servicios API REST con el framework de Spring Boot.

**WebStorm.** IDE completo que incluye herramientas para crear, editar y depurar código en JavaScript, HTML, CSS, y otras tecnologías web.

### Software Deployment

Google Play Console. La plataforma de Google permite subir aplicaciones móviles en
producción dentro del catálogo de Play Store.

### 5.1.2. Source Code Management

Para llevar a cabo una mejor gestión y desarrollo en equipo trabajaremos bajo la
metodología de Git Flow y convenciones para los commits, la cual se basa en desarrollo
de tareas y requerimientos en ramas especiales sin afectar la rama principal de nuestro
repositorio ni el progreso de los demás desarrolladores.

### Flujo de trabajo en Git

**Rama principal**

- Rama donde se encontrará el código puesto en producción, listo para el uso de los
  usuarios finales.

**Rama de desarrollo**

- Rama donde estarán los últimos desarrollos de requerimientos listos para llevar a
  producción.

**Ramas auxiliares**

- Ramas de _features_: En esta rama se llevarán a cabo los requerimientos asignados por integrante sin
  repercutir en sus desarrollos.

- Ramas de _hotfix_: En estas ramas se encargan principalmente de resolver bugs o incidencias en caliente.

- Ramas de _release_: En estas ramas se lleva a cabo el último paso donde se validará y resolverá posibles
  incidencias antes de subir a producción el desarrollo.

### Convenciones de commits

Nuestro equipo de desarrolladores trabajará bajo las buenas prácticas de los commits
para facilitar la redacción e identificación del impacto en nuestro producto software.

`<type>(scope): <description>`

**type**: Campo obligatorio donde se especifica el tipo de cambio realizado. Los tipos de
commits son los siguientes:

- **feat**: Introduce una nueva funcionalidad en el código.
- **fix**: Soluciona un error en el código.
- **style**: Modifica aspectos estéticos del proyecto, como formatear los archivos.
- **refactor**: Mejora el código sin añadir nuevas funcionalidades. Esto puede incluir
  la implementación de buenas prácticas.
- **docs**: Realiza cambios en la documentación sin impactar las funcionalidades del
  proyecto.
- **build**: Ajusta la configuración del proyecto, como agregar, eliminar o modificar
  dependencias.

**scope**: Campo opcional que indica el alcance del commit, incluyendo los identificadores
de historias de usuario o requisitos.

**description**: Campo obligatorio que ofrece un resumen breve del commit, en inglés y
comenzando con un verbo en infinitivo.

### Convenciones para versionamiento de lanzamientos

Para el desarrollo del proyecto, se utilizará el modelo de versionamiento “Semantic
Versioning 2.0.0” (https://semver.org/). Los commits y tags de los lanzamientos
seguirán el siguiente formato:

- Release vX.Y.Z

Donde:

- X: Indica un cambio de versión mayor (MAJOR). Es usado principalmente para
  realizar cambios significativos con respecto a versiones anteriores.
- Y: Indica un cambio de versión menor (MINOR). Este tipo de lanzamiento
  incluye funcionalidades adicionales o mejoras al producto final.
- Z: Indica la versión del parche (PATCH). No alteran las funcionalidades del
  producto, solo se encarga de corregir errores.

### 5.1.3. Source Code Style Guide & Conventions

En la siguiente sección estaremos detallando las nomenclaturas para los siguientes
lenguajes de programación y frameworks a utilizar a lo largo del proyecto.

- Gherkin
- Las especificaciones deben ser claras y fáciles de leer.
- Evitar el uso de términos técnicos para asegurar una mejor comprensión entre los
  colaboradores.
- Utilizar las palabras clave Given, When, Then, And, y But para describir el
  comportamiento del sistema.
- Evitar la redundancia en la descripción de los escenarios.
- Java
- Uso de camelCase para nombre variables y métodos
- Uso de PascalCase para nombrar clases, interfaces, record y otras estructuras.
- Importaciones explícitas (evitar importaciones con \*)
- Estructura de clases, organizar y agrupar los atributos, constructores y métodos.
- Usar indentación de dos espacios.
- La longitud de una línea no debe superar los 100 caracteres.

### 5.1.4. Software Deployment Configuration

Para el despliegue de nuestro servicio API REST usaremos la plataforma de alojamiento
Render a través de contenedores de Docker para subir nuestras aplicaciones ubicadas en
nuestro repositorio de GitHub.

Enlace al repositorio: https://github.com/NetviaOrganization/HomeyPark-Web-Service

1. Como primer paso, crearemos nuestro proyecto en un nuevo repositorio de GitHub llamado “HomeyPark-Web-Service”

<img src="../Assets/HomeyPark-Web-Service.png"/>

2. Seguido de ello, ingresamos a la plataforma de Render y crearemos un nuevo servicio web.

<img src="../Assets/plataforma-Render-create.png"/>

3. Configuraremos el nuevo servicio conectándolo con nuestro repositorio de GitHub e indicaremos trabajar con el lenguaje Docker, lo que nos permitirá usar contenedores con Java y Spring Boot.

<img src="../Assets/deploying-web-service.png"/>

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

| ID  | Title                                             | Title Task ID | Title | Description | Estimation (Hours) | Assigned To      | Status (To-do, In Process, To Review, Done, Cancelled) |
| --- | ------------------------------------------------- | ------------- | ----- | ----------- | ------------------ | ---------------- | ------------------------------------------------------ |
| US- | Integrar mapa de Google Maps                      | TASK-001      |       |             | 2                  | Sebastian Cachis | Done                                                   |
| US- | Búsqueda de estacionamiento por dirección         | TASK-002      |       |             | 2                  | Adriano Cruz     | Done                                                   |
| US- | Usar ubicación de dispositivo para buscar en mapa | TASK-003      |       |             | 1                  | Amner Llamo      | Done                                                   |
| US- | Ver espacios de estacionamientos cercanos         | TASK-004      |       |             | 2                  | Marcelo Garro    | Done                                                   |
| US- | Visualizar detalles de estacionamiento            | TASK-005      |       |             | 2                  | Lucio Yen        | Done                                                   |                                                  |
| US- | Visualizar el entorno del estacionamiento         | TASK-006      |       |             | 2                  | Adriano Cruz     | Done                                                   |
| US- | Registrar una cochera                             | TASK-007      |       |             | 3                  | Amner Llamo      | Done                                                   |
| US- | Visualizar cocheras registradas                   | TASK-008      |       |             | 2                  | Marcelo Garro    | Done                                                   |
| US- | Modificar cochera registrada                      | TASK-009      |       |             | 2                  | Lucio Yen        | Done                                                   |
| US- | Eliminar la cochera                               | TASK-010      |       |             | 1                  | Sebastian Cachis | Done                                                   |

### 5.2.2. Implemented Landing Page Evidence

Como resultado del primer sprint, se presenta el despliegue de la Landing Page

<img src="../Assets/landingpage1.png"/>
<img src="../Assets/landingpage2.png"/>
<img src="../Assets/landingpage3.png"/>
<img src="../Assets/landingpage4.png"/>
<img src="../Assets/landingpage5.png"/>

### 5.2.3. Implemented Frontend-Web Application Evidence

<img src="../Assets/implementedWebApp/login-web.png" width="400"/>

<img src="../Assets/implementedWebApp/signup-web.png" width="400"/>

<img src="../Assets/implementedWebApp/find-park-web.png" width="400"/>

<img src="../Assets/implementedWebApp/detail-parking-web.png" width="400"/>

<h3 id="524-acuerdo-de-servicio-saas">5.2.4. Acuerdo de Servicio - SaaS</h3>

El presente Acuerdo de Servicio (en adelante, el "Acuerdo") regula los términos y condiciones aplicables al uso de la plataforma HomeyPark, un servicio de software como servicio (SaaS) ofrecido por Netvia. Al acceder y utilizar los servicios provistos en la plataforma web y móvil de HomeyPark, el usuario acepta quedar legalmente vinculado por los términos de este Acuerdo.

1. Alcance del Servicio  
HomeyPark es una solución SaaS que permite a conductores (en adelante, "Usuarios de Parking") buscar, reservar y pagar por espacios de estacionamiento ofrecidos por terceros (en adelante, "Anfitriones") a través de una interfaz digital. Asimismo, permite a los Anfitriones registrar y gestionar la disponibilidad de sus cocheras privadas.

2. Derechos y Obligaciones del Usuario  
- Los usuarios se comprometen a hacer uso del sistema de manera diligente, lícita y conforme a los fines para los cuales fue diseñado.

- El usuario garantiza que la información proporcionada durante el registro y uso del servicio es veraz, completa y actualizada.

- Los usuarios deberán respetar las condiciones específicas de uso y las normas internas establecidas por los Anfitriones respecto a sus cocheras.

3. Responsabilidades del Proveedor (Netvia)  
- Netvia se compromete a mantener la disponibilidad del servicio, salvo casos de mantenimiento programado, fuerza mayor o fallas técnicas imprevistas.

- El proveedor no garantiza la disponibilidad de estacionamientos ni se responsabiliza por pérdidas, daños o robos ocurridos en el uso físico de los espacios.

- Se brindará soporte técnico razonable mediante canales digitales para incidencias con el uso de la plataforma.

4. Seguridad y Protección de Datos  
- Toda la información personal será tratada conforme a las normas vigentes en materia de protección de datos personales en el Perú.

- HomeyPark implementa mecanismos de autenticación, encriptación y validación de usuarios para preservar la integridad del sistema y de sus usuarios.

5. Limitación de Responsabilidad  
- HomeyPark actúa como un intermediario entre usuarios y anfitriones, por lo que no se hace responsable por el cumplimiento de los acuerdos entre ellos.

- El uso del servicio se realiza bajo riesgo propio del usuario. HomeyPark no asume responsabilidad por daños indirectos, incidentales o consecuentes.

6. Modificaciones al Servicio  
- Netvia se reserva el derecho de actualizar, modificar o suspender funcionalidades de HomeyPark previa notificación a los usuarios a través de los canales registrados.

7. Terminación  
- Cualquiera de las partes podrá dar por terminado el uso del servicio en cualquier momento. La terminación no exime del cumplimiento de obligaciones previamente contraídas.

8. Legislación Aplicable  
- Este Acuerdo se regirá por las leyes de la República del Perú. Ante cualquier controversia, las partes se someten a la jurisdicción de los tribunales del distrito judicial de Lima Metropolitana.

<img src="../Assets/Terminos-y-Condiciones.png"/>

Link: https://homey-park-experiments.web.app/terms-conditions

### 5.2.5. Implemented Native-Mobile Application Evidence

A continuación, se presentan las pantallas de nuestra aplicación móvil:

<img src="../Assets/mobile-maps.png" width="250"/>

<img src="../Assets/tu-garaje.png" width="250"/>

<img src="../Assets/vehiculos.png" width="250"/>

### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

Crear un usuario

<img src="../Assets/ImplementedRESTfulAPI/create-user.png" width="400"/>

Obtener todos los usuarios

<img src="../Assets/ImplementedRESTfulAPI/get-users.png" width="400"/>

<img src="../Assets/ImplementedRESTfulAPI/edit-user.png" width="400"/>

Crear un parking

<img src="../Assets/ImplementedRESTfulAPI/create-parking.png" width="400"/>

Obtener todos los parkings

<img src="../Assets/ImplementedRESTfulAPI/get-parkings.png" width="400"/>

<img src="../Assets/ImplementedRESTfulAPI/edit-parking.png" width="400"/>

Eliminar un parking

<img src="../Assets/ImplementedRESTfulAPI/delete-parking.png" width="400"/>

Obtener todas las reservaciones

<img src="../Assets/ImplementedRESTfulAPI/get-reservations.png" width="400"/>

<img src="../Assets/ImplementedRESTfulAPI/get-reservation.png" width="400"/>

### 5.2.7. RESTful API documentation

En esta sección se presentan los endpoints desarrollados en el presente sprint y se adjuntan capturas de
las acciones CRUD realizadas con OpenAPI. Dentro del alcance del sprint, se han desarrollado los
bounded contexts de User Management, Parking Management, Reservation Management, Schedule
Management, Location Management, y Vehicle Management.

<img src="../Assets/backend.png" width="550"/>

### 5.2.8. Team Collaboration Insights


| Nombre                          | Actividad                                                |
| ------------------------------- | -------------------------------------------------------- |
| Sebastian Cachis Gonzales       | Implementacion y desarrollo de Backend                   |
| Adriano Sebastian Cruz Palomino | Implementacion y desarrollo de la App Web y Landing Page |
| Amner Levi Llamo Sanchez        | Implementacion y desarrollo de Backend                   |
| Marcelo Fabian Garro Vega       | Implementacion y desarrollo de la App Web y Mobile App   |
| Lucio Heli Yen Cerna            | Implementacion y desarrollo de la App Web y Mobile App   |

Se realizaron los commits por una persona, pero eso desestima el aporte evidenciado entre los miebros de grupo.


## 5.3. Video About-the-Product

[Video del Producto](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/Ed-CJXEtQkhNgspiE93_ZogBiQ-p2sSwNMiWje5okRfPEw?e=9Rypp3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

<img src="../Assets/about-product.png"/>

<h1 id="capitulo-vi-product-verification--validation">Capítulo VI: Product Verification & Validation</h1>

## 6.1. Testing Suites & Validation
### 6.1.1. Core Entities Unit Tests

Los Core Entities Unit Tests son cruciales en el desarrollo de software para asegurar la calidad y el funcionamiento adecuado de las entidades centrales, lo que ayuda a prevenir errores y simplifica el mantenimiento del código.

User Service Test

<img src="../Assets/chapter6/Unit_User.png"/>

Role Service Test

<img src="../Assets/chapter6/Unit_Role.png"/>

Vehicle Service Test

<img src="../Assets/chapter6/Unit_Vehicle.png"/>

Location Service Test

<img src="../Assets/chapter6/Unit_Location.png"/>

Parking Service Test

<img src="../Assets/chapter6/Unit_Parking.png"/>

Schedule Service Test

<img src="../Assets/chapter6/Unit_Schedule.png"/>

Reservation Service Test

<img src="../Assets/chapter6/Unit_Reservation.png"/>

Profile Service Test

<img src="../Assets/chapter6/Unit_Profile.png"/>

### 6.1.2. Core Integration Tests

Las Core Integration Tests resultan esenciales para verificar la correcta interacción de los controladores con otros componentes del sistema, tales como servicios y bases de datos. Al poner a prueba escenarios de error, estas pruebas aseguran que el sistema gestione apropiadamente situaciones inesperadas y responda con los códigos de estado precisos. Esto se traduce en una mejor experiencia para el usuario, simplifica la depuración y contribuye a la creación de software robusto y de alta calidad.

Profile Controller Test

<img src="../Assets/chapter6/Integ_Profile.png"/>

Vehicle Controller Test

<img src="../Assets/chapter6/Integ_Vehicle.png"/>

Location Controller Test

<img src="../Assets/chapter6/Integ_Location.png"/>

Parking Controller Test

<img src="../Assets/chapter6/Integ_Parking.png"/>

Reservation Controller Test

<img src="../Assets/chapter6/Integ_Reservation.png"/>

Schedule Controller Test

<img src="../Assets/chapter6/Integ_Schedule.png"/>

### 6.1.3. Core Behavior-Driven Development

<img src="../Assets/chapter6/Behavior-DrivenAll.png"/>

<img src="../Assets/chapter6/Behavior-DrivenUS09.png"/>

<img src="../Assets/chapter6/Behavior-DrivenUS10.png"/>

### 6.1.4. Core System Tests

| US-09           | Registrarse | Given el usuario está en la página de registro, mWhen completa todos los campos requeridos y presiona “Registrarse”, Then se crea la cuenta y se redirige al login. Given el usuario ingresa un correo ya registrado, When intenta crear la cuenta, Then se muestra un mensaje de error.     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US09-Test.png"/>

| US-10           | Iniciar sesión | Given el usuario tiene una cuenta registrada, When ingresa credenciales válidas y presiona “Iniciar sesión”, Then accede a su dashboard. Given el usuario ingresa credenciales incorrectas, When intenta iniciar sesión, Then se muestra un mensaje de error y no se permite el acceso.     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US10-Test.png"/>

| US-12           | Buscar estacionamientos por dirección | Given el usuario ingresa una dirección válida, When presiona el botón de buscar, Then se muestran las cocheras disponibles en esa zona. Given el usuario ingresa una dirección inválida, When intenta buscar, Then se muestra un mensaje de error.     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US12-Test.png"/>

| US-13           | Visualizar estacionamientos en mapa Given hay estacionamientos disponibles | When el usuario accede al mapa, Then se muestran los marcadores en la ubicación correcta. Given no hay estacionamientos, When el usuario accede al mapa, Then se muestra un mensaje indicando "Sin resultados".     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US13-Test.png"/>

| US-15           | Ver detalle de cochera | Given el usuario selecciona un estacionamiento, When accede al detalle, Then ve información completa: ubicación, precio, horario, calificación. Given hay un error al cargar el detalle, When intenta acceder, Then se muestra un mensaje de error.     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US15-Test.png"/>

| US-18           | Registrar cochera | Given el anfitrión llena todos los campos requeridos, When presiona “Registrar cochera”, Then la cochera se guarda exitosamente. Given falta información, When intenta registrar, Then se muestra un mensaje de validación.     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US18-Test.png"/>

| US-19           | Ver cocheras registradas | Given el anfitrión tiene cocheras registradas, When accede a la sección de cocheras, Then se muestra el listado con sus detalles. Given el anfitrión no tiene cocheras, When accede a la sección, Then se muestra un mensaje indicando que no hay cocheras registradas.     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US19-Test.png"/>

| US-40           | Añadir vehículo | Given el usuario completa los campos del vehículo, When presiona “Guardar”, Then el vehículo se registra y aparece en la lista. Given falta un campo obligatorio, When intenta guardar, Then se muestra un mensaje de error.     |
| ----------------|----------------| ---------- |

<img src="../Assets/chapter6/US40-Test.png"/>

<h1 id="capitulo-vii-devops-practices">Capítulo VII: DevOps Practices</h1>

## 7.1. Continuous Integration
### 7.1.1. Tools and Practices
Para implementar la Integración Continua (CI), utilizamos GitHub Actions, una herramienta de automatización integrada en GitHub que permite construir, probar y verificar automáticamente cada push o pull request a la rama main

**Tools:**

- GitHub Actions: Es la herramienta principal para la automatización del pipeline de integración. Permite ejecutar tareas como compilación, pruebas y ejecución de workflows en cada evento del repositorio.

- Docker: Se emplea para contenerizar la aplicación backend, garantizando que el entorno de ejecución sea consistente desde el desarrollo hasta la producción.

- Render: Plataforma utilizada para desplegar automáticamente la aplicación Spring Boot en la nube mediante la opción webhooks.

**Practices:**

- Disparadores por rama (main): Cada commit a esta rama activa el pipeline.

- Compilación automática: El código es construido dentro del pipeline usando Maven.

- Pruebas automatizadas: Se ejecutan pruebas unitarias para validar la estabilidad del sistema.

- Contenerización: El backend se empaqueta en una imagen Docker preparada para producción.

- Despliegue automatizado (hook): Una vez validado el pipeline, se envía una solicitud al webhook de Render para iniciar el despliegue.

### 7.1.2. Build & Test Suite Pipeline Components

El pipeline de Integración Continua implementado en GitHub Actions se estructura en varias etapas que garantizan que cada cambio en el código sea correctamente validado antes de su despliegue. Estas etapas permiten detectar errores tempranamente, asegurar la calidad del software y mantener el proyecto en un estado siempre desplegable.

Componentes del Pipeline del Backend:

1. Checkout del código fuente:

    - El pipeline comienza con la acción de checkout, la cual descarga el contenido del repositorio para que las siguientes tareas puedan ejecutarse sobre la versión más reciente del código.

2. Configuración del entorno:

    - Se configura el entorno de ejecución instalando Java 17 (distribución Temurin) y preparando el entorno para compilar el proyecto.

3. Construcción del proyecto (build):

    - Se ejecuta mvn clean install, lo que permite compilar el código fuente y resolver todas las dependencias declaradas en el pom.xml.

    - En esta etapa también se generan los artefactos necesarios para el despliegue (por ejemplo, el .jar final).

4. Ejecución de pruebas:

    - Se ejecuta mvn test, lo que dispara las pruebas unitarias integradas en el proyecto.

    - Esta fase es crítica para verificar que los cambios realizados no introduzcan fallos en la lógica de negocio ni rompan funcionalidades existentes.

5. Notificación de despliegue (solo en rama main):

    - Si el commit pertenece a la rama main y todas las fases anteriores se completan exitosamente, se ejecuta un curl al webhook de Render (Render Deploy Hook) para iniciar automáticamente el despliegue.

## 7.2. Continuous Delivery
### 7.2.1. Tools and Practices

El objetivo de la Entrega Continua (Continuous Delivery) es garantizar que la aplicación esté siempre en un estado desplegable y validado, de modo que pueda ser publicada en producción de manera rápida y segura con una simple aprobación manual. Para lograrlo, se integraron herramientas que permiten automatizar todo el proceso hasta la etapa previa al despliegue final.

**Tools:**

- GitHub Actions: Es la herramienta central del pipeline, donde se automatizan las etapas de construcción, pruebas y despliegue condicional. Está configurado para detectar cambios en las ramas main y develop, permitiendo un flujo de validación constante.

- Docker: Utilizado para contenerizar la aplicación backend desarrollada en Spring Boot. Garantiza un entorno de ejecución coherente entre desarrollo, pruebas y producción, reduciendo riesgos por diferencias de configuración.

- Render Deploy Hook: Se configura un webhook de Render que permite disparar el despliegue desde GitHub Actions. En el caso de Entrega Continua, este webhook puede activarse manualmente o de forma controlada desde un entorno intermedio como develop.

**Practices:**

- Feature Branching: Cada nueva funcionalidad se desarrolla en una rama independiente. Luego de pasar pruebas y revisión de código, estas ramas se fusionan en develop (entorno de staging) o en main (producción).

- Despliegue Automatizado: En la rama main, el pipeline activa automáticamente el webhook de Render, lo que produce un despliegue inmediato al entorno de producción una vez que se validan los cambios. Esto asegura que toda versión fusionada en main pase directamente a producción sin intervención manual.

- Separación de entornos (.env): Se utilizaron archivos .env para separar claramente las configuraciones de desarrollo y producción, lo que facilita validaciones intermedias antes de desplegar versiones finales.

### 7.2.2. Stages Deployment Pipeline Components

**Integración Continua (CI):**  
Cada vez que se realiza un commit o pull request hacia la rama develop o main, GitHub Actions ejecuta automáticamente un pipeline que compila el proyecto con Maven, corre las pruebas y valida la construcción. Este paso garantiza que el código esté siempre en un estado desplegable.

**Validación previa al despliegue:**  
La validación se lleva a cabo mediante la ejecución del build y pruebas en un entorno aislado definido por el contenedor Docker. Esto permite asegurar que la aplicación sea coherente y funcional antes de cualquier despliegue.

**Despliegue automático a producción (main):**  
Cuando los cambios se fusionan a la rama main, el pipeline ejecuta un paso adicional que activa un Webhook de Render. Esto produce un despliegue inmediato de la nueva versión de la aplicación backend (Spring Boot), de forma completamente automatizada.

**Separación de entornos:**  
Se han definido configuraciones diferenciadas mediante variables de entorno en archivos .env, lo que permite manejar distintos entornos (por ejemplo, desarrollo y producción) sin modificar el código fuente.

**Monitoreo y observabilidad (integrado en Render):**  
Render proporciona monitoreo básico de la aplicación desplegada. Si el despliegue falla o hay errores de inicialización, estos quedan registrados automáticamente en el dashboard, permitiendo su revisión y solución.

## 7.3. Continuous Deployment
### 7.3.1. Tools and Practices

El objetivo de Continuous Deployment (CD) es que cada cambio validado automáticamente se despliegue directamente al entorno de producción sin intervención manual, siempre y cuando pase todas las pruebas previas definidas.

**Tools:**

- GitHub Actions: Utilizado como motor de automatización del pipeline CI/CD. Permite detectar cambios en la rama main y ejecutar una serie de pasos automatizados, entre ellos el despliegue continuo.

- Docker: Se utiliza para contenerizar la aplicación backend (Java Spring Boot). Esto garantiza que el entorno de ejecución en producción sea idéntico al entorno en el que se realizan las pruebas, reduciendo el riesgo de errores por diferencias de configuración.

- Render: Plataforma encargada de ejecutar el entorno de producción. Se configuró para que despliegue automáticamente la nueva versión de la aplicación cada vez que recibe una señal (deploy hook) desde GitHub Actions.

**Practices:**

- Despliegue basado en commits (commit-based deployment): Cada vez que se realiza un push a la rama main, GitHub Actions ejecuta el flujo completo: construcción, pruebas, y si todo es exitoso, activa el hook de despliegue en Render.

- Pipeline completamente automatizado: No hay intervención manual entre la validación del código y el despliegue final. Esto permite entregas más rápidas, frecuentes y confiables al entorno productivo.

- Rollback manual supervisado: Si bien el despliegue es automático, en caso de fallos se debe hacer un rollback manual en Render, seleccionando una versión anterior. Esto permite control frente a errores críticos sin automatizar retrocesos que puedan agravar fallas si no son correctamente evaluadas.

### 7.3.2. Production Deployment Pipeline Components

El pipeline de despliegue a producción está completamente automatizado y se ejecuta cada vez que se realiza un push en la rama main. El objetivo es que la nueva versión de la aplicación backend llegue al entorno productivo sin intervención manual, garantizando agilidad y confiabilidad.

**Componentes del pipeline del Backend:**

1. Activación automática por GitHub Actions: ante un push a main, se inicia el pipeline.

2. Compilación y pruebas: el código se construye con Maven y se ejecutan pruebas unitarias.

3. Despliegue con Render Deploy Hook: si todo es exitoso, GitHub Actions dispara un webhook que comunica a Render que debe desplegar la nueva versión.

4. Ejecución en contenedor: Render construye la imagen de la app y la ejecuta dentro de un contenedor Docker.

5. Monitoreo automático: Render monitorea la aplicación desplegada, reiniciando si detecta fallos.

# Conclusiones, Bibliografía y Anexos

- ## Conclusiones

  Definir la viabilidad y el enfoque del proyecto HomeyPark como solución a la escasez de estacionamientos urbanos.
  Comprender las necesidades de conductores y propietarios, los principales usuarios.
  Analizar la competencia para identificar oportunidades de diferenciación.
  Diseñar la arquitectura, UI y UX de la aplicación móvil y web.
  Adoptar la metodología Lean UX para un desarrollo iterativo y centrado en el usuario.
  Organizar el equipo y asignar roles para una gestión eficiente del proyecto.
  Identificar desafíos y riesgos iniciales para planificar estrategias de mitigación.
  En resumen, esta fase inicial establece una base sólida para el desarrollo de HomeyPark, demostrando la capacidad del equipo para abordar el problema, entender a los usuarios y diseñar una solución tecnológica viable.

  Durante esta segunda fase del proyecto, se consolidaron avances clave en la implementación del producto. Se refactorizaron los módulos del frontend y backend, siguiendo principios de arquitectura limpia y el patrón CQRS, lo cual permitió una mejor organización de la lógica de negocio y una mayor escalabilidad del sistema.
  Un aspecto importante fue la realización de pruebas a diferentes niveles: se implementaron pruebas unitarias, integrales y funcionales, cubriendo tanto los servicios del backend como los flujos principales del sistema, garantizando así la robustez del producto ante distintos escenarios de uso.
  Por otro lado, se configuraron pipelines de integración y despliegue continuo (CI/CD) mediante GitHub Actions y Render, lo cual aseguró la entrega automática y confiable de cada nueva versión del backend en producción.
  En síntesis, la segunda etapa del proyecto consolidó la transición de la propuesta conceptual a un producto funcional. Se completaron desarrollos clave del frontend, backend y landing page, se validaron funcionalidades mediante pruebas unitarias, integrales y funcionales, y se implementaron pipelines CI/CD que garantizan la calidad y continuidad del despliegue. Estos avances fortalecen la viabilidad técnica del sistema y preparan el terreno para una siguiente fase de validación con usuarios reales.

  

- ## Bibliografía

El Comercio. (2024). Congestión vehicular en Lima: La ciudad más lenta de América Latina con solo 14.5 km/h en hora punta. https://elcomercio.pe/lima/congestion-vehicular-en-lima-la-ciudad-mas-lenta-de-america-latina-con-solo-145-kmh-en-hora-punta-trafico-caos-vehicular-ultimas-noticia/

- ## Anexos

  Landing Page: https://homey-park-experiments.web.app/

  Web App: https://homey-park-experiments-app.web.app/login

  Organización en GitHub: https://github.com/orgs/NetviaOrganization/repositories

  Trello: https://trello.com/b/TghZeTMj/product-backlog-v2
