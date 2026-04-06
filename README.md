<div align="center">
  <img src="Resources/UPC_logo_transparente.png" alt="Logo-UPC" width="150">

## Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**Ciclo:** 2026-10

**Código y Nombre del Curso:** 1asi0730 - Aplicaciones Web

**Sección:** 12053

**Profesor:** Efraín Ricardo Bautista Ubillús

----
## Informe de Trabajo Final
### SyncedHealth

### CortiSense
#### Relación de integrantes 
| Integrante                  | Código         |
|---------------------------------|----------------|
| Gutierrez Santillán, Sebastián Augusto             | u202417329     |
| León Morales, Johan Yonel             | u20231h055     |
| Mauricio Silva, Guiou Justinn        | u20241e242     |
| Pareja Calloapaza, Marcelo Fausto          | u202411627     |
| Santiago Atanacio, Jairo Mathias                   | u202418755     |

</div>

<br><div align="center"><h3>Abril 2026</h3></div><br>
<div style="text-align: justify;">

<br><br>
---
### Registro de Versiones del Informe

<div align="justify">

|**Versión**|**Fecha**|**Autor**|**Descripción de modificación**|
| - | - | - | - |
|1\.0|05/04/2026|Marcelo Fausto Pareja Calloapaza|Se agregó la estructura inicial del proyecto|
|1\.1\.0|06/04/2026|Marcelo Fausto Pareja Calloapaza|Se agregó la Descripción de la StartUp|

</div><br><br>

---
<div align="justify">

# Project Report Collaboration Insights

URL de Organización de GITHUB del equipo SyncedHealth:
https://github.com/SyncedHealth-AplicacionesWeb

URL de Repositorio del Project Report:
https://github.com/SyncedHealth-AplicacionesWeb/upc-pre-202610-1asi0730-12053-SyncedHealth-report

<strong>*Entrega TB1:*</strong>


---

# Contenido

- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statement](#1221-lean-ux-problem-statement)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de Entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture Event Storming.](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming.](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3 Validation Interviews.](#53-validation-interviews)
    - [5.3.1 Diseño de entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2 Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3 Evaluaciones Según Heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4 Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:<br><br>
**ABET – EAC - Student Outcome 5**<br>
**Criterio:** La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.<br><br>
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.<br><br>

<table >
  <thead>
    <tr>
      <th colspan="3"><b>Criterio específico</b></th>
      <th colspan="3"><b>Acciones realizadas</b></th>
      <th colspan="3"><b>Conclusiones</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
	<td colspan="3">Trabaja en equipo para proporcionar liderazgo en forma conjunta.</td>
      <td colspan="3" align = "justify">
      <h3>Gutierrez Santillán, Sebastián Augusto</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>León Morales, Johan Yonel</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Mauricio Silva, Guiou Justinn</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Pareja Calloapaza, Marcelo Fausto</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Santiago Atanacio, Jairo Mathias</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
          <br>
      </td>
      <td colspan="3">
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      </td>
    </tr>
    <tr>
      <td colspan="3">Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
      <td colspan="3" align = "justify">
      <h3>Gutierrez Santillán, Sebastián Augusto</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>León Morales, Johan Yonel</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Mauricio Silva, Guiou Justinn</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Pareja Calloapaza, Marcelo Fausto</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      <h3>Santiago Atanacio, Jairo Mathias</h3>
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
		  <br>
      </td>
      <td colspan="3">
        <b>AV1</b><p></p>
        <b>TP1</b><p></p>
        <b>AV2</b><p></p>
        <b>TF1</b><p></p>
      </td>
    </tr>
  </tbody>
</table>

---

# Capítulo I: Introducción
## 1.1 Startup Profile
### 1.1.1 Descripción de la Startup

**Nombre:**  SyncedHealth

**Área:**  Innovación tecnológica en Medicina y manejo de niveles de estrés

SyncedHealth es una startup conformada por estudiantes de la facultad de ingeniería de la Universidad Peruana de Ciencias Aplicadas (UPC). La compañía nace con el objetivo de mejorar, optimizar y desarrollar el sistema de salud mediante una correcta gestión de los horarios de trabajo del personal médico. De esa manera, mejorar su desempeño en horas laborales. A través de la integración de dispositivos IoT avanzados, monitoreamos biomarcadores críticos como los niveles de cortisol y la variabilidad de la frecuencia cardíaca para prevenir el agotamiento profesional (burnout). De esa manera, buscamos mejorar su desempeño en horas laborales y garantizar la seguridad del paciente.

* **Misión:**
La misión de SyncedHealth es salvaguardar el bienestar del personal sanitario mediante la implementación de soluciones tecnológicas de vanguardia que permitan una gestión humana y científica de la carga laboral. Nos dedicamos a transformar la cultura de trabajo en las instituciones de salud, sustituyendo la fatiga crónica por un monitoreo preventivo basado en datos reales. A través de nuestros sistemas de medición IoT, buscamos proporcionar diagnósticos precisos sobre el estado físico y mental del médico en tiempo real, permitiendo que la toma de decisiones administrativas se traduzca en una atención médica de mayor calidad, con menos errores y un personal más resiliente.

* **Visión:**
La visión de SyncedHealth es consolidarse como el estándar global en el monitoreo de la salud ocupacional médica, liderando la transición hacia hospitales inteligentes y proactivos. Nos proyectamos como el aliado tecnológico indispensable para los sistemas de salud en la región, donde la integración de biotecnología e inteligencia de datos permita erradicar el estrés crónico en el personal de salud. Aspiramos a ser la plataforma que no solo gestione horarios, sino que dicte las pautas para una práctica médica sostenible, equilibrada y tecnológicamente optimizada.

* **Valores:**
	* Nos comprometemos con la precisión absoluta de los datos. Valoramos el rigor científico de nuestras mediciones de cortisol y signos vitales, entendiendo que de su exactitud depende la salud de quienes cuidan a los demás.
	* Creemos en la detección temprana antes que en la corrección. Nuestra filosofía se centra en anticipar el agotamiento del personal para evitar consecuencias críticas tanto para el profesional como para el paciente.
	* Buscamos constantemente la mejora de nuestros dispositivos IoT. No nos conformamos con lo existente, sino que adaptamos la tecnología más reciente para solucionar los desafíos más complejos del sector salud.
	* Valoramos la privacidad y el manejo responsable de la información sensible. Garantizamos que el monitoreo de salud se realice bajo estándares éticos, asegurando que la tecnología sea siempre una herramienta de apoyo y protección para el trabajador.
	* Fomentamos un equilibrio donde la tecnología sirve a la humanidad. Entendemos que un sistema de salud eficiente solo es posible cuando el personal médico está en sus plenas capacidades físicas y mentales.
	* Nos enfocamos en resultados tangibles. Nuestra plataforma de pago garantiza un soporte continuo y una actualización constante, asegurando que las instituciones de salud cuenten con una herramienta de alta disponibilidad para la gestión de su capital más valioso: su gente.

  ### 1.1.2 Perfiles de integrantes del equipo
  
| **Integrante**                         | **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Imagen**                                                                                                       |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Gutierrez Santillán, Sebastián Augusto - u202417329** | | <img src="Resources/Profiles/sebastian.jpg" alt="Foto de Gutierrez Santillán, Sebastián Augusto" width="150"/> |
| **León Morales, Johan Yonel - u20231h055** | | <img src="Resources/Profiles/johan.jpg?raw=true" alt="Imagen de León Morales, Johan Yonel"/> |
| **Mauricio Silva, Guiou Justinn - u20241e242** | | <img src="Resources/Profiles/mauricio.jpg?raw=true" alt="Imagen de Mauricio Silva, Guiou Justinn"/> |
| **Pareja Calloapaza, Marcelo Fausto - u202411627** |Mi nombre es Marcelo Fausto Pareja Calloapaza, tengo 19 años y curso el 5to ciclo de la carrera de Ingeniería de Software que es identificado mediante el código u202411627. Soy una persona de naturaleza sincera y motivadora, pues siempre me encuentro dispuesto a brindar mi ayuda y colaboración en las diversas situaciones ellas sean requeridas. Algunas de mis mayores fortalezas son mis habilidades relacionadas con la escritura de código, lectura y redacción de textos, las cuales uso activamente para enriquecer múltiples proyectos. El propósito que me guía en cualquiera de ellos es la búsqueda de la perfección de mis habilidades sociales y conocimientos, los cuales se encuentran centrados en un enfoque de crecimiento personal y profesional.| <img src="Resources/Profiles/marcelo.jpg?raw=true" alt="Imagen de Pareja Calloapaza, Marcelo Fausto"/> |
| **Santiago Atanacio, Jairo Mathias - u202418755** | | <img src="Resources/Profiles/santiago.jpg?raw=true" alt="Imagen de Santiago Atanacio, Jairo Mathias"/> |

## 1.2 Solution Profile


### 1.2.1 Antecedentes y problemática


**5W's y 2H's**
<br>

* **What?**

<br><br>
* **Why?**

<br><br>
* **Who?**

<br><br>
* **When?**

<br><br>
* **Where?**

<br><br>
* **How?**

<br><br>
* **How much?**

<br><br>

### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statement
**Problem Statement 1:**
<br>
..
<br>

**Problem Statement 2:**
<br>
..
<br>

#### 1.2.2.2 Lean UX Assumptions

 + **User Assumptions:** 

    + **¿Quién es el usuario?** <br> ..<br><br>

    + **¿Dónde encaja nuestro producto en su trabajo o en su vida?** <br>.. <br><br>

    + **¿Cuándo y cómo se utiliza nuestro producto?** <br>.. <br><br>

    + **¿Qué problemas resuelve nuestro producto?** <br>.. <br><br>

    + **¿Qué características son importantes?** <br>.. <br><br>

    + **¿Cómo debe verse y comportarse nuestro producto?** <br>.. <br><br>

 + **Business Outcomes:** 

    1. **Creo que nuestros usuarios necesitan** 

    2. **Estas necesidades se pueden resolver con** 

    3. **Nuestros usuarios iniciales son** 

    4. **El valor #1 que un cliente quiere de nuestro servicio es que** 

    5. **El usuario también puede obtener beneficios adicionales como** 

    6. **Vamos a adquirir la mayoría de nuestros clientes a través de** 

    7. **Haremos dinero a través de** 

    8. **Nuestras competencias principales son** 

    9. **Los venceremos debido a** 

    11. **Nuestro mayor riesgo es** 

    12. **Resolveremos esto a través de** 

#### 1.2.2.3 Lean UX Hypothesis Statements
**Creemos que**  **sabremos que es cierto** 

**Creemos que**  **sabremos que es cierto** 

**Creemos que**  **sabremos que es cierto** 


#### 1.2.2.4 Lean UX Canvas

<table>
    <tr>
        <td valign="top" >
            <div align="center"> <br><b>Problema de negocios</b> </div><br>
            <p>Las PYMES constructoras pierden dinero y reputación por falta de control de KPIs y trazabilidad, generando errores estructurales y multas.</p><br>
        </td>
        <td rowspan="2" valign="top">
            <div align="center"><br><b>Ideas de las soluciones</b> </div><br>
            <p>Plataforma web "Kipu" para gestión centralizada, dashboards de control de inventarios, seguimiento de PPC y registro histórico de decisiones.
            </p><br>
        </td>
            <td valign="top">
            <div align="center"> <br><b>Resultados Comerciales</b> </div><br>
            <p>1. Reducción de RNC. 
			<br>2. Incremento en la retención de clientes (suscripción SaaS).
			<br>3. Posicionamiento como estándar tecnológico local.</p><br>
            </td>
        </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>Usuarios y Clientes</b></div><br>
            <p>Ingenieros civiles, arquitectos residentes y dueños de PYMES constructoras (sector privado).</p><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>Beneficios del usuario</b></div><br>
            <p>	1. Control total de costos.
			<br>2. Reducción de riesgos legales mediante trazabilidad.
			<br>3. Toma de decisiones basada en datos reales.</p><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"> <br><b>Hipótesis</b> </div><br>
            <p>Creemos que al digitalizar el control de obra (PPC e Inventarios), los gestores reducirán sobrecostos y mejorarán la precisión de entrega de sus proyectos.</p> <br>
        </td>
        <td valign="top">
            <div align="center"> <br><b>¿Qué es lo más importante que necesitamos aprender primero? </b> </div><br><p>¿Están los usuarios dispuestos a abandonar el registro manual por una app en obra para evitar multas y pérdidas?</p> <br>
        </td>
        <td valign="top">
            <div align="center">  <br><b>¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver las dudas y para hacer lo siguiente más importante?</b> </div><br><p>Crear un prototipo funcional que permita registrar el avance diario (PPC) y el uso de materiales clave, testeándolo con 2 constructoras locales.</p> <br>
        </td>
    </tr>
</table>

## 1.3 Segmentos Objetivo

+ **S1**<br>

    + **Características demográficas:** <br>
    + **Características geográficas:** <br><br>

+ **S2**<br>

    + **Características demográficas:** <br>
    + **Características geográficas:** <br><br>

---

# Capítulo II: Requirements Elicitation & Analysis


## 2.1 Competidores

En esta sección se identificarán los mejores referentes para posteriormente realizar un análisis competitivo que nos ayudará a saber nuestro posicionamiento y el valor agregado que ofreceremos en el mercado. 

Según la investigación, se descubrieron apps webs y/o aplicaciones similares. Sin embargo, estamos considerando cinco competidores directos o indirectos que se parezcan más a nuestra startup.

* **C1**<br>


* **C2**<br>


### 2.1.1 Análisis Competitivo

En esta sección se realizará el análisis competitivo de los competidores identificados en la sección inicial con el objetivo de tener una idea más clara sobre nuestro producto frente a los competidores y aprender para mejorar nuestro producto.

<table>
	<thead>
		<tr><th colspan="7">Competitive Analysis Landscape</th></tr>
	</thead>
	<tbody>
		<tr>
			<td colspan="2">¿Por qué llevar a cabo este análisis?</td>
			<td colspan="5"></td>
		</tr>
		<tr>
			<td colspan="2">
				<div align="center">Nombre</div>
			</td>
			<td><div align="center"><b>Nuestro</b></div></td>
			<td><div align="center"><b>C1</b></div></td>
			<td><div align="center"><b>C2</b></div></td>
			<td><div align="center"><b>C3</b></div></td>
			<td><div align="center"><b>C4</b></div></td>
		</tr>
		<tr>
			<td colspan="2">
				<div align="center">Logo</div>
			</td>
			<td><div align="center">
				<img src="Resources/Style%20Guidelines/logo.png?raw=true" alt="Our logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/procore.png?raw=true" alt="C1 logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/buildertrend.png?raw=true" alt="C2 logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/mondaydotcom.png?raw=true" alt="C3 logo"/>
			</div></td>
			<td><div align="center">
				<img src="Resources/Competitors/cype-presto.png?raw=true" alt="C4 logo"/>
			</div></td>
		</tr>
		<tr>
			<td rowspan="2">Perfil</td>
			<td>Overview</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Ventaja Competitiva</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="2">Marketing</td>
			<td>Mercado Objetivo</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Estrategias</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="3">Producto</td>
			<td>Servicios</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Precios</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Canales</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td rowspan="4">SWOT</td>
			<td>Fortalezas</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Debilidades</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Oportunidades</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Amenazas</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

**Estrategia de Diferenciación:**
**Estrategia de Liderazgo en Costos:**
**Estrategia de Marketing:**
**Tácticas:**

## 2.2 Entrevistas

En esta sección se abordará la investigación en base a la información que se obtendrá de los segmentos entrevistados con el objetivo de conocer mejor a nuestros segmentos objetivos y aprender de ellos y sus procesos.

### 2.2.1 Diseño de entrevistas

### 2.2.2 Registro de entrevistas

### 2.2.3 Análisis de entrevistas

## 2.3 Needfinding

### 2.3.1. User Personas.
### 2.3.2. User Task Matrix.
### 2.3.3. User Journey Mapping.
### 2.3.4. Empathy Mapping.

## 2.4. Big Picture Event Storming.
## 2.5. Ubiquitous Language

---
# Capítulo III: Requirements Specification

## 3.1. User Stories.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **US-XX** | | | **Escenario 1:** <br>Dado que <br>Cuando <br>Entonces | **EP-XX** |
| | | | | |

## 3.2. Impact Mapping

## 3.3. Product Backlog

---
# Capítulo IV: Product Design

## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.3. Web Applications Mock-ups.
### 4.4.4. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.
### 4.6.2. Software Architecture Context Diagram.
### 4.6.3. Software Architecture Container Diagrams.
### 4.6.4. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
## 4.8. Database Design.
### 4.8.1. Database Diagrams.

---
# Capítulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.
#### 5.2.1.2. Aspect Leaders and Collaborators.
#### 5.2.1.3. Sprint Backlog 1.
#### 5.2.1.4. Development Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.
## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
### 5.3.2. Registro de Entrevistas.
### 5.3.3. Evaluaciones según heurísticas.
## 5.4. Video About-the-Product.
---
# Conclusiones
# Bibliografía
# Anexos
