<div align="center">
  
![Logotipo Descripción generada automáticamente](https://res.cloudinary.com/daassyisd/image/upload/v1714691535/gmplcgrlsv9sihpusivm.png)

**UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**

**SI572-2402-WV71 Desarrollo de Soluciones IOT**

**TB1**

<br>

**Carrera:** Ingeniería de Software

**Ciclo:** 07

**Sección:** WV71

**Profesor:** Angel Augusto Velasquez Nuñez

**Startup:** Fractalies

**Producto:** GreenTools

<br>

**Integrantes:**

Miguel Angel Ramirez Alfaro (U20202117152)  
Lino Abraham Quenta Leon (U202022353)  
Giovanni Andres Ramos Calderon (U202122512)  
Jean Patrick Yemsi Sanchez Rios (U20181e536)  
Franco Felix Yance Gutierrez (U202013614)

<br>

**Septiembre, 7 de 2024**

</div>

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|---------------------------|
| 1.0 | 2024-09-06 |Miguel Angel Ramirez Alfaro <br><br> Franco Felix Yance Gutierrez <br><br> Giovanni Andres Ramos Calderon <br><br> Lino Abraham Quenta Leon <br><br> Jean Patrick Yemsi Sanchez Rios | Capítulo I: Introducción, Capítulo II: Requirements Elicitation & Analysis, Capítulo III: Requirements Specification y Capítulo IV: Solution Software Design|

# Project Report Collaboration Insights

URL de nuestro repositorio para el Project Report:[https://github.com/FractalisGrupo03IOT/InformeFinal](https://github.com/FractalisGrupo03IOT/InformeFinal)

## Desarrollo de actividades y colaboración

### Entrega 1 (TB1)

- **Franco Yance**: Adicion del "Startup profile, Lean UX Problem Statements, antecedentes y problematica".
- **Miguel Angel**: Estructura inicial del informe y mejora de "User Personas".
- **Lino Quenta**: Adición de "Lean UX Process", "Impact Mapping", y mejoras en las historias de usuario.
- **Giovanni Andres**: Desarrollo de "Software Architecture"
- **Jean Patrick**: Actualización de "Software Architecture" y adición de "Solution UX Design".

## Evidencia de colaboración

![image](https://media.discordapp.net/attachments/1282304254929010689/1282317904641134652/Captura_de_pantalla_2024-09-08_073253.png?ex=66deeb1c&is=66dd999c&hm=b5bfc3f9ef375659fc3b8656eeb9848f000356ab41477e433e2faf5c636af843&=&format=webp&quality=lossless&width=559&height=671)

#Contenido

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
- [Conclusiones](#42173-conclusiones)
- [Bibliografía](#42174-conclusiones)
- [Anexos](#42175-conclusiones)
# Student Outcome
### Conpentencia de Student Outcome
| Criterio | Acciones realizadas | Conclusión |
| -------- | ------------------- | ---------- |
| **Criterio 1: Trabaja en equipo para proporcionar liderazgo en forma conjunta** | - Miguel Ángel tomó la responsabilidad de iniciar el proyecto liderando la estructura inicial del informe. Se aseguró de que todos tuvieran una base sólida para avanzar, dividiendo las tareas de manera eficiente.<br> - Lino Quenta se aseguró de añadir las secciones más críticas como "Lean UX Process", lo que impulsó el progreso del equipo y aseguró que no se perdieran elementos clave del informe.<br> - Giovanni Andrés reorganizó el contenido del informe, mejorando la coherencia y fluidez del documento. Esto ayudó a que la presentación final fuera mucho más clara y entendible.<br> - Jean Patrick coordinó la actualización de la arquitectura del sistema y se aseguró de que los aspectos técnicos estuvieran bien reflejados en el informe, lo que elevó su calidad técnica.<br> - Franco participó activamente en la revisión final del informe, asegurando que todo el documento estuviera alineado con los objetivos iniciales y contribuyendo con ideas para mejorar la presentación visual. | El equipo trabajó de manera cohesionada, con cada miembro asumiendo roles clave de liderazgo en momentos adecuados. Esto permitió que el informe se desarrollara de manera sólida y estructurada, mejorando la calidad del resultado final. |
| **Criterio 2: Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | - Miguel Ángel se encargó de la planificación inicial del proyecto, asignando tareas y asegurándose de que el equipo siguiera un cronograma para cumplir con los objetivos propuestos.<br> - Lino Quenta promovió un ambiente de trabajo colaborativo, integrando las ideas de todos los miembros y asegurando que cada aportación fuera tomada en cuenta para el éxito del proyecto.<br> - Giovanni Andrés se encargó de revisar y reestructurar las secciones del informe, asegurando que todo el contenido estuviera alineado y en orden para facilitar el progreso del equipo.<br> - Jean Patrick cumplió con los objetivos técnicos del proyecto mejorando la arquitectura del sistema y asegurando que todos los elementos de diseño UX estuvieran bien implementados.<br> - Franco gestionó la comunicación entre los miembros del equipo, asegurándose de que todos estuvieran al tanto de los avances y contribuyendo a que el equipo mantuviera el enfoque. | El equipo logró crear un entorno inclusivo y colaborativo, donde cada miembro aportó significativamente. La planificación fue clara y efectiva, lo que permitió cumplir los objetivos en tiempo y forma. |


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Fractalis es una startup dedicada a transformar la agricultura mediante la innovación tecnológica. Nos especializamos en desarrollar soluciones que integran el Internet de las Cosas (IoT) y la automatización para empoderar a agricultores de todo el mundo. En Fractalis, creemos en la convergencia de tecnología y sostenibilidad para crear un futuro agrícola más eficiente y responsable. Nuestro objetivo es revolucionar el sector, brindando herramientas accesibles y escalables que mejoran la productividad, optimizan el uso de recursos y promueven prácticas agrícolas sostenibles. Fractalis es más que una startup; es un movimiento hacia la modernización de la agricultura global.

<div align=center>
    <img src="https://media.discordapp.net/attachments/1282304254929010689/1282304308087492701/logo.jpg?ex=66dede73&is=66dd8cf3&hm=3dc374ec3598919b16e4cc663b63a7cfb50b4c93f14e6b4a98c606b84363045c&=&format=webp" alt="Franco Felix Yance Gutierrez" style="margin-bottom: 5px;" width="300"/>

</div>

- **Visión:** Nuestra visión en Fractalis es liderar la transformación global de la agricultura a través de la tecnología, empoderando a agricultores de todo el mundo con herramientas inteligentes que hagan la agricultura más eficiente, sostenible y resiliente. Aspiramos a ser un referente en la innovación agrícola, promoviendo un futuro donde la tecnología y la naturaleza trabajen en armonía para asegurar la seguridad alimentaria y el bienestar del planeta.

- **Misión:** En Fractalis, nuestra misión es desarrollar y proporcionar soluciones tecnológicas avanzadas que integren IoT y automatización, permitiendo a los agricultores optimizar la gestión de sus cultivos. Nos dedicamos a mejorar la eficiencia operativa, reducir el desperdicio de recursos y fomentar prácticas sostenibles, ayudando a agricultores de todos los tamaños a enfrentar los desafíos del futuro agrícola con éxito y responsabilidad.

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="4">
            <img src="https://media.discordapp.net/attachments/1282304254929010689/1282304307798081546/franco.jpg?ex=66dede73&is=66dd8cf3&hm=204a64c30aa310b6206a98e322eb6aec5934963cdeaf608197b2ea8bfdf78130&=&format=webp" alt="Franco Felix Yance Gutierrez" style="margin-bottom: 5px;" width="800"/>
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
        <b>Código de Estudiante:</b>
        <br>
        202022353
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
        <td rowspan="4">
            <img src="https://media.discordapp.net/attachments/1282304254929010689/1282304307244306532/94036246_229317588318715_8422413077701459968_n.jpg?ex=66dede72&is=66dd8cf2&hm=c5c2ebe2f37fa4dd3254e4ea0161ef734e05c40d23187d153e5232f2b4fd1595&=&format=webp" alt="Jean Patrick Yemsi Sanchez Rios" style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Sanchez Rios, Jean Patrick Yemsi
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
        <b>Código de Estudiante:</b>
        <br>
        202023456
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
        <td rowspan="4">
            <img src="https://media.discordapp.net/attachments/1280405882517196875/1282200057986420777/image.png?ex=66de7d5b&is=66dd2bdb&hm=9a9bd990d00a6e9ae32c3d1b9479d5358e36c91d9a4eaf766329e631f5ed4e57&=&format=webp&quality=lossless&width=481&height=603" alt="Giovanni Ramos"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Giovanni Andrés Ramos Calderón
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
        <b>Código de Estudiante:</b>
        <br>
        202021234
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
        <td rowspan="4">
            <img src="https://media.discordapp.net/attachments/1228537935368945717/1282026507916677234/7afa87f0-059c-4ea8-98bf-2b9f74fd82fb.png?ex=66dddbba&is=66dc8a3a&hm=586155cecd320bdb58131d442b8d3ea2d3bd31ca62545daad526ae1cf54b7a09&=&format=webp&quality=lossless&width=313&height=417" alt="Quenta Leon"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
           Quenta Leon, Lino Abraham
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
        <b>Código de Estudiante:</b>
        <br>
        202024789
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Me considero a mí mismo como una persona responsable, y apasionada por la tecnología. Poseo conocimientos en programación, en lenguajes como C++, C#, Java y Python. Me gusta aprender cosas nuevas y mejorar mis conocimientos, cuando no estoy estudiando me gusta leer, y escuchar música. Una de mis mejores cualidades es el trabajo en equipo, me considero alguien resiliente y productivo.
        </td>
    </tr>
  <tr align="center">
        <td rowspan="4">
            <img src="https://media.discordapp.net/attachments/624357483116232707/1282204510625992744/foto2.png?ex=66de8181&is=66dd3001&hm=d6e2c90689248f9f9c1933b2345b320bbf915b7dd7a3376b113f1aa07e686641&=&format=webp&quality=lossless" alt="Miguel Angel Ramirez Alfaro"  style="margin-bottom: 5px;" width="800"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
           Miguel Angel Ramirez Alfaro
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
        <b>Código de Estudiante:</b>
        <br>
        202026345
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy estudiante de 8vo ciclo de la carrera profesional de Ingeniería de Software. Me apasiona la tecnología y sus infinitas aplicaciones. Me considero un joven innovador, soñador, responsable y comprometido. Además, me gusta trabajar en equipo, solucionar problemas y mejorar los procesos que nos faciliten el trabajo, pero sobre todo, mejorar la experiencia del usuario (cliente).
        </td>
    </tr>
</table>


## 1.2. Solution Profile

### Antecedentes y Problemática

**Enunciado del Problema:**
La agricultura moderna enfrenta desafíos crecientes relacionados con el uso ineficiente de recursos, la falta de datos en tiempo real sobre las condiciones de los cultivos y la dificultad para automatizar procesos clave como el riego y la ventilación. Los pequeños y medianos agricultores, en particular, carecen de acceso a tecnologías avanzadas que optimicen sus operaciones y reduzcan los costos.

**Puntos Importantes a Resolver:**
1. **Monitoreo en Tiempo Real**: Los agricultores necesitan tener información actualizada sobre las condiciones de sus cultivos (temperatura, humedad, luz, nutrientes) para tomar decisiones informadas.
2. **Automatización de Procesos**: Es fundamental reducir el desperdicio de recursos como agua y energía mediante la automatización de procesos agrícolas.
3. **Acceso a Tecnología**: Hacer accesible la tecnología avanzada sin una inversión inicial considerable para pequeños agricultores.

**Objetivos del Proyecto:**
1. Desarrollar una plataforma que permita el monitoreo y gestión eficiente de cultivos en tiempo real.
2. Integrar dispositivos IoT para automatizar y optimizar los recursos utilizados en la agricultura.
3. Ofrecer una solución asequible a agricultores mediante un modelo de suscripción y alquiler de equipos tecnológicos.

**Restricciones del Proyecto:**
1. La plataforma debe ser fácil de usar tanto en dispositivos móviles como web.
2. El sistema debe ser escalable para adaptarse a diferentes tamaños de cultivo.
3. Los dispositivos y sensores deben tener un costo accesible y mantenimiento sencillo.

### Lean UX Process

**Hipótesis del Producto:**
GreenTools ayudará a los agricultores a optimizar el uso de recursos y a mejorar la eficiencia operativa mediante el monitoreo en tiempo real y la automatización de procesos críticos como el riego.

**Ejecución del Lean UX:**
1. **Entrevistas a Usuarios**: Se realizaron entrevistas con agricultores para identificar las principales dificultades en la gestión de sus cultivos y la falta de herramientas tecnológicas accesibles.
2. **Prototipado y Pruebas**: Se desarrolló un prototipo de la plataforma GreenTools y se probó con un grupo piloto de agricultores. El enfoque inicial fue mejorar la interfaz y asegurar la integración fluida de los dispositivos IoT.
3. **Iteraciones**: Tras las pruebas, se ajustó la funcionalidad de la plataforma, simplificando la visualización de datos y mejorando la precisión de los sensores.

GreenTools sigue validando su efectividad en cultivos específicos a través de pruebas en condiciones reales con agricultores de diferentes tamaños y especialidades.

### 1.2.1. Antecedentes y problemática

- **Who?**  
Nuestros usuarios son dueños de invernaderos y microcultivos que buscan optimizar la gestión y monitoreo de sus cultivos. Estos agricultores, a menudo pequeños y medianos, están interesados en mejorar la eficiencia y sostenibilidad de sus operaciones mediante la implementación de tecnología avanzada.

- **What?**  
El problema que enfrentan nuestros usuarios es la falta de acceso a soluciones tecnológicas accesibles y efectivas que integren sensores IoT con herramientas de gestión agrícola. Esta carencia impide que los agricultores obtengan datos en tiempo real y automatizar procesos críticos, lo que resulta en una gestión ineficiente de los recursos y bajos rendimientos de sus cultivos.

- **When?**  
El problema descrito se presenta de manera continua, cada vez que los agricultores intentan gestionar sus cultivos sin las herramientas tecnológicas adecuadas. Esto conduce a una pérdida constante de recursos, menores rendimientos y mayores dificultades para mantener prácticas agrícolas sostenibles.

- **Where?**  
El problema se encuentra principalmente en las operaciones de pequeños y medianos agricultores, especialmente aquellos que operan invernaderos y microcultivos. Estos productores a menudo no tienen acceso a tecnologías avanzadas que les permitan optimizar sus procesos y competir eficazmente en el mercado.

- **Why?**  
Nuestros usuarios no logran encontrar en el mercado soluciones tecnológicas que integren de manera efectiva los sensores IoT con la automatización de procesos agrícolas. Las opciones disponibles son a menudo costosas, difíciles de implementar o carecen de la funcionalidad necesaria para mejorar significativamente sus operaciones.

- **How?**  
Para nuestros usuarios, resulta muy complicado encontrar una solución que no solo sea tecnológicamente avanzada, sino también accesible y fácil de usar. Esta problemática ha impulsado la creación de GreenTools, una plataforma que conectará sensores y dispositivos IoT en invernaderos y microcultivos, permitiendo a los agricultores monitorear, automatizar y optimizar sus operaciones de manera eficiente desde cualquier lugar.

- **How much?**  
La problemática se origina debido a la falta de soluciones accesibles y efectivas en el mercado para la integración de IoT en la agricultura. Esto lleva a que los agricultores desperdicien recursos y obtengan bajos rendimientos, lo que afecta tanto la viabilidad económica de sus operaciones como su capacidad para practicar una agricultura sostenible. GreenTools abordará este vacío proporcionando una plataforma IoT intuitiva que permitirá a los agricultores mejorar significativamente la eficiencia y productividad de sus cultivos.



### 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

#### 1. Domain

El dominio de GreenTools abarca la gestión agrícola para pequeños y medianos agricultores, específicamente aquellos que operan invernaderos y microcultivos. La solución busca resolver los problemas relacionados con la falta de acceso a herramientas tecnológicas avanzadas, asequibles y fáciles de usar para optimizar sus procesos agrícolas. 

#### 2. Customer Segments

El segmento de clientes incluye:
- **Dueños de invernaderos**: Agricultores que gestionan cultivos bajo condiciones controladas y requieren herramientas para monitorear y automatizar procesos críticos como el riego y la ventilación.
- **Microcultivadores**: Agricultores con pequeños lotes de cultivos diversificados, que necesitan soluciones de bajo costo que les permitan optimizar el uso de recursos y mejorar la productividad.

#### 3. Pain Points

Los principales puntos de dolor que enfrentan los agricultores incluyen:
- **Acceso limitado a la tecnología**: Las soluciones tecnológicas actuales son costosas y complicadas de implementar.
- **Ineficiencia en la gestión de recursos**: Los agricultores no cuentan con herramientas adecuadas para optimizar el uso de agua, luz y otros insumos críticos.
- **Falta de automatización**: Los procesos manuales incrementan el riesgo de error humano y resultan en desperdicio de recursos.
- **Falta de datos en tiempo real**: Sin datos actualizados, es difícil tomar decisiones informadas sobre el estado de los cultivos.

#### 4. Gap

Existe una brecha entre las necesidades tecnológicas de los pequeños y medianos agricultores y las soluciones tecnológicas disponibles en el mercado. Las soluciones actuales son costosas, complejas y no se adaptan bien a las condiciones específicas de estos agricultores. Esto ha impedido que muchos adopten tecnologías de automatización y monitoreo para mejorar la eficiencia de sus operaciones.

#### 5. Visión/Estrategia

La estrategia de GreenTools es cerrar esta brecha tecnológica al proporcionar una plataforma de gestión agrícola accesible, económica y fácil de usar, que integre sensores IoT y sistemas de monitoreo en tiempo real. La visión es democratizar el acceso a la tecnología avanzada en la agricultura, permitiendo a los pequeños y medianos agricultores mejorar su productividad y sostenibilidad. Al implementar GreenTools, los agricultores podrán gestionar mejor sus recursos, automatizar procesos clave y obtener información precisa y en tiempo real para optimizar sus operaciones.

#### 6. Initial Segment

El segmento inicial de usuarios son los pequeños y medianos agricultores, en particular aquellos que gestionan invernaderos y microcultivos. Este grupo ha sido seleccionado debido a su necesidad crítica de soluciones tecnológicas accesibles que puedan mejorar la eficiencia operativa sin requerir grandes inversiones iniciales.

---

### Assumptions

- **Los agricultores pequeños y medianos están dispuestos a adoptar soluciones tecnológicas si son accesibles y fáciles de implementar.**
- **La automatización de procesos como el riego y la ventilación reducirá significativamente el desperdicio de recursos y aumentará los rendimientos.**
- **El acceso a datos en tiempo real ayudará a los agricultores a tomar decisiones más informadas y mejorar la eficiencia general de sus operaciones.**

### Hypothesis Statements

1. Si proporcionamos una plataforma de monitoreo en tiempo real y automatización basada en IoT, los agricultores podrán reducir el desperdicio de recursos en al menos un 20%.
2. Si GreenTools es asequible y fácil de usar, al menos el 50% de los pequeños y medianos agricultores estarán dispuestos a adoptar la solución en el primer año de lanzamiento.
3. Si los agricultores pueden acceder a datos precisos sobre sus cultivos, podrán mejorar la productividad en un 15% en un plazo de seis meses.

### Lean UX Canvas

| **Aspecto**        | **Descripción**                                                                                                                                      |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Usuarios**       | Dueños de invernaderos y microcultivos que buscan optimizar sus operaciones mediante tecnologías accesibles.                                           |
| **Problema**       | Falta de acceso a tecnologías asequibles y efectivas para optimizar la gestión agrícola y el uso de recursos.                                          |
| **Solución**       | Plataforma de monitoreo y automatización basada en IoT, que ofrece herramientas para la gestión eficiente de cultivos en tiempo real.                 |
| **Beneficios**     | Mejora en la eficiencia operativa, reducción del desperdicio de recursos, aumento de la productividad y sostenibilidad en las operaciones agrícolas.   |
| **Suposiciones**   | Los agricultores adoptarán tecnologías si son accesibles, fáciles de usar y demuestran un impacto positivo en la eficiencia y productividad.           |
| **Métricas**       | Reducción del desperdicio de recursos en un 20%, mejora en la productividad en un 15%, tasa de adopción del 50% en el primer año.                     |

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

**Features:**

1. **Monitoreo en tiempo real**: Los usuarios pueden monitorear las condiciones clave del cultivo, como la humedad del suelo, temperatura y otras variables críticas en tiempo real.
2. **Automatización de procesos**: La plataforma permite automatizar tareas como el riego y la ventilación, ajustándose a las condiciones actuales del cultivo.
3. **Alertas personalizadas**: Se envían notificaciones basadas en parámetros predefinidos por el usuario, como cambios críticos en la temperatura o humedad.
4. **Análisis predictivos**: La plataforma ofrece análisis predictivos que anticipan necesidades futuras y problemas potenciales basados en datos históricos.
5. **Compatibilidad con múltiples dispositivos**: La plataforma es accesible desde cualquier dispositivo (smartphone, tablet, ordenador) y funciona en los navegadores modernos.


#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que GreenTools será una herramienta invaluable para los agricultores que buscan mejorar la gestión de sus invernaderos y microcultivos mediante tecnología IoT. Sabremos que tuvimos éxito cuando más del 80% de nuestros usuarios expresen satisfacción con la plataforma y reporten mejoras en la eficiencia operativa.

- Creemos que la automatización de procesos agrícolas permitirá a los usuarios de GreenTools optimizar el uso de recursos y mejorar los rendimientos de sus cultivos. Sabremos que tuvimos éxito cuando los usuarios reporten un aumento significativo en el rendimiento de sus cultivos tras el uso de la plataforma.
  
- Creemos que los agricultores estarán dispuestos a suscribirse a GreenTools y alquilar los equipos IoT necesarios para la optimización de sus operaciones. Sabremos que tuvimos éxito cuando alcancemos una tasa de renovación de suscripciones superior al 70%.

- Creemos que la plataforma será utilizada por agricultores de pequeños y medianos invernaderos y microcultivos, siendo este nuestro segmento objetivo. Sabremos que tuvimos éxito cuando la mayoría de nuestros usuarios pertenezca a este segmento y encuentren valor en las funcionalidades de la plataforma.

- Creemos que una interfaz intuitiva y responsive es crucial para la adopción exitosa de GreenTools. Sabremos que tuvimos éxito cuando más del 80% de los usuarios reporten que la plataforma es fácil de usar y eficiente en encuestas de satisfacción.

#### 1.2.2.4. Lean UX Canvas

<div align=center>
    <img src="https://media.discordapp.net/attachments/1282304254929010689/1282304307512873010/canvas.jpg?ex=66dede72&is=66dd8cf2&hm=64c195014c52cbb5de045b4f24db8451630da23f1cdb786ca2d9b32584157e16&=&format=webp&width=720&height=366" alt="Canvas"/>
</div>

## 1.3. Segmentos objetivo

| Tipo de Usuario | Dueños de Invernaderos | Propietarios de Microcultivos |
| :-------------- | :--------------------- | :---------------------------- |
| **Geográfico**   | País: Perú <br><br> Zona residencial: No es relevante, pueden ser de diferentes zonas del país. | País: Perú <br><br> Zona residencial: No es relevante, pueden ser de diferentes zonas del país. |
| **Psicográfico** | Clase Social: Clase media y clase alta. <br><br> Estilo de vida: Personas con un fuerte interés en la agricultura moderna y la tecnología, que buscan maximizar el rendimiento y la sostenibilidad de sus cultivos mediante la integración de soluciones tecnológicas avanzadas. | Clase Social: Clase media y clase alta. <br><br> Estilo de vida: Individuos interesados en la diversificación de cultivos en espacios pequeños, que desean implementar tecnologías innovadoras para mejorar la eficiencia y sostenibilidad de sus prácticas agrícolas. |
| **Demográfico**  | Edad: Mayores de 30 años. <br><br> Nivel de Ingreso: Medio a alto, con capacidad para invertir en membresías y alquiler de equipos IoT. <br><br> Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte. | Edad: Mayores de 30 años. <br><br> Nivel de Ingreso: Medio a alto, con disposición para gastar en tecnología avanzada que optimice la producción agrícola. <br><br> Nacionalidad: Nacionalidad peruana. En el caso de ser extranjero, deberá identificarse con su pasaporte. <br><br> Estudios: Educación superior, con un interés marcado en temas tecnológicos y agrícolas. |

<br><br>

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores

| **Nombre del Competidor** | **Descripción**                                                                                                                                                                                                 | **Sitio Web**                     |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------|
| Agrosmart                 | Agrosmart es una empresa brasileña que se especializa en ofrecer soluciones de monitoreo remoto para el sector agrícola. A través de sensores avanzados y análisis en tiempo real, apoya a los agricultores en la toma de decisiones más acertadas. | [agrosmart.com.br](https://agrosmart.com.br) |
| AGROS                     | Es una compañía peruana que brinda soluciones completas para el monitoreo y automatización en el sector agrícola. Su objetivo es proporcionar herramientas tecnológicas que faciliten a los agricultores la gestión eficiente de sus cultivos.           | [agros.tech](https://agros.tech)  |
| CropX                     | CropX es una empresa israelí destacada en la agricultura de precisión. Su enfoque se centra en el desarrollo de sensores de suelo y software avanzado para optimizar en tiempo real la irrigación, los nutrientes y la gestión de cultivos.              | [cropx.com](https://cropx.com)    |


### 2.1.1. Análisis competitivo

# Análisis de Competencia

### Competitive Analysis Landscape
¿Por qué llevar a cabo este análisis? 

¿Cómo reconocer a nuestros competidores más relevantes?

Este análisis se llevó a cabo con el propósito de identificar a nuestros posibles competidores y desarrollar estrategias y tácticas que nos permitan diferenciarnos de ellos.

| Categoría              | GreenTools                                                                                                                                                  | Agrosmart                                                                                                                                                 | CropX                                                                                                                                                       | AGROS                                                                                                                                                               |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Overview**           | Plataforma tecnológica que integra IoT y automatización para optimizar la gestión agrícola en tiempo real.                                                | Empresa brasileña que proporciona soluciones de monitoreo remoto y análisis en tiempo real para la agricultura.                                           | Empresa israelí que ofrece soluciones de agricultura de precisión con un enfoque en el análisis predictivo y gestión del suelo.                            | Compañía peruana especializada en automatización y monitoreo agrícola para grandes y medianos agricultores.                                                        |
| **Ventaja competitiva**| Integra IoT y automatización para un control preciso y sostenible de los recursos en tiempo real.                                                          | Sostenibilidad y una red extensa en Brasil y América Latina. Soluciones que ayudan a reducir el desperdicio de recursos.                                  | Soluciones inteligentes para la gestión del suelo y fuerte presencia internacional.                                                                        | Especialización en sistemas de riego automatizado para una gestión eficiente del agua.                                                                            |
| **Mercado objetivo**   | Propietarios de invernaderos y agricultores que buscan modernizar su gestión agrícola.                                                                       | Agricultores en Brasil y América Latina interesados en monitoreo remoto y análisis en tiempo real.                                                       | Agricultores de precisión a gran escala que buscan tecnología avanzada para optimizar el riego y la nutrición.                                             | Grandes y medianos agricultores en Perú que necesitan soluciones de automatización para gestión de recursos.                                                     |
| **Estrategias de marketing** | Publicidad digital en redes sociales y campañas a nivel nacional.                                                                                            | Estrategias de publicidad pagada, campañas en redes sociales y creación de contenido relevante sobre agricultura de precisión y sostenibilidad.           | Publicación de estudios de caso y testimonios de clientes, además de publicidad pagada.                                                                   | Anuncios en medios locales, demostraciones en eventos agrícolas y ferias.                                                                                           |
| **Productos & Servicios** | Plataforma web y móvil que permite gestionar agua, luz, y nutrientes en tiempo real; incluye planes Monocultivo y Multicultivo.                             | Plataforma web y móvil para datos y análisis en tiempo real.                                                                                            | Plataforma SaaS para gestión precisa del riego y la nutrición del suelo, con análisis predictivo.                                                            | Sistemas de automatización de riego y herramientas para el monitoreo de condiciones del cultivo.                                                                  |
| **Precios & Costos**   | Monocultivo ($10), Multicultivo ($15) más alquiler de dispositivos Arduino y sensores especializados.                                                         | Generalmente $300 - $1,000 basado en cantidad de sensores y alcance. Incluye suscripción mensual o anual.                                                | $2,000 - $4,000 por sistema, con costos adicionales para mantenimiento y soporte.                                                                           | $1,000 - $3,000 por sistema, con un costo adicional de 10-20% para mantenimiento y soporte.                                                                       |
| **Canales de distribución (Web y/o Móvil)** | Plataforma accesible desde la web y aplicaciones móviles.                                                                                                  | Suscripciones online accesibles desde cualquier dispositivo con internet.                                                                               | Distribución a través de su plataforma SaaS y red de distribuidores.                                                                                          | Asociaciones con distribuidores locales y ventas directas a través de su sitio web.                                                                               |
| **Fortalezas**         | Integración de tecnologías IoT y automatización que optimizan recursos y mejoran la eficiencia operativa.                                                    | Red extensa en América Latina y enfoque en sostenibilidad con soluciones para reducir desperdicios.                                                       | Soluciones avanzadas de gestión del suelo y fuerte presencia global.                                                                                           | Especialización en riego automatizado, una solución crucial para la gestión de agua.                                                                             |
| **Debilidades**        | Nuevo en el mercado, enfrenta desafíos de financiamiento y reconocimiento de marca.                                                                           | Dependencia de infraestructura tecnológica en regiones con tecnología deficiente.                                                                         | Costo elevado para pequeños agricultores, limitando la adopción en ciertos mercados.                                                                        | Innovación puede no estar al mismo nivel que competidores más avanzados en IoT y análisis predictivo.                                                            |
| **Oportunidades**      | Creciente demanda de prácticas agrícolas sostenibles ofrece potencial de liderazgo en modernización agrícola.                                                | Posibilidad de expansión fuera de América Latina aprovechando la experiencia en agricultura de precisión.                                                 | Expansión de productos para nuevas áreas agrícolas y mayor adopción de monitoreo del suelo.                                                                  | Creciente demanda de tecnologías de automatización agrícola como el riego automatizado.                                                                          |
| **Amenazas**           | Competencia de startups más grandes y establecidas en el sector de tecnología agrícola.                                                                      | Competencia intensa en mercados de rápida expansión de soluciones tecnológicas similares.                                                                 | Exposición a riesgos climáticos, económicos, y regulatorios en mercados volátiles.                                                                         | Regulaciones gubernamentales sobre el uso del agua y sostenibilidad pueden afectar la adopción de sus productos.                                                 |
### 2.1.2. Estrategias y tácticas frente a competidores

# Estrategia de GreenTools

Posicionar a GreenTools como un líder en la agricultura de precisión mediante la innovación tecnológica, con un enfoque en sostenibilidad y eficiencia, superando a la competencia a través de la diferenciación en servicios y productos, el aprovechamiento de oportunidades de mercado y la mitigación de amenazas.

- Estrategia de Enfoque:
Reconocemos que el auge de la tecnología y el creciente uso de computadoras y smartphones han impulsado una alta demanda en los servicios de gestión y asesoramiento agrícola. Por ello, consideramos que contar con una plataforma web sólida sería de gran utilidad para que las personas puedan investigar y aprender más sobre nuestro tema principal directamente desde sus propios dispositivos.

- Estrategia de Diferenciación en Tecnología y Valor:
**Adaptabilidad del Producto:**
Crear un modelo de tecnología adaptable que permita a GreenTools ofrecer una plataforma flexible, adecuada tanto para pequeños agricultores como para grandes explotaciones agrícolas, diferenciándose así de competidores más especializados como AGROS o CropX.

- Estrategia de Expansión en el Mercado:
**Implementación de Programas de Demostración:**
Mostrar el valor de la tecnología de GreenTools en acción mediante jornadas de campo, demostraciones virtuales y tutoriales que permitan a los agricultores experimentar los beneficios de la automatización y la sostenibilidad.


## 2.2. Entrevistas

### Objetivo de la Entrevista:

Comprender las necesidades y expectativas de los dueños de invernaderos en cuanto al uso de tecnología para la gestión agrícola.

### 2.2.1. Diseño de entrevistas

## Entrevista a Dueños de Invernaderos

## Preguntas

1. **¿Cómo describirías tu interés en la tecnología aplicada a la agricultura?**
2. **¿Cuáles son los principales cultivos que manejas en tu invernadero?**
3. **¿Qué retos enfrentas en términos de sostenibilidad y optimización del uso de recursos (agua, energía)?**
4. **¿Qué importancia le das al monitoreo en tiempo real de las condiciones dentro del invernadero?**
5. **¿Qué tipo de herramientas tecnológicas utilizas actualmente?**
6. **¿Cómo han impactado tu operación?**
7. **¿Cuánto estarías dispuesto a invertir en soluciones tecnológicas que puedan mejorar la eficiencia y sostenibilidad de tu invernadero?**
8. **¿Qué características considerarías esenciales en una plataforma de gestión de cultivos como GreenTools?**
9. **¿Te interesarían servicios adicionales, como capacitación en el uso de tecnologías IoT?**
10. **¿Qué factores te motivarían a cambiar o adoptar nuevas tecnologías en tu operación?**

## Entrevista a Propietarios de Microcultivos

## Preguntas

1. **¿Cómo describirías tu experiencia manejando múltiples cultivos en un espacio reducido?**
2. **¿Qué desafíos enfrentan tus cultivos en términos de recursos como agua y nutrientes?**
3. **¿Qué tipo de tecnología, si alguna, estás utilizando actualmente para gestionar tus cultivos? ¿Qué te gustaría mejorar?**
4. **¿Cuán importante es para ti contar con información en tiempo real sobre las condiciones de tus cultivos?**
5. **¿Cómo ves el uso de IoT y automatización para ayudarte en la gestión diaria de múltiples cultivos?**
6. **¿Estarías dispuesto a pagar por una solución que optimice la producción de varios cultivos al mismo tiempo? Si es así, ¿cuál sería un precio justo para ti?**
7. **¿Qué funcionalidades te parecen más útiles en una plataforma como GreenTools?**
8. **¿Qué barreras te frenan a la hora de adoptar nueva tecnología en tus microcultivos?**
9. **¿Qué tipo de soporte (como capacitación o asesoría técnica) te ayudaría a maximizar el uso de estas tecnologías?**


### 2.2.2. Registro de entrevistas

**Segmento 01:**

| **Entrevistado 01**                                         |                                                                                     |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Nombre y apellidos**                                       | Sonia Hcayhualla Anco                                                                    |
| **Imagen**                                                   | ![Texto alternativo](https://media.discordapp.net/attachments/1282304254929010689/1282304308351598715/entrevista01.png?ex=66dede73&is=66dd8cf3&hm=100d3f22c8c308e6363a4f9a06914c0e96cd38f235b708838eefdb1449be0253&=&format=webp&quality=lossless&width=720&height=301)                                                                    |
| **Inicio de la entrevista**                                  | 00:05                                                                                |
| **Fin de la entrevista**                                     | 06:40                                                                                |
| **Duración**                                                 | 06:40                                                                              |
| **Enlace de entrevista**                                     | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EckNEWl06ixHle5L2RIWuHsBTcYcGWSCUKFTc-n6uipqXw?e=sKQKoh) |
| **Resumen de la entrevista**                                 | En la entrevista, la participante, proveniente de la región de Puno, se dedica al cultivo y venta de fresas en un invernadero. A pesar de no haber utilizado tecnología hasta ahora, muestra un claro interés en incorporarla para mejorar sus prácticas agrícolas. Identifica el riego como el mayor gasto y desea optimizar el consumo de agua y energía. También menciona la importancia de monitorear los cultivos en tiempo real y estaría dispuesta a invertir en una aplicación móvil que permita realizar estas funciones, aunque no tiene un presupuesto definido. La entrevistada valora la capacitación para utilizar nuevas tecnologías y espera que una aplicación le permita ampliar su mercado, generar más demanda y aumentar sus ganancias mediante procesos como el riego automático y otros beneficios que facilitarían su labor agrícola. |

<br><br>

| **Entrevistado 02**                                         |                                                                                     |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Nombre y apellidos**                                       | Fabio Orna                                                                          |
|**Imagen**                                                   | ![Texto alternativo](https://media.discordapp.net/attachments/1282304254929010689/1282304308628553852/entrevista02.png?ex=66dede73&is=66dd8cf3&hm=5eecc84d2fa95c8776db68435eb31a6e23e7f56a7159fb83ba03614748a13a97&=&format=webp&quality=lossless&width=720&height=401)                                  |
| **Inicio de la entrevista**                                  | 06:40                                                                               |
| **Fin de la entrevista**                                     | 11:00                                                                               |
| **Duración**                                                 | 04:60                                                                               |
| **Enlace de entrevista**                                     | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EckNEWl06ixHle5L2RIWuHsBTcYcGWSCUKFTc-n6uipqXw?e=sKQKoh)                                                                    |
| **Resumen de la entrevista**                                 | En la entrevista, Fabio Orna, de 30 años, expresa un fuerte interés en la automatización y el control total en su invernadero de tomates y fresas. Enfrenta retos en la optimización del uso de agua y energía, y considera que el monitoreo en tiempo real es crucial para tomar decisiones sobre sus cultivos. Utiliza herramientas como rociadores automáticos y lámparas especiales, y está dispuesto a invertir en aplicaciones tecnológicas para mejorar su operación. Destaca la importancia de recibir capacitación en tecnologías IoT y valora características como la visualización de datos en tiempo real y la gestión de inventarios en plataformas de gestión de cultivos. |

<br><br>

| **Entrevistado 03**                                         |                                                                                     |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Nombre y apellidos**                                       |  Fer López                                               |
| **Imagen**                                                   | ![Texto alternativo](https://media.discordapp.net/attachments/1282304254929010689/1282304308943130714/entrevista03.png?ex=66dede73&is=66dd8cf3&hm=c4875e66d98a756b4c971a6e747ef976699893cf8ea65877113a11f958e48517&=&format=webp&quality=lossless&width=720&height=205)                           |
| **Inicio de la entrevista**                                  | 11:00                                                                               |
| **Fin de la entrevista**                                     | 20:01                                                                               |
| **Duración**                                                 | 09:01                                                                               |
| **Enlace de entrevista**                                     | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EckNEWl06ixHle5L2RIWuHsBTcYcGWSCUKFTc-n6uipqXw?e=sKQKoh)                                                                    |
| **Resumen de la entrevista**                                 | En la entrevista, López, de 29 años y con formación en Ingeniería Ambiental, discute su interés en la tecnología aplicada a la agricultura. Menciona que actualmente cultiva tomates, pimientos y pepinos en su invernadero y enfrenta retos en la optimización del uso de agua y energía. Destaca la importancia del monitoreo en tiempo real para mantener las condiciones adecuadas para sus cultivos. Aunque no utiliza actualmente herramientas tecnológicas, está explorando sistemas de riego automático y reconoce que la falta de conocimientos en tecnología es un obstáculo. Está dispuesto a invertir en soluciones tecnológicas si el costo es justo y valora características como el control de riego, la gestión de nutrientes y la regulación del clima en una plataforma de gestión de cultivos. También considera importante recibir capacitación en el uso de tecnologías IoT y está motivado por la necesidad de adaptarse a los avances tecnológicos para mejorar la eficiencia y sostenibilidad de su operación. |

<br><br>

**Segmento 02**

| **Entrevistado 01**                                         |                                                                                     |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Nombre y apellidos**                                       | Yonny Ramos                                                                         |
| **Imagen**                                                   | ![Texto alternativo](https://media.discordapp.net/attachments/1282304254929010689/1282304309219819530/entrevista04.png?ex=66dede73&is=66dd8cf3&hm=a576d27d28b7269616cdd1901a3105e62996b28a7d33916fa416610af9582ab9&=&format=webp&quality=lossless&width=720&height=449)                            |
| **Inicio de la entrevista**                                  | 20:13                                                                               |
| **Fin de la entrevista**                                     | 32:38                                                                               |
| **Duración**                                                 | 12:25                                                                               |
| **Enlace de entrevista**                                     | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EdL4DDH2Ox1KjvdKcQeUib0Bh_UdI2HK9Cz1Jp5A7eFT_g?e=ZV7Rkc) |
| **Resumen de la entrevista**                                 | Kenny Ramos, estudiante de Ingeniería Agraria, tiene un jardín pequeño donde cultiva rabanitos, ajíes, rocotos y hierbas. Enfrenta desafíos con la salinidad y el pH del suelo en Lima. Actualmente no utiliza tecnología, pero le gustaría tener sensores para medir el pH y la salinidad. Considera importante el monitoreo en tiempo real para cultivos más grandes. Las principales barreras para adoptar nuevas tecnologías son la desinformación y el presupuesto. Recomienda ofrecer capacitación y asesoría técnica para facilitar la adopción tecnológica, teniendo en cuenta las diferencias culturales y contextuales. |

<br><br>

| **Entrevistado 02**                                         |                                                                                     |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Nombre y apellidos**                                       | José Daniel Sarate Castro                                                               |
| **Imagen**                                                   | ![Texto alternativo](https://media.discordapp.net/attachments/1282304254929010689/1282304309505163314/entrevista05.png?ex=66dede73&is=66dd8cf3&hm=52ef83d4257a805a9a7b907f683128e74a6726ccc8385d94aade0b293150c23b&=&format=webp&quality=lossless&width=720&height=440)                            |
| **Inicio de la entrevista**                                  | 32:38                                                                               |
| **Fin de la entrevista**                                     | 36:43                                                                               |
| **Duración**                                                 | 04:05                                                                               |
| **Enlace de entrevista**                                     | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EckNEWl06ixHle5L2RIWuHsBTcYcGWSCUKFTc-n6uipqXw?e=sKQKoh) |
| **Resumen de la entrevista**                                 | José Daniel Sar Castro, jefe técnico de un equipo de karting, busca mejorar el rendimiento de los karts para reducir costos de gasolina y aumentar las ganancias. Desea un sistema de monitoreo que ofrezca datos en tiempo real sobre presión de llantas, temperatura del motor y revoluciones por minuto. Enfrenta dificultades por falta de tecnología adecuada y conocimientos técnicos. Considera útil una plataforma con monitoreo en tiempo real y recomendaciones basadas en inteligencia artificial, y valora una interfaz intuitiva, integración con otros sistemas y soporte técnico. |

<br><br>

| **Entrevistado 03**                                         |                                                                                     |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Nombre y apellidos**                                       | Heurestes Hamani                                                                              |
| **Imagen**                                                   | ![Texto alternativo](https://media.discordapp.net/attachments/1282304254929010689/1282304309777797141/entrevista06.png?ex=66dede73&is=66dd8cf3&hm=f2a58c850d92fd3a2ff9e99f6e4da0ddba8c0149845f09ffa606c03e284bb2c4&=&format=webp&quality=lossless)                                                                       |
| **Inicio de la entrevista**                                  | 36:43                                                                               |
| **Fin de la entrevista**                                     | 41:57                                                                               |
| **Duración**                                                 | 05:14                                                                               |
| **Enlace de entrevista**                                     | [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EckNEWl06ixHle5L2RIWuHsBTcYcGWSCUKFTc-n6uipqXw?e=sKQKoh)                                                                       |
| **Resumen de la entrevista**                                 | Heurestes Hamani, de 35 años y residente en Camaná, Arequipa, se dedica a los microcultivos. Destaca la importancia de la planificación y la atención constante a los recursos como agua y nutrientes. Actualmente no utiliza tecnología para gestionar sus cultivos, pero considera esencial tener información en tiempo real sobre las condiciones de los cultivos. Cree que la automatización y el uso de IoT serían muy útiles, especialmente para la dosificación de agua y la gestión de la humedad. Está dispuesto a pagar entre 500 a 1000 soles por una solución que optimice la producción y valora la automatización y la facilidad de uso de las plataformas tecnológicas. Sugiere que la capacitación en forma de videos o manuales sería beneficiosa para adaptar nuevas tecnologías. |

<br><br>



### 2.2.3. Análisis de entrevistas

**Segmento 1: Dueños de Invernaderos**

- **Optimización del riego y consumo de energía**: Los dueños de invernaderos, como Sonia Hcayhualla y Fabio Orna, están enfocados en maximizar la eficiencia de sus cultivos, destacando el alto gasto de agua y energía como uno de sus principales problemas. Mencionan que el riego es el factor más costoso y están interesados en soluciones que automaticen estos procesos. Su interés por la sostenibilidad y la mejora en el rendimiento los lleva a considerar tecnologías IoT que les permitan controlar el riego y gestionar la energía de manera más eficiente, lo que concuerda con su estilo de vida enfocado en la adopción de herramientas modernas y sostenibles. 

- **Monitoreo en tiempo real como necesidad crítica**: Para los propietarios de invernaderos, como Fabio y López, el monitoreo en tiempo real es una herramienta clave para optimizar la gestión de sus cultivos. Fabio usa sistemas automatizados y está dispuesto a invertir en tecnologías que le brinden acceso a datos constantes sobre la humedad, temperatura y necesidades de los cultivos. Esto resuena con su capacidad económica media-alta y su disposición a implementar tecnologías avanzadas para mejorar la producción. Asimismo, la disposición de López a implementar riego automático refleja la alineación de este segmento con soluciones tecnológicas que mejoren la gestión de los invernaderos.

- **Capacitación tecnológica**: Aunque el interés en la tecnología es alto, los entrevistados, especialmente Sonia y López, mencionan la falta de conocimientos técnicos como una barrera para la adopción de nuevas tecnologías. Sin embargo, su perfil psicográfico revela un gran interés en aprender y adaptarse, con Sonia reconociendo la importancia de recibir capacitación para aprovechar al máximo las tecnologías que mejoren su producción. Este segmento busca plataformas y cursos que les permitan integrar la tecnología en sus operaciones diarias, lo que es consistente con su interés en maximizar la eficiencia agrícola.

- **Inversión escalable**: Los entrevistados expresan una disposición a invertir en soluciones tecnológicas si estas les garantizan una mejora significativa en el rendimiento de sus cultivos. Hamani, por ejemplo, menciona que estaría dispuesto a pagar entre 500 y 1000 soles por una solución tecnológica que optimice la producción de su invernadero. Los dueños de invernaderos del segmento de clase media y alta tienen los recursos para hacer inversiones escalables en tecnología, especialmente si estas soluciones les permiten reducir costos a largo plazo y aumentar la sostenibilidad.

**Segmento 2: Propietarios de Microcultivos**

- **Interés en tecnología accesible y eficiente**: Los propietarios de microcultivos, como Kenny Ramos y Hamani, muestran un interés claro en adoptar soluciones tecnológicas, aunque su enfoque está más en optimizar pequeños espacios. Al igual que los dueños de invernaderos, consideran el riego y el control de nutrientes como aspectos clave para mejorar su producción. Sin embargo, su inversión tiende a ser más limitada, lo que requiere soluciones tecnológicas más accesibles y económicas. Este grupo psicográficamente pertenece a una clase media que busca implementar tecnologías de manera gradual.

- **Monitoreo de variables críticas en pequeños cultivos**: Aunque el tamaño de los cultivos es menor que el de los invernaderos, los microcultivadores también destacan la importancia del monitoreo en tiempo real de variables clave como el pH y la salinidad del suelo. Kenny Ramos menciona que el monitoreo de estos parámetros es fundamental, especialmente en entornos urbanos donde la calidad del suelo puede ser un desafío. Al igual que en los invernaderos, estos agricultores están abiertos a soluciones tecnológicas que les permitan un control preciso de sus cultivos, aunque con una menor capacidad de inversión inicial.

- **Adaptabilidad y educación en tecnología**: Para los propietarios de microcultivos, la falta de conocimientos en tecnología es una barrera significativa. Kenny y Hamani coinciden en que la falta de información adecuada y la capacitación son desafíos importantes para poder adoptar soluciones tecnológicas. Sin embargo, ambos están interesados en aprender, lo que refuerza la necesidad de desarrollar plataformas educativas accesibles y fáciles de entender. Estos usuarios valoran la flexibilidad de los proyectos, ya que están enfocados en implementar tecnologías a pequeña escala que puedan ajustarse a sus necesidades particulares.

- **Inversión cuidadosa y escalonada**: Los propietarios de microcultivos, a pesar de tener un nivel de ingreso medio-alto, buscan tecnologías que les proporcionen valor sin requerir grandes inversiones iniciales. Están dispuestos a invertir en herramientas que optimicen la eficiencia de sus cultivos, pero el costo es una preocupación más relevante en comparación con los dueños de invernaderos. Hamani, por ejemplo, menciona que está dispuesto a invertir siempre y cuando el costo esté alineado con los beneficios directos que la tecnología le ofrecerá en términos de automatización y facilidad de uso.
  
## 2.3. Needfinding

### 2.3.1. User Personas

Los User Personas son esenciales para el éxito de GreenTools para ofrecer soluciones personalizadas que aborden de manera eficaz los desafíos únicos de cada segmento objetivo. Desde la implementación de tecnologías IoT para dueños de invernaderos interesados en maximizar la eficiencia y sostenibilidad de sus cultivos, hasta la diversificación y optimización de recursos para propietarios de microcultivos, los User Personas guían el diseño de nuestra oferta, asegurando que responda con precisión a las demandas tanto de principiantes en la adopción tecnológica como de expertos que buscan innovación avanzada en sus operaciones agrícolas.

![User01](https://media.discordapp.net/attachments/624357483116232707/1279965053931622420/image.png?ex=66d85619&is=66d70499&hm=7dfdf7d098c72c25bf9cf0c4f2071f82121929bdc8a7d63bda6e03718c32f2ec&=&format=webp&quality=lossless&width=334&height=468)

![User02](https://media.discordapp.net/attachments/624357483116232707/1279965078413774971/image.png?ex=66d8561f&is=66d7049f&hm=a45f0a6ce90d0bb2a7470c478dbee81fa9c849e2ae4642bbf8ef56188c98370e&=&format=webp&quality=lossless&width=292&height=468)


### 2.3.2. User Task Matrix

## Tareas

| Tarea                           | Dueño de Invernadero - Frecuencia | Dueño de Invernadero - Importancia | Propietario de Microcultivo - Frecuencia | Propietario de Microcultivo - Importancia |
|---------------------------------|-----------------------------------|-----------------------------------|------------------------------------------|-------------------------------------------|
| Monitorear las condiciones climáticas | Alta                              | Alta                              | Media                                     | Alta                                      |
| Controlar los niveles de riego        | Alta                              | Alta                              | Alta                                      | Alta                                      |
| Gestionar múltiples cultivos          | Alta                              | Alta                              | Alta                                      | Alta                                      |
| Ajustar las condiciones del invernadero | Alta                              | Alta                              | N/A                                       | N/A                                       |
| Supervisar el crecimiento de los cultivos | Alta                              | Alta                              | Alta                                      | Alta                                      |
| Reducir el uso de agua y energía      | Media                             | Alta                              | Alta                                      | Alta                                      |
| Realizar mantenimiento de equipos     | Media                             | Media                             | Media                                     | Media                                     |
| Identificar plagas y enfermedades     | Alta                              | Alta                              | Alta                                      | Alta                                      |
| Analizar datos de rendimiento         | Medio                             | Alta                              | Medio                                     | Medio                                     |
| Gestionar costos y presupuesto        | Alta                              | Media                             | Alta                                      | Media                                     |

### 2.3.3. User Journey Mapping

Segmento Objetivo: Dueños de Invernaderos

![UJM-01](https://media.discordapp.net/attachments/624357483116232707/1279962158813417603/journey-01.png?ex=66d85367&is=66d701e7&hm=70b6bf079e7663566343faa8e89c8991dc8c66b64419ac2fb0decb3a3f21c072&=&format=webp&quality=lossless&width=648&height=468)

Segmento Objetivo: Propietarios de Microcultivos

![UJM-02](https://media.discordapp.net/attachments/624357483116232707/1279965113813827655/image.png?ex=66d85627&is=66d704a7&hm=919342a2261955c5855b9b266669d12b11469a87b81123e56e7d97b486770db6&=&format=webp&quality=lossless&width=718&height=468)

### 2.3.4. Empathy Mapping

Para elaborar los Empathy Maps de los User Personas de GreenTools, el proceso sigue un enfoque colaborativo para comprender a fondo a cada usuario, enfocándonos en sus emociones, necesidades, frustraciones y expectativas.

![EM-01](https://media.discordapp.net/attachments/624357483116232707/1279963429704044645/user01.png?ex=66d85496&is=66d70316&hm=e57eee7148406abe0a52bc95b084a409a224ce98189b1846ba89dbaf50a5db98&=&format=webp&quality=lossless&width=420&height=468)

![EM-02](https://media.discordapp.net/attachments/624357483116232707/1279963447248949329/user02.png?ex=66d8549a&is=66d7031a&hm=19e4f57a19cd33daae335cb11f4a473a61105177a24653f9f8bd88e7004c233d&=&format=webp&quality=lossless&width=410&height=468)

### 2.3.5. As-is Scenario Mapping

![ASM-01](https://media.discordapp.net/attachments/1282304254929010689/1282315339442426000/Imagen2.jpg?ex=66dee8b9&is=66dd9739&hm=1ba29bd8cacdcbf601d739750267e8c145d59d57543c7ca887875c931bdd675e&=&format=webp)

![ASM-02](https://media.discordapp.net/attachments/1282304254929010689/1282316078697156771/Imagen3.jpg?ex=66dee969&is=66dd97e9&hm=c7f815eb24f72baccd97677488b7f652d5d78b7d914bfaeed07f91eea19b9c3d&=&format=webp)

## 2.4. Ubiquitous Language

- **Greenhouse (Invernadero):** Estructura cerrada diseñada para controlar las condiciones climáticas internas, optimizando el crecimiento de plantas.

- **Microfarm (Microcultivo):** Pequeñas parcelas de terreno dedicadas al cultivo de diversas especies agrícolas, generalmente en áreas urbanas o residenciales.

- **IoT (Internet of Things - Internet de las Cosas):** Red de dispositivos conectados que intercambian datos automáticamente, aplicados en la agricultura para el monitoreo y control remoto de cultivos y sistemas de irrigación.

- **Subscription Model (Modelo de Suscripción):** Modelo de negocio en el que los usuarios pagan una tarifa recurrente para acceder a servicios o productos, como el acceso a plataformas de gestión agrícola y el alquiler de equipos IoT.

- **Farm Management Software (Software de Gestión Agrícola):** Plataforma tecnológica que centraliza la información sobre cultivos, sensores y recursos, permitiendo a los agricultores tomar decisiones basadas en datos para mejorar la eficiencia operativa.
# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
### Cultivadores de invernadero

![Imagen de Cultivadores de invernadero](https://media.discordapp.net/attachments/1228537935368945717/1277297738538815602/Diagrama_en_blanco_-_Pagina_1_1.png?ex=66dd2277&is=66dbd0f7&hm=76955413de78a6701e14fe2f56c79f69b49266772ca2a19b51e60667d9ba1f4a&=&format=webp&quality=lossless&width=1025&height=345)

### Micro cultivo

![Imagen de Micro cultivo](https://media.discordapp.net/attachments/1228537935368945717/1277297738903589117/Diagrama_en_blanco_-_Pagina_1.png?ex=66dd2277&is=66dbd0f7&hm=dac1156e5fd3a1d76c553a76d72e6591a17365f1031ec626019c5e52a5326d4e&=&format=webp&quality=lossless&width=1025&height=345)


## 3.2. User Stories

## **Tabla de Epics**

| **Epic ID** | **Título**                            | **Descripción**                                                                                                                                                                                                                         |
|-------------|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP1         | Landing Page                          | Desarrollo de la página de aterrizaje para GreenTools con secciones de encabezado, beneficios, características, planes y precios, testimonios y footer.                                                                            |
| EP2         | Aplicación Móvil                      | Desarrollo de la aplicación móvil en Flutter que incluye monitoreo en tiempo real, control remoto, visualización de datos históricos, gestión de perfiles de cultivo, alertas y notificaciones, y configuración de horarios de dispositivos. |
| EP3         | Aplicación Web                        | Desarrollo de la aplicación web en Angular que incluye dashboard centralizado, administración de cultivos, análisis y reportes, gestión de dispositivos IoT, y gestión de usuarios y permisos.                                         |
| EP4         | Backend, Lógica de Negocio e IoT      | Desarrollo del backend en Spring Boot para la gestión de cultivos de precision toda la logica de negocio como, sensores, dispositivos, usuarios, automatización, integración y generación de reportes|
| EP5         | Embedded App                          |Desarrollo y la configuración de un simulador IoT utilizando Wokwi con ESP32 para la simulación de sensores y actuadores como un servo motor para la automatización.                                               |
| EP6         | Backend Distribuido Fake Api | Extensión del backend para gestionar mejor la carga de datos IoT, implementando un segundo backend para distribuir eficientemente la recolección de datos y optimizarla para mandar datos y mejorar la latencia.                                        |
---
| **Epic / Story ID** | **Título**                                              | **Descripción**                                                                                                                                                                                                                      | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | **Relacionado con (Epic ID)** |
|---------------------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| EP1/US1             | Visualizar el encabezado de la página                   | Como **visitante**, quiero ver un encabezado claro y atractivo en la página de inicio que comunique la propuesta de valor de GreenTools.                                                                                                | 1. **Dado** que un visitante está en la página de inicio, **Cuando** accede a la página, **Entonces** el sistema muestra el encabezado principal con la propuesta de valor de GreenTools.<br>2. **Dado** que el encabezado se visualiza correctamente, **Cuando** el visitante interactúa con la página, **Entonces** la información permanece visible sin interrupciones.                                                                                                                                                           | EP1                           |
| EP1/US2             | Mostrar los beneficios clave de GreenTools              | Como **visitante**, quiero leer los beneficios clave para entender por qué GreenTools es relevante para mi negocio agrícola.                                                                                                        | 1. **Dado** que se visualiza la sección de beneficios, **Cuando** se accede a la sección, **Entonces** el sistema presenta información clara sobre monitoreo en tiempo real y control automatizado.<br>2. **Dado** que los beneficios están desplegados, **Cuando** un visitante navega la sección, **Entonces** los beneficios están organizados de manera comprensible y accesible.                                                                                                                                                                   | EP1                           |
| EP1/US3             | Mostrar características de productos                    | Como **visitante**, quiero ver las características de GreenTools para saber cómo se adaptan a mis necesidades.                                                                                                                 | 1. **Dado** que se accede a la sección de características, **Cuando** se visualiza la sección, **Entonces** el sistema describe claramente las características clave como la integración IoT y control remoto.<br>2. **Dado** que las características están visibles, **Cuando** un visitante interactúa con ellas, **Entonces** permanecen accesibles y se muestran sin errores.                                                                                                                                                                 | EP1                           |
| EP1/US4             | Ver planes y precios                                    | Como **visitante**, quiero ver los planes y precios de GreenTools para decidir cuál es el mejor para mi negocio.                                                                                                                 | 1. **Dado** que se accede a la sección de planes y precios, **Cuando** el visitante accede a la sección, **Entonces** el sistema muestra la información de manera clara y sin distracciones.<br>2. **Dado** que hay varios planes disponibles, **Cuando** el visitante explora la página, **Entonces** el sistema permite la comparación entre los distintos planes disponibles.                                                                                                                                                                           | EP1                           |
| EP1/US5             | Leer testimonios de clientes                            | Como **visitante**, quiero leer testimonios de clientes para conocer cómo GreenTools ha impactado a otros negocios.                                                                                                             | 1. **Dado** que se accede a la sección de testimonios, **Cuando** el visitante accede a la página, **Entonces** el sistema muestra testimonios reales sin interferencias.<br>2. **Dado** que los testimonios son mostrados, **Cuando** un visitante navega en la página, **Entonces** los testimonios están accesibles y ordenados cronológicamente.                                                                                                                                                                                | EP1                           |
| EP1/US6             | Implementar Footer con enlaces importantes              | Como **visitante**, quiero ver el footer con enlaces a contacto, términos y condiciones, para poder encontrar información adicional sobre la empresa.                                                                                | 1. **Dado** que el visitante está en la parte final de la página, **Cuando** se visualiza el footer, **Entonces** el sistema proporciona enlaces a contacto, política de privacidad y redes sociales correctamente accesibles.<br>2. **Dado** que el footer está implementado, **Cuando** un visitante utiliza los enlaces del footer, **Entonces** el sistema redirige correctamente a las secciones correspondientes.                                                                                                                                                       | EP1                           |
| EP2/US1             | Monitorear cultivos en tiempo real                      | Como **usuario**, quiero ver datos en tiempo real sobre la temperatura y humedad de mis cultivos para tomar decisiones inmediatas.                                                                                                 | 1. **Dado** que un usuario accede a la sección de monitoreo, **Cuando** revisa los datos de un cultivo, **Entonces** el sistema muestra datos actualizados de forma continua.<br>2. **Dado** que los datos se presentan en gráficos, **Cuando** los datos cambian, **Entonces** el sistema actualiza los gráficos en tiempo real.                                                                                                                                                                                                                              | EP2                           |
| EP2/US2             | Control remoto de dispositivos IoT                       | Como **usuario**, quiero controlar remotamente dispositivos IoT desde la app móvil para gestionar los niveles de riego en mis cultivos.                                                                                             | 1. **Dado** que un usuario accede a la sección de control de dispositivos, **Cuando** activa un dispositivo, **Entonces** el sistema envía el comando correspondiente al dispositivo IoT.<br>2. **Dado** que los dispositivos están conectados, **Cuando** un usuario cambia un ajuste, **Entonces** el sistema actualiza la operación del dispositivo IoT de manera inmediata.                                                                                                                                                                   | EP2                           |
| EP2/US3             | Visualizar datos históricos                              | Como **usuario**, quiero revisar el historial de datos para evaluar el comportamiento de mis cultivos durante un periodo específico.                                                                                               | 1. **Dado** que un usuario accede a los datos históricos, **Cuando** selecciona un rango de fechas, **Entonces** el sistema muestra los datos correspondientes al período seleccionado.<br>2. **Dado** que los datos se visualizan, **Cuando** un usuario cambia entre diferentes periodos, **Entonces** el sistema actualiza los gráficos sin demora.                                                                                                                                                                                                       | EP2                           |
| EP2/US4             | Configuración de perfiles de cultivo                     | Como **usuario**, quiero personalizar perfiles de cultivo para definir los parámetros específicos de mis plantas.                                                                                                                 | 1. **Dado** que un usuario accede a la sección de perfiles, **Cuando** crea un perfil, **Entonces** el sistema permite el ajuste de parámetros como temperatura y humedad.<br>2. **Dado** que un usuario guarda el perfil, **Cuando** utiliza el perfil, **Entonces** el sistema aplica correctamente los ajustes a los sensores asociados.                                                                                                                                                                                            | EP2                           |
| EP2/US5             | Configuración de alertas críticas                        | Como **usuario**, quiero recibir alertas cuando las condiciones críticas del cultivo sean detectadas para actuar de inmediato.                                                                                                      | 1. **Dado** que un usuario está configurando alertas, **Cuando** define una condición crítica, **Entonces** el sistema monitorea continuamente y notifica cuando se sobrepasa el límite establecido.<br>2. **Dado** que ocurre una condición crítica, **Cuando** el sistema detecta dicha condición, **Entonces** el sistema envía una alerta en tiempo real al usuario.                                                                                                                                                                           | EP2                           |
| EP2/US6             | Configuración de horarios de dispositivos                | Como **usuario**, quiero programar horarios para que mis dispositivos funcionen automáticamente en momentos específicos.                                                                                                            | 1. **Dado** que un usuario configura los horarios, **Cuando** define una programación para un dispositivo, **Entonces** el sistema activa el dispositivo automáticamente en el tiempo definido.<br>2. **Dado** que los horarios están programados, **Cuando** llega el tiempo programado, **Entonces** el sistema opera los dispositivos sin intervención manual.                                                                                                                           | EP2                           |
| EP2/US8             | Configuración avanzada de notificaciones en la app móvil  | Como **usuario**, quiero configurar diferentes tipos de notificaciones en la app móvil para recibir alertas personalizadas según mis necesidades.                                                                                    | 1. **Dado** que un usuario configura las notificaciones, **Cuando** define diferentes niveles de alerta, **Entonces** el sistema envía notificaciones basadas en las condiciones preestablecidas.<br>2. **Dado** que se detecta una condición crítica, **Cuando** el sistema evalúa las alertas, **Entonces** la aplicación prioriza las notificaciones según el nivel de importancia definido por el usuario.                                                                                             | EP2                           |
| EP2/US9             | Sincronización de datos entre la aplicación web y la app móvil | Como **usuario**, quiero que los datos entre la app móvil y la aplicación web estén sincronizados para poder acceder a la información en ambos dispositivos sin inconsistencias.                                                         | 1. **Dado** que un usuario realiza cambios en la app móvil, **Cuando** accede a la aplicación web, **Entonces** el sistema actualiza automáticamente los datos en ambos dispositivos.<br>2. **Dado** que se visualizan los datos, **Cuando** un usuario realiza un cambio en la aplicación web, **Entonces** el sistema refleja automáticamente el cambio en la app móvil sin requerir intervención manual.                                                                                      | EP2                           |
| EP2/US10            | Personalización de la interfaz de usuario en la app móvil | Como **usuario**, quiero personalizar la apariencia de la app móvil para hacerla más cómoda y fácil de usar.                                                                                                                       | 1. **Dado** que un usuario accede a las configuraciones, **Cuando** modifica la apariencia de la interfaz, **Entonces** el sistema refleja los cambios en tiempo real sin afectar el funcionamiento.<br>2. **Dado** que la personalización está habilitada, **Cuando** un usuario realiza un cambio, **Entonces** el sistema guarda la configuración y la mantiene en futuras sesiones.                                                                                                                                  | EP2                           |
| EP3/US1             | Ver dashboard centralizado de cultivos                   | Como **usuario**, quiero ver todos mis cultivos y sensores en un dashboard centralizado para obtener una visión general.                                                                                                          | 1. **Dado** que un usuario accede al dashboard, **Cuando** visualiza la pantalla principal, **Entonces** el sistema organiza todos los cultivos y sensores en un solo lugar.<br>2. **Dado** que el dashboard se carga, **Cuando** los datos de los sensores cambian, **Entonces** el sistema refleja los cambios en tiempo real en el dashboard.                                                                                                                                                                             | EP3                           |
| EP3/US2             | Gestión de dispositivos IoT conectados                   | Como **usuario**, quiero administrar los dispositivos IoT para controlar su configuración desde la aplicación web.                                                                                                               | 1. **Dado** que un usuario accede a la sección de dispositivos IoT, **Cuando** accede a la configuración de un dispositivo, **Entonces** el sistema permite ajustar sus parámetros.<br>2. **Dado** que un usuario realiza cambios en la configuración, **Cuando** guarda la configuración, **Entonces** el sistema aplica los nuevos ajustes al dispositivo de manera inmediata.                                                                                                                                  | EP3                           |
| EP3/US3             | Gestión de usuarios y permisos                           | Como **administrador**, quiero gestionar las cuentas de usuario para controlar los permisos de acceso a diferentes funcionalidades.                                                                                                  | 1. **Dado** que un administrador accede a la sección de gestión de usuarios, **Cuando** crea un nuevo usuario, **Entonces** el sistema permite asignarle permisos específicos.<br>2. **Dado** que un administrador modifica un rol, **Cuando** aplica los cambios, **Entonces** el sistema ajusta el acceso del usuario de acuerdo con los permisos asignados.                                                                                                                                    | EP3                           |
| EP3/US4             | Notificaciones en la aplicación web sobre cambios críticos | Como **usuario**, quiero recibir notificaciones en la aplicación web cuando ocurren cambios críticos en las condiciones de mis cultivos para poder tomar acción.                                                                           | 1. **Dado** que se detecta un cambio crítico en los sensores, **Cuando** ocurre una condición fuera de los parámetros normales, **Entonces** el sistema envía una notificación en tiempo real al usuario.<br>2. **Dado** que las notificaciones están activas, **Cuando** un usuario accede a la aplicación web, **Entonces** el sistema muestra un registro de las notificaciones pasadas en la sección correspondiente.                                                                                                      | EP3                           |
| EP3/US5             | Exportación de reportes en formato CSV desde la aplicación web | Como **usuario**, quiero poder exportar los reportes de mis cultivos en formato CSV para realizar análisis más detallados fuera de la plataforma.                                                                                         | 1. **Dado** que un usuario solicita la exportación de un reporte, **Cuando** el usuario realiza la solicitud, **Entonces** el sistema genera un archivo CSV con los datos seleccionados.<br>2. **Dado** que el archivo CSV se ha generado, **Cuando** un usuario lo descarga, **Entonces** el sistema asegura que el archivo esté correctamente formateado y contenga los datos solicitados.                                                                                                                   | EP3                           |
| EP3/US6             | Administración de usuarios y roles en la aplicación web | Como **administrador**, quiero gestionar diferentes roles de usuario en la aplicación web para asegurar el acceso correcto a las funciones basadas en el rol de cada uno.                                                                | 1. **Dado** que un administrador accede a la sección de administración, **Cuando** crea o modifica un rol, **Entonces** el sistema permite asignar permisos específicos para cada función.<br>2. **Dado** que los roles están definidos, **Cuando** un usuario intenta acceder a una función restringida, **Entonces** el sistema deniega el acceso si no tiene los permisos correspondientes.                                                                                                           | EP3                           |
| EP3/US7             | Gestión de notificaciones de alertas en la aplicación web | Como **usuario**, quiero recibir notificaciones de alertas críticas en la aplicación web para poder actuar inmediatamente ante cualquier cambio en los cultivos.                                                                        | 1. **Dado** que se detecta una condición crítica, **Cuando** ocurre un cambio crítico en los sensores, **Entonces** el sistema envía una notificación visible en el dashboard principal del usuario.<br>2. **Dado** que las notificaciones están activas, **Cuando** una alerta es recibida, **Entonces** el sistema guarda un historial accesible para futuras referencias.                                                                                                    | EP3                           |
| EP4/US1             | Gestión de cultivos y sensores                          | Como **developer**, quiero desarrollar la gestion los cultivos y sensores en el backend para almacenar y actualizar datos de los dispositivos IoT.                                                                                              | 1. **Dado** que el backend recibe una solicitud de datos de un cultivo, **Cuando** procesa la solicitud, **Entonces** el sistema devuelve la información actualizada de ese cultivo.<br>2. **Dado** que se crea un nuevo cultivo, **Cuando** el backend procesa la solicitud, **Entonces** el sistema registra correctamente el cultivo en la base de datos.                                                                                                                       | EP4                           |
| EP4/US2             | Integración con dispositivos IoT                         | Como **developer**, quiero integrar dispositivos IoT para enviar comandos y recibir datos de los sensores.                                                                                                                         | 1. **Dado** que el backend procesa un comando desde la aplicación, **Cuando** se envía el comando, **Entonces** el sistema transmite el comando al dispositivo IoT correspondiente.<br>2. **Dado** que el backend recibe una respuesta desde el dispositivo IoT, **Cuando** se procesa la respuesta, **Entonces** el sistema almacena los datos en la base de datos.                                                                                                                | EP4                           |
| EP4/US3             | Generación de reportes automáticos                       | Como **developer**, quiero generar reportes automáticos de los datos recopilados de los cultivos para análisis.                                                                                                                   | 1. **Dado** que el backend recibe una solicitud de reporte, **Cuando** procesa la solicitud, **Entonces** el sistema genera un reporte con los datos históricos y actuales.<br>2. **Dado** que se ha generado un reporte, **Cuando** se completa el proceso, **Entonces** el sistema lo pone disponible para descarga.                                                                                                                                                                     | EP4                           |
| EP4/US4             | Control de automatización en el backend                  | Como **developer**, quiero implementar reglas de automatización para controlar dispositivos basados en las condiciones del cultivo.                                                                                                   | 1. **Dado** que las reglas de automatización están configuradas, **Cuando** se cumple una condición específica, **Entonces** el backend ejecuta automáticamente los comandos predefinidos.<br>2. **Dado** que la automatización está activa, **Cuando** un dispositivo realiza una acción por automatización, **Entonces** el backend registra el estado actualizado del dispositivo.                                                                                                       | EP4                           |
| EP4/US5             | Autenticación y permisos de usuarios                     | Como **developer**, quiero gestionar la autenticación y los permisos de acceso para garantizar que solo usuarios autorizados puedan interactuar con la plataforma.                                                                    | 1. **Dado** que un usuario intenta iniciar sesión, **Cuando** proporciona credenciales válidas, **Entonces** el sistema autentica al usuario y le permite el acceso.<br>2. **Dado** que un usuario tiene un rol específico, **Cuando** intenta acceder a una funcionalidad restringida, **Entonces** el sistema deniega el acceso si no tiene los permisos adecuados.                                                                                                                       | EP4                           |
| EP4/US6             | Control de acceso basado en roles en el backend          | Como **developer**, quiero implementar control de acceso basado en roles en el backend para asegurar que los usuarios solo puedan realizar acciones permitidas según sus roles.                                                       | 1. **Dado** que un usuario hace una solicitud al backend que requiere permisos especiales, **Cuando** procesa la solicitud, **Entonces** el sistema verifica los permisos antes de permitir la acción.<br>2. **Dado** que un usuario tiene permisos limitados, **Cuando** intenta realizar una acción fuera de su rol, **Entonces** el sistema rechaza la solicitud con un mensaje de error adecuado.                                                                                                         | EP4                           |
| EP4/US7             | Soporte para múltiples bases de datos en el backend      | Como **developer**, quiero que el backend soporte múltiples bases de datos para manejar diferentes tipos de datos y asegurar la escalabilidad del sistema.                                                                           | 1. **Dado** que el backend está configurado para múltiples bases de datos, **Cuando** realiza una consulta, **Entonces** el sistema identifica correctamente la base de datos de destino.<br>2. **Dado** que los datos están distribuidos en varias bases, **Cuando** el backend accede a múltiples fuentes, **Entonces** el sistema maneja la integración de datos sin errores ni duplicaciones.                                                                                     | EP4                           |
| EP4/US8             | Generación de reportes basados en condiciones críticas   | Como **developer**, quiero que el backend genere reportes automáticamente cuando se detectan condiciones críticas en los cultivos para análisis y monitoreo.                                                                          | 1. **Dado** que se detecta una condición crítica, **Cuando** el sistema la procesa, **Entonces** genera un reporte detallado con los datos relevantes y lo almacena en el backend.<br>2. **Dado** que se generan múltiples reportes, **Cuando** un usuario solicita un informe, **Entonces** el sistema proporciona el reporte más reciente basado en las condiciones críticas detectadas.                                                                                                                                                   | EP4                           |
| EP5/US1             | Interacción con sensores IoT                             | Como **developer**, quiero recibir datos de sensores IoT en tiempo real para asegurarme de que el sistema embebido funcione correctamente.                                                                                            | 1. **Dado** que los sensores están conectados, **Cuando** el dispositivo embebido recibe los datos, **Entonces** el sistema envía automáticamente los datos al sistema central.<br>2. **Dado** que los sensores envían nueva información, **Cuando** no hay conexión con el servidor central, **Entonces** el sistema embebido almacena temporalmente los datos.                                                                                                                                | EP5                           |
| EP5/US2             | Control local de dispositivos IoT                        | Como **usuario**, quiero controlar dispositivos IoT localmente desde la aplicación embebida para asegurarme de que funcionen sin conexión a internet.                                                                                 | 1. **Dado** que los dispositivos están conectados localmente, **Cuando** se envía un comando desde la aplicación embebida, **Entonces** el sistema ejecuta la acción en los dispositivos IoT sin necesidad de conexión a la nube.<br>2. **Dado** que el sistema está operando localmente, **Cuando** se realiza una acción de control, **Entonces** el sistema registra la acción para enviarla al servidor central una vez restaurada la conexión.                                                                            | EP5                           |
| EP5/US3             | Actualización automática de firmware de dispositivos     | Como **developer**, quiero actualizar automáticamente el firmware de los dispositivos IoT sin afectar su funcionamiento.                                                                                                           | 1. **Dado** que se lanza una actualización de firmware, **Cuando** el dispositivo se conecta al servidor, **Entonces** el sistema embebido descarga e instala la actualización automáticamente.<br>2. **Dado** que la actualización está en progreso, **Cuando** se completa la instalación, **Entonces** el dispositivo continúa su operación sin interrupciones.                                                                                                                                   | EP5                           |
| EP5/US4             | Operación desconectada de la aplicación embebida        | Como **usuario**, quiero que la aplicación embebida continúe funcionando incluso sin conexión a internet para que los datos se guarden localmente.                                                                                     | 1. **Dado** que el sistema no tiene acceso a internet, **Cuando** los sensores envían datos, **Entonces** el sistema embebido almacena la información localmente.<br>2. **Dado** que se restaura la conexión a internet, **Cuando** el sistema embebido se sincroniza, **Entonces** envía los datos acumulados al servidor central sin pérdida de información.                                                                                                                                              | EP5                           |
| EP5/US5             | Implementación de failover en dispositivos embebidos   | Como **developer**, quiero implementar un sistema de failover en los dispositivos embebidos para asegurar que sigan funcionando en caso de fallo del servidor principal.                                                             | 1. **Dado** que el servidor principal falla, **Cuando** el dispositivo embebido detecta la falta de comunicación, **Entonces** cambia automáticamente a un servidor de respaldo sin interrupciones.<br>2. **Dado** que el servidor principal vuelve a estar en línea, **Cuando** se restablece la conexión, **Entonces** el sistema embebido restablece la comunicación con el servidor principal sin perder datos.                                                                                                       | EP5                           |
| EP5/US6             | Soporte para múltiples tipos de sensores en dispositivos embebidos | Como **developer**, quiero agregar soporte para diferentes tipos de sensores IoT en la aplicación embebida para permitir la integración de diversos dispositivos.                                                                      | 1. **Dado** que se conecta un nuevo tipo de sensor, **Cuando** el sistema embebido lo detecta, **Entonces** identifica y gestiona los datos correctamente.<br>2. **Dado** que los sensores están operando, **Cuando** se reciben datos de diferentes tipos, **Entonces** el sistema embebido los procesa y almacena de manera consistente y correcta.                                                                                                             | EP5                           |
| EP6/US1             | Balanceo de carga en backend distribuido               | Como **developer**, quiero implementar un balanceo de carga para distribuir el procesamiento de datos de los dispositivos IoT entre múltiples servidores backend.                                                                           | 1. **Dado** que hay múltiples servidores backend disponibles, **Cuando** se reciben solicitudes de datos, **Entonces** el sistema distribuye la carga de manera eficiente entre los servidores.<br>2. **Dado** que un servidor presenta un fallo, **Cuando** otro servidor recibe la carga adicional, **Entonces** el sistema redistribuye el tráfico sin afectar el rendimiento.                                                                                                                         | EP6                           |
| EP6/US2             | Gestión de métricas de rendimiento                     | Como **developer**, quiero acceder a las métricas de rendimiento del backend distribuido para evaluar la eficiencia del sistema en tiempo real.                                                                                        | 1. **Dado** que el backend distribuido está operativo, **Cuando** un administrador accede al dashboard de métricas, **Entonces** el sistema muestra el uso de recursos, tráfico de datos y latencias del sistema.<br>2. **Dado** que las métricas están visibles, **Cuando** un administrador cambia los parámetros de visualización, **Entonces** los gráficos se actualizan en tiempo real.                                                                                                                                                      | EP6                           |
| EP6/US3             | Monitoreo de fallos en el backend distribuido          | Como **developer**, quiero monitorear fallos en el backend distribuido para tomar acciones correctivas cuando sea necesario.                                                                                                       | 1. **Dado** que el sistema está en producción, **Cuando** se detecta un fallo en un servidor, **Entonces** el sistema notifica automáticamente al administrador.<br>2. **Dado** que un servidor falla y la carga se redirige a otro servidor, **Cuando** ocurre esta situación, **Entonces** el sistema mantiene un registro de la falla y las acciones correctivas realizadas.                                                                                                                      | EP6                           |
| EP6/US4             | Configuración de múltiples servidores backend         | Como **developer**, quiero configurar múltiples servidores backend para manejar la creciente cantidad de datos de dispositivos IoT en tiempo real.                                                                                    | 1. **Dado** que se configura un nuevo servidor, **Cuando** el sistema lo detecta, **Entonces** añade automáticamente el servidor al clúster de servidores.<br>2. **Dado** que el servidor comienza a operar, **Cuando** se reciben solicitudes, **Entonces** el sistema procesa las solicitudes sin generar demoras ni errores.                                                                                                                                                       | EP6                           |
| EP6/US5             | Integración de API para el backend distribuido        | Como **developer**, quiero integrar una API REST para que el backend distribuido pueda recibir y procesar solicitudes externas de forma escalable.                                                                                    | 1. **Dado** que el backend recibe una solicitud de API, **Cuando** procesa la solicitud, **Entonces** el sistema devuelve una respuesta con el estado y los datos solicitados.<br>2. **Dado** que el backend está en funcionamiento, **Cuando** un cliente realiza múltiples solicitudes, **Entonces** el sistema las procesa de manera eficiente sin sobrecargar un único servidor.                                                                                                               | EP6                           |
| EP6/US6             | Configuración de redundancia en el backend distribuido | Como **developer**, quiero configurar redundancia en los servidores backend para asegurar que los datos IoT sean siempre accesibles y seguros.                                                                                      | 1. **Dado** que se pierde la conexión con un servidor, **Cuando** el servidor de respaldo toma el control, **Entonces** el sistema mantiene los datos accesibles para los usuarios.<br>2. **Dado** que los servidores se sincronizan, **Cuando** se restauran los datos, **Entonces** el sistema mantiene la consistencia sin pérdida de información.                                                                                                                                                   | EP6                           |
| EP6/US7             | Optimización del tiempo de respuesta del backend      | Como **developer**, quiero optimizar el tiempo de respuesta del backend distribuyendo la carga de manera eficiente entre los servidores.                                                                                           | 1. **Dado** que hay múltiples servidores backend, **Cuando** se reciben solicitudes simultáneas, **Entonces** el sistema mantiene el tiempo de respuesta dentro de los márgenes aceptables definidos.<br>2. **Dado** que un servidor recibe más carga de lo normal, **Cuando** se detecta una sobrecarga, **Entonces** el sistema redistribuye automáticamente las solicitudes a otros servidores.                                                                                                   | EP6                           |
| EP6/US8             | Implementación de colas de mensajes para el backend    | Como **developer**, quiero implementar colas de mensajes para gestionar las solicitudes de los dispositivos IoT y asegurar que ninguna información se pierda en caso de sobrecarga.                                                        | 1. **Dado** que las solicitudes de los dispositivos llegan al backend, **Cuando** la carga es demasiado alta, **Entonces** el sistema encola las solicitudes y las procesa por orden de llegada.<br>2. **Dado** que el sistema se recupera de la sobrecarga, **Cuando** procesa los mensajes en la cola, **Entonces** lo hace sin pérdida de datos.                                                                                                                                                                   | EP6                           |
| EP6/US9             | Configuración de monitoreo de tráfico en el backend   | Como **developer**, quiero monitorear el tráfico de datos en el backend distribuido para asegurar la estabilidad y eficiencia del sistema.                                                                                       | 1. **Dado** que el backend distribuido está activo, **Cuando** un administrador revisa las métricas de tráfico, **Entonces** el sistema muestra la cantidad de solicitudes y la distribución de la carga entre los servidores.<br>2. **Dado** que el tráfico supera un umbral predefinido, **Cuando** se produce un pico de solicitudes, **Entonces** el sistema genera una alerta automática para que el administrador tome acción.                                                                              | EP6                           |

## 3.3. Impact Mapping
El Impact Mapping de GreenTools muestra cómo los cultivadores de invernadero y los microcultivadores de precisión pueden lograr los Business Goals de la plataforma mediante cambios de comportamiento específicos, funcionalidades clave y la integración de tecnologías IoT.

![Descripción de la imagen](https://drive.google.com/uc?export=view&id=1aoa8aKWnhcx5sy6CKkLCSotOURZwXKAu)
---
![Primera imagen](https://drive.google.com/uc?export=view&id=1Ss4vWunEo6qt3-9Lu_4mFqWtAIIJkxKn)
---
![Segunda imagen](https://drive.google.com/uc?export=view&id=1jCcMtueHfu5nX50f6WfUEAEZB5pbdD4B)
---
![Tercera imagen](https://drive.google.com/uc?export=view&id=1-P7aGhfw3ixaPG4aqA8WMvLPqKfhjPlV)

Los Business Goals de GreenTools se centran en incrementar la eficiencia y sostenibilidad en la gestión de cultivos mediante la adopción de tecnologías IoT y soluciones de precisión. El objetivo principal es atraer usuarios al plan Premium y ofrecerles herramientas para optimizar el uso de recursos, a través del monitoreo en tiempo real, la automatización del riego y la toma de decisiones basada en datos, GreenTools busca reducir costos operativos y aumentar la productividad agrícola, facilitando una gestión más eficiente de los cultivos, tanto para cultivadores de invernadero como para microcultivadores de precisión.

## 3.4. Product Backlog

El **Product Backlog** contiene todas las **Historias de Usuario** priorizadas y estimadas según su valor para el negocio. Se ha utilizado **Trello** como herramienta para gestionar el Product Backlog. A continuación, se presenta una tabla que resume las historias de usuario con su orden de prioridad y estimación en **Story Points**.

## **Tabla de Product Backlog**

| **Orden** | **User Story ID** | **Título**                                            | **Descripción**                                                                                                                                                                                                                      | **Story Points** |
|-----------|-------------------|-------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| 1         | EP1/US1           | Visualizar el encabezado de la página                 | Como **visitante**, quiero ver un encabezado claro y atractivo en la página de inicio que comunique la propuesta de valor de GreenTools.                                                                                                | 3                |
| 2         | EP1/US2           | Mostrar los beneficios clave de GreenTools            | Como **visitante**, quiero leer los beneficios clave para entender por qué GreenTools es relevante para mi negocio agrícola.                                                                                                        | 5                |
| 3         | EP1/US3           | Mostrar características de productos                  | Como **visitante**, quiero ver las características de GreenTools para saber cómo se adaptan a mis necesidades.                                                                                                                 | 5                |
| 4         | EP1/US4           | Ver planes y precios                                  | Como **visitante**, quiero ver los planes y precios de GreenTools para decidir cuál es el mejor para mi negocio.                                                                                                                 | 5                |
| 5         | EP1/US5           | Leer testimonios de clientes                          | Como **visitante**, quiero leer testimonios de clientes para conocer cómo GreenTools ha impactado a otros negocios.                                                                                                             | 3                |
| 6         | EP1/US6           | Implementar Footer con enlaces importantes            | Como **visitante**, quiero ver el footer con enlaces a contacto, términos y condiciones, para poder encontrar información adicional sobre la empresa.                                                                                | 2                |
| 7         | EP2/US1           | Monitorear cultivos en tiempo real                    | Como **usuario**, quiero ver datos en tiempo real sobre la temperatura y humedad de mis cultivos para tomar decisiones inmediatas.                                                                                                 | 8                |
| 8         | EP2/US2           | Control remoto de dispositivos IoT                     | Como **usuario**, quiero controlar remotamente dispositivos IoT desde la app móvil para gestionar los niveles de riego en mis cultivos.                                                                                             | 8                |
| 9         | EP2/US3           | Visualizar datos históricos                            | Como **usuario**, quiero revisar el historial de datos para evaluar el comportamiento de mis cultivos durante un periodo específico.                                                                                               | 5                |
| 10        | EP2/US4           | Configuración de perfiles de cultivo                   | Como **usuario**, quiero personalizar perfiles de cultivo para definir los parámetros específicos de mis plantas.                                                                                                                 | 5                |
| 11        | EP2/US5           | Configuración de alertas críticas                      | Como **usuario**, quiero recibir alertas cuando las condiciones críticas del cultivo sean detectadas para actuar de inmediato.                                                                                                      | 8                |
| 12        | EP2/US6           | Configuración de horarios de dispositivos              | Como **usuario**, quiero programar horarios para que mis dispositivos funcionen automáticamente en momentos específicos.                                                                                                            | 5                |
| 13        | EP2/US8           | Configuración avanzada de notificaciones en la app móvil | Como **usuario**, quiero configurar diferentes tipos de notificaciones en la app móvil para recibir alertas personalizadas según mis necesidades.                                                                                    | 5                |
| 14        | EP2/US9           | Sincronización de datos entre la aplicación web y la app móvil | Como **usuario**, quiero que los datos entre la app móvil y la aplicación web estén sincronizados para poder acceder a la información en ambos dispositivos sin inconsistencias.                                                         | 8                |
| 15        | EP2/US10          | Personalización de la interfaz de usuario en la app móvil | Como **usuario**, quiero personalizar la apariencia de la app móvil para hacerla más cómoda y fácil de usar.                                                                                                                       | 3                |
| 16        | EP3/US1           | Ver dashboard centralizado de cultivos                 | Como **usuario**, quiero ver todos mis cultivos y sensores en un dashboard centralizado para obtener una visión general.                                                                                                          | 8                |
| 17        | EP3/US2           | Gestión de dispositivos IoT conectados                 | Como **usuario**, quiero administrar los dispositivos IoT para controlar su configuración desde la aplicación web.                                                                                                               | 5                |
| 18        | EP3/US3           | Gestión de usuarios y permisos                         | Como **administrador**, quiero gestionar las cuentas de usuario para controlar los permisos de acceso a diferentes funcionalidades.                                                                                                  | 8                |
| 19        | EP3/US4           | Notificaciones en la aplicación web sobre cambios críticos | Como **usuario**, quiero recibir notificaciones en la aplicación web cuando ocurren cambios críticos en las condiciones de mis cultivos para poder tomar acción.                                                                           | 8                |
| 20        | EP3/US5           | Exportación de reportes en formato CSV desde la aplicación web | Como **usuario**, quiero poder exportar los reportes de mis cultivos en formato CSV para realizar análisis más detallados fuera de la plataforma.                                                                                         | 5                |
| 21        | EP3/US6           | Administración de usuarios y roles en la aplicación web | Como **administrador**, quiero gestionar diferentes roles de usuario en la aplicación web para asegurar el acceso correcto a las funciones basadas en el rol de cada uno.                                                                | 5                |
| 22        | EP3/US7           | Gestión de notificaciones de alertas en la aplicación web | Como **usuario**, quiero recibir notificaciones de alertas críticas en la aplicación web para poder actuar inmediatamente ante cualquier cambio en los cultivos.                                                                        | 8                |
| 23        | EP4/US1           | Gestión de cultivos y sensores                          | Como **developer**, quiero gestionar los cultivos y sensores en el backend para almacenar y actualizar datos de los dispositivos IoT.                                                                                                | 5                |
| 24        | EP4/US2           | Integración con dispositivos IoT                       | Como **developer**, quiero integrar dispositivos IoT para enviar comandos y recibir datos de los sensores.                                                                                                                         | 8                |
| 25        | EP4/US3           | Generación de reportes automáticos                     | Como **developer**, quiero generar reportes automáticos de los datos recopilados de los cultivos para análisis.                                                                                                                   | 5                |
| 26        | EP4/US4           | Control de automatización en el backend                | Como **developer**, quiero implementar reglas de automatización para controlar dispositivos basados en las condiciones del cultivo.                                                                                                   | 8                |
| 27        | EP4/US5           | Autenticación y permisos de usuarios                   | Como **developer**, quiero gestionar la autenticación y los permisos de acceso para garantizar que solo usuarios autorizados puedan interactuar con la plataforma.                                                                    | 8                |
| 28        | EP4/US6           | Control de acceso basado en roles en el backend        | Como **developer**, quiero implementar control de acceso basado en roles en el backend para asegurar que los usuarios solo puedan realizar acciones permitidas según sus roles.                                                       | 8                |
| 29        | EP4/US7           | Soporte para múltiples bases de datos en el backend    | Como **developer**, quiero que el backend soporte múltiples bases de datos para manejar diferentes tipos de datos y asegurar la escalabilidad del sistema.                                                                           | 5                |
| 30        | EP4/US8           | Generación de reportes basados en condiciones críticas | Como **developer**, quiero que el backend genere reportes automáticamente cuando se detectan condiciones críticas en los cultivos para análisis y monitoreo.                                                                          | 8                |
| 31        | EP5/US1           | Interacción con sensores IoT                           | Como **developer**, quiero recibir datos de sensores IoT en tiempo real para asegurarme de que el sistema embebido funcione correctamente.                                                                                            | 5                |
| 32        | EP5/US2           | Control local de dispositivos IoT                      | Como **usuario**, quiero controlar dispositivos IoT localmente desde la aplicación embebida para asegurarme de que funcionen sin conexión a internet.                                                                                 | 8                |
| 33        | EP5/US3           | Actualización automática de firmware de dispositivos   | Como **developer**, quiero actualizar automáticamente el firmware de los dispositivos IoT sin afectar su funcionamiento.                                                                                                           | 5                |
| 34        | EP5/US4           | Operación desconectada de la aplicación embebida        | Como **usuario**, quiero que la aplicación embebida continúe funcionando incluso sin conexión a internet para que los datos se guarden localmente.                                                                                     | 5                |
| 35        | EP5/US5           | Implementación de failover en dispositivos embebidos   | Como **developer**, quiero implementar un sistema de failover en los dispositivos embebidos para asegurar que sigan funcionando en caso de fallo del servidor principal.                                                             | 8                |
| 36        | EP5/US6           | Soporte para múltiples tipos de sensores en dispositivos embebidos | Como **developer**, quiero agregar soporte para diferentes tipos de sensores IoT en la aplicación embebida para permitir la integración de diversos dispositivos.                                                                      | 5                |
| 37        | EP6/US1           | Balanceo de carga en backend distribuido               | Como **developer**, quiero implementar un balanceo de carga para distribuir el procesamiento de datos de los dispositivos IoT entre múltiples servidores backend.                                                                           | 8                |
| 38        | EP6/US2           | Gestión de métricas de rendimiento                     | Como **developer**, quiero acceder a las métricas de rendimiento del backend distribuido para evaluar la eficiencia del sistema en tiempo real.                                                                                        | 5                |
| 39        | EP6/US3           | Monitoreo de fallos en el backend distribuido          | Como **developer**, quiero monitorear fallos en el backend distribuido para tomar acciones correctivas cuando sea necesario.                                                                                                       | 8                |
| 40        | EP6/US4           | Configuración de múltiples servidores backend         | Como **developer**, quiero configurar múltiples servidores backend para manejar la creciente cantidad de datos de dispositivos IoT en tiempo real.                                                                                    | 5                |
| 41        | EP6/US5           | Integración de API para el backend distribuido        | Como **developer**, quiero integrar una API REST para que el backend distribuido pueda recibir y procesar solicitudes externas de forma escalable.                                                                                    | 8                |
| 42        | EP6/US6           | Configuración de redundancia en el backend distribuido | Como **developer**, quiero configurar redundancia en los servidores backend para asegurar que los datos IoT sean siempre accesibles y seguros.                                                                                      | 8                |
| 43        | EP6/US7           | Optimización del tiempo de respuesta del backend      | Como **developer**, quiero optimizar el tiempo de respuesta del backend distribuyendo la carga de manera eficiente entre los servidores.                                                                                           | 8                |
| 44        | EP6/US8           | Implementación de colas de mensajes para el backend    | Como **developer**, quiero implementar colas de mensajes para gestionar las solicitudes de los dispositivos IoT y asegurar que ninguna información se pierda en caso de sobrecarga.                                                        | 8                |
| 45        | EP6/US9           | Configuración de monitoreo de tráfico en el backend   | Como **developer**, quiero monitorear el tráfico de datos en el backend distribuido para asegurar la estabilidad y eficiencia del sistema.                                                                                       | 5                |

---

### **Herramienta Utilizada para el Product Backlog**

Se ha utilizado **Trello** para gestionar y mantener el Product Backlog. A continuación, se incluye una captura de pantalla de la configuración actual del Product Backlog en Trello y el enlace público para acceder al mismo.

#### **Captura de Pantalla del Product Backlog en Trello**

![Imagen](https://drive.google.com/uc?export=view&id=1KirGckMAWOuiEIgC7Uh8aqo-mFdD2roO)

#### **Enlace Público al Product Backlog en Trello**

[Acceder al Product Backlog en Trello](https://trello.com/b/ECT6oUU8/greentools)

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design
El proceso que hemos seguido abarca el uso de herramientas de EventStorming, Candidate Context Discovery, Domain Message Flows Modeling, Bounded Context Canvases y Context Mapping para definir los contextos delimitados de nuestra solución, los eventos que desencadenan el uso de un contexto, el flujo que ocurre para que se cumpla un escenario y las relaciones entre los contextos delimitados. Así mismo hemos aplicado el resultado de este proceso para el diseño de nuestra arquitectura de software usando C4.
### 4.1.1. EventStorming
Como primer paso de este proceso hemos realizado una lluvia de ideas sobre los eventos que ocurren en nuestro sistema.
#### 4.1.1.1. Candidate Context Discovery
##### Step 1: Unstructured Exploration
Comenzamos con la lluvia de ideas de los eventos relaciones con el dominio empresarial que exploramos. Los eventos se formulan en tiempo pasado.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407433528737846/Green_Tols.jpg?ex=66dd3dd8&is=66dbec58&hm=490e815a0472aa1209b5dda819f8c01eab4e19c918f98ef7728708462c33eee6&=&format=webp&width=802&height=1610)
##### Step 2: Timelines
Organizamos los eventos en el orden que ocurren dentro del dominio empresarial. Se comienza con un flujo que define un escenario empresarial exitoso, a continuación se evalúan otros escenarios alternativos. 
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407433260564520/Green_Tols_1.jpg?ex=66dd3dd8&is=66dbec58&hm=e682ed582b49aa106216ffa37e5c55b2066af6fc939c5e0a8536ce954a4c9669&=&format=webp&width=2014&height=1610)
##### Step 3: Paint Points
Identificamos los puntos en el proceso que requieren atención. Pueden ser cuellos de botella, pasos que requieren autorización o dudas sobre el evento.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407433017036830/Green_Tols_2.jpg?ex=66dd3dd8&is=66dbec58&hm=9e17ce2fdef2a1c54e3fdb47472a58dff905c2c8eee93b6023ff4fe33701752e&=&format=webp&width=2070&height=1610)
##### Step 4: Pivotal Points
Buscamos eventos comerciales importantes que indiquen un cambio en el contexto o fase. A estos se denominan eventos fundamentales y se les marca con una barra vertical que divida los eventos antes y después del fundamental.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407432702459946/Green_Tols_3.jpg?ex=66dd3dd8&is=66dbec58&hm=034f7e93a2b7c58021265a1fb469b19c967ccf435835a647e107ad32f09bb765&=&format=webp&width=1768&height=1610)
##### Step 5: Commands
Un comando describe qué desencadena  un evento o un flujo de eventos. Describen operaciones del sistema y se formula en imperativo.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280409740698062858/Green_Tols_18.jpg?ex=66dd3fff&is=66dbee7f&hm=6383f0a6519feacadef7d6916e99a8ecdf7d2713d6b585997e383ba299e9b466&=&format=webp&width=2154&height=1344)
##### Step 6: Policies
Normalmente los comandos no tienen un actor asociados con ellos. Para esto, se buscan políticas de automatización que ejecuten estos comandos. Estos son escenarios en el que un evento desencadena la ejecución de un comando.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407435223236618/Green_Tols_4.jpg?ex=66dd3dd9&is=66dbec59&hm=e5814907475a52c907b222a306d55025543d1e5bbb5716aaf697ffd221596ad8&=&format=webp&width=2154&height=1384)
##### Step 7: Read Models
Un modelo de lectura es la vista que el actor usa para ejecutar un comando. 
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407434778902639/Green_Tols_5.jpg?ex=66dd3dd9&is=66dbec59&hm=544be4151f5db810364cf5d3fb87266b341fcb69c811de6f1377a69b026982cc&=&format=webp&width=2154&height=1318)
##### Step 8: External Systems
No hay sistemas externos
##### Step 9: Aggregates
Cuando todos los eventos y comandos se relizaron, se organizan conceptos relacionados en un agregado, este recibe comandos y produce eventos.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280411167126196297/Green_Tols_19.jpg?ex=66dd4153&is=66dbefd3&hm=b91ce8c89c4af641dc4bab6103b4ce6f565230500bff4aa532ed3aac8ca334e5&=&format=webp&width=2154&height=1344)
##### Step 10: Bounded Contexts
Finalmente se buscan agregados que esten relacionados entre sí, ya sea por funcionalidades dependientes o porque están acoplados por las políticas. Estos grupos de agregados forman los limites de contextos delimitados.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407434518597652/Green_Tols_6.jpg?ex=66dd3dd9&is=66dbec59&hm=b4d4dcb685406e0aa7cbb34ee418d9e9a0241dc18d67d97f418be017c3f3763e&=&format=webp&width=2154&height=1296)

#### 4.1.1.2. Domain Message Flows Modeling
En esta sección se evidencia el proceso para visualizar la colaboración entre bounded context para resolver los casos que se presentan dentro de nuestro sistema. Hemos usado la técnica de visualización Domain Storytelling.

##### Caso 1: Un cliente cambia su tipo de membresía
El dueño del cultivo genera un evento para cambiar su membresía. Este evento pasa al bounded context "Cuenta" donde se asigna el nuevo tipo de membresía escogido por el dueño del cultivo.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407493847154719/Green_Tols_12.jpg?ex=66dd3de7&is=66dbec67&hm=f01bcc0041e91047298e627305be686963f17568f8c4cc1fa0612ac5d537b6de&=&format=webp&width=2154&height=1202)
##### Caso 2: Un usuario crea una cuenta
El dueño del cultivo genera un evento para registrarse en el sistema. Este evento pasa al bounded context "Cuenta" donde se registra los datos del dueño del cultivo y su tipo de membresía.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407494287687774/Green_Tols_11.jpg?ex=66dd3de7&is=66dbec67&hm=4bb2b1b81f3c4fbc3a86902f425a29149be32961557043185bedb3f1bb579449&=&format=webp&width=2154&height=1198)
##### Caso 3: El usuario aumenta un nuevo cultivo
El dueño del cultivo usa un comando para añadir un cultivo en su inventario. Este pasa al bounded context "Inventario de cultivo" donde se asignan los sensores correspondientes y se actualiza el inventario de usuario.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407494690345094/Green_Tols_10.jpg?ex=66dd3de7&is=66dbec67&hm=a96ae7b4242b9c9bab169c20a33fb9e8352438fa7a53b0591b128283970b7824&=&format=webp&width=2154&height=1200)
##### Caso 4: El usuario solicita el estado actual de su cultivo
El dueño del cultivo genera query, el cual pasa al bounded context "Estado del cultivo", se genera un comando para obtener los datos de su cultivo y se devuelven al usuario.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407495176622122/Green_Tols_9.jpg?ex=66dd3de7&is=66dbec67&hm=4ba1c916a017431e83a37edbe54ea331ee22524a9dcc2c7dfa4d4fb0e4c0033b&=&format=webp&width=2154&height=1186)
##### Caso 5: El cliente solicita el reporte de su cultivo
El dueño del cultivo genera query para obtener un reporte de su cultivo, el cual pasa al bounded context "Estado del cultivo", se genera un comando para generar un reporte y enviarselo al usuario.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407495499710547/Green_Tols_8.jpg?ex=66dd3de7&is=66dbec67&hm=8ba42519a8997dbff171e44fe5b82712aaf39df130d78cbb8d6cb096ccacdd5f&=&format=webp&width=2154&height=1204)
##### Caso 6: Los sensores recolectan información
Los sensores generan eventos periodicamente para recolectar información y enviarlos al bounded context "Solución IoT", el cual luego de procesar y resumir los datos, los envía a "Estado de cultivo", donde se almacena la información de los cultivos para estar disponible para los usuarios.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407495843516416/Green_Tols_7.jpg?ex=66dd3de7&is=66dbec67&hm=41fd712de0f93dbfe112e45b1619a09c868e1d9690fb22ba7905081854ff7860&=&format=webp&width=2154&height=1222)

#### 4.1.1.3. Bounded Context Canvases
##### Bounded context: Inventario del cultivo
Este contexto permite administrar los cultivos de los usuarios a través de un inventario. Brinda soporte, genera compromiso con el usuario y es una característica genérica. El comando "Añadir cultivo" genera un cambio de contexto entrante. Inventario se refiere a la colección de cultivos por usuario. Una política importante a resaltar es que, si el cliente tiene una membresía monocultivo, su inventario solo puede adiministrar un cultivo. Los eventos salientes están relacionados al registro y actualización del inventario.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407496107888672/Green_Tols_16.jpg?ex=66dd3de7&is=66dbec67&hm=4087c1b2aa1c53d978130fbe3ce47a1f60391dcab6c1c2fd64e17eb4f182ac50&=&format=webp&width=2154&height=1264)

##### Bounded context: Cuenta
Este contexto permite manejar la información de los usuarios y los tipos de cultivos que tendrán a través de sus membresías. Los comandos relacionados al registro, inicio de sesión y cambio de membresía generan el cambio de contexto entrante. Un usuario es un cliente con uno o más cultivos y la membresía es el plan de suscripción del usuario. No se puede cambiar de membresía a una ya existente, tiene que ser nueva o de otro tipo. Los eventos salientes están relacionados al registro exitoso y el nuevo tipo de membresía escogida.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407493406625823/Green_Tols_13.jpg?ex=66dd3de7&is=66dbec67&hm=4999dd9b5b210f8e422f9ed5a87f7c114dfeb874c83d7f2a69ef34c564864765&=&format=webp&width=2154&height=1242)

##### Bounded context: Estado del cultivo
Este contexto realiza un análisis del estado de los cultivos a través de la información recolectada por los sensores. Las características de este contexto brindan soporte al usuario, generan compromiso y es un producto ya usado en el mercado, pero personalizado para nuestro sistema. Los comandos para generar reportes y ver el estado actual del cultivo son entrantes a este contexto. El reporte es el análisis de todos los datos recolectados de un cultivo, mientras que el estado actual son los datos recientes de un cultivo. Los eventos salientes se relacionan a los reportes generados y solicitudes para la recolección de datos.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407496489439332/Green_Tols_15.jpg?ex=66dd3de7&is=66dbec67&hm=01ec1e56d1201ca09311d6ab71e95147e65806b2e9b4de548e3f86aa92becede&=&format=webp&width=2154&height=1246)

##### Bounded context: Sistema IoT
Este contexto nos brinda datos como temeperatura, pH y humedad del suelo a través de los sensores. Este context es el centro del dominio, es lo que nos permite generar ganancias y se personaliza para cada cliente. Los eventos relacionados a la recolección de datos y evaluación del uso del actuador son los que permiten entrar a este contexto. Actuador de refiere al sistema de riego del cultivo, el cuál se activará si la humedad del suelo no es óptima. Los eventos salientes son los que generen el reporte del cultivo, los cuales son eventos de entrada para el bounded context "Estado de cultivo".
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407496875315232/Green_Tols_14.jpg?ex=66dd3de8&is=66dbec68&hm=fd4ebdd935a15f39e047358ddbcafa0302c23a138a47a47b6ed181e6bdc2febd&=&format=webp&width=2154&height=1242)

### 4.1.2. Context Mapping

En esta sección se describen los contactos y relaciones entre los contextos delimitados con sus patrones correspondientes. La relación entre "Estado de cultivo" y "Solución IoT" es de tipo Upstream Dowstream, ya que los cambios en la recolección de datos de los sensores tienen un impacto en la forma en la que se generan los reportes de los cultivos de los usuarios, sin embargo cualquier cambio o falla de "Estao de cultivo" no tiene un impacto en la recolección de datos IoT. Los sensores y actuadores siguen funcionando sin problema. Por otro lado, "Estado de cultivo" y "Cuenta" tienen una relación Partnership ya que un error en cualquiera de los dos, termina afectando a ambos contextos. Si la cuenta falla, el usuario no puede ver los reportes de su cultivo, y si los reportes fallan, aunque pueda iniciar sesión, no sirve de nada ya que no tiene acceso a las funcionalidades del sistema. El mismo tipo de relación ocurre entre "Cuenta" e "Inventario de cultivo".
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280407512658612314/Green_Tols_17.jpg?ex=66dd3deb&is=66dbec6b&hm=c7f7894771cd4d7dc3c54aaeb3478a5de65d301a0a6570f002e94a1d5b7e80cd&=&format=webp&width=798&height=700)

### 4.1.3. Software Architecture
Para desarrollar la arquitectura de nuestro software hemos usado el modelo C4, el cuál descompone la estructura del sistema en contenedores y componentes. Hemos usado la herramienta Visual Paradigm para generar nuestros diagramas de arquitectura. En esta sección se aboradrán los diagramas en los niveles de contexto, contenedores y despliegue.
#### 4.1.3.1. Software Architecture System Landscape Diagram
Este diagrama permite ver nuestro sistema funcionando en el mundo real, abarcando más alla de sistemas externos y usuarios de nuestro dominio. Nuestro sistema aparte de ser usados por los dueños de los invernaderos, será usado por las personas encargadas de dar mantenimiento a los cultivos.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280938931776651388/Green_Tools-Landscape.png?ex=66dd3298&is=66dbe118&hm=15994e1d32299191c71bc4f5f105d539ee0f49456573b9fcf51940e5158aa039&=&format=webp&quality=lossless&width=1428&height=1208)

#### 4.1.3.2. Software Architecture Context Level Diagrams
Este diagram nos permite ver nuestros sistema de manera más general, el cual se representa como una caja en el centro y rodeado por los usuarios y sistema externos con los que interactua. Para nuestro dominio existen dos tipos de usuarios, los dueños de microcultivos e invernaderos.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1280938932044959745/Green_Tools-Context.png?ex=66dd3298&is=66dbe118&hm=930576b10800f2235126febb777546b662773c1153ab35c36b0aa324b1003630&=&format=webp&quality=lossless&width=1088&height=650)

#### 4.1.3.3. Software Architecture Container Level Diagrams.
Los contenedores son los servidores o productos de software que conforman nuestro sistema, es en esencia una unidad desplegable o ejecutable que compila código o almacena datos. Nuestos sistema usa una Aplicación Web para entregar el contenido estático y dinámico como el Landing Page y Single Page App. El Single Page App es el que provee de todas las funcionalidades para monitorear el cultivo, la aplicación móvil provee las mimas funcionalidades pero para dispositivos móvil. Nuestra API almacena los reportes de los cultivos, estos reportes se generan con los datos que envía el Edge Computing Server, el cuál recolecta y resume la información enviada por los sensores a través del Embedded App. Este último es el software que corre en el microcontrolador ESP32 para el funcionamiento de los sensores y actuadores.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1282166668872908821/Green_Tools-Containers_1.png?ex=66de5e43&is=66dd0cc3&hm=ee475c4fb134b62a57dc8b381d6329ac534451fbbe90a41689217e5003bcb06b&=&format=webp&quality=lossless&width=854&height=671)

#### 4.1.3.4. Software Architecture Deployment Diagrams
Este último diagrama muestra las plataformas y herramientas de despliegue para cada uno de nuestros contenedores. El single Page App funciona en el navegador del usuario, la aplicación móvil en el smarthpone del usuario y el Embedded App en el microcontrolador ESP32. Los otros contenedores si necesitan ser desplegados en servidores Apache Tomcat y Azure DB para las bases de datos.
![Texto alternativo](https://media.discordapp.net/attachments/1280405882517196875/1282166668553879654/Green_Tools-Deployment_1.png?ex=66de5e43&is=66dd0cc3&hm=ab4f1b5ae5b06cbcc6771af5de75291bef0d90461b7b7f33e6acee0aa933e7bf&=&format=webp&quality=lossless&width=876&height=671)

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

![Account Bounded ContextC4](https://github.com/user-attachments/assets/5366a07f-ec6b-4cd9-92d3-4dd93e46b638)

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

![Account Bounded Context-DiagramaC](https://media.discordapp.net/attachments/1280405882517196875/1282145122489860127/BD_CUENTA.png?ex=66de4a32&is=66dcf8b2&hm=38c1470d22f7a57b9633e097a609bc0fa542e3ebcc7e9911c8da7f0eb4e21348&=&format=webp&quality=lossless&width=825&height=573)

##### 4.2.1.6.2. Bounded Context Database Design Diagram

![Account Bounded Context](https://media.discordapp.net/attachments/1280405882517196875/1282150691657224233/GreenTools-2024-09-07_20-27.png?ex=66de4f62&is=66dcfde2&hm=78cb1a1e0b5af71acbf18ef5dddd8c4eba049437e4d70e7ed651338c2a5d18f8&=&format=webp&quality=lossless&width=947&height=671)

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

![IoT System Bounded ContextC4](https://github.com/user-attachments/assets/88b59230-c175-48ea-a85f-d2af94296e17)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

![IoT System Bounded Context-DiagramC](https://media.discordapp.net/attachments/1280405882517196875/1282145122741391380/BC_SISTEMA_IOT.png?ex=66de4a32&is=66dcf8b2&hm=db13828d866641dd0e45c3c80b9d7012a06ec4e20560a9bec6957151394987db&=&format=webp&quality=lossless&width=195&height=638)

##### 4.2.2.6.2. Bounded Context Database Design Diagram

![IoT System Bounded Context](https://media.discordapp.net/attachments/1280405882517196875/1282150691997225001/GreenTools-2024-09-07_20-28_1.png?ex=66de4f62&is=66dcfde2&hm=7fcb74b595b854f0976ba9fa710032cea580ae34bde69358a6c975dfcf399713&=&format=webp&quality=lossless&width=947&height=671)

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

![Crop Inventory Bounded ContextC4](https://github.com/user-attachments/assets/e91bac39-f8ab-44ef-8056-f28f784ab8f5)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

![Crop Inventory Bounded Context-DiagramC](https://media.discordapp.net/attachments/1280405882517196875/1282145122972336231/BC_INVENTARIO_CULTIVO.png?ex=66de4a32&is=66dcf8b2&hm=f4572290d1e6835be10d8d1c0daca9722ec7684a12ba027b7df236bafcbc8cde&=&format=webp&quality=lossless&width=316&height=671)

##### 4.2.3.6.2. Bounded Context Database Design Diagram

![Crop Status Bounded Context](https://media.discordapp.net/attachments/1280405882517196875/1282150692420583454/GreenTools-2024-09-07_20-28.png?ex=66de4f62&is=66dcfde2&hm=7b71bf96310cd7066836c673a41fafb42b0b2507b6cb5993d6c21b2ab6c027f8&=&format=webp&quality=lossless&width=947&height=671)

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

![Crop Status Bounded ContextC4](https://github.com/user-attachments/assets/c4c60e07-357c-438e-bd78-021fac633696)

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

![Crop Status Bounded Context-DiagramC](https://media.discordapp.net/attachments/1280405882517196875/1282145123215478845/BD_REPORTE.png?ex=66de4a32&is=66dcf8b2&hm=b68a941cc498c73c7e400402e89e4fda569db05e50df4f5ab73f09d2eadb137b&=&format=webp&quality=lossless&width=534&height=465)

##### 4.2.4.6.2. Bounded Context Database Design Diagram

![Crop Status Bounded Context](https://media.discordapp.net/attachments/1280405882517196875/1282150692697669685/GreenTools-2024-09-07_20-27_1.png?ex=66de4f62&is=66dcfde2&hm=c7fb353f3e617af167dae216d22a39e1c4cdd9ea0cd82bf481e177409eda3687&=&format=webp&quality=lossless&width=947&height=671)

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines
En esta sección, se definen las directrices de estilo que garantizarán una presentación visual coherente para todo el equipo de desarrollo. Se incluye un repositorio centralizado con assets, fuentes y otros recursos comunes para mantener la consistencia en las aplicaciones web y móvil. Estas guías están divididas en **General Style Guidelines**, **Web Style Guidelines**, y **Mobile Style Guidelines** para asegurar la homogeneidad en toda la plataform que  facilita el reconocimiento instantáneo por parte de nuestros clientes y stakeholders.
### General Style Guidelines

En esta sección se describen las decisiones y referencias visuales clave que establecen los fundamentos de la identidad visual de **GreenTools**. Estas directrices abarcan **Branding**, **Typography**, **Colors**, **Spacing**, así como las dimensiones para el **tono de comunicación y lenguaje aplicado**. Estas decisiones visuales se alinean con los principios del diseño de la marca y el sistema visual adoptado.

#### Branding
El **branding** de GreenTools está centrado en reflejar su misión de sostenibilidad y tecnología avanzada. La identidad de la marca es clara, orientada a la optimización de la agricultura mediante IoT, lo que se refleja en un **logotipo limpio y simple** que simboliza innovación (bombillo) y naturaleza (planta).

- **Valores clave**: Sostenibilidad, Innovación, Eficiencia.
- **Tono visual**: Natural, Tecnológico, Futurista.
- **Logotipo**: 
    ![Logo](https://drive.google.com/uc?export=view&id=15RvMnlCJf7e-WBn3nUwddx3yADLhFJg3)
  - El logotipo combina un bombillo con una planta en su interior, simbolizando la fusión entre tecnología y agricultura ecológica.


#### Typography
La elección de tipografía sigue una estética moderna y funcional, utilizando fuentes sans-serif como **Roboto**, **Arial** o **Open Sans**, que ofrecen buena legibilidad tanto en interfaces web como móviles. Estas tipografías reflejan claridad y simplicidad, alineándose con la misión de ofrecer una solución tecnológica fácil de usar.

- **Fuente principal**: **Roboto** (o alternativa sans-serif). Puedes descargar la fuente desde [Google Fonts](https://fonts.google.com/specimen/Roboto).
- **Tamaños de fuente**:
  - **Títulos**: Tamaños mayores para encabezados, en torno a 24px - 32px.
  - **Subtítulos**: Tamaños intermedios para subcategorías, 18px - 24px.
  - **Cuerpo de texto**: Texto general entre 14px - 16px para garantizar una lectura cómoda.

El uso de **espaciado entre letras** y **líneas de texto** debe ser amplio para evitar aglomeración, mejorando así la experiencia del usuario.

##### Colors
La paleta de colores de GreenTools refleja su compromiso con la sostenibilidad y el enfoque natural-tecnológico. Los colores están pensados para transmitir serenidad, profesionalismo y modernidad.

- **Verde Claro (#A8D5BA, RGB: 168, 213, 186)**: Color de fondo principal. Transmite calma, equilibrio y un enfoque natural.
  - Muestra de color: ![Verde Claro](https://example.com/verde-claro)
- **Verde Oscuro (#3A795D, RGB: 58, 121, 93)**: Usado en iconos y acentos. Refleja confianza, estabilidad y conexión con la naturaleza.
  - Muestra de color: ![Verde Oscuro](https://example.com/verde-oscuro)
- **Rojo (#D0605E, RGB: 208, 96, 94)**: Reservado para botones de acción (CTAs) y alertas. Su uso está dirigido a captar la atención en puntos importantes o críticos.
  - Muestra de color: ![Rojo](https://example.com/rojo)

Puedes descargar la paleta de colores completa en formato [ASE](https://example.com/paleta-ase) para usarla en tus herramientas de diseño.

#### Spacing
El **espaciado** juega un papel clave en el diseño limpio y funcional de GreenTools. Los márgenes y rellenos entre elementos visuales deben garantizar una separación suficiente, permitiendo que cada componente tenga espacio para respirar sin saturar al usuario con demasiada información en pantalla.

- **Márgenes**: Utilizar un margen consistente entre secciones, idealmente de **16px** a **24px** para pantallas grandes, y **8px** a **12px** en móviles.
- **Padding**: Los botones y elementos interactivos deben tener un relleno interno que garantice que el contenido sea fácil de interactuar, con un mínimo de **16px** de padding.

#### Tono de Comunicación y Lenguaje Aplicado
El tono de comunicación de GreenTools está cuidadosamente equilibrado entre lo **formal** y lo **entusiasta**, con un enfoque **respetuoso** y **sereno**, adecuado para los usuarios agrícolas que buscan soluciones tecnológicas.

- **Formal/Casual**: El tono debe ser **formal** pero accesible, permitiendo que los usuarios se sientan guiados y apoyados en sus decisiones, sin que el lenguaje sea demasiado técnico o inaccesible.
- **Entusiasta/Sereno**: Se busca un enfoque más **sereno** que entusiasta, dado que los usuarios necesitan claridad y precisión para tomar decisiones críticas sobre sus cultivos.
- **Respetuoso/Irreverente**: Siempre **respetuoso** y profesional, reflejando el compromiso de GreenTools con el éxito y la sostenibilidad agrícola.

#### Referencias Visuales
Para garantizar consistencia en todas las plataformas, se puede tomar como referencia el **[Material Design System](https://material.io/design)** de Google, el cual proporciona una base sólida para la organización de los componentes visuales y la interacción. Las adaptaciones hechas al sistema existente tienen en cuenta las particularidades del sector agrícola y la necesidad de un diseño más sobrio y accesible.

#### Principios de Diseño
1. **Simplicidad**: La interfaz debe ser clara y fácil de navegar, eliminando distracciones innecesarias.
2. **Funcionalidad**: Cada decisión de diseño debe estar orientada a facilitar el uso de las herramientas, minimizando la complejidad.
3. **Coherencia**: Asegurarse de que todas las decisiones de diseño sean consistentes en toda la plataforma, tanto en la versión web como en la móvil.
4. **Accesibilidad**: Se debe priorizar que los elementos sean accesibles para todos los usuarios, considerando buenas prácticas de diseño inclusivo (como contraste adecuado y tamaños de fuente legibles).

Estas directrices generales ofrecen las bases para crear una experiencia visual y comunicacional que esté alineada con la identidad de GreenTools, reflejando sus valores y objetivos de sostenibilidad y eficiencia.

  ### 5.1.2. Web, Mobile and IoT Style Guidelines
  _Contenido por añadir..._

## 5.2. Information Architecture

  ### 5.2.1. Organization Systems
  _Contenido por añadir..._

  ### 5.2.2. Labeling Systems
  _Contenido por añadir..._

  ### 5.2.3. SEO Tags and Meta Tags
  _Contenido por añadir..._

  ### 5.2.4. Searching Systems
  _Contenido por añadir..._

  ### 5.2.5. Navigation Systems
  _Contenido por añadir..._

## 5.3. Landing Page UI Design

  ### 5.3.1. Landing Page Wireframe
  _Contenido por añadir..._

  ### 5.3.2. Landing Page Mock-up
  _Contenido por añadir..._

## 5.4. Applications UX/UI Design

  ### 5.4.1. Applications Wireframes
  _Contenido por añadir..._

  ### 5.4.2. Applications Wireflow Diagrams
  _Contenido por añadir..._

  ### 5.4.3. Applications Mock-ups
  _Contenido por añadir..._

  ### 5.4.4. Applications User Flow Diagrams
  _Contenido por añadir..._

## 5.5. Applications Prototyping
_Contenido por añadir..._

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

  ### 6.1.1. Software Development Environment Configuration
  _Contenido por añadir..._
  
  ### 6.1.2. Source Code Management
  _Contenido por añadir..._
  
  ### 6.1.3. Source Code Style Guide & Conventions
  _Contenido por añadir..._
  
  ### 6.1.4. Software Deployment Configuration
  _Contenido por añadir..._

## 6.2. Landing Page, Services & Applications Implementation

  ### 6.2.1. Sprint 1

  #### 6.2.1.1. Sprint Planning n
  _Contenido por añadir..._
    
  #### 6.2.1.2. Sprint Backlog n
  _Contenido por añadir..._
    
  #### 6.2.1.3. Development Evidence for Sprint Review
    _Contenido por añadir..._
    
  #### 6.2.1.4. Testing Suite Evidence for Sprint Review
    _Contenido por añadir..._
    
  #### 6.2.1.5. Execution Evidence for Sprint Review
    _Contenido por añadir..._
    
  #### 6.2.1.6. Services Documentation Evidence for Sprint Review
    _Contenido por añadir..._
    
  #### 6.2.1.7. Software Deployment Evidence for Sprint Review
    _Contenido por añadir..._
    
  #### 6.2.1.8. Team Collaboration Insights during Sprint
    _Contenido por añadir..._


# Conclusiones
La implementación de user personas fue fundamental durante la fase de arquitectura de nuestro proyecto IoT. Al enfocar el diseño en dueños de invernaderos y microcultivos, pudimos estructurar la arquitectura de forma que cada uno de los bounded contexts —IoT system, inventario, reporte y cuenta— reflejara sus necesidades. Esto nos permitió visualizar cómo la plataforma atendería de manera eficiente la gestión de sensores, cultivos, análisis de datos y administración de usuarios, asegurando que la solución esté alineada con las expectativas y flujos de trabajo reales de los usuarios.

Las entrevistas con usuarios del segmento objetivo fueron clave para la recolección de información relevante para definir nuestros user personas. Esta retroalimentación directa permitió estructurar la arquitectura del sistema, asegurando que los bounded contexts como el manejo de sensores, cultivos, reportes y cuentas se alinearan con las necesidades y procesos reales de los dueños de invernaderos y microcultivos. Así, logramos una arquitectura más robusta y centrada en el usuario.

El enfoque de Domain-Driven Design (DDD) fue esencial en la definición de la arquitectura de nuestro proyecto, ayudándonos a estructurar el sistema en cuatro bounded contexts clave: IoT system, inventario, reporte y cuenta. Estos contextos claramente delimitados nos permitieron dividir el dominio agrícola en áreas funcionales y coherentes, facilitando una mejor comprensión y gestión de los requisitos del proyecto. Este enfoque garantiza que, cuando se desarrolle el software, cada componente del sistema refleje las particularidades del dominio agrícola y esté alineado con las necesidades del usuario final.

El uso del modelo C4 para diseñar la arquitectura de software fue clave en nuestro proyecto. Este enfoque nos permitió visualizar claramente las diferentes capas de abstracción, desde los diagramas de contexto hasta los componentes internos de cada bounded context (IoT system, inventario, reporte y cuenta). Al descomponer el sistema en estas vistas, logramos una representación precisa y comprensible tanto para los desarrolladores como para los stakeholders, facilitando la alineación de expectativas y asegurando que la arquitectura pueda evolucionar de manera consistente a medida que avance el proyecto.

El uso de diagramas de clases, diagramas de bases de datos y diagramas de componentes C4 para cada bounded context (IoT system, inventario, reporte y cuenta) fue fundamental para estructurar la arquitectura de manera sólida y detallada. Los diagramas de clases nos permitieron definir las relaciones entre las entidades clave dentro de cada contexto, mientras que los diagramas de bases de datos facilitaron la organización y normalización de la información relacionada con sensores, cultivos, reportes y usuarios. Por otro lado, los diagramas de componentes del modelo C4 nos ayudaron a visualizar cómo se integran los distintos servicios y módulos, asegurando una correcta interacción entre ellos y garantizando la cohesión en el diseño general del sistema. Estos diagramas proporcionaron una guía clara para el desarrollo futuro, asegurando que cada contexto esté alineado con las necesidades funcionales y técnicas del proyecto.

# Bibliografía
Ahmad, D. S. N. A., Fatah, F. A., Saili, A. R., Saili, J., Hamzah, N. M., Nor, R. C. M., Omar, Z., & Ghali, M. (2025). Exploration of the Challenges in Adopting Smart Farming Among Smallholder Farmers: A Qualitative Study. *Journal of Advanced Research in Applied Sciences and Engineering Technology*, 45(1), 17–27. [https://doi.org/10.37934/araset.45.1.1727](https://doi.org/10.37934/araset.45.1.1727)

Dibbern, T., Romani, L. A. S., & Massruhá, S. M. F. S. (2024). Main drivers and barriers to the adoption of Digital Agriculture technologies. *Smart Agricultural Technology*, 8. [https://doi.org/10.1016/j.atech.2024.100459](https://doi.org/10.1016/j.atech.2024.100459)

Hundal, G. S., Laux, C. M., Buckmaster, D., Sutton, M. J., & Langemeier, M. (2023). Exploring Barriers to the Adoption of Internet of Things-Based Precision Agriculture Practices. *Agriculture (Switzerland)*, 13(1). [https://doi.org/10.3390/agriculture13010163](https://doi.org/10.3390/agriculture13010163)

# Anexos

upc-pre-202402-si572-WV71-Fractalis-expo-tb1

[https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EVt2-jDf-c9HgC7IvDM1PHwBrfitg_t6FMiSBYMjUlW9fQ?e=LPHiwN](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EVt2-jDf-c9HgC7IvDM1PHwBrfitg_t6FMiSBYMjUlW9fQ?e=LPHiwN)

upc-pre-202402-si572-WV71-Fractalis-entrevista-tb1

[https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EckNEWl06ixHle5L2RIWuHsBTcYcGWSCUKFTc-n6uipqXw?e=ybOhvp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202013614_upc_edu_pe/EckNEWl06ixHle5L2RIWuHsBTcYcGWSCUKFTc-n6uipqXw?e=ybOhvp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

