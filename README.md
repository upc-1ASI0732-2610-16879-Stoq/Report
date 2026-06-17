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
        U202319431 - Luciana Carolina Choquehuanca Nuñez <br>
        U202224619 - Ronald Joel Peralta Chipa <br>
        U202210973 - Sanchez Rios, Camila Cristina <br>
        U202313773 - Fabiola Del Rocio Saldaña Ayalan <br>
        U20221B778 - Roy Linsh Fernandez Remon  <br>
    </p>
    <p><em>Mayo, 2026</em></p>
</div>

<br>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe


| Version | Fecha | Autor | Descripcion de modificaciones |
|---|---|---|---|
| TP  |11/05/2026  | - Luciana Carolina Choquehuanca Nuñez <br> - Ronald Joel Peralta Chipa <br> - Sanchez Rios, Camila Cristina <br> - Fabiola Del Rocio Saldaña Ayalan <br> - Roy Linsh Fernandez Remon  <br> | Capitulo I: Introduccion <br> Capitulo II: Requirements Elicitation & Analysis <br> Capítulo III: Requirements Specification <br> Capítulo IV: Product Design <br> Capítulo V: Product Implementation<br> Capítulo VI: Product Verification & Validation <br> Capítulo VII: DevOps Practices     |
| TB2  |15/06/2026  | - Luciana Carolina Choquehuanca Nuñez <br> - Ronald Joel Peralta Chipa <br> - Sanchez Rios, Camila Cristina <br> - Fabiola Del Rocio Saldaña Ayalan <br> - Roy Linsh Fernandez Remon  <br> | Capítulo VI: Product Verification & Validation <br> Capítulo VII: DevOps Practices <br> Capítulo VIII: Experiment-Driven    |

<div style="page-break-after: always;"></div>


# Contenido

## Tabla de contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
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
      - [Organization Systems](#organization-systems)
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
    - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
    - [User Goal: “Crear cuenta e ingresar a la aplicación”](#user-goal-crear-cuenta-e-ingresar-a-la-aplicación)
    - [User Goal: “Crear un nuevo rol para el personal”](#user-goal-crear-un-nuevo-rol-para-el-personal)
    - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
    - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
    - [User Goal: “Registrar salida de productos (venta/consumo/merma)”](#user-goal-registrar-salida-de-productos-ventaconsumomerma)
    - [User Goal: “Gestionar inventario (ingresar reposición y crear producto)”](#user-goal-gestionar-inventario-ingresar-reposición-y-crear-producto)
  - [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
  - [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
    - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
  - [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams](#491-class-diagrams)
    - [4.9.2. Class Dictionary](#492-class-dictionary)
    - [IAM Context](#iam-context)
    - [Product Management Context](#product-management-context)
    - [Inventory Context](#inventory-context)
    - [Sales Context](#sales-context)
    - [Alert Stock Context](#alert-stock-context)
    - [Reports Context](#reports-context)
  - [4.10. Database Design](#410-database-design)
    - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)
- [Capitulo V: Product Implementation](#capitulo-v-product-implementation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
      - [Software Deployment](#software-deployment)
    - [5.1.2. Source Code Management](#512-source-code-management)
      - [GitFlow](#gitflow)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
      - [Mobile Development (UI \& Logic)](#mobile-development-ui--logic)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
      - [Requisitos de Estructura](#requisitos-de-estructura)
      - [Pasos para el Despliegue](#pasos-para-el-despliegue)
  - [5.2. Product Implementation \& Deployment](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [Sprint 1: Núcleo Móvil, APIs Base y Landing Page](#sprint-1-núcleo-móvil-apis-base-y-landing-page)
    - [Sprint 2: Funcionalidades Avanzadas y Alertas](#sprint-2-funcionalidades-avanzadas-y-alertas)
    - [Sprint 3: Integración de Hardware, Geolocalización y Cierre](#sprint-3-integración-de-hardware-geolocalización-y-cierre)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)
      - [1. Definiciones](#1-definiciones)
      - [2. Objeto del Acuerdo](#2-objeto-del-acuerdo)
      - [3. Registro y Acceso](#3-registro-y-acceso)
      - [4. Tarifas y Planes](#4-tarifas-y-planes)
      - [5. Propiedad Intelectual](#5-propiedad-intelectual)
      - [6. Uso Aceptable](#6-uso-aceptable)
      - [7. Protección de Datos y Privacidad](#7-protección-de-datos-y-privacidad)
      - [8. Disponibilidad del Servicio](#8-disponibilidad-del-servicio)
      - [9. Limitación de Responsabilidad](#9-limitación-de-responsabilidad)
      - [10. Modificaciones del Acuerdo](#10-modificaciones-del-acuerdo)
    - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
    - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.7. RESTful API documentation](#527-restful-api-documentation)
      - [Authentication](#authentication)
      - [Products](#products)
      - [Combos](#combos)
      - [Tags](#tags)
      - [Units](#units)
      - [Sales](#sales)
      - [Inventory](#inventory)
      - [StockAlert](#stockalert)
      - [Report](#report)
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
      - [6.2.1.1. .Coding standard \& Code conventions](#6211-coding-standard--code-conventions)
      - [6.2.1.2. Code Quality \& Code Security.](#6212-code-quality--code-security)
    - [6.2.2. Reviews](#622-reviews)
  - [6.2.2. Reviews](#622-reviews-1)
  - [6.3. Validation Interviews.](#63-validation-interviews)
    - [6.3.1. Diseño de Entrevistas.](#631-diseño-de-entrevistas)
    - [6.3.2. Registro de Entrevistas.](#632-registro-de-entrevistas)
    - [6.3.3. Evaluaciones segun heuristicas.](#633-evaluaciones-segun-heuristicas)
  - [6.4. Auditoria de Experiencias de Usuario.](#64-auditoria-de-experiencias-de-usuario)
    - [6.4.1. Auditoria realizada.](#641-auditoria-realizada)
      - [6.4.1.1. Información del grupo auditado.](#6411-información-del-grupo-auditado)
      - [6.4.1.2. Cronograma de auditoría realizada](#6412-cronograma-de-auditoría-realizada)
      - [6.4.1.3. Contenido de la auditoría realizada](#6413-contenido-de-la-auditoría-realizada)
    - [6.4.2. Auditoria recibida.](#642-auditoria-recibida)
      - [6.4.2.1. Información del grupo auditor.](#6421-información-del-grupo-auditor)
      - [6.4.2.2. Cronograma de auditoría recibida.](#6422-cronograma-de-auditoría-recibida)
      - [6.4.2.3. Contenido de auditoría recibida.](#6423-contenido-de-auditoría-recibida)
      - [6.4.2.4. Resumen de modificaciones para subsanar hallazgos.](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)
- [Capitulo VII: DevOps Practices](#capitulo-vii-devops-practices)
  - [7.1. Continuous Integration](#71-continuous-integration)
    - [7.1.1. Tools and Practices](#711-tools-and-practices)
    - [7.1.2. Build \& Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
  - [7.2. Continuous Delivery](#72-continuous-delivery)
    - [7.2.1. Tools and Practices](#721-tools-and-practices)
    - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
  - [7.3. Continuous deployment](#73-continuous-deployment)
    - [7.3.1. Tools and Practices](#731-tools-and-practices)
      - [Recomendaciones](#recomendaciones)
      - [Consideraciones adicionales](#consideraciones-adicionales)
    - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
- [Conclusiones](#conclusiones)
- [Recomendaciones](#recomendaciones-1)
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
        <p><b>AV1:</b> Demostré compromiso ético y profesional en el desarrollo del proyecto al participar en la configuración del entorno de desarrollo, la gestión del código fuente y la definición de estándares de codificación, promoviendo un trabajo colaborativo ordenado, mantenible y alineado con buenas prácticas de ingeniería de software. Además, aseguré que las configuraciones y convenciones aplicadas facilitaran la trazabilidad de cambios, la integración entre integrantes del equipo y la sostenibilidad del proyecto a largo plazo.  </p>
        <p><b>TB1:</b> Apliqué criterios éticos y profesionales durante la implementación y despliegue del producto, contribuyendo en el documentacion y desarrollo de la landing page, aplicaciones web y mobile, APIs RESTful, pruebas de integración y procesos de despliegue continuo. Asimismo, participé en la documentación técnica y en la coordinación del equipo para asegurar la calidad, confiabilidad y disponibilidad de la solución desarrollada. </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Saldaña Ayalan, Fabiola Del Rocio</b></p>
        <p><b>AV1: </b> Demostré responsabilidad profesional al liderar el diseño del producto (Capítulo IV), aplicando estándares como Domain-Driven Design (DDD) y el modelo C4 para la arquitectura de StockWise. Me aseguré de documentar de manera clara y simplificada la alta disponibilidad, el aislamiento de IA, garantizando que el diseño arquitectónico, de bases de datos y de interfaces (UX/UI) responda fielmente a las necesidades del negocio y permita un mantenimiento ordenado y sostenible por parte de todo el equipo.</p>
        <p><b>TB1: </b> Reconocí mi responsabilidad ética y profesional al implementar los Core System Tests y configurar el Build & Test Suite Pipeline. Al automatizar la validación del código y estructurar las pruebas de los flujos críticos (como las ventas y el descuento de inventario secuencial), garantizo la integridad de los datos de los usuarios, evitando que despliegues con errores técnicos lleguen a producción y afecten las operaciones diarias de las empresas que confían en nuestra plataforma.</p>
        <p><b>AV2: </b> Para esta entrega, demostr'e mi responsabilidad ética y profesional al desarrollar Static Code Analysis & Monitoreo ya que garanticé que el código entregado fuera limpio y seguro para evitar fallas en producción. También contribuí con las hipótesis y las métricas del negocio para validar el comportamiento del software bajo el estándar que el cliente espera y medir el impacto real.</p>
        <p><b>TB2: </b> </p>
        <p><b>Sanchez Rios, Camila</b></p>
        <p><b>AV1:</b>  Reconozco mi responsabilidad ética y profesional de garantizar que la gestión digital de inventarios no excluya a quienes tienen poca experiencia tecnológica. Por eso, he priorizado una interfaz intuitiva, accesible desde cualquier dispositivo y con entrada por voz, asegurando que emprendedores y bodegueros puedan usar la solución sin barreras.  </p>
        <p><b>TB1:</b>  Reconozco que protejer la información comercial de los usuarios mediante prácticas seguras de manejo de datos, respetando la confidencialidad de sus registros de stock, ventas y ganancias.  </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Choquehuanca Nuñez, Luciana Carolina</b></p>
        <p><b>AV1:</b> Reconocí responsabilidad ética y profesional en situaciones de ingeniería de software al sustentar la propuesta con evidencia obtenida de entrevistas, análisis de competidores y artefactos de needfinding. Esto permitió evitar decisiones basadas en suposiciones y orientar la solución hacia necesidades reales de los usuarios. </p>
        <p><b>TB1:</b> Reconocí responsabilidad ética y profesional en situaciones de ingeniería de software al aplicar BDD y prácticas de integración continua para comprobar el comportamiento esperado del sistema antes de su entrega. Esto ayudó a reducir errores, mejorar la trazabilidad del desarrollo y fortalecer la confiabilidad del producto.  </p>
        <p><b>AV2: </b> Para este avance, reconozco la responsabilidad ética y profesional en el desarrollo de soluciones de ingeniería de software al diseñar StockWise, asegurando que la gestión de inventarios se base en principios de transparencia, trazabilidad y reducción de errores operativos. Asimismo, la definición de métricas, KPIs y experimentos garantiza un enfoque estructurado y responsable en la toma de decisiones técnicas, evitando suposiciones sin validación y promoviendo un desarrollo basado en evidencia y buenas prácticas de ingeniería. </p>
        <p><b>TB2: </b> </p>
        <p><b>Fernandez Remon, Roy Linsh</b></p>
        <p><b>AV1: </b> Al elaborar la TP1, al trabajar en el capítulo III, ayudar en parte del Core System Test y Production Deployment Pipeline Components, pude indicar cómo las historias de usuario, entre ellas las más relevantes, influren directamente las decisiones de la arquitectura del sistema y en el desarrollo de tests de manera correcta y aplicada en el proyecto.</p>
        <p><b>TB1: </b> En este proceso, fundamenté la relación directa entre las historias de usuario de mayor relevancia y la configuración de la arquitectura, garantizando una metodología de testing coherente y aplicada a las necesidades del software.</p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
      </td>
      <td> Como equipo, se logró cumplir este criterio porque el desarrollo del proyecto se realizó con responsabilidad profesional, tomando decisiones basadas en evidencia obtenida durante el análisis de usuarios, entrevistas, evaluación del contexto y revisión de buenas prácticas de ingeniería de software. Esto permitió evitar que la solución se construyera únicamente sobre suposiciones, priorizando necesidades reales y problemas identificados en los segmentos objetivo. Además, se consideró la importancia de trabajar con trazabilidad, validación y calidad durante el proceso, fortaleciendo la confiabilidad del producto y el compromiso ético del equipo con una solución útil y bien sustentada. </td>
    </tr>
    <tr>
      <td><b>Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales</b></td>
      <td>
        <p><b>Peralta Chipa, Ronald Joel</b></p>
        <p><b>AV1:</b> Participé en la configuración del entorno de desarrollo, la gestión del código fuente y la definición de estándares de codificación, promoviendo un flujo de trabajo ordenado, mantenible y alineado con buenas prácticas de ingeniería de software. Además, las decisiones técnicas adoptadas permitieron optimizar recursos, facilitar la colaboración entre integrantes del equipo y asegurar una mejor escalabilidad y sostenibilidad del proyecto. </p>
        <p><b>TB1:</b> Contribuí en la implementación y despliegue de aplicaciones web, mobile y APIs RESTful, priorizando la calidad, disponibilidad y confiabilidad de la solución desarrollada. Asimismo, participé en la documentación técnica, pruebas de integración y procesos de despliegue continuo para garantizar un funcionamiento estable y una experiencia consistente para los usuarios.También impulsé el uso de herramientas y prácticas de integración y despliegue continuo que ayudaron a reducir errores en producción, optimizar tiempos de entrega y mejorar la eficiencia del desarrollo. </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Saldaña Ayalan, Fabiola Del Rocio</b></p>
        <p><b>AV1: </b>Emití juicios informados durante el diseño arquitectónico y de producto de StockWise, evaluando directamente el impacto económico y operativo en nuestros usuarios finales. Diseñé una arquitectura enfocada en la alta disponibilidad y el procesamiento Edge para que los negocios no detengan sus ventas por falta de conectividad, protegiendo su competitividad y reduciendo drásticamente las pérdidas económicas asociadas a las caídas del sistema o desorganización de la información. </p>
        <p><b>TB1: </b>Consideré el impacto tecnológico y económico al implementar los componentes del pipeline de Integración Continua (CI) y las pruebas del sistema central. Esta decisión técnica optimiza los recursos tecnológicos del equipo, acelera la entrega de valor de forma segura y, al asegurar matemáticamente que los cálculos de inventario sean exactos en cada despliegue, protege el margen de ganancia y la estabilidad financiera de los negocios que adoptan la solución.</p>
        <p><b>AV2: </b> Para este avance, emití juicios infomrados ya que el análisis estático y el monitoreo continuo garantizan un software optimizado y de alta eficiencia computacional. Finalmente, el uso de BDD y evaluaciones heurísticas genera un impacto social positivo, garantizando una plataforma accesible, inclusiva y con alta disponibilidad para entornos globales (Capítulo VI).  </p>
        <p><b>TB2: </b> </p>
        <p><b>Sanchez Rios, Camila</b></p>
        <p><b>AV1:</b>Me encargué de crear la organización y los repositorios en el github. Colaboré con Capítulo I: Introduccion y Capítulo IV: Product Design, del mismo modo de subir la landing actualizada en el repositorio. </p>
        <p><b>TB1:</b> Contribuí en la implementación de los avances de las pruebas de los Core Entities Unit Tests y colabore en la realizacion del Capítulo VII: DevOps Practices.  </b> </p>
        <p><b>AV2: </b> </p>
        <p><b>TB2: </b> </p>
        <p><b>Choquehuanca Nuñez, Luciana Carolina</b></p>
        <p><b>AV1: </b> Emití juicios informados considerando el impacto de la solución al analizar cómo las necesidades, frustraciones y tareas de los usuarios podían afectar la aceptación del producto. Esto permitió orientar la propuesta hacia una solución útil, viable y alineada al contexto social y económico del público objetivo.  </p>
        <p><b>TB1: </b> Emití juicios informados considerando el impacto de la solución al seleccionar prácticas como BDD e integración continua para mejorar la calidad del software. Esto permitió reducir riesgos técnicos, evitar retrabajo y asegurar que el producto pueda mantenerse y evolucionar de forma más confiable.</p>
        <p><b>AV2: </b> Para este avance, emito juicios informados considerando el impacto de la solución en distintos contextos, ya que el diseño basado en experimentos, métricas y validaciones permite optimizar la eficiencia operativa de pequeños negocios, reduciendo pérdidas económicas por descontrol de inventario. Asimismo, StockWise genera un impacto social positivo al facilitar la digitalización de procesos en PYMES y emprendedores, promoviendo el acceso a herramientas tecnológicas simples, escalables y adaptables a distintos contextos de uso. </p>
        <p><b>TB2: </b> </p>
        <p><b>Fernandez Remon, Roy Linsh</b></p>
        <p><b>AV1:</b> Reconozco que la realización importante y de manera correcta de estas US ayudan completamente al desarrollo de los tests por los cuales se tienen que desarrollar de manera cuidadosa para poder evitar errores y lograr el trabajo de manera satisfactoria. </p>
        <p><b>TB1:</b> Soy consciente de que la correcta definición y realización de estas US impacta directamente en la calidad del testing. Por ello, su elaboración debe ser exhaustiva para evitar inconsistencias técnicas y garantizar la entrega exitosa del trabajo. </p>
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
  </tr>
  <tr>
    <th>
      <img src="assets/Chapter-1/Roy.jpeg" alt="Foto de perfil de Roy" width="800px">
    </th>
    <td valign="top">
      <p><b>Roy Fernández Remón</b></p>
      <p>
        Soy estudiante de la carrera de Ingeniería de Software. Soy una persona muy responsable y mi pasión del día a día es codificar sin errores. Conozco ampliamente los lenguajes de C#, Java, Phyton y Kotlin
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

<div style="page-break-after: always;"></div>


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

<div style="page-break-after: always;"></div>

# Capitulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Para el desarrollo de esta sección, el equipo llevó a cabo un proceso estructurado centrado en proyectar la experiencia ideal de nuestros User Personas al interactuar con StockWise. El proceso inició con una etapa de preparación, donde se revisaron los problemas identificados en los As-Is Scenario Mappings. Posteriormente, se realizó una lluvia de ideas individual para proponer soluciones tecnológicas directas a través de las funcionalidades de la aplicación (como el escaneo rápido o las alertas de stock). 

Tras esto, el equipo se reunió para una revisión e identificación de fases, agrupando las ideas y estableciendo las columnas cronológicas que representan el nuevo flujo de trabajo. Una vez que procedimos a nombrar las fases, comparamos el mapa resultante con el As-Is, identificando que el To-Be Scenario Mapping ofrece cambios significativos: reduce la carga cognitiva, automatiza el registro de datos y transforma sentimientos de frustración y estrés en tranquilidad y control. A continuación, se presentan los escenarios elaborados para cada User Persona. 

**1. To-Be Scenario Mapping: Carla Dueña de Bodega / Microempresa)** 

Carla acaba de recibir un nuevo pedido de proveedores en su tienda y necesita registrar el ingreso de los productos al inventario rápidamente mientras atiende su negocio. 

 <img src="assets/Chapter-3/Scenario%20Mapping.jpg" alt="ScenarioMapping01" width="800px"> 

**2. To-Be Scenario Mapping: Sebastián (Administrador de Inventario / Startup)**

Sebastián necesita generar un reporte de fin de mes para identificar qué productos tienen baja rotación y cuáles necesitan reabastecimiento urgente antes de la próxima. 

 <img src="assets/Chapter-3/Scenario%20Mapping%2002.jpg" alt="ScenarioMapping02" width="800px">

**Cambios identificados frente al As-Is Scenario Mapping (Comparación)** 

Al contrastar estos mapas con la situación actual (As-Is), destacan los siguientes beneficios del escenario To-Be con StockWise: 

- De manual a automatizado: Se elimina el registro en libretas o la digitación celda por celda en hojas de cálculo, pasando al escaneo de códigos y automatización de sumas. 
- De reactivo a proactivo: Los usuarios ya no descubren que falta stock cuando el cliente lo pide; el sistema les avisa antes mediante alertas de "Stock Crítico".
- Cambio emocional drástico: La frustración, el miedo a equivocarse en los cálculos y la pérdida de tiempo se transforman en sentimientos de confianza, eficiencia y tranquilidad. 

## 3.2. User Stories

Las User Stories son clave en metodologías ágiles porque traducen los requisitos funcionales desde la mirada del usuario. Cada historia especifica una necesidad concreta, lo que permite planificar, priorizar y construir el sistema de forma iterativa. Así se asegura que cada función aporte valor real y permanezca alineada con las expectativas del usuario final.

 <img src="assets/Chapter-3/US01.png" alt="US01" width="800px"> 

 <img src="assets/Chapter-3/US02.png" alt="US02" width="800px"> 

 <img src="assets/Chapter-3/US03.png" alt="US03" width="800px"> 

 <img src="assets/Chapter-3/US04.png" alt="US04" width="800px"> 

 <img src="assets/Chapter-3/US05.png" alt="US05" width="800px"> 

 <img src="assets/Chapter-3/US06.png" alt="US06" width="800px"> 

 <img src="assets/Chapter-3/US07.png" alt="US07" width="800px"> 

 <img src="assets/Chapter-3/US08.png" alt="US08" width="800px"> 

 <img src="assets/Chapter-3/US09.png" alt="US09" width="800px"> 

 <img src="assets/Chapter-3/US10.png" alt="US10" width="800px"> 

 <img src="assets/Chapter-3/US11.png" alt="US11" width="800px"> 

 <img src="assets/Chapter-3/US12.png" alt="US12" width="800px"> 

 <img src="assets/Chapter-3/US13.png" alt="US13" width="800px"> 

 <img src="assets/Chapter-3/US14.png" alt="US14" width="800px">

 <img src="assets/Chapter-3/US15.png" alt="US15" width="800px">

 <img src="assets/Chapter-3/US16.png" alt="US16" width="800px">

 <img src="assets/Chapter-3/US17.png" alt="US17" width="800px">

 <img src="assets/Chapter-3/US18.png" alt="US18" width="800px"> 

 <img src="assets/Chapter-3/US19.png" alt="US19" width="800px"> 

 <img src="assets/Chapter-3/US20.png" alt="US20" width="800px"> 

 <img src="assets/Chapter-3/US21.png" alt="US21" width="800px"> 

 <img src="assets/Chapter-3/US22.png" alt="US22" width="800px"> 

 <img src="assets/Chapter-3/US23.png" alt="US23" width="800px"> 

 <img src="assets/Chapter-3/US24.png" alt="US24" width="800px"> 

 <img src="assets/Chapter-3/US25.png" alt="US25" width="800px"> 

 <img src="assets/Chapter-3/US26.png" alt="US26" width="800px"> 

 <img src="assets/Chapter-3/US27.png" alt="US27" width="800px"> 

 <img src="assets/Chapter-3/US28.png" alt="US28" width="800px"> 

 <img src="assets/Chapter-3/US29.png" alt="US29" width="800px"> 

 <img src="assets/Chapter-3/US30.png" alt="US30" width="800px"> 

 <img src="assets/Chapter-3/US31.png" alt="US31" width="800px"> 

 <img src="assets/Chapter-3/US32.png" alt="US32" width="800px"> 

 <img src="assets/Chapter-3/US33.png" alt="US33" width="800px"> 

 <img src="assets/Chapter-3/US34.png" alt="US34" width="800px"> 

 <img src="assets/Chapter-3/US35.png" alt="US35" width="800px"> 

 <img src="assets/Chapter-3/US36.png" alt="US36" width="800px"> 

 <img src="assets/Chapter-3/US37.png" alt="US37" width="800px"> 

 <img src="assets/Chapter-3/US38.png" alt="US38" width="800px"> 

 <img src="assets/Chapter-3/US39.png" alt="US39" width="800px"> 

 <img src="assets/Chapter-3/US40.png" alt="US40" width="800px"> 


**Technical Stories** 

En esta sección se describen las historias técnicas que desarrollamos para implementar las funcionalidades clave. Cada historia define tareas específicas que el equipo de desarrollo debe realizar, como crear endpoints, manejar validaciones, controlar el stock, generar reportes, entre otros.

 <img src="assets/Chapter-3/TS01.png" alt="TS01" width="800px"> 

 <img src="assets/Chapter-3/TS02.png" alt="TS02" width="800px"> 

 <img src="assets/Chapter-3/TS03.png" alt="TS03" width="800px"> 

 <img src="assets/Chapter-3/TS04.png" alt="TS04" width="800px"> 

 <img src="assets/Chapter-3/TS05.png" alt="TS05" width="800px"> 

 <img src="assets/Chapter-3/TS06.png" alt="TS06" width="800px"> 

 <img src="assets/Chapter-3/TS07.png" alt="TS07" width="800px"> 

 <img src="assets/Chapter-3/TS08.png" alt="TS08" width="800px"> 

 <img src="assets/Chapter-3/TS09.png" alt="TS09" width="800px"> 

 <img src="assets/Chapter-3/TS10.png" alt="TS10" width="800px"> 

 <img src="assets/Chapter-3/TS11.png" alt="TS11" width="800px"> 

 <img src="assets/Chapter-3/TS12.png" alt="TS12" width="800px"> 

 <img src="assets/Chapter-3/TS13.png" alt="TS13" width="800px"> 

 <img src="assets/Chapter-3/TS14.png" alt="TS14" width="800px"> 

 <img src="assets/Chapter-3/TS15.png" alt="TS15" width="800px"> 

 <img src="assets/Chapter-3/TS16.png" alt="TS16" width="800px"> 

**Spike Story** 

 <img src="assets/Chapter-3/SPK01.png" alt="SPK01" width="800px"> 

 <img src="assets/Chapter-3/SPK02.png" alt="SPK02" width="800px"> 

 <img src="assets/Chapter-3/SPK03.png" alt="SPK03" width="800px"> 

 <img src="assets/Chapter-3/SPK04.png" alt="SPK04" width="800px"> 

 <img src="assets/Chapter-3/SPK05.png" alt="SPK05" width="800px"> 

## 3.3. Product Backlog

| #  | User Story ID | Título                                                               | Story Points |
|----|---------------|----------------------------------------------------------------------|--------------|
| 1  | US01          | Registrar producto nuevo                                             | 5            |
| 2  | US05          | Generar alertas por bajo stock                                       | 5            |
| 3  | US07          | Añadir etiquetas para productos                                      | 5            |
| 4  | US08          | Generar estadística de productos más vendidos                        | 5            |
| 5  | US09          | Generar estadística de categoría más vendida                         | 5            |
| 6  | US11          | Generar estadística de stock promedio                                | 5            |
| 7  | US15          | Configurar roles y permisos                                          | 5            |
| 8  | US17          | Registrar lote de productos                                          | 5            |
| 9  | US20          | Añadir etiquetas a productos                                         | 5            |
| 10 | US26          | Registrar productos por voz                                          | 5            |
| 11 | US27          | Registrar geolocalización de productos y entregas                    | 5            |
| 12 | US28          | Localizar productos con mapa y QR                                    | 5            |
| 13 | US02          | Editar información de producto                                       | 3            |
| 14 | US03          | Registrar salida de producto                                         | 3            |
| 15 | US04          | Ver historial de movimientos                                         | 3            |
| 16 | US06          | Buscar productos en inventario                                       | 3            |
| 17 | US10          | Generar ticket promedio                                              | 3            |
| 18 | US12          | Generar reportes de inventario                                       | 3            |
| 19 | US13          | Controlar productos caducados                                        | 3            |
| 20 | US14          | Registrar devolución de productos                                    | 3            |
| 21 | US16          | Gestionar proveedores                                                | 3            |
| 22 | US18          | Visualizar historial de stock                                        | 3            |
| 23 | US19          | Configurar alertas de stock mínimo                                   | 3            |
| 24 | US21          | Buscar productos en inventario                                       | 3            |
| 25 | US22          | Generar alertas por productos caducados                              | 3            |
| 26 | US23          | Registrar ingreso de productos                                       | 3            |
| 27 | US25          | Comparar ventas entre periodos                                       | 3            |
| 28 | US29          | Gestionar predicción de reabastecimiento                             | 3            |
| 29 | TS03          | Generar API Creación de productos                                    | 3            |
| 30 | TS06          | Generar API Productos por etiqueta                                   | 3            |
| 31 | SPK01         | Implementar entrada por voz, comandos estructurados e interpretación | 3            |
| 32 | SPK03         | Geolocalizar y modelar la ubicación                                  | 3            |
| 33 | SPK04         | Configurar predicción de reabastecimiento                            | 3            |
| 34 | TS07          | Generar API Registro de inventario                                   | 3            |
| 35 | US30          | Escanear por lotes con cámara rápida                                 | 3            |
| 36 | US32          | Optimizar tiempos de respuesta                                       | 3            |
| 37 | US35          | Alertas en tiempo real                                               | 3            |
| 38 | TS14          | Generar API Consulta de alertas                                      | 3            |
| 39 | US24          | Visualizar resumen de stock por categoría                            | 2            |

**Gestión del producto Backlog** 

 <img src="assets/Chapter-3/Trello.png" alt="Trello" width="800px"> 

_Imagen (N°10). Elaboración propia. Realizado en Trello_ 

Trello del Product Backlog:
https://trello.com/invite/b/69fcb34c3773ca9fb5de2d61/ATTI1644207d65abc14d280915502d0695bc0DE32724/stoq-product-backlog

## 3.4. Impact Mapping

**Segmento Objetivo 1: Bodegas especializadas por rubro** 

 <img src="assets/Chapter-3/stockwise%20-%20impact%20map-bodeguero.png" alt="Objetivo1" width="800px"> 

_Imagen (N°8). Elaboración propia. Realizado en UXPRESSIA_

 <img src="assets/Chapter-3/stockwise%20-%20impact%20map-emprendedor.png" alt="Objetivo2" width="800px"> 

_Imagen (N°9). Elaboración propia. Realizado en UXPRESSIA_

<div style="page-break-after: always;"></div>


# Capitulo IV: Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

**Branding**

StockWise es una marca pensada para ofrecer confianza, cercanía y eficiencia a pequeñas y medianas empresas, especialmente bodegas de barrio y emprendimientos. El branding refleja accesibilidad, modernidad y calidez. El enfoque está en facilitar la transformación digital de la gestión de inventarios con una interfaz clara, amigable y funcional.

**Logotipo**

El logo combina una bodega estilizada con colores cálidos y un código de barras, representando tanto la esencia física del negocio como la modernización a través de tecnología.

- La palabra "Stock" en rojo (#BC162A) resalta la acción y lo esencial del inventario.
- La palabra "Wise" en marrón oscuro (#302325) sugiere inteligencia y fiabilidad.
  
El código de barras integrado representa la gestión estructurada y la automatización del stock.

<div align="center">
  <img src="assets/Chapter-4/logo.png" alt="c4-container"/>
</div>

**Tono de comunicación**

Nos comunicamos como lo haría un buen amigo del barrio, claro, sin complicaciones, y con buena onda. Queremos transmitir una sensación de seguridad y eficiencia, mientras mantenemos una comunicación cercana y amigable.

**Lenguaje (Language):**

Usamos términos fáciles de entender: “productos”, “alertas”, “entradas/salidas”, “usuarios”. Evitamos jerga técnica innecesaria o anglicismos si no son esenciales.

**Colores**

La paleta de colores de StockWise ha sido cuidadosamente seleccionada para transmitir profesionalismo, confianza y accesibilidad.

**Primary Colors:**

- #BC162A (Rojo intenso): Botones principales, acciones críticas, alertas importantes
- #EE7F27 (Naranja vibrante): Botones secundarios, estados activos, notificaciones
- #302325 (Marrón oscuro): Texto principal, headers, elementos de navegación

**Background Colors:**

- #F5E1A4 (Fondo cálido claro): Fondo general de la aplicación
- #D9D593 (Gris suave): Fondos de secciones, cards secundarios

**Functional Colors:**

- #27A300 (Verde éxito): Confirmaciones, estados positivos
- #FFC107 (Amarillo advertencia): Alertas moderadas, advertencias
- #DC3545 (Rojo error): Estados de error, acciones destructivas

<center> <img src="assets/Chapter-4/color.jpeg" style="width: 250px;"/> </center>
<br>

**Tipografía**

La elección tipográfica para StockWise es un componente esencial que complementa la identidad visual de la marca. Se han seleccionado dos familias tipográficas que juntas ofrecen versatilidad y coherencia, asegurando que la comunicación sea clara y efectiva en todos los medios.

**Font Families:**

- Inter: Para textos largos, body copy y contenido principal
- Nunito: Para headers, botones y elementos de interfaz

**Font Scale (Mobile First):**

- h1: 24px / 1.1 / Bold
- h2: 20px / 1.1 / SemiBold
- h3: 18px / 1.2 / Medium
- Body Large: 17px / 1.4 / Regular
- Body: 16px / 1.4 / Regular
- Small: 14px / 1.4 / Regular
- Caption: 12px / 1.3 / Regular

**Weights:**

- Bold (700): Títulos principales, acciones críticas
- SemiBold (600): Subtítulos, botones importantes
- Medium (500): Etiquetas, elementos interactivos
- Regular (400): Texto body, contenido principal
- Light (300): Texto secundario, descripciones

**Border Radius:**

- Small: 8px (botones pequeños, inputs)
- Medium: 12px (cards, modales)
- Large: 16px (containers principales)

**Spacing System (8px base):**

- xs: 4px
- sm: 8px
- md: 16px
- lg: 24px
- xl: 32px
- xxl: 48px

**Shadows:**

- Low: 0 2px 4px rgba(48, 35, 37, 0.1)
- Medium: 0 4px 8px rgba(48, 35, 37, 0.15)
- High: 0 8px 16px rgba(48, 35, 37, 0.2)
  
### 4.1.2. Web Style Guidelines

DISEÑO RESPONSIVE:

- El diseño se adaptará automáticamente al tamaño de la pantalla.

COMPONENTES VISUALES:

- Botones: Redondeados con 10px de radio. Cambian de color y tienen un efecto de sombra al usarse.

- Formularios: Cajas de texto con bordes suaves y sombreados ligeros, 40px. de alto.

- Links: En azul (#0000FF), subrayado. Subrayado, con color de cambio a azul oscuro (#00008E).

- Navegación: Menú superior: Con enlaces a las principales secciones.

<center> <img src="assets/Chapter-4/webStyleStockTrack.png" style="width: 250px;"/> </center>
<br>

### 4.1.3. Mobile Style Guidelines

El diseño móvil de StockWise prioriza la eficiencia en tareas rápidas, la facilidad de uso con una sola mano y la legibilidad en condiciones de poca luz o movimiento (típicas en bodegas y almacenes). Los principios clave son: accesibilidad táctil, minimalismo visual y respuesta inmediata.

**Navegación Móvil**

- Barra inferior (Bottom Tab Bar): Principal elemento de navegación. Contiene entre 4 y 5 iconos con etiqueta textual: _Inicio , Inventario, Movimientos, Alertas y Perfil._

  - Altura: 56px.
  - Iconos activos: Color primario #BC162A.
  - Iconos inactivos: Gris medio (#8E8E93).
  - Efecto táctil: Ripple o cambio de opacidad al presionar.

- **Navegación jerárquica:** Uso de flecha de retorno (<) en la esquina superior izquierda de cada pantalla secundaria, siguiendo el estándar de iOS y Android.

**Componentes Táctiles**

- Botones: Altura mínima de 48px (recomendación de accesibilidad). Ancho ajustable según contenido.

  - Botón primario: Fondo #BC162A, texto blanco, border radius 12px. Padding vertical: 12px, horizontal: 24px.
  - Botón secundario: Borde de 1.5px sólido #EE7F27, texto #EE7F27, fondo transparente.
  - Botón flotante (FAB): Para acciones rápidas como "Agregar producto" o "Escanear lote". Fondo #EE7F27, icono blanco, tamaño 56px, sombra media.

- Elementos de lista (Cards): Altura mínima 72px, separación entre cards de 8px. Al tocar una card, se resalta con un fondo gris muy claro (#F2F2F2) o un cambio de sombra. Espaciado interno: 12px.

**Entradas de Datos Específicas para Móvil**

- Campos de texto: Altura 48px, border radius 12px, borde de 1px #D9D593. Fondo blanco o #F5E1A4. Al activarse, borde cambia a #EE7F27 y aparece un ícono de limpiar (X) si hay texto.
  
- Escáner QR / Cámara rápida (Plan C): Llamada a pantalla completa con visor. El botón de captura debe estar en la parte inferior, a 72px del borde, para alcanzar con el pulgar. Confirmación posterior con un modal de resumen (producto sugerido + cantidad) antes de registrar.

**Feedback y Estados**

- Alerta in-app (Snackbar/Toast): Aparece en la parte inferior, sobre la barra de navegación. Duración 3 segundos. Fondo #302325, texto blanco, botón de acción (si aplica) en color #FFC107.

- Estados de carga: Indicador circular (spinner) con color primario, centrado en pantalla o dentro del componente correspondiente. Para acciones largas, mostrar mensaje: "Actualizando inventario...".

- Gestos táctiles: Soporte para "pull to refresh" en listas de inventario y movimientos. Deslizar horizontalmente (swipe) sobre un producto para mostrar acciones rápidas: Editar (lápiz) y Eliminar (basurero, color rojo error).

**Adaptabilidad y Accesibilidad**

- Tamaño mínimo de objetivo táctil: 44x44 puntos (Apple HIG) o 48x48dp (Material Design). Aplicado a todos los elementos interactivos: botones, enlaces, tarjetas seleccionables.

- Modo oscuro (no incluido inicialmente): Preparado para futura implementación. Usar variables de color que permitan mapeo inverso.

- Orientación: Soportada principalmente vertical (retrato). La orientación horizontal (landscape) se habilita solo para mapas (Plan B y C) y visualización de reportes gráficos, con adaptación de la barra superior.

#### 4.1.3.1. iOS Mobile Style Guidelines

Para la versión iOS de StockWise, se aplican las pautas generales de la marca (colores, tipografía, espaciado) adaptadas a las convenciones del ecosistema Apple (Human Interface Guidelines).

**Navegación**

- Barra inferior (Tab Bar): Altura 49px (estándar iOS). Íconos con estilo de línea (SF Symbols) que se llenan en estado activo. Color activo #BC162A, inactivo gris sistema (#8E8E93).

- Barra superior (Navigation Bar): Título grande (Large Title) en pantalla principal. Título pequeño en pantallas secundarias. Botón de retorno con texto de pantalla anterior.

**Controles y Componentes**

- Botones primarios: Texto centrado en mayúsculas? No (evitar mayúsculas forzadas en iOS). Fondo #BC162A, esquinas redondeadas (12px), altura 50px.

- Botón flotante (FAB): No se usa en iOS nativo. En su lugar, acción primaria como botón fijo en la parte inferior de la pantalla o dentro de la barra de navegación superior (lado derecho).

- Switches y toggles: Estilo iOS estándar (fondo gris, círculo blanco), con color activo #27A300 (verde éxito).

- Alertas (UIAlertController): Para confirmaciones destructivas (ej. eliminar producto), usar acción en rojo. Para notificaciones simples, preferir UIAlertController estilo action sheet desde la parte inferior.

**Gestos y Comportamiento**

- Swipe para atrás: Gestual nativo desde el borde izquierdo de la pantalla, soportado en todas las vistas.

- Pull to refresh: Animación estándar de iOS (spinner con líneas curvas).

- Selección de fecha/cantidad: Usar UIDatePicker (ruedas) o UIPickerView en la parte inferior, en lugar de modales personalizados.

**Teclado y Entrada de Datos**

- Escáner QR: Usar AVFoundation para cámara. El visor debe respetar las esquinas redondeadas del dispositivo.

**Tipografía y Escala**

- Mantener las fuentes Inter y Nunito (no usar SF Pro por consistencia de marca). Asegurarse de que el tamaño mínimo de texto sea 15pt para body (vs 16px en Android/web).

- Títulos grandes (Large Title): 34pt, Bold, #302325.

#### 4.1.3.2. Android Mobile Style Guidelines

Para la versión Android de StockWise, se aplican las pautas generales de la marca adaptadas a las convenciones de Material Design.

**Navegación**

- Barra inferior (Bottom Navigation): Altura 56px (estándar Material). Íconos con línea en estado inactivo, rellenos en estado activo. Color activo #BC162A, inactivo gris oscuro (#757575). Efecto ripple al presionar.

- Barra superior (Top App Bar): Altura 56px. Color de fondo #F5E1A4 o blanco. Ícono de hamburguesa (☰) para navegación lateral si aplica.

**Controles y Componentes**

- Botones primarios: Texto en mayúsculas? Sí (convención Material). Fondo #BC162A, esquinas redondeadas 12px, altura 48px, padding horizontal 24px. Efecto ripple en #EE7F27 al presionar.

- Botón flotante (FAB): Sí se usa. Tamaño 56px, fondo #EE7F27, icono blanco (@drawable/ic_add o similar). Elevación (sombra) por defecto 6dp. Ubicación: inferior derecha, margen 16px.

- Switches y toggles: Estilo Material Switch. Color activo #27A300, inactivo #D9D593.

- Alertas (Dialog): Para confirmaciones, usar AlertDialog con botones "Cancelar" (izquierda) y "Aceptar" (derecha).

**Gestos y Comportamiento**

- Swipe para atrás: Gestual desde cualquier borde lateral, sin botón de flecha adicional (navegación predictiva).

- Pull to refresh: Animación estándar Material (spinner circular con trayectoria).

- Swipe sobre lista: Deslizar horizontalmente sobre un producto para acciones rápidas: Editar (lápiz) y Eliminar (basurero, fondo rojo #DC3545).

**Entrada de Datos**

- Escáner QR / cámara rápida: Usar CameraX o ML Kit. El visor debe mostrar un rectángulo guía para encuadre.

- Campos de texto: Altura 48px, border radius 8px. Al activarse, subrayado o borde cambia a #EE7F27. Soporte para autocompletado sugerido.

**Tipografía y Escala**

- Mantener Inter y Nunito. Tamaño mínimo de texto: 14sp (vs 16px en web). Escala tipográfica basada en dp (no pt ni px).


## 4.2. Information Architecture

La arquitectura de la información, también conocida como Information Architecture (IA), implica la organización de la información de manera clara y lógica, de modo que los usuarios puedan comprender su ubicación, lo que han descubierto, qué pueden esperar y qué está disponible a su alrededor. Esto tiene como objetivo permitir a los usuarios encontrar con facilidad lo que están buscando, y a los clientes, comprender las capacidades de la plataforma. Además, la arquitectura de la información posibilita la incorporación de nuevas funciones y la expansión del producto sin generar una estructura compleja o de difícil comprensión (Rosenfeld, Morville & Arango 2015).

### 4.2.1. Organization Systems
La interfaz se divide en módulos bien definidos, accesibles desde un panel de navegación estructurado jerárquicamente. Estos módulos incluyen: Inicio, Home, Inventario y Configuración. Cada sección agrupa funciones específicas según su propósito, permitiendo que las tareas clave estén siempre al alcance del usuario.

#### Organization Systems

La arquitectura de organización de StockWise está diseñada siguiendo principios de agrupación lógica y progresiva de la información, permitiendo a los usuarios acceder rápidamente a las funciones necesarias según su rol y contexto de uso.

**Estructura Organizacional Principal**

| Módulo                        | Descripción                                                  | Funciones Principales                                                                                                                   | Acceso por Rol             |
| ----------------------------- | ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| **Dashboard Principal**       | Vista consolidada del estado del inventario y métricas clave | - Resumen ejecutivo de stock<br>- Alertas prioritarias<br>- Acciones rápidas<br>- Métricas en tiempo real                               | Admin, Encargado           |
| **Gestión de Inventario**     | Núcleo operativo para administración completa de productos   | - Registro y edición de productos<br>- Control de niveles de stock<br>- Categorización y etiquetado<br>- Gestión de ubicaciones físicas | Admin, Encargado, Empleado |
| **Operaciones Diarias**       | Módulo para transacciones y movimientos regulares            | - Registro de entradas/salidas<br>- Ajustes de inventario<br>- Historial de movimientos<br>- Devoluciones y mermas                      | Admin, Encargado, Empleado |
| **Reportes y Analytics**      | Sistema de generación y visualización de datos               | - Reportes personalizados<br>- Análisis de tendencias<br>- Métricas de rendimiento<br>- Exportación de datos                            | Admin, Encargado           |
| **Configuración del Sistema** | Administración de preferencias y usuarios                    | - Gestión de perfiles de usuario<br>- Configuración de empresa<br>- Preferencias de notificaciones<br>- Backup y seguridad              | Admin                      |

**Principios de Organización Aplicados**

1. **Agrupación por Funcionalidad**
   Las características se organizan según su propósito común, facilitando la asociación mental y reduciendo la carga cognitiva.

1. **Jerarquía Visual Progresiva**
   La información se presenta desde lo general hacia lo específico, permitiendo drill-down controlado según las necesidades del usuario.

1. **Contextualización Dinámica**
   Las opciones disponibles se adaptan según el rol del usuario y el módulo activo, mostrando solo las funciones relevantes.

1. **Consistencia Transversal**
   Mismos patrones organizativos se aplican en todos los módulos, creando una experiencia unificada y predecible.

**Organización de Contenido por Módulo**

**Módulo de Inventario**

- **Agrupación Primaria:** Por estado de stock (Normal, Bajo, Crítico)
- **Agrupación Secundaria:** Por categorías de producto
- **Agrupación Terciaria:** Por ubicación física en bodega

**Módulo de Reportes**

- **Agrupación Temporal:** Diario, Semanal, Mensual
- **Agrupación por Métrica:** Ventas, Stock, Rentabilidad
- **Agrupación por Producto:** Individual, Por categoría, Global
  
### 4.2.2. Labeling Systems

El sistema de etiquetado en StockWise sigue principios de claridad, consistencia y contexto, asegurando que los usuarios comprendan inmediatamente la función de cada elemento.

**Principios de Etiquetado:**

- Lenguaje Natural: Usamos términos del dominio del usuario ("productos", "proveedores", "ventas")
- Consistencia: Mismo término para misma función en toda la aplicación
- Jerarquía Visual: Tamaño y peso tipográfico reflejan importancia
- Contexto: Las etiquetas cambian según el módulo y las acciones disponibles

**Sistema de Iconografía:**

- **Acciones Principales:**

  - Agregar/Registrar
  - Editar/Modificar
  - Eliminar/Descartar
  - Buscar/Filtrar
  - Exportar/Compartir

- **Módulos y Secciones:**

  - Dashboard - Vista general
  - Inventario - Gestión de productos
  - Movimientos - Entradas y salidas
  - Reportes - Analytics y métricas
  - Configuración - Ajustes del sistema

- **Estados del Sistema:**
  - Completado/Éxito
  - Advertencia/Alerta
  - Error/Problema
  - Procesando/En curso

**Microcopy y Mensajes:**

- **Botones de Acción:** "Agregar Producto", "Registrar Entrada", "Generar Reporte"
- **Mensajes de Confirmación:** "¿Estás seguro de eliminar este producto?"
- **Estados Vacíos:** "Aún no tienes productos registrados"
- **Guías Contextuales:** "Usa el código de barras para buscar más rápido"

### 4.2.3. SEO Tags and Meta Tags

**SEO Tags**

SEO (Search Engine Optimization) Tags son elementos de HTML que ayudan a los motores de búsqueda a entender el contenido y la estructura de una página web. Estos tags influyen en cómo los motores de búsqueda indexan y clasifican tu sitio en los resultados de búsqueda.

**Algunos ejemplos importantes de SEO Tags para StockWise:**

**Title Tags para Páginas Principales:**

```html
<!-- Página de Inicio -->
<title>StockWise - App de Gestión de Inventarios para PYMES</title>

<!-- Página de Características -->
<title>Gestión de Inventario | StockWise App</title>

<!-- Página de Precios -->
<title>Planes de Gestión de Inventario | StockWise</title>
```

**Header Tags Estructurados:**

```html
<h1>Gestiona Tu Inventario desde tu Móvil y PC</h1>
<h2>La solución simple para negocios en crecimiento</h2>
<h3>Control total de tu stock en tiempo real</h3>
```

**Meta Descriptions Optimizadas:**

```html
<meta
  name="description"
  content="StockWise - App móvil de gestión de inventarios para PYMES. Controla stock, genera reportes y evita quiebres de inventario desde tu teléfono."
/>

<meta
  name="keywords"
  content="gestión inventarios, app móvil y web, control stock, PYMES, bodegas, emprendedores"
/>
```

**Open Graph Tags para Redes Sociales:**

```html
<meta property="og:title" content="StockWise - App de Inventarios" />
<meta
  property="og:description"
  content="Gestiona tu inventario desde cualquier lugar con StockWise"
/>
<meta property="og:image" content="/images/stockwise-social-preview.png" />
```

### 4.2.4. Searching Systems

El sistema de búsqueda de StockWise está diseñado para ser intuitivo y potente, permitiendo a los usuarios encontrar rápidamente la información que necesitan en su inventario.

**Características del Sistema de Búsqueda:**

- **Búsqueda Inteligente:**
  - Búsqueda por texto libre en múltiples campos (nombre, - código, categoría, proveedor)
  - Búsqueda por código de barras usando la cámara del dispositivo
  - Búsqueda por voz para hands-free operation
  - Búsqueda predictiva con sugerencias en tiempo real
- **Resultados de Búsqueda:**
  - Ordenamiento por relevancia, nombre, stock, fecha
  - Vista de tarjetas con información esencial
  - Acciones rápidas desde los resultados
  - Historial de búsquedas recientes
- **Búsqueda por Lotes:**
  - Escaneo múltiple de códigos de barras
  - Reconocimiento de imágenes para productos sin código
  - Procesamiento offline con sincronización posterior

### 4.2.5. Navigation Systems
El sistema de navegación de StockWise está optimizado para dispositivos móviles, priorizando la accesibilidad y la eficiencia en las tareas diarias.

**Patrones de Navegación Principal:**

**Bottom Navigation Bar:**

```text
[Inicio]  [Inventario]  [Agregar]  [Reportes]  [Perfil]
```

**Navegación por Gestos:**

- Deslizar hacia la derecha: Menú lateral
- Deslizar hacia abajo: Actualizar contenido
- Deslizar hacia arriba: Acciones rápidas
- Toque largo: Opciones contextuales

**Navegación Contextual:**

- Breadcrumbs para ubicación en estructuras profundas
- Botón "Atras" nativo del dispositivo
- Navegación por pestañas en secciones complejas
- Accesos directos personalizables según uso frecuente

**Navegación para Accesibilidad:**

- Soporte completo para lectores de pantalla
- Navegación por teclado en versiones tablet
- Tamaños de touch target mínimos de 44px
- Alto contraste y modos de daltonismo
  
## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe
El prototipado de la landing page cuenta diversas secciones:

- Header: Incluye botones para facilitar la navegación
- Hero Section: Con un botón CTA principal, un título y una imagen.
- Sección de Beneficios / Características: mostrara un resumen de 3 beneficios que ofrece la app
- Planes / Precios: Trendra 2 planes con su referente título y lista de características y contara con un botón CTA secundario por cada plan.
- Testimonios: Consta de un título y subtítulo, así como de unos testimonios de usuarios de cada segmento, lo que aumenta la confianza en los potenciales clientes.
- Llamado a la acción final (CTA grande) : Tiene un título y subtítulo, un boton CTA grande para "Try our app"
- Footer: Sección que da fin a la landing page, cuenta con las redes sociales de la plataforma.

**Wireframe Desktop**

<center> <img src="assets/Chapter-4/wireframes-web/Wireframe-Desktop.png" style="width: 420px;"/> </center>
<br>

**Wireframe Mobile**

En la versión mobile el navbar se reemplaza por un menu desplegable.

<center> <img src="assets/Chapter-4/wireframes-mobile/Wireframe - Mobile.png" style="width: 420px;"/> </center>
<br>

### 4.3.2. Landing Page Mock-up

**Wireframe Desktop**

<center> <img src="assets/Chapter-4/mockups-web/Mockup-Desktop.png" style="width: 420px;"/> </center>
<br>


**Wireframe Mobile**

En la versión mobile el navbar se reemplaza por un menu desplegable.
<center> <img src="assets/Chapter-4/mockups-mobile/Mockup - Mobile.png" style="width: 420px;"/> </center>

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

Los wireframes ayudan a los diseñadores y desarrolladores a planificar la arquitectura y la funcionalidad de la aplicación, permitiendo visualizar cómo los usuarios interactuarán con ella. Son esenciales en las primeras etapas de desarrollo, ya que facilitan la comunicación de ideas, la identificación de problemas potenciales y la alineación de todos los involucrados en el proyecto antes de pasar al diseño detallado y la programación.

**Iniciar sesión**

La siguiente imagen evidencia el wireframe de la sección de “inicio de sesión” desde la vista desktop web browser. En ella, los usuarios deberán ingresar las credenciales necesarias para poder acceder a la aplicación, siempre y cuando posean con una cuenta previamente creada.
<center> <img src="assets/Chapter-4/wireframes-mobile/Inicio de sesión.png" style="width: 420px;"/> </center>
<br>

**Crear cuenta**

La siguiente imagen presenta la sección de “registro de usuario”, a través de la cual los administradores podrán remitir a la aplicación la información necesaria para crear una cuenta.
<center> <img src="assets/Chapter-4/wireframes-mobile/Registro.png" style="width: 420px;"/> </center>
<br>

**Elegir plan de pago**

La siguiente imagen presenta la sección “Elegir plan de pago”, la cual despliega las categorías de planes disponibles en la plataforma. Los tres planes están diseñados para adaptarse a las necesidades de los administradores de tienda acorde a sus necesidades.
<center> <img src="assets/Chapter-4/wireframes-mobile/Seleccionar plan.png" style="width: 420px;"/> </center>
<br>

**Pasarela de pagos**

La siguiente imagen corresponde a la sección “Pasarela de pagos” donde los usuarios son dirigidas a un formulario para seleccionar y registrar su método de pago. Una vez que el proceso de pago es completado exitosamente, se notifica al usuario con un mensaje confirmando el vinculo de su tarjeta con la plataforma. Del mismo modo, si el usuario desea retirar su información o actualizar lo podra hacer a travéz de su perfil.
<center> <img src="assets/Chapter-4/wireframes-mobile/Pago.png" style="width: 420px;"/> </center>
<br>

**Mi perfil**

La sección titulada “Mi perfil” solicita al usuario que complete información en dos categorías para registrar sus datos. Adicionalmente, la categoría "cambiar cuenta" ofrece la opción de permitir al usuario cambiar de cuenta a una de empleador y utilizar las herramientas de este por la plataforma. Tambien, tiene libertad de cambiar el plan si es necesario.

_Perfil Administrador_

En este perfil, el usuario puede ver a la derecha sus herramientas correpondientes a su cuenta.
<center> <img src="assets/Chapter-4/wireframes-mobile/Perfil.png" style="width: 420px;"/> </center>
<br>
<center> <img src="assets/Chapter-4/wireframes-mobile/Perfil (1).png" style="width: 420px;"/> </center>
<br>

**Panel de control (Dashboard)**

Esta pantalla representa el panel de control principal del sistema StockWise. Su objetivo es proporcionar al usuario una vista general del estado del inventario y acceso rápido a funciones clave. Entre sus elementos principales se encuentran:

- Resumen de información:
  - Total de Productos: número total de ítems registrados.
  - Fecha del Último Proveedor: muestra la última fecha de ingreso de productos (por proveedor).
  - Próximos a Caducar: productos con fecha de vencimiento próxima, indicando la fecha y el stock restante.
- Accesos rápidos:
  - Historial de Movimientos: seguimiento de entradas y salidas del inventario.
  - Inventario: acceso directo a la lista completa de productos.
- Botones de acción:
  - Agregar Productos: para registrar nuevos productos en el sistema.
  - Kits de Productos: permite combinar productos individuales en un kit.
  - Devolución de Productos: facilita el registro de productos devueltos por proveedores o clientes.
<center> <img src="assets/Chapter-4/wireframes-mobile/Dashboard.png" style="width: 420px;"/> </center>
<br>

**Combinación de Productos en Kits**

Esta sección está dedicada a la funcionalidad de crear kits de productos, una herramienta útil para negocios que venden combos o paquetes predefinidos. Las características principales incluyen:

Buscador de productos: permite al usuario localizar rápidamente productos por nombre. Listado de productos existentes: Muestra el nombre, precio y stock disponible de cada producto. Incluye un botón de acción en cada fila para añadir productos al kit. Botón “Seleccionar para kit”: una vez seleccionados los productos deseados, el usuario puede avanzar para crear el kit final. Esta funcionalidad mejora la gestión del stock agrupado y permite optimizar estrategias de venta, como combos promocionales o paquetes de temporada.
<center> <img src="assets/Chapter-4/wireframes-mobile/Combinar Producto.png" style="width: 420px;"/> </center>
<br>

**Agregar Producto**

Esta pantalla permite visualizar todos los productos actualmente registrados en el inventario, con acceso rápido para editar o ver más detalles. Las funcionalidades clave incluyen:

- Tarjetas de producto con información relevante:
  - Nombre del producto (ej. Galleta).
  - Categoría/etiqueta (ej. Golosina).
  - Stock disponible.
- Botón “+ Detalle” para ver información adicional o editar.
- Botón “+”: permite agregar un nuevo producto desde cero
- Buscador de productos y opción de filtro por categoría o stock.
<center> <img src="assets/Chapter-4/wireframes-mobile/Agregar Producto (1).png" style="width: 420px;"/> </center>
<br>

**Registro de Nuevo Producto**

Pantalla que aparece al presionar el botón “+”, diseñada para agregar un nuevo producto al sistema. Incluye los siguientes campos:

- Nombre del producto.
- Etiquetas/Categorías (por ejemplo: Golosina, Bebida).
- Precio de compra y de venta.
- Cantidad inicial del producto.
- Número de lote y fecha de caducidad.
- Notas adicionales, si se desea registrar observaciones específicas.

Una vez completado el formulario, se debe presionar "Guardar" para registrar el nuevo ítem.
<center> <img src="assets/Chapter-4/wireframes-mobile/Agregar Producto.png" style="width: 420px;"/> </center>
<br>  

_Edición Rápida de Producto_

Este modal aparece al hacer clic en “+ Detalle” sobre cualquier tarjeta de producto en la pantalla principal. Permite realizar modificaciones rápidas sobre un producto específico:

- Editar etiquetas.
- Actualizar cantidad.
- Modificar fecha de caducidad.
- Agregar notas.

Incluye botones para “Duplicar” (crear una copia rápida del producto) y “Eliminar” (quitar del sistema).
<center> <img src="assets/Chapter-4/wireframes-mobile/Agregar Producto (2).png" style="width: 420px;"/> </center>
<br>  

**Historial de Movimientos**

Esta vista permite al usuario consultar todos los movimientos registrados en el sistema, ya sea por producto individual, por categoría o mediante cálculo del ticket promedio.

- Filtros disponibles:
  - Tipo de gestión: Producto, Categoría o Stock Promedio.
  - Rango de fecha: permite buscar registros por fechas específicas.
- Resultados organizados en tarjetas que muestran:
  - Producto o categoría
  - Fecha del movimiento
  - Precio unitario (si aplica)
  - Cantidad gestionada
  - Total del movimiento
- También cuenta con botones para:
  - Editar un registro
  - Eliminar un registro (con confirmación previa).
<center> <img src="assets/Chapter-4/wireframes-mobile/Historial.png" style="width: 420px;"/> </center>
<br>  

_Confirmación de Eliminación_

Al presionar el botón de eliminar, se despliega una ventana emergente de confirmación que advierte al usuario antes de borrar un registro del historial.
<center> <img src="assets/Chapter-4/wireframes-mobile/Historial Eliminar.png" style="width: 420px;"/> </center>
<br>  

**Ticket Promedio**

Al seleccionar “Stock Promedio” como tipo de gestión, se habilita el acceso al cálculo de Ticket Promedio, que estima el valor promedio de venta por unidad en un rango de fechas. Este recurso permite realizar un análisis financiero rápido sobre el comportamiento de productos específicos.

- Campos del formulario:
  -  Rango de fecha.
  -  Producto a analizar.
  -  Cantidad de ventas.
  - Precio total de ventas.
  - Resultado del ticket promedio (calculado automáticamente).
- Botones:
  - Crear: Guarda el registro del ticket.
  - Cancelar: Cierra el modal sin guardar.
<center> <img src="assets/Chapter-4/wireframes-mobile/Historial Ticket Promedio.png" style="width: 420px;"/> </center>
<br> 

**Pantalla principal de Inventario por Lote**

Esta pantalla permite la visualización y gestión del inventario agrupado por lote de entrada.

- Filtros en la parte superior:
  - Búsqueda por Producto
  - Proveedor
  - Fecha de ingreso
  - Cantidad
  - Precio
- Lista de productos ingresados por lote:
  - Proveedor
  - Producto
  - Fecha de entrada
  - Cantidad por unidad
  - Precio por unidad
  - Unidad de medida
- Botón rojo “Generar Nuevo Lote” ubicado a la derecha, que permite agregar un nuevo registro.
<center> <img src="assets/Chapter-4/wireframes-mobile/Inventario por lote.png" style="width: 420px;"/> </center>
<br> 

_Busqueda Avanzada_
<center> <img src="assets/Chapter-4/wireframes-mobile/Inventario por lote (2).png" style="width: 420px;"/> </center>
<br> 

**Pantalla de Inventario por Producto**

Visualización clara de todos los productos del inventario, con opción de filtrar por condiciones específicas, lo cual optimiza el control individualizado del stock.

- Filtros:
  - Categoría
  - Productos
  - Rango de Fecha
  - Stock Mínimo.
- Tabla:
  - Categoría
  - Producto
  - Fecha de entrada
  - Cantidad
  - Precio
  - Stock mínimo
  - Unidad de medida.
- Botón: “Generar Nuevo Lote”.
<center> <img src="assets/Chapter-4/wireframes-mobile/Inventario por producto.png" style="width: 420px;"/> </center>
<br> 

_Edición de Registro_

Facilita la actualización de datos en tiempo real, permitiendo mantener el inventario siempre actualizado y preciso.

- Elementos mostrados:
  - Formulario editable con campos: Categoría, Producto, Cantidad por unidad, Precio por unidad, Unidad de medida.
  - Botones de acción: “Crear” (confirmar edición) y “Cancelar”.
<center> <img src="assets/Chapter-4/wireframes-mobile/Inventario por producto (1).png" style="width: 420px;"/> </center>
<br> 

### 4.4.2. Mobile Applications Wireflow Diagrams

Los Mobile Applications Wireflow Diagrams son una combinación de wireframes y flujos de usuario (user flows) que ilustran no solo la estructura y disposición de las pantallas de una Mobile Application, sino también cómo los usuarios navegarán entre ellas. Estos diagramas proporcionan una visión detallada del recorrido del usuario, mostrando las interacciones clave y las transiciones de una pantalla a otra dentro de la aplicación.

**User Goal Registrar:** El usuario desea crear una nueva cuenta para comenzar a usar la plataforma y vincular su método de pago según el plan seleccionado.

**Flujo funcional:**

1. El usuario selecciona la opción “Registrar” en la Landing Page.
2. Ingresa los datos solicitados: correo electrónico, nombre y contraseña.
3. Selecciona el tipo de plan.
4. Si elige el Plan Negocio, completa los datos de la tarjeta y confirma el pago.
5. El sistema valida la transacción.
6. Si el pago es exitoso, se muestra una ventana flotante indicando “Pago realizado correctamente”.
7. Si el pago falla, se muestra una alerta de error con el mensaje “No se pudo procesar el pago”.
8. Finalmente, se redirige al usuario a la pantalla de Inicio de sesión.
<center> <img src="assets/Chapter-4/user goal Registrar.png" style="width: 420px;"/> </center>
<br> 

**User Goal: Iniciar sesión**

El usuario desea iniciar sesión en la plataforma utilizando sus credenciales y acceder a las funciones principales del sistema.

**Flujo funcional:**

1. El usuario ingresa su correo electrónico y contraseña.
2. El usuario selecciona la opción “Iniciar sesión”.
3. El sistema valida las credenciales ingresadas.
4. Si las credenciales son correctas, el sistema autoriza el acceso y muestra el panel principal (Dashboard).
5. Desde el panel principal, el usuario puede acceder al módulo de Perfil y editar su información personal.
6. Si las credenciales son incorrectas, el sistema muestra un mensaje de error: “Correo o contraseña incorrectos” y permite reintentar el acceso.
<center> <img src="assets/Chapter-4/user goal Iniciar sesion.png" style="width: 420px;"/> </center>
<br> 

**User Goal: Navegar por el Dashboard**

El usuario explora la vista principal y accede a las herramientas clave del sistema.

**Flujo funcional:**

1. El usuario accede al Dashboard después de iniciar sesión.
2. Visualiza el total de productos registrados y fecha del último proveedor.
3. Observa un resumen de productos próximos a caducar con stock y fecha.
4. Accede a botones de acción rápida (Historial de Movimientos, Inventario, Agregar Productos, Kits y Devolución de productos)
5. Selecciona cualquiera de las secciones para continuar su gestión.
<center> <img src="assets/Chapter-4/user goal Navegador por el dashboard.png" style="width: 420px;"/> </center>
<br> 

**User Goal: Inventario (Producto / Lote)**

El usuario explora la vista de inventario y accede a los registros de productos y lotes.

**Flujo funcional:**

1. Ingresa a la sección de Inventario.
2. Revisa el listado de productos presionando el botón "por producto".
3. Filtra los productos por categoría, nombre del producto, fecha o stock mínimo.
4. Consulta el listado con información clave: fecha de entrada, cantidad por unidad, precio, stock mínimo y unidad de medida.
<center> <img src="assets/Chapter-4/user goal Inventario.png" style="width: 420px;"/> </center>
<br> 

**User Goal: Botones Principales (Agregar Producto y Kits)**

El usuario visualiza la sección principal y gestiona productos y kits desde las opciones disponibles.

**Flujo funcional:**

1. Pulsa el botón "Agregar Producto".
2. Rellena los campos solicitados para registrar uno nuevo.
3. Pulsa el botón "Crear Kit".
4. Combina productos existentes para crear un kit nuevo.
5. El usuario pulsa el botón “Añadir Productos” desde el Dashboard.
6. Visualiza una galería de productos existentes y accede a opciones para editarlos o duplicarlos.
7. Puede agregar uno nuevo haciendo clic en el botón “+”, donde se despliega un formulario con campos como nombre,etiquetas, cantidad, lote, precios, fecha de caducidad y notas.
8. Desde el menú principal, también accede a la opción “Kits”.
<center> <img src="assets/Chapter-4/user goal Botones principales.png" style="width: 420px;"/> </center>
<br> 

**User Goal: Historial de Movimientos**

El usuario consulta y analiza los movimientos del inventario, accediendo a información de entradas, salidas y métricas relacionadas.

**Flujo funcional:**

1. Navega a la sección de Historial.
2. Visualiza entradas y salidas de productos.
3. Filtra movimientos por fecha, producto o lote.
4. El usuario accede a la sección de Historial desde el panel principal.
5. Filtra los registros por tipo de gestión, categoría, stock promedio y fecha.
6. Visualiza los movimientos realizados, incluyendo datos como nombre del producto, fecha de consulta, precio unitario, cantidad y total.
7. Consulta métricas como el stock promedio, estado del producto y stock ideal.
8. Cuenta con botones para editar o eliminar cada registro y, para los stock promedio, exportar la información y realiza un ticket promedio.
<center> <img src="assets/Chapter-4/user goal Historial .png" style="width: 420px;"/> </center>
<br> 

### 4.4.3. Mobile Applications Mock-ups

**Iniciar sesión**
<center> <img src="assets/Chapter-4/mockups-mobile/Inicio de sesión (1).png" style="width: 420px;"/> </center>
<br>

**Crear cuenta**
<center> <img src="assets/Chapter-4/mockups-mobile/Registro (1).png" style="width: 420px;"/> </center>
<br> 

**Elegir plan de pago**
<center> <img src="assets/Chapter-4/mockups-mobile/Seleccionar plan (1).png" style="width: 420px;"/> </center>
<br> 

**Pasarela de pagos**
<center> <img src="assets/Chapter-4/mockups-mobile/Pago (1).png" style="width: 420px;"/> </center>
<br> 

**Mi perfil**

*Perfil Administrador*
<center> <img src="assets/Chapter-4/mockups-mobile/Perfil.png" style="width: 420px;"/> </center>
<br> 
<center> <img src="assets/Chapter-4/mockups-mobile/Perfil ajustes.png" style="width: 420px;"/> </center>
<br> 

**Panel de control (Dashboard)**
<center> <img src="assets/Chapter-4/mockups-mobile/Dashboard.png" style="width: 420px;"/> </center>
<br> 

**Combinación de Productos en Kits**
<center> <img src="assets/Chapter-4/mockups-mobile/Combinar producto.png" style="width: 420px;"/> </center>
<br> 

**Agregar Producto**
<center> <img src="assets/Chapter-4/mockups-mobile/Agregar Producto.png" style="width: 420px;"/> </center>
<br> 

**Registro de Nuevo Producto**
<center> <img src="assets/Chapter-4/mockups-mobile/Registro Prodcuto.png" style="width: 420px;"/> </center>
<br> 

*Edición Rápida de Producto*
<center> <img src="assets/Chapter-4/mockups-mobile/Edicion Producto.png" style="width: 420px;"/> </center>
<br> 

**Historial de Movimientos**
<center> <img src="assets/Chapter-4/mockups-mobile/Historial.png" style="width: 420px;"/> </center>
<br> 

*Confirmación de Eliminación*
<center> <img src="assets/Chapter-4/mockups-mobile/Historial Eliminar.png" style="width: 420px;"/> </center>
<br> 

**Ticket Promedio**   
<center> <img src="assets/Chapter-4/mockups-mobile/Historial Ticket Promedio.png" style="width: 420px;"/> </center>
<br> 

**Pantalla principal de Inventario por Lote**
<center> <img src="assets/Chapter-4/mockups-mobile/Inventario.png" style="width: 420px;"/> </center>
<br> 

*Busqueda Avanzada*
<center> <img src="assets/Chapter-4/mockups-mobile/Inventario Busqueda.png" style="width: 420px;"/> </center>
<br>

**Pantalla de Inventario por Producto**
<center> <img src="assets/Chapter-4/mockups-mobile/Inventario por producto.png" style="width: 420px;"/> </center>
<br>

*Edición de Registro*
<center> <img src="assets/Chapter-4/mockups-mobile/Inventario por producto edi.png" style="width: 420px;"/> </center>
<br>

### 4.4.4. Mobile Applications User Flow Diagrams

**User Goal: Registrar**
<center> <img src="assets/Chapter-4/Color user goal Registrar.png" style="width: 420px;"/> </center>
<br>

**User Goal: Iniciar sesión**
<center> <img src="assets/Chapter-4/Color user goal Iniciar sesion.png" style="width: 420px;"/> </center>
<br>

**User Goal: Navegar por el dashboard**
<center> <img src="assets/Chapter-4/Color user goal Navegador.png" style="width: 420px;"/> </center>
<br>

**User Goal: Inventario (Producto/Lote)**
<center> <img src="assets/Chapter-4/Color user goal Inventario .png" style="width: 420px;"/> </center>
<br>

**User Goal: Botones Principales (Agregar Producto y Kits)**
<center> <img src="assets/Chapter-4/Color user goal Botones principales .png" style="width: 420px;"/> </center>
<br>

**User Goal: Historial de Movimientos**
<center> <img src="assets/Chapter-4/Color user goal Historial .png" style="width: 420px;"/> </center>
<br>

## 4.5. Mobile Applications Prototyping

El apartado de Mobile Application Prototyping muestra el primer acercamiento visual e interactivo al diseño de la aplicación. A través del uso de herramientas de prototipado, se crean representaciones dinámicas que permiten simular la navegación, disposición de módulos y flujos de interacción del usuario antes de pasar a la fase de desarrollo.

Durante este proceso, se estructuran pantallas clave como el login, panel de control, gestión de productos, movimientos de stock, generación de reportes y alertas de inventario. El objetivo es anticipar posibles mejoras de usabilidad y validar la propuesta funcional con los usuarios finales.

El prototipo también permite identificar ajustes necesarios en la experiencia de usuario (UX) y verificar que los requisitos funcionales definidos en las User Stories se reflejen correctamente en las interfaces propuestas.

A continuación, se presenta el enlace para visualizar el video de navegación del prototipo interactivo:

[![Demo](<assets/Chapter-4/mockups-mobile/Inicio de sesión (1).png>)](assets/Chapter-3/Grabación%20de%20pantalla%202025-10-09%20165528.mp4)

### 4.5.1. Android Mobile Applications Prototyping

A continuación, se presenta el enlace para visualizar el video de navegación del prototipo interactivo:

[![Demo](<assets/Chapter-4/mockups-mobile/Dashboard.png>)](assets/Chapter-3/Grabación%20de%20pantalla%202025-10-09%20165528.mp4)

### 4.5.2. iOS Mobile Applications Prototyping

A continuación, se presenta el enlace para visualizar el video de navegación del prototipo interactivo:

[![Demo](<assets/Chapter-4/mockups-mobile/Dashboard.png>)](assets/Chapter-3/Grabación%20de%20pantalla%202025-10-09%20165528.mp4)

## 4.6. Web Applications UX/UI Design

 <img src="assets/Chapter-4/wireframes-web/Register.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/login.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Inicio.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Inventario.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Inventario - Información Producto-1.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Inventario - Nuevo Producto-1.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Inventario - Reposición-1.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Inventario - Nuevo kit-1.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Proveedores.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Proveedores-1.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Administración del personal - Creación personal-1.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Administración del personal - Creación rol.jpg" alt="Web Wireframes" width="800px">
 <img src="assets/Chapter-4/wireframes-web/Salida producto.jpg" alt="Web Wireframes" width="800px">


### 4.6.2. Web Applications Wireflow Diagrams

 <img src="assets/Chapter-4/wireframes-web/flow1.png" alt="Wireflow 1" width="900px">

### User Goal: “Crear cuenta e ingresar a la aplicación”

User persona: Empresa — Administrador
**Happy path**

1. En Regístrate, completa Nombre, Email y Contraseña → pulsa Registrarse.
2. El sistema valida y crea la cuenta (opcional: confirma email).
3. En Iniciar sesión, ingresa Email y Contraseña → Entrar.
4. Accede al Dashboard (métricas y notificaciones cargadas).

**Unhappy paths**

* Email ya registrado o formato inválido → mensaje y bloqueo.
* Contraseña débil/incorrecta → mensaje y reintento.
* Cuenta inactiva/no verificada → aviso con instrucciones.
* Falla de red/sesión → error; el formulario conserva los datos.

<br>

 <img src="assets/Chapter-4//wireframes-web/flow2.png" alt="Wireflow 2" width="900px">

### User Goal: “Crear un nuevo rol para el personal”

User persona: Empresa — Administrador

**Happy path**

1. Desde el Dashboard, abre Administración del personal.
2. Pulsa Nuevo Rol.
3. En el modal, indica Nombre del rol y Permisos (p. ej., Inventario, Compras, Estadísticas, Cuentas).
4. Guardar → el rol se crea y queda disponible para asignarlo a usuarios.

**Unhappy paths**

* Cancelar → no se guarda nada.
* Nombre de rol vacío/duplicado → mensaje y bloqueo.
* Sin permisos seleccionados (si es obligatorio) → aviso para completar.
* Falla de red/sesión → error y preservación del formulario para reintentar.
<br>

### 4.6.3. Web Applications Mock-ups

 <img src="assets/Chapter-4/mockups-web/login-2.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/login-1.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Inventario-1.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Inventario - Información Producto.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Inventario - Nuevo Producto.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Inventario - Reposición.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Inventario - Reposición (1).jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Proveedores-2.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Proveedores-3.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Administración del personal-1.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Administración del personal - Creación Personal.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Administración del personal - Creación roles.jpg" alt="Web Mockups" width="800px">
 <img src="assets/Chapter-4/mockups-web/Salida producto-1.jpg" alt="Web Mockups" width="800px">


<br>

### 4.6.4. Web Applications User Flow Diagrams

 <img src="assets/Chapter-4/mockups-web/flowdiagram1.png" alt="Web Flow Diagram" width="800px">

### User Goal: “Registrar salida de productos (venta/consumo/merma)”

User persona: Tienda/Almacén — Operador(a)
**Happy path**

1. Desde Inicio, abre Salida de productos (barra lateral).
2. En Salida de productos:

   * Busca/filtra por nombre o código (ej. “Bolsa Papitas”).
   * Selecciona uno o varios productos (ve Precio unitario y Stock actual).
   * (Opcional) agrega un Kit desde Kits (p. ej., “Combo Película”).
3. En el panel Borrador salida de productos (derecha):

   * Ajusta la Cantidad por ítem.
   * Se calcula Precio por línea y Total automáticamente.
   * (Opcional) elimina líneas.
4. Guardar:

   * Se valida stock, se registra el movimiento y se descuenta inventario (los kits se desglosan en componentes).


**Unhappy paths**

* Cancelar → se descarta el borrador; no se registra ningún movimiento.
* Cantidad > stock → alerta y bloqueo hasta corregir.

<br>

 <img src="assets/Chapter-4/mockups-web/flowdiagram2.png" alt="Web Flow Diagram" width="800px">
 <img src="assets/Chapter-4/mockups-web/flowdiagram3.png" alt="Web Flow Diagram" width="500px">
 <img src="assets/Chapter-4/mockups-web/flowdiagram4.png" alt="Web Flow Diagram" width="500px">


### User Goal: “Gestionar inventario (ingresar reposición y crear producto)”

User persona: Tienda/Almacén — Operador(a)

A) Ingresar reposición

**Happy path**

1. Desde Inicio, abre Inventario (barra lateral).
2. Revisa Productos y Kits; pulsa Ingresar reposición.
3. En el modal, completa Lote, Fecha de recepción y Fecha de vencimiento.
4. Define Cantidad ingresando por producto; se calcula el Total.
5. Guardar → se registra la reposición, aumenta el stock y se actualizan alertas/métricas.

**Unhappy paths**

* Cancelar → se descarta el formulario, no se registra nada.
* Fechas inválidas (vencimiento < recepción) → error y bloqueo.
* Cantidades inválidas (0, negativas o vacías) → validación en línea.
* Falla de red/sesión → error y preservación del formulario para reintentar.

B) Crear nuevo producto

**Happy path**

1. En Inventario, pulsa + Producto.
2. Completa Nombre, Categoría, Proveedor, Stock mínimo y Precio unitario.
3. Guardar → se crea el producto, aparece en la lista y queda disponible para reposiciones/kits.

**Unhappy paths**

* Cancelar → no se crea el producto.
* Campos obligatorios vacíos** o nombre duplicado → mensaje y bloqueo.
* Valores inválidos (precio ≤ 0, stock mínimo < 0) → validación en línea.
* Falla de red/sesión → error y preservación del formulario.


## 4.7. Web Applications Prototyping

El prototipo web ha sido concebido aplicando principios de arquitectura de información, diseño centrado en el usuario y las heurísticas de usabilidad, con el propósito de brindar una experiencia intuitiva, eficiente y accesible. La navegación se organiza de manera jerárquica y lógica, lo que facilita a los usuarios localizar rápidamente las funciones principales, como el registro de movimientos de inventario, la visualización de reportes y configuración de personal. La interfaz mantiene una disposición visual uniforme, apoyada en una paleta de colores equilibrada y tipografía clara, reforzando la identidad de la plataforma. Los elementos interactivos se han colocado estratégicamente para optimizar la interacción y minimizar la carga cognitiva del usuario. Cada componente del prototipo asegura coherencia visual, visibilidad del estado del sistema y retroalimentación inmediata ante cada acción. Asimismo, se adoptan buenas prácticas y estándares de diseño web contemporáneos para garantizar una experiencia fluida y adaptable en distintos dispositivos.

<https://www.figma.com/proto/jKNuDhwMS5qe3o6zF4ugo8/OPEN-SOURCE?node-id=150-3805&p=f&t=C8AMNn5sgvqnuoFs-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=150%3A5901>

## 4.8. Domain-Driven Software Architecture

### 4.8.1. Software Architecture Context Diagram
 <img src="assets/Chapter-4/c4/SystemContext-001.png" alt="Sytem Context" width="800px">

### 4.8.2. Software Architecture Container Diagrams
 <img src="assets/Chapter-4/c4/Container-001.png" alt="Sytem Container" width="800px">

### 4.8.3. Software Architecture Components Diagrams

- IAM Context
 <img src="assets/Chapter-4/c4/Component-001.png" alt="Sytem Container" width="300px">

 - Product Context
 <img src="assets/Chapter-4/c4/Component-002.png" alt="Sytem Container" width="400px">

 - Inventory Context
 <img src="assets/Chapter-4/c4/Component-003.png" alt="Sytem Container" width="400px">

 - Sales Context
 <img src="assets/Chapter-4/c4/Component-004.png" alt="Sytem Container" width="400px">
 
 - Alert Context
 <img src="assets/Chapter-4/c4/Component-005.png" alt="Sytem Container" width="500px">


## 4.9. Software Object-Oriented Design

### 4.9.1. Class Diagrams

 <img src="assets/Chapter-4/diagramadeclases.png" alt="Sytem Container" width="700px">


### 4.9.2. Class Dictionary
El presente diccionario de clases describe los principales elementos del diagrama de clases de StockWise. Se incluyen entidades del dominio, servicios, repositorios y enumeraciones agrupadas por contexto, con el objetivo de explicar su responsabilidad dentro del sistema.

<br>

### IAM Context

| Clase / Interfaz | Tipo | Descripción | Atributos principales | Métodos principales |
|---|---|---|---|---|
| `User` | Clase | Representa a un usuario registrado en StockWise. Puede ser encargado de ventas, administrador de negocio o configurador del sistema. | `Id`, `Name`, `Email`, `PasswordHash`, `Role`, `IsActive` | `ChangeRole(role)`, `Deactivate()` |
| `UserRole` | Enum | Define los roles disponibles para los usuarios del sistema. | `SalesManager`, `BusinessAdmin`, `SystemConfigurator` | No aplica |
| `IUserService` | Interface | Define las operaciones de negocio relacionadas con usuarios, autenticación y cambio de roles. | No aplica | `SignUp(name, email, password)`, `SignIn(email, password)`, `ChangeUserRole(userId, role)` |
| `IUserRepository` | Interface | Define las operaciones de acceso a datos para usuarios. | No aplica | `FindById(id)`, `FindByEmail(email)`, `Save(user)`, `Update(user)` |


### Product Management Context

| Clase / Interfaz | Tipo | Descripción | Atributos principales | Métodos principales |
|---|---|---|---|---|
| `Product` | Clase | Representa un producto registrado en el catálogo del negocio. Es una de las entidades centrales del sistema. | `Id`, `Name`, `Description`, `Sku`, `SalePrice`, `MinStock`, `IsActive` | `UpdatePrice(price)`, `ChangeMinStock(minStock)`, `Deactivate()` |
| `Category` | Clase | Representa la categoría a la que pertenece un producto. | `Id`, `Name` | No aplica |
| `Unit` | Clase | Representa la unidad de medida utilizada por un producto. | `Id`, `Name`, `Abbreviation` | No aplica |
| `Tag` | Clase | Representa una etiqueta asociada a productos para facilitar su clasificación o búsqueda. | `Id`, `Name` | No aplica |
| `IProductService` | Interface | Define las operaciones de negocio para la gestión del catálogo de productos. | No aplica | `CreateProduct(product)`, `UpdateProduct(product)`, `GetProductById(id)`, `GetAllProducts()` |
| `IProductRepository` | Interface | Define las operaciones de persistencia para productos. | No aplica | `FindById(id)`, `FindAll()`, `Save(product)`, `Update(product)` |


### Inventory Context

| Clase / Interfaz | Tipo | Descripción | Atributos principales | Métodos principales |
|---|---|---|---|---|
| `InventoryItem` | Clase | Representa el stock actual de un producto dentro del inventario. | `Id`, `ProductId`, `CurrentQuantity`, `MinStock`, `Status`, `LastUpdated` | `IncreaseStock(quantity)`, `DecreaseStock(quantity)`, `IsLowStock()` |
| `InventoryMovement` | Clase | Representa un movimiento de inventario, como entrada, salida, ajuste o venta. | `Id`, `ProductId`, `Type`, `Quantity`, `UnitCost`, `MovementDate`, `Reason` | No aplica |
| `MovementType` | Enum | Define los tipos de movimientos que pueden registrarse en el inventario. | `Entry`, `Exit`, `Adjustment`, `Sale` | No aplica |
| `StockStatus` | Enum | Define el estado del stock de un producto. | `Available`, `LowStock`, `OutOfStock` | No aplica |
| `IInventoryService` | Interface | Define las operaciones de negocio relacionadas con el inventario. | No aplica | `RegisterEntry(productId, quantity, cost)`, `RegisterExit(productId, quantity, reason)`, `GetInventoryByProduct(productId)`, `GetLowStock()` |
| `IInventoryRepository` | Interface | Define las operaciones de acceso a datos para el inventario. | No aplica | `FindByProductId(productId)`, `SaveMovement(movement)`, `UpdateStock(item)`, `FindLowStock()` |


### Sales Context

| Clase / Interfaz | Tipo | Descripción | Atributos principales | Métodos principales |
|---|---|---|---|---|
| `Sale` | Clase | Representa una venta realizada dentro del sistema. Contiene información general de la transacción. | `Id`, `SaleDate`, `CustomerName`, `Total`, `Status` | `AddLine(line)`, `CalculateTotal()`, `Cancel()` |
| `SaleLine` | Clase | Representa el detalle de una venta, incluyendo producto, cantidad, precio unitario y subtotal. | `Id`, `ProductId`, `ProductName`, `Quantity`, `UnitPrice`, `Subtotal` | `CalculateSubtotal()` |
| `SaleStatus` | Enum | Define los estados posibles de una venta. | `Created`, `Completed`, `Cancelled` | No aplica |
| `ISalesService` | Interface | Define las operaciones de negocio relacionadas con el registro y consulta de ventas. | No aplica | `RegisterSale(sale)`, `GetSalesByDate(from, to)` |
| `ISaleRepository` | Interface | Define las operaciones de persistencia para ventas. | No aplica | `FindById(id)`, `FindByDate(from, to)`, `Save(sale)` |


### Alert Stock Context

| Clase / Interfaz | Tipo | Descripción | Atributos principales | Métodos principales |
|---|---|---|---|---|
| `StockAlert` | Clase | Representa una alerta generada cuando el stock de un producto está por debajo del mínimo permitido. | `Id`, `ProductId`, `ProductName`, `CurrentStock`, `MinStock`, `Status`, `CreatedAt` | `MarkAsSent()`, `Resolve()` |
| `AlertStatus` | Enum | Define el estado de una alerta de stock. | `Pending`, `Sent`, `Resolved` | No aplica |
| `IAlertService` | Interface | Define la lógica para generar, notificar y resolver alertas de bajo stock. | No aplica | `GenerateLowStockAlerts()`, `NotifyAlert(alert)`, `ResolveAlert(alertId)` |
| `IAlertRepository` | Interface | Define las operaciones de persistencia para las alertas de stock. | No aplica | `FindPending()`, `Save(alert)`, `Update(alert)` |


### Reports Context

| Clase / Interfaz | Tipo | Descripción | Atributos principales | Métodos principales |
|---|---|---|---|---|
| `Report` | Clase | Representa un reporte generado por el sistema, basado en ventas, inventario o categorías. | `Id`, `Type`, `GeneratedAt`, `TotalSales`, `TotalProducts`, `Summary` | No aplica |
| `ReportType` | Enum | Define los tipos de reportes disponibles en StockWise. | `Sales`, `Inventory`, `Category`, `StockAverage` | No aplica |
| `IReportService` | Interface | Define la lógica para generar y consultar reportes del sistema. | No aplica | `GenerateSalesReport(from, to)`, `GenerateInventoryReport()`, `GetReportsByDate(from, to)` |
| `IReportRepository` | Interface | Define las operaciones de persistencia para reportes. | No aplica | `Save(report)`, `FindByDate(from, to)` |


## 4.10. Database Design
### 4.10.1. Relational/Non-Relational Database Diagram

 <img src="assets/Chapter-4/databasediagram.png" alt="Sytem Container" width="800px">


<div style="page-break-after: always;"></div>

# Capitulo V: Product Implementation

## 5.1. Software Configuration Management
En la siguiente sección se describe la ruta de referencia de cada uno de los productos de software para que cualquier miembro del equipo pueda desarrollar cada punto del trabajo.

### 5.1.1. Software Development Environment Configuration
  * **UXPressia:** Plataforma colaborativa que nos permitirá crear user personas e integrarlos con los múltiples mapas para evaluar sus prioridades.
* **Figma:** Herramienta colaborativa que nos permitirá desarrollar wireframes y mockups de la interfaz móvil.
* **Miro:** Plataforma en línea que facilita la colaboración en tiempo real mediante pizarras digitales para crear diagramas, mapas mentales y flujos de trabajo móvil.
* **Lucidchart / Diagrams.net:** Aplicaciones destinadas a la elaboración de Wireflows, User Flows móviles y diagramas de clases.
* **Kotlin and Flutter:** Lenguaje y framework principal utilizado para el desarrollo de la aplicación móvil nativa o híbrida.
* **Jetpack Compose:** Frameworks modernos utilizados para la construcción de la interfaz de usuario móvil mediante componentes declarativos.
* **HTML** Es el lenguaje de marcado que se utiliza para estructurar y organizar el contenido de una página web.
* **CSS** Es el lenguaje de estilos que se utiliza para controlar la apariencia visual de la página.


#### Software Deployment
* **Git:** Herramienta de control de versiones que nos permitirá rastrear cambios, colaborar de manera eficiente y mantener un historial detallado de las modificaciones en el código fuente.
* **GitHub:** Plataforma de alojamiento que facilitará la colaboración en equipo, la gestión de ramas, el seguimiento de issues y la integración continua (CI/CD).



### 5.1.2. Source Code Management
El proyecto seguirá las convenciones de flujo de trabajo establecidas por el modelo **GitFlow** para el control de versiones, utilizando **GitHub** como plataforma y sistema de control de versiones. A continuación, se detallará cómo se implementará GitFlow como Workflow de control de versiones, además de proporcionar los URL de los repositorios de GitHub para cada producto: Landing Page, Web Services y Frontend Web Applications.

*   **Repositorio Landing Page:** [https://github.com/upc-1ASI0732-2610-16879-Stoq/Stoq-LandingPage.git](https://github.com/upc-pre-202510-1asi0730-4366-AyniTech/Landing-Page)
*   **Repositorio Web Services:** [https://github.com/upc-1ASI0732-2610-16879-Stoq/Stoq-Manager-General-BackEnd.git](https://github.com/upc-pre-202510-1asi0730-4366-AyniTech/Web-Services)
*   **Repositorio Mobil Applications:** [https://github.com/upc-1ASI0732-2610-16879-Stoq/MobileAppMobileApp.git](https://github.com/upc-pre-202510-1asi0730-4366-AyniTech/Frontend-Web-Applications)
*   **Repositorio Web Applications:** [https://github.com/upc-1ASI0732-2610-16879-Stoq/Stoq-FrontendWeb.git](https://github.com/upc-pre-202510-1asi0730-4366-AyniTech/Frontend-Web-Applications)

#### GitFlow

**Estructura de branches (Ramas):**

1.  **Master branch (Rama principal):** Esta rama será considerada como la principal para la aplicación, y contendrá versiones estables y finales del desarrollo. Solo se permitirán cambios que hayan sido previamente probados y verificados en otras ramas de prueba.
2.  **Develop branch (Rama de desarrollo):** El propósito de esta rama es llevar a cabo los avances del proyecto en equipo y de mantener los archivos centrales del desarrollo continuo.
3.  **Feature branches (Ramas de funcionalidad):** Cada funcionalidad desarrollada por el equipo o separada del enfoque actual del desarrollo tendrá su propia rama. Una vez que una funcionalidad esté completamente trabajada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, `feature/nombre-de-la-funcionalidad`.
4.  **Release branches (Ramas de lanzamiento):** Estas ramas se utilizarán para mantener una instancia de la rama develop que esté próxima a ser incluida en la rama principal. Se seguirá el sistema de versionamiento semántico (Semantic Versioning) para nombrar las Releases.

**Versionamiento Semántico:**

Para nombrar las Releases, se aplicará el sistema de versionamiento semántico (**Semantic Versioning 2.0.0**).

**Convenciones de Commits:**

Para los mensajes de los commits realizados, se utilizará la especificación **Conventional Commits** basada en *Angular Commit Guidelines*. La estructura a seguir será la siguiente:

`git commit -m "<type>[optional scope]:<title>" -m"<description>"`

### 5.1.3. Source Code Style Guide & Conventions
#### Mobile Development (UI & Logic)
Para garantizar la mantenibilidad de la aplicación móvil, se seguirán las siguientes convenciones:

* **Nomenclatura de Recursos:** Todos los archivos de recursos (iconos, layouts, drawables) deben utilizar `snake_case` (ej. `ic_back_button.xml`, `fragment_login.xml`).
* **Estilo de Código (Kotlin/Swift):** Se seguirá la guía oficial de estilo del lenguaje elegido (ej. Google Kotlin Style Guide). Uso de `camelCase` para variables y funciones, y `PascalCase` para clases.
* **Arquitectura:** Se implementará el patrón **MVVM (Model-View-ViewModel)** para separar la lógica de negocio de la interfaz de usuario.
* **Gestión de Strings:** No se debe escribir texto directamente ("hardcoded") en la interfaz. Todos los textos deben estar definidos en archivos de recursos de strings para facilitar la localización (multi-idioma).
* **Componentes Reutilizables:** Se priorizará la creación de componentes de UI pequeños y reutilizables para mantener la consistencia visual en todas las pantallas de la app.

* **Sintaxis de Elementos HTML:** Todos los elementos deben cerrarse obligatoriamente para garantizar un código coherente y ordenado (ej. `<p>Esto es un párrafo.</p>`).
* **Nomenclatura y Case Sensitivity:** Se limitará el uso de minúsculas en nombres de elementos y atributos, evitando combinar mayúsculas para mantener la legibilidad y el orden.
* **Atributos y Comillas:** Se deben utilizar comillas en los atributos, especialmente en casos donde existan espacios entre los valores.
* **Disponibilidad de Contenido (Multimedia):** Es obligatorio especificar el texto `alt` y las dimensiones `width` y `height` en las imágenes para facilitar la disponibilidad y carga del contenido.
* **Nomenclatura CSS:** Los nombres de las clases deben ser breves, autodescriptivos y utilizar guiones para separar palabras (ej. `#video-id`, `.hero-shadow`).
* **Optimización de Unidades:** Se debe evitar especificar la unidad de medida (px, %, em) cuando el valor utilizado sea `0`.
* **Legibilidad y Estructura CSS:** Las declaraciones y selectores deben separarse en nuevas líneas para agilizar la lectura y el mantenimiento del código.

### 5.1.4. Software Deployment Configuration
Para el despliegue de la Landing Page, es necesario contar con una cuenta de GitHub, una organización establecida y un repositorio dedicado. El proceso de despliegue se realizará aprovechando las capacidades de **GitHub Pages**. A continuación, se detallan los requisitos y pasos a seguir:

#### Requisitos de Estructura
Para un despliegue correcto, el repositorio debe mantener la siguiente estructura de archivos y nomenclaturas:
* **index.html**: Archivo principal que contiene la estructura y contenido de la landing page.
* **style.css**: Archivo que contiene las hojas de estilo del sitio.
* **assets/**: Carpeta raíz para recursos multimedia.
    * **img/**: Subcarpeta dedicada exclusivamente a las imágenes del sitio.

#### Pasos para el Despliegue
1. **Creación del Repositorio:** Crear un repositorio específico dentro de la organización de GitHub para alojar exclusivamente el código de la Landing Page.
2. **Carga de Archivos:** Subir los archivos siguiendo la estructura mencionada anteriormente mediante un `commit` inicial a la rama principal.
3. **Configuración de GitHub Pages:** 
   * Dirigirse a la sección de **Settings** del repositorio.
   * En el menú lateral, seleccionar **Pages**.
   * En el apartado "Build and deployment", seleccionar la rama correspondiente (generalmente `main` o `master`) y la carpeta raíz (`/root`).
4. **Verificación y Lanzamiento:** 
   * Esperar a que GitHub realice las comprobaciones automáticas (*GitHub Actions*). 
   * Una vez culminado el proceso, GitHub proporcionará una URL pública (ej. `https://nombre-organizacion.github.io/repo-name/`) donde la Landing Page estará oficialmente desplegada.

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs
A continuación, se detallan los Sprint Backlogs trabajados a lo largo del desarrollo de la plataforma Stoq. La planificación abarca desde la configuración inicial y desarrollo del núcleo móvil, hasta la integración de funcionalidades avanzadas como geolocalización y escaneo por código de barras.

### Sprint 1: Núcleo Móvil, APIs Base y Landing Page

El objetivo de este primer sprint fue establecer la infraestructura base, desarrollar los servicios de autenticación y construir los módulos principales de gestión de inventario para la aplicación móvil.

| Story Id | Story Title | Task Id | Task Title | Description | Est. (Hrs) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| TS02 | APIs IAM | TSK-11 | Endpoint de Login | Desarrollo de los endpoints para emisión de JWT y validación de credenciales. | 4 | Luciana Choquehuanca | Done |
| US01 | Registro de Producto | TSK-01 | Formulario de Productos | Interfaz móvil para crear productos con validación de campos obligatorios. | 6 | Fabiola Saldaña | Done |
| TS03 | APIs Product | TSK-12 | Endpoint de Creación | Construcción del endpoint para almacenar nuevos productos y validar unicidad. | 5 | Roy Fernandez | Done |
| US06 | Búsqueda en Inventario | TSK-05 | Filtros Avanzados | Implementación de barra de búsqueda en tiempo real por nombre o código. | 5 | Sanchez Camila | Done |
| US12 | Reportes Base | TSK-08 | Vista de Estadísticas | Visualización de reportes por fecha/categoría y exportación a PDF. | 6 | Ronald Peralta | Done |
| US17 | Registro por Lotes | TSK-09 | Ingreso Masivo | Interfaz para registro de lotes de productos con proveedor y fecha de vencimiento. | 5 | Fabiola Saldaña | Done |



### Sprint 2: Funcionalidades Avanzadas y Alertas

Durante este sprint, el equipo se enfocó en optimizar el flujo de inventario, integrando sistemas de alertas tempranas, gestión de roles y la exploración de comandos por voz.

| Story Id | Story Title | Task Id | Task Title | Description | Est. (Hrs) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| US19 | Alertas de Stock | TSK-27 | Lógica de Notificaciones | Sistema de alertas automáticas en la app cuando el stock cae por debajo del mínimo. | 5 | Ronald Peralta | Done |
| US22 | Alertas de Caducidad | TSK-28 | Control de Vencimientos | Detección de productos perecibles próximos a vencer con alertas visuales. | 5 | Fabiola Saldaña | Done |
| US18 | Historial de Movimientos | TSK-26 | Gráficas de Evolución | Construcción de la vista histórica con filtros de periodo y gráficas de stock. | 5 | Roy Fernandez | Done |
| US15 | Configuración de Roles | TSK-24 | Gestión de Usuarios | Pantalla móvil para administrar accesos (Admin/Empleado) vinculada al backend. | 5 | Sanchez Camila | Done |
| US16 | Proveedores | TSK-25 | Directorio de Contactos | Módulo para registrar y enlazar proveedores con los lotes de ingreso. | 5 | Luciana Choquehuanca | Done |
| US14 | Devoluciones | TSK-23 | Flujo de Retornos | Funcionalidad para registrar mermas o devoluciones actualizando el stock central. | 5 | Ronald Peralta | Done |
| SPK01 | Innovación UX | TSK-31 | Entrada por Voz (Spike) | Prototipo de integración Speech-to-Text para comandos básicos de inventario. | 6 | Luciana Choquehuanca | In-Process |
| US01 | Gestión de Productos (Web) | TSK-W03 | Web Inventory CRUD | Desarrollo de las tablas de gestión de productos (Crear, Editar, Listar) en la versión Web. | 7 | Fabiola Saldaña | Done |

### Sprint 3: Integración de Hardware, Geolocalización y Cierre

El último sprint culminó el desarrollo con el acceso al dispositivo (GPS), mejoras de seguridad y las pruebas integrales y unitarias de calidad.

| Story Id | Story Title | Task Id | Task Title | Description | Est. (Hrs) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| TS07 | Quality Assurance | TSK-38 | Testing Final | Pruebas de integración E2E validando la comunicación completa entre app y API. | 6 | Luciana Choquehuanca | Done |
| US31 | Escáner de Barras | TSK-33 | Lector de Cámara | Integración de la cámara del dispositivo móvil para escanear y registrar ventas. | 6 | Sanchez Camila | Done |
| US27 | Ubicación | TSK-34 | Geolocalización de Sedes | Integración de mapas para gestionar ubicaciones de sedes y almacenes. | 5 | Roy Fernandez | Done |
| US33 | Legal & Compliance | TSK-35 | Términos y Condiciones | Checkbox y vista de aceptación obligatoria de T&C durante el proceso de registro. | 4 | Fabiola Saldaña | Done |
| US34 | Seguridad IAM | TSK-36 | Restricciones de Acceso | Aplicación estricta de permisos por rol en las pantallas críticas de la app. | 5 | Ronald Peralta | Done |
| US32 | Optimización UI/UX | TSK-37 | Refinamiento Visual | Mejoras finales en la interfaz, optimización de tiempos y fluidez de navegación. | 4 | Sanchez Camila | Done |

### 5.2.2. Implemented Landing Page Evidence
En esta sección se presenta la evidencia visual de la Landing Page oficial de Stoq, la cual sirve como el punto de contacto principal para los clientes potenciales. La página ha sido diseñada bajo un enfoque de conversión, resaltando la propuesta de valor de la plataforma (gestión inteligente y movilidad) e integrando internacionalización (i18n) para soportar múltiples idiomas. Se incluyen capturas de las secciones clave: Hero Section, Beneficios, Planes de Suscripción y Footer.

![Landing Page](./assets/Chapter-5/landing_1.png)

Link: [https://landing_page.com](https://stockwiselanding.netlify.app/)

### 5.2.3. Implemented Frontend-Web Application Evidence
Se detallan a continuación las interfaces que componen el Dashboard Web de Administración. Este componente está orientado al dueño de negocio o administrador, permitiendo una gestión centralizada y profunda del inventario que complementa la operación móvil. Las capturas muestran el panel de control con métricas en tiempo real, la tabla de gestión de productos con opciones avanzadas de filtrado y el módulo de administración de usuarios para la asignación de roles.

![Front_app](./assets/Chapter-5/front_app.png)

Link: [https://front_app.com](https://stocktrack-frontend.vercel.app/auth/register)

### 5.2.4. Acuerdo de Servicio - SaaS
El presente Acuerdo de Servicio regula los términos y condiciones bajo los cuales los usuarios acceden y utilizan la plataforma Stoq, una solución SaaS (Software as a Service) desarrollada para optimizar la gestión de inventarios y control de stock en pequeñas y medianas empresas (pymes), startups y bodegas especializadas en el Perú.

Este acuerdo se incorpora como parte integral de los "Términos y Condiciones" disponibles en el sitio web oficial de Stoq, y su aceptación es obligatoria para completar el registro y uso de las aplicaciones web y móviles.

#### 1. Definiciones
"Plataforma": Ecosistema compuesto por la aplicación móvil (Kotlin/Flutter), el dashboard web y el backend operado por el equipo de desarrollo de Stoq.

"Usuario": Persona natural o jurídica que accede a la plataforma en calidad de Administrador o Empleado.

"Comercio/Pyme": Negocio registrado que utiliza Stoq para la gestión de sus activos y mercadería.

"Cuenta": Perfil de acceso individual vinculado a una organización específica.

"Plan": Modalidad de suscripción (Freemium o Premium) que determina las funcionalidades activas y límites de registros.

#### 2. Objeto del Acuerdo
Stoq concede al usuario una licencia limitada, no exclusiva, intransferible y revocable para utilizar la plataforma exclusivamente con fines de gestión operativa de inventarios, logística y administración de ventas internas.

#### 3. Registro y Acceso
El uso de la plataforma requiere la creación de una cuenta mediante el formulario de registro oficial.

Cada usuario es responsable de la confidencialidad de sus credenciales (correo y contraseña) y del uso que se realice bajo su sesión.

Stoq se reserva el derecho de suspender o eliminar cuentas que realicen actividades fraudulentas o infrinjan la integridad del sistema.

#### 4. Tarifas y Planes
La plataforma opera bajo un modelo de suscripción SaaS. El Plan Premium permite el acceso a funciones avanzadas como el escaneo por código de barras, geolocalización de sedes y reportes de analítica profunda.

Las suscripciones se renuevan automáticamente al finalizar el periodo contratado, a menos que el usuario gestione la cancelación antes del vencimiento.

Ante el impago del servicio, Stoq se reserva el derecho de restringir el acceso a las funciones premium, manteniendo la cuenta en modo de consulta o bajo las limitaciones del plan gratuito.

#### 5. Propiedad Intelectual
Todos los derechos sobre la plataforma, incluyendo código fuente (Backend, Web y Mobile), diseño de interfaces (UI), marcas y algoritmos de predicción pertenecen exclusivamente al equipo de desarrollo de Stoq.

#### 6. Uso Aceptable
Queda expresamente prohibido:

- Manipular el código fuente o intentar realizar ingeniería inversa sobre las aplicaciones.

- Utilizar la plataforma para el registro de productos o actividades ilícitas según la normativa peruana.

- Interferir con la operación técnica de los Web Services o realizar ataques de denegación de servicio.

#### 7. Protección de Datos y Privacidad
Stoq garantiza el cumplimiento estricto de la Ley N.º 29733 - Ley de Protección de Datos Personales del Perú.

Los datos de inventario y personales serán tratados únicamente para fines operativos y estadísticos de la plataforma.

Los usuarios tienen derecho a acceder, rectificar o suprimir sus datos mediante los canales de soporte establecidos.

Se emplean medidas de seguridad técnicas (encriptación y tokens JWT) para proteger la información almacenada.

#### 8. Disponibilidad del Servicio
Stoq busca mantener una alta disponibilidad del servicio (99.5%). No obstante, el acceso puede interrumpirse temporalmente por mantenimientos programados o fallas en servicios de terceros (hosting/nube).

#### 9. Limitación de Responsabilidad
Stoq no se responsabiliza por errores en el conteo físico de productos, decisiones financieras basadas en los reportes generados o pérdidas de mercadería derivadas de un mal uso de la plataforma por parte del usuario.

#### 10. Modificaciones del Acuerdo
Stoq podrá actualizar este acuerdo para reflejar nuevas funcionalidades o cambios legales. Se notificará a los usuarios con al menos 5 días de anticipación a través de la aplicación o correo electrónico registrado.

### 5.2.5. Implemented Native-Mobile Application Evidence
Este apartado presenta la evidencia de la implementación de la aplicación móvil nativa. Se muestran capturas de la interfaz y funcionalidades principales, destacando la interacción del usuario y el correcto funcionamiento de la aplicación en el entorno móvil.

![Native-Mobile](./assets/Chapter-5/mobile_1.png)
![Native-Mobile](./assets/Chapter-5/mobile_2.png)

### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence
Este apartado muestra la evidencia de la implementación de una API RESTful, documentada mediante Swagger. Se presentan los endpoints disponibles, sus métodos HTTP, parámetros y respuestas, lo que facilita la comprensión, prueba e integración del backend del sistema.

![RESTful API](./assets/Chapter-5/swagger_1.png)
![RESTful API](./assets/Chapter-5/swagger_2.png)

Link: [https://stoq-web-backend.onrender.com/swagger-ui.html](https://stoq-web-backend.onrender.com/swagger-ui.html)

### 5.2.7. RESTful API documentation
La documentación de la API RESTful fue generada mediante **Swagger / OpenAPI**, accesible desde el entorno de desarrollo. A continuación se detallan todos los endpoints disponibles, agrupados por módulo funcional.

---

#### Authentication
*Gestión de autenticación y roles de usuario.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `POST` | `/api/v1/authentication/sign-up` | Registrar una nueva cuenta de usuario |
| `POST` | `/api/v1/authentication/sign-in` | Autenticar e iniciar sesión |
| `PUT` | `/api/v1/authentication/change-role` | Cambiar el rol de un usuario |

---

#### Products
*Puntos de acceso disponibles para la gestión de productos.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/v1/products/{productId}` | Obtener Producto por Id |
| `POST` | `/api/v1/products` | Crear Producto |
| `GET` | `/api/v1/products` | Obtener todos los Productos |
| `GET` | `/api/v1/products/by-category/{categoryId}` | Obtener Productos por Categoría |
| `GET` | `/api/v1/products/by-tag/{tagId}` | Obtener Productos por Etiqueta |

---

#### Combos
*Puntos de acceso disponibles para la gestión de combos (kits).*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/v1/combos/{comboId}` | Obtener Combo por Id |
| `POST` | `/api/v1/combos` | Crear Combo |
| `GET` | `/api/v1/combos` | Obtener todos los Combos |

---

#### Tags
*Puntos de acceso para la gestión de etiquetas.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/v1/tags` | Obtener todas las etiquetas |

---

#### Units
*Puntos de acceso para la gestión de unidades de medida.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/v1/units` | Obtener todas las unidades de medida |

---

#### Sales
*Operaciones de ventas con integración automática de inventario y reportes.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `POST` | `/api/v1/sales` | Realizar venta con stock automático |
| `GET` | `/api/v1/sales/{id}` | Obtener venta por ID |
| `GET` | `/api/v1/sales/check-stock/{productId}` | Verificar stock disponible |

---

#### Inventory
*Operaciones del inventario general, por producto y por lote.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/v1/inventory` | Obtener todos los registros de inventario |
| `POST` | `/api/v1/inventory/by-product` | Crear Inventario por Producto |
| `GET` | `/api/v1/inventory/by-product` | Listar todos los Inventarios por Producto con filtros |
| `GET` | `/api/v1/inventory/by-product/{id}` | Obtener Inventario por Producto por ID |
| `DELETE` | `/api/v1/inventory/by-product/{id}` | Eliminar Inventario por Producto por ID |
| `POST` | `/api/v1/inventory/by-batch` | Crear Inventario por Lote |
| `GET` | `/api/v1/inventory/by-batch` | Listar todos los Inventarios por Lote con filtros |
| `GET` | `/api/v1/inventory/by-batch/{id}` | Obtener Inventario por Lote por ID |
| `DELETE` | `/api/v1/inventory/by-batch/{id}` | Eliminar Inventario por Lote por ID |

---

#### StockAlert
*Gestión de alertas de stock y nivel de inventario.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/alerts` | Obtener alertas de stock |
| `GET` | `/api/alerts/by-category` | Obtener alertas por categoría |
| `GET` | `/api/alerts/summary` | Obtener resumen de alertas |

---

#### Report
*Puntos de acceso disponibles para la gestión de reportes de categoría y de stock promedio.*

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/v1/reports` | Obtener todos los reportes generales |
| `POST` | `/api/v1/reports/category` | Crear CategoryReport |
| `GET` | `/api/v1/reports/category` | Listar CategoryReports |
| `GET` | `/api/v1/reports/category/{id}` | Obtener CategoryReport por ID |
| `GET` | `/api/v1/reports/category/by-date` | Filtrar CategoryReports por fecha |
| `POST` | `/api/v1/reports/stock-average` | Crear StockAverageReport |
| `GET` | `/api/v1/reports/stock-average` | Listar StockAverageReports |
| `GET` | `/api/v1/reports/stock-average/{id}` | Obtener StockAverageReport por ID |
| `GET` | `/api/v1/reports/stock-average/by-date` | Filtrar StockAverageReports por fecha |

### 5.2.8. Team Collaboration Insights

**Enlace de los repositorios de la organización**<br>

Link: [https://github.com/upc-1ASI0732-2610-16879-Stoq](https://github.com/upc-1ASI0732-2610-16879-Stoq)


**TP:**
- Reporte<br>
 <img src="assets/Chapter-5/insight-tp-report1.png" alt="Insight TP" width="500px"><br>
 <img src="assets/Chapter-5/insight-tp-report.png" alt="Insight TP" width="500px">
<br>
- Landing Page<br>
  <img src="assets/Chapter-5/insight-tp-landing1.png" alt="Insight TP" width="500px"><br>
  <img src="assets/Chapter-5/insight-tp-landing.png" alt="Insight TP" width="500px">
<br>
- Backend <br>
   <img src="assets/Chapter-5/insight-tp-back1.png" alt="Insight TP" width="500px"><br>
   <img src="assets/Chapter-5/insight-tp-back.png" alt="Insight TP" width="500px"><br>
- Frontend <br>
  <img src="assets/Chapter-5/insight-tp-front1.png" alt="Insight TP" width="500px"><br>
  <img src="assets/Chapter-5/insight-tp-front.png" alt="Insight TP" width="500px">

## 5.3. Video About-the-Product
StockWise es una aplicación digital y móvil creada para optimizar la gestión de inventarios, permitiendo controlar de manera automática los vencimientos, los niveles mínimos de stock y la organización de kits de productos. Su propuesta está dirigida principalmente a pequeños y medianos negocios, ofreciéndoles una solución práctica, económica y sencilla de utilizar, con el objetivo de disminuir pérdidas y mejorar la toma de decisiones.

A través de la aplicación, los usuarios pueden escanear productos directamente desde su celular, recibir notificaciones anticipadas cuando un artículo está próximo a agotarse o vencer, y acceder a un panel en tiempo real con métricas importantes y reportes completos. En el video se observa cómo el usuario registra productos, verifica el estado del inventario y confirma pedidos de forma rápida con un solo toque, evidenciando la eficiencia y facilidad de uso del sistema. Según comenta uno de los usuarios: “StockWise me ha ayudado a mantener mi inventario organizado sin invertir demasiado tiempo; ahora todo está al alcance de un clic y nunca más se me venció un producto”.

![RESTful API](./assets/Chapter-5/aboutProduct.png)

Link: [https://Video_About_Product.com](https://youtu.be/OPvuExjrxCY)

<div style="page-break-after: always;"></div>

<div style="page-break-after: always;"></div>

# Part II: Verification, Validation & Pipeline

# Capitulo VI: Product Verification & Validation

## 6.1. Testing Suites & Validation

### 6.1.1. Core Entities Unit Tests

Se muestra evidencia de los test a las historios de usuario del proyecto

US01 - Crear producto válido: valida que el agregado Product se construye correctamente con datos completos y normaliza los valores de texto.

<img src="assets/Chapter-6/core unit tests 1.png" alt="Product Registration Feature File" width="800px">

US01 / US19 - Stock inicial y mínimo: valida que minStock acepta valores válidos, incluyendo cero, y rechaza negativos.

<img src="assets/Chapter-6/core unit tests 2.png" alt="Product Registration Feature File" width="800px">

US19 - Configurar stock mínimo: valida que el producto permita actualizar el límite mínimo de stock correctamente.

<img src="assets/Chapter-6/core unit tests 3.png" alt="Product Registration Feature File" width="800px">

US03 - Registrar salida de producto: valida que Batch descuenta stock correctamente al registrar una salida.

<img src="assets/Chapter-6/core unit tests 4.png" alt="Product Registration Feature File" width="800px">

US14 - Registrar devolución: valida que el stock aumente al registrar una devolución.

<img src="assets/Chapter-6/core unit tests 5.png" alt="Product Registration Feature File" width="800px">

### 6.1.2. Core Integration Tests
En esta sección se presentan las pruebas de integración desarrolladas para validar la correcta comunicación e interacción entre los componentes principales de StockWise, garantizando el funcionamiento coordinado y consistente de los distintos módulos que conforman el sistema.

**Información General Test-1**

| Elemento | Descripción |
|---|---|
| Clase de Test | `ProductControllerIntegrationTest` |
| Módulo(s) | inventory, shared, iam - US12, US13 |
| Descripción General | Validar la integración completa del módulo de productos dentro del sistema StockWise, comprobando que las operaciones relacionadas con la gestión de productos funcionen correctamente desde la capa HTTP hasta la persistencia en base de datos. |


**Escenario 1**
| Evidencia | Descripción |
|---|---|
| ![Escenario 1](./assets/Chapter-6/test1_sc1.png)  | Este escenario valida que el sistema pueda registrar correctamente un nuevo producto cuando se envían datos válidos, verificando el flujo completo desde la solicitud HTTP hasta la persistencia en base de datos. Se comprueba la integración entre controller, servicios de aplicación, aggregate Product, repositorios JPA y la base de datos H2. Esta validación es importante porque asegura que la funcionalidad principal de creación de productos opere correctamente y que la información registrada mantenga consistencia dentro del inventario. |

**Escenario 2**

| Evidencia | Descripción |
|---|---|
| ![Escenario 2](./assets/Chapter-6/test1_sc2.png) | Este escenario valida que el sistema rechace productos con un precio unitario inválido, específicamente valores negativos, comprobando que las reglas de negocio definidas en el dominio sean respetadas antes de persistir información. La prueba garantiza que las validaciones del aggregate y el manejo de excepciones funcionen correctamente a través de toda la integración del sistema. Esto es importante para proteger la integridad de los datos financieros y evitar inconsistencias en cálculos de ventas, reportes y valorización de inventario. |

**Escenario 3**
| Evidencia | Descripción |
|---|---|
| ![Escenario 3](./assets/Chapter-6/test1_sc3.png) | Este escenario verifica que el sistema no permita registrar productos sin nombre o con nombres vacíos, validando las restricciones obligatorias del dominio y el correcto manejo de respuestas HTTP ante entradas inválidas. La prueba asegura que los datos esenciales del catálogo sean obligatorios y que el sistema prevenga registros incompletos que puedan afectar búsquedas, clasificación de productos y operaciones posteriores dentro del inventario.|

**Escenario 4** 

| Evidencia | Descripción |
|---|---|
| ![Escenario 4](./assets/Chapter-6/test1_sc4.png) | Este escenario valida que el sistema pueda actualizar correctamente la información de un producto existente, verificando la integración entre el endpoint REST, los servicios de actualización, el aggregate Product, el repositorio JPA y la persistencia en base de datos. Se comprueba que los cambios enviados sean reflejados correctamente y que las validaciones del dominio continúen aplicándose durante la edición. Esta validación es importante porque garantiza que la información del catálogo pueda mantenerse actualizada y consistente a lo largo del tiempo. |

---
**Información General Test-2**

| Elemento | Descripción |
|---|---|
| Clase de Test | `ProviderProductIntegrationTest` |
| Módulo(s) | inventory, shared - US24, US26 |
| Descripción General | Validar la integración entre los módulos de proveedores y productos, asegurando que las relaciones funcionales entre ambos aggregates se comporten correctamente dentro del sistema. |


**Escenario 1** 

| Evidencia | Descripción |
|---|---|
| ![Escenario 1](./assets/Chapter-6/test2_sc1.png) | Este escenario valida que el sistema pueda registrar correctamente un nuevo proveedor utilizando datos válidos, comprobando el flujo completo desde la solicitud HTTP hasta la persistencia en base de datos. La prueba verifica la integración entre controller, servicios de aplicación, aggregate Provider, value objects, repositorios JPA y la base de datos H2. Esta validación es importante porque garantiza que los proveedores puedan ser gestionados correctamente y que la información crítica de abastecimiento quede almacenada de manera consistente y segura. |

**Escenario 2**

| Evidencia | Descripción |
|---|---|
| ![Escenario 2](./assets/Chapter-6/test2_sc2.png) | Este escenario valida que el sistema rechace proveedores con correos electrónicos inválidos, comprobando que las reglas de validación implementadas en los value objects del dominio funcionen correctamente durante todo el flujo de integración. La prueba asegura que las excepciones generadas por datos inconsistentes sean manejadas adecuadamente y que la información inválida no llegue a persistirse en la base de datos. Esta validación es importante porque protege la calidad de los datos y evita problemas posteriores relacionados con notificaciones, contacto con proveedores y trazabilidad del sistema. |

**Escenario 3**

| Evidencia | Descripción |
|---|---|
| ![Escenario 3](./assets/Chapter-6/test2_sc3.png) | Este escenario valida la integración funcional entre los módulos de productos y proveedores, verificando que un producto solo pueda registrarse cuando se encuentra asociado a un proveedor existente dentro del sistema. La prueba comprueba la interacción entre múltiples aggregates, servicios de aplicación, repositorios y validaciones de negocio relacionadas con integridad referencial. Esta validación es importante porque asegura consistencia entre entidades del inventario y evita relaciones inválidas que puedan afectar procesos de compras, abastecimiento y trazabilidad de productos. |

---

**Información General Test-3**

| Elemento | Descripción |
|---|---|
| Clase de Test | `MovementControllerIntegrationTest` |
| Módulo(s) | inventory, sales - US03, US14 |
| Descripción General | Validar la integración entre los módulos de inventario y ventas, comprobando que los movimientos de entrada y salida de stock actualicen correctamente la cantidad disponible en base de datos, y que el sistema rechace operaciones que excedan el stock disponible. |

**Escenario 1**

| Evidencia | Descripción |
|---|---|
| ![Escenario 1](./assets/Chapter-6/test3_sc1.png) | Este escenario valida que el sistema descuente correctamente el stock de un producto cuando se registra una venta válida, verificando el flujo completo desde la solicitud HTTP hasta la persistencia en base de datos H2. Se comprueba la integración entre el controlador de ventas, los servicios de aplicación, el repositorio de lotes y la lógica de descuento del aggregate. Esta validación es importante porque garantiza que cada transacción de salida mantenga la consistencia del inventario y refleje el stock real disponible para operaciones posteriores. |

**Escenario 2**

| Evidencia | Descripción |
|---|---|
| ![Escenario 2](./assets/Chapter-6/test3_sc2.png) | Este escenario valida que el sistema incremente correctamente el stock de un producto cuando se registra un lote de reposición, comprobando la integración entre el endpoint de lotes, los servicios de aplicación, el repositorio JPA y la base de datos H2. La prueba verifica que la cantidad del nuevo lote se sume correctamente al stock existente del producto. Esta validación es importante porque asegura que el proceso de reabastecimiento opere de forma confiable y que el inventario refleje en todo momento las entradas registradas por el equipo de almacén. |

**Escenario 3**

| Evidencia | Descripción |
|---|---|
| ![Escenario 3](./assets/Chapter-6/test3_sc3.png) | Este escenario verifica que el sistema rechace una solicitud de venta cuya cantidad supera el stock disponible del producto, comprobando que las reglas de negocio del dominio sean aplicadas correctamente antes de persistir cualquier cambio. La prueba garantiza que el sistema retorne un error HTTP 400 ante este tipo de operación inválida. Esta validación es importante porque protege la integridad del inventario y evita que el sistema registre ventas que no pueden ser satisfechas con el stock existente. |

---

**Información General Test-4**

| Elemento | Descripción |
|---|---|
| Clase de Test | `StockAlertIntegrationTest` |
| Módulo(s) | inventory, alertstock - US05 |
| Descripción General | Validar la integración entre los módulos de inventario y alertas de stock, comprobando que el sistema genere y persista automáticamente una alerta cuando una salida de stock deja el nivel por debajo del mínimo configurado, y que no genere alertas innecesarias cuando el stock se mantiene dentro del rango aceptable. |

**Escenario 1**

| Evidencia | Descripción |
|---|---|
| ![Escenario 1](./assets/Chapter-6/test4_sc1.png) | Este escenario valida que el sistema genere y persista automáticamente una alerta de stock bajo cuando una venta reduce el inventario por debajo del mínimo configurado para el producto, comprobando la integración entre el módulo de ventas, el servicio de alertas y el repositorio de alertas en base de datos H2. Esta validación es importante porque garantiza que el mecanismo de alerta temprana funcione de forma automática y confiable, permitiendo al equipo de almacén reaccionar oportunamente ante situaciones de desabastecimiento. |

**Escenario 2**

| Evidencia | Descripción |
|---|---|
| ![Escenario 2](./assets/Chapter-6/test4_sc2.png) | Este escenario verifica que el sistema no genere alertas de stock cuando una salida de inventario deja el nivel igual o por encima del mínimo configurado, comprobando que la lógica de disparo de alertas sea precisa y no produzca falsos positivos. La prueba consulta directamente el repositorio de alertas para confirmar que ningún registro fue persistido. Esta validación es importante porque evita que el equipo de almacén reciba notificaciones innecesarias que puedan generar ruido operativo y reducir la efectividad del sistema de alertas. |

---

**Información General Test-5**

| Elemento | Descripción |
|---|---|
| Clase de Test | `IamInventoryIntegrationTest` |
| Módulo(s) | iam, inventory - US01, US12 |
| Descripción General | Validar la integración entre el módulo de autenticación y autorización (IAM) y los endpoints de inventario, comprobando que el sistema proteja correctamente el acceso a los recursos según el token y los permisos del usuario autenticado. |

**Escenario 1**

| Evidencia | Descripción |
|---|---|
| ![Escenario 1](./assets/Chapter-6/test5_sc1.png) | Este escenario valida que el sistema rechace con HTTP 401 cualquier solicitud al endpoint de productos que no incluya un token de autenticación, comprobando que los filtros de seguridad estén activos y configurados correctamente. Esta validación es importante porque garantiza que los recursos del inventario estén protegidos frente a accesos anónimos y que el sistema cumpla con los requisitos de seguridad definidos para la plataforma SaaS. |

**Escenario 2**

| Evidencia | Descripción |
|---|---|
| ![Escenario 2](./assets/Chapter-6/test5_sc2.png) | Este escenario valida que un usuario autenticado con permisos de inventario pueda acceder correctamente al endpoint de productos, recibiendo una respuesta HTTP 200 con el listado correspondiente. La prueba comprueba la integración completa entre el proceso de registro, la generación del token JWT y la autorización en el endpoint protegido. Esta validación es importante porque asegura que el flujo de autenticación funcione de extremo a extremo y que los usuarios con los permisos correctos puedan operar sin restricciones. |

**Escenario 3**

| Evidencia | Descripción |
|---|---|
| ![Escenario 3](./assets/Chapter-6/test5_sc3.png) | Este escenario verifica que un usuario autenticado pero sin permisos de inventario reciba una respuesta HTTP 403 al intentar acceder al endpoint de productos, comprobando que el sistema aplique correctamente las reglas de autorización por rol. La prueba crea un usuario con acceso exclusivo a ventas e intenta acceder a un recurso restringido. Esta validación es importante porque garantiza el principio de mínimo privilegio en la plataforma, protegiendo los datos del inventario frente a accesos no autorizados de usuarios con roles insuficientes. |

### 6.1.3. Core Behavior-Driven Development

En esta sección se presentan las pruebas Behavior-Driven Development desarrolladas para validar el comportamiento esperado de las funcionalidades principales de StockWise desde la perspectiva del usuario. El desarrollo de estas pruebas se basó en las User Stories priorizadas del Product Backlog, específicamente US01 - Registrar producto nuevo y US05 - Generar alertas por bajo stock, ambas pertenecientes al epic EP01 - Funciones básicas de inventario. Estas historias fueron seleccionadas porque representan funciones centrales del sistema de inventario.

**Evidence 1: Product Registration Feature File**

<img src="assets/Chapter-6/prueba-3.png" alt="Product Registration Feature File" width="800px">

**Evidence 2: Low Stock Alert Feature File**

<img src="assets/Chapter-6/prueba-2.png" alt="Low Stock Alert Feature File" width="800px">

**Evidence 3: BDD Test Execution Results**

<img src="assets/Chapter-6/prueba-1.png" alt="BDD Test Execution Results" width="800px">


### 6.1.4. Core System Tests

<img src="assets/Chapter-6/core-system-gherkin.png" alt="Core system test gherkin" width="800px">

<img src="assets/Chapter-6/core-system-test1.png" alt="Core system test 1" width="800px">

<img src="assets/Chapter-6/core-system-test-evidencia.png" alt="Core system test 1 evidence" width="800px">

## 6.2. Static testing & Verification 
Esta sección describe las actividades de control de calidad que se ejecutan directamente sobre el código fuente, especificaciones y artefactos del proyecto sin necesidad de poner el sistema en marcha. Su objetivo es identificar de manera temprana ambigüedades, defectos de diseño, vulnerabilidades de seguridad y desviaciones de las pautas de desarrollo establecidas.

### 6.2.1. Static Code Analysis

Consiste en la evaluación automatizada del código base utilizando herramientas especializadas. A través de este análisis se audita la mantenibilidad, el cumplimiento de reglas sintácticas, la deuda técnica y los posibles riesgos de seguridad antes de que el código sea integrado a las ramas principales del repositorio.

#### 6.2.1.1. .Coding standard & Code conventions

**Backend - Java/Spring Boot** <br>
El backend implementa convenciones de código rigurosas basadas en los estándares oficiales de Spring Framework y las mejores prácticas de la arquitectura limpia. La nomenclatura sigue patrones semánticos y descriptivos: los controladores utilizan el sufijo Controller, los servicios emplean Service o la distinción CommandService / QueryService para segregar las operaciones de lectura y escritura (patrón CQRS), y los componentes de transformación adoptan el sufijo Assembler para la conversión eficiente entre entidades del dominio y recursos REST (DTOs).

La estructura de paquetes refleja fielmente una arquitectura hexagonal, donde cada contexto acotado (Bounded Context) está claramente delimitado en los paquetes domain, application, interfaces.rest e infrastructure, facilitando una estricta separación de responsabilidades. Adicionalmente, todos los métodos públicos incluyen documentación técnica mediante Javadoc, detallando parámetros y valores de retorno. El manejo de excepciones es homogéneo mediante una capa global de captura de errores, la cual procesa excepciones de negocio específicas (tales como ProductAlreadyExistsException o ProductNotFoundException) y las traduce en códigos de estado HTTP semánticos (201, 400, 404, 500).

Las anotaciones nativas de Spring (@RestController, @PostMapping, @GetMapping) y de documentación (@Operation, @ApiResponse) se aplican de forma transversal para generar de manera automática el contrato de la API mediante OpenAPI/Swagger. Finalmente, la inyección de dependencias se realiza exclusivamente a través de constructores, promoviendo la inmutabilidad de los componentes y simplificando el diseño de pruebas unitarias.

<img src="assets/Chapter-6/code-backend1.png" alt="Carpetas Backend" width="250px">
<img src="assets/Chapter-6/code-backend2.png" alt="Code Backend" width="700px">


**Frontend - Angular/TypeScript** <br>
El frontend se alinea con las convenciones oficiales recomendadas por el equipo de Angular y las directrices de TypeScript, estructurándose mediante una arquitectura modular orientada a características (Features). Cada módulo de negocio (auth, inventory, dashboard, etc.) replica la filosofía de separación de responsabilidades en las capas de presentation, domain, infrastructure y application.

Los archivos se nombran estrictamente utilizando la convención kebab-case (auth-api.ts, auth-guard.ts, inventory.store.ts), mientras que las clases e interfaces emplean PascalCase (AuthApi, InventoryStore, AuthGuard). Los servicios inyectables se configuran mediante el decorador @Injectable({ providedIn: 'root' }), lo que optimiza el empaquetado mediante tree-shaking y previene la duplicidad de instancias. Se destaca el uso de Angular Signals para la gestión del estado reactivo de la interfaz, adoptando así la API moderna del framework para reducir la complejidad operativa frente a patrones RxJS tradicionales.

La documentación mediante JSDoc es mandatoria en métodos críticos, especialmente en guards y servicios de dominio. Los guards de protección de rutas implementan la interfaz funcional CanActivateFn, validando la vigencia del token JWT, los estados de autenticación y los roles del usuario antes de permitir el acceso a las vistas. El código prohíbe la lógica compleja dentro de los templates HTML, delegando dicha responsabilidad a los componentes y almacenes (stores) fuertemente tipados.

<img src="assets/Chapter-6/code-frontend1.png" alt="Carpetas Frontend" width="250px">
<img src="assets/Chapter-6/code-frontend2.png" alt="Code Frontend" width="700px">


**Landing Page - React/TypeScript** <br>
La landing page se construye mediante componentes funcionales de React basados en TypeScript, asegurando la tipación estática (type safety) en toda la capa de presentación. Los componentes se nombran en PascalCase (Header, HeroSection, PricingSection) y se centralizan dentro del directorio src/components/. Cada componente declara y recibe propiedades (Props) fuertemente tipadas, mitigando errores comunes en tiempo de compilación.

Para el diseño visual se utiliza Tailwind CSS, aplicando clases utilitarias directamente sobre el atributo className, lo que resulta en un estilo cohesivo, ágil y libre de archivos CSS externos innecesarios. Los colores corporativos de la marca se encuentran centralizados en el archivo de configuración de Tailwind, evitando valores arbitrarios dispersos.

La internacionalización del sitio se gestiona a través de un LanguageContext que expone el hook personalizado useLanguage(), permitiendo a los componentes acceder y alternar el idioma de manera global sin incurrir en prop drilling. El código mantiene un acceso unificado a las variables de entorno y URLs de redirección mediante constantes globales. Asimismo, componentes clave como ImageWithFallback implementan patrones defensivos para mitigar fallos en la carga de recursos multimedia externos, garantizando una experiencia de usuario fluida.

<img src="assets/Chapter-6/code-landing.png" alt="Carpetas Landing" width="250px">


#### 6.2.1.2. Code Quality & Code Security.

**Backend - Java/Spring Boot** <br>
La calidad en el backend se asegura mediante el desacoplamiento de la arquitectura hexagonal y el uso de DTOs, lo que reduce la complejidad ciclomática y la deuda técnica. En el ámbito de la seguridad a nivel de código, el sistema destaca por:
- Control de Acceso: Integración de Spring Security y tokens JWT. Los endpoints se protegen mediante autorización basada en roles con la anotación @PreAuthorize.
- Validación Defensiva: Aplicación estricta de Bean Validation (@Valid, @NotNull) en controladores para sanitizar los datos de entrada y prevenir ataques de inyección (SQLi) o XSS.
- Transparencia: Todos los flujos de autorización y códigos de respuesta están completamente documentados y declarados en el contrato de OpenAPI/Swagger.

**Frontend - Angular/TypeScript** <br>
La calidad del frontend se basa en una arquitectura modular por features y en el uso estricto de TypeScript (strict: true), garantizando un tipado fuerte que elimina errores en tiempo de compilación. Las prácticas de seguridad y estabilidad aplicadas incluyen:

- Protección de Navegación: Implementación de guards funcionales (CanActivateFn) que interceptan las rutas y validan la vigencia del JWT y los permisos antes de renderizar cualquier vista.
- Gestión de Estado Inmutable: El uso de Angular Signals previene fugas de memoria (memory leaks) y asegura un flujo de datos reactivo y predecible.
- Saneamiento: Confianza en los mecanismos nativos del framework para sanitizar el DOM y neutralizar vulnerabilidades de Client-Side XSS.

**Landing Page - React/TypeScript** <br>
A pesar de su naturaleza informativa, la landing page se rige por estándares de calidad basados en componentes funcionales reutilizables y tipados estáticos que evitan caídas de la interfaz. Sus medidas de seguridad y buenas prácticas comprenden:

- Navegación Segura: Uso mandatorio del atributo rel="noopener noreferrer" en enlaces externos para mitigar ataques de manipulación de pestañas (Tabnabbing).
- Gestión de Contexto: Centralización de traducciones mediante LanguageContext fuertemente tipado, evitando referencias nulas en la interfaz.
- Aislamiento: Configuración hermética de variables de entorno para evitar la filtración accidental de URLs o credenciales de desarrollo en el build de producción.

### 6.2.2. Reviews
## 6.2.2. Reviews

Durante el desarrollo del sistema **NorthEye**, se realizaron revisiones continuas del producto con el objetivo de asegurar la calidad del código, validar el cumplimiento de los requerimientos funcionales y no funcionales, y detectar de manera temprana posibles errores de diseño, implementación o integración.

Estas revisiones se ejecutaron en distintos niveles del ciclo de desarrollo, abarcando tanto el código fuente como los artefactos de diseño y la integración de componentes del sistema (backend, frontend y landing page).

**Peer Code Reviews**

Cada funcionalidad implementada en el backend (FastAPI) y en el frontend (React/Angular según módulo) pasó por un proceso de revisión entre pares antes de ser integrada a la rama principal del repositorio.

Durante estas revisiones se evaluaron los siguientes aspectos:

- Cumplimiento de las convenciones de codificación establecidas en el proyecto.
- Correcta implementación de la lógica de negocio en servicios y controladores.
- Uso adecuado de DTOs y separación de responsabilidades.
- Legibilidad, mantenibilidad y estructura del código.
- Detección de posibles errores lógicos o redundancias.
- Validación del manejo de excepciones y respuestas HTTP consistentes.

Asimismo, se verificó que los cambios realizados no generen conflictos con funcionalidades existentes y que el código cumpla con los estándares definidos dentro del flujo GitFlow antes de su merge a la rama principal.

**Sprint Reviews**

Al final de cada sprint del proyecto se realizaron sesiones de Sprint Review con el equipo de desarrollo, en las cuales se presentó el incremento funcional del sistema NorthEye.

En estas sesiones se llevaron a cabo las siguientes actividades:

- Demostración de las funcionalidades implementadas en el sprint.
- Validación del cumplimiento de las historias de usuario definidas en el Product Backlog.
- Revisión del comportamiento del sistema en escenarios reales de uso.
- Recolección de feedback por parte del equipo y ajustes necesarios para el siguiente sprint.
- Validación de la integración entre backend, frontend y servicios REST.

Estas revisiones permitieron asegurar la alineación del producto con los objetivos del proyecto y facilitaron la toma de decisiones sobre mejoras en la arquitectura y experiencia de usuario.

**Design & Architecture Reviews**

Además de las revisiones de código y funcionalidad, se realizaron revisiones de diseño y arquitectura del sistema, enfocadas en garantizar la coherencia del modelo propuesto.

En este proceso se validaron:

- Consistencia del diseño basado en arquitectura hexagonal en el backend.
- Correcta separación de capas (domain, application, infrastructure, interfaces).
- Definición adecuada de entidades, agregados y relaciones en el modelo de datos.
- Coherencia entre el diseño del frontend y los servicios expuestos por la API.
- Alineación entre los diagramas de arquitectura y la implementación real.

**Quality Assurance Reviews**

Como parte del aseguramiento de calidad, se realizaron revisiones orientadas a verificar el cumplimiento de criterios de calidad del sistema, incluyendo:

- Correcto funcionamiento de endpoints mediante pruebas manuales.
- Validación de respuestas de la API en escenarios exitosos y de error.
- Revisión de consistencia en la interfaz de usuario.
- Evaluación de usabilidad básica en flujos principales del sistema.
- Verificación de integración entre módulos del sistema.

**Resultado de las revisiones**

Gracias a las revisiones realizadas a lo largo del desarrollo, se logró:

- Reducir errores en etapas tempranas del ciclo de desarrollo.
- Mejorar la calidad del código antes de su integración.
- Asegurar coherencia entre diseño, implementación y requisitos.
- Incrementar la estabilidad del sistema en cada sprint.
- Mantener trazabilidad entre historias de usuario y entregables funcionales.

## 6.3. Validation Interviews.
### 6.3.1. Diseño de Entrevistas.

**Segmento #1: Bodegas especializadas por rubro**

**Presentación del entrevistado:**

¿Cuál es tu nombre?

¿Qué edad tienes?

¿Desde cuándo gestionas esta bodega?

¿Cuál es el rubro principal de tu bodega?

El usuario interactúa con la app móvil de la plataforma para gestión de inventarios.

Landing page

Acciones clave dentro del sistema

Navegación interactivo por la interfaz app móvil

**User Goal: Registrar**

El usuario selecciona la opción "Register", completa los campos solicitados y hace clic en el botón "Registrar".

A continuación, se muestra el panel "Add Card", donde debe llenar los campos relacionados con su tarjeta y correo electrónico.

Una vez que el proceso de pago se complete exitosamente, se notifica al usuario con un mensaje confirmando el vínculo de su tarjeta con la plataforma.

Del mismo modo, si el usuario desea retirar su información o actualizarla, lo podrá hacer a través de su perfil.

Finalmente, hacer clic en el botón "Aceptar".

**User Goal: Iniciar sesión**

El usuario introduce su correo y contraseña.

Luego hace clic en el botón "Log In".

Después, se le redirige al panel de perfil.

Allí puede editar su información personal y acceder a herramientas según su perfil ("Administrador" o "Empleado").

**User Goal: Navegar por el Dashboard**

El usuario inicia sesión desde la Landing Page.

Ingresa a la vista principal del Dashboard.

Visualiza el total de productos registrados y la fecha del último proveedor.

Visualiza un resumen de productos próximos a caducar con su respectiva fecha y stock disponible.

Accede a botones de acción rápida como “Historial”, “Inventario”, “Añadir Productos”, “Kits” y “Devolución de productos”.

**User Goal: Inventario (Producto / Lote)**

Ingresa a la sección de Inventario.

Revisa el listado de productos presionando el botón "por producto".

Filtra los productos por categoría, nombre del producto, fecha o stock mínimo.

Consulta el listado con información clave: fecha de entrada, cantidad por unidad, precio, stock mínimo y unidad de medida.

User Goal: Botones Principales (Agregar Producto y Kits)

Pulsa el botón "Agregar Producto".

Rellena los campos solicitados para registrar uno nuevo.

Pulsa el botón "Crear Kit".

Combina productos existentes para crear un kit nuevo.

El usuario pulsa el botón “Añadir Productos” desde el Dashboard.

Visualiza una galería de productos existentes y accede a opciones para editarlos o duplicarlos.

Puede agregar uno nuevo haciendo clic en el botón “+”, donde se despliega un formulario con campos como nombre, etiquetas, cantidad, lote, precios, fecha de caducidad y notas.

Desde el menú principal, también accede a la opción “Kits”.

En esta sección, selecciona productos existentes y los combina mediante el botón “Seleccionar para kit”, indicando cantidad e inventario disponible.

**User Goal: Historial de Movimientos**

Navega a la sección de Historial.

Visualiza entradas y salidas de productos.

Filtra movimientos por fecha, producto o lote.

El usuario accede a la sección de Historial desde el panel principal.

Filtra los registros por tipo de gestión, categoría, stock promedio y fecha.

Visualiza los movimientos realizados, incluyendo datos como nombre del producto, fecha de consulta, precio unitario, cantidad y total.

Consulta métricas como el stock promedio, estado del producto y stock ideal.

Cuenta con botones para editar o eliminar cada registro y, para los stock promedio, exportar la información y realiza un ticket promedio.

**User Goal: Alerta de Stock**

El usuario accede a la sección de Alertas desde el menú superior.

Consulta una lista de productos que presentan alertas por stock mínimo o por cercanía a su fecha de vencimiento.

Visualiza detalles como categoría de alerta, tipo de producto, nombre y fecha de alerta.

Puede ingresar a una vista de detalles, generar reportes o confirmar acciones desde botones individuales por producto.

También puede eliminar una alerta específica luego de una confirmación emergente.

Preguntas principales:

- ¿Te resultó fácil encontrar cómo agregar un producto?
- ¿Qué tal fue el proceso para registrar el stock por producto y por lote?
- ¿Te resultó claro el apartado de “Próximos a caducar”? ¿Te pareció útil?
- ¿Probaste la sección de kits? ¿Te resultó útil combinar productos?
- ¿Hubo algo que no entendiste o que te confundió mientras usabas la app?
- ¿Qué te pareció el diseño general de la landing page?
- ¿Tuviste alguna dificultad visual o técnica durante la navegación?

Valoración de experiencia

- Del 1 al 10, ¿qué tan útil te pareció la app para tu bodega?
- ¿Qué funcionalidad te pareció más valiosa?
- ¿Qué función le agregarías sí o sí?
- ¿Recomendarías esta plataforma a otros dueños de bodegas? ¿Por qué?
- 
**Segmento #2: Startups y emprendedores con necesidades logísticas**

Presentación del entrevistado

- ¿Cuál es tu nombre?
- ¿Qué edad tienes?
- ¿Qué tipo de producto vendes o almacenas?
- ¿Tienes local físico, almacén propio o trabajas con terceros?
- Interactúa el usuario con la landing page y la versión web de nuestra plataforma para gestión gestionar stock, registrar compras y generar reportes.

Landing page

Acciones clave dentro del sistema

Navegación interactivo por la interfaz app móvil

**User Goal: Registrar**

El usuario selecciona la opción "Register", completa los campos solicitados y hace clic en el botón "Registrar".

A continuación, se muestra el panel "Add Card", donde debe llenar los campos relacionados con su tarjeta y correo electrónico.

Una vez que el proceso de pago se complete exitosamente, se notifica al usuario con un mensaje confirmando el vínculo de su tarjeta con la plataforma.

Del mismo modo, si el usuario desea retirar su información o actualizarla, lo podrá hacer a través de su perfil.

Finalmente, hacer clic en el botón "Aceptar".

**User Goal: Iniciar sesión**

El usuario introduce su correo y contraseña.

Luego hace clic en el botón "Log In".

Después, se le redirige al panel de perfil.

Allí puede editar su información personal y acceder a herramientas según su perfil ("Administrador" o "Empleado").

**User Goal: Navegar por el Dashboard**

El usuario inicia sesión desde la Landing Page.

Ingresa a la vista principal del Dashboard.

Visualiza el total de productos registrados y la fecha del último proveedor.

Visualiza un resumen de productos próximos a caducar con su respectiva fecha y stock disponible.

Accede a botones de acción rápida como “Historial”, “Inventario”, “Añadir Productos”, “Kits” y “Devolución de productos”.

**User Goal: Inventario (Lote)**

Accede a la sección de Inventario por lote.

Filtra los lotes por nombre del producto, proveedor, fecha de entrada, cantidad o precio.

Consulta el listado con información detallada como proveedor, producto, fecha, cantidad por unidad, precio y unidad de medida.

Gestiona las acciones disponibles para cada lote desde la columna correspondiente.

**User Goal: Botones Principales (Agregar Producto y Kits)**

Pulsa el botón "Agregar Producto".

Rellena los campos solicitados para registrar uno nuevo.

Pulsa el botón "Crear Kit".

Combina productos existentes para crear un kit nuevo.

El usuario pulsa el botón “Añadir Productos” desde el Dashboard.

Visualiza una galería de productos existentes y accede a opciones para editarlos o duplicarlos.

Puede agregar uno nuevo haciendo clic en el botón “+”, donde se despliega un formulario con campos como nombre, etiquetas, cantidad, lote, precios, fecha de caducidad y notas.

Desde el menú principal, también accede a la opción “Kits”.

En esta sección, selecciona productos existentes y los combina mediante el botón “Seleccionar para kit”, indicando cantidad e inventario disponible.

**User Goal: Historial de Movimientos**

Navega a la sección de Historial.

Visualiza entradas y salidas de productos.

Filtra movimientos por fecha, producto o lote.

El usuario accede a la sección de Historial desde el panel principal.

Filtra los registros por tipo de gestión, categoría, stock promedio y fecha.

Visualiza los movimientos realizados, incluyendo datos como nombre del producto, fecha de consulta, precio unitario, cantidad y total.

Consulta métricas como el stock promedio, estado del producto y stock ideal.

Cuenta con botones para editar o eliminar cada registro y, para los stock promedio, exportar la información y realiza un ticket promedio.

**User Goal: Alerta de Stock**

El usuario accede a la sección de Alertas desde el menú superior.

Consulta una lista de productos que presentan alertas por stock mínimo o por cercanía a su fecha de vencimiento.

Visualiza detalles como categoría de alerta, tipo de producto, nombre y fecha de alerta.

Puede ingresar a una vista de detalles, generar reportes o confirmar acciones desde botones individuales por producto.

También puede eliminar una alerta específica luego de una confirmación emergente.

**Preguntas principales:**

- ¿Qué opinas de las alertas de stock mínimo/máximo y vencimiento? ¿Son suficientes?
- ¿La sección de historial de movimientos te pareció útil para revisar tus registros?
- ¿Te resultó útil la opción de devolución de productos?
- ¿Los reportes del historial son útiles para tomar decisiones?
- ¿Hubo algo que no entendiste o que te confundió mientras usabas la app?
- ¿Qué te pareció el diseño general de la landing page?
- ¿Tuviste alguna dificultad visual o técnica durante la navegación?

**Valoración de experiencia**

- Del 1 al 10, ¿qué tan útil te pareció la app móvil para tu bodega?
- ¿Qué funcionalidad te pareció más valiosa?
- ¿Qué función le agregarías sí o sí?
- ¿Recomendarías esta plataforma a otros emprendedores? ¿Por qué?

### 6.3.2. Registro de Entrevistas.

**Segmento #1: Dueños de bodegas**

| Nº | Datos del entrevistado                                  | Resumen de la entrevista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Evidencia de entrevista                                                                                                                                                                                                   |
|----|---------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | - **Nombre:** Ariana Agreda <br> - **Edad:** 20 años    | Ariana ayuda a su familia en el negocio familiar el cual es una bodega. Comenta que le resulta amigable y sencillo el flujo de la aplicación. Le ha gustado las notificaciones acerca de los productos que están por vencerse y agotarse. De igual forma, le ha parecido bueno como funciona lo de ingresar productos. Ella nos sugiere que para los reportes y pantalla de proveedores deberían mostrarse qué productos distribuye cada proveedor para un mayor seguimiento.                                                                                                                                                                                                                                                | ![Entrevista 1 - Dueños de bodegas](./assets/Chapter-6/entrevista-Ariana.png)  <br> <a href="https://drive.google.com/file/d/1V4lmrnzp-ti0Fky-YqT2-ltAyMjlksPa/view?usp=sharing">Validation Interview Ariana</a>          | 
| 2  | - **Nombre:** Mauricio Elera <br> - **Edad:** 25 años   | Mauricio administra el inventario de un negocio en crecimiento y percibe que StockWise le brinda una experiencia profesional y confiable gracias a su diseño ordenado y fácil de navegar. Destaca que las métricas rápidas y las alertas inteligentes le permiten reaccionar a tiempo ante riesgos como el bajo stock o productos por vencer. Considera muy intuitivo el proceso para registrar productos y gestionar roles de personal. Aunque está satisfecho con la estructura general del sistema, señala que un módulo de facturación y la integración con software contable harían la plataforma mucho más completa. Para él, la mayor ventaja de StockWise es centralizar toda la operación en un solo lugar, lo que le ayuda a reducir errores y mantener una gestión mucho más eficiente. | ![Entrevista 2 - Dueños de bodegas](./assets/Chapter-6/entrevista-Mauricio-Elera.png) <br> <a href="https://drive.google.com/file/d/1w0eSBDppZk9Z8G-TsmMfLN1sAYyxbZXt/view?usp=sharing">Validation Interview Mauricio</a> | 
| 3  | - **Nombre:** Marcelo Binda <br> - **Edad:** 26         | Marcelo Binda considera que StockWise representa una mejora significativa frente a los métodos tradicionales de gestión de inventario que utiliza actualmente, como cuadernos y hojas de Excel. Destaca que la aplicación le permite tener un mayor control y visibilidad del stock en tiempo real, reduciendo la incertidumbre sobre la disponibilidad de productos. Además, valora positivamente la simplicidad de la interfaz y la rapidez con la que puede realizar tareas básicas como el registro de productos y la consulta del inventario. Señala que la incorporación de alertas automáticas y un dashboard centralizado le ayuda a tomar decisiones más informadas y evitar pérdidas por falta de control. En general, percibe la herramienta como una solución práctica y adecuada para pequeñas bodegas que buscan digitalizar su operación. | ![Entrevista 3 - Dueños de bodegas](./assets/Chapter-6/Marcelo-Binda.png) <br><a href="https://youtu.be/N24bfq0zY5w">Validation Interview Marcelo (YouTube)</a>                                                           |
| 4  | - **Nombre:** Maryori Atanacio <br> - **Edad:** 24 años | Maryori ayuda con la administración y atención a su familia  bodega familiar. Comenta que la aplicación mostrada le pareció muy sencilla e intitutiva de usar sobre todo para la administración de productos que ofrece en su bodega. Considera que la funcionalidad de la sección de inventario es muy funcional y le ayudaría demasiado en el control de stocks y fecha de vencimiento en su producto. Recomienda que, se debería de añadir una funcionalidad para que pueda usarse con un lector de códigos de barras y sea más sencilla el agregar productos. | ![Entrevista 3 - Dueños de bodegas](./assets/Chapter-6/Marcelo-Binda.png) <br><a href="https://drive.google.com/file/d/1OtOnqF1lKWmzHf7uf1sX3Xd0sYxj4Ask/view?usp=sharing">Validation Interview Maryori</a> |

<br>


**Segmento #2: Startups y emprendedores en expansión con necesidades logísticas**

| Nº | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|----|------------------------|------------------------------------------| ----------------------- |
| 1  | - **Nombre:** Alexander Miranda Vivanco <br> - **Edad:** 27 años | Alexander posee un emprendimiento de venta de artículos para mascotas. Durante la entrevista reconoció que StockWise le sería de mucha ayuda por la logística del inventario. Las métricas del dashboard le parecieron idóneas. Sugirió facilitar el flujo de cuando se crea un producto y se agrega una reposición. Asimismo, comentó que le sería de mucha utlidad generar reportes acerca de aquellos productos que se hayan vencido. También especificó que poder agregar etiquetas personalizables sería adecuado y recomendó implementar una mejor lógica respecto a la reposición del stock. | ![Entrevista 1 - Startups y emprendedores en expansión con necesidades logísticas](./assets/Chapter-6/entrevista-Alexander-Miranda.png) <br> <a href="https://drive.google.com/file/d/14zPKDtkD_IFM2UjiPwRLCzG2cnPtis6E/view?usp=sharing">Validation Interview Alexander</a> |

| Nº | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|----|------------------------|------------------------------------------| ----------------------- |
| 2  | - **Nombre:** Briseth Hurtado <br> - **Edad:** 27 años | Briseth, quien cuenta con un emprendimiento de venta de artículos para mascotas, señaló que StockWise le resultaría de gran utilidad para gestionar su inventario y valoró positivamente las métricas presentadas en el dashboard. Además, sugirió simplificar el proceso de creación de productos y reposiciones, incorporar reportes de productos vencidos, permitir etiquetas personalizables y mejorar la lógica de reposición de stock para optimizar la administración del negocio. | ![Entrevista 2 - Startups y emprendedores en expansión con necesidades logísticas](./assets/Chapter-6/entrevista-Briseth.png) <br> <a href="https://drive.google.com/file/d/1SVhaXsh7jYZ6zZEcPJHA6YWHBGtPcM1K/view?usp=sharing">Validation Interview Briseth</a> |

| Nº | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|----|------------------------|------------------------------------------| ----------------------- |
| 3  | - **Nombre:** Juan Carlos Ramírez <br> - **Edad:** 49 años | Juan Carlos Ramírez, emprendedor de 49 años, compartió su experiencia al utilizar la aplicación para la gestión de inventarios, destacando la facilidad de uso en el registro y control de productos, así como la organización del historial de movimientos. Consideró que estas herramientas podrían ayudarlo significativamente en su proceso de digitalización, ya que actualmente gestiona las entradas y salidas de manera manual mediante boletas y facturas físicas. En cuanto al diseño, señaló que la interfaz es clara y ordenada, aunque sugirió mejorar la personalización de reportes para adaptarlo mejor a las necesidades de su negocio. Finalmente, destacó que funcionalidades como la alerta de stock bajo y la gestión por lotes serían de gran apoyo para tener un control más preciso del inventario, y que la incorporación de estas herramientas digitales le permitiría automatizar procesos y liberar tiempo operativo en su gestión diaria. | ![Entrevista 3 - Startups y emprendedores en expansión con necesidades logísticas](./assets/Chapter-6/seg2-carlitos.png) <br> <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202313773_upc_edu_pe/IQAuZWd-FH7TToFY_sNa6w96AaorWRZA95mLFTK9JzecuiQ?e=C4w6aw">Validation Interview Carlos</a> |

### 6.3.3. Evaluaciones segun heuristicas.


**TAREAS A EVALUAR:**
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
1. Navegación entre módulos del dashboard (Inicio, Inventario, Proveedores, etc.)
2. Creación de un Kit de productos
3. Búsqueda y filtrado en la sección de Proveedores
4. Gestión de usuarios
5. Generación de reportes avanzados

No están incluidas en esta versión de la evaluación las siguientes tareas:
1. Registro de nuevo usuario
2. Proceso de pago
3. Integraciones con APIs

---

**ESCALA DE SEVERIDAD:**

| Nivel | Descripción |
|-------|-------------|
| 1     | Problema superficial: puede ser fácilmente superado por el usuario ó ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |



**TABLA RESUMEN:**

| # | Problema                                                                                             | Escala de severidad | Heurística/Principio violada(o)                            |
|---|------------------------------------------------------------------------------------------------------|---------------------|-------------------------------------------------------------|
| 1 | Duplicidad redundante de alertas de stock en la vista general del Dashboard | 2                   | Consistencia y estándares / Reducción de carga cognitiva               |
| 2 | Inoperancia total de la búsqueda y el botón "Filtrar" en el módulo de Proveedores | 3                   | Retroalimentación del sistema / Flexibilidad y eficiencia                            |
| 3 | Falta de responsividad y superposición de textos en el contenedor lateral de Kits | 3                   | Diseño estético y minimalista                    |
| 4 | Bloqueo funcional en el menú de acciones de la tabla de Inventario | 4                   | Control y libertad del usuario |
| 5 | Permisión de sobreventa de Kits sin stock e insuficiencia en la gestión de errores | 4                   | Prevención de errores / Recuperación ante errores |        


**Detalle de hallazgos**
- **Hallazgo H-01**

| Campo | Detalle |
| :--- | :--- |
| **Tarea evaluada** | Visualización de alertas en el Dashboard |
| **Ubicación** | Dashboard general - Icono de notificaciones (Campana superior) |
| **Problema identificado** | Duplicidad redundante de alertas de stock en la misma pantalla |
| **Severidad** | 2 |
| **Heurística vulnerada** | Consistencia y estándares / Diseño estético y minimalista |
| **Descripción** | Al hacer clic en el icono de la campana en la barra superior, el panel flotante de notificaciones se despliega directamente sobre una vista principal que ya tiene como único propósito listar de forma idéntica las alertas de *"Producto a agotarse"* y *"Producto pronto a caducar"*. |
| **Impacto para el usuario** | Genera ruido visual innecesario y redundancia de datos. Al presentarse la misma información en dos capas superpuestas, se satura la interfaz y se sobrecarga cognitivamente al usuario sin aportar valor real. |
| **Recomendación** | Implementar una validación de ruta: si el usuario ya se encuentra dentro de la sección principal de notificaciones/alertas, el dropdown de la campana superior debe desactivarse o simplemente no abrirse al hacer clic, quedando como un indicador visual estático. |

**Evidencia**
*Figura 1. Menú desplegable de notificaciones duplicando la información de la sección de fondo.*

<img src="./assets/Chapter-6/ev-heuristica2.png" alt="Figura 1 - Hallazgo H-01" width="250px">


- **Hallazgo H-02**

| Campo | Detalle |
| :--- | :--- |
| **Tarea evaluada** | Búsqueda y filtrado de proveedores |
| **Ubicación** | Módulo de Proveedores - Barra de herramientas superior |
| **Problema identificado** | Inoperancia funcional de la barra de búsqueda y el botón "Filtrar" |
| **Severidad** | 3 |
| **Heurística vulnerada** | Retroalimentación del sistema / Flexibilidad y eficiencia de uso |
| **Descripción** | Los componentes de interacción en la sección de Proveedores (el campo de texto para buscar y el botón *"Filtrar"*) actúan visualmente como elementos interactivos. Sin embargo, al ingresar datos o hacer clic en ellos, la tabla de registros permanece estática sin procesar el filtro ni emitir señales de carga. |
| **Impacto para el usuario** | Alta frustración y sensación de que la plataforma está rota. Si el volumen de proveedores crece, la incapacidad de buscar o filtrar obliga al escaneo manual, rompiendo la eficiencia del flujo de trabajo. |
| **Recomendación** | Conectar el valor del `<input>` a un filtro reactivo en el frontend o disparar la petición correspondiente al backend. Si la opción avanzada de "Filtrar" aún no está desarrollada, se debe deshabilitar el botón visualmente y añadir un *tooltip* informativo: *"Función en desarrollo"*. |

**Evidencia**

![Figura 2 - Hallazgo H-02](./assets/Chapter-6/ev-heuristica3.png)

*Figura 2. Módulo de proveedores con controles de búsqueda y filtrado inactivos.*


- **Hallazgo H-03**

| Campo | Detalle |
| :--- | :--- |
| **Tarea evaluada** | Visualización de Kits estructurados |
| **Ubicación** | Barra lateral derecha - Panel de visualización de Kits |
| **Problema identificado** | Falta de responsividad y superposición de textos (*overlapping*) |
| **Severidad** | 3 |
| **Heurística vulnerada** | Diseño estético y minimalista (Visual UI Bug) |
| **Descripción** | En la tarjeta de detalle de los componentes del kit (ej. *"Pack Galletas Deli"*), las cajas de texto no se adaptan correctamente al ancho reducido de la barra lateral. Esto ocasiona que los nombres largos de los productos colisionen y se encimen sobre las etiquetas de *"Precio unitario"* y *"Total"*. |
| **Impacto para el usuario** | Perjudica gravemente la legibilidad de los costos de cada ítem del kit, lo que puede inducir a errores de cálculo visuales por parte del usuario y proyecta un acabado descuidado de la interfaz. |
| **Recomendación** | Modificar las reglas CSS del contenedor interno del ítem. Se sugiere aplicar una propiedad flex-direction en columna (`flex-direction: column`) cuando el espacio sea estrecho para situar los precios debajo del nombre, o aplicar un límite de ancho con truncamiento de texto (`text-overflow: ellipsis`). |

**Evidencia**

<img src="./assets/Chapter-6/ev-heuristica4.png" alt="Figura 1 - Hallazgo H-03" width="250px">


*Figura 3. Superposición visual de textos y precios en el bloque del Kit.*


- **Hallazgo H-04**

| Campo | Detalle |
| :--- | :--- |
| **Tarea evaluada** | Gestión y edición de existencias del inventario |
| **Ubicación** | Módulo de Inventario - Tabla de Productos (Columna Acciones) |
| **Problema identificado** | Bloqueo funcional total al seleccionar las opciones del menú de acciones |
| **Severidad** | 4 |
| **Heurística vulnerada** | Control y libertad del usuario |
| **Descripción** | Al interactuar con el botón de tres puntos en la fila de cualquier producto, el menú contextual se despliega de manera correcta mostrando las acciones de *"Ver detalle"*, *"Editar"* y *"Eliminar"*. No obstante, al hacer clic sobre cualquiera de las opciones, el sistema las ignora por completo y no ejecuta ninguna acción. |
| **Impacto para el usuario** | Bloqueo crítico del flujo de administración. El usuario pierde el control y la libertad sobre los datos del inventario, viéndose imposibilitado de actualizar precios, corregir datos o eliminar ítems obsoletos. |
| **Recomendación** | Verificar que las opciones del menú tengan correctamente enlazados sus manejadores de eventos (`onClick`). Adicionalmente, revisar que no exista un conflicto de capas (`z-index`) que coloque el menú detrás de una capa invisible, impidiendo registrar la pulsación del ratón. |

**Evidencia**

![Figura 4 - Hallazgo H-04](./assets/Chapter-6/ev-heuristica5.png)

*Figura 4. Menú de acciones desplegado pero inoperante al clic.*


 - **Hallazgo H-05**

| Campo | Detalle |
| :--- | :--- |
| **Tarea evaluada** | Control de flujo de existencias y registro de ventas |
| **Ubicación** | Módulo de Gestión de Ventas - Borrador de salida de productos |
| **Problema identificado** | Permisión de sobreventa de Kits sin stock disponible y manejo de error genérico |
| **Severidad** | 4 |
| **Heurística vulnerada** | Prevención de errores / Ayuda a reconocer y recuperarse de errores |
| **Descripción** | El selector del borrador de salida permite añadir cantidades ilimitadas de un kit (ej. 14 unidades de *"Combo gaseosas"*), ignorando que los productos que lo componen individualmente tienen stock en cero en la tabla izquierda. Al intentar *"Guardar"*, el sistema procesa la solicitud inválida y arroja un banner de error genérico: *"Error al guardar la venta. Por favor, intente nuevamente"*. |
| **Impacto para el usuario** | Muy grave. Permite la venta ficticia de productos inexistentes y desorienta al usuario con un mensaje de error que sugiere un problema del servidor en lugar de explicar la causa real (falta de existencias). El usuario queda atrapado sin saber cómo corregir la acción. |
| **Recomendación** | 1. **En Frontend:** Deshabilitar dinámicamente el botón `+` de incremento en el borrador si la cantidad del kit requiere más unidades de las disponibles en el stock real de cualquiera de sus componentes. <br>2. **En Mensajería:** Cambiar la respuesta del banner por un texto descriptivo: *"No se pudo registrar la venta: Stock insuficiente en los componentes del Kit"*. |

**Evidencia**

![Figura 5 - Hallazgo H-05](./assets/Chapter-6/ev-heuristica1.png)

*Figura 5. Ventana de ventas mostrando el incremento desmedido de un kit sin stock y el consecuente banner de error genérico.*


## 6.4. Auditoria de Experiencias de Usuario.
La auditoría de experiencias de usuario fue llevada a cabo con el objetivo de obtener retroalimentación externa sobre la calidad de la interfaz y la arquitectura de información de StockWise, así como de brindar retroalimentación a otro equipo de trabajo. El proceso contempló dos dimensiones: la auditoría realizada a un grupo externo y la auditoría recibida por parte de otro grupo evaluador.

### 6.4.1. Auditoria realizada.
#### 6.4.1.1. Información del grupo auditado.

| Campo                    | Detalle                                                       |
| ------------------------ | ------------------------------------------------------------- |
| Grupo auditado           | Grupo 2                                                       |
| Startup                  | EduLabs                                     |
| Producto evaluado        | Demy                                  |
| Integrantes del equipo   | Daniel Crispin, Rafael Dominguez, Henry Esteban, Renso Julca y Diego Vilca |
| Repositorio del proyecto | https://github.com/orgs/EduLabs-Experimentos/repositories                                   |
| Landing Page             | https://demy-edulabs.netlify.app/                             |
| Aplicación web           | https://edulabs-experimentos.github.io/demy-admin-web/sign-up |

#### 6.4.1.2. Cronograma de auditoría realizada

| Actividad                                                | Fecha      | Responsable          | Duración estimada |
| -------------------------------------------------------- | ---------- | -------------------- | ----------------- |
| Recepción del informe de auditoría externa               | 11/06/2026 | Ronald Peralta  | 30 minutos        |
| Revisión y análisis de hallazgos identificados           | 11/06/2026 | Ronald Peralta  | 1 hora            |
| Priorización de observaciones y acciones correctivas     | 12/06/2026 | Ronald Peralta  | 30 minutos        |
| Evaluación integral del flujo funcional de la aplicación | 13/06/2026 | Ronald Peralta  | 1 hora            |
| Implementación de mejoras y corrección de incidencias    | 13/06/2026 | Ronald Peralta  | 30 minutos        |

#### 6.4.1.3. Contenido de la auditoría realizada
La presente auditoría tuvo como objetivo evaluar la usabilidad y experiencia de usuario del producto desarrollado por el grupo auditado. Para ello, se analizaron los principales flujos de interacción de la aplicación, identificando problemas relacionados con navegación, retroalimentación del sistema, accesibilidad, consistencia visual y comprensión de la interfaz.

**Tareas evaluadas**

Durante la auditoría se ejecutaron las siguientes tareas representativas del flujo de uso de la aplicación:

| N.° | Tarea evaluada       | Descripción                            |
| --- | -------------------- | -------------------------------------- |
| 1   | Navegación global | Interacción con la barra de navegación (Header) para retornar a la vista principal. |
| 2   | Visualización de contenido | Carga y renderizado de los recursos multimedia en las distintas secciones informativas. |
| 3   | Análisis de rendimiento | Evaluación de métricas de carga, accesibilidad y SEO utilizando la herramienta Google Lighthouse. |
| 4   | Arquitectura de la información | Recorrido por las secciones de la Landing Page para evaluar la carga cognitiva y relevancia del contenido. |
| 5   | Flujo de conversión | Búsqueda del enlace o botón principal (Call to Action) para iniciar el proceso de registro en la Web App. |
| 6   | Navegación interna | Exploración de las opciones secundarias del menú de navegación ("Configuración" y "Ayuda"). |
| 7   | Registro de datos de usuario | Ingreso de información demográfica y de contacto en el formulario de la sección "ESTUDIANTES". |
| 8   | Gestión de disponibilidad | Configuración de rangos de tiempo (hora de inicio y fin) en la sección de "Horarios". |
| 9   | Adaptabilidad visual |Evaluación de la legibilidad de la interfaz al alternar el esquema de colores (Modo Oscuro) en la sección "Cobranzas".|


**Escala de severidad utilizada**

| Nivel | Descripción                                                                       |
| ----- | --------------------------------------------------------------------------------- |
| 1     | Problema superficial que no afecta significativamente la experiencia del usuario. |
| 2     | Problema menor que genera cierta dificultad pero permite completar la tarea.      |
| 3     | Problema importante que dificulta considerablemente la interacción.               |
| 4     | Problema crítico que impide completar la tarea o continuar utilizando el sistema. |


 **Resumen de hallazgos identificados**

| ID   | Tarea                    | Problema identificado                                                | Severidad | Heurística vulnerada              |
| ---- | ------------------------ | ------------------------------------------------------------------- | --------- | --------------------------------- |
| H-01 | Navegación global        | Logotipo inactivo sin redirección a la página de inicio.            | 2         | Consistencia y estándares         |
| H-02 | Visualización de contenido | Imagen rota o no renderizada en la sección "Nosotros".             | 2         | Diseño estético y minimalista     |
| H-03 | Análisis de rendimiento  | Bajo puntaje de rendimiento (59/100) en la métrica de Lighthouse.   | 3         | Flexibilidad y eficiencia de uso  |
| H-04 | Arquitectura de la información | Exceso de secciones y contenido redundante (sección "Pasos"). | 1         | Diseño estético y minimalista     |
| H-05 | Flujo de conversión      | Ausencia total de botón CTA hacia el registro de la aplicación web. | 4         | Control y libertad del usuario    |
| H-06 | Navegación interna | Enlaces inactivos en el menú de navegación principal. | 3 | Control y libertad del usuario |
| H-07 | Registro de datos de usuario | Ausencia de validaciones lógicas en campos de teléfono y fecha de nacimiento. | 3 | Prevención de errores |
| H-08 | Gestión de disponibilidad | Interfaz de selección de horas (Time Picker) poco intuitiva y demandante. | 2 | Flexibilidad y eficiencia de uso |
| H-09 | Adaptabilidad visual | Deficiencia de contraste y pérdida de claridad en el modo oscuro (Módulo de facturas). | 2 | Diseño estético y minimalista |

---

** Detalle de hallazgos**
- **Hallazgo H-01**

| Campo                   | Detalle                                                                                                                                                                                                                |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Navegación global                                                                                                                                                                                                      |
| Ubicación               | Landing Page - Barra de navegación superior (Header)                                                                                                                                                                   |
| Problema identificado   | Logotipo de la marca inactivo sin hipervínculo al Home                                                                                                                                                                 |
| Severidad               | 2                                                                                                                                                                                                                      |
| Heurística vulnerada    | Consistencia y estándares                                                                                                                                                                                              |
| Descripción             | Al navegar por las distintas secciones de la página, el usuario intenta hacer clic en el logotipo "Demy" para regresar rápidamente al inicio, pero este elemento es estático y no contiene un enlace (etiqueta `<a>`). |
| Impacto para el usuario | Genera fricción en la navegación. El usuario se ve obligado a hacer scroll manual hacia arriba o buscar alternativas para regresar, rompiendo una convención estándar de diseño web.                                   |
| Recomendación           | Envolver el logotipo en una etiqueta de ancla (`<a>`) o componente de enrutamiento que apunte a la ruta raíz (`/` o `#home`).                                                                                          |

**Evidencia**

![Figura 1 - Hallazgo H-01](assets/Chapter-6/hallazgo-h01.png)

*Figura 1. Barra de navegación donde se observa el logotipo estático.*

---

- **Hallazgo H-02**

| Campo                   | Detalle                                                                                                                                                                                                         |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Visualización de contenido                                                                                                                                                                                      |
| Ubicación               | Landing Page - Sección "Nosotros"                                                                                                                                                                               |
| Problema identificado   | Elemento de imagen no disponible (Enlace roto)                                                                                                                                                                  |
| Severidad               | 2                                                                                                                                                                                                               |
| Heurística vulnerada    | Diseño estético y minimalista / Prevención de errores                                                                                                                                                           |
| Descripción             | Dentro del apartado "Nosotros", uno de los recursos gráficos no logra cargar correctamente, mostrando el icono estándar de "imagen rota" o un espacio en blanco en el navegador.                                |
| Impacto para el usuario | Disminuye la percepción de calidad y profesionalismo del producto. Puede generar desconfianza en el usuario sobre el mantenimiento del sitio.                                                                   |
| Recomendación           | Verificar la ruta del atributo `src` en la etiqueta `<img>`. Asegurar que el archivo exista en el directorio de despliegue o proveer un atributo `alt` descriptivo junto con una imagen de respaldo (fallback). |

**Evidencia**

![Figura 1 - Hallazgo H-02](assets/Chapter-6/hallazgo-h02.png)

*Figura 2. Sección "Nosotros" evidenciando el error de carga del recurso multimedia.*

---

- **Hallazgo H-03**

| Campo                   | Detalle                                                                                                                                                                                                                      |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Análisis de rendimiento                                                                                                                                                                                                      |
| Ubicación               | Landing Page - Entorno global                                                                                                                                                                                                |
| Problema identificado   | Puntaje deficiente de Performance (59/100) en Lighthouse                                                                                                                                                                     |
| Severidad               | 3                                                                                                                                                                                                                            |
| Heurística vulnerada    | Flexibilidad y eficiencia de uso                                                                                                                                                                                             |
| Descripción             | La auditoría técnica con Google Lighthouse arroja resultados contrastantes: Accesibilidad (90), Buenas prácticas (77), SEO (91), pero el Rendimiento cae a 59/100, indicando tiempos de carga lentos para el hilo principal. |
| Impacto para el usuario | Un bajo rendimiento impacta directamente en los Core Web Vitals (como el LCP). Los usuarios con conexiones inestables pueden abandonar la página antes de que termine de cargar.                                             |
| Recomendación           | Optimizar el tamaño y formato de las imágenes (usar WebP), diferir la carga de JavaScript no crítico y minificar los archivos estáticos CSS/JS para mejorar el First Contentful Paint (FCP).                                 |

**Evidencia**

![Figura 1 - Hallazgo H-03](assets/Chapter-6/hallazgo-h03.png)

*Figura 3. Resultados del análisis de Google Lighthouse.*

---

- **Hallazgo H-04**

| Campo                   | Detalle                                                                                                                                                                                                                                                          |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Arquitectura de la información                                                                                                                                                                                                                                   |
| Ubicación               | Landing Page - Cuerpo de la página (Sección "Pasos")                                                                                                                                                                                                             |
| Problema identificado   | Sobrecarga de información y redundancia de secciones                                                                                                                                                                                                             |
| Severidad               | 1                                                                                                                                                                                                                                                                |
| Heurística vulnerada    | Diseño estético y minimalista                                                                                                                                                                                                                                    |
| Descripción             | La página presenta un volumen excesivo de secciones verticales (Características, Pasos, Testimonios, Nosotros, Precios, Preguntas, Contacto). Específicamente, la sección "Pasos" describe un proceso que resulta ser demasiado trivial, sin aportar valor real. |
| Impacto para el usuario | Incrementa la fatiga visual y la carga cognitiva del usuario al tener que hacer demasiado scroll. Diluye la atención y desvía al usuario de la acción principal que debe realizar.                                                                               |
| Recomendación           | Simplificar la estructura de la Landing Page. Eliminar la sección "Pasos" y condensar u ocultar información secundaria en acordeones o enlaces internos para mantener un flujo más directo.                                                                      |

**Evidencia**

![Figura 1 - Hallazgo H-03](assets/Chapter-6/hallazgo-h04.png)

*Figura 4. Sección "Pasos" que aporta baja relevancia al flujo de la página.*

---

- **Hallazgo H-05**

| Campo                   | Detalle                                                                                                                                                                                                             |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Flujo de conversión                                                                                                                                                                                                 |
| Ubicación               | Landing Page - Menú de navegación y Hero Section                                                                                                                                                                    |
| Problema identificado   | Ausencia de un botón de llamada a la acción (CTA) hacia la aplicación web                                                                                                                                           |
| Severidad               | 4                                                                                                                                                                                                                   |
| Heurística vulnerada    | Control y libertad del usuario / Prevención de errores                                                                                                                                                              |
| Descripción             | El propósito principal de la Landing Page es captar usuarios, pero no existe un botón prominente (como "Regístrate" o "Ingresar a la App") que dirija al usuario al flujo de registro (`/sign-up`) de la Web App.   |
| Impacto para el usuario | Impide por completo la conversión. El usuario interesado en el producto se queda estancado en la Landing Page sin un camino claro para comenzar a utilizar la aplicación, frustrando el objetivo de negocio.        |
| Recomendación           | Implementar botones CTA de alto contraste y tamaño adecuado tanto en la esquina superior derecha del menú de navegación como en la sección principal (Hero Section), enlazados directamente a la vista de registro. |

**Evidencia**

![Figura 1 - Hallazgo H-03](assets/Chapter-6/hallazgo-h05.png)

*Figura 5. Ausencia de botones de registro en el primer impacto visual de la página.*

---

- **Hallazgo H-06**

| Campo                   | Detalle                                                                                                                                                                                                                              |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Tarea evaluada          | Navegación interna                                                                                                                                                                                                                   |
| Ubicación               | Web App - Barra de navegación lateral/superior                                                                                                                                                                                       |
| Problema identificado   | Secciones "Configuración" y "Ayuda" sin funcionalidad                                                                                                                                                                                |
| Severidad               | 3                                                                                                                                                                                                                                    |
| Heurística vulnerada    | Control y libertad del usuario                                                                                                                                                                                                       |
| Descripción             | Al intentar acceder a las opciones de "Configuración" y "Ayuda" desde el menú principal, los enlaces no ejecutan ninguna acción, no redirigen a ninguna vista, ni muestran un mensaje indicando que la función está en construcción. |
| Impacto para el usuario | Genera confusión y frustración. El usuario percibe la aplicación como incompleta o defectuosa al no poder acceder a herramientas críticas de gestión de su cuenta o soporte.                                                         |
| Recomendación           | Implementar las vistas correspondientes para estas rutas. Si las funcionalidades aún no están desarrolladas, se deben ocultar temporalmente los enlaces del menú o mostrar un modal informativo de "Próximamente" (Coming soon).     |

**Evidencia**

![Figura 1 - Hallazgo H-06](assets/Chapter-6/hallazgo-h06.png)

*Figura 6. Elementos del menú de navegación que no presentan interactividad.*

---

- **Hallazgo H-07**

| Campo                   | Detalle                                                                                                                                                                                                                                                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Registro de datos de usuario                                                                                                                                                                                                                                                                                              |
| Ubicación               | Web App - Sección "ESTUDIANTES" (Formulario de creación/edición)                                                                                                                                                                                                                                                          |
| Problema identificado   | Falta de validación lógica en inputs de teléfono y fecha de nacimiento                                                                                                                                                                                                                                                    |
| Severidad               | 3                                                                                                                                                                                                                                                                                                                         |
| Heurística vulnerada    | Prevención de errores                                                                                                                                                                                                                                                                                                     |
| Descripción             | El formulario presenta dos fallas críticas de validación: 1) El campo de número de celular restringe la entrada estrictamente a 9 dígitos y no permite ingresar códigos de país (ej. +51), limitando la internacionalización. 2) El selector de fecha de cumpleaños permite seleccionar la fecha actual o fechas futuras. |
| Impacto para el usuario | Compromete la integridad de la base de datos al permitir el ingreso de información irreal o malformada. Limita el uso de la plataforma a un formato telefónico local, excluyendo posibles usuarios extranjeros.                                                                                                           |
| Recomendación           | Implementar validaciones de fecha (ej. `max="[fecha-actual]"` en el input de tipo date) para bloquear fechas futuras en los cumpleaños. Incorporar un componente de Input Phone que incluya un selector desplegable de códigos de país y ajuste la longitud esperada según la región.                                     |

**Evidencia**

![Figura 1 - Hallazgo H-07](assets/Chapter-6/hallazgo-h07.png)

*Figura 7. Formulario aceptando datos incongruentes en los campos de contacto y nacimiento.*

---

- **Hallazgo H-08**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Gestión de disponibilidad                                                                                                                                                                                                                                |
| Ubicación               | Web App - Sección "Horarios"                                                                                                                                                                                                                             |
| Problema identificado   | Interfaz de selección de horas (Time Picker) incómoda y poco fluida                                                                                                                                                                                      |
| Severidad               | 2                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Flexibilidad y eficiencia de uso                                                                                                                                                                                                                         |
| Descripción             | El componente utilizado para ingresar la "Hora de inicio" y "Hora de fin" en las sesiones requiere múltiples clics o una manipulación poco ergonómica, dificultando la entrada rápida de datos, especialmente si se deben configurar múltiples horarios. |
| Impacto para el usuario | Incrementa innecesariamente el tiempo y el esfuerzo requerido para completar una tarea repetitiva, degradando la experiencia de uso (fricción operativa).                                                                                                |
| Recomendación           | Reemplazar el componente actual por un Time Picker más intuitivo (por ejemplo, selectores visuales de reloj, campos con autocompletado en formato HH:MM, o incrementos rápidos de 15/30 minutos mediante botones).                                       |

**Evidencia**

![Figura 1 - Hallazgo H-08](assets/Chapter-6/hallazgo-h08.png)

*Figura 8. Interfaz de configuración de horarios evidenciando un flujo de selección ineficiente.*

---

- **Hallazgo H-09**

| Campo                   | Detalle                                                                                                                                                                                                                                                                                   |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Adaptabilidad visual                                                                                                                                                                                                                                                                      |
| Ubicación               | Web App - Sección "Cobranzas" (Apartado de facturas)                                                                                                                                                                                                                                      |
| Problema identificado   | Pérdida de claridad y legibilidad en el esquema de Modo Oscuro                                                                                                                                                                                                                            |
| Severidad               | 3                                                                                                                                                                                                                                                                                         |
| Heurística vulnerada    | Diseño estético y minimalista (Accesibilidad)                                                                                                                                                                                                                                             |
| Descripción             | Al activar el tema oscuro (Dark Mode), los estilos CSS específicos del apartado de facturas no se adaptan correctamente. El texto y los elementos de la interfaz carecen del contraste necesario contra los fondos oscuros, volviendo la información difícil o imposible de leer.         |
| Impacto para el usuario | Impide la correcta visualización de datos financieros sensibles. Causa fatiga visual severa y vulnera las pautas de accesibilidad (WCAG) sobre el ratio de contraste mínimo requerido.                                                                                                    |
| Recomendación           | Auditar y ajustar la paleta de colores del Modo Oscuro utilizando variables CSS. Asegurar que los colores de texto principales (ej. blanco o gris claro) tengan un ratio de contraste de al menos 4.5:1 sobre los fondos oscuros correspondientes a las tablas y tarjetas de facturación. |

**Evidencia**

![Figura 1 - Hallazgo H-09](assets/Chapter-6/hallazgo-h09.png)

*Figura 9. Problemas de contraste en el módulo de facturas al utilizar el tema oscuro.*



### 6.4.2. Auditoria recibida.
#### 6.4.2.1. Información del grupo auditor.
| Campo                    | Detalle                                                       |
| ------------------------ | ------------------------------------------------------------- |
| Grupo auditado           | Grupo 3                                                       |
| Startup                  | Stoq                                     |
| Producto evaluado        | StockWise                                  |
| Integrantes del equipo   | Ronald Peralta, Luciana Choquehuanca, Camila Rios, Fabiola Del Rocio y Roy Fernandes|
| Repositorio del proyecto | https://github.com/orgs/upc-1ASI0732-2610-16879-Stoq/repositories                                  |
| Landing Page             | https://stockwiselanding.netlify.app/                            |
| Aplicación web           | https://stocktrack-frontend.vercel.app/auth/register |

#### 6.4.2.2. Cronograma de auditoría recibida.

| Actividad                                                | Fecha      | Responsable          | Duración estimada |
| -------------------------------------------------------- | ---------- | -------------------- | ----------------- |
| Recepción del informe de auditoría externa de StockWise  | 11/06/2026 | Rafael Dominguez       | 30 minutos        |
| Revisión, análisis y catalogación de hallazgos           | 11/06/2026 | Rafael Dominguez       | 1 hora            |
| Priorización de observaciones según escala de severidad  | 12/06/2026 | Diego Vilca      | 30 minutos        |
| Asignación de tareas al equipo y planificación del plan correctivo | 12/06/2026 | Diego Vilca       | 1 hora            |
| Implementación de mejoras y corrección de incidencias críticas | 13/06/2026 | Equipo EduLabs  | 6 horas           |
| Validación final y pruebas de regresión de los flujos corregidos | 14/06/2026 | Equipo EduLabs       | 1 hora y 30 min   |

#### 6.4.2.3. Contenido de auditoría recibida.
- **Hallazgo H-01**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Inicio de sesión (Login)                                                                                                                                                                                                                                 |
| Ubicación               | Web App - Pantalla de Login                                                                                                                                                                                                                              |
| Problema identificado   | Espera prolongada con spinner infinito sin mensaje de contexto ni manejo de tiempo de espera (timeout)                                                                                                                                                   |
| Severidad               | 2                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Visibilidad del estado del sistema / Control y libertad del usuario                                                                                                                                                                                      |
| Descripción             | Al realizar el primer intento de inicio de sesión, el sistema muestra correctamente un indicador de carga (spinner) en el botón. Sin embargo, debido a una alta latencia del servidor, este spinner se mantiene girando indefinidamente (más de 30 segundos) sin ofrecer ninguna actualización de estado. Al no existir un límite de tiempo de espera (timeout) ni un botón para cancelar la petición, el usuario percebe que la aplicación se ha "congelado", obligándolo a cerrar y recargar la página manualmente para poder continuar. |
| Impacto para el usuario | Causa frustración y desorientación al no saber si el proceso sigue activo, obligándolo a abandonar la tarea actual y realizar acciones manuales de recuperación (recarga de página) para desbloquear la interfaz.                                         |
| Recomendación           | Establecer un tiempo máximo de espera para la petición HTTP (por ejemplo, 10 o 15 segundos). Si el servidor no responde en ese lapso, se debe detener el spinner y mostrar un mensaje de error claro al usuario (ej. "El servidor está tardando más de lo esperado, por favor intenta nuevamente"). Alternativamente, si se sabe que el servidor puede tener un "arranque en frío", mostrar un aviso temporal que diga "Conectando con el servidor, esto puede tomar unos segundos...". |

**Evidencia**

![Figura 1 - Hallazgo H-01](assets/Chapter-6/hallazgo-m1.png)

*Figura 1. Interfaz de inicio de sesión evidenciando un indicador de carga indefinido y falta de manejo de timeout.*

---

- **Hallazgo H-02**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Recuperación de credenciales                                                                                                                                                                                                                             |
| Ubicación               | Web App - Pantalla de Login (Enlace "¿Olvidaste tu contraseña?")                                                                                                                                                                                         |
| Problema identificado   | El enlace de "Olvidaste tu contraseña" no dirige al flujo de recuperación, recargando la vista actual                                                                                                                                                    |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Control y libertad del usuario                                                                                                                                                                                                                           |
| Descripción             | Al hacer clic en la opción "¿Olvidaste tu contraseña?", el sistema no redirige al usuario a la vista correspondiente para restablecer sus credenciales. En su lugar, el enlace simplemente recarga la página de login actual y altera la URL agregando un parámetro (ej. ?returnUrl=%2Fdashboard). Esto atrapa al usuario en un bucle sin salida si realmente ha perdido su contraseña, impidiendo su recuperación. |
| Impacto para el usuario | Bloquea por completo el acceso a los usuarios que no recuerdan sus credenciales, generando un flujo roto que impide la autonomía del usuario para recuperar su cuenta.                                                                                   |
| Recomendación           | Revisar el enrutamiento (routing) en el frontend de la aplicación web. Se debe asegurar que el enlace tenga la ruta correcta hacia el componente de recuperación (por ejemplo, /auth/recovery) en lugar de apuntar a la misma vista de login, eliminando la recarga innecesaria de la página. |

**Evidencia**

![Figura 2 - Hallazgo H-02](assets/Chapter-6/hallazgo-m2.png)

*Figura 2. Enlace de recuperación de contraseña que genera un bucle de redirección en la misma pantalla.*

---

- **Hallazgo H-03**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Configuración de idioma / Interacción general                                                                                                                                                                                                            |
| Ubicación               | Web App - Esquina superior derecha de la interfaz                                                                                                                                                                                                         |
| Problema identificado   | Elemento interactivo superpuesto o muy cerca de un elemento gráfico decorativo                                                                                                                                                                           |
| Severidad               | 1                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Diseño estético y minimalista                                                                                                                                                                                                                            |
| Descripción             | En la esquina superior derecha, el selector de idioma (ES/EN) se encuentra visualmente sobrepuesto o demasiado pegado al elemento gráfico decorativo (el círculo amarillo de fondo). Esto genera ruido visual, reduce la claridad de la interfaz y da una apariencia poco pulida al diseño, aunque no impide la funcionalidad del botón. |
| Impacto para el usuario | Genera ruido visual y reduce la legibilidad de los controles, proyectando una imagen de falta de pulido estético y descuido en el diseño visual de la aplicación.                                                                                         |
| Recomendación           | Ajustar los estilos CSS del contenedor del botón. Se debe aumentar el margen (margin) o el espaciado interno (padding) para separarlo del círculo decorativo, o en su defecto, ajustar el posicionamiento absoluto y el z-index de los elementos de fondo para que no interfieran con las áreas de interacción de los componentes superiores. |

**Evidencia**

![Figura 3 - Hallazgo H-03](assets/Chapter-6/hallazgo-m3.png)

*Figura 3. Superposición visual entre el selector de idioma y el elemento gráfico decorativo de fondo.*

---

- **Hallazgo H-04**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Navegación y persistencia de ruta                                                                                                                                                                                                                        |
| Ubicación               | Web App - Sección Dashboard                                                                                                                                                                                                                              |
| Problema identificado   | Redirección inesperada a la vista de "Ajustes" al refrescar el Dashboard                                                                                                                                                                                 |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Control y libertad del usuario                                                                                                                                                                                                                           |
| Descripción             | Estando en la vista principal del Dashboard, si el usuario recarga la página (F5 o botón de refresh del navegador), el sistema pierde el contexto de la ruta actual y lo redirige automáticamente a la sección de "Settings" (Ajustes). Esto interrumpe el flujo de trabajo del usuario, causándole desorientación y obligándolo a hacer clics adicionales para volver a la pantalla de inicio. |
| Impacto para el usuario | Interrumpe drásticamente el flujo de trabajo operativo, obligando al usuario a reorientarse y a realizar acciones repetitivas de navegación para regresar a su ubicación original.                                                                       |
| Recomendación           | Revisar la configuración del enrutador del frontend (ej. Vue Router, React Router). Se debe asegurar que el estado de la aplicación o el manejo de rutas privadas/autenticadas respete la URL actual (/dashboard) durante la recarga del navegador, en lugar de usar una redirección por defecto hacia /settings. |

**Evidencia**

![Figura 4 - Hallazgo H-04](assets/Chapter-6/hallazgo-m41.png)
![Figura 4 - Hallazgo H-04](assets/Chapter-6/hallazgo-m42.png)

*Figura 4. Pérdida del contexto de navegación al actualizar la página desde el Dashboard principal.*

---

- **Hallazgo H-05**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Configuración global (Cambio de idioma)                                                                                                                                                                                                                  |
| Ubicación               | Web App - Menú lateral izquierdo (Sidebar)                                                                                                                                                                                                               |
| Problema identificado   | Control global (cambio de idioma) oculto al colapsar el menú lateral                                                                                                                                                                                     |
| Severidad               | 2                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Consistencia y estándares / Flexibilidad y eficiencia de uso                                                                                                                                                                                             |
| Descripción             | El botón para alternar el idioma (ES/EN) está ubicado dentro del menú lateral izquierdo (sidebar). El problema de diseño radica en que, si el usuario decide colapsar este menú para tener más espacio de visualización, el control de idioma desaparece. Los controles de configuración global no deben depender de elementos colapsables de navegación específica. |
| Impacto para el usuario | Limita el acceso a funciones globales del sistema, forzando al usuario a desplegar elementos de navegación secundarios únicamente para poder interactuar con una preferencia básica de la interfaz.                                                      |
| Recomendación           | Reubicar el selector de idiomas. El estándar en el diseño de interfaces web (UI) dicta que este tipo de controles globales se coloquen en la barra superior (Header o Topbar), preferiblemente alineado a la derecha, cerca del icono de notificaciones o del perfil del usuario, garantizando su visibilidad y acceso en todo momento. |

**Evidencia**

![Figura 5 - Hallazgo H-05](assets/Chapter-6/hallazgo-m5.png)

*Figura 5. Ocultamiento del selector de idioma global debido al colapso del menú de navegación lateral.*

---

- **Hallazgo H-06**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Visualización de alertas y notificaciones                                                                                                                                                                                                                |
| Ubicación               | Web App - Sección Dashboard (Panel derecho y Barra superior)                                                                                                                                                                                             |
| Problema identificado   | Duplicidad innecesaria de la interfaz de notificaciones en la misma vista                                                                                                                                                                                |
| Severidad               | 2                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Diseño estético y minimalista                                                                                                                                                                                                                            |
| Descripción             | La pantalla del Dashboard presenta redundancia de información. Existe un panel estático en el lado derecho que muestra una lista de notificaciones (ej. "Product running out") y, simultáneamente, en la barra superior hay un icono de campana que despliega exactamente la misma lista en un menú flotante. Esta duplicidad satura la interfaz con información repetida y desperdicia espacio valioso en la pantalla principal. |
| Impacto para el usuario | Sobrecarga cognitivamente al usuario debido a la redundancia visual, reduciendo además el espacio útil en pantalla que podría destinarse a información analítica relevante.                                                                              |
| Recomendación           | Eliminar el panel estático de notificaciones del cuerpo del Dashboard. Se recomienda mantener únicamente el icono de la campana en la barra superior con su respectivo menú desplegable (que es el estándar de la industria). El espacio liberado en el lado derecho del Dashboard puede aprovecharse para expandir los gráficos de métricas o incluir un nuevo indicador de negocio. |

**Evidencia**

![Figura 6 - Hallazgo H-06](assets/Chapter-6/hallazgo-m6.png)

*Figura 6. Redundancia de componentes informativos al mostrar notificaciones de forma paralela en dos secciones de la pantalla.*

---

- **Hallazgo H-07**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Navegación por menú lateral                                                                                                                                                                                                                              |
| Ubicación               | Web App - Menú lateral de navegación (Sidebar)                                                                                                                                                                                                           |
| Problema identificado   | Texto truncado e incompleto en una opción del menú lateral                                                                                                                                                                                               |
| Severidad               | 1                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Diseño estético y minimalista                                                                                                                                                                                                                            |
| Descripción             | En la parte inferior del menú de navegación lateral (sidebar), la etiqueta del último botón ("Administración d...") o ("Personal adminis...") es demasiado larga para el ancho predeterminado del contenedor. Al no caber, el texto se corta abruptamente con puntos suspensivos. Aunque esto no impide hacer clic en el botón, da un aspecto visual poco profesional y descuidado a la interfaz. |
| Impacto para el usuario | Afecta negativamente la estética visual y la legibilidad inmediata de las opciones de menú, requiriendo que el usuario adivine o deduzca el significado completo de la etiqueta.                                                                         |
| Recomendación           | La mejor práctica en diseño de menús es utilizar etiquetas cortas y directas. Se recomienda cambiar el texto a una alternativa más concisa (por ejemplo, "Administración", "Personal" o "Usuarios"). Si por reglas de negocio es obligatorio mantener el texto original completo, se debe implementar un atributo de accesibilidad tipo tooltip (título emergente) nativo en HTML (title="Personal administration") o (title="Administración de personal") que se muestre cuando el usuario pase el cursor (hover) sobre el botón. |

**Evidencia**

![Figura 7 - Hallazgo H-07](assets/Chapter-6/hallazgo-m7.png)

*Figura 7. Etiqueta de navegación truncada por restricciones de ancho en el menú lateral.*

---

- **Hallazgo H-08**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Gestión de inventario (Edición de productos)                                                                                                                                                                                                             |
| Ubicación               | Web App - Menú contextual de acciones en listado de productos                                                                                                                                                                                            |
| Problema identificado   | La acción "Editar" producto en el menú contextual no responde ni ofrece retroalimentación                                                                                                                                                                |
| Severidad               | 4                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Visibilidad del estado del sistema / Control y libertad del usuario                                                                                                                                                                                      |
| Descripción             | Al abrir el menú de acciones (icono de tres puntos) en un producto específico y seleccionar la opción "Editar", la interfaz no responde de ninguna manera. No se abre ningún modal, ni se redirige a otra vista, ni se muestra ningún mensaje de error. Esta falta de respuesta bloquea por completo la capacidad del usuario para actualizar la información del inventario. |
| Impacto para el usuario | Bloqueo crítico de una función principal del sistema, rompiendo la confianza del usuario al no proveer ningún tipo de respuesta o indicativo de fallo tras ejecutar una acción.                                                                          |
| Recomendación           | Revisar el evento de clic asociado a la opción "Editar" en el código (ej. @click en Vue). Asegurar que el componente modal de edición esté correctamente importado y que la variable reactiva que controla su visibilidad cambie a verdadero (true). Además, verificar en la consola del navegador si existe algún error de JavaScript bloqueando la ejecución del evento. |

**Evidencia**

![Figura 8 - Hallazgo H-08](assets/Chapter-6/hallazgo-m8.png)

*Figura 8. Interfaz de listado de productos donde la opción del menú contextual no gatilla acción alguna.*

---

- **Hallazgo H-09**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Gestión de inventario (Eliminación de productos)                                                                                                                                                                                                         |
| Ubicación               | Web App - Menú contextual de acciones en listado de productos                                                                                                                                                                                            |
| Problema identificado   | Fallo en la funcionalidad de eliminación y uso de alertas nativas del navegador                                                                                                                                                                          |
| Severidad               | 4                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Prevención de errores / Diseño estético y minimalista                                                                                                                                                                                                    |
| Descripción             | Al intentar eliminar un producto mediante el menú de acciones, ocurren dos problemas graves: primero, el sistema lanza un cuadro de diálogo alert() nativo del navegador para confirmar la acción, lo cual rompe completamente la estética y consistencia del diseño de la aplicación. Segundo, tras confirmar la acción en dicho cuadro, el producto no se elimina del listado, fallando en su propósito principal. |
| Impacto para el usuario | Pérdida de integridad funcional (error crítico al no eliminar el elemento solicitado) acoplada a una experiencia visual deficiente que devalúa el estándar de diseño de la plataforma.                                                                    |
| Recomendación           | Reemplazar el uso de alert() o confirm() nativos de JavaScript por un componente modal de confirmación diseñado específicamente para la aplicación (que siga el sistema de diseño actual). En cuanto a la funcionalidad, se debe depurar la petición HTTP de tipo DELETE hacia el servidor para identificar por qué no se está completando la eliminación, y actualizar el estado local del listado (la tabla) para que el producto desaparezca de la vista inmediatamente después de una respuesta exitosa. |

**Evidencia**

![Figura 9 - Hallazgo H-09](assets/Chapter-6/hallazgo-m9.png)

*Figura 9. Cuadro de diálogo nativo del navegador interfiriendo con la interfaz gráfica en un flujo de eliminación fallido.*

---

- **Hallazgo H-10**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Creación y registro de "Kits"                                                                                                                                                                                                                            |
| Ubicación               | Web App - Formulario de nuevo Kit                                                                                                                                                                                                                        |
| Problema identificado   | Falta de validación y mensajería de error al intentar guardar un "Kit" con campos obligatorios vacíos                                                                                                                                                    |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores                                                                                                                                                                                  |
| Descripción             | En el formulario de creación de un nuevo "Kit", si el usuario omite un campo obligatorio (como el nombre del kit) e intenta guardar los cambios, el sistema simplemente falla silenciosamente. No se guarda el registro, pero tampoco se resalta el campo faltante ni se muestra ningún mensaje de advertencia. El usuario se queda sin saber qué hizo mal o por qué su acción no tuvo efecto. |
| Impacto para el usuario | Genera incertidumbre y desprotección operativa al procesar envíos inválidos de manera silenciosa, impidiendo que el usuario sepa cómo corregir la información errónea introducida.                                                                       |
| Recomendación           | Implementar validación de formularios en el frontend antes de enviar los datos. Se debe deshabilitar el botón de guardar si los campos obligatorios están vacíos o, preferiblemente, si el usuario hace clic en guardar, resaltar los campos faltantes en color rojo y mostrar un mensaje de error explícito debajo del campo (ej. "El nombre del kit es obligatorio"), indicándole claramente cómo corregir el problema. |

**Evidencia**

![Figura 10 - Hallazgo H-10](assets/Chapter-6/hallazgo-m10.png)

*Figura 10. Formulario de creación procesando datos inválidos de forma silenciosa sin indicar campos obligatorios omitidos.*

--- 

- **Hallazgo H-11**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Visualización de la sección de Proveedores                                                                                                                                                                                                               |
| Ubicación               | Web App - Sección Proveedores                                                                                                                                                                                                                            |
| Problema identificado   | Duplicidad innecesaria del título de la sección en la cabecera                                                                                                                                                                                           |
| Severidad               | 1                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Diseño estético y minimalista                                                                                                                                                                                                                            |
| Descripción             | En la vista actual, el título "Proveedores" aparece repetido dos veces de forma casi consecutiva: una vez en la barra superior (Topbar) junto al icono de notificaciones, y otra vez inmediatamente debajo, en rojo, como encabezado del contenedor principal. Esta redundancia no aporta valor informativo, genera ruido visual y desperdicia espacio vertical en la pantalla. |
| Impacto para el usuario | Sobrecarga la interfaz con información repetida de manera adyacente y reduce el área útil vertical destinada a la visualización de los datos operativos de los proveedores.                                                                               |
| Recomendación           | Eliminar el segundo título ("Proveedores" en texto rojo) del área de contenido para mantener un diseño más limpio, dejando únicamente el título de la barra superior como indicador global de la vista. Alternativamente, ese espacio inferior puede usarse para un componente de breadcrumbs (migas de pan) si la navegación se vuelve más profunda. |

**Evidencia**

![Figura 11 - Hallazgo H-11](assets/Chapter-6/hallazgo-m11.png)

*Figura 11. Redundancia visual por duplicidad del título identificador de la sección en la cabecera de la pantalla.*

---

- **Hallazgo H-12**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Búsqueda y filtrado de proveedores                                                                                                                                                                                                                       |
| Ubicación               | Web App - Barra de búsqueda en la sección Proveedores                                                                                                                                                                                                    |
| Problema identificado   | Falta de interactividad y retroalimentación en el botón "Filtrar"                                                                                                                                                                                        |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Visibilidad del estado del sistema / Flexibilidad y eficiencia de uso                                                                                                                                                                                    |
| Descripción             | El usuario puede ingresar texto en el campo de búsqueda ("Buscar"), pero al hacer clic en el botón contiguo de "Filtrar", el sistema no ejecuta ninguna acción. La tabla no se actualiza, la página no recarga y no se muestra ningún mensaje de error o estado de "cargando". El botón actúa como un elemento estático, lo que rompe la expectativa del usuario y frustra la tarea de búsqueda. |
| Impacto para el usuario | Bloquea la capacidad de filtrar registros rápidamente, forzando al usuario a realizar una lectura visual manual y reduciendo drásticamente la eficiencia en la localización de datos.                                                                    |
| Recomendación           | Asegurar que el evento de clic del botón esté correctamente enlazado a la función de filtrado en el controlador del componente. Si la funcionalidad de búsqueda aún está en desarrollo, el botón debe estar visualmente deshabilitado (disabled) o, al hacer clic, debería mostrar una notificación tipo toast indicando que la función estará disponible próximamente. |

**Evidencia**

![Figura 12 - Hallazgo H-12](assets/Chapter-6/hallazgo-m12.png)

*Figura 12. Componente de filtrado inactivo que no procesa el texto ingresado en el campo de búsqueda.*

---

- **Hallazgo H-13**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Gestión de proveedores (Eliminación de registros)                                                                                                                                                                                                        |
| Ubicación               | Web App - Listado de la sección Proveedores                                                                                                                                                                                                              |
| Problema identificado   | Uso de alertas nativas para confirmar eliminación y ausencia de estado de carga durante el procesamiento                                                                                                                                                 |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Consistencia y estándares / Visibilidad del estado del sistema                                                                                                                                                                                           |
| Descripción             | La acción de eliminar un proveedor presenta dos fallos de experiencia. Primero, invoca un cuadro de diálogo nativo del navegador (confirm()) en lugar de un modal propio, rompiendo la consistencia visual del sistema. Segundo, tras aceptar la alerta, el sistema tarda entre 3 y 5 segundos en remover el registro de la tabla sin mostrar ningún indicador visual de carga (spinner), dejando al usuario con la incertidumbre de si el clic funcionó o si el sistema se colgó. |
| Impacto para el usuario | Provoca incertidumbre operativa prolongada al no dar señales de que la solicitud está en proceso, lo que puede inducir al usuario a presionar el botón repetidamente o a asumir que la aplicación falló.                                                 |
| Recomendación           | Al desarrollar sistemas CRUD integrales para el control de operaciones, el estándar en frameworks modernos exige mantener todo el flujo dentro de la interfaz gráfica propia. Se debe reemplazar la alerta nativa por un componente modal personalizado para la confirmación. Además, es obligatorio inyectar un estado de carga local (por ejemplo, deshabilitar el icono del basurero y cambiarlo por un spinner) durante los segundos que tarde la petición HTTP, actualizando la tabla de inmediato al recibir la respuesta exitosa 200 OK. |

**Evidencia**

![Figura 13 - Hallazgo H-13](assets/Chapter-6/hallazgo-m13.png)

*Figura 13. Flujo de eliminación que utiliza cuadros nativos de confirmación y procesa el borrado con retraso y sin retroalimentación.*

---

- **Hallazgo H-14**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Visualización de la sección de Ventas                                                                                                                                                                                                                    |
| Ubicación               | Web App - Sección Gestión de Ventas                                                                                                                                                                                                                      |
| Problema identificado   | Duplicidad innecesaria del título de la sección ("Gestión de Ventas")                                                                                                                                                                                    |
| Severidad               | 1                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Diseño estético y minimalista                                                                                                                                                                                                                            |
| Descripción             | Al igual que en la vista de Proveedores, la pantalla de Ventas presenta el título "Gestión de Ventas" repetido dos veces seguidas (en la barra superior y como encabezado del área de trabajo). Esto es redundante y ocupa espacio vertical que podría ser aprovechado para mostrar más productos en la tabla sin necesidad de hacer scroll. |
| Impacto para el usuario | Degrada la armonía visual de la interfaz mediante repetición de datos y limita artificialmente el espacio disponible para desplegar las filas de la tabla de ventas.                                                                                     |
| Recomendación           | Mantener la consistencia en el diseño de las plantillas (layouts). Se debe remover el título secundario del contenedor principal y conservar únicamente el título de la barra superior.                                                                  |

**Evidencia**

![Figura 14 - Hallazgo H-14](assets/Chapter-6/hallazgo-m14.png)

*Figura 14. Pantalla de ventas con redundancia estructural en la ubicación y despliegue del título principal.*

---

- **Hallazgo H-15**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Búsqueda y filtrado de productos para la venta                                                                                                                                                                                                           |
| Ubicación               | Web App - Módulo de ventas (Barra de búsqueda)                                                                                                                                                                                                           |
| Problema identificado   | Falta de interactividad en el botón "Filtro" de la barra de búsqueda                                                                                                                                                                                     |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Visibilidad del estado del sistema / Flexibilidad y eficiencia de uso                                                                                                                                                                                    |
| Descripción             | El usuario puede ingresar el nombre de un producto (ej. "Bolsa Papitas") en el input de texto, pero al presionar el botón "Filtro", la acción es ignorada por el sistema. La tabla de productos no se filtra ni se muestra ningún mensaje, lo que obliga al usuario a buscar el ítem manualmente entre toda la lista, reduciendo drásticamente la eficiencia en el proceso de venta. |
| Impacto para el usuario | Genera fricción operativa severa y retrasos en la atención al cliente, forzando búsquedas manuales ineficientes dentro de catálogos extensos de productos.                                                                                                |
| Recomendación           | Vincular correctamente el evento @click (o equivalente según el framework utilizado) del botón al método de filtrado. Dado que los productos ya están listados en el DOM, se recomienda implementar un filtrado local (procesando el array de datos en el cliente) para que la búsqueda sea instantánea, en lugar de hacer una nueva petición al servidor. |

**Evidencia**

![Figura 15 - Hallazgo H-15](assets/Chapter-6/hallazgo-m15.png)

*Figura 15. Botón de filtro de productos inerte ante las solicitudes de interacción del usuario.*

---

- **Hallazgo H-16**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Configuración del carrito de compras (Añadir/Modificar ítems)                                                                                                                                                                                            |
| Ubicación               | Web App - Sección Ventas (Panel central de productos y Panel derecho de carrito)                                                                                                                                                                         |
| Problema identificado   | Latencia excesiva sin retroalimentación visual al agregar productos o modificar cantidades en el carrito                                                                                                                                                 |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Visibilidad del estado del sistema / Flexibilidad y eficiencia de uso                                                                                                                                                                                    |
| Descripción             | Al hacer clic en el ícono verde para agregar un producto al "Borrador salida de productos" (carrito), o al intentar aumentar su cantidad, el sistema sufre una latencia aproximada de 3 segundos antes de reflejar el cambio en el panel derecho. Durante este tiempo, la interfaz no bloquea el botón ni muestra un indicador de carga, lo que genera confusión e invita al usuario a hacer múltiples clics accidentales pensando que la acción no funcionó. |
| Impacto para el usuario | Induce a la carga errónea o duplicada de cantidades en el carrito de compras debido a la falta de respuesta en tiempo real, entorpeciendo el flujo de checkout.                                                                                         |
| Recomendación           | Implementar un patrón de diseño de Interfaz de Usuario Optimista (Optimistic UI). Cuando se desarrolla un sistema transaccional donde la agilidad operativa es clave, las actualizaciones de estado (como añadir a un carrito) deben reflejarse instantáneamente en la pantalla manipulando el estado local del frontend. La sincronización de estos datos con la base de datos a través de peticiones HTTP debe ocurrir en segundo plano. Adicionalmente, si es estrictamente necesario esperar al servidor, se debe cambiar el icono del carrito por un pequeño spinner de carga durante esos 3 segundos. |

**Evidencia**

![Figura 16 - Hallazgo H-16](assets/Chapter-6/hallazgo-m16.png)

*Figura 16. Retraso visual en la actualización del desglose de productos añadidos al carrito de salida.*

---

- **Hallazgo H-17**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Gestión de inventario multiidioma (Creación de categorías/productos)                                                                                                                                                                                     |
| Ubicación               | Web App - Sección Inventario (Modales "New Category" y "New product" en idioma inglés)                                                                                                                                                                    |
| Problema identificado   | Exposición de variables internas de código (llaves de traducción) al cambiar el idioma a inglés                                                                                                                                                          |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Relación entre el sistema y el mundo real / Prevención de errores                                                                                                                                                                                        |
| Descripción             | Al cambiar el idioma de la aplicación a inglés (botón "EN") y abrir los modales de creación en la sección de Inventario (como "New Category" o "New product"), el sistema falla al renderizar los textos. En lugar de mostrar lenguaje natural, expone las llaves o variables internas del diccionario de internacionalización (por ejemplo: inventory.newCategory, inventory.categoryNamePlaceholder, inventory.isActive). Esto confunde gravemente al usuario final, quien no tiene por qué entender la estructura del código, dificultando la correcta inserción de datos. |
| Impacto para el usuario | Rompe la comprensión de la interfaz de usuario, impidiendo que operadores angloparlantes entiendan qué datos introducir en los campos del formulario.                                                                                                    |
| Recomendación           | Revisar la configuración del paquete de internacionalización (i18n) en el código fuente. Se debe verificar el archivo del diccionario correspondiente al idioma inglés (ej. en.json o en.js) e incluir todas las llaves faltantes que se están utilizando en la vista de inventario con sus respectivas traducciones legibles. Adicionalmente, configurar un valor de retroceso (fallback locale) para que, en caso de faltar una traducción en inglés, el sistema muestre el texto en español por defecto en lugar de la variable de código. |

**Evidencia**

![Figura 17 - Hallazgo H-17](assets/Chapter-6/hallazgo-m17.png)

*Figura 17. Despliegue de variables lógicas e identificadores del sistema de traducción en lugar de cadenas de texto adaptadas.*

---

- **Hallazgo H-18**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Visualización de la sección de Reportes                                                                                                                                                                                                                  |
| Ubicación               | Web App - Sección Reports                                                                                                                                                                                                                                |
| Problema identificado   | Duplicidad innecesaria del título de la sección ("Reports")                                                                                                                                                                                              |
| Severidad               | 1                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Diseño estético y minimalista                                                                                                                                                                                                                            |
| Descripción             | Siguiendo el mismo patrón de error visual encontrado en las vistas de Proveedores y Ventas, la pantalla de Reportes muestra el título duplicado: uno en la barra superior y otro en texto rojo justo debajo, en el área de contenido. Esta repetición es redundante, no aporta nueva información al usuario y resta espacio valioso que podría utilizarse para visualizar los datos o los gráficos de los reportes. |
| Impacto para el usuario | Satura de manera reiterada la visualización del entorno de trabajo, restando espacio para gráficos analíticos complejos o tablas de datos consolidadas.                                                                                                  |
| Recomendación           | Estandarizar el diseño (layout) de las vistas principales del sistema. Se debe eliminar el título secundario (el texto rojo dentro del contenedor) en esta y todas las demás pantallas, centralizando la indicación de la vista actual únicamente en la barra de navegación superior. |

**Evidencia**

![Figura 18 - Hallazgo H-18](assets/Chapter-6/hallazgo-m18.png)

*Figura 18. Sección analítica que presenta duplicidad estética de su título descriptivo.*

---

- **Hallazgo H-19**

| Campo                   | Detalle                                                                                                                                                                                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tarea evaluada          | Registro de personal y asignación de permisos                                                                                                                                                                                                            |
| Ubicación               | Web App - Modal "Nuevo Personal"                                                                                                                                                                                                                         |
| Problema identificado   | Modal de creación de personal atascado en estado de carga indefinido tras una operación exitosa                                                                                                                                                          |
| Severidad               | 3                                                                                                                                                                                                                                                        |
| Heurística vulnerada    | Visibilidad del estado del sistema / Prevención de errores                                                                                                                                                                                               |
| Descripción             | Al completar el formulario para "Nuevo Personal", asignar los permisos correspondientes y hacer clic en "Guardar", el botón cambia a un estado de carga (spinner) y se congela indefinidamente. La ventana modal nunca se cierra ni se muestra un mensaje de confirmación. Sin embargo, si el usuario observa la tabla atenuada en el fondo, puede notar que el nuevo registro sí fue creado y añadido al sistema. Esta falsa retroalimentación de "procesando" hace creer al administrador que el sistema falló, lo que puede inducirlo a cancelar, refrescar la página o intentar crear al mismo usuario duplicado. |
| Impacto para el usuario | Genera desconfianza e incertidumbre en operaciones críticas de personal, propiciando que el administrador intente registrar al mismo empleado varias veces de manera redundante.                                                                         |
| Recomendación           | Corregir la resolución de la promesa (Promise) de la petición HTTP en el frontend. La lógica del componente debe actualizar el estado de carga (isLoading = false) e invocar la función para cerrar el modal automáticamente tan pronto como el servidor devuelva un código de éxito (ej. 201 Created o 200 OK). Adicionalmente, se debe limpiar el formulario para futuras inserciones y mostrar una notificación temporal (toast) que confirme explícitamente: "Usuario creado con éxito". |

**Evidencia**

![Figura 19 - Hallazgo H-19](assets/Chapter-6/hallazgo-m19.png)

*Figura 19. Bloqueo visual indefinido del formulario de alta a pesar del correcto registro de la entidad en segundo plano.*


#### 6.4.2.4. Resumen de modificaciones para subsanar hallazgos.
A partir de los hallazgos recibidos en la auditoría externa, el equipo Stoq priorizó los recursos del Sprint actual en resolver las fallas críticas de severidad alta (3 y 4), las cuales impactaban directamente la operabilidad y transaccionalidad de StockWise. 

| # | Hallazgo original | Severidad | Acción tomada | Estado |
| :--- | :--- | :---: | :--- | :--- |
| **2** | El enlace de "Olvidaste tu contraseña" no dirige al flujo de recuperación, recargando la vista actual. | 3 | Se corrigió el enrutamiento (routing) en el frontend, asignando la ruta `/auth/recovery` al enlace para dirigir correctamente al usuario al flujo de restablecimiento de credenciales. | Completado |
| **4** | Redirección inesperada a la vista de "Ajustes" al refrescar el Dashboard. | 3 | Se reconfiguraron los guards y las condiciones del enrutador para asegurar que el sistema retenga y respete la URL activa (`/dashboard`) tras un refresco de página. | Completado |
| **8** | La acción "Editar" producto en el menú contextual no responde ni ofrece retroalimentación. | 4 | Se corrigió el evento de escucha (`@click`) en el menú contextual del inventario y se reparó la variable reactiva que controla la apertura del modal de edición. | Completado |
| **9** | Fallo en la funcionalidad de eliminación y uso de alertas nativas del navegador en Productos. | 4 | Se reemplazó la alerta nativa por un modal de confirmación integrado en la UI y se depuró la petición HTTP `DELETE` junto con la actualización inmediata del estado local de la tabla. | Completado |
| **10** | Falta de validación y mensajería de error al intentar guardar un "Kit" con campos obligatorios vacíos. | 3 | Se integró validación de formularios en el frontend que resalta los campos vacíos obligatorios en rojo, bloquea el botón de guardado y despliega mensajes guía específicos. | Completado |
| **12** | Falta de interactividad y retroalimentación en el botón "Filtrar". | 3 | Se vinculó la función de filtrado al evento de clic del botón y se configuró un estado visual deshabilitado (`disabled`) en caso de que el campo de búsqueda se encuentre vacío. | Completado |
| **13** | Uso de alertas nativas para confirmar eliminación y ausencia de estado de carga durante el procesamiento en Proveedores. | 3 | Se sustituyó la confirmación nativa por un componente modal y se inyectó un spinner de carga local en la tabla para indicar que la petición de borrado está en proceso. | Completado |
| **15** | Falta de interactividad en el botón "Filtro" de la barra de búsqueda de Ventas. | 3 | Se enlazó el botón de filtrado a un método de procesamiento local sobre el arreglo de datos del cliente para ofrecer búsquedas e iteraciones instantáneas. | Completado |
| **16** | Latencia excesiva sin retroalimentación visual al agregar productos o modificar cantidades en el carrito. | 3 | Se aplicó un patrón de Interfaz de Usuario Optimista (Optimistic UI) para reflejar los cambios en el carrito de inmediato en el cliente mientras la petición se procesa en segundo plano. | Completado |
| **17** | Exposición de variables internas de código (llaves de traducción) al cambiar el idioma a inglés. | 3 | Se completaron los diccionarios de internacionalización (`en.json`) en las vistas de inventario y se configuró un *fallback locale* hacia el español para prevenir la visualización de código. | Completado |
| **19** | Modal de creación de personal atascado en estado de carga indefinido tras una operación exitosa. | 3 | Se corrigió la resolución de la promesa en el envío del formulario para forzar el cierre automático del modal, limpiar los inputs y disparar una notificación toast de éxito. | Completado |

Los cambios de mayor prioridad (severidad 3 o 4) fueron atendidos en su totalidad y desplegados antes del cierre del Sprint actual. Por otro lado, los hallazgos de severidad menor (1 y 2), asociados principalmente a duplicidades visuales y ajustes menores de diseño estético, fueron trasladados al Product Backlog para ser planificados en futuras iteraciones de mantenimiento UI.


<div style="page-break-after: always;"></div>


# Capitulo VII: DevOps Practices

## 7.1. Continuous Integration

### 7.1.1. Tools and Practices

En StockWise usamos GitHub como repositorio central para el control de versiones y la colaboración del equipo. La integración continua se plantea como una práctica clave para validar los cambios realizados en el proyecto antes de integrarlos a ramas principales, asegurando que el código compile correctamente y que las pruebas automatizadas puedan ejecutarse de forma constante.

Las pruebas automatizadas son una parte importante de la calidad del producto; por eso el proceso de CI está organizado para considerar la ejecución de:

**Maven** — herramienta principal para gestionar dependencias, compilar el backend y ejecutar las pruebas del proyecto.

**JUnit** — framework utilizado para ejecutar pruebas automatizadas en Java, incluyendo pruebas unitarias y pruebas de integración.

**Cucumber (Gherkin)** — herramienta utilizada para casos BDD; los archivos `.feature` describen escenarios de comportamiento del sistema y se transforman en pruebas ejecutables.

**JUnit Platform** — componente utilizado para descubrir y ejecutar las pruebas dentro del entorno Java.

**GitHub** — plataforma utilizada como repositorio central para almacenar el código fuente, revisar cambios y evidenciar la colaboración del equipo.

**GitHub Actions** — herramienta considerada para automatizar el proceso de Continuous Integration mediante la ejecución del build y las pruebas en eventos como `push` o `pull_request`.

**GitFlow** — flujo de trabajo usado para organizar las ramas del proyecto, separando el desarrollo principal, funcionalidades, pruebas y versiones estables.

**Conventional Commits** — convención usada para mantener mensajes de commit claros, trazables y fáciles de revisar.

Prácticas aplicadas:

- Ejecutar la suite de pruebas antes de integrar cambios a ramas principales.

- Separar las pruebas por tipo según su propósito: Unit Tests, Integration Tests, BDD Tests y System Tests.

- Mantener las pruebas unitarias enfocadas en componentes pequeños, rápidos y aislados.

- Usar pruebas de integración para validar la comunicación entre módulos, servicios y endpoints del backend.

- Utilizar Cucumber y archivos `.feature` para mantener la trazabilidad entre User Stories, Acceptance Criteria y pruebas automatizadas.

- Ejecutar el build del backend con Maven para verificar que el proyecto compile correctamente.

- Revisar los resultados de las pruebas antes de aprobar o integrar cambios.

- Utilizar Conventional Commits para diferenciar cambios de funcionalidad, corrección, configuración o pruebas, por ejemplo: `test: add bdd scenarios for inventory features`.

- Mantener las ramas organizadas bajo GitFlow para evitar cambios directos sobre ramas estables.

- Registrar evidencias de ejecución mediante capturas, resultados de pruebas y commits en GitHub.

### 7.1.2. Build & Test Suite Pipeline Components

Nuestro objetivo es Compilar el backend y validar automáticamente que los cambios superen todas las pruebas (Unit, Integration, BDD) antes de permitir un merge o despliegue.

**Activadores (on):** `push` y `pull_request` en ramas `feature/*`, `develop` y `testing`.

**Pasos del pipeline:**

1. `actions/checkout@v4` — Clonar el repositorio.
2. `actions/setup-java@v4` — Instalar JDK 17 y habilitar caché de Maven.
3. `mvn clean compile` — Validar sintaxis y dependencias sin ejecutar pruebas.
4. `mvn verify` — Ejecutar la suite completa de pruebas.
5. Subir artefactos de resultados (archivos `.xml`) para auditoría.
6. Reportar estado en el PR.

**YAML de ejemplo** (`.github/workflows/build-test-suite.yml`):

yaml
name: Build & Test Suite

on:
  push:
    branches: [ develop, testing, 'feature/**' ]
  pull_request:
    branches: [ develop, testing ]

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    
    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Set up JDK 17
        uses: actions/setup-java@v4
        with:
          java-version: '17'
          distribution: 'temurin'
          cache: maven

      - name: Compile Backend
        run: mvn clean compile

      - name: Run Tests
        run: mvn verify

      - name: Upload test results
        if: always()
        uses: actions/upload-artifact@v4
        with:
          name: test-results
          path: |
            target/surefire-reports/*.xml
            target/failsafe-reports/*.xml


**Puntos clave técnicos:**

* Se fija el entorno en Java 17 tanto en el workflow como en el `<java.version>` del `pom.xml`, asegurando compatibilidad nativa con Spring Boot 3.x.
* Se utiliza `mvn verify` para ejecutar el ciclo completo. El `maven-surefire-plugin` se encarga de las pruebas unitarias y el `maven-failsafe-plugin` (previamente configurado en el POM) de las pruebas de integración y BDD.
* La caché de Maven reduce los tiempos de build. Los reportes de Surefire y Failsafe se exportan como artefactos para facilitar el análisis.
*  Si la fase de compilación o alguna prueba falla, el workflow se detiene y las reglas del repositorio impiden el merge.

## 7.2. Continuous Delivery

### 7.2.1. Tools and Practices

El pipeline de entrega continua (CD) del sistema de gestión de inventario fue implementado utilizando GitHub Actions como herramienta principal de automatización y orquestación de despliegues. El proyecto backend desarrollado en Java utiliza Maven como gestor de dependencias y compilación.

Las prácticas aplicadas durante el proceso de integración y despliegue fueron las siguientes:

- **Automatización de despliegue:** cada cambio aprobado en la rama testing ejecuta automáticamente el pipeline de despliegue hacia el entorno de pruebas.
- **Validación previa:** el sistema únicamente permite el despliegue de versiones que hayan superado satisfactoriamente las pruebas unitarias implementadas con JUnit.
- **Control de versiones:** se utilizó GitHub para la gestión colaborativa del código fuente mediante ramas (main, testing y ramas feature).
- **Trazabilidad:** los resultados de compilación y pruebas son almacenados automáticamente como artefactos del pipeline para fines de monitoreo y auditoría.
- **Buenas prácticas DevOps:** se aplicó integración continua y despliegue continuo para asegurar estabilidad, control y rapidez en las actualizaciones del sistema.

### 7.2.2. Stages Deployment Pipeline Components

El pipeline de despliegue continuo del sistema fue estructurado en diferentes etapas automatizadas que permiten validar, compilar y desplegar la aplicación de manera segura y controlada.

Las etapas implementadas fueron las siguientes:

-  Build: compilación automática del proyecto Java utilizando Maven para verificar la integridad del código fuente.
- Unit Testing: ejecución automática de pruebas unitarias sobre las entidades principales del sistema, como productos e inventario, utilizando JUnit.
- Package: generación del artefacto ejecutable .jar para el despliegue del sistema.
- Deploy to Testing: despliegue automático de la aplicación hacia el entorno de pruebas luego de aprobar correctamente las validaciones.
- Smoke Tests: ejecución de pruebas básicas para verificar el correcto funcionamiento de los módulos principales del sistema de inventario.
- Production Deployment: despliegue manual o controlado hacia producción una vez verificadas las pruebas del entorno testing.

## 7.3. Continuous deployment

### 7.3.1. Tools and Practices
El proceso de Continuous Deployment (CD) automático hacia producción únicamente deberá habilitarse cuando la suite de pruebas y los *smoke scenarios* presenten un nivel adecuado de robustez, confiabilidad y cobertura.

#### Recomendaciones

- No habilitar despliegues automáticos hacia producción sin mecanismos de control adicionales, tales como:
  - aprobación humana (*approval gate*),
  - estrategias de *feature flags*,
  - validaciones previas obligatorias.

- En caso de habilitar CD automático:
  - la rama `main` deberá ejecutar un workflow automatizado responsable de:
    1. construir la aplicación,
    2. ejecutar pruebas Unit, Integration y Specs,
    3. generar y publicar artefactos,
    4. y realizar el despliegue automático hacia la plataforma objetivo (por ejemplo, Railway o Azure).

- El pipeline de despliegue deberá incluir mecanismos de rollback automático:
  - ante la detección de fallos en los *smoke tests* posteriores al despliegue,
  - el sistema deberá revertir automáticamente a la última versión estable disponible.

#### Consideraciones adicionales

- Todo despliegue a producción deberá generar trazabilidad mediante logs, métricas y registros de auditoría.
- Se recomienda integrar monitoreo continuo y alertas automáticas para detectar degradaciones funcionales o de rendimiento posteriores al despliegue.

### 7.3.2. Production Deployment Pipeline Components

- **Source Control Management:** Git 
- **Build and compilation:** Vite, SWC (Speedy Web Compiler) y npm (Node Package Manager)
- **Artifact repository:** npm Public Registry (Registro público de npm) 


<div style="page-break-after: always;"></div>

# Conclusiones

El informe consolida el ciclo de vida de StockWise como solución SaaS orientada a pymes, startups y bodegas que hoy dependen de registros manuales o herramientas poco especializadas. La evidencia documentada (Lean UX, entrevistas, needfinding y especificación con user stories, backlog e impact mapping) muestra que el problema no es solo “falta de software”, sino falta de trazabilidad, consistencia de datos y visibilidad en tiempo real, lo que se traduce en quiebres de stock, sobrecostos y decisiones de compra poco informadas.

En términos de diseño e implementación, el trabajo demuestra que es viable abordar el dominio con arquitectura y modelado centrados en el negocio (contextos delimitados, diseño orientado a objetos y modelo de datos), complementados con experiencias diferenciadas en web y móvil y una API REST que actúa como contrato estable entre capas. La planificación por sprints y la entrega de evidencias (landing, frontends, app móvil nativa, backend y documentación de API) reflejan un producto coherente con la propuesta de valor: digitalizar inventario, ventas y alertas sin exigir al usuario una curva de adopción propia de un ERP tradicional.

La verificación y validación aportan un cierre técnico sólido: las pruebas unitarias e de integración garantizan la estabilidad del núcleo del dominio, mientras que el enfoque BDD con Gherkin conecta explícitamente los requisitos con el comportamiento observable. Asimismo, la incorporación del análisis estático de código eleva los estándares de mantenibilidad y seguridad, complementándose con validaciones heurísticas de usabilidad y auditorías de experiencia de usuario —tanto realizadas como recibidas— que aseguran un producto final intuitivo, robusto y centrado en el cliente.

Las prácticas DevOps demuestran una madurez alineada a las demandas de un entorno productivo. La automatización del pipeline de construcción y pruebas en la integración continua (CI) mitiga el riesgo de regresiones tempranas, mientras que el despliegue continuo (CD) y la estructuración del monitoreo y alertado en tiempo real (Continuous Monitoring) garantizan la alta disponibilidad de la plataforma y una capacidad de respuesta proactiva ante incidentes operativos antes de que afecten al usuario final.

Por otro lado, la adopción del desarrollo guiado por experimentos (Experiment-Driven Development) valida científicamente la evolución del producto. El planteamiento de hipótesis claras y el seguimiento riguroso de métricas de negocio del dominio (Domain Business Metrics) mitigan la incertidumbre del mercado, permitiendo orientar el esfuerzo de ingeniería y el backlog de producto hacia funcionalidades con éxito comercial comprobado y valor real para las organizaciones.

Finalmente, las soluciones de ingeniería implementadas demuestran un impacto multidimensional: reducen el riesgo financiero al alinear el desarrollo con experimentos validados y pipelines automatizados; minimizan el impacto ambiental y el gasto operativo en la nube optimizando la eficiencia computacional mediante análisis estático y políticas de monitoreo; y generan un beneficio social tangible al ofrecer una plataforma accesible, inclusiva y altamente disponible que democratiza la digitalización en entornos globales.

# Recomendaciones

1. Medición de valor en campo: validar con usuarios reales las hipótesis Lean UX (alertas, reportes, freemium) mediante encuestas o entrevistas de seguimiento y métricas de producto (activación, retención, conversión a planes premium), no solo con pruebas técnicas.

2. Cobertura y calidad de pruebas: mantener la separación Unit / Integration / BDD / System y ampliar gradualmente escenarios críticos (concurrencia, permisos IAM, reportes y alertas en condiciones límite) antes de aspirar a continuous deployment pleno hacia producción.

3. Observabilidad: al acercarse a despliegues productivos, incorporar de forma explícita logs estructurados, métricas y alertas de servicio (como ya se sugiere en el capítulo de DevOps), de modo que los fallos posteriores al despliegue sean detectables y reversibles.

4. Continuidad del pipeline: asegurar que el workflow de GitHub Actions y la publicación de artefactos de pruebas formen parte del flujo habitual del equipo (revisión en PR), de modo que la integración continua sea un requisito de merge, no solo documentación.
   
<div style="page-break-after: always;"></div>

# Bibliografia 

1. Dux Software. (2025, 9 abril). Dux Software: El Sistema de Gestión para tu Negocio. https://www.duxsoftware.com.ar/
2. Mecalux. (s. f.). Store fulfillment. Mecalux.pe. https://www.mecalux.pe/software/store-fulfillment
3. SoftDoIt. (s. f.). ▷Vendus: agiliza la gestión de tu punto de venta. https://www.softwaredoit.es/vendus/vendus.html


<div style="page-break-after: always;"></div>


# Anexos 

Enlace del repositorio repositorio: [https://github.com/upc-1ASI0732-2610-16879-Stoq](https://github.com/upc-1ASI0732-2610-16879-Stoq)

Enlace directo del reporte: [https://github.com/upc-1ASI0732-2610-16879-Stoq/Report.git](https://github.com/upc-1ASI0732-2610-16879-Stoq/Report.git)

Enlace Landing: [https://stockwiselanding.netlify.app/](https://stockwiselanding.netlify.app/)

Enlace Frontend: [https://stocktrack-frontend.vercel.app/auth/register](https://stocktrack-frontend.vercel.app/auth/register)

Enlace Backend: [https://stoq-web-backend.onrender.com/swagger-ui.html](https://stoq-web-backend.onrender.com/swagger-ui.html)

