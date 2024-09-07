**UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**

![Logotipo Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714691535/gmplcgrlsv9sihpusivm.png)

**SI572-2402-WV71 Desarrollo de Soluciones IOT**

Informe de Trabajo Final TB1

**Carrera:** Ingeniería de Software

**Ciclo:** 07

**Sección:** WV71

**Profesor:** Angel Augusto Velasquez Nuñez

**Startup:** Fractalies

**Producto:** Green Tools

**Integrantes:**

Miguel Angel Ramirez Alfaro (U20)

Lino Abraham Quenta Leon (U202022353)

Giovanni Andres Ramos Calderon (U20)

Jean Patrick Yemsi Sanchez Rios (U20)

Franco Felix Yance Gutierrez (U20)

**Agosto, 25 de 2024**

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|---------------------------|
| 1.0 | 2024-08-20 | Miguel Angel  | Versión inicial del informe |
| 1.1 | 2024-08-22 | Lino Quenta | Adición de la sección "Lean UX Process" |
| 1.2 | 2024-08-23 | Giovanni Andres | Corrección de errores en la sección "Competidores" |
| 1.3 | 2024-08-27 | Miguel Angel | Mejora de la sección "User Personas" basada en retroalimentación del docente |
| 1.4 | 2024-08-29 | Lino Quenta | Adición de la sección "Impact Mapping" |
| 2.0 | 2024-08-30 |Giovanni Andres| Reestructuración completa del informe para mejorar la coherencia |
| 2.1 | 2024-09-22 | Jean Patrick | Actualización de la sección "Software Architecture" |
| 2.3 | 2024-09-05 | Jean Patrick | Adición de la sección "Solution UX Design" |
| 2.4 | 2024-09-20 | Lino Quenta | Mejoras en las Hisotorias de Usuario.|
| 3.0 | 2024-09-26 | Giovanni Andres  | Mejoras en la arquitectura de C4 Model. |

Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
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
  
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
      - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1. Bounded Context: \<Bounded Context Name>](#421-bounded-context-bounded-context-name)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.6. Bounded Context Software Architecture Component Level Diagrams](#4216-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.7. Bounded Context Software Architecture Code Level Diagrams](#4217-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.1.7.1. Bounded Context Domain Layer Class Diagrams](#42171-bounded-context-domain-layer-class-diagrams)
      - [4.2.1.7.2. Bounded Context Database Design Diagram](#42172-bounded-context-database-design-diagram)

- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
  - [5.1. Style Guidelines](#51-style-guidelines)
    - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
  - [5.2. Information Architecture](#52-information-architecture)
    - [5.2.1. Organization Systems](#521-organization-systems)
    - [5.2.2. Labeling Systems](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    - [5.2.4. Searching Systems](#524-searching-systems)
    - [5.2.5. Navigation Systems](#525-navigation-systems)
  - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
    - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
    - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
  - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
    - [5.4.1. Applications Wireframes](#541-applications-wireframes)
    - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
    - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
    - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
  - [5.5. Applications Prototyping](#55-applications-prototyping)

- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
  - [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
    - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
  - [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
    - [6.2.1. Sprint 1](#621-sprint-1)
      - [6.2.1.1. Sprint Planning n](#6211-sprint-planning-n)
      - [6.2.1.2. Sprint Backlog n](#6212-sprint-backlog-n)
      - [6.2.1.3. Development Evidence for Sprint Review](#6213-development-evidence-for-sprint-review)
      - [6.2.1.4. Testing Suite Evidence for Sprint Review](#6214-testing-suite-evidence-for-sprint-review)
      - [6.2.1.5. Execution Evidence for Sprint Review](#6215-execution-evidence-for-sprint-review)
      - [6.2.1.6. Services Documentation Evidence for Sprint Review](#6216-services-documentation-evidence-for-sprint-review)
      - [6.2.1.7. Software Deployment Evidence for Sprint Review](#6217-software-deployment-evidence-for-sprint-review)
      - [6.2.1.8. Team Collaboration Insights during Sprint](#6218-team-collaboration-insights-during-sprint)
    - [6.2.2. Sprint 2](#622-sprint-2)
      - [6.2.2.1. Sprint Planning n](#6221-sprint-planning-n)
      - [6.2.2.2. Sprint Backlog n](#6222-sprint-backlog-n)
      - [6.2.2.3. Development Evidence for Sprint Review](#6223-development-evidence-for-sprint-review)
      - [6.2.2.4. Testing Suite Evidence for Sprint Review](#6224-testing-suite-evidence-for-sprint-review)
      - [6.2.2.5. Execution Evidence for Sprint Review](#6225-execution-evidence-for-sprint-review)
      - [6.2.2.6. Services Documentation Evidence for Sprint Review](#6226-services-documentation-evidence-for-sprint-review)
      - [6.2.2.7. Software Deployment Evidence for Sprint Review](#6227-software-deployment-evidence-for-sprint-review)
      - [6.2.2.8. Team Collaboration Insights during Sprint](#6228-team-collaboration-insights-during-sprint)
  - [6.3. Validation Interviews](#63-validation-interviews)
    - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
    - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
    - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
  - [6.4. Video About-the-Product](#64-video-about-the-product)

# Project Report Collaboration Insights

URL de nuestro repositorio para el Project Report:[ https://github.com/linoabraham/Fractalis](https://github.com/FractalisGrupo03IOT/InformeFinal)

## Desarrollo de actividades y colaboración

### Entrega 1 (TB1)

- **Miguel Angel**: Estructura inicial del informe y mejora de "User Personas".
- **Lino Quenta**: Adición de "Lean UX Process", "Impact Mapping", y mejoras en las historias de usuario.
- **Giovanni Andres**: Correcciones en "Competidores" y reestructuración del informe.
- **Jean Patrick**: Actualización de "Software Architecture" y adición de "Solution UX Design".


### Entrega 2 (TP1)

-----

### Entrega 3 (TB2)

-----

### Entrega 4 (TF1)

----

## Evidencia de colaboración

![image](url aca)




# Student Outcome

### Competencia ABET 5

| **Criterio**                                                                          | **Acciones realizadas**                                                                                      |
|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| **Criterio 1:** Trabaja en equipo para proporcionar liderazgo en forma conjunta        | - **Miguel Angel**: Lideró la creación de la estructura inicial del informe.                                 |
|                                                                                       | - **Lino Quenta**: Facilitó la adición de secciones clave, impulsando el progreso del equipo.                |
|                                                                                       | - **Giovanni Andres**: Reestructuró el informe, mejorando la coherencia general.                              |
|                                                                                       | - **Jean Patrick**: Coordinó la actualización de la arquitectura del sistema.                                |
| **Criterio 2:** Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | - **Miguel Angel**: Estableció la planificación inicial del informe.                                         |
|                                                                                       | - **Lino Quenta**: Promovió un entorno colaborativo al incluir secciones críticas como "Lean UX Process".     |
|                                                                                       | - **Giovanni Andres**: Aseguró la coherencia y alineación del equipo mediante la reestructuración del informe.|
|                                                                                       | - **Jean Patrick**: Cumplió los objetivos técnicos con la mejora de la arquitectura y el diseño UX.           |




# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Fractalis es una startup dedicada a transformar la agricultura mediante la innovación tecnológica. Nos especializamos en desarrollar soluciones que integran el Internet de las Cosas (IoT) y la automatización para empoderar a agricultores de todo el mundo. En Fractalis, creemos en la convergencia de tecnología y sostenibilidad para crear un futuro agrícola más eficiente y responsable. Nuestro objetivo es revolucionar el sector, brindando herramientas accesibles y escalables que mejoran la productividad, optimizan el uso de recursos y promueven prácticas agrícolas sostenibles. Fractalis es más que una startup; es un movimiento hacia la modernización de la agricultura global.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148057185847361546/logo.png" alt="logo" style="margin-bottom: 5px;" width="500"/>
</div>

- **Visión:** Nuestra visión en Fractalis es liderar la transformación global de la agricultura a través de la tecnología, empoderando a agricultores de todo el mundo con herramientas inteligentes que hagan la agricultura más eficiente, sostenible y resiliente. Aspiramos a ser un referente en la innovación agrícola, promoviendo un futuro donde la tecnología y la naturaleza trabajen en armonía para asegurar la seguridad alimentaria y el bienestar del planeta.

- **Misión:** En Fractalis, nuestra misión es desarrollar y proporcionar soluciones tecnológicas avanzadas que integren IoT y automatización, permitiendo a los agricultores optimizar la gestión de sus cultivos. Nos dedicamos a mejorar la eficiencia operativa, reducir el desperdicio de recursos y fomentar prácticas sostenibles, ayudando a agricultores de todos los tamaños a enfrentar los desafíos del futuro agrícola con éxito y responsabilidad.

### 1.1.2. Perfiles de integrantes del equipo
<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1156251884647092394/WIN_20230926_09_34_37_Pro.jpg" alt="Franco Felix Yance Gutierrez" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Yance Gutierrez, Franco Felix 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy una persona apasionada por la tecnología y la programación, siempre interesado en estar al día con las últimas tendencias y avances en el área. Me encanta trabajar en equipo y colaborar para idear soluciones innovadoras y efectivas a problemáticas de la vida real. También me atrae el mundo de las start-ups y cómo pueden tener un impacto positivo en la sociedad a través de la tecnología. Me caracterizo por tener un pensamiento analítico y creativo, y siempre busco dar distintos puntos de vista a la hora de realizar un trabajo. Estoy comprometido en seguir aprendiendo y contribuyendo al desarrollo de la industria de la tecnología. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148059889537662976/pic_1.jpg" alt="Checa Paolo" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Checa Apolinario, Paolo Sebastián
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Poseo conocimientos en programación en el entorno del lenguaje C++. Estoy dispuesto a aportar nuevas ideas al equipo, tengo fácil adaptación a los roles designados y buena organización. Soy responsable y dispongo de la capacidad para aportar ideas innovadoras en beneficio de nuestro proyecto.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148303043629162647/054020181E187.jpg" alt="Pozo Rodrigo" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Pozo Campos, Rodrigo Jair
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy estudiante de la carrera de ingeniería de software, me considero una persona responsable en mis entregas y apasionada por el mundo tecnológico. Siento que puedo aportar mucho de mi en este grupo para poder realizar un buen producto. Tengo conocimientos en algunos lenguajes de programación como C++, Python y en desarrollo web. Pienso que nuestro grupo de trabajo puede generar resultados satisfactorios en base a los entregables y evidencias que mostremos a lo largo del curso.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148370399395074108/Diseno_sin_titulo.png" alt="Arenas José"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Arenas Conde, José Anthony
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Por lo general, me veo a mí mismo como alguien capaz de superar adversidades y hábil en varios campos, como la expresión verbal y escrita. También poseo conocimientos en la elaboración de productos, adquiridos a través de cursos previos. Como miembro de este equipo, mi meta es contribuir a la creación de un producto de calidad que satisfaga las necesidades de nuestros usuarios. Asimismo, soy alguien que sabe trabajar en conjunto y ha participado en numerosas empresas grupales en el pasado. Tengo la habilidad de escuchar y comprometerse con mis colegas, además de estar dispuesto a aceptar responsabilidades y contribuir con mi esfuerzo para alcanzar las metas del equipo.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://cdn.discordapp.com/attachments/1148057148522233868/1148239074021351464/intranet_2020.jpg" alt="Cáceres Arnol"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Cáceres Bueno, Arnol Omar
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Me considero a mí mismo como una persona responsable, y apasionada por la tecnología. Poseo conocimientos en programación, en lenguajes como C++, C#, Java y Python. Me gusta aprender cosas nuevas y mejorar mis conocimientos, cuando no estoy estudiando me gusta leer, y escuchar música. Una de mis mejores cualidades es el trabajo en equipo, me considero alguien resiliente y productivo.
        </td>
    </tr>
</table>

## 1.2. Solution Profile

- **Nombre del Producto:** <br><br>

  GreenTools es una plataforma tecnológica innovadora que transforma la gestión agrícola a través de la integración de dispositivos IoT y tecnologías avanzadas. Disponible tanto en aplicaciones móviles como web, la plataforma permite a los agricultores monitorear y gestionar sus cultivos en tiempo real, optimizando el uso de recursos y mejorando la eficiencia operativa. <br><br>

- **Descripción del Producto:** <br><br>

  Utilizando dispositivos Arduino y sensores avanzados, GreenTools recoge datos precisos sobre las condiciones de los cultivos, incluyendo temperatura, humedad, luz y niveles de nutrientes. Cada dispositivo está registrado con un código de identificación único, facilitando su integración y control dentro del sistema. La plataforma también automatiza procesos críticos, como el riego y la ventilación, contribuyendo a reducir el desperdicio de recursos y a mejorar los rendimientos de los cultivos.<br><br>
GreenTools está diseñada para ser adaptable a las necesidades específicas de diferentes tipos de agricultores, con planes personalizados para dueños de invernaderos enfocados en monocultivos y propietarios de microcultivos que manejan múltiples tipos de cultivos simultáneamente.<br><br>

- **Monetización:** <br><br>

GreenTools opera bajo un modelo de negocio dual que combina suscripciones SaaS con el alquiler de equipos IoT, asegurando que todos los agricultores tengan acceso continuo a las herramientas y tecnologías necesarias para optimizar sus operaciones. <br><br>

- **Plan Monocultivo:** <br><br>

Este plan está diseñado para dueños de invernaderos que se especializan en un único tipo de cultivo. Ofrece acceso completo a las funcionalidades avanzadas de GreenTools, incluyendo monitoreo en tiempo real, análisis predictivo, informes detallados y soporte técnico prioritario. Además, este plan incluye el alquiler de dispositivos Arduino y sensores optimizados para el monocultivo, garantizando una alta precisión y eficiencia en la gestión de un solo tipo de cultivo.
 <br><br>

- **Plan Multicultivo:** <br><br>

Dirigido a dueños de microcultivos y agricultores que cultivan múltiples especies simultáneamente, este plan también ofrece acceso completo a todas las funcionalidades avanzadas de la plataforma. Incluye el alquiler de dispositivos Arduino y sensores diseñados para manejar una variedad de cultivos, proporcionando información específica y detallada para cada tipo de cultivo y facilitando la optimización del uso de recursos en entornos diversos. <br><br>

Ambos planes incluyen el alquiler de los equipos Arduino con sensores, lo que permite a los agricultores acceder a tecnología avanzada sin una inversión inicial significativa, haciendo que GreenTools sea una solución accesible y flexible. Además, la plataforma ofrece la posibilidad de adquirir productos y servicios adicionales a través de un marketplace interno, diversificando las fuentes de ingresos.<br><br>


### 1.2.1. Antecedentes y problemática

- **Who?** <br><br>

Nuestros usuarios son dueños de invernaderos y microcultivos que buscan optimizar la gestión y monitoreo de sus cultivos. Estos agricultores, a menudo pequeños y medianos, están interesados en mejorar la eficiencia y sostenibilidad de sus operaciones mediante la implementación de tecnología avanzada.<br><br>

- **What?** <br><br>

El problema que enfrentan nuestros usuarios es la falta de acceso a soluciones tecnológicas accesibles y efectivas que integren sensores IoT con herramientas de gestión agrícola. Esta carencia impide que los agricultores obtengan datos en tiempo real y automatizar procesos críticos, lo que resulta en una gestión ineficiente de los recursos y bajos rendimientos de sus cultivos.<br><br>

- **When?** <br><br>

El problema descrito se presenta de manera continua, cada vez que los agricultores intentan gestionar sus cultivos sin las herramientas tecnológicas adecuadas. Esto conduce a una pérdida constante de recursos, menores rendimientos y mayores dificultades para mantener prácticas agrícolas sostenibles.<br><br>

- **Where?** <br><br>

El problema se encuentra principalmente en las operaciones de pequeños y medianos agricultores, especialmente aquellos que operan invernaderos y microcultivos. Estos productores a menudo no tienen acceso a tecnologías avanzadas que les permitan optimizar sus procesos y competir eficazmente en el mercado. <br><br>

- **Why?** <br><br>

Nuestros usuarios no logran encontrar en el mercado soluciones tecnológicas que integren de manera efectiva los sensores IoT con la automatización de procesos agrícolas. Las opciones disponibles son a menudo costosas, difíciles de implementar o carecen de la funcionalidad necesaria para mejorar significativamente sus operaciones.<br><br>

- **How?** <br><br>

Para nuestros usuarios, resulta muy complicado encontrar una solución que no solo sea tecnológicamente avanzada, sino también accesible y fácil de usar. Esta problemática ha impulsado la creación de GreenTools, una plataforma que conectará sensores y dispositivos IoT en invernaderos y microcultivos, permitiendo a los agricultores monitorear, automatizar y optimizar sus operaciones de manera eficiente desde cualquier lugar.<br><br>

- **How much?** <br><br>

La problemática se origina debido a la falta de soluciones accesibles y efectivas en el mercado para la integración de IoT en la agricultura. Esto lleva a que los agricultores desperdicien recursos y obtengan bajos rendimientos, lo que afecta tanto la viabilidad económica de sus operaciones como su capacidad para practicar una agricultura sostenible. GreenTools abordará este vacío proporcionando una plataforma IoT intuitiva que permitirá a los agricultores mejorar significativamente la eficiencia y productividad de sus cultivos. <br><br>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

La gestión agrícola en pequeños y medianos invernaderos y microcultivos enfrenta desafíos considerables debido a la falta de integración tecnológica accesible y adaptable a sus necesidades específicas. A pesar de los avances tecnológicos significativos en la agricultura de precisión, la adopción de estas tecnologías entre los pequeños agricultores sigue siendo limitada. Esto se debe, en gran medida, a la ausencia de soluciones tecnológicas que no solo sean rentables, sino que también ofrezcan una interfaz fácil de usar y se adapten a las condiciones específicas de cada tipo de cultivo y entorno agrícola (Hundal et al., 2023).


Muchos agricultores intentan optimizar la gestión y monitoreo de sus cultivos con el objetivo de mejorar la eficiencia en el uso de recursos y aumentar la productividad. Sin embargo, se encuentran con barreras sustanciales, como la falta de acceso a herramientas de gestión que integren sensores IoT y sistemas de análisis de datos en tiempo real. Esta carencia no solo impide la optimización de procesos, sino que también resulta en una gestión ineficiente de los recursos, con consecuencias negativas tales como rendimientos bajos, desperdicio de insumos, y, en última instancia, una mayor vulnerabilidad frente a los cambios climáticos y las fluctuaciones del mercado (Dibbern et al., 2024).


Aunque existen tecnologías avanzadas que podrían abordar estos problemas, estas suelen ser prohibitivamente costosas y excesivamente complejas para los pequeños agricultores. La falta de recursos financieros y la dificultad para adquirir conocimientos técnicos necesarios para operar estas tecnologías agravan el problema, creando una brecha tecnológica significativa entre los grandes productores y los pequeños agricultores. Esta situación no solo limita la capacidad de los agricultores para acceder a datos críticos en tiempo real, sino que también restringe la automatización de procesos fundamentales que podrían mejorar la eficiencia operativa y la sostenibilidad de las operaciones agrícolas (Ahmad et al., 2025).


En este contexto, surge una necesidad urgente de desarrollar una solución integrada que haga uso de la tecnología IoT de una manera que sea accesible, rentable y fácil de implementar. Esta solución debe permitir a los pequeños y medianos agricultores monitorear y gestionar sus cultivos de manera más eficiente, ofreciendo herramientas que se ajusten a sus capacidades y necesidades específicas. Al ofrecer una plataforma que integre sensores IoT con sistemas de gestión agrícola, se podría facilitar un uso más eficiente de los recursos, aumentar los rendimientos y reducir los desperdicios, todo mientras se promueve una agricultura más sostenible y resiliente (Hundal et al., 2023; Dibbern et al., 2024).


La pregunta clave que nuestra startup busca resolver es: ¿Cómo podemos aplicar nuestro conocimiento tecnológico para ofrecer una plataforma accesible y eficaz que permita a los pequeños y medianos agricultores optimizar la gestión y monitoreo de sus cultivos? Al abordar esta cuestión, nuestra solución pretende cerrar la brecha tecnológica existente y proporcionar a los agricultores las herramientas necesarias para competir en un mercado cada vez más digitalizado.


#### 1.2.2.2. Lean UX Assumptions
**Business outcomes:**

-Los usuarios de GreenTools están interesados en optimizar la gestión y monitoreo de sus cultivos a través de la tecnología IoT.
-Los usuarios valoran la posibilidad de automatizar procesos agrícolas para mejorar la eficiencia operativa.
-Los usuarios desean una plataforma intuitiva, fácil de usar, que les permita gestionar sus cultivos desde cualquier lugar.
-Los usuarios buscan funcionalidades adicionales, como alertas personalizadas y análisis predictivos basados en datos históricos.
-La plataforma debe ser compatible con múltiples dispositivos y navegadores modernos.
-Los usuarios están dispuestos a pagar por planes de suscripción que incluyan el alquiler de equipos IoT avanzados.
-Los usuarios valoran el soporte técnico eficiente y la posibilidad de integrar sus operaciones agrícolas con otras herramientas de -gestión.


**Users: assumptions**

- **¿Quién es el usuario?**

Los usuarios de GreenTools son agricultores dueños de pequeños y medianos invernaderos y microcultivos, que buscan mejorar la eficiencia y sostenibilidad de sus operaciones mediante el uso de tecnología IoT. Estos usuarios valoran soluciones que les permitan obtener datos precisos y automatizar procesos clave en sus operaciones diarias.

- **¿Dónde encaja nuestro producto en su trabajo o vida?**

GreenTools se integra directamente en las actividades diarias de gestión agrícola, facilitando la optimización de recursos y mejorando la productividad a través de una interfaz que puede ser utilizada tanto en dispositivos móviles como en navegadores web.

- **¿Qué problema tiene nuestro producto? ¿Cómo se resuelve?**

El problema principal que aborda GreenTools es la falta de integración entre sensores IoT y herramientas de gestión agrícola accesibles. Se resuelve mediante una plataforma que permite a los agricultores monitorear, automatizar y optimizar sus operaciones en tiempo real, desde cualquier lugar, facilitando la toma de decisiones informadas y la mejora de la eficiencia operativa.

- **¿Cuándo y cómo es usado nuestro producto?**

GreenTools se utiliza de manera continua en la gestión diaria de cultivos. Los usuarios pueden acceder a la plataforma en cualquier momento, desde cualquier lugar, para monitorear las condiciones de sus cultivos, recibir alertas y automatizar procesos como el riego o la ventilación.

- **¿Qué características son importantes?**

Las características más importantes incluyen la capacidad de monitoreo en tiempo real, la automatización de procesos agrícolas, las alertas personalizadas, los análisis predictivos basados en datos históricos y la facilidad de integración con dispositivos IoT.

- **¿Cómo debe verse nuestro producto y comportarse?**

GreenTools debe tener una interfaz sencilla, intuitiva y responsive, que permita a los usuarios gestionar sus cultivos de manera eficiente sin complicaciones. La plataforma debe ser rápida, confiable y ofrecer un soporte técnico accesible para resolver cualquier problema que los usuarios puedan enfrentar.

#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que GreenTools será una herramienta invaluable para los agricultores que buscan mejorar la gestión de sus invernaderos y microcultivos mediante tecnología IoT. Sabremos que tuvimos éxito cuando más del 80% de nuestros usuarios expresen satisfacción con la plataforma y reporten mejoras en la eficiencia operativa.

- Creemos que la automatización de procesos agrícolas permitirá a los usuarios de GreenTools optimizar el uso de recursos y mejorar los rendimientos de sus cultivos. Sabremos que tuvimos éxito cuando los usuarios reporten un aumento significativo en el rendimiento de sus cultivos tras el uso de la plataforma.
  
- Creemos que los agricultores estarán dispuestos a suscribirse a GreenTools y alquilar los equipos IoT necesarios para la optimización de sus operaciones. Sabremos que tuvimos éxito cuando alcancemos una tasa de renovación de suscripciones superior al 70%.

- Creemos que la plataforma será utilizada por agricultores de pequeños y medianos invernaderos y microcultivos, siendo este nuestro segmento objetivo. Sabremos que tuvimos éxito cuando la mayoría de nuestros usuarios pertenezca a este segmento y encuentren valor en las funcionalidades de la plataforma.

- Creemos que una interfaz intuitiva y responsive es crucial para la adopción exitosa de GreenTools. Sabremos que tuvimos éxito cuando más del 80% de los usuarios reporten que la plataforma es fácil de usar y eficiente en encuestas de satisfacción.

#### 1.2.2.4. Lean UX Canvas

<div align=center>
    <img src="https://i.imgur.com/96Ok3zu.jpeg" alt="Canvas"/>
</div>

## 1.3. Segmentos objetivo


| Tipo de Usuario | Dueños de Invernaderos                                                                                                                                                                                                                                 | Propietarios de Microcultivos                                                                                                                                                                                               |
| :-------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Geográfico      | País: Perú <br><br> Zona residencial: No es relevante, pueden ser de diferentes zonas del país.                                                                                                                                                                                      | País: Perú <br><br> Zona residencial: No es relevante, pueden ser de diferentes zonas del país.                                                                                                                                                                          |
| Psicográfico    | Clase Social: Clase media y clase alta. <br><br> Estilo de vida: Personas con un fuerte interés en la agricultura moderna y la tecnología, que buscan maximizar el rendimiento y la sostenibilidad de sus cultivos mediante la integración de soluciones tecnológicas avanzadas.
 | Clase Social: Clase media y clase alta. <br><br> Estilo de vida: Individuos interesados en la diversificación de cultivos en espacios pequeños, que desean implementar tecnologías innovadoras para mejorar la eficiencia y sostenibilidad de sus prácticas agrícolas. |
| Demográfico     | Edad: Mayores de 30 años. <br><br> Nivel de Ingreso: Medio a alto, con capacidad para invertir en membresías y alquiler de equipos IoT. <br><br> Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte.                                                    | Edad: Mayores de 30 años. <br><br> Nivel de Ingreso: Medio a alto, con disposición para gastar en tecnología avanzada que optimice la producción agrícola.<br><br> 
Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte. <br><br> Estudios: Educación superior, con un interés marcado en temas tecnológicos y agrícolas.
                         |

<br><br>


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas
#### Segmento: Dueños de Invernaderos

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
### Cultivadores de invernadero

![Imagen de Cultivadores de invernadero](https://media.discordapp.net/attachments/1228537935368945717/1277297738538815602/Diagrama_en_blanco_-_Pagina_1_1.png?ex=66dd2277&is=66dbd0f7&hm=76955413de78a6701e14fe2f56c79f69b49266772ca2a19b51e60667d9ba1f4a&=&format=webp&quality=lossless&width=1025&height=345)

### Micro cultivo

![Imagen de Micro cultivo](https://media.discordapp.net/attachments/1228537935368945717/1277297738903589117/Diagrama_en_blanco_-_Pagina_1.png?ex=66dd2277&is=66dbd0f7&hm=dac1156e5fd3a1d76c553a76d72e6591a17365f1031ec626019c5e52a5326d4e&=&format=webp&quality=lossless&width=1025&height=345)


## 3.2. User Stories
### Epics

| Epic ID | Título                        | Descripción                                                                                                                                  |
|---------|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| EP1     | Landing Page                  | Desarrollo de la página de aterrizaje para Green Tools con secciones de encabezado, beneficios, características, planes y precios, testimonios y footer. |
| EP2     | Aplicación Móvil              | Desarrollo de la aplicación móvil en Flutter que incluye monitoreo en tiempo real, control remoto, visualización de datos históricos, gestión de perfiles de cultivo, alertas y notificaciones, y configuración de horarios de dispositivos. |
| EP3     | Aplicación Web                | Desarrollo de la aplicación web en Angular que incluye dashboard centralizado, administración de cultivos, análisis y reportes, gestión de dispositivos IoT, y gestión de usuarios y permisos. |
| EP4     | Backend, Lógica de Negocio e IoT   | Desarrollo del backend en Spring Boot para la gestión de cultivos, sensores, dispositivos, usuarios, automatización, integración con IoT y generación de reportes. Además, incluye la configuración de un simulador IoT utilizando Wokwi con ESP32 para la simulación de sensores y actuadores como un servo motor para la automatización. |

### Historias de Usuario - AgroVision

| Epic / Story ID | Título                                  | Descripción                                                                                                                                                        | Criterios de Aceptación                                                                                                                                                   | Relacionado con (Epic ID) |
|-----------------|-----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| EP1/US1         | Crear Encabezado Principal              | Como visitante, quiero ver un encabezado atractivo con el título y subtítulo de Green Tools para captar mi interés.                                                 | **SCENARIO 1**: Visualización del encabezado principal. <br> **Dado** que estoy en la landing page, **Cuando** veo el encabezado, **Entonces** debo ver el título "Green Tools: La Revolución en Cultivos Controlados de Precisión" y el subtítulo. | EP1                       |
| EP1/US2         | Mostrar Beneficios Clave                | Como visitante, quiero leer los beneficios clave de AgroVision para entender por qué elegirlo.                                                                     | **SCENARIO 1**: Lectura de beneficios clave. <br> **Dado** que estoy en la sección de beneficios, **Cuando** leo la sección, **Entonces** debo ver los beneficios clave como monitoreo en tiempo real, control inteligente, análisis y soporte. | EP1                       |
| EP1/US3         | Destacar Características Clave          | Como visitante, quiero conocer las características principales de Green Tools para evaluar sus capacidades.                                                         | **SCENARIO 1**: Visualización de características clave. <br> **Dado** que estoy en la sección de características, **Cuando** leo la sección, **Entonces** debo ver características como integración IoT avanzada, interfaz intuitiva, alertas, y personalización. | EP1             |
| EP1/US4         | Mostrar Planes y Precios                | Como visitante, quiero ver los planes y precios disponibles para elegir el que mejor se adapte a mis necesidades.                                                  | **SCENARIO 1**: Visualización de planes y precios. <br> **Dado** que estoy en la sección de planes y precios, **Cuando** leo la sección, **Entonces** debo ver una descripción clara de los planes Básico y Premium con llamadas a la acción correspondientes. | EP1           |
| EP1/US5         | Mostrar Testimonios y Casos de Éxito    | Como visitante, quiero leer testimonios y casos de éxito para ver cómo otros han mejorado con Green Tools.                                                          | **SCENARIO 1**: Visualización de testimonios y casos de éxito. <br> **Dado** que estoy en la sección de testimonios, **Cuando** leo la sección, **Entonces** debo ver testimonios reales de clientes y casos de éxito que demuestren los beneficios de AgroVision. | EP1           |
| EP1/US6         | Implementar Footer                      | Como visitante, quiero encontrar información de contacto y enlaces legales al final de la página para obtener más detalles y soporte.                              | **SCENARIO 1**: Visualización de footer. <br> **Dado** que estoy en el footer, **Cuando** leo la sección, **Entonces** debo ver enlaces a contacto, redes sociales, política de privacidad, y términos de servicio.                      | EP1                       |
| EP2/US1         | Monitoreo en Tiempo Real                | Como usuario, quiero ver datos en tiempo real de mis cultivos para monitorear sus condiciones actuales.                                                            | **SCENARIO 1**: Visualización de datos en tiempo real. <br> **Dado** que estoy en la aplicación móvil, **Cuando** accedo a la sección de monitoreo, **Entonces** debo ver gráficos interactivos con datos actualizados de temperatura, humedad y nutrientes. | EP2            |
| EP2/US2         | Control Remoto de Dispositivos          | Como usuario, quiero controlar dispositivos conectados desde la aplicación para gestionar mi cultivo.                                                              | **SCENARIO 1**: Control de dispositivos de forma remota. <br> **Dado** que estoy en la aplicación móvil, **Cuando** accedo a la sección de control remoto, **Entonces** debo poder encender/apagar dispositivos y ajustar parámetros manualmente o de forma automática. | EP2        |
| EP2/US3         | Visualización de Datos Históricos       | Como usuario, quiero ver datos históricos de mis cultivos para analizar tendencias y patrones.                                                                     | **SCENARIO 1**: Visualización de datos históricos. <br> **Dado** que estoy en la sección de datos históricos, **Cuando** accedo a los gráficos, **Entonces** debo poder seleccionar rangos de fechas y comparar diferentes períodos de tiempo.      | EP2                       |
| EP2/US4         | Gestión de Perfiles de Cultivo          | Como usuario, quiero crear y gestionar perfiles de cultivo personalizados para ajustar parámetros específicos.                                                    | **SCENARIO 1**: Creación y gestión de perfiles de cultivo. <br> **Dado** que estoy en la sección de perfiles de cultivo, **Cuando** creo o edito un perfil, **Entonces** debo poder ajustar parámetros como humedad, temperatura, y nutrientes, y guardar la configuración. | EP2         |
| EP2/US5         | Configuración de Alertas y Notificaciones| Como usuario, quiero recibir notificaciones sobre condiciones críticas para tomar acciones rápidamente.                                                             | **SCENARIO 1**: Configuración de alertas y notificaciones. <br> **Dado** que estoy en la aplicación móvil, **Cuando** se detecta una condición crítica, **Entonces** debo recibir una notificación push o local con información relevante sobre la situación del cultivo. | EP2       |
| EP2/US6         | Configuración de Horarios de Dispositivos| Como usuario, quiero programar horarios para los dispositivos conectados para automatizar tareas.                                                                  | **SCENARIO 1**: Programación de horarios de dispositivos. <br> **Dado** que estoy en la sección de configuración de horarios, **Cuando** configuro un horario, **Entonces** debo poder elegir fechas y horas, y guardar la configuración para que el dispositivo actúe automáticamente. | EP2      |
| EP2/US7         | Iniciar Sesión                          | Como usuario, quiero iniciar sesión en la aplicación para acceder a mis datos personales y configuraciones.                                                       | **SCENARIO 1**: Inicio de sesión. <br> **Dado** que estoy en la pantalla de inicio de sesión, **Cuando** ingreso mis credenciales, **Entonces** debo poder acceder a mi cuenta y ver mis datos personales.                         | EP2                       |
| EP3/US1         | Dashboard Centralizado                  | Como usuario, quiero ver una vista integral de todos mis cultivos y datos en tiempo real para un análisis centralizado.                                            | **SCENARIO 1**: Visualización de dashboard centralizado. <br> **Dado** que estoy en el dashboard, **Cuando** accedo a la vista centralizada, **Entonces** debo ver métricas clave, gráficos interactivos y mapas de calor sobre el estado de los cultivos y sensores. | EP3         |
| EP3/US2         | Administración de Cultivos              | Como usuario, quiero gestionar y configurar mis cultivos desde la aplicación web para ajustar sus parámetros.                                                     | **SCENARIO 1**: Administración de cultivos. <br> **Dado** que estoy en la sección de administración de cultivos, **Cuando** edito la configuración de un cultivo, **Entonces** debo poder ajustar parámetros específicos y ver el estado general del cultivo. | EP3      |
| EP3/US3         | Generación de Reportes                  | Como usuario, quiero generar y exportar reportes detallados sobre mis cultivos para análisis y seguimiento.                                                       | **SCENARIO 1**: Generación de reportes. <br> **Dado** que estoy en la sección de reportes, **Cuando** genero un reporte, **Entonces** debo poder personalizar el contenido, exportar en PDF o CSV, y ver un resumen visual de los datos. | EP3          |
| EP3/US4         | Gestión de Dispositivos IoT             | Como usuario, quiero gestionar dispositivos IoT conectados desde la web para ver su estado y ajustar configuraciones.                                             | **SCENARIO 1**: Gestión de dispositivos IoT. <br> **Dado** que estoy en la sección de gestión de dispositivos, **Cuando** accedo a la configuración de un dispositivo, **Entonces** debo ver su estado y poder ajustarlo o recibir actualizaciones sobre su rendimiento. | EP3     |
| EP3/US5         | Gestión de Usuarios y Permisos          | Como administrador, quiero gestionar cuentas de usuarios y permisos para controlar el acceso a las funcionalidades.                                                | **SCENARIO 1**: Gestión de usuarios y permisos. <br> **Dado** que estoy en la sección de gestión de usuarios, **Cuando** creo o actualizo un usuario, **Entonces** debo poder asignar roles, controlar permisos y gestionar accesos a diferentes funcionalidades. | EP3    |
| EP4/US1         | Gestión de Cultivos y Sensores          | Como desarrollador, quiero gestionar los cultivos y sensores en el backend para almacenar y actualizar datos.                                                      | **SCENARIO 1**: Gestión de cultivos y sensores. <br> **Dado** que un usuario interactúa con cultivos y sensores, **Cuando** se realizan cambios, **Entonces** el backend debe permitir la creación, actualización y consulta de cultivos y sensores. | EP4        |
| EP4/US2         | Control de Dispositivos y Automatización | Como desarrollador, quiero implementar la lógica para controlar dispositivos y aplicar reglas de automatización.                                                  | **SCENARIO 1**: Control de dispositivos y automatización. <br> **Dado** que se recibe una solicitud para controlar un dispositivo, **Cuando** el backend procesa el comando, **Entonces** debe actualizar el estado del dispositivo y aplicar las reglas de automatización correspondientes. | EP4    |
| EP4/US3         | Gestión de Usuarios y Accesos           | Como desarrollador, quiero gestionar la autenticación y permisos de usuarios para proteger el acceso a la plataforma.                                             | **SCENARIO 1**: Gestión de usuarios y accesos. <br> **Dado** que un usuario intenta autenticarse, **Cuando** proporciona credenciales válidas, **Entonces** el backend debe autenticar al usuario, generar un token JWT, y gestionar permisos de acceso según el rol. | EP4     |
| EP4/US4         | Integración con Dispositivos IoT        | Como desarrollador, quiero integrar con dispositivos IoT para enviar comandos y recibir datos.                                                                    | **SCENARIO 1**: Integración con dispositivos IoT. <br> **Dado** que se envía un comando a un dispositivo IoT, **Cuando** el backend lo procesa, **Entonces** debe enviar el comando al dispositivo y recibir datos actualizados.                  | EP4                       |
| EP4/US5         | Generación de Reportes                  | Como desarrollador, quiero generar reportes basados en datos históricos y actuales de cultivos.                                                                   | **SCENARIO 1**: Generación de reportes. <br> **Dado** que se solicita un reporte, **Cuando** el backend procesa la solicitud, **Entonces** debe generar un reporte detallado basado en datos históricos y actuales, y proporcionar los resultados en el formato solicitado. | EP4  |
| EP4/US6         | Gestión de Carga de IoT                 | Como desarrollador, quiero implementar un backend adicional para distribuir la carga o gestionar de manera más eficiente los datos que se recopilan de dispositivos IoT. | **SCENARIO 1**: Distribución de carga de IoT. <br> **Dado** que el backend principal no maneja eficientemente la carga de datos, **Cuando** se distribuye la carga al backend adicional, **Entonces** la latencia en la actualización de datos debe reducirse significativamente. | EP4 |
| EP4/US7         | Registro de Serial de Sensores IoT      | Como desarrollador, quiero registrar los seriales de los sensores IoT para mantener un control adecuado de los dispositivos conectados.                            | **SCENARIO 1**: Registro de serial de sensores IoT. <br> **Dado** que un nuevo sensor IoT es conectado, **Cuando** se registra su serial en el sistema, **Entonces** debe quedar asociado al dispositivo correspondiente y visible en el backend para su gestión. | EP4 |
| EP4/US8         | Configuración de Simulación IoT en Wokwi| Como desarrollador, quiero configurar la simulación de dispositivos IoT en Wokwi utilizando un ESP32 para probar la integración y funcionalidad de sensores y actuadores. | **SCENARIO 1**: Configuración de simulación en Wokwi. <br> **Dado** que el backend está conectado a la plataforma de simulación, **Cuando** el ESP32 recibe comandos o envía datos, **Entonces** debo poder verificar la correcta interacción de los sensores (temperatura, humedad, pH) y actuador (servo motor para válvula de riego). | EP4 |

## 3.3. Impact Mapping
[(![image](https://github.com/user-attachments/assets/13ac363f-26bf-4bb7-8f05-6116676e091c)]

## 3.4. Product Backlog


| Orden | User Story ID | Título                                 | Descripción                                                                                                                                                        | Story Points |
|-------|---------------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1     | EP1/US1       | Crear Encabezado Principal             | Como visitante, quiero ver un encabezado atractivo con el título y subtítulo de Green Tools para captar mi interés.                                                 | 2            |
| 2     | EP1/US2       | Mostrar Beneficios Clave               | Como visitante, quiero leer los beneficios clave de AgroVision para entender por qué elegirlo.                                                                     | 3            |
| 3     | EP1/US3       | Destacar Características Clave         | Como visitante, quiero conocer las características principales de Green Tools para evaluar sus capacidades.                                                         | 3            |
| 4     | EP1/US4       | Mostrar Planes y Precios               | Como visitante, quiero ver los planes y precios disponibles para elegir el que mejor se adapte a mis necesidades.                                                  | 3            |
| 5     | EP1/US5       | Mostrar Testimonios y Casos de Éxito   | Como visitante, quiero leer testimonios y casos de éxito para ver cómo otros han mejorado con Green Tools.                                                          | 2            |
| 6     | EP1/US6       | Implementar Footer                     | Como visitante, quiero encontrar información de contacto y enlaces legales al final de la página para obtener más detalles y soporte.                              | 2            |
| 7     | EP2/US1       | Monitoreo en Tiempo Real               | Como usuario, quiero ver datos en tiempo real de mis cultivos para monitorear sus condiciones actuales.                                                            | 5            |
| 8     | EP2/US2       | Control Remoto de Dispositivos         | Como usuario, quiero controlar dispositivos conectados desde la aplicación para gestionar mi cultivo.                                                              | 5            |
| 9     | EP2/US3       | Visualización de Datos Históricos      | Como usuario, quiero ver datos históricos de mis cultivos para analizar tendencias y patrones.                                                                     | 4            |
| 10    | EP2/US4       | Gestión de Perfiles de Cultivo         | Como usuario, quiero crear y gestionar perfiles de cultivo personalizados para ajustar parámetros específicos.                                                    | 5            |
| 11    | EP2/US5       | Configuración de Alertas y Notificaciones| Como usuario, quiero recibir notificaciones sobre condiciones críticas para tomar acciones rápidamente.                                                             | 4            |
| 12    | EP2/US6       | Configuración de Horarios de Dispositivos| Como usuario, quiero programar horarios para los dispositivos conectados para automatizar tareas.                                                                  | 3            |
| 13    | EP2/US7       | Iniciar Sesión                         | Como usuario, quiero iniciar sesión en la aplicación para acceder a mis datos personales y configuraciones.                                                       | 2            |
| 14    | EP3/US1       | Dashboard Centralizado                 | Como usuario, quiero ver una vista integral de todos mis cultivos y datos en tiempo real para un análisis centralizado.                                            | 8            |
| 15    | EP3/US2       | Administración de Cultivos             | Como usuario, quiero gestionar y configurar mis cultivos desde la aplicación web para ajustar sus parámetros.                                                     | 6            |
| 16    | EP3/US3       | Generación de Reportes                 | Como usuario, quiero generar y exportar reportes detallados sobre mis cultivos para análisis y seguimiento.                                                       | 4            |
| 17    | EP3/US4       | Gestión de Dispositivos IoT            | Como usuario, quiero gestionar dispositivos IoT conectados desde la web para ver su estado y ajustar configuraciones.                                             | 7            |
| 18    | EP3/US5       | Gestión de Usuarios y Permisos         | Como administrador, quiero gestionar cuentas de usuarios y permisos para controlar el acceso a las funcionalidades.                                                | 5            |
| 19    | EP4/US1       | Gestión de Cultivos y Sensores         | Como desarrollador, quiero gestionar los cultivos y sensores en el backend para almacenar y actualizar datos.                                                      | 8            |
| 20    | EP4/US2       | Control de Dispositivos y Automatización| Como desarrollador, quiero implementar la lógica para controlar dispositivos y aplicar reglas de automatización.                                                  | 8            |
| 21    | EP4/US3       | Gestión de Usuarios y Accesos          | Como desarrollador, quiero gestionar la autenticación y permisos de usuarios para proteger el acceso a la plataforma.                                             | 6            |
| 22    | EP4/US4       | Integración con Dispositivos IoT       | Como desarrollador, quiero integrar con dispositivos IoT para enviar comandos y recibir datos.                                                                    | 7            |
| 23    | EP4/US5       | Generación de Reportes                 | Como desarrollador, quiero generar reportes basados en datos históricos y actuales de cultivos.                                                                   | 6            |
| 24    | EP4/US6       | Gestión de Carga de IoT                | Como desarrollador, quiero implementar un backend adicional para distribuir la carga o gestionar de manera más eficiente los datos que se recopilan de dispositivos IoT. | 8            |
| 25    | EP4/US7       | Registro de Serial de Sensores IoT     | Como desarrollador, quiero registrar los seriales de los sensores IoT para mantener un control adecuado de los dispositivos conectados.                            | 4            |
| 26    | EP4/US8       | Configuración de Simulación IoT en Wokwi| Como desarrollador, quiero configurar la simulación de dispositivos IoT en Wokwi utilizando un ESP32 para probar la integración y funcionalidad de sensores y actuadores. | 5            |



# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery
##### Step 1: Unstructured Exploration
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407433528737846/Green_Tols.jpg?ex=66dd3dd8&is=66dbec58&hm=490e815a0472aa1209b5dda819f8c01eab4e19c918f98ef7728708462c33eee6&=&format=webp&width=802&height=1610)
##### Step 2: Timelines
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407433260564520/Green_Tols_1.jpg?ex=66dd3dd8&is=66dbec58&hm=e682ed582b49aa106216ffa37e5c55b2066af6fc939c5e0a8536ce954a4c9669&=&format=webp&width=2014&height=1610)
##### Step 3: Paint Points
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407433017036830/Green_Tols_2.jpg?ex=66dd3dd8&is=66dbec58&hm=9e17ce2fdef2a1c54e3fdb47472a58dff905c2c8eee93b6023ff4fe33701752e&=&format=webp&width=2070&height=1610)
##### Step 4: Pivotal Points
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407432702459946/Green_Tols_3.jpg?ex=66dd3dd8&is=66dbec58&hm=034f7e93a2b7c58021265a1fb469b19c967ccf435835a647e107ad32f09bb765&=&format=webp&width=1768&height=1610)
##### Step 5: Commands
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280409740698062858/Green_Tols_18.jpg?ex=66dd3fff&is=66dbee7f&hm=6383f0a6519feacadef7d6916e99a8ecdf7d2713d6b585997e383ba299e9b466&=&format=webp&width=2154&height=1344)
##### Step 6: Policies
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407435223236618/Green_Tols_4.jpg?ex=66dd3dd9&is=66dbec59&hm=e5814907475a52c907b222a306d55025543d1e5bbb5716aaf697ffd221596ad8&=&format=webp&width=2154&height=1384)
##### Step 7: Read Models
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407434778902639/Green_Tols_5.jpg?ex=66dd3dd9&is=66dbec59&hm=544be4151f5db810364cf5d3fb87266b341fcb69c811de6f1377a69b026982cc&=&format=webp&width=2154&height=1318)
##### Step 8: External Systems
No hay sistemas externos
##### Step 9: Aggregates
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280411167126196297/Green_Tols_19.jpg?ex=66dd4153&is=66dbefd3&hm=b91ce8c89c4af641dc4bab6103b4ce6f565230500bff4aa532ed3aac8ca334e5&=&format=webp&width=2154&height=1344)
##### Step 10: Bounded Contexts
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407434518597652/Green_Tols_6.jpg?ex=66dd3dd9&is=66dbec59&hm=b4d4dcb685406e0aa7cbb34ee418d9e9a0241dc18d67d97f418be017c3f3763e&=&format=webp&width=2154&height=1296)

#### 4.1.1.2. Domain Message Flows Modeling
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407493847154719/Green_Tols_12.jpg?ex=66dd3de7&is=66dbec67&hm=f01bcc0041e91047298e627305be686963f17568f8c4cc1fa0612ac5d537b6de&=&format=webp&width=2154&height=1202)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407494287687774/Green_Tols_11.jpg?ex=66dd3de7&is=66dbec67&hm=4bb2b1b81f3c4fbc3a86902f425a29149be32961557043185bedb3f1bb579449&=&format=webp&width=2154&height=1198)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407494690345094/Green_Tols_10.jpg?ex=66dd3de7&is=66dbec67&hm=a96ae7b4242b9c9bab169c20a33fb9e8352438fa7a53b0591b128283970b7824&=&format=webp&width=2154&height=1200)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407495176622122/Green_Tols_9.jpg?ex=66dd3de7&is=66dbec67&hm=4ba1c916a017431e83a37edbe54ea331ee22524a9dcc2c7dfa4d4fb0e4c0033b&=&format=webp&width=2154&height=1186)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407495499710547/Green_Tols_8.jpg?ex=66dd3de7&is=66dbec67&hm=8ba42519a8997dbff171e44fe5b82712aaf39df130d78cbb8d6cb096ccacdd5f&=&format=webp&width=2154&height=1204)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407495843516416/Green_Tols_7.jpg?ex=66dd3de7&is=66dbec67&hm=41fd712de0f93dbfe112e45b1619a09c868e1d9690fb22ba7905081854ff7860&=&format=webp&width=2154&height=1222)

#### 4.1.1.3. Bounded Context Canvases
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407496107888672/Green_Tols_16.jpg?ex=66dd3de7&is=66dbec67&hm=4087c1b2aa1c53d978130fbe3ce47a1f60391dcab6c1c2fd64e17eb4f182ac50&=&format=webp&width=2154&height=1264)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407493406625823/Green_Tols_13.jpg?ex=66dd3de7&is=66dbec67&hm=4999dd9b5b210f8e422f9ed5a87f7c114dfeb874c83d7f2a69ef34c564864765&=&format=webp&width=2154&height=1242)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407496489439332/Green_Tols_15.jpg?ex=66dd3de7&is=66dbec67&hm=01ec1e56d1201ca09311d6ab71e95147e65806b2e9b4de548e3f86aa92becede&=&format=webp&width=2154&height=1246)
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407496875315232/Green_Tols_14.jpg?ex=66dd3de8&is=66dbec68&hm=fd4ebdd935a15f39e047358ddbcafa0302c23a138a47a47b6ed181e6bdc2febd&=&format=webp&width=2154&height=1242)

### 4.1.2. Context Mapping

![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407512658612314/Green_Tols_17.jpg?ex=66dd3deb&is=66dbec6b&hm=c7f7894771cd4d7dc3c54aaeb3478a5de65d301a0a6570f002e94a1d5b7e80cd&=&format=webp&width=798&height=700)

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280938931776651388/Green_Tools-Landscape.png?ex=66dd3298&is=66dbe118&hm=15994e1d32299191c71bc4f5f105d539ee0f49456573b9fcf51940e5158aa039&=&format=webp&quality=lossless&width=1428&height=1208)

#### 4.1.3.2. Software Architecture Context Level Diagrams
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280938932044959745/Green_Tools-Context.png?ex=66dd3298&is=66dbe118&hm=930576b10800f2235126febb777546b662773c1153ab35c36b0aa324b1003630&=&format=webp&quality=lossless&width=1088&height=650)

#### 4.1.3.3. Software Architecture Container Level Diagrams.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407434019733525/Green_Tools-Containers.png?ex=66dd3dd9&is=66dbec59&hm=54d3c1574c54dc1ff1fb9ad19c63cff346a0164a7167e84f7000b172f8710d2e&=&format=webp&quality=lossless&width=1696&height=1332)

#### 4.1.3.4. Software Architecture Deployment Diagrams
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407433763622994/Green_Tools-Deployment.png?ex=66dd3dd9&is=66dbec59&hm=fcb3ffaf9e4d6e1801141fa497e8c264ecd35940cd1259941cac174c215eb7af&=&format=webp&quality=lossless&width=1856&height=1326)

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: \<Account>

#### 4.2.1.1. Domain Layer

Entities:
Value Objects: 
Aggregates:
Repositories:
Services:

#### 4.2.1.2. Interface Layer

API Endpoints:
DTOs:
View Models: 
Controllers:

#### 4.2.1.3. Application Layer

Services:
Commands/Queries:
Command Handlers: 
Event Handlers:

#### 4.2.1.4. Infrastructure Layer

Persistence Mechanisms:
External Service Integrations:
Factories:
API Clients: 

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

![Account Bounded Context-DiagramaC](https://github.com/user-attachments/assets/839f44b5-c3e7-4a28-8b0f-d4c66adb7c26)

##### 4.2.1.6.2. Bounded Context Database Design Diagram

![Account Bounded Context](https://github.com/user-attachments/assets/f571b0d8-b4b5-4940-9752-8dd968ba1437)

### 4.2.2. Bounded Context: \<IoT System>

#### 4.2.2.1. Domain Layer

Entities:
Value Objects: 
Aggregates:
Repositories:
Services:

#### 4.2.2.2. Interface Layer

API Endpoints:
DTOs:
View Models: 
Controllers:

#### 4.2.2.3. Application Layer

Services:
Commands/Queries:
Command Handlers: 
Event Handlers:

#### 4.2.2.4. Infrastructure Layer

Persistence Mechanisms:
External Service Integrations:
Factories:
API Clients: 

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

![IoT System Bounded Context-DiagramC](https://github.com/user-attachments/assets/84368510-5475-47ea-8345-df7ecfee0220)

##### 4.2.2.6.2. Bounded Context Database Design Diagram

![IoT System Bounded Context](https://github.com/user-attachments/assets/079afb50-8f12-431b-bdfa-fb08f394b741)

### 4.2.3. Bounded Context: \<Crop Inventory>

#### 4.2.3.1. Domain Layer

Entities:
Value Objects: 
Aggregates:
Repositories:
Services:

#### 4.2.3.2. Interface Layer

API Endpoints:
DTOs:
View Models: 
Controllers:

#### 4.2.3.3. Application Layer

Services:
Commands/Queries:
Command Handlers: 
Event Handlers:

#### 4.2.3.4. Infrastructure Layer

Persistence Mechanisms:
External Service Integrations:
Factories:
API Clients: 

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

![Crop Inventory Bounded Context-DiagramC](https://github.com/user-attachments/assets/a877c231-1ced-4af2-b58f-2c2c0e222659)

##### 4.2.3.6.2. Bounded Context Database Design Diagram

![Crop Status Bounded Context](https://github.com/user-attachments/assets/022acbc4-ca0b-4639-9603-3ae33bd8cdc9)

### 4.2.4. Bounded Context: \<Crop Status>

#### 4.2.4.1. Domain Layer

Entities:
Value Objects: 
Aggregates:
Repositories:
Services:

#### 4.2.4.2. Interface Layer

API Endpoints:
DTOs:
View Models: 
Controllers:

#### 4.2.4.3. Application Layer

Services:
Commands/Queries:
Command Handlers: 
Event Handlers:

#### 4.2.4.4. Infrastructure Layer

Persistence Mechanisms:
External Service Integrations:
Factories:
API Clients: 

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

![Crop Status Bounded Context-DiagramC](https://github.com/user-attachments/assets/6c828cf5-8263-42fe-943b-69287cad3d06)

##### 4.2.4.6.2. Bounded Context Database Design Diagram

![Crop Status Bounded Context](https://github.com/user-attachments/assets/c5cfacfb-f312-4e08-b5c5-df79bfce18bf)

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

### 5.4.3. Applications Mock-ups

### 5.4.4. Applications User Flow Diagrams

## 5.5. Applications Prototyping

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Source Code Style Guide & Conventions

### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning n

#### 6.2.1.2. Sprint Backlog n

#### 6.2.1.3. Development Evidence for Sprint Review

#### 6.2.1.4. Testing Suite Evidence for Sprint Review

#### 6.2.1.5. Execution Evidence for Sprint Review

#### 6.2.1.6. Services Documentation Evidence for Sprint Review

#### 6.2.1.7. Software Deployment Evidence for Sprint Review

#### 6.2.1.8. Team Collaboration Insights during Sprint

### 6.2.2. Sprint 2

#### 6.2.2.1. Sprint Planning n

#### 6.2.2.2. Sprint Backlog n

#### 6.2.2.3. Development Evidence for Sprint Review

#### 6.2.2.4. Testing Suite Evidence for Sprint Review

#### 6.2.2.5. Execution Evidence for Sprint Review

#### 6.2.2.6. Services Documentation Evidence for Sprint Review

#### 6.2.2.7. Software Deployment Evidence for Sprint Review

#### 6.2.2.8. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews

### 6.3.1. Diseño de Entrevistas

### 6.3.2. Registro de Entrevistas

### 6.3.3. Evaluaciones según heurísticas

## 6.4. Video About-the-Product
