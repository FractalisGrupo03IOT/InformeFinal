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

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

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

## Entrevistado 01

|                     |                                                                                                                                                                                                                 |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y Apellido**         | Sonia Hcaylluhua                                                                                                                                                                                                                |
| **Edad**                      | 32                                                                                                                                                                                                                                |
| **Ubicación**                 | PUNO - PUNO - PUNO                                                                                                                                                                                                              |
| **Imagen**                    | ![Sonia Hcaylluhua](https://media.discordapp.net/attachments/1228537935368945717/1279448960561447057/image.png?ex=66d47b33&is=66d329b3&hm=b30536094cd394565707fc9a99158b1640d17c0b5a18fdc5c11122802c73bea6&=&format=webp&quality=lossless&width=742&height=417) |
| **Cultivo Principal**         | Fresas                                                                                                                                                                                                                          |
| **Interés en Tecnología**     | Alta, está interesada en herramientas tecnológicas para optimizar procesos y mejorar la eficiencia del negocio.                                                                                                                   |
| **Retos en Gestión**          | Monitoreo manual significativo y costos altos en riego, especialmente en términos de consumo de agua.                                                                                                                             |
| **Solución Tecnológica Deseada** | Aplicación móvil equipada con sensores para monitoreo en tiempo real de los cultivos.                                                                                                                                         |
| **Inversión en Tecnología**   | Abierta a considerar la inversión si la tecnología ofrece mejoras significativas en la gestión del invernadero; no tiene una cifra exacta.                                                                                          |
| **Necesidad de Capacitación** | Sí, necesitaría capacitación para utilizar correctamente las nuevas herramientas tecnológicas.                                                                                                                                  |
| **Expectativas de la Tecnología** | Optimizar el riego, reducir gastos, mejorar la productividad y expandir el negocio para llegar a más mercados.                                                                                                                   |

|                       |                                                                                                                                                                                                                               |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y Apellido**          | Victor Felopez                                                                                                                                                                                                                           |
| **Edad**                       | 29 años                                                                                                                                                                                                                                  |
| **Ubicación**                  | Lima, Victoria                                                                                                                                                                                                                           |
| **Imagen**                     | ![Victor Felopez](https://media.discordapp.net/attachments/624357483116232707/1280635277475582084/image.png?ex=66d8cc0b&is=66d77a8b&hm=c045d7c0c2c236c52ec65cf16a86fed0182d0608c4e2a356a10a0dbecc9a0ef5&=&format=webp&quality=lossless&width=550&height=226) |
| **Cultivo Principal**          | Tomates y otros cultivos que requieren alta precisión                                                                                                                                                                                     |
| **Interés en Tecnología**      | Alta, está interesado en aplicar IoT para mejorar la gestión de sus cultivos en invernaderos.                                                                                                                                            |
| **Retos en Gestión**           | Actualmente no utiliza tecnología avanzada, lo que limita la eficiencia y control en tiempo real de sus cultivos.                                                                                                                        |
| **Solución Tecnológica Deseada**| Aplicación móvil con monitoreo en tiempo real de los cultivos, acompañada de videos instructivos para facilitar su uso.                                                                                                                  |
| **Inversión en Tecnología**    | Está dispuesto a considerar la inversión si la tecnología puede mejorar la eficiencia operativa de su invernadero.                                                                                                                        |
| **Necesidad de Capacitación**  | Sí, considera importante el soporte educativo para adaptarse rápidamente a nuevas tecnologías.                                                                                                                                           |
| **Expectativas de la Tecnología** | Monitoreo en tiempo real, mejorar la eficiencia de su operación agrícola, y soporte educativo a través de videos instructivos.                                                                                                             |
### 2.2.3. Análisis de entrevistas

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

![ASM-01](https://media.discordapp.net/attachments/624357483116232707/1279965593709056020/image.png?ex=66d8569a&is=66d7051a&hm=20ae08a09bb4c3f5213fe1240a73f783a6088d75153cffa54d5eae15950efe99&=&format=webp&quality=lossless)

![ASM-02](https://media.discordapp.net/attachments/624357483116232707/1279965604819894292/image.png?ex=66d8569c&is=66d7051c&hm=736688e1d56dc3283a4ff22f531e44a5277235717e61f39d196bf7e1ea9d7385&=&format=webp&quality=lossless)

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
