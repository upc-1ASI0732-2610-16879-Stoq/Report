<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="200">
</p>

<h2 align="center">Universidad Peruana de Ciencias Aplicadas</h2>
<h3 align="center">Ingenieri­a de Software</h3>

<p align="center">
    Periodo: 202610 <br>
    1ASI0732 | Diseño de Experimentos de Ingenierí­a de Software <br>
    NRC: 16879 <br>
    Docente: Alex Humberto Sanchez Ponce <br>
</p>

<hr>

<div align="center">
    <h5><strong>Informe del Trabajo Final</strong></h5>
    Startup: Stoq <br>
    Producto: StockWise <br>
</div>

<div align="center">
    <h5><strong>Integrantes</strong></h5>
    <p>
        U - Luciana Carolina Choquehuanca Nuñez <br>
        U202224619 - Ronald Joel Peralta Chipa <br>
        U202210973 - Sanchez Rios, Camila Cristina <br>
        U - Fabiola Del Rocio Saldaña Ayalan <br>
        U - Roy Linsh Fernandez Remon  <br>
    </p>
    <p><em>Abril, 2026</em></p>
</div>

<br>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe


| Version | Fecha | Autor | Descripcion de modificaciones |
|---|---|---|---|
| TP  |11/05/2026  | - Luciana Carolina Choquehuanca Nuñez <br> - Ronald Joel Peralta Chipa <br> - Sanchez Rios, Camila Cristina <br> - Fabiola Del Rocio Saldaña Ayalan <br> - Roy Linsh Fernandez Remon  <br> | Capitulo I: Introduccion <br> Capitulo II: Requirements Elicitation & Analysis <br> Capítulo III: Requirements Specification <br> Capítulo IV: Product Design <br> Capítulo V: Product Implementation<br> Capítulo VI: Product Verification & Validation <br> Capítulo VII: DevOps Practices     |

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights

## Enlace del repositorio del informe

https://github.com/upc-1ASI0732-2610-16879-Stoq/Report 

## Enlace de los repositorios de la organizacion

https://github.com/upc-1ASI0732-2610-16879-Stoq 

<div style="page-break-after: always;"></div>

# Contenido

## Tabla de contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Enlace del repositorio del informe](#enlace-del-repositorio-del-informe)
  - [Enlace de los repositorios de la organizacion](#enlace-de-los-repositorios-de-la-organizacion)
- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Part I: As-Is Software Project](#part-i-as-is-software-project)
- [Capitulo I: Introduccion](#capitulo-i-introduccion)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripcion de la Startup](#111-descripcion-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problematica](#121-antecedentes-y-problematica)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capitulo II: Requirements Elicitation \& Analysis](#capitulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Analisis competitivo](#211-analisis-competitivo)
    - [2.1.2. Estrategias y tacticas frente a competidores](#212-estrategias-y-tacticas-frente-a-competidores)
      - [Estrategias Generales de Posicionamiento](#estrategias-generales-de-posicionamiento)
      - [Estrategias Ofensivas frente a Competidores](#estrategias-ofensivas-frente-a-competidores)
      - [Estrategias Defensivas](#estrategias-defensivas)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseno de entrevistas](#221-diseno-de-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Analisis de entrevistas](#223-analisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capitulo III: Requirements Specification](#capitulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Product Backlog](#33-product-backlog)
  - [3.4. Impact Mapping](#34-impact-mapping)
- [Capitulo IV: Product Design](#capitulo-iv-product-design)
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
- [Capitulo V: Product Implementation](#capitulo-v-product-implementation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Product Implementation \& Deployment](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)
    - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
    - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.7. RESTful API documentation](#527-restful-api-documentation)
    - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
  - [5.3. Video About-the-Product](#53-video-about-the-product)
- [Part II: Verification, Validation \& Pipeline](#part-ii-verification-validation--pipeline)
- [Capitulo VI: Product Verification \& Validation](#capitulo-vi-product-verification--validation)
  - [6.1. Testing Suites \& Validation](#61-testing-suites--validation)
    - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
    - [6.1.2. Core Integration Tests](#612-core-integration-tests)
    - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
    - [6.1.4. Core System Tests](#614-core-system-tests)
  - [6.2. Static testing \& Verification](#62-static-testing--verification)
    - [6.2.1. Static Code Analysis](#621-static-code-analysis)
      - [6.2.1.1. Coding standard \& Code conventions](#6211-coding-standard--code-conventions)
      - [6.2.1.2. Code Quality \& Code Security](#6212-code-quality--code-security)
    - [6.2.2. Reviews](#622-reviews)
  - [6.3. Validation Interviews](#63-validation-interviews)
    - [6.3.1. Diseno de Entrevistas](#631-diseno-de-entrevistas)
    - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
    - [6.3.3. Evaluaciones segun heuristicas](#633-evaluaciones-segun-heuristicas)
  - [6.4. Auditoria de Experiencias de Usuario](#64-auditoria-de-experiencias-de-usuario)
    - [6.4.1. Auditoria realizada](#641-auditoria-realizada)
      - [6.4.1.1. Informacion del grupo auditado](#6411-informacion-del-grupo-auditado)
      - [6.4.1.2. Cronograma de auditoria realizada](#6412-cronograma-de-auditoria-realizada)
      - [6.4.1.3. Contenido de auditoria realizada](#6413-contenido-de-auditoria-realizada)
    - [6.4.2. Auditoria recibida](#642-auditoria-recibida)
      - [6.4.2.1. Informacion del grupo auditor](#6421-informacion-del-grupo-auditor)
      - [6.4.2.2. Cronograma de auditoria recibida](#6422-cronograma-de-auditoria-recibida)
      - [6.4.2.3. Contenido de auditoria recibida](#6423-contenido-de-auditoria-recibida)
      - [6.4.2.4. Resumen de modificaciones para subsanar hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)
- [Capitulo VII: DevOps Practices](#capitulo-vii-devops-practices)
  - [7.1. Continuous Integration](#71-continuous-integration)
    - [7.1.1. Tools and Practices](#711-tools-and-practices)
    - [7.1.2. Build \& Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
  - [7.2. Continuous Delivery](#72-continuous-delivery)
    - [7.2.1. Tools and Practices](#721-tools-and-practices)
    - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
  - [7.3. Continuous deployment](#73-continuous-deployment)
    - [7.3.1. Tools and Practices](#731-tools-and-practices)
    - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
  - [7.4. Continuous Monitoring](#74-continuous-monitoring)
    - [7.4.1. Tools and Practices](#741-tools-and-practices)
    - [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)
    - [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)
    - [7.4.4. Notification Pipeline Components](#744-notification-pipeline-components)
- [Part III: Experiment-Driven Lifecycle](#part-iii-experiment-driven-lifecycle)
- [Capitulo VIII: Experiment-Driven Development](#capitulo-viii-experiment-driven-development)
  - [8.1. Experiment Planning](#81-experiment-planning)
    - [8.1.1. As-Is Summary](#811-as-is-summary)
    - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
    - [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)
    - [8.1.4. Question Backlog](#814-question-backlog)
    - [8.1.5. Experiment Cards](#815-experiment-cards)
  - [8.2. Experiment Design](#82-experiment-design)
    - [8.2.1. Hypotheses](#821-hypotheses)
    - [8.2.2. Domain Business Metrics](#822-domain-business-metrics)
    - [8.2.3. Measures](#823-measures)
    - [8.2.4. Conditions](#824-conditions)
    - [8.2.5. Scale Calculations and Decisions](#825-scale-calculations-and-decisions)
    - [8.2.6. Methods Selection](#826-methods-selection)
    - [8.2.7. Data Analytics: Goals, KPIs and Metrics Selection](#827-data-analytics-goals-kpis-and-metrics-selection)
    - [8.2.8. Web and Mobile Tracking Plan](#828-web-and-mobile-tracking-plan)
  - [8.3. Experimentation](#83-experimentation)
    - [8.3.1. To-Be User Stories](#831-to-be-user-stories)
    - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)
    - [8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
      - [8.3.3.1. To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)
      - [8.3.3.2. Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)
      - [8.3.3.3. Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)
      - [8.3.3.4. Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)
      - [8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
      - [8.3.3.6. Team Collaboration Insights](#8336-team-collaboration-insights)
    - [8.3.4. To-Be Validation Interviews](#834-to-be-validation-interviews)
      - [8.3.4.1. Diseno de Entrevistas](#8341-diseno-de-entrevistas)
      - [8.3.4.2. Registro de Entrevistas](#8342-registro-de-entrevistas)
  - [8.4. Experiment Aftermath \& Analysis](#84-experiment-aftermath--analysis)
    - [8.4.1. Analysis and Interpretation of Results](#841-analysis-and-interpretation-of-results)
    - [8.4.2. Re-scored and Re-prioritized Question Backlog](#842-re-scored-and-re-prioritized-question-backlog)
  - [8.5. Continuous Learning](#85-continuous-learning)
    - [8.5.1. Shareback Session Artifacts: Learning Workflow](#851-shareback-session-artifacts-learning-workflow)
  - [8.6. To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)
    - [8.6.1. About-the-Product Intro Video](#861-about-the-product-intro-video)
- [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video App Validation](#video-app-validation)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografia](#bibliografia)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

# Student Outcome

ABET – EAC - Student Outcome 4

**Criterio:** La capacidad de reconocer responsabilidades éticas y profesionales en situaciones de ingeniería y hacer juicios informados, que deben considerar el impacto de las soluciones de ingeniería en contextos globales, económicos, ambientales y sociales.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 4.

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
  <tbody>
    <tr>
      <td><b>Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software</b></td>
      <td>
        <p><b>Peralta Chipa, Ronald Joel </b></p>
        <p><b>AV1:Demostré compromiso ético y profesional en el desarrollo del proyecto al participar en la configuración del entorno de desarrollo, la gestión del código fuente y la definición de estándares de codificación, promoviendo un trabajo colaborativo ordenado, mantenible y alineado con buenas prácticas de ingeniería de software. Además, aseguré que las configuraciones y convenciones aplicadas facilitaran la trazabilidad de cambios, la integración entre integrantes del equipo y la sostenibilidad del proyecto a largo plazo. </b> </p>
        <p><b>TB1:Apliqué criterios éticos y profesionales durante la implementación y despliegue del producto, contribuyendo en el documentacion y desarrollo de la landing page, aplicaciones web y mobile, APIs RESTful, pruebas de integración y procesos de despliegue continuo. Asimismo, participé en la documentación técnica y en la coordinación del equipo para asegurar la calidad, confiabilidad y disponibilidad de la solución desarrollada. </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Saldaña Ayalan, Fabiola Del Rocio</b></p>
        <p><b>AV1: </b> </p>
        <p><b>TB1: </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Sanchez Rios, Camila</b></p>
        <p><b>AV1: </b> </p>
        <p><b>TB1: </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Choquehuanca Nuñez, Luciana Carolina</b></p>
        <p><b>AV1: Reconocí responsabilidad ética y profesional en situaciones de ingeniería de software al sustentar la propuesta con evidencia obtenida de entrevistas, análisis de competidores y artefactos de needfinding. Esto permitió evitar decisiones basadas en suposiciones y orientar la solución hacia necesidades reales de los usuarios. </b> </p>
        <p><b>TB1: Reconocí responsabilidad ética y profesional en situaciones de ingeniería de software al aplicar BDD y prácticas de integración continua para comprobar el comportamiento esperado del sistema antes de su entrega. Esto ayudó a reducir errores, mejorar la trazabilidad del desarrollo y fortalecer la confiabilidad del producto. </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Fernandez Remon, Roy Linsh</b></p>
        <p><b>AV1: </b> </p>
        <p><b>TB1: </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
      </td>
      <td> Como equipo, se logró cumplir este criterio porque el desarrollo del proyecto se realizó con responsabilidad profesional, tomando decisiones basadas en evidencia obtenida durante el análisis de usuarios, entrevistas, evaluación del contexto y revisión de buenas prácticas de ingeniería de software. Esto permitió evitar que la solución se construyera únicamente sobre suposiciones, priorizando necesidades reales y problemas identificados en los segmentos objetivo. Además, se consideró la importancia de trabajar con trazabilidad, validación y calidad durante el proceso, fortaleciendo la confiabilidad del producto y el compromiso ético del equipo con una solución útil y bien sustentada. </td>
    </tr>
    <tr>
      <td><b>Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales</b></td>
      <td>
        <p><b>Peralta Chipa, Ronald Joel</b></p>
        <p><b>AV1: Participé en la configuración del entorno de desarrollo, la gestión del código fuente y la definición de estándares de codificación, promoviendo un flujo de trabajo ordenado, mantenible y alineado con buenas prácticas de ingeniería de software. Además, las decisiones técnicas adoptadas permitieron optimizar recursos, facilitar la colaboración entre integrantes del equipo y asegurar una mejor escalabilidad y sostenibilidad del proyecto. </b> </p>
        <p><b>TB1: Contribuí en la implementación y despliegue de aplicaciones web, mobile y APIs RESTful, priorizando la calidad, disponibilidad y confiabilidad de la solución desarrollada. Asimismo, participé en la documentación técnica, pruebas de integración y procesos de despliegue continuo para garantizar un funcionamiento estable y una experiencia consistente para los usuarios.También impulsé el uso de herramientas y prácticas de integración y despliegue continuo que ayudaron a reducir errores en producción, optimizar tiempos de entrega y mejorar la eficiencia del desarrollo. </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Saldaña Ayalan, Fabiola Del Rocio</b></p>
        <p><b>AV1: </b> </p>
        <p><b>TB1: </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Sanchez Rios, Camila</b></p>
        <p><b>AV1: </b> </p>
        <p><b>TB1: </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Choquehuanca Nuñez, Luciana Carolina</b></p>
        <p><b>AV1: Emití juicios informados considerando el impacto de la solución al analizar cómo las necesidades, frustraciones y tareas de los usuarios podían afectar la aceptación del producto. Esto permitió orientar la propuesta hacia una solución útil, viable y alineada al contexto social y económico del público objetivo. </b> </p>
        <p><b>TB1: Emití juicios informados considerando el impacto de la solución al seleccionar prácticas como BDD e integración continua para mejorar la calidad del software. Esto permitió reducir riesgos técnicos, evitar retrabajo y asegurar que el producto pueda mantenerse y evolucionar de forma más confiable. </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Fernandez Remon, Roy Linsh</b></p>
        <p><b>AV1: </b> </p>
        <p><b>TB1: </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
      </td>
      <td> Como equipo, se logró cumplir este criterio porque las decisiones del proyecto fueron evaluadas considerando el impacto que la solución puede generar en los usuarios, el negocio y el entorno. Se analizaron aspectos sociales relacionados con la utilidad y accesibilidad del producto, así como aspectos económicos vinculados a la reducción de errores, optimización de procesos y mejora de la eficiencia. También se consideró la sostenibilidad del desarrollo mediante prácticas que favorecen la mantenibilidad, escalabilidad y evolución del software, permitiendo que la propuesta aporte valor de forma responsable y alineada a necesidades reales. </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>

# Part I: As-Is Software Project

# Capitulo I: Introduccion

## 1.1. Startup Profile

### 1.1.1. Descripcion de la Startup

StockWise es una startup tecnológica especializada en el desarrollo de soluciones digitales para la gestión de inventarios. La compañía está dirigida principalmente a pequeñas y medianas empresas, startups en fase de crecimiento y bodegas especializadas que requieren un control preciso y eficiente de sus productos. Su propuesta de valor se centra en facilitar el registro de entradas y salidas de mercancía, la administración de múltiples usuarios, la configuración de alertas inteligentes, la generación de reportes detallados y la emisión de boletas de venta. Todo ello se ofrece a través de una interfaz intuitiva y accesible desde cualquier dispositivo, lo que permite a los negocios operar con mayor agilidad y sin limitaciones geográficas.

StockWise propone digitalizar y centralizar tanto el control del inventario como el registro de las ganancias de la tienda, brindando a los negocios la capacidad de tomar decisiones basadas en datos reales y optimizar su operación diaria .Para adaptarse a las distintas necesidades y niveles ofrece cuatro planes de funcionalidad avanzada. El Plan A – Geolocalización (GPS) incorpora funciones de ubicación para optimizar la trazabilidad y distribución de productos, posibilitando identificar su procedencia, registrar puntos de entrega y visualizar en un mapa interactivo todas las sedes o sucursales vinculadas a la tienda principal.

El Plan B – Localización y predicción inteligente combina dos capacidades clave. Por un lado, localiza mediante un mapa interactivo con integración de códigos QR para ubicar productos dentro del almacén de manera precisa. Por otro lado, predice mediante un sistema de reabastecimiento inteligente basado en patrones de ventas, que sugiere cuándo y cuánto stock reponer para evitar quiebres de inventario. Finalmente, el Plan C – Escaneo por lotes con cámara rápida ofrece una alternativa eficiente al código de barras tradicional: la aplicación toma una fotografía del producto o lote, y una API de visión —como Google ML Kit— devuelve etiquetas genéricas. El usuario confirma el producto exacto y la cantidad en un menú antes de registrarlo, pudiendo ver directamente su ubicación en el almacén virtual. Esta variedad de planes permite a StockWise atender desde negocios que recién comienzan su transformación digital hasta aquellos que requieren funcionalidades avanzadas de inteligencia y geolocalización.

<br>
<b>Misión: </b>Brindar a pequeñas y medianas empresas una solución de gestión de inventarios y pagos sencilla, accesible y eficiente, que les permita digitalizar su operación, reducir errores logísticos y tomar decisiones basadas en datos reales, apoyando así su crecimiento sostenible.

<br>
<b>Visión: </b>StockWise se enfoca en ser una aplicación preferida de los empresarios que buscan una gestión de inventarios, herramientas de alto valor con un modelo escalable, adaptable y centrado en el usuario.

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <th>
      <img src="assets/Chapter-1/fotoFabs.jpg" alt="Foto de perfil de " width="800px">
    </th>
    <td valign="top">
      <p><b> Saldaña Ayala, Fabiola del Rocio</b></p>
      <p>
        Soy estudiante de la carrera de Ingeniería de Software, actualmente me encuentro en el quinto ciclo. Me gusta viajar, aprender nuevos idiomas, leer y me interesa aprender más acerca de nuevas tecnologías.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/luciana.jpg" alt="Foto de perfil de Luciana" width="800px">
    </th>
    <td valign="top">
      <p><b>Luciana Carolina Choquehuanca Nuñez</b></p>
      <p>
       Soy estudiante de la carrera de Ingeniería de Software, actualmente cursando el séptimo ciclo, y tengo 20 años. Me considero una persona proactiva, con gran interés en participar en proyectos que impliquen adquirir nuevos conocimientos y seguir aprendiendo constantemente. Me gusta mantener el orden en mi trabajo, por lo que siempre busco entregar resultados que cumplan con los estándares requeridos. Además, disfruto aprender tanto de mis profesores como de mis compañeros, ya que considero que el aprendizaje colaborativo es clave para mi desarrollo profesional.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/fotocam.png" alt="Foto de perfil de Camila" width="800px">
    </th>
    <td valign="top">
      <p><b>Sánchez Ríos, Camila Cristina</b></p>
      <p>
       Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, actualmente me encuentro en el octavo ciclo. Poseo conocimientos sólidos en el desarrollo de aplicaciones web y de escritorio utilizando lenguajes como HTML, Java y C#, aplicando principios de diseño orientados al dominio (Domain Driven Design) y metodologías de desarrollo modernas. Además, tengo experiencia en diseño de interfaces y prototipado con Figma, lo que me permite aportar al equipo en la creación de soluciones visualmente coherentes, funcionales y centradas en la experiencia del usuario (UI/UX)..
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/ronald_perfil.jpg" alt="Foto de perfil de Kevin" width="800px">
    </th>
    <td valign="top">
      <p><b>Ronald Joel Peralta Chipa</b></p>
      <p>
        Soy estudiante de la carrera de Ingeniería de Software. Soy una persona comprometida con el orden, con un estilo de liderazgo democrático y una gran capacidad para escuchar y comprender. Disfruto crecer en equipo y aprender constantemente de los demás. Además, tengo interés en la cultura DevSecOps y la gestión de proyectos, lo que me permite tener un enfoque integral orientado a la seguridad, organización y mejora continua.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/.png" alt="Foto de perfil de Alejandro" width="800px">
    </th>
    <td valign="top">
      <p><b>...</b></p>
      <p>
        ...
      </p>
    </td>
  </tr>
    <tr>
  </tr>
</table>
<br>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problematica

- **Who (¿Quiénes?)**<br>
  Emprendedores, startups y pequeñas/medianas empresas con bodegas físicas que almacenan productos de distintos rubros como ropa, calzado, electrodomésticos, ferretería o alimentos.

- **What (¿Qué sucede?)**<br>
  A medida que sus negocios escalan, la gestión manual del inventario con hojas de cálculo o registros físicos se vuelve ineficiente, generando pérdidas, errores, quiebres de stock, sobrecompras y desorden logístico.

- **When (¿Cuándo ocurre?)**<br>
  En el momento en que el negocio empieza a crecer, aumentar su variedad de productos o abrir múltiples canales de venta, como tiendas físicas y plataformas online.

- **Where (¿Dónde ocurre?)**<br>
  En bodegas físicas propias, espacios alquilados o incluso en el hogar del emprendedor, especialmente en etapas tempranas o de expansión del negocio.

- **Why (¿Por qué es un problema?)**<br>
  La falta de un sistema centralizado y en tiempo real impide tomar decisiones estratégicas basadas en datos. Esto afecta la planificación de compras, genera pérdidas económicas, y daña la experiencia del cliente final.

- **How (¿Cómo lo solucionan hoy?)**<br>
  Mediante herramientas manuales como cuaderno o hojas de papel, inventarios escritos o software no especializado, que resultan limitados, propensos a errores y poco escalables.

- **How much (¿Cuánto cuesta no resolverlo?)**<br>
  El costo se traduce en pérdidas económicas significativas por productos no vendidos, errores de stock, tiempo invertido en tareas manuales y menor competitividad frente a negocios más organizados.

  Según un estudio realizado por GS1 Uruguay (2024), el porcentaje de productos no encontrados en góndolas alcanzó el 7.08 %, lo que representa un aumento del 74 % respecto al año anterior; este dato indica que por cada 100 productos auditados, 7 no estaban disponibles, evidenciando el impacto directo que una gestión ineficiente de inventarios puede tener en la disponibilidad, las ventas y la experiencia del cliente.

   <img src="assets/Chapter-1/Evolucion-del-Indice.png" alt="Lean Ux canvas" width="800px">


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El propósito de StockWise es proporcionar un sistema intuitiva y accesible para que empresas pequeñas y medianas, startups y bodegas especializadas puedan gestionar su inventario de forma eficiente, digitalizada y sin complicaciones técnicas ni altos costos.

Actualmente, pequeñas y medianas empresas, startups y bodegas especializadas dependen de métodos manuales como hojas de cálculo o registros en papel para gestionar su inventario. Esta forma de trabajo genera errores frecuentes en los registros, desactualización en tiempo real, pérdida de productos, sobrecompras innecesarias, falta de trazabilidad y una gestión logística ineficiente. Según NetSuite (2024), la precisión promedio del inventario en este tipo de negocios es solo del 83%, lo que impacta directamente en los costos operativos, la satisfacción del cliente y la rentabilidad general. A medida que estas empresas escalan, el desorden operativo se vuelve insostenible, reduciendo su capacidad de respuesta ante la demanda y su competitividad en el mercado.

Por lo tanto, surge la necesidad de diseñar una aplicación de gestión de inventarios que sea simple, funcional y adaptable, capaz de ofrecer control exacto del stock en tiempo real, reducción de errores humanos, mejora de la trazabilidad, alertas inteligentes y reportes analíticos que respalden la toma de decisiones. Frente a este escenario, la pregunta clave que guía el desarrollo de StockWise es: ¿cómo lograr que las bodegas y almacenes adopten un sistema automatizado que elimine los procesos manuales, reduzca errores y mejore la eficiencia operativa sin limitar el crecimiento del negocio?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creemos que los negocios emergentes necesitan digitalizar su gestión de inventarios a través de una solución móvil accesible.

2. Estas necesidades se pueden satisfacer con una aplicación móvil intuitiva, escalable y de bajo costo.

3. Nuestros clientes iniciales serán emprendedores, startups y pequeñas empresas con bodegas especializadas que operan de manera ágil.

4. El principal valor que busca el cliente es tener control y visibilidad total de su inventario en tiempo real, desde cualquier lugar.

5. El cliente obtendrá además alertas inteligentes, reportes automáticos, generación de boletas de venta y una experiencia de usuario móvil optimizada.

6. Adquiriremos la mayoría de nuestros clientes mediante publicidad en redes sociales dirigida, ASO (Optimización de la App Store) y asociaciones con comunidades de emprendedores.

7. Nuestro modelo de ingresos se basará en un esquema freemium dentro de la app, con upgrade a planes premium que desbloqueen funcionalidades avanzadas.

8. Nuestra competencia directa e indirecta incluye aplicaciones genéricas como hojas de cálculo móviles (Excel, Sheets), recordatorios básicos (Calendar) y ERPs complejos con apps móviles poco intuitivas.

9. Nuestra ventaja competitiva radicará en la simplicidad móvil, el enfoque específico en las pymes y la especialización en la gestión de inventarios sobre la marcha.

10. El mayor riesgo para el negocio es una baja tasa de adopción o la percepción de que la app es compleja o redundante frente a métodos manuales.

11. Mitigaremos este riesgo realizando pruebas de usabilidad móvil con usuarios reales, iteraciones rápidas basadas en feedback y una estrategia de onboarding dentro de la app que guíe al usuario paso a paso.

**User Assumptions:**</br>

- **¿Quién es el usuario?** Dueños de negocios, encargados de bodegas o logística en pymes/startups que necesitan gestionar inventarios de forma remota.
- **¿Qué problemas busca resolver nuestro producto?** La falta de control inmediato del stock, los errores por registros manuales en papel, los sobrecostos por pérdidas y las ventas fallidas debido a quiebres de stock inesperados.

- **¿Qué características son importantes?** Un registro rápido de productos (por voz, cámara o manual), un historial de movimientos accesible, alertas push personalizables, reportes visuales simplificados y la generación de boletas de venta directamente desde el dispositivo móvil.

- **¿Dónde encaja nuestro producto en su trabajo?** Se integra en su flujo de trabajo diario para la gestión del inventario en la bodega, en el punto de venta o durante las rondas de reposición, permitiendo decisiones informadas desde cualquier lugar.

- **¿Cuándo y cómo es usado nuestro producto?** Se utiliza de manera frecuente a lo largo del día, directamente desde sus teléfonos inteligentes, para registrar entradas/salidas al momento, consultar niveles de stock en tiempo real y generar comprobantes al instante.

- **¿Cómo debe verse y comportarse?** Debe tener una interfaz de usuario (UI) móvil limpia, simple y con navegación táctil intuitiva. Debe ser rápida, responsiva y funcionar sin conexión para casos de uso críticos.

**Feature Assumptions:**

Creemos que la aplicación móvil debe contar con una interfaz táctil intuitiva y diseños adaptados a dispositivos móviles que permitan a emprendedores y administradores adoptarla sin dificultad, minimizando la curva de aprendizaje.

Creemos que la app debe proporcionar notificaciones push y alertas personalizables (por stock bajo, fechas de vencimiento o pedidos de proveedores) que mantendrán a los usuarios informados de manera proactiva para prevenir errores operativos.

Creemos que el sistema debe incluir un módulo de reportes y dashboards visuales optimizados para móvil que permitan visualizar de un vistazo métricas clave (productos más vendidos, niveles de stock, tendencias), facilitando la toma de decisiones ágiles.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1:** Creemos que las alertas inteligentes push resolverán el problema de pérdidas económicas por quiebres de stock inesperados que enfrentan las pymes.  
Sabremos que es cierto  
Cuando al menos el 80% de los usuarios activos reporten una reducción del 25% en pérdidas por productos agotados y mejoren su planificación de reabastecimiento en encuestas trimestrales.

**Hipótesis 2:** Creemos que los reportes visuales móviles resolverán la falta de visibilidad sobre el rendimiento del inventario que impide a los emprendedores tomar decisiones estratégicas basadas en datos.  
Sabremos que es cierto  
Cuando el 70% de los usuarios utilicen los reportes semanalmente y reporten una mejora del 30% en sus decisiones de compra y gestión de stock.

**Hipótesis 3:** Creemos que el modelo freemium resolverá la barrera económica que impide a pequeños negocios acceder a herramientas profesionales de gestión de inventarios.  
Sabremos que es cierto  
Cuando logremos una adopción del 15% de usuarios gratuitos que conviertan a premium en 60 días, demostrando el valor percibido de la solución.

**Hipótesis 4:** Creemos que las alertas automatizadas por stock bajo resolverán el problema de sobrecostos operativos causados por el monitoreo manual del inventario.  
Sabremos que tenemos razón  
Cuando los usuarios reduzcan en 40% el tiempo dedicado a control manual de stock y eliminen el 90% de los quiebres de inventario críticos.

**Hipótesis 5:** Creemos que la generación digital de boletas de venta resolverá los errores de facturación y la desorganización financiera que afecta el flujo de caja de las pymes.  
Sabremos que tenemos razón  
Cuando los usuarios reporten una reducción del 50% en errores de facturación y mejoren en 35% la precisión de su control de ingresos diarios.

#### 1.2.2.4. Lean UX Canvas

 <img src="assets/Chapter-1/Lean-UX-Canvas.jpg" alt="Lean Ux canvas" width="800px">

_Imagen (N°1). Elaboración propia. Realizado en Canva_

<div style="page-break-after: always;"></div>

## 1.3. Segmentos objetivo

**Segmento 1: Dueños de bodegas**

**Aspectos demográficos:**

- Sexo: Femenino, Masculino
- Edades: 20 a 60 años
- Nivel socioeconómico: Clases B y C
- Aspectos geográficos:
- Nacionalidad: Peruana
- Zona geográfica: Urbana
- Departamento: Lima Metropolitana y otras ciudades con fuerte actividad comercial

**Aspectos psicográficos:**

- Dirigen negocios mayoristas o minoristas que gestionan inventario con productos variados en tallas, colores, fechas de vencimiento o dimensiones técnicas.
- Enfrentan desafíos como alta rotación de productos, pérdidas por desorden o falta de trazabilidad y decisiones poco informadas de compra.
- Buscan soluciones para profesionalizar su operación, evitar errores y mantener el control del stock.
- Valoran herramientas tecnológicas, que les permite ordenar su inventario, recibir alertas según el tipo de producto y tomar decisiones basadas en reportes visuales y detallados

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

**Aspectos demográficos:**

- Sexo: Masculino
- Edades: 22 a 45 años
- Nivel socioeconómico: Clases B y C
- Aspectos geográficos:
- Nacionalidad: Peruana
- Zona geográfica: Urbana
- Departamento: Lima Metropolitana y otras ciudades con fuerte actividad comercial

**Aspectos psicográficos:**

- Están en una etapa de crecimiento empresarial y buscan escalar su operación de manera eficiente.
- Tienen una mentalidad emprendedora y están dispuestos a invertir en herramientas que optimicen su logística.
- Reconocen que el desorden en su inventario afecta su productividad y atención al cliente.
- Valoran las soluciones tecnológicas que profesionalicen su negocio y les permitan competir a mayor escala.

Además de definir los segmentos por criterios psicográficos, hemos incorporado datos demográficos concretos para fundamentar mejor la selección de segmentos y mejorar las estrategias de mercado hacia los usuarios reales de nuestra app.

# Capitulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Analisis competitivo

<table border="1" cellspacing="0" cellpadding="6">
  <tr>
    <th colspan="5">
      <b>Objetivo del análisis:</b> Identificar el posicionamiento competitivo de StockWise en el mercado de plataformas digitales de gestión de inventarios para pymes, entendiendo sus ventajas diferenciales y oportunidades de mejora.
    </th>
  </tr>
  <tr>
    <th></th>
    <th>StockWise <img src="img/stock.jpeg"></th>
    <th>Zoho Inventory <img src="img/Zoho.png"></th>
    <th>Odoo Inventory <img src="img/odoo.png"></th>
    <th>TradeGecko <img src="img/trade.png"></th>
  </tr>
  <tr>
    <th colspan="5"><b>PERFIL</b></th>
  </tr>
  <tr>
    <td><b>Overview</b></td>
    <td>Solución digital integral de gestión de inventarios para pymes y emprendedores, accesible desde cualquier dispositivo</td>
    <td>Suite de negocio completa con módulo de inventario como parte de su ecosistema</td>
    <td>Software de gestión open-source con módulo de inventario personalizable</td>
    <td>Plataforma de gestión de inventario centrada en comercio electrónico y retail</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva</b></td>
    <td>Accesibilidad multidispositivo, interfaz intuitiva, planes funcionales específicos (GPS, QR, IA y escaneo por cámara) y enfoque en pymes</td>
    <td>Integración completa con ecosistema Zoho y terceros, robustez funcional</td>
    <td>Flexibilidad y personalización por ser open-source</td>
    <td>Fuerte integración con canales de e-commerce y plataformas de venta</td>
  </tr>
  <tr>
    <th colspan="5"><b>PERFIL DE MARKETING</b></th>
  </tr>
  <tr>
    <td><b>Mercado objetivo</b></td>
    <td>Pymes, emprendedores, startups y bodegas especializadas</td>
    <td>Medianas empresas y pymes en crecimiento</td>
    <td>Empresas de todos los tamaños que buscan personalización</td>
    <td>Negocios de e-commerce y retail</td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>Marketing digital, SEO, comunidades de emprendedores, modelo freemium</td>
    <td>Marketing B2B, fuerza de ventas, contenido educativo</td>
    <td>Comunidad open-source, partners de implementación</td>
    <td>Marketing especializado en e-commerce, ferias sectoriales</td>
  </tr>
  <tr>
    <th colspan="5"><b>PERFIL DE PRODUCTO</b></th>
  </tr>
  <tr>
    <td><b>Productos & Servicios</b></td>
    <td>Plataforma web responsive con gestión de inventario, alertas, reportes, boletas y planes avanzados con GPS, QR, predicción inteligente y escaneo por cámara</td>
    <td>Software web y móvil con inventario, órdenes de venta, envíos y facturación</td>
    <td>Suite modular web/móvil con inventario, manufactura, ventas y CRM</td>
    <td>Plataforma web/móvil con inventario, pedidos, logística y analítica</td>
  </tr>
  <tr>
    <td><b>Precios & Costos</b></td>
    <td>Modelo freemium con planes premium escalables por funcionalidad</td>
    <td>Planes por volumen de órdenes, desde gratis hasta enterprise</td>
    <td>Freemium modular, costos de implementación y personalización</td>
    <td>Planes premium por volumen de ventas y usuarios</td>
  </tr>
  <tr>
    <td><b>Canales de distribución</b></td>
    <td>Web responsive accesible desde laptop, tablet o celular</td>
    <td>Web y móvil (iOS/Android)</td>
    <td>Web y móvil (iOS/Android)</td>
    <td>Web y móvil (iOS/Android)</td>
  </tr>
  <tr>
    <th colspan="5"><b>Análisis SWOT</b></th>
  </tr>
  <tr>
    <td><b>Fortalezas</b></td>
    <td>- Accesibilidad desde cualquier dispositivo<br>- Interfaz intuitiva<br>- Funcionalidades innovadoras (GPS, QR, IA y escaneo por cámara)<br>- Enfoque específico en pymes</td>
    <td>- Ecosistema integrado<br>- Solución completa<br>- Reconocimiento de marca<br>- Escalabilidad</td>
    <td>- Flexibilidad y personalización<br>- Comunidad activa<br>- Modelo open-source<br>- Múltiples módulos integrados</td>
    <td>- Especialización en e-commerce<br>- Integraciones con plataformas de venta<br>- Analytics avanzado</td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>- Marca desconocida<br>- Ecosistema limitado vs competidores<br>- Recursos limitados vs grandes competidores</td>
    <td>- Curva de aprendizaje más pronunciada<br>- Puede ser complejo para pymes muy pequeñas<br>- Costo elevado para planes avanzados</td>
    <td>- Requiere personalización para funcionar óptimamente<br>- Soporte puede ser limitado en versión community</td>
    <td>- Enfoque muy específico en e-commerce<br>- Menos adaptable a otros modelos de negocio<br>- Precios elevados</td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>- Crecimiento del mercado de pymes digitales<br>- Tendencia hacia soluciones accesibles desde cualquier dispositivo<br>- Expansión a Latinoamérica<br>- Alianzas con comunidades de emprendedores</td>
    <td>- Expansión a nuevos mercados<br>- Desarrollo de más integraciones<br>- Consolidación como suite integral</td>
    <td>- Crecimiento de la comunidad de desarrolladores<br>- Expansión de funcionalidades multidispositivo<br>- Alianzas con implementadores</td>
    <td>- Crecimiento del e-commerce global<br>- Expansión a nuevos verticales de retail<br>- Desarrollo de analytics predictivo</td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>- Entrada de competidores establecidos al mercado de soluciones digitales para inventarios<br>- Commoditización de funcionalidades básicas<br>- Dificultad para captar usuarios frente a alternativas gratuitas</td>
    <td>- Competencia de soluciones más especializadas<br>- Precios más competitivos de alternativas<br>- Cambios en regulaciones internacionales</td>
    <td>- Fragmentación de la comunidad<br>- Calidad variable de implementaciones<br>- Competencia de soluciones SaaS más pulidas</td>
    <td>- Competencia de plataformas de e-commerce con módulos nativos<br>- Cambios en APIs de plataformas de venta<br>- Consolidación del mercado</td>
  </tr>
</table>


### 2.1.2. Estrategias y tacticas frente a competidores

#### Estrategias Generales de Posicionamiento

**1. Especialización en experiencia multidispositivo**

**Objetivo:** Diferenciarnos como una solución digital intuitiva, accesible desde cualquier dispositivo y adaptada a la operación diaria de las pymes.

**Tácticas:**

- Desarrollar funcionalidades avanzadas como GPS, ubicación por QR, predicción inteligente y escaneo por cámara.
- Optimizar la interfaz para laptop, tablet y celular, manteniendo una navegación clara y rápida.
- Garantizar funcionamiento offline para operaciones críticas.
- Implementar notificaciones contextuales y personalizables para alertas de stock, vencimientos y movimientos.

**2. Enfoque en usabilidad para PYMES**

**Objetivo:** Ofrecer la curva de aprendizaje más corta del mercado.

**Tácticas:**

- Crear un sistema de onboarding guiado dentro de la plataforma.
- Desarrollar tutoriales interactivos por funcionalidad.
- Implementar asistente inteligente para tareas complejas.
- Diseñar plantillas preconfiguradas por tipo de negocio.

#### Estrategias Ofensivas frente a Competidores

**1. Contra Zoho Inventory**

**Debilidad a explotar:** Complejidad para PYMES pequeñas.

**Tácticas:**

- Campañas comparativas destacando simplicidad frente a complejidad.
- Programa de migración asistida desde Zoho.
- Planes de precio más competitivos para el segmento pequeño-mediano.
- Funcionalidades “justo lo necesario” sin sobrecarga de opciones.

**2. Contra Odoo Inventory**

**Debilidad a explotar:** Requiere personalización e implementación.

**Tácticas:**

- Mensajería centrada en “funciona desde el día 1”.
- Precios transparentes sin costos ocultos de implementación.
- Casos de éxito de implementación en menos de 24 horas.
- Servicio de configuración inicial incluido en planes premium.

**3. Contra TradeGecko**

**Debilidad a explotar:** Enfoque limitado a e-commerce.

**Tácticas:**

- Posicionamiento como solución multicanal integral.
- Funcionalidades para negocios físicos y digitales.
- Campañas dirigidas a retail tradicional con interés en digitalizarse.
- Precios más accesibles para negocios mixtos.

#### Estrategias Defensivas

**1. Ante posible commoditización**

**Tácticas:**

- Desarrollo continuo de funcionalidades innovadoras como GPS, QR, predicción inteligente y escaneo por lotes.
- Programa de fidelización con beneficios escalables.
- Integraciones exclusivas con proveedores locales.
- Comunidad de usuarios para feedback y co-creación.

**2. Protección frente a entrada de grandes competidores**

**Tácticas:**

- Alianzas estratégicas con asociaciones de PYMES.
- Contratos a largo plazo con precios congelados.
- Desarrollo de especialización vertical por industria.
- Branding fuerte centrado en el enfoque PYME.


## 2.2. Entrevistas

### 2.2.1. Diseno de entrevistas

La finalidad de realizar entrevistas es obtener un alcance más completo sobre las experiencias, perspectivas y opiniones de los segmentos de mercado definidos. Nuestro objetivo es recolectar información valiosa que nos permita conocer mejor a nuestro público objetivo. Con estas entrevistas se tendrá una visión más clara de las necesidades y expectativas de nuestros usuarios.

### 2.2.1. Diseño de entrevistas

**Segmento #1: Bodegas especializadas por rubro**

**Preguntas principales**

1. ¿Podrías contarme cómo gestionas actualmente el inventario de tu bodega?
2. ¿Cuáles son los mayores retos que enfrentas al momento de organizar tus productos?
3. ¿Has tenido pérdidas o problemas por errores en el inventario? ¿Cómo los resolviste?
4. ¿Qué tan importante es para ti tener un control en tiempo real de tu stock?
5. ¿Utilizas algún sistema o herramienta digital? ¿Cuál y cómo te va con ella?

**Preguntas complementarias**

1. ¿Cómo te enteras cuando falta un producto o está a punto de vencerse?
2. ¿Qué tipo de reportes o información te gustaría tener sobre tu inventario?
3. ¿Qué dispositivos usas más en tu trabajo, como laptop, celular o tablet?
4. ¿Cómo crees que una plataforma digital podría ayudarte a mejorar tu operación?

**Segmento #2: Startups y emprendedores en expansión con necesidades logísticas**

**Preguntas principales**

1. ¿Cómo manejas actualmente el inventario de tu negocio?
2. ¿En qué momentos has sentido que el control del stock te limita o te hace perder tiempo?
3. ¿Cómo llevas el registro de entradas y salidas de productos?
4. ¿Qué te gustaría mejorar de tu proceso logístico actual?
5. ¿Has considerado usar alguna plataforma para gestionar tu inventario? ¿Por qué sí o por qué no?

**Preguntas complementarias**

1. ¿Qué herramientas digitales usas en tu negocio actualmente?
2. ¿Dónde almacenas tus productos?
3. ¿Qué tan seguido necesitas revisar el stock?
4. ¿Qué redes sociales o canales digitales usas para vender?


### 2.2.2. Registro de entrevistas

**Segmento 1: Bodegas especializadas por rubro**

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>1</td>
    <th>Nombre</th>
    <td>Marcelo Binda</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>26</td>
    <th>Distrito</th>
    <td>San Borja</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="img/Segmento 1 - Marcelo Binda.png.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
      En la entrevista, Marcelo Binda comenta que gestiona el inventario de su bodega de forma manual, usando un cuaderno y, en algunos casos, Excel. Señala que su principal dificultad es mantener el stock actualizado, controlar los productos próximos a vencer y saber qué mercadería debe reponer. También menciona que ha tenido pérdidas por productos vencidos o por pensar que tenía stock cuando ya se había agotado. Actualmente realiza conteos manuales y organiza los productos por fecha de vencimiento. Considera importante contar con una plataforma digital que le permita registrar entradas y salidas, recibir alertas de bajo stock o vencimiento y acceder a reportes sobre ventas, ganancias y movimientos del negocio.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://youtu.be/BDUiVJaxxLY">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">00:00 - 5:11</td>
  </tr>
</table>

<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>2</td>
    <th>Nombre</th>
    <td>Elvis Aranga Mesa</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>31</td>
    <th>Distrito</th>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="img/seg1-Elvis.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
      Elvis Aranga Meza, encargado de un mini market en Surco, compartió su experiencia utilizando la plataforma StockWise para la gestión de bodegas, destacando la facilidad de uso tanto para agregar productos como para navegar por las funciones principales, y calificando su utilidad con un 9 sobre 10. Consideró el diseño visual adecuado y sencillo, aunque sugirió optimizar la interfaz para pantallas pequeñas y otros dispositivos. Resaltó la utilidad de funciones como la visualización de fechas de vencimiento para evitar mermas y la organización de productos por lote, lo cual facilita la gestión de promociones. Sugirió incorporar reportes y estadísticas que permitan proyectar ventas y establecer metas. Finalmente, recomendó la plataforma a otros bodegueros, especialmente por su precio y utilidad, aunque señaló la importancia de brindar asistencia a usuarios con menos experiencia tecnológica.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g068_upc_edu_pe/EfICOj-xe6REtnBdqmvY7QsB40AX08yJQHh4VQP5k9XQUA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SCUtfJ">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">5:48 - 11:47</td>
  </tr>
</table>

<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>3</td>
    <th>Nombre</th>
    <td>Catalina Villa Guerra</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>28</td>
    <th>Distrito</th>
    <td>Breña</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="img/Interview-Catalina-Villa.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
      Catalina es una administradora de 28 años, encargada de gestionar una bodega familiar en el distrito de Breña. Ella menciona que las funciones que más le gustaron fueron la de alerta de productos próximos a vencer y la de control de stock, ya que considera que le ayudarían a evitar pérdidas por productos caducados y a mantener un mejor seguimiento de sus existencias. Sin embargo, percibe que estas funciones aún son básicas y podrían ofrecer opciones más avanzadas, como recordatorios personalizados o reportes automáticos. En cuanto a la interfaz, a Catalina le agradó el diseño sencillo y organizado, destacando que los botones son fáciles de identificar y las categorías están bien distribuidas. También comentó que la plataforma le resultaría útil para delegar mejor el control del inventario entre los miembros de su familia, facilitando así la administración general de la bodega.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g068_upc_edu_pe/EfICOj-xe6REtnBdqmvY7QsB40AX08yJQHh4VQP5k9XQUA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SCUtfJ">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">11:48 - 21:31</td>
  </tr>
</table>

<br>

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>4</td>
    <th>Nombre</th>
    <td>Juan Carlos Ramírez</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>49</td>
    <th>Distrito</th>
    <td>Surquillo</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="img/seg2-carlitos.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
      Juan Carlos Ramírez, emprendedor de 49 años, compartió su experiencia al utilizar la plataforma para la gestión de inventarios, destacando la facilidad de uso en el registro y control de productos, así como la organización del historial de movimientos. Consideró que estas herramientas podrían ayudarlo significativamente en su proceso de digitalización, ya que actualmente gestiona las entradas y salidas de manera manual mediante boletas y facturas físicas. En cuanto al diseño, señaló que la interfaz es clara y ordenada, aunque sugirió mejorar la personalización de reportes para adaptarlo mejor a las necesidades de su negocio. Finalmente, destacó que funcionalidades como la alerta de stock bajo y la gestión por lotes serían de gran apoyo para tener un control más preciso del inventario, y que la incorporación de estas herramientas digitales le permitiría automatizar procesos y liberar tiempo operativo en su gestión diaria.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g068_upc_edu_pe/EfICOj-xe6REtnBdqmvY7QsB40AX08yJQHh4VQP5k9XQUA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SCUtfJ">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">21:31 - 25:14</td>
  </tr>
</table>

<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>5</td>
    <th>Nombre</th>
    <td>Leonardo Gamboa</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>26</td>
    <th>Distrito</th>
    <td>San Miguel</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="img/Segmento2_Leo.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
      Leonardo G., emprendedor que maneja actualmente su inventario de manera manual con hojas de Excel y una libreta, probó la plataforma y comentó que le pareció intuitiva, útil y eficaz para el control de su negocio. Señaló que la sección de alertas de stock le resultó especialmente atractiva, ya que le permitiría evitar ventas de productos agotados y responder más rápido a la demanda constante que maneja. En cuanto al diseño, mencionó que la interfaz es clara y sencilla, con botones fáciles de identificar y una navegación fluida. Leonardo destacó que la herramienta podría ayudarlo a organizar mejor sus pedidos y actualizar su inventario sin esfuerzo, reemplazando las hojas manuales que utiliza actualmente. También valoró que la plataforma sea accesible y de fácil uso, algo clave para quienes aún no están acostumbrados a los sistemas digitales, pero buscan dar ese paso hacia la automatización de su negocio.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">25:14 - 29:36</td>
  </tr>
</table>

<br>

<table border="1">
  <tr>
    <th>Entrevista</th>
    <td>6</td>
    <th>Nombre</th>
    <td>Smith Morales Quispe</td>
  </tr>
  <tr>
    <th>Edad</th>
    <td>22</td>
    <th>Distrito</th>
    <td>Surco-Lima</td>
  </tr>
  <tr>
    <th>Captura de la entrevista: <img src="img/seg6.png" alt="Captura de la entrevista" width="200"></th>
    <td colspan="3">
      Un propietario de una ferretería comentó que la propuesta del proyecto le resultó muy interesante y especialmente útil para negocios que manejan una gran variedad de productos y herramientas. Durante la prueba, destacó la facilidad de uso de la plataforma y la organización del panel principal, sobre todo en el registro de productos y el control del inventario. Mencionó que actualmente administra todo su inventario utilizando Excel, por lo que considera que la plataforma podría simplificar y centralizar el control de stock, pedidos y movimientos en un solo sistema digital. También valoró la función de alertas de stock bajo y el historial de movimientos, ya que le permitirían tener un mejor control de sus existencias, evitar faltantes y reducir errores humanos en la actualización de datos. Respecto al diseño visual, señaló que la landing page le pareció moderna, atractiva y profesional, transmitiendo confianza desde el primer momento. Como sugerencia de mejora, indicó que las opciones de exportación de datos a Excel o PDF podrían ofrecer formatos más personalizables según las necesidades del negocio.
    </td>
  </tr>
  <tr>
    <th>URL de la grabación</th>
    <td colspan="3">
      <a href="https://drive.google.com/file/d/1CU0BlBX412Uo9P1yHLja47PFH4_acMIu/view?usp=sharing">
        Ver grabación
      </a>
    </td>
  </tr>
  <tr>
    <th>Timing</th>
    <td colspan="3">29:36 - 33:36</td>
  </tr>
</table>



### 2.2.3. Analisis de entrevistas

**Segmento 1: Bodegas especializadas por rubro**

Los entrevistados (Milagros, Elvis, Catalina) gestionan inventarios de forma manual, con cuadernos o Excel, lo que dificulta mantener la información precisa y actualizada. Cuando los datos llegan tarde, los productos se vencen sin que nadie lo note y se pierden ventas; además, los cambios de precio no quedan registrados. El problema no es falta de interés por la tecnología, sino que registrar toma tiempo mientras atienden a clientes. Para este grupo, la solución debe reducir pasos: registro rápido desde cualquier dispositivo, duplicado de fichas o carga de varios productos a la vez, una pantalla que muestre “lo que vence pronto” con avisos simples y la ubicación por estantería para encontrar productos sin perder minutos. Con ello deberían bajar las pérdidas, reducir el tiempo de registro y aumentar la confianza en el sistema.

Además de los aspectos técnicos, los entrevistados expresan frustración por el desorden y la pérdida de productos, pero también muestran disposición a adoptar soluciones simples que les permitan sentir mayor control y tranquilidad en la gestión diaria.

<table border="1" cellpadding="6" cellspacing="0" style="border-collapse:collapse; width:100%; font-family: Arial, sans-serif; font-size: 13px;">
  <thead style="background:#f2f2f2;">
    <tr>
      <th style="text-align:left;">Característica</th>
      <th style="text-align:center;">Frecuencia (n/3)</th>
      <th style="text-align:center;">Porcentaje</th>
      <th style="text-align:left;">Entrevistas relacionadas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Control manual del inventario (cuaderno/Excel)</td>
      <td style="text-align:center;">3/3</td>
      <td style="text-align:center;"><strong>100%</strong></td>
      <td>1(Milagros), 2(Elvis), 3(Catalina)</td>
    </tr>
    <tr>
      <td>Pérdidas por productos vencidos / falta de alertas</td>
      <td style="text-align:center;">3/3</td>
      <td style="text-align:center;"><strong>100%</strong></td>
      <td>1, 2, 3</td>
    </tr>
    <tr>
      <td>Precios desactualizados o cambios no registrados</td>
      <td style="text-align:center;">2/3</td>
      <td style="text-align:center;">67%</td>
      <td>1, 2</td>
    </tr>
    <tr>
      <td>Falta de tiempo por atención a clientes (se omiten registros)</td>
      <td style="text-align:center;">2/3</td>
      <td style="text-align:center;">67%</td>
      <td>1, 3</td>
    </tr>
    <tr>
      <td>Preferencia por solución simple y rápida (alertas de vencimiento, registro ágil)</td>
      <td style="text-align:center;">3/3</td>
      <td style="text-align:center;"><strong>100%</strong></td>
      <td>1, 2, 3</td>
    </tr>
    <tr>
      <td>Necesidad de ubicar productos por estantería/sector</td>
      <td style="text-align:center;">2/3</td>
      <td style="text-align:center;">67%</td>
      <td>1, 3</td>
    </tr>
  </tbody>
</table>

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

Los entrevistados Juan Carlos, Leonardo y Eduardo manejan inventarios mayormente manuales o semiautomatizados mediante Excel, cuadernos y sistemas en transición. El reto principal es coordinar más volumen y varios canales, como WhatsApp y redes sociales. Muchas salidas no quedan en un solo registro y preparar pedidos demora porque no se ubican los productos con precisión. Además, varias personas pueden cambiar precios o cantidades, pero no siempre queda claro quién realizó cada modificación. Necesitan orden sin un sistema pesado: roles y permisos con historial para saber quién hizo cada cambio, zonas y códigos QR para acelerar el picking, combos que resten insumos automáticamente y reportes simples por canal para ver qué se mueve más. Así pueden crecer sin perder control.

Pese a estas limitaciones operativas, en este grupo se percibe una actitud proactiva y de mejora continua: buscan herramientas que reflejen su crecimiento y les brinden seguridad al delegar tareas, evidenciando motivación por alcanzar mayor eficiencia y profesionalización.

<table border="1" cellpadding="6" cellspacing="0" style="border-collapse:collapse; width:100%; font-family: Arial, sans-serif; font-size: 13px;">
  <thead style="background:#f2f2f2;">
    <tr>
      <th style="text-align:left;">Característica</th>
      <th style="text-align:center;">Frecuencia (n/3)</th>
      <th style="text-align:center;">Porcentaje</th>
      <th style="text-align:left;">Entrevistas relacionadas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Gestión manual o semiautomatizada (Excel/cuadernos/sistema parcial)</td>
      <td style="text-align:center;">3/3</td>
      <td style="text-align:center;"><strong>100%</strong></td>
      <td>4(Juan Carlos), 5(Leonardo), 6(Eduardo)</td>
    </tr>
    <tr>
      <td>Ventas y coordinación por WhatsApp/redes sociales</td>
      <td style="text-align:center;">3/3</td>
      <td style="text-align:center;"><strong>100%</strong></td>
      <td>4, 5, 6</td>
    </tr>
    <tr>
      <td>Problemas para ubicar productos y preparar pedidos rápido</td>
      <td style="text-align:center;">2/3</td>
      <td style="text-align:center;">67%</td>
      <td>4, 5</td>
    </tr>
    <tr>
      <td>Falta de control centralizado / trazabilidad de cambios de precio y salidas</td>
      <td style="text-align:center;">2/3</td>
      <td style="text-align:center;">67%</td>
      <td>5, 6</td>
    </tr>
    <tr>
      <td>Interés en digitalizar para ganar eficiencia (sin sistemas pesados)</td>
      <td style="text-align:center;">3/3</td>
      <td style="text-align:center;"><strong>100%</strong></td>
      <td>4, 5, 6</td>
    </tr>
    <tr>
      <td>Necesidad de roles/permisos e historial de cambios</td>
      <td style="text-align:center;">2/3</td>
      <td style="text-align:center;">67%</td>
      <td>5, 6</td>
    </tr>
    <tr>
      <td>Reportes simples por canal y mayor visibilidad del stock</td>
      <td style="text-align:center;">2/3</td>
      <td style="text-align:center;">67%</td>
      <td>4, 5</td>
    </tr>
  </tbody>
</table>

Ambos segmentos comparten el manejo manual, los problemas con perecibles y la falta de visibilidad, por lo que requieren automatización. La diferencia es que las bodegas piden simplicidad inmediata, mientras que las startups necesitan además trazabilidad y velocidad. Por ello se propone empezar con un núcleo fácil de usar, basado en alertas de caducidad, registro rápido, ubicación clara y cambios de precio con historial. Luego, según la necesidad del negocio, se pueden activar funciones de escala como roles, QR, combos y reportes por canal. Si con esto bajan las mermas, disminuye el tiempo de registro y sube la exactitud del stock, la solución será escalable, intuitiva y eficiente, alineada con lo que se recogió en las entrevistas.


## 2.3. Needfinding

En el siguiente apartado, analizaremos a nuestros segmentos objetivos para identificar sus necesidades y, con base en ello, ofrecerles soluciones óptimas a sus problemas.


### 2.3.1. User Personas

**Segmento 1: Bodegas especializadas por rubro**

<img src="img/segmento1.png" alt="User persona - segmento 1" width="600"/>

_Imagen (N°2). Elaboración propia. Realizado en UXPressia_

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

<img src="img/segmento2.png" alt="User persona - segmento 2" width="600"/>

_Imagen (N°3). Elaboración propia. Realizado en UXPressia_

<br>
<br>
<br>

### 2.3.2. User Task Matrix

**Segmento 1: Bodegas especializadas por rubro**

| **Task Matrix**                                                   | **Frecuencia** | **Importancia** |
| ----------------------------------------------------------------- | -------------- | --------------- |
| Supervisar el stock y revisar niveles de inventario               | Alta           | Alta            |
| Realizar conteos físicos o auditorías manuales                    | Media          | Alta            |
| Negociar precios y coordinar con proveedores                      | Alta           | Alta            |
| Revisar reportes de ventas, rotación y márgenes                   | Media          | Alta            |
| Ingresar datos en Excel o sistemas básicos de control             | Media          | Media           |
| Delegar tareas a sus asistentes o empleados                       | Media          | Alta            |
| Atender clientes en tienda                                        | Alta           | Alta            |
| Coordinar pedidos con mayoristas o distribuidores                 | Alta           | Alta            |
| Capacitarse en nuevas herramientas digitales                      | Baja           | Media           |
| Resolver errores de inventario (_sobrestock_, productos vencidos) | Alta           | Alta            |
| Registrar productos rápidamente y confirmar datos                 | Media          | Alta            |
| Escanear lotes con cámara rápida y validar                        | Alta           | Alta            |
| Ubicar productos en almacén con QR/mapa                           | Alta           | Alta            |
| Revisar alertas de predicción de stock                            | Media          | Alta            |
| Visualizar sedes, entregas y procedencia en mapa (GPS)            | Baja           | Media           |

<br>

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

| **Task Matrix**                                                    | **Frecuencia** | **Importancia** |
| ------------------------------------------------------------------ | -------------- | --------------- |
| Supervisar la operación del negocio y el movimiento de productos   | Alta           | Alta            |
| Gestionar inventario de insumos y productos terminados             | Alta           | Alta            |
| Registrar entradas, salidas y devoluciones de productos            | Media          | Alta            |
| Coordinar pedidos con clientes o puntos de venta                   | Alta           | Alta            |
| Definir nuevos productos o adaptar la oferta según la demanda      | Alta           | Alta            |
| Publicar contenido y gestionar redes sociales                      | Alta           | Media           |
| Empaquetar productos y organizar despachos                         | Media          | Alta            |
| Analizar qué productos se venden más y qué insumos se usan más     | Media          | Alta            |
| Actualizar listas de precios, catálogos o colecciones              | Media          | Media           |
| Registrar ventas y organizar información contable o administrativa | Media          | Alta            |
| Aprender herramientas digitales para mejorar su operativa          | Media          | Alta            |
| Registrar insumos o productos desde cualquier dispositivo          | Alta           | Alta            |
| Registrar clientes y entregas con GPS                              | Alta           | Alta            |
| Analizar predicciones de ventas y reabastecimiento                 | Media          | Alta            |
| Escanear productos en lotes y asignar ubicación                    | Alta           | Alta            |
| Recibir alertas de sobrestock o quiebre                            | Media          | Alta            |

<br>

### 2.3.3. User Journey Mapping

**Segmento 1: Bodegas especializadas por rubro**

<img src="img/journeymap1.png" alt="User journey - segmento 1" width="600"/>

_Imagen (N°4). Elaboración propia. Realizado en UXPressia_

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

<img src="img/journeymap1.png" alt="User journey - segmento 2" width="600"/>

_Imagen (N°5). Elaboración propia. Realizado en UXPressia_

<br>
<br>

### 2.3.4. Empathy Mapping

**Segmento 1: Bodegas especializadas por rubro**

<img src="img/empathymap1.png" alt="Empathy map - segmento 1" width="800"/>

_Imagen (N°6). Elaboración propia. Realizado en UXPressia_

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

<img src="img/empathymap2.png" alt="Empathy map - segmento 2" width="800"/>

_Imagen (N°7). Elaboración propia. Realizado en UXPressia_

<br>
<br>


### 2.3.5. As-is Scenario Mapping

Esta sección describe cómo los usuarios realizan actualmente sus actividades antes de incorporar StockWise. El objetivo es identificar los puntos de fricción del proceso actual y evidenciar dónde la plataforma puede aportar mayor valor.

**Segmento 1: Bodegas especializadas por rubro**

| Etapa actual | Acción del usuario | Problema identificado | Oportunidad para StockWise |
| ------------ | ------------------ | --------------------- | -------------------------- |
| Registro de productos | Anota entradas y salidas en cuadernos, Excel o sistemas básicos. | La información puede quedar incompleta, duplicada o desactualizada. | Centralizar el registro de productos y movimientos desde una plataforma accesible desde cualquier dispositivo. |
| Control de stock | Revisa manualmente la cantidad disponible en estantes o almacén. | Se pierde tiempo y no siempre se detecta el stock bajo a tiempo. | Mostrar alertas de stock bajo y reportes simples para tomar decisiones rápidas. |
| Gestión de vencimientos | Revisa fechas de vencimiento producto por producto. | Pueden generarse pérdidas por productos vencidos o próximos a vencer. | Activar alertas de vencimiento y visualización por lotes. |
| Ubicación de productos | Busca productos por memoria o por ubicación física aproximada. | La atención puede volverse lenta y desordenada. | Usar ubicación por estantería, QR o mapa interno del almacén. |
| Revisión de resultados | Calcula ventas y ganancias de forma manual. | La toma de decisiones depende de información tardía o imprecisa. | Generar reportes de movimientos, ventas y ganancias. |

**Segmento 2: Startups y emprendedores en expansión con necesidades logísticas**

| Etapa actual | Acción del usuario | Problema identificado | Oportunidad para StockWise |
| ------------ | ------------------ | --------------------- | -------------------------- |
| Registro operativo | Usa Excel, libretas, Notion u otras herramientas separadas. | La información queda dispersa y es difícil mantener trazabilidad. | Unificar inventario, movimientos, reportes y usuarios en una sola plataforma. |
| Preparación de pedidos | Coordina ventas y entregas por WhatsApp, redes sociales o puntos de venta. | Se generan errores por falta de actualización del stock. | Registrar salidas, devoluciones y boletas de venta en tiempo real. |
| Delegación de tareas | Varias personas modifican productos, precios o cantidades. | No siempre se sabe quién realizó cada cambio. | Incorporar roles, permisos e historial de movimientos. |
| Reabastecimiento | Decide compras según experiencia o revisión manual. | Puede haber quiebres de stock o sobrestock. | Usar predicción inteligente basada en patrones de venta. |
| Análisis del negocio | Revisa datos de ventas de forma manual o incompleta. | Es difícil saber qué productos generan mayor rotación o ganancia. | Generar reportes detallados para apoyar decisiones basadas en datos reales. |

<br>


## 2.4. Ubiquitous Language

El siguiente glosario presenta los términos clave utilizados a lo largo del desarrollo del proyecto StockWise. Este lenguaje común busca asegurar que todos los miembros del equipo, tanto técnicos como no técnicos, compartan una comprensión unificada de los conceptos centrales del sistema, facilitando así la comunicación y el diseño colaborativo.

<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; width: 100%; font-family: Arial, sans-serif;">
  <thead style="background-color: #f2a654; color: white;">
    <tr>
      <th style="width: 30%;">Palabra</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Landing Page</td>
      <td>Página principal de presentación al llegar al sitio oficial de StockWise.</td>
    </tr>
    <tr>
      <td>Inventario</td>
      <td>Conjunto de productos almacenados en una bodega, almacén o negocio, con detalles como cantidad, ubicación y fecha de vencimiento.</td>
    </tr>
    <tr>
      <td>Producto</td>
      <td>Artículo registrado en la plataforma con nombre, descripción, stock mínimo, unidades, fecha de vencimiento y categoría.</td>
    </tr>
    <tr>
      <td>Stock</td>
      <td>Cantidad disponible de un producto específico en el inventario.</td>
    </tr>
    <tr>
      <td>Stock bajo</td>
      <td>Estado que indica que la cantidad de un producto está por debajo del mínimo definido por el usuario.</td>
    </tr>
    <tr>
      <td>Panel de Control</td>
      <td>Interfaz principal para visualizar métricas, movimientos y reportes del inventario.</td>
    </tr>
    <tr>
      <td>Movimiento de Inventario</td>
      <td>Registro de cambios en cantidades de productos por compras, ventas, pérdidas o ajustes.</td>
    </tr>
    <tr>
      <td>Reporte</td>
      <td>Documento visual o estadístico que resume información clave del inventario para la toma de decisiones.</td>
    </tr>
    <tr>
      <td>Bodega</td>
      <td>Negocio pequeño con venta de productos de primera necesidad, como alimentos, bebidas y artículos de consumo diario.</td>
    </tr>
    <tr>
      <td>Usuario Administrador</td>
      <td>Persona con acceso total que puede gestionar usuarios, configuraciones y datos de la plataforma.</td>
    </tr>
    <tr>
      <td>Emprendedor</td>
      <td>Usuario en etapa de crecimiento que busca profesionalizar la gestión de su negocio.</td>
    </tr>
    <tr>
      <td>Dueña de bodega</td>
      <td>Usuario con experiencia comercial que desea optimizar la gestión operativa con herramientas digitales.</td>
    </tr>
    <tr>
      <td>Versión Freemium</td>
      <td>Modelo que permite acceso gratuito a funciones básicas y pago por funciones premium.</td>
    </tr>
    <tr>
      <td>Onboarding</td>
      <td>Proceso de bienvenida y guía para enseñar a nuevos usuarios a usar la plataforma.</td>
    </tr>
    <tr>
      <td>MVP (Producto Mínimo Viable)</td>
      <td>Versión inicial con funciones mínimas para validar hipótesis clave con usuarios reales.</td>
    </tr>
    <tr>
      <td>Geolocalización</td>
      <td>Funcionalidad que permite registrar o visualizar ubicaciones relacionadas con sedes, entregas, procedencia de productos o puntos de distribución.</td>
    </tr>
    <tr>
      <td>Código QR</td>
      <td>Código escaneable utilizado para identificar productos, lotes o ubicaciones dentro del almacén.</td>
    </tr>
    <tr>
      <td>Predicción inteligente</td>
      <td>Funcionalidad que analiza patrones de ventas para sugerir cuándo y cuánto stock reponer.</td>
    </tr>
    <tr>
      <td>Escaneo por cámara</td>
      <td>Funcionalidad que permite registrar productos o lotes mediante una fotografía, apoyándose en una API de visión para reconocer etiquetas generales.</td>
    </tr>
    <tr>
      <td>Boleta de venta</td>
      <td>Documento emitido por la plataforma para registrar una venta realizada por el negocio.</td>
    </tr>
  </tbody>
</table>

# Capitulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Product Backlog

## 3.4. Impact Mapping

# Capitulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

### 4.1.3. Mobile Style Guidelines

#### 4.1.3.1. iOS Mobile Style Guidelines

#### 4.1.3.2. Android Mobile Style Guidelines

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

# Capitulo V: Product Implementation

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

### 5.2.2. Implemented Landing Page Evidence

### 5.2.3. Implemented Frontend-Web Application Evidence

### 5.2.4. Acuerdo de Servicio - SaaS

### 5.2.5. Implemented Native-Mobile Application Evidence

### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

### 5.2.7. RESTful API documentation

### 5.2.8. Team Collaboration Insights

## 5.3. Video About-the-Product

# Part II: Verification, Validation & Pipeline

# Capitulo VI: Product Verification & Validation

## 6.1. Testing Suites & Validation

### 6.1.1. Core Entities Unit Tests

### 6.1.2. Core Integration Tests

### 6.1.3. Core Behavior-Driven Development

### 6.1.4. Core System Tests

## 6.2. Static testing & Verification

### 6.2.1. Static Code Analysis

#### 6.2.1.1. Coding standard & Code conventions

#### 6.2.1.2. Code Quality & Code Security

### 6.2.2. Reviews

## 6.3. Validation Interviews

### 6.3.1. Diseno de Entrevistas

### 6.3.2. Registro de Entrevistas

### 6.3.3. Evaluaciones segun heuristicas

## 6.4. Auditoria de Experiencias de Usuario

### 6.4.1. Auditoria realizada

#### 6.4.1.1. Informacion del grupo auditado

#### 6.4.1.2. Cronograma de auditoria realizada

#### 6.4.1.3. Contenido de auditoria realizada

### 6.4.2. Auditoria recibida

#### 6.4.2.1. Informacion del grupo auditor

#### 6.4.2.2. Cronograma de auditoria recibida

#### 6.4.2.3. Contenido de auditoria recibida

#### 6.4.2.4. Resumen de modificaciones para subsanar hallazgos

# Capitulo VII: DevOps Practices

## 7.1. Continuous Integration

### 7.1.1. Tools and Practices

### 7.1.2. Build & Test Suite Pipeline Components

## 7.2. Continuous Delivery

### 7.2.1. Tools and Practices

### 7.2.2. Stages Deployment Pipeline Components

## 7.3. Continuous deployment

### 7.3.1. Tools and Practices

### 7.3.2. Production Deployment Pipeline Components

## 7.4. Continuous Monitoring

### 7.4.1. Tools and Practices

### 7.4.2. Monitoring Pipeline Components

### 7.4.3. Alerting Pipeline Components

### 7.4.4. Notification Pipeline Components

# Part III: Experiment-Driven Lifecycle

# Capitulo VIII: Experiment-Driven Development

## 8.1. Experiment Planning

### 8.1.1. As-Is Summary

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

### 8.1.3. Experiment-Ready Questions

### 8.1.4. Question Backlog

### 8.1.5. Experiment Cards

## 8.2. Experiment Design

### 8.2.1. Hypotheses

### 8.2.2. Domain Business Metrics

### 8.2.3. Measures

### 8.2.4. Conditions

### 8.2.5. Scale Calculations and Decisions

### 8.2.6. Methods Selection

### 8.2.7. Data Analytics: Goals, KPIs and Metrics Selection

### 8.2.8. Web and Mobile Tracking Plan

## 8.3. Experimentation

### 8.3.1. To-Be User Stories

### 8.3.2. To-Be Product Backlog

### 8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle

#### 8.3.3.1. To-Be Sprint Backlogs

#### 8.3.3.2. Implemented To-Be Landing Page Evidence

#### 8.3.3.3. Implemented To-Be Frontend-Web Application Evidence

#### 8.3.3.4. Implemented To-Be Native-Mobile Application Evidence

#### 8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence

#### 8.3.3.6. Team Collaboration Insights

### 8.3.4. To-Be Validation Interviews

#### 8.3.4.1. Diseno de Entrevistas

#### 8.3.4.2. Registro de Entrevistas

## 8.4. Experiment Aftermath & Analysis

### 8.4.1. Analysis and Interpretation of Results

### 8.4.2. Re-scored and Re-prioritized Question Backlog

## 8.5. Continuous Learning

### 8.5.1. Shareback Session Artifacts: Learning Workflow

## 8.6. To-Be Software Platform Pre-launch

### 8.6.1. About-the-Product Intro Video

# Conclusiones

# Conclusiones y recomendaciones

# Video App Validation

# Video About-the-Team

# Bibliografia

# Anexos
