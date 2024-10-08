<div align="center">

## Universidad Peruana de Ciencias Aplicadas

![logo](assets/logos/upc_logo.png)

#### Nombre del curso: Aplicaciones Web
##### Carrera: Ingeniería de Software
##### Nombre del profesor: Ángel Augusto Velasquez Nuñez
##### Sección: WS53

#### "Informe de Trabajo Final"
##### Nombre de la Startup: Latte
##### Nombre del Producto: FoodSuit

#### Integrantes
Bernaola Pérez, André Arturo (U202114192)<br>
Grandez Mansilla, Jean Pierre (U202212484)<br>
Pacheco Astiguetta, Sebastian (U202110291)<br>
Paiva Quispe, Josue Gonzalo (U202119095)<br>
Velarde Luyo, Piero Alberto (U20211A620)<br>

**Agosto de 2024**
</div>

# Registro de Versiones del Informe
<table BORDER>
    <tr>
        <td>VERSION</td>
        <td>FECHA</td>
        <td> AUTOR </td>
        <td>DESCRIPCION DE MODIFICACION</td>
    </tr>
    <tr>
        <td>01</td>
        <td>17/08/2024</td>
        <td> Sebastian Pacheco Astiguetta </td>
        <td>Formato del documento</td>
    </tr>
    <tr>
        <td>02</td>
        <td>20/08/2024</td>
        <td>Josue Paiva Quispe</td>
        <td>Antecedentes y problematicas</td>
    </tr>
    <tr>
        <td>03</td>
        <td>20/08/2024</td>
        <td>Josue Paiva Quispe</td>
        <td>Lean UX Hypothesis Statements</td>
    </tr>
    <tr>
        <td>04</td>
        <td>21/08/24</td>
        <td>Sebastian Pacheco Astiguetta</td>
        <td>Desarrollo del descipción de la StartUp y segmentos Objetivos</td>
    </tr>
    <tr>
        <td>05</td>
        <td>21/08/24</td>
        <td>Piero Velarde</td>
        <td>Desarrollo del Lean UX Canvas</td>
    </tr>
    <tr>
        <td>06</td>
        <td>27/08/24</td>
        <td>Jean Grandez Mansilla</td>
        <td>Desarrollo del Needfinding e Impact Mapping</td>
    </tr>
    <tr>
        <td>07</td>
        <td>29/08/24</td>
        <td>Sebatian Pacheco Astiguetta</td>
        <td>Desarrollo del Análisis competitivo, Estrategias y tácticas frente a competidores, entrevistasy análisis</td>
    </tr>
    <tr>
        <td>08</td>
        <td>30/08/24</td>
        <td>Andre Bernaola</td>
        <td>Desarrollo de las User Stories y Product Backlog </td>
    </tr>
    <tr>
        <td>09</td>
        <td>04/09/24</td>
        <td>Piero Velarde</td>
        <td>>Desarrollo Information Arquitecture y Application Wireframes</td>
    </tr>
    <tr>
        <td>10</td>
        <td>06/09/24</td>
        <td>Andre Bernaola</td>
        <td>Desarrollo del Style Guidelines y Landing Page</td>
    </tr>
    <tr>
        <td>11</td>
        <td>07/09/24</td>
        <td>Sebastian Pacheco Astiguetta</td>
        <td>Domain Driven Software Architecture, Software Object Oriented Design y Database Design</td>
    <tr>
        <td>12</td>
        <td>07/09/24</td>
        <td>Josue Paiva Quispe</td>
        <td>Desarrollo de Application Mockups</td>
    </tr>
    <tr>
        <td>13</td>
        <td>07/09/24</td>
        <td>Jean Grandez Mansilla</td>
        <td>Desarrollo de Software Configuration Management</td>
    </tr>
</table>

## Contenido

- [Student Outcome](#student-outcome)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Capítulo I: Introducción](#cap1)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#cap2)
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



- [Capítulo III: Requirements Specification](#cap3)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)


- [Capítulo IV: Product Design](#cap4)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
        - [4.7.2. Class Dictionary](#472-class-dictionary)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)


- [Capítulo V: Product Implementation, Validation & Deployment](#cap5)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
            - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
            - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET – EAC - Student Outcome 5**
Criterio: *La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.*
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

<table>
	<tbody>
		<tr>
			<td>Criterio específico</td>
			<td>Acciones realizadas</td>
			<td>Conclusiones</td>
		</tr>
		<tr>
			<td>Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>
			<td>
                Bernaola Pérez, André Arturo<br>
                TB1<br>
                Desarrollé y analicé las historias de usuario, además de participar en la creación del prototipo de nuestro producto mediante el desarrollo de guías de estilo y la landing page, así como en la elaboración de un prototipo.<br>
                Grandez Mansilla, Jean Pierre<br>
                TB1<br>
                Realicé el análisis del needfinding, impact mapping y el desarrollo de software. Además, supervisé y participé en el desarrollo del prototipo de la solución.<br>
                Pacheco Astiguetta, Sebastian<br>
                TB1<br>
                Desarrollé el análisis de competidores, estrategias y tácticas frente a competidores, entrevistas y análisis, además del diseño de la arquitectura de software.<br>
                Paiva Quispe, Josue Gonzalo<br>
                TB1<br>
                Realicé el análisis de la startup, el perfil de la solución, el lean UX process y participé en la elaboración del prototipo, especialmente en la elaboración de la landing page como mockup.<br>
                Velarde Luyo, Piero Alberto<br>
                TB1<br>
                Desarrollé el Lean UX Canvas, participé en los wireframes del prototipo y supervisé la información de la arquitectura, asegurando su correcto diseño.<br>
            </td>
			<td>Al analizar todos los segmentos importantes de un proyecto de este nivel, y recibir todo tipo de retroalimentación, es posible poder fijar la base de lo que se desea del producto y por tanto se logra definir un producto confiable y con las suficientes funcionalidades para solventar la problemática.</td>
		</tr>
		<tr>
			<td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
			<td>
                Bernaola Pérez, André Arturo<br>
                TB1<br>
                Formé parte del avance como equipo, supervisando las actividades de todos y planificando actividades futuras, cumpliendo los objetivos propuestos.<br>
                Grandez Mansilla, Jean Pierre<br>
                TB1<br>
                Incentivé al resto a realizar sus objetivos mientras cumplía con los míos, además de llevar a cabo un seguimiento de las actividades a desarrollar.<br>
                Pacheco Astiguetta, Sebastian<br>
                TB1<br>
                Establecí los objetivos a alcanzar del equipo y supervisé el avance de todos los integrantes.<br>
                Paiva Quispe, Josue Gonzalo<br>
                TB1<br>
                Analicé mis objetivos con el proyecto, realicé las actividades propuestas y asistí en el avance de los objetivos de mis compañeros.<br>
                Velarde Luyo, Piero Alberto<br>
                TB1<br>
                Planifiqué los objetivos que se asignaron, desarrollándolos con eficiencia y respetando las decisiones que mis compañeros realizaron.<br>
            </td>
			<td>Al establecer metas claras y planificar las tareas de manera eficiente, se logra cumplir con los objetivos propuestos y se mantiene un ambiente de trabajo colaborativo e inclusivo, lo que permite alcanzar los objetivos propuestos.</td>
		</tr>
	</tbody>
</table>

## Project Report Collaboration Insights


## Capítulo I: Introducción <a id="cap1"></a>


### 1.1. Startup Profile
En esta seccion presentaremos nuestra start-up, el sector que buscamos incursionar, la soluciona propuesta a la problematica escojida y demas informacion permitente para poder entender la vision del equipo con respecto al proyecto

#### 1.1.1. Descripción de la Startup
En el presente informe presentamos la start-up: “Latte” y la solucion que buscamos desarrollar llamada "Foodsuit" la cual tiene como objetivo ser una aplicación que facilite y organice el flujo de trabajo tanto de empleados como de gerentes en un restaurante u negocio similar. Para ello buscamos ofrecer a los dos sectores de usuario previamente mencionados un espacio donde poder consultar información relevante que necesite de actualización constante, como lo sería el inventario de productos perecibles, el ingreso diario en la caja, el rendimiento laboral, etc.

#### Misión
“Nuestra misión es la de ofrecer una interfaz de trabajo ágil, rápida e intuitiva para los empleados y encargados de un restaurante, con el fin de facilitar la consulta de información, agilizar el ingreso y actualización de datos relevantes de distintas áreas y permitir la consulta de dicha información para todo el equipo de trabajo”

#### Visión
“Nuestra visión es la de apoyar el crecimiento de diversos negocios emergentes y ya establecidos en nuestro país, con el fin de promover el crecimiento económico de pequeños empresarios que buscan incursionar en este sector empresarial”

#### 1.1.2. Perfiles de integrantes del equipo
### 1.2. Solution Profile
Como ya se menciono FoodSuit busca hacer eficiente la logistica de la administracion de un restaurante proporcionando diversas herramientas y caracteristicas que detallamos a continuacion:

- **Registro de inventario de productos perecibles:** Los administradores podran llevar un control del producto almacenado de una manera mas eficiente indicando fechas de caducidad, cantidad, tipo de producto, etc. Ellos podran registrar, modificar y eliminar componentes de este registro, podran consultarlo en el momento que deseen y los dias restantes de caducidad se actualizaran todos los dias en tiempo real

- **Ingreso diario de caja:** En esta seccion el administrador podra registrar su ingreso diario, esta informacion se almancenara en su calendario y podra consultarla, la aplicacion cada semana o mes le mostrara el crecimiento o decrecimiento con respecto a la semana pasada y mes pasado

- **Horario del personal:** El horario le permite al administrador indicar los turnos y horas de trabajo correspondientes a cada empleado con el fin de poder llevar un mejor control de su asistencia y sus horas de trabajo, al final de cada mes se le indicara al administrador cuantas horas trabajo cada empleado, facilitando asi el pago de los mismos
#### 1.2.1 Antecedentes y problemática
#### Uso de la técnica  The 5'W's w Y 2'H's

| LAS 5W y 2H | Pregunta| Descripción|
|-------------|---------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Who?| ¿Quién podria beneficiarse?| Administradores y empleados de restaurantes y similares
|What?| ¿Cuál es el problema?|La complicada logistica detras de un restaurante y lo complicado que resulta consultar rapidamente informacion crucial|
|When?| ¿Cuando sucede?|Algunos problemas de logistica pueden ser cuando se acumula mucho producto sin fechar, llevar la cuenta de las horas de trabajo de un empleado sin un sistema de marcado, etc|
|Where?| ¿Donde aparece el problema?|En el ritmo frenetico de trabajo en un restaurante, pues se presentan situaciones todo el tiempo|
|Why?| ¿Porqué sucede el problema?|Es la naturaleza misma de este tipo de negocio, al ser un sector orientado a la atencion al cliente, siempre surgen situaciones y problematicas|
|How?| ¿Como?|Los negocion no cuentan con herramientas especificas para ellos, mas que las tradicionales pizarras y agendas que suelen acumular mucho registro y son complicadas de consultar|
|How much?| Cuanto?|Segun el INE cerca del 60% de restaurantes cierran en su primer año de vida y el 70% no pasa de los 5 años, estas son estadisticas preocupantes si tomamos en cuenta la gran cantidad de inversion que requiere un negocio de este estilo|
#### 1.2.2 Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
Al momento de gestionar un restaurante, los gerentes o encargados requieren de toda la información posible para poder realizar una óptima administración de los recursos para aumentar la eficiencia del establecimiento. No obstante, durante este proceso existes múltiples datos complejos de tener un seguimiento, los cuales, son vitales para una buena toma de decisiones. 

¿Cómo se puede mejorar la eficiencia de obtención de dichos datos y obtener una claridad para mejorar el desempeño general de un restaurante ?
##### 1.2.2.2. Lean UX Assumptions
**Business Assumptions** 

1. Creo que mis clientes necesitan graficos que simplifiquen la vista de la información vital para la gestión de su estableciemiento.
2. Mis clientes necesitan que sus trabajadores pertenecientes al área de cocina puedan hacer un registro del inventario de la misma.
3. Mis clientes requieren de una alerta que le advierta sobre la escacez de los productos en el inventario de la cocina.
4. El valor primordial que un encargado de restaurante busca de mi servicio es que la información que este le brinda sea confiable e intuitiva.
5. El valor primordial que un trabajador de restaurante busca de mi servicio es su fácil uso y rapidez para que estos puedan agilizar su labor.
6. Se obtendrá dinero desde el momento que la aplicación esté abierta al publico por su modelo de suscripción.
7. Atraeremos a la mayoría de nuestros clientes por medio de publicidads en redes sociales como Facebook, TikTok e Instagram.
8. Mi principal competencia en el mercado serán otras aplicaciones que también se encargan de la gestión de restaurantes.
9. Los venceremos debido a la intuitibidad y eficacia de mostrar la información relevante en nuestra aplicación, lo que le brindará más tiempo aprobechable al encargado del restaurante.
10. Mi mayor riesgo de servicio es la cantidad de información que se necesita almacenar en la base de datos.
11. Resolveremos el riesgo por medio de la implementación de más discos de capacidad, al igual que la optimización en el almacenaje de los datos.

**User Assumptions**

1. ¿Quién es el usuario? Los usuarios son los encargados o gerentes de restaurantes y sus trabajadores.
2. ¿Dónde encaja nuestro servicio? ¿En su trabajo o vida? Nuestro servicio encaja en su trabajo.
3. ¿Qué problemas resuelve nuestro servicio para el usuario? Reduce el esfuerzo y tiempo requerido al momento de administrar un restaurante, brindando con total fácilidad la información necesaria.
4. ¿En qué contexto utiliza el usuario nuestro producto? Nuestro servicio es usado diariamente por el gerente o encargado para monitorizar el desempeño del resturante, al igual que ciertas caracteristicas reservadas para el uso de los empleados.
5. ¿Qué características son importantes para el usuario? Las características que encontramos son de vital importancia para nuestro servicio es que sea fácil de usar, que genere gráfico con respecto a la información primordial para un encargado , sea esta el desempeño de los empleados, el flujo de dinero diaro, entre otros, que brinde alertas automáticas con respecto a los insumos utilizados por el personal de cocina y que permita registrar el horario de ingreso y salida de los empleados.
6. ¿Cómo debe verse nuestro servicio y cómo debe comportarse? Nuestro servicio debe mostrar toda la información del desempeño diario y general del restaurante de forma intuitiva, al igual que ofrecer una claridad de estos datos.

**User Outcomes**

1. El encargado del restaurante desea visualizar con claridad todos los datos respecto a la gestión del establecimiento, con el fin de poder ejercer una mejor toma de decisiones.
2. El encargado del restaurante desea tener la información en tiempo real con respecto al registro del inventario por parte del personal de la cocina, para así poder adquirir los productos faltantes a tiempo y no perjudicar el optimo funcionamiento del establecimiento.
3. El encargado del restaurante desea visualizar un registro del ingreso diario de caja para de esta manera saber el desempeño con respecto a los días o meses anteriores.
4. El personal del restaurante desea que la plataforma tenga una interfaz para el registro de pedidos de los clientes.
5. El personal del restaurante desea que la plataforma registre su horario de ingreso y salida para de esta manera hacer un seguimiento de su tiempo de trabajo.

**Business Outcomes**

1. El encargado del restaurante podrá realizar un mejor trabajo al momento de mejorar el desempeño de su establecimiento si este tiene acceso de fomra sencilla a toda la información necesaria.
2. El encargado del restaurante podrá evaluar el desempeño en lo que respecta a ingresos diarios del restaurante en un amplio rango de tiempo para poder analizar los días en los que más clientes asisten.
3. El encargado del restaurante podrá estar al tanto, en tiempo real, con respecto a los insumos utilizados en la cocina, así como recibir alertas si es que uno de estos empieza a escasear para no perjudicar la labor de sus empleados.
4. El encargado del restaurante podrá hacer un seguimiento sobre la eficiencia de sus empleados en el trabajo, al igual que establecer sus horarios de trabajo y visualizar el cumplimiento de estos mismos.
5. El personal del restaurante podrá aumentar trabajar sin complicación alguna si este mantiene un control diario del inventario de insumos de la cocina.

##### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que conseguiremos una mejora en la eficiencia de la gestión del restaurante si los encargados del restaurante logran visualizar de forma fácil y clara la información indispensable con los gráficos y tablas presentes en la aplicación.

- Creemos que conseguiremos evitar problemas en la elaboración de platillos si el personal encargado de la cocina logra registrar cada insumo que ingresa o es utilizado en la cocina con la opción de registro de inventario.

- Creemos que conseguiremos monitorear el desempeño laboral si los empleados logran agilizar sus tareas con la plataforma de registro de pedidos.

##### 1.2.2.4. Lean UX Canvas
<img src="assets/LeanUXCanvas.png" alt="Lean UX Canvas">

### 1.3. Segmentos objetivo
Hemos identificado dos segmentos distintos de usuarios:

- Administrador: Se trata de usuarios de 25 años o mas, se trata de la persona que cubre el rol de de gerente o encargado del local, tiene que llevar en orden el inventariado, los ingresos, la cantidad de horas de trabajo de cada empleado, etc.

- Empleado: Este usuario puede encargarse de diversas areas del local, como la cocina, la atencion al cliente, caja, etc. Este sector cuenta con 18 años o mas.

## Capítulo II: Requirements Elicitation & Analysis <a id="cap2"></a>

### 2.1. Competidores
Identificamos tres competidores, cuyos productos son similares directamente o indirectamente a lo que nosotros queremos ofrecer.
1. **Restaurant\.pe**: Es un software para restaurantes que optimiza la gestión del restaurante mediante funcionalidades como un menú online, una plataforma para pedidos y emisión de comprobantes, visualizar ventas y stock, facturación electrónica, entre otros. Ofrece una interfaz amigable, es multiplataforma y puede funcionar con o sin conexión a internet.<br>
<img src="assets/logos/Restaurant.pe_logo.png" alt="Logo Restaurant.pe" width="150"><br>

2. **El Tenedor**: Es un software para restaurantes y personas que buscan restaurantes donde comer. La aplicación almacena la carta del restaurante e información pública como reseñas, ubicación, etc. Permite a las personas reservar mesas del restaurante que disponga de esta aplicación para facilitar la atención.<br>
<img src="assets/logos/ElTenedor_logo.png" alt="Logo El Tenedor" width="150"><br>

3. **Rest\.pe**: Es un software para restaurantes que optimiza la gestión del restaurante y capacita a los trabajadores para aumentar la eficacia del entorno laboral. Aparte de las funcionalidades básicas para un restaurante, presenta múltiples funcionalidades como publicidad local, recetarios, cocina smart, entre otros. Este software es customizable por empresa, por lo que se adapta a lo que la empresa desea según contrato.<br>
<img src="assets/logos/Rest.pe_logo.png" alt="Logo Rest.pe" width="150"><br>

#### 2.1.1. Análisis competitivo
<table border="2" style="text-align: center;">
	<tbody>
		<tr >
			<td colspan="6">Competitive Analysis Landscape</td>
		</tr>
		<tr>
			<td colspan="2">¿Por que llevar a cabo este análisis?</td>
			<td colspan="4">El analizar nuestros competidores nos permite identificar qué estrategias debemos usar para poder desarrollar una aplicación que destaque en el mercado, analizando todos los detalles que diferencie nuestro producto de otros.
            </td>
		</tr>
		<tr>
			<td colspan="2"></td>
			<td>FoodSuite</td>
			<td>Restaurant.pe</td>
			<td>El Tenedor</td>
			<td>Rest.pe</td>
		</tr>
		<tr>
			<td rowspan="2">Perfil</td>
			<td>Overview</td>
			<td>Aplicación que ofrece funcionalidades de gestión para diversos áreas de un restaurante, como los pedidos. Permite la realización de actividades diarias en un restaurante que se pueda realizar en un dispositivo móvil o desde una aplicación web.</td>
			<td>Aplicación que optimiza la gestión del restaurante proporcionando una interfaz amigable de pedidos, emisión de comprobantes y visualización de ventas. Presenta un conteo de stock e inventario en tiempo real, además de poder ser manejado desde múltiples dispositivos.</td>
			<td>Aplicación que gestiona las mesas del restaurante de manera sencilla, además de un listado digital de reservas confirmadas. Estas reservas las permite la aplicación sin necesidad de llamar e incluye la opción de pago desde la misma app.</td>
			<td>Aplicación customizada por un equipo para cada empresa cliente, cuyas funcionalidades incluyen una cocina smart, capacitación, estadísticas, búsqueda por voz, recetarios, publicidad local, entre otros.</td>
		</tr>
		<tr>
			<td>Ventaja competitiva ¿Que valor ofrece a los clientes?</td>
			<td>Optimiza la gestión del inventario de restaurantes mediante actualizaciones y alertas en tiempo real, lo que permite a los usuarios mantener el control del stock desde cualquier lugar.</td>
			<td>Proporciona una solución para la gestión de restaurantes, que abarca desde el control de caja y la gestión de productos hasta la facturación electrónica y el delivery.</td>
			<td>Facilita la visibilidad en línea de los restaurantes a través de su plataforma de reservas y descubrimiento, lo que ayuda a atraer nuevos clientes y aumentar las reservas tanto locales como internacionales. </td>
			<td>Ofrece una solución integral y transparente para restaurantes, eliminando sobrecostos al proporcionar un sistema sin sorpresas, que es adaptable tanto para restaurantes pequeños como para cadenas medianas.</td>
		</tr>
		<tr>
			<td rowspan="2">Perfil de Marketing</td>
			<td>Mercado objetivo</td>
			<td>Restaurantes que buscan una solución especializada en la gestión administrativa</td>
			<td>Desde pequeños restaurantes y foodtrucks hasta grandes cadenas de restaurantes</td>
			<td>Restaurantes en Europa y Australia que desean mejorar su visibilidad en línea</td>
			<td>Restaurantes de tamaño mediano a grande que buscan una solución de punto de venta completa y adaptable</td>
		</tr>
		<tr>
			<td>Estrategias de marketing</td>
			<td><ul>
				<li>Optimización de Inventario</li>
				<li>Automatización y Eficiencia</li>
				<li>Informes y Análisis</li>
			</ul></td>
			<td><ul>
				<li>Ahorro de Tiempo y Dinero</li>
				<li>Multiplataforma y Flexibilidad</li>
				<li>Precio Competitivo</li>
			</ul></td>
			<td><ul>
				<li>Promociones y Descuentos</li>
				<li>Visibilidad en Línea</li>
				<li>Reducción de No-Shows</li>
			</ul></td>
			<td><ul>
				<li>Eliminación de Costos Adicionales</li>
				<li>Adaptabilidad y Soporte</li>
				<li>Experiencia y Fiabilidad</li>
			</ul></td>
		</tr>
		<tr>
			<td rowspan="3">Perfil de Producto</td>
			<td>Productos & Servicios</td>
			<td><ul>
				<li>Control y actualización del inventario en tiempo real</li>
				<li>Sincronización de datos entre dispositivos</li>
				<li>Generación de informes detallados</li>
				<li>Automatización de tareas y procesos</li>
			</ul></td>
			<td><ul>
				<li>Control de caja y gestión de productos</li>
				<li>Control de insumos y stock</li>
				<li>Facturación electrónica</li>
				<li>Gestión de pedidos, delivery interno y externo</li>
				<li>Registro de recetas y movimientos entre almacenes</li>
				<li>Operación en línea y fuera de línea</li>
			</ul></td>
			<td><ul>
				<li>Visibilidad en línea para restaurantes a través de una página personalizada</li>
				<li>Sistema de reservas</li>
				<li>Descuentos de hasta el 50% y programa de recompensas</li>
				<li>Herramientas para reducir la inasistencia de clientes</li>
				<li>Capacitación gratuita y soporte continuo</li>
			</ul></td>
			<td><ul>
				<li>Gestión de ventas, delivery interno y externo, y mesas mapeadas</li>
				<li>Carta QR funcional y aplicación/web propia para pedidos</li>
				<li>Facturación electrónica</li>
				<li>Control de inventario, estadísticas de ventas y cierre de caja</li>
				<li>Automatización de procesos</li>
			</ul></td>
		</tr>
		<tr>
			<td>Precios &amp; Costos</td>
			<td><ul>
				<li>Basic: $99</li>
				<li>Pro: $199</li>
				<li>Enterprise: $399</li>
			</ul></td>	
			<td><ul>
				<li>Para crecimiento: $94</li>
				<li>Para total control: $440</li>
			</ul></td>
			<td><ul>
				<li>Basic: $32</li>
				<li>Pro: $57</li>
				<li>Pro+: $113</li>
			</ul></td>	
			<td><ul>
				<li>Básico: $53</li>
				<li>Cadena: $120</li>
				<li>Básico (anual): $534</li>
				<li>Cadena (anual): $1334</li>
			</ul></td>	
		</tr>
		<tr>
			<td>Canales de distribución (Web y/o Móvil)</td>
			<td>Web y móvil</td>
			<td>Web y móvil</td>
			<td>Web y móvil</td>
			<td>Web y móvil</td>
		</tr>
		<tr>
			<td rowspan="4">Análisis SWOT</td>
			<td>Fortalezas</td>
			<td>Se especializa en gestión de inventario, automatización e interfaz intuitiva.</td>
			<td>Presenta una solución integral con una amplia gama de funciones cubriendo todas las áreas clave.</td>
			<td>Proporciona a los restaurantes una plataforma sólida para aumentar su visibilidad.</td>
			<td>Elimina sobrecostos y pagos adicionales, además de adaptarse a restaurantes de cualquier tamaño.</td>
		</tr>
		<tr>
			<td>Debilidades</td>
			<td>Tiene un enfoque limitado con respecto a trabajadores, no puede analizar roles que no necesitan de competencia.</td>
			<td>El costo inicial, aunque sea competitivo, puede ser una limitación para pequeños negocios.</td>
			<td>Su enfoque principal en un continente específico y algunos países puede limitar su alcance.</td>
			<td>Aunque tengan experiencia nacional e internacional, hay una falta de presencia internacional.</td>
		</tr>
		<tr>
			<td>Oportunidades</td>
			<td>Puede encajar fácilmente en el crecimiento de mercados emergentes gracias a la digitalización de la gestión.</td>
			<td>La digitalización de la gestión de restaurantes representa oportunidades para nuevos clientes, y tomó ventaja.</td>
			<td>Colaborar con otras plataformas de gestión de restaurantes ofreciendo una solución más completa.</td>
			<td>El desarrollo de funciones enfocados al análisis avanzado de datos o un marketing digital completo favorecería su crecimiento.</td>
		</tr>
		<tr>
			<td>Amenazas</td>
			<td>Podría perder mercado frente a software que presente una solución más completa y con más funciones.</td>
			<td>Tiene mucha dependencia tecnológica, y su servicio al cliente es limitado, por lo que genera desconfianza.</td>
			<td>Soluciones como éste tiene mucha competencia en el mercado, dificultando su dominio en el mismo.</td>
			<td>La saturación del mercado con respecto a competencia en soluciones de punto de venta puede limitar su crecimiento.</td>
		</tr>
	</tbody>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores.
Para destacar frente a los competidores, debemos establecer estrategias y tácticas que diferencie nuestro producto de otros. 
1. **Propuesta de Valor Único**:
* Estrategia: Diferenciación mediante una solución de gestión avanzado y específico.
* Táctica: Desarrollar y promover las estrategias de marketing que nuestro producto proporciona
2. **Experiencia del Usuario**:
* Estrategia: Enfoque en una interfaz de usuario intuitiva y un flujo de trabajo eficiente.
* Táctica: Implementar un soporte al cliente en la plataforma para resolver dudas.
3. **Ampliación de Base de Usuarios**
* Estrategia: Expandir la presencia en mercados emergentes y pequeños negocios.
* Táctica: Presentar un producto demo que permita a los usuarios poder experimentar con lo que ofrecemos.
4. **Marketing Digital Dirigido**
* Estrategia: Enfocar en la segmentación precisa dirigidas al marketing digital.
* Táctica: Utilizar estrategias de contenido público como redes sociales para promocionar a usuarios nuestro producto.
5. **Colaboraciones Estratégicas**
* Estrategia: Formar alianzas con empresas de mercado más relevantes para los restaurantes.
* Táctica: Colaborar con centros de suministros que proporcionen su contacto para que el usuario pueda tener contactos según su distrito.
### 2.2. Entrevistas
Las entrevistas siguientes nos sirven para conocer lo que los clientes esperan de un producto, qué experiencias tuvieron con productos similares y qué tipo de decisiones nosotros tenemos que tomar. Al analizar estas entrevistas, nosotros tendremos una idea de cómo desarrollar nuestro producto de manera que ésta se adapte a lo que el cliente desea.
#### 2.2.1. Diseño de entrevistas
El diseño de las entrevistas va acorde a la información que nosotros queremos conocer acerca de las experiencias y necesidades que nuestros grupos objetivos nos proporcionarán. Se han desarrollado preguntas para ambos grupos objetivos:
* **Administrador de restaurante**
1. Como administrador, ¿Qué papel desempeñas en la administración del restaurante? ¿Qué tipo de actividades debes desarrollar día a día?
2. ¿Cómo se organizan ustedes, administradores y trabajadores, en el restaurante?
3. ¿Has tenido problemas relacionados con el método de organización que mencionaste? ¿Qué tipo de soluciones deben llevar a cabo?
4. Aparte de la organización mencionada, ¿qué otros problemas has tenido que enfrentar?
5. ¿Tienen algún sistema que registre toda información relacionada con los aspectos de relaciones humanas, finanzas y productividad en general? ¿Llegó a ser lo que buscaban?
6. Acorde al tema de relaciones humanas, ¿qué pensarían de un sistema que permita a los trabajadores desde el móvil registrar las mesas que ha atendido y/o registrar los platos de una manera más eficiente?
7. Acorde al tema de finanzas, ¿qué pensarían de un sistema que pueda almacenar en un solo lugar (y de manera organizada) todos los reportes de inventario y gastos/ganancias que el negocio obtiene, además de generar estadísticas para una comparación sencilla?
8. Acorde al tema de productividad, ¿qué pensarían de un sistema que pueda mostrar gráficos mensuales conteniendo una comparación de productividad de un trabajador con fechas anteriores?
9. Si la aplicación presentara estadísticas, por ejemplo, cuándo se compra más un plato en el mes, ¿cómo crees que eso pueda ayudar? ¿Cambiarías el funcionamiento de la carta para beneficiar el negocio?
10. ¿Qué otras funcionalidades, muy aparte de los temas mencionados, quisieras que tuviera la aplicación?
11. Si esta aplicación tuviera todas estas funcionalidades, ¿sería suficiente para cambiar el sistema actual que el negocio usa?
12. ¿Cómo crees que los trabajadores reaccionarían ante un nuevo sistema?
* **Trabajador**
1. Como trabajador, ¿Qué actividades debes realizar en el restaurante?
2. ¿Tienen un sistema que ustedes usen para poder manejar pedidos, asistencia o similares?
3. Sea aplicación o manual la respuesta, ¿qué tan satisfecho te encuentras? ¿Estarías de acuerdo con que hubiera un cambio de sistema?
4. ¿Qué consideras que es importante que una aplicación de gestión de restaurante tenga para los trabajadores?
5. ¿Qué pensarías de una aplicación que te permitiera acceder a un sistema de pedidos y poder ingresar productos de la carta con mayor eficiencia?
6. ¿Qué pensarías de una aplicación que pueda calcular tu rendimiento laboral semanal y así poder insertar un sistema de recompensa si mantienes ese rendimiento alto?
7. Si la aplicación tuviera las funcionalidades mencionadas, ¿cómo crees que mejoraría tu rendimiento laboral? ¿Sería más eficiente?
#### 2.2.2. Registro de entrevistas.
Registramos las entrevistas para recopilar y organizar la información que se nos ha proporcionado. Gracias a las entrevistas a los grupos objetivos, podremos analizar y recalcar las necesidades que el cliente espera que la aplicación cumpla.<br>
Link a las entrevistas: https://tinyurl.com/55rja6hb<br>
*Las imágenes de las entrevistas pueden redireccionar al timestamp indicado.*
#### Administrador
* **Entrevista 1** <br>
Nombre completo: Verónica Astiguetta<br>
Edad: 54 años<br>
Papel desempeñado: Tesorera<br>
Empresa: Bodega Queirolo S.A.C.<br>
Distrito: Centro de Lima<br><br>
**Detalles de la entrevista:** <br><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202110291_upc_edu_pe/EZ1hZ887ju9Ag-fvFRRxixsBBGySTT6oBEr-g8O-PN9Ftw?e=51tnB6&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MjguMDl9fQ%3D%3D">
	<img src="assets/VeronicaEntrevista.png" alt="Entrevista 1" width="500"></a><br>
Inicio de la entrevista: 0:28<br>
Fin de la entrevista: 13:09<br>
**Transcripción resumen de entrevista:**<br>
Expresa satisfacción con una organización regulada mediante un sistema, ya que describe que cuando era manual hubo complicaciones. Indica que el sistema actual que usan les ayuda mucho en las actividades básica de la empresa; sin embargo, hay demasiadas funciones que no sacan el provecho máximo del sistema debido a falta de tiempo o son innecesarios. Muestra interés por permitir a los trabajadores usar sus dispositivos en vez de usar un solo dispositivo el cual sería el sistema principal, lo cual consideraría uno de los problemas de este sistema. Muestra interés por lograr almacenar todos los documentos relacionados a las finanzas en un solo lugar, en especial una página web donde pueda acceder desde cualquier lado. Muestra interés por aumentar la productividad de los trabajadores mediante un sistema de cálculo de rendimiento y por tanto establecer una competencia como motivación. Ve importante utilizar las estadísticas de platos más vendidos en cierta temporada para ajustar la carta. Ve posible el cambio de sistema, pues opina que las características proporcionadas son buenas para el negocio.

* **Entrevista 2**
Nombre completo: Iván Pacheco<br>
Edad: 53 años<br>
Papel desempeñado: Administración general<br>
Empresa: Bodega Queirolo S.A.C.<br>
Distrito: Centro de Lima<br><br>
**Detalles de la entrevista:** <br><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202110291_upc_edu_pe/EZ1hZ887ju9Ag-fvFRRxixsB9Vt7BVp_S8q5iqMpo1n9MQ?e=6YqTRa&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6ODE1LjMxfX0%3D">
	<img src="assets/IvanEntrevista.png" alt="Entrevista 2" width="500"></a><br>
Inicio de la entrevista: 13:35<br>
Fin de la entrevista: 53:43<br>
**Transcripción resumen de entrevista:**<br>
Opina que la estructura actual que tiene el negocio es adecuado y todos respetan los roles, pero hubo problemas con trabajadores nuevos. El sistema que utiliza el negocio respeta estos roles: solo la administración utiliza esta aplicación, mientras que los trabajadores aún dependen de ciertos elementos materiales. Expresa satisfacción con el sistema actual, ya que cumple con los requisitos que la empresa exige que la aplicación tenga; sin embargo, hay varios problemas que experimenta con la aplicación. Se muestra indiferente con respecto a permitir a los trabajadores usar dispositivos para facilitar su labor, ya que es más eficiente usar el método del papel para recibir los pedidos, pero si el dispositivo logra ser eficiente para ahorrar tiempo, ve útil la funcionalidad propuesta. Ve conveniente que el sistema pueda manejar los reportes financieros desde la misma aplicación web. No ve necesario utilizar estadísticas para calcular el reporte de trabajadores, ya que es más verificable el observar al trabajador en comparación con otro durante el periodo laboral en comparación a depender de un sistema. Muestra totalmente útil la funcionalidad de mostrar estadísticas de, por ejemplo, los platos más vendidos, ya que podrá priorizar la salida de platos más pedidos y acelerar el servicio. Ve posible el cambio de sistema, pero tiene expectativas con respecto a que el sistema no caiga, sea fácil de usar, sea cómodo y el proveedor de servicio de atención tenga disponibilidad de tiempo larga (comparando con su sistema actual, que tiene estas desventajas).

* **Entrevista 3**
Nombre completo: Eduardo Ventura<br>
Edad: 20<br>
Papel desempeñado: Tesorero<br>
Empresa: Emotiv<br>
Distrito: San Juan de Gaucho<br><br>
**Detalles de la entrevista:** <br><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202110291_upc_edu_pe/EZ1hZ887ju9Ag-fvFRRxixsBBGySTT6oBEr-g8O-PN9Ftw?e=FWZ6fA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MzI2MS40Mn19">
	<img src="assets/EduardoEntrevista.png" alt="Entrevista 3" width="500"></a><br>
Inicio de la entrevista: 54:21<br>
Fin de la entrevista: 1:04:49<br>
**Transcripción resumen de entrevista:**<br>
Expresa satisfacción con una organización regulada mediante un sistema, ya que describe que cuando era manual no era tan eficiente manejar papeles. A pesar de que el sistema que usa para manejar las finanzas es Excel, opina que la herramienta es suficiente para cumplir sus trabajos. Muestra interés por permitir a los trabajadores disponer de un sistema que les ayuda a realizar su labor de manera más rápida y que almacene pedidos para que él mismo pueda dar apoyo si hay muchas personas. Ve bien un sistema que almacene los reportes financieros, aunque el excel le satisface suficiente. No muestra tanto interés, pero le parece bien poder visualizar el rendimiento de los trabajadores mediante estadísticas. No muestra tanto interés, pero ve útil utilizar las estadísticas de platos más vendidos en cierta temporada para deshacerse de platos que no venden. Ve posible el cambio de sistema, pues opina que tener varias funciones automatizadas puede beneficiar al negocio.

#### Trabajador
* **Entrevista 4**
Nombre completo: Janaira Toledo<br>
Edad: 22<br>
Papel desempeñado: Cajera<br>
Distrito: San Miguel<br><br>
**Detalles de la entrevista:** <br><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202110291_upc_edu_pe/EZ1hZ887ju9Ag-fvFRRxixsBBGySTT6oBEr-g8O-PN9Ftw?e=OKfD05&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6Mzg5OS43fX0%3D">
	<img src="assets/JanairaEntrevista.png" alt="Entrevista 4" width="300"></a><br>
Inicio de la entrevista: 1:04:59<br>
Fin de la entrevista: 1:06:59<br>
**Transcripción resumen de entrevista:**<br>
Prefiere que el restaurante tenga un nuevo sistema, ya que el actual presenta muchas fallas con respecto a asistencia y otros. Le parece buena idea el introducir un sistema que les permita registrar los pedidos desde sus dispositivos. Piensa que sería beneficioso un sistema que calcule el rendimiento de los trabajadores para impulsar el esfuerzo laboral que cada uno proporciona.

* **Entrevista 5**
Nombre completo: Fabricio Sánchez<br>
Edad: 20<br>
Papel desempeñado: Cocinero/Mozo<br>
Distrito: Chorrillos<br><br>
**Detalles de la entrevista:** <br><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202110291_upc_edu_pe/EZ1hZ887ju9Ag-fvFRRxixsBBGySTT6oBEr-g8O-PN9Ftw?e=GC0CnC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6NDAzMC4zM319">
	<img src="assets/FabricioEntrevista.png" alt="Entrevista 5" width="500"></a><br>
Inicio de la entrevista: 1:07:10<br>
Fin de la entrevista: 1:09:56<br>
**Transcripción resumen de entrevista:**<br>
Se encuentra satisfecho con el sistema actual que usa la empresa, aunque suele ser lento en cuanto al rendimiento. Quiere que la aplicación sea rápida y permita a los trabajadores poder registrar los pedidos y ver el rendimiento laboral semanal. Le parece motivador tener funciones como ésta para que pueda desempeñar mejor ya que facilita la comunicación de los trabajadores.

* **Entrevista 6**
Nombre completo: Gonzalo Velarde<br>
Edad: 20<br>
Papel desempeñado: Cocinero/Mozo<br>
Distrito: Pueblo Libre<br><br>
**Detalles de la entrevista:** <br><a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202110291_upc_edu_pe/EZ1hZ887ju9Ag-fvFRRxixsBBGySTT6oBEr-g8O-PN9Ftw?e=CVrdRi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6NDIzMC40NX19">
	<img src="assets/GonzaloEntrevista.png" alt="Entrevista 6" width="500"></a><br>
Inicio de la entrevista: 1:10:30<br>
Fin de la entrevista: 1:09:56<br>
**Transcripción resumen de entrevista:**<br>
El sistema actual que el restaurante usa no es sencillo para principiantes, tuvo que acostumbrarse al sistema y piensa que puede mejorar en algunos aspectos. Sugiere que lo mejor que puede tener la aplicación es una sección donde vea en qué puede mejorar. Se enfoca en el sector de atención al cliente, las sugerencias que se proporcionaron como el cálculo del rendimiento laboral y similares puede incentivar a los trabajadores a ser reconocidos por su esfuerzo y por tanto ser premiados.

#### 2.2.3. Análisis de entrevistas
Al analizar las entrevistas, podemos comprender las expectativas y necesidades que los usuarios piden, además de recibir feedback en cuanto a cómo debería ser su producto ideal. Con esto, recurriremos a la toma de decisiones para el desarrollo del producto.
#### **Administrador**
<img src="assets/piecharts/Analysis1.png" alt="analysis1"><br>
<img src="assets/piecharts/Analysis2.png" alt="analysis2"><br>
<img src="assets/piecharts/Analysis3.png" alt="analysis3"><br>
<img src="assets/piecharts/Analysis4.png" alt="analysis4"><br>
<img src="assets/piecharts/Analysis5.png" alt="analysis5"><br>
<img src="assets/piecharts/Analysis6.png" alt="analysis6"><br>

#### **Trabajador**
<img src="assets/piecharts/Analysis7.png" alt="analysis7"><br>
<img src="assets/piecharts/Analysis8.png" alt="analysis8"><br>
<img src="assets/piecharts/Analysis9.png" alt="analysis9">

### 2.3. Needfinding
#### 2.3.1. User Personas

### User Persona Segmento Administrador
<img src="assets/Eduardo Ventura.png" alt="UserPersona Eduardo" width="800"></a><br>
<br>
### User Persona Segmento Trabajador
<img src="assets/Laura Martinez.png" alt="UserPersona Laura" width="800"></a><br>

#### 2.3.2. User Task Matrix
En esta sección se presentará el User Task Matrix, una herramienta que permite identificar las tareas más relevantes para cada segmento, así como la frecuencia e importancia de cada una de ellas.

<table>
  <tr>
    <th rowspan="2" valign="top"><b><i>User Task Matrix</i></b></th>
    <th colspan="2" valign="top"><b><i>Eduardo</i></b></th>
    <th colspan="2" valign="top"><b><i>Laura Martínez</i></b></th>
  </tr>
  <tr>
    <td valign="top"><b><i>Frecuencia</i></b></td>
    <td valign="top"><b><i>Importancia</i></b></td>
    <td valign="top"><b><i>Frecuencia</i></b></td>
    <td valign="top"><b><i>Importancia</i></b></td>
  </tr>
  <tr>
    <td>Registrar boletas y facturas</td>
    <td><b><i>Siempre</i></b></td>
    <td><b><i>Alta</i></b></td>
    <td><b><i>Nunca</i></b></td>
    <td><b><i>Baja</i></b></td>
  </tr>
  <tr>
    <td>Optimización de procesos internos</td>
    <td><b><i>A menudo</i></b></td>
    <td><b><i>Alta</i></b></td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Medio</i></b></td>
  </tr>
  <tr>
    <td>Supervisión de flujo de ingresos y egresos</td>
    <td><b><i>Siempre</i></b></td>
    <td><b><i>Alta</i></b></td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
  <tr>
    <td>Adopción de nuevas tecnologías para la gestión</td>
    <td><b><i>A menudo</i></b></td>
    <td><b><i>Alta</i></b></td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
  <tr>
    <td>Coordinación con el equipo de operaciones</td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Medio</i></b></td>
    <td><b><i>Siempre</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
  <tr>
    <td>Atención al cliente</td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Medio</i></b></td>
    <td><b><i>Siempre</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
  <tr>
    <td>Programación de servicios</td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Medio</i></b></td>
    <td><b><i>A menudo</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
  <tr>
    <td>Manejo de pedidos</td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Medio</i></b></td>
    <td><b><i>Siempre</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
  <tr>
    <td>Resolución de problemas operativos</td>
    <td><b><i>A menudo</i></b></td>
    <td><b><i>Alta</i></b></td>
    <td><b><i>Siempre</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
  <tr>
    <td>Seguimiento de la satisfacción del cliente</td>
    <td><b><i>A veces</i></b></td>
    <td><b><i>Medio</i></b></td>
    <td><b><i>Siempre</i></b></td>
    <td><b><i>Alta</i></b></td>
  </tr>
</table>

### Explicación de la User Task Matrix

- **Registrar boletas y facturas**: Eduardo lo hace siempre y es de alta importancia, ya que mediante a esto mantiene un flujo de caja organizado.
- **Optimización de procesos internos**: Eduardo lo hace a menudo y es de alta importancia, ya que busca mejorar la eficiencia de su empresa.
- **Supervisión de flujo de ingresos y egresos**: Eduardo lo hace siempre y es de alta importancia, ya que necesita tener un control de sus finanzas.
- **Adopción de nuevas tecnologías para la gestión**: Eduardo lo hace a menudo y es de alta importancia, ya que busca mejorar la eficiencia de su empresa.
- **Coordinación con el equipo de operaciones**: Laura lo hace siempre y es de alta importancia, ya que día a día necesita coordinarse con su equipo.
- **Atención al cliente**: Laura lo hace siempre y es de alta importancia, ya que necesita mantener una buena relación con sus clientes.
- **Programación de servicios**: Laura lo hace a menudo y es de alta importancia, y con esto mantiene un orden en su día de trabajo.
- **Manejo de pedidos**: Laura lo hace siempre y es de alta importancia, ya que necesita mantener un control de los pedidos.
- **Resolución de problemas operativos**: Laura lo hace siempre y es de alta importancia, ya que debe saber resolver estos casos con efectividad y rapidez para la
  satisfacción de los clientes.

#### 2.3.3. User Journey Mapping
Mediante los User Journey Maps, se representa la situación (AS-Is) de la experiencia de los usuarios al interactuar desde la creación hasta la finalización
del proyecto de gestión interna de un restaurante. Estos mapas permiten visualizar los puntos de contacto,
emociones y acciones de los usuarios a lo largo de su recorrido, identificando oportunidades de mejora y optimización.

#### **User Journey Map Administrador**
<img src="assets/Eduardo%20Journey%20Map.png" alt="UserJourneyMap Eduardo" width="800"><br>
#### ** User Journey Map Trabajador**

<img src="assets/Laura%20Martinez%20Journey%20map.png" alt="UserJourneyMap Laura"><br>
#### 2.3.4. Empathy Mapping

- Empathy Map Administrador
<img src="assets/Empathy map Admin.png" alt="EmpathyMap Eduardo" width="800"><br>

- Empathy Map Trabajador
<img src="assets/Empathy map Laura.png" alt="EmpathyMap Laura"><br>


#### 2.3.5. As-is Scenario Mapping

**As-Is Scenario Mapping Administrador**
#### Preparación de la actividad
Graficamos el cuadro y lo dividimos en fases: Steps, Doing, Thinking y Feeling
<br>
<img src="assets/As-Is inicio.png" alt="As-is inicio"><br>
#### Brainstorming
 Luego de la lluvia de ideas, se obtuvo el siguiente resultado:
<img src="assets/As-Is brain.png" alt="Brainstorming Administradores"><br>
#### As-Is Scenario Mapping Administrador
Luego de organizar las ideas e identificar las fases, se obtuvo el siguiente resultado:
<img src="assets/As-Is admin.png" alt="As-Is Admin completo"><br>

**As-Is Scenario Mapping Trabajador**
#### Preparación de la actividad
Graficamos el cuadro y lo dividimos en fases: Steps, Doing, Thinking y Feeling
<br><img src="assets/As-Is inicio.png" alt="As-is inicio"><br>
#### Brainstorming
Luego de la lluvia de ideas, se obtuvo el siguiente resultado:
<img src="assets/As-Is brainT.png" alt="Brainstorming Trabajador"><br>
#### As-Is Scenario Mapping Administrador
Luego de organizar las ideas e identificar las fases, se obtuvo el siguiente resultado:
<img src="assets/As-Is trabajador.png" alt="As-Is Trabajador completo"><br>
### 2.4. Ubiquitous Language

En esta sección se presentará el lenguaje ubicuo, una herramienta que permite establecer un vocabulario común y preciso para la comunicación entre los miembros del equipo de desarrollo y los stakeholders.
Este lenguaje facilita la comprensión y el consenso en torno a los conceptos y términos clave del proyecto.

- **Admin:** Usuario que tiene acceso a la gestión de la empresa.
- **Trabajador:** Usuario que tiene acceso a la gestión de los pedidos.
- **Gestión:** Acción de administrar y organizar los recursos de la empresa.
- **Pedidos:** Solicitud de un cliente para adquirir un producto o servicio.
- **Facturas:** Documento que detalla la venta de un producto o servicio.
- **Boletas:** Documento que detalla la venta de un producto o servicio.
- **Ingresos:** Dinero que entra a la empresa.
- **Egresos:** Dinero que sale de la empresa.
- **Clientes:** Personas que adquieren productos o servicios de la empresa.

## Capítulo III: Requirements Specification <a id="cap3"></a>

### 3.1. To-Be Scenario Mapping

**To-Be Scenario Mapping Administrador**

#### Preparación de la actividad
Graficamos el cuadro y lo dividimos en fases: Steps, Doing, Thinking y Feeling
<br>
<img src="assets/As-Is inicio.png" alt="Inicio del To-be scenario map"> <br>

#### Brainstorming
Luego de la lluvia de ideas, se obtuvo el siguiente resultado:
<img src="assets/tobe-brain.png" alt="Brainstorming Administrador"><br>

#### To-Be Scenario Mapping Administrador
Luego de organizar las ideas e identificar las fases, se obtuvo el siguiente resultado:

<img src="assets/tobe.png" alt="To-Be Scenario Map Admin completo"><br>

**To-Be Scenario Mapping Trabajador**

#### Preparación de la actividad
Graficamos el cuadro y lo dividimos en fases: Steps, Doing, Thinking y Feeling
<br>
<img src="assets/As-Is inicio.png" alt="Inicio del To-be scenario map"> <br>

#### Brainstorming
Luego de la lluvia de ideas, se obtuvo el siguiente resultado:
<img src="assets/tobe-braint.png" alt="Brainstorming Trabajador"><br>

#### To-Be Scenario Mapping Trabajador
Luego de organizar las ideas e identificar las fases, se obtuvo el siguiente resultado:
<img src="assets/tobe-trabajador.png" alt="To-Be Scenario map Trabajador completo"><br>

### 3.2. User stories

###### User Epics

| Epic ID | Título                              | Descripción                                                                                       |
|---------|-------------------------------------|---------------------------------------------------------------------------------------------------|
| EP001   | Optimización del Registro y Control de Finanzas | Implementar un sistema automatizado para registrar y controlar las finanzas del restaurante, incluyendo pedidos, gastos, e informes financieros. |
| EP002   | Mejora en la Gestión de Pedidos y Asistencia | Desarrollar una solución para registrar pedidos desde dispositivos móviles, marcar horas de trabajo y calcular automáticamente las horas trabajadas. |
| EP003   | Análisis y Optimización del Desempeño del Restaurante | Proporcionar herramientas para analizar la productividad del personal, ventas de platos y optimización del menú basada en datos. |
| EP004   | Gestión de Recursos                  | Facilitar la organización y disponibilidad de los recursos necesarios para el funcionamiento del restaurante, incluyendo inventario, asistencia, turnos y administración de mesas. |
| EP005   | Optimización y Adaptación Técnica de la Landing Page | Optimizar y adaptar la landing page para mejorar el rendimiento, la accesibilidad y la experiencia del usuario. |
| EP006   | Implementación de la Landing Page | Diseñar y desarrollar una landing page efectiva, que permita a los visitantes entender claramente el producto, sus características y beneficios, y facilite la conversión de visitantes en clientes potenciales |

<br>

###### User Stories for Administrators

| Epic / Story ID | Título                              | Descripción                                                                                                          | Criterios de Aceptación                                                                                                          | Epic ID |
|-----------------|-------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| US-01           | Registro Automático de Pedidos en un Historial | Como administrador, quiero registrar automáticamente los pedidos en un historial, para analizar los datos posteriormente. | **Escenario 1: Registro exitoso**<br>**Dado** que se realiza un pedido<br>**Cuando** se ingresa al sistema<br>**Entonces** el pedido se guarda automáticamente en el historial de pedidos.<br>**Escenario 2: Registro fallido**<br>**Dado** que ocurre un error en el sistema<br>**Cuando** se ingresa un pedido<br>**Entonces** el sistema informa que el registro ha fallado y no se guarda el pedido. | EP001                    |
| US-02           | Alerta de Recursos Bajos            | Como administrador, quiero recibir alertas cuando los recursos estén bajos para asegurar una reposición oportuna.      | **Escenario 1: Alerta generada**<br>**Dado** que un recurso alcanza la cantidad mínima<br>**Cuando** se revisa el inventario<br>**Entonces** se envía una alerta sobre las cantidades bajas del recurso.<br>**Escenario 2: Sin alerta**<br>**Dado** que el recurso está por encima de la cantidad mínima<br>**Cuando** se revisa el inventario<br>**Entonces** no se envía ninguna alerta. | EP001                    |
| US-03           | Generación de Reportes Financieros  | Como administrador, quiero generar reportes de finanzas para analizar el desempeño del restaurante.                    | **Escenario 1: Reporte de ingresos**<br>**Dado** que se solicita un reporte de ingresos<br>**Cuando** se genera el reporte<br>**Entonces** se muestra un informe detallado de los ingresos.<br>**Escenario 2: Reporte de gastos**<br>**Dado** que se solicita un reporte de gastos<br>**Cuando** se genera el reporte<br>**Entonces** se muestra un informe detallado de los gastos. | EP001                    |
| US-04           | Registro de Gastos e Imprevistos    | Como administrador, quiero registrar los gastos imprevistos para tener un control exhaustivo de los gastos del restaurante. | **Escenario 1: Registro de gasto imprevisto**<br>**Dado** que ocurre un gasto imprevisto<br>**Cuando** se ingresa el gasto al sistema<br>**Entonces** el gasto se registra correctamente en la categoría adecuada.<br>**Escenario 2: Clasificación de gasto**<br>**Dado** que se registra un gasto imprevisto<br>**Cuando** se ingresa el gasto<br>**Entonces** el sistema clasifica el gasto según la categoría correspondiente. | EP001                    |
| US-05           | Registro de Costos de Platos        | Como administrador, quiero registrar el costo de cada plato para calcular las ganancias netas diarias.                  | **Escenario 1: Registro de costo**<br>**Dado** que se registra el costo de un nuevo plato<br>**Cuando** se ingresa el costo<br>**Entonces** el sistema muestra el costo total del plato.<br>**Escenario 2: Actualización de costo**<br>**Dado** que se actualiza el costo de un plato existente<br>**Cuando** se ingresan los nuevos costos<br>**Entonces** el sistema recalcula y muestra las ganancias netas actualizadas. | EP001                    |
| US-09           | Visualización de Productividad      | Como administrador, quiero visualizar gráficos de productividad para evaluar el rendimiento de los empleados.                | **Escenario 1: Visualización correcta**<br>**Dado** que se solicita la visualización de gráficos de productividad<br>**Cuando** se accede a los gráficos<br>**Entonces** se muestran las estadísticas actualizadas de productividad.<br>**Escenario 2: Datos insuficientes**<br>**Dado** que no hay suficientes datos<br>**Cuando** se accede a los gráficos<br>**Entonces** se muestra un mensaje indicando que los datos son insuficientes para generar el gráfico. | EP003                    |
| US-10           | Comparación de Productividad        | Como administrador, quiero comparar la productividad del personal entre diferentes períodos para identificar mejoras.        | **Escenario 1: Comparación entre períodos**<br>**Dado** que se seleccionan diferentes períodos para comparación<br>**Cuando** se realiza la comparación<br>**Entonces** se muestran las diferencias de productividad entre los períodos.<br>**Escenario 2: Falta de datos para comparación**<br>**Dado** que no hay datos para algunos períodos<br>**Cuando** se intenta realizar la comparación<br>**Entonces** el sistema muestra un mensaje indicando que faltan datos para algunos períodos. | EP003                    |
| US-11           | Informe de Ventas de Platos         | Como administrador, quiero recibir informes sobre los platos más y menos vendidos para ajustar el menú.                         | **Escenario 1: Informe de platos más vendidos**<br>**Dado** que se solicita un informe de ventas<br>**Cuando** se genera el informe<br>**Entonces** se muestra una lista de los platos más vendidos.<br>**Escenario 2: Informe de platos menos vendidos**<br>**Dado** que se solicita un informe de ventas<br>**Cuando** se genera el informe<br>**Entonces** se muestra una lista de los platos menos vendidos. | EP003                    |
| US-12           | Optimización del Menú               | Como administrador, quiero recibir sugerencias basadas en datos de ventas para optimizar la carta del restaurante.      | **Escenario 1: Sugerencias basadas en datos**<br>**Dado** que se analizan los datos de ventas<br>**Cuando** se generan sugerencias<br>**Entonces** se presentan recomendaciones para mejorar la carta.<br>**Escenario 2: Ajuste de la carta según sugerencias**<br>**Dado** que se reciben sugerencias de optimización<br>**Cuando** se ajusta la carta<br>**Entonces** se actualiza la oferta de platos en el menú según las recomendaciones. | EP003                    |
| US-13           | Registro de Inventario              | Como administrador, quiero registrar y actualizar el inventario para asegurar disponibilidad de insumos.               | **Escenario 1: Registro de nuevo inventario**<br>**Dado** que se ingresa nuevo inventario<br>**Cuando** se actualiza el registro<br>**Entonces** el sistema refleja los cambios en tiempo real.<br>**Escenario 2: Actualización de inventario existente**<br>**Dado** que se actualiza el inventario existente<br>**Cuando** se ingresan los nuevos datos<br>**Entonces** el sistema muestra la información actualizada correctamente. | EP004                    |
| US-14           | Gestión de Asistencia               | Como administrador, quiero monitorear la asistencia del personal para identificar patrones y tomar decisiones.         | **Escenario 1: Monitoreo de asistencia**<br>**Dado** que se accede al módulo de asistencia<br>**Cuando** se consulta la asistencia de un empleado<br>**Entonces** se muestran los registros de ausencias y tardanzas.<br>**Escenario 2: Consulta en tiempo real**<br>**Dado** que se revisa la asistencia en tiempo real<br>**Cuando** se accede a la información<br>**Entonces** se muestra la asistencia actual del personal. | EP004                    |
| US-15           | Programación de Turnos              | Como administrador, quiero programar y modificar los turnos del personal para asegurar una cobertura adecuada.         | **Escenario 1: Programación de nuevo turno**<br>**Dado** que se accede a la programación de turnos<br>**Cuando** se asigna un nuevo turno<br>**Entonces** la programación se actualiza y se notifica al empleado.<br>**Escenario 2: Modificación de turno existente**<br>**Dado** que se accede a la programación de turnos<br>**Cuando** se modifica un turno existente<br>**Entonces** el sistema actualiza la programación y notifica al empleado. | EP004                    |
| US-16           | Optimización de la Carta de Platos  | Como administrador, quiero optimizar la carta de platos según la demanda histórica para mejorar la oferta del restaurante. | **Escenario 1: Optimización basada en ventas**<br>**Dado** que se analizan las estadísticas de ventas<br>**Cuando** se generan recomendaciones<br>**Entonces** se presenta una carta personalizada para días específicos.<br>**Escenario 2: Ajuste del menú según demanda**<br>**Dado** que se revisan los datos de ventas<br>**Cuando** se actualiza la carta<br>**Entonces** el menú refleja los platos más demandados. | EP004                    |
| US-17           | Administración de Mesas             | Como administrador, quiero gestionar la asignación de mesas para maximizar la eficiencia en la atención al cliente.    | **Escenario 1: Asignación de mesa**<br>**Dado** que se accede a la administración de mesas<br>**Cuando** se asigna una mesa a un cliente<br>**Entonces** la disponibilidad de mesas se actualiza en tiempo real.<br>**Escenario 2: Reasignación de mesa**<br>**Dado** que se necesita reasignar una mesa<br>**Cuando** se asigna la mesa a un nuevo cliente<br>**Entonces** se actualiza la disponibilidad de mesas adecuadamente. | EP004                    |
| US-18           | Presentación del Producto           | Como visitante, quiero ver una presentación clara del producto de administración de restaurantes en la landing page para entender sus características y beneficios. | **Escenario 1: Presentación visible**<br>Dado que accede a la landing page<br>Cuando visita la sección de presentación<br>Entonces se muestra un resumen detallado del producto y sus características.<br>**Escenario 2: Presentación incompleta**<br>Dado que hay un problema con la carga de contenido<br>Cuando visita la sección de presentación<br>Entonces se muestra un mensaje de error. | EP006                      |
| US-19           | Características Principales         | Como visitante, quiero ver las características principales del producto en la landing page para evaluar si cumple con mis necesidades.                         | **Escenario 1: Características visibles**<br>Dado que accede a la landing page<br>Cuando visita la sección de características<br>Entonces se muestran las características principales del producto.<br>**Escenario 2: Características no disponibles**<br>Dado que el contenido de características no se carga<br>Cuando visita la sección<br>Entonces se muestra un mensaje indicando que el contenido está temporalmente no disponible. | EP006                      |
| US-20           | Llamada a la Acción                 | Como visitante, quiero encontrar botones de llamada a la acción (CTA) para solicitar una demo o contactar con el equipo de ventas fácilmente.                 | **Escenario 1: CTA visible**<br>Dado que accede a la landing page<br>Cuando visita la página<br>Entonces se deben mostrar botones de solicitud de demo y contacto en ubicaciones prominentes.<br>**Escenario 2: CTA no funcional**<br>Dado que un botón de CTA no funciona<br>Cuando intenta usar el botón<br>Entonces el sistema muestra un mensaje de error o no realiza la acción esperada. | EP006                      |
| US-21           | Accesibilidad en Dispositivos Móviles | Como visitante, quiero que la landing page sea accesible y funcional en dispositivos móviles para asegurarme de que puedo navegar y acceder a la información correctamente. | **Escenario 1: Accesibilidad correcta**<br>Dado que accede a la landing page desde un dispositivo móvil<br>Cuando navega por la página<br>Entonces el contenido debe ser accesible y funcional.<br>**Escenario 2: Accesibilidad limitada**<br>Dado que hay problemas con la accesibilidad<br>Cuando navega en un dispositivo móvil<br>Entonces se debe mostrar un mensaje indicando que algunas funciones pueden no estar disponibles. | EP006                      |
<br>

###### User Stories for Workers


| Epic / Story ID | Título                              | Descripción                                                                                                          | Criterios de Aceptación                                                                                                          | Relacionado con (Epic ID) |
|-----------------|-------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| US-06           | Registro de Pedidos en Móvil        | Como trabajador, quiero registrar los pedidos desde un dispositivo móvil para agilizar el proceso.                     | **Escenario 1: Registro exitoso en móvil**<br>**Dado** que se ingresa un pedido desde el móvil<br>**Cuando** se envía el pedido al sistema<br>**Entonces** el pedido se registra correctamente.<br>**Escenario 2: Error en el registro**<br>**Dado** que se presenta un error en la conexión<br>**Cuando** se intenta registrar un pedido<br>**Entonces** el sistema muestra un mensaje de error y no se guarda el pedido. | EP002                    |
| US-07           | Marcación de Horas                  | Como trabajador, quiero marcar mis horas de entrada y salida para un registro preciso.                                | **Escenario 1: Marcación de hora correcta**<br>**Dado** que se marca la hora de entrada o salida<br>**Cuando** se realiza la marcación<br>**Entonces** la hora se registra correctamente.<br>**Escenario 2: Error en la marcación**<br>**Dado** que ocurre un problema técnico<br>**Cuando** se marca la hora<br>**Entonces** el sistema muestra un mensaje de error y no se registra la hora. | EP002                    |
| US-08           | Cálculo Automático de Horas Trabajadas| Como trabajador, quiero que la aplicación calcule automáticamente las horas trabajadas para facilitar el proceso de pago. | **Escenario 1: Cálculo correcto de horas**<br>**Dado** que se han registrado las horas trabajadas<br>**Cuando** se calcula el total de horas<br>**Entonces** el total de horas se refleja correctamente en el reporte.<br>**Escenario 2: Error en el cálculo**<br>**Dado** que se presenta un problema con el cálculo<br>**Cuando** se realiza el cálculo de horas<br>**Entonces** el sistema muestra un mensaje de error indicando que los registros son incorrectos o incompletos, y no se calcula el total de horas hasta que se corrijan los datos. | EP002                    |

<br>

###### Technical Stories

| Epic / Story ID | Título                              | Descripción                                                                                                          | Criterios de Aceptación                                                                                                          | Relacionado con (Epic ID) |
|-----------------|-------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| TS-01           | Implementación de Diseño Responsivo | Como desarrollador, quiero asegurar que la landing page esté completamente adaptada para dispositivos móviles, incluyendo la navegación y el contenido. | - **Escenario 1: Visualización en Dispositivos Móviles**<br>**Dado** que la landing page se visualiza en un dispositivo móvil<br>**Cuando** se accede a la página<br>**Entonces** la navegación debe ser accesible mediante un menú hamburguesa y el contenido debe ajustarse correctamente al tamaño de la pantalla.<br><br>- **Escenario 2: Navegación en Móviles**<br>**Dado que** el menú hamburguesa está implementado<br>**Cuando** un usuario interactúa con el menú en un dispositivo móvil<br>**Entonces** el menú debe desplegarse correctamente y permitir la navegación entre secciones. | EP005                  |
| TS-02           | Optimización de SEO Básica          | Como desarrolador, quiero aplicar prácticas básicas de SEO en la landing page para mejorar la visibilidad en motores de búsqueda. | - **Escenario 1: Configuración de Etiquetas Meta**<br>**Dado** que se han añadido etiquetas meta relevantes a la landing page<br>**Cuando** se visualiza el código fuente de la página<br>**Entonces** las etiquetas meta deben estar correctamente configuradas y visibles.<br><br>- **Escenario 2: Análisis de SEO**<br>**Dado que** la optimización SEO está configurada<br>**Cuando** se analiza la página con herramientas SEO<br>**Entonces** la página debe mostrar una puntuación mejorada en comparación con la versión anterior. | EP005                    |
| TS-03           | Implementación de Accesibilidad Web | Como desarrolador, quiero asegurar que la landing page cumpla con los estándares de accesibilidad web (WCAG) para usuarios con discapacidades. | - **Escenario 1: Navegación con Teclado**<br>**Dado* que la landing page está cargada<br>**Cuando** un usuario navega utilizando solo el teclado<br>**Entonces** todos los elementos interactivos deben ser accesibles y enfocados correctamente.<br><br>- **Escenario 2: Uso con Lectores de Pantalla**<br>**Dado que** la landing page está cargada<br>**Cuando** un usuario utiliza un lector de pantalla<br>**Entonces** el contenido debe ser legible y navegable con el lector de pantalla. | EP005                  |

### 3.3. Impact Mapping
<br><img src="assets/Impact%20map.png"><br>
### 3.4. Product Backlog

# Product Backlog

| # Orden | User Story Id | Título                              | Descripción                                                                                | Story Points (1 / 2 / 3 / 5 / 8) |
|---------|---------------|-------------------------------------|--------------------------------------------------------------------------------------------|---------------------------------|
| 1       | US-18         | Presentación del Producto           | Como visitante, quiero ver una presentación clara del producto de administración de restaurantes en la landing page para entender sus características y beneficios. | 1                               |
| 2       | US-19         | Características Principales         | Como visitante, quiero ver las características principales del producto en la landing page para evaluar si cumple con mis necesidades.                          | 1                               |
| 3       | US-20         | Llamada a la Acción                 | Como visitante, quiero encontrar botones de llamada a la acción (CTA) para solicitar una demo o contactar con el equipo de ventas fácilmente.                  | 1                               |
| 4       | US-21         | Accesibilidad en Dispositivos Móviles | Como visitante, quiero que la landing page sea accesible y funcional en dispositivos móviles para asegurarme de que puedo navegar y acceder a la información correctamente. | 3                               |
| 5       | US-13         | Registro de Inventario              | Como administrador, quiero registrar y actualizar el inventario para asegurar disponibilidad de insumos. | 5                               |
| 6       | US-01         | Registro Automático de Pedidos en un Historial| Como administrador, quiero registrar automáticamente los pedidos en un historial, para analizar los datos posteriormente. | 3                             |
| 7       | US-04         | Registro de Gastos e Imprevistos    | Como administrador, quiero registrar los gastos imprevistos para tener un control exhaustivo de los gastos del restaurante. | 5                               |
| 8       | US-05         | Registro de Costos de Platos        | Como administrador, quiero registrar el costo de cada plato para calcular las ganancias netas diarias. | 5                               |
| 9       | US-07         | Marcación de Horas                  | Como trabajador, quiero marcar mis horas de entrada y salida para un registro preciso. | 3                               |
| 10      | US-08         | Cálculo Automático de Horas Trabajadas | Como trabajador, quiero que la aplicación calcule automáticamente las horas trabajadas para facilitar el proceso de pago. | 5                               |
| 11      | US-03         | Generación de Reportes Financieros  | Como administrador, quiero generar reportes de finanzas para analizar el desempeño del restaurante. | 5                               |
| 12      | US-02         | Alerta de Recursos Bajos            | Como administrador, quiero recibir alertas cuando los recursos estén bajos para asegurar una reposición oportuna. | 3                               |
| 13      | US-06         | Registro de Pedidos en Móvil        | Como trabajador, quiero registrar los pedidos desde un dispositivo móvil para agilizar el proceso. | 5                               |
| 14      | US-14         | Gestión de Asistencia               | Como administrador, quiero monitorear la asistencia del personal para identificar patrones y tomar decisiones. | 5                               |
| 15      | US-15         | Programación de Turnos              | Como administrador, quiero programar y modificar los turnos del personal para asegurar una cobertura adecuada. | 5                               |
| 16      | US-16         | Optimización de la Carta de Platos  | Como administrador, quiero optimizar la carta de platos según la demanda histórica para mejorar la oferta del restaurante. | 5                               |
| 17      | US-17         | Administración de Mesas             | Como administrador, quiero gestionar la asignación de mesas para maximizar la eficiencia en la atención al cliente. | 5                               |
| 18      | US-09         | Visualización de Productividad      | Como administrador, quiero visualizar gráficos de productividad para evaluar el rendimiento de los empleados. | 5                               |
| 19      | US-10         | Comparación de Productividad        | Como administrador, quiero comparar la productividad del personal entre diferentes períodos para identificar mejoras. | 5                               |
| 20      | US-11         | Informe de Ventas de Platos         | Como administrador, quiero recibir informes sobre los platos más y menos vendidos para ajustar el menú. | 5                               |
| 21      | US-12         | Optimización del Menú               | Como administrador, quiero recibir sugerencias basadas en datos de ventas para optimizar la carta del restaurante. | 5                               |

Link del Pivotal Tracker: https://www.pivotaltracker.com/n/projects/2716645

## Capítulo IV: Product Design <a id="cap4"></a>

### 4.1. Style Guidelines
Esta sección define las pautas de estilo para garantizar consistencia visual y funcional en todo el producto. Se centra en la identidad visual de la marca, la tipografía, los colores, los iconos, los botones, y la experiencia del usuario. 
#### 4.1.1. General Style Guidelines
Las pautas generales de estilo están diseñadas para asegurar una identidad de marca cohesiva que transmita profesionalismo, modernidad y eficiencia, especialmente orientada a aplicaciones como la nuestra, que mejoran los flujos de trabajo en restaurantes de diversos tipos.

- **Branding**: Utilizamos una paleta de colores que equilibra el profesionalismo, la modernidad y la seriedad, en consonancia con la funcionalidad de un administrador de restaurantes. El color primario `#00141A` es un tono profundo y elegante que representa profesionalismo, confiabilidad, y estabilidad. Este tono oscuro permite un contraste fuerte con los elementos secundarios y resaltados, asegurando la legibilidad y una jerarquía visual clara. El color secundario, un vibrante tono rojo/naranja `#FF3800`, introduce un toque de dinamismo y urgencia, ideal para destacar acciones importantes o llamadas a la acción dentro de la interfaz.
	<br>
	<img src="assets/style-guidelines/landing-color-pallette.png" alt="Color Pallette">
	<br>

- **Typography**: Se ha elegido la tipografía `Poppins` debido a su claridad, modernidad y legibilidad en todos los tamaños de pantalla. Las diferentes variaciones de peso `(ExtraBold, SemiBold, Medium, Regular)` permiten crear una jerarquía clara y aseguran que los usuarios puedan navegar fácilmente por la interfaz.

  	<br>

  <img src="assets/style-guidelines/typography.png" alt="Typography">

	<br>
- **Icons**: Los íconos lineales y minimalistas se utilizan para asegurar una comunicación rápida y efectiva. Son lo suficientemente distintivos para ser reconocidos rápidamente y se alinean con el estilo moderno de la aplicación.
  
  <br>

  <img src="assets/style-guidelines/icons.png" alt="Icons">

  <br>



- **Buttons**: Los botones están diseñados para ser altamente visibles y accesibles. Se utilizan colores de alta visibilidad como el naranja y el rojo para las acciones principales, mientras que los bordes redondeados mejoran la usabilidad en dispositivos táctiles. 

  <br>
  
  <img src="assets/style-guidelines/buttons.png" alt="Buttons">

  <br>
  
- **Spacing and Layout**: Se establece un sistema de espaciado uniforme que garantiza la claridad visual y un flujo de contenido organizado. El espacio adecuado entre los elementos ayuda a los usuarios a enfocarse en las tareas y facilita la navegación en pantallas táctiles. 

#### 4.1.2. Web Style Guidelines
Las pautas de estilo web están específicamente orientadas a la usabilidad y accesibilidad en plataformas digitales, especialmente en dispositivos utilizados en entornos de trabajo rápidos como los restaurantes.

- **Responsive Design**: Todo el diseño está optimizado para ser completamente responsive, asegurando que los elementos sean accesibles y fáciles de interactuar en cualquier tamaño de pantalla, desde dispositivos móviles hasta tablets y desktops.


- **Color Accessibility**: Los colores están seleccionados con criterios de contraste adecuados para cumplir con los estándares de accesibilidad como Web Content Accessibility Guidelines (WCAG), asegurando que todo el texto sea fácilmente legible contra su fondo respectivo. Se incluyen alternativas de alto contraste para usuarios con discapacidades visuales.

  <br>

	<img src="assets/style-guidelines/web-guidelines/web-color-pallette.png" alt="Web Color Pallette">
  
  <br>

- **Hover and Active States**: Los botones, enlaces e iconos incluyen estados de "hover" y "active" claramente definidos para proporcionar retroalimentación visual a los usuarios. Esto es esencial para mejorar la experiencia de usuario y reducir errores.
 <br>

  <img src="assets/style-guidelines/web-guidelines/buttons.png" alt="Web Buttons">

 <br>

- **Performance Optimization**: Se priorizan los diseños ligeros que cargan rápidamente y utilizan imágenes y recursos optimizados. La eficiencia en la carga es crucial para mantener la fluidez en el entorno de uso rápido de un restaurante.
  
- **Navigation and Interactivity**: La navegación está diseñada para ser intuitiva, con accesos directos a funciones clave y un uso mínimo de submenús. Los elementos interactivos tienen retroalimentación visual y táctil para mejorar la experiencia del usuario.


- **Consistent Component Usage**: Se utilizan componentes reutilizables y consistentes a lo largo de la interfaz web, como botones, tarjetas, y formularios, lo que garantiza una experiencia de usuario cohesiva y facilita el mantenimiento y la escalabilidad del código.




### 4.2. Information Architecture
En esta sección, el equipo plantea las decisiones y sustento que dirigen la manera en la que se organizará el contenido en las experiencias web y móvil, incluyendo el Landing Page y las Aplicaciones. Dichas propuestas deben estar orientadas a que los visitantes y usuarios se adapten con facilidad a la funcionalidad de cada producto y puedan encontrar todo aquello que necesiten sin esfuerzo. Se incluyen las decisiones sobre los Organization Systems, Labeling Systems, SEO Tags and Meta Tags, Searching Systems y Navigation Systems.
#### 4.2.1. Organization Systems
En esta sección, se describen las estructuras de organización utilizadas en el contenido de la aplicación web y móvil. Se ha optado por un sistema jerárquico para la mayoría de las secciones, dado que facilita la navegación desde lo general a lo específico. Las secciones principales incluyen: ``Home``, ``Features``, ``Pricing`` y ``Footer``. Además, se aplican organizaciones secuenciales en la sección de precios, donde los usuarios siguen un proceso paso a paso para seleccionar un plan de suscripción. Finalmente, se utiliza una organización matricial en las secciones de reportes y análisis, donde los datos se presentan de manera cruzada para brindar comparaciones útiles.

#### 4.2.2. Labeling Systems
Las etiquetas dentro de la aplicación han sido diseñadas para ser simples, claras y concisas, evitando confusiones para los usuarios.


#### 4.2.3. SEO Tags and Meta Tags
Se ha implementado una estrategia de SEO para asegurar una mejor visibilidad en los motores de búsqueda. A continuación, se presentan las etiquetas utilizadas en las principales páginas de la aplicación:

- **Title**: Food Suit - Gestión Integral de Restaurantes
- **Meta Description**: Food Suite es una solución completa para la gestión de restaurantes, permitiendo optimizar el flujo de trabajo, controlar el inventario y mejorar la eficiencia con una interfaz intuitiva.
- **Meta Keywords**: gestión de restaurantes, control de inventario, soluciones para restaurantes, Food Suit, eficiencia en restaurantes
- **Meta Author**: Latte Company

Estas etiquetas ayudan a mejorar el posicionamiento del sitio en los motores de búsqueda y a atraer al público objetivo.

#### 4.2.4. Searching Systems
Para mejorar la experiencia del usuario, se ha incluido un sistema de búsqueda en la barra de navegación, lo que permite a los usuarios buscar fácilmente contenido dentro del sitio. El sistema de búsqueda incluye filtros que permiten moverse entre las secciones `home`, `features`, y `pricing`. Adicionalmente usamos CTOs ubicados estratégicamente en diversas secciones, la cual dirige al usuario a contactarnos por una demo. 

#### 4.2.5. Navigation Systems
Se ha implementado un sistema de navegación claro y accesible que permite a los usuarios desplazarse fácilmente por el sitio. La navegación principal incluye enlaces a las secciones clave: ``Home``, ``Features`` y ``Pricing``. Además, se ha añadido una barra de navegación fija (sticky navigation) para que los usuarios siempre tengan acceso al menú de secciones, independientemente de su posición en la página.


### 4.3 Landing Page UI Design

El diseño de la Landing Page de Food Suit se enfoca en proporcionar una experiencia intuitiva y clara para los propietarios de restaurantes que buscan mejorar la eficiencia en la gestión de sus negocios. Utilizamos principios de jerarquía visual y diseño inclusivo para facilitar la navegación, asegurando que la información más relevante esté al alcance de los usuarios sin sobrecargar visualmente la página.

El diseño se ha traducido en una interfaz que presenta los beneficios clave del producto de manera concisa, incluyendo una llamada a la acción destacada para captar la atención de los usuarios rápidamente. Además, se aplicó un sistema de diseño coherente para garantizar una experiencia uniforme en todos los dispositivos.


#### 4.3.1 Landing Page Wireframe

El Wireframe refleja la estructura básica y el flujo de la landing page tanto para **Desktop** como para **Mobile**. Se divide en varias secciones clave:
- **Encabezado**: Incluye el logotipo, navegación y un botón destacado de "Try Now".
- **Sección Hero**: Muestra una introducción al producto con un CTA claro. Se utilizan imágenes o gráficos para hacer la propuesta más atractiva visualmente.
- **Sección de Problemas y Soluciones**: Expone los problemas comunes que enfrentan los propietarios de restaurantes y cómo la solución los resuelve.
- **Sección de Beneficios Clave**: Presenta de forma clara las características y beneficios del producto.
- **Tabla de Precios**: Muestra los distintos planes disponibles con información relevante para cada uno de ellos.
- **Pie de Página**: Incluye información sobre la empresa, links a redes sociales y contacto.

<br>

<img src="assets/landing-page-design/Landing page Wireframe.svg" alt="landing page wireframe" width="500">

### 4.3.2 Landing Page Mock-up

El Mock-up final del diseño se basa en los wireframes previos, pero añade colores, tipografías e imágenes que fortalecen la identidad de la marca. La elección de colores se centra en tonos modernos y profesionales que reflejan la confianza y eficiencia del producto.

Se incluyen los siguientes detalles visuales:
- **Color Primario**: Se utiliza para destacar los botones y llamadas a la acción, dirigiendo la atención de los usuarios a los elementos interactivos más importantes.
- **Tipografías**: Se escoge una tipografía legibles y modernas, manteniendo la coherencia en toda la página.
- **Imágenes e Ilustraciones**: Refuerzan el mensaje clave y añaden un toque visual agradable sin distraer al usuario de la información principal.

El diseño también es adaptable a dispositivos móviles, asegurando una experiencia de usuario consistente y optimizada.

<br>

<img src="assets/landing-page-design/mockup.png" alt="landing page mock-up" width="500">


### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes

Esta es la página principal que ve el administrador.

![Mock Up - Home](https://github.com/user-attachments/assets/3b535871-a64f-4636-8a53-641809ba75a6)

En esta sección podrá ver el desempeño del restaurante.

![Wireframe - Finance](https://github.com/user-attachments/assets/ac2b8402-6f76-4d87-94ec-eb812ccba306)

También podrá editar los valores si este lo desea.

![Wireframe - Finance (1)](https://github.com/user-attachments/assets/16627a96-5fa7-4e78-bf11-ead075d70ba4)

En este apartado se visualizará el desempeño de cada empleado.

![Wireframe - Employees](https://github.com/user-attachments/assets/dcf75a64-247d-4a2f-8fe3-b5f422772599)

Esta sección es para agregar un empleado más.

![Wireframe - Employees (1)](https://github.com/user-attachments/assets/6f29b75b-6714-4e8e-8b49-93d42a911fd2)

En esta página el administrador podrá editar la horas de trabajo de cada empleado.

![Wireframe - Employees (2)](https://github.com/user-attachments/assets/7d05112a-1f90-4b26-93ad-9904f6c42837)

Esta sección es para la visualización de los insumos de cocina restantes.

![Wireframe - Inventory](https://github.com/user-attachments/assets/48d35a54-2ed3-418a-9a3d-6c342d6df6e7)


Este apartado es para los meseros, es esta podrán agregar pedidos.

![Wireframe - Add Order](https://github.com/user-attachments/assets/d0de4f3e-e63e-4d82-8e47-689ff53dafe0)

En esta sección se podrá seleccionar el tipo de platillo para agragar a la orden

![Wireframe - Add Order (1)](https://github.com/user-attachments/assets/76fb82dc-8f7c-4d17-afe3-1691828a144e)

En esta página se podrá agregar un platillo de entrada.

![Wireframe - Add Order (2)](https://github.com/user-attachments/assets/d57c8ab7-11d1-44f9-a36e-4b75b93a1754)

Asimismo, en este apartado se podrá agregar un plato principal.

![Wireframe - Add Order (3)](https://github.com/user-attachments/assets/94b5b1ef-7068-464d-bdee-e5a4a5c30887)

En esta sección se podrá agregar un platillo especial a la orden.

![Wireframe - Add Order (4)](https://github.com/user-attachments/assets/1f17206e-ac65-4fa3-acc2-0adfdf0b2d6a)

Este apartado es para la selección de un postre a la orden.

![Wireframe - Add Order (5)](https://github.com/user-attachments/assets/c1a73b0e-1a61-4e66-8182-f794c98b44f7)

Esta sección es para agregar bebidas a la orden.

![Wireframe - Add Order (6)](https://github.com/user-attachments/assets/23076034-9c72-4bf6-9aed-50c0bc296c6d)

En este apartado se podrá editar las ordenes existentes.

![Wireframe - Add Order (7)](https://github.com/user-attachments/assets/214434f5-a52e-43ac-85db-cc8967911b85)


Este apartado es para los cocineros, en esta página podrán observar los pedidos pendientes.

![Wireframe - Order](https://github.com/user-attachments/assets/f0972e2a-bde0-459a-a30f-3641f8465895)


En esta sección podrán observar los insumos restantes de cocina.

![Wireframe - Inventory (1)](https://github.com/user-attachments/assets/051e0386-992e-42fb-853b-63875aa654c2)

Y en esta editarlos.

![Wireframe - Edit Inventory](https://github.com/user-attachments/assets/02d83e47-21e3-4529-a5df-6b522d3595af)

#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups

Esta es la página principal que ve el administrador.

![Mock Up - Home (1)](https://github.com/user-attachments/assets/e1f0acac-6298-4faa-8b9e-ddb9b76e3488)

En esta sección podrá ver el desempeño del restaurante.

![Wireframe - Finance (2)](https://github.com/user-attachments/assets/950f0f25-40a3-4623-b58a-df0d43319c42)


También podrá editar los valores si este lo desea.

![Wireframe - Finance (3)](https://github.com/user-attachments/assets/e54e6307-df0f-4048-a6c1-422f6ac3bc9d)


En este apartado se visualizará el desempeño de cada empleado.

![Wireframe - Employees (3)](https://github.com/user-attachments/assets/c773106d-8d50-414e-bef6-947607cf4058)


Esta sección es para agregar un empleado más.

![Wireframe - Employees (4)](https://github.com/user-attachments/assets/bc9eb5db-1898-4c4e-a9b5-b6f29cbdc380)


En esta página el administrador podrá editar la horas de trabajo de cada empleado.

![Wireframe - Employees (5)](https://github.com/user-attachments/assets/d9f9e8b4-9925-4e6f-a446-4abebde0b8ed)


Esta sección es para la visualización de los insumos de cocina restantes.

![Wireframe - Inventory (2)](https://github.com/user-attachments/assets/27aa5a08-45bf-48b5-a41d-f2bfe43bc412)


Este apartado es para los meseros, es esta podrán agregar pedidos.

![Wireframe - Add Order (8)](https://github.com/user-attachments/assets/bb299acd-c9ef-4ca6-9497-f28d11eb02a7)

En esta sección se podrá seleccionar el tipo de platillo para agragar a la orden 

![Wireframe - Add Order (9)](https://github.com/user-attachments/assets/215c047c-00e7-4ce8-bc08-03613539516f)


En esta página se podrá agregar un platillo de entrada.

![Wireframe - Add Order (10)](https://github.com/user-attachments/assets/62b38ed4-ee26-4f65-b877-ac2df92a817a)

 
Asimismo, en este apartado se podrá agregar un plato principal.

![Wireframe - Add Order (11)](https://github.com/user-attachments/assets/8377c15d-7a26-4605-8c4c-0ce1d7386a1a)


En esta sección se podrá agregar un platillo especial a la orden.

![Wireframe - Add Order (12)](https://github.com/user-attachments/assets/7d1018ac-1eff-4427-8d47-fdb24e28bfc8)


Este apartado es para la selección de un postre a la orden.

![Wireframe - Add Order (13)](https://github.com/user-attachments/assets/a13b02cd-7710-44c8-a0c9-372888572812)


Esta sección es para agregar bebidas a la orden.

![Wireframe - Add Order (14)](https://github.com/user-attachments/assets/4c8495b2-acf1-4775-8355-d4591a9c426d)

En este apartado se podrá editar las ordenes existentes.

![Wireframe - Add Order (15)](https://github.com/user-attachments/assets/28a4649e-1361-4df6-a5a5-b2804744caff)


Este apartado es para los cocineros, en esta página podrán observar los pedidos pendientes.

![Wireframe - Order (1)](https://github.com/user-attachments/assets/01198a2c-2b7a-4933-93c8-cd1bf4fcbc8e)


En esta sección podrán observar los insumos restantes de cocina.

![Wireframe - Inventory (3)](https://github.com/user-attachments/assets/9e90c444-8975-4610-bc47-03b9c566c51e)


Y en esta editarlos.

![Wireframe - Edit Inventory (1)](https://github.com/user-attachments/assets/de5926fd-7e4d-406d-831c-2906451567cc)


#### 4.4.4. Web Applications User Flow Diagrams
### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
La arquitectura de software orientada al dominio proporciona una imagen de lo que se quiere en la estructura de software de nuestro producto. Tal imagen refleja lo que nosotros, Latte, planteamos para FoodSuit: identificar las funcionalidades de la solución y cómo se van a estructurar adaptándose a los elementos a usar.
#### 4.6.1. Software Architecture Context Diagram
Los elementos presentes son:

- Visitor (Visitante): Visualiza el landing page.
- Business Administrator (Administrador de Negocio): Accede a la aplicación web.
- Worker (Trabajador): Accede a la aplicacion móvil
- System Administrator (Administrador de Sistema): Supervisa el funcionamiento de las aplicaciones.
- FoodSuit: Software que los usuarios utilizarán.
  ![Context](assets/c4model/structurizr-SystemContext-001.png)

#### 4.6.2. Software Architecture Container Diagrams
Los elementos presentes son:

- Landing Page: Página que presenta el producto.
- Web App: Frontend donde los administradores de empresa interactúan con la aplicación web.
- Mobile App: Frontend donde los trabajadores de empresa interactúan con la aplicación móvil.
- API: Conexión entre el frontend y backend.
- Bounded Contexts: Las funcionalidades que el sistema proporciona a los usuarios.
- Bases de datos: Almacenará datos como inventario y toda la logística de la empresa.
  ![Container](assets/c4model/structurizr-Container-001.png)

#### 4.6.3. Software Architecture Components Diagrams
**Order and Inventory**<br>
Los elementos presentes son:
- Controllers: Controlan un conjunto de funcionalidades.
- Managers: Realizan una secuencia para llevar a cabo una acción.
- Repositories: Permiten el acceso a una base de datos o un servicio externo.
  ![Container](assets/c4model/structurizr-Component-001.png)

**Finance Monitoring**<br>
Los elementos presentes son:
- Controller: Controla un conjunto de funcionalidades.
- Manager: Realiza una secuencia para llevar a cabo una acción.
- Generator: Realiza una generación de un archivo en base a datos proporcionados.
- Calculador: Realiza una serie de cálculos en base a datos proporcionados.
  ![Container](assets/c4model/structurizr-Component-002.png)

**Business Optimization**<br>
Los elementos presentes son:
- Controller: Controla un conjunto de funcionalidades.
- Manager: Realiza una secuencia para llevar a cabo una acción.
- Generator: Realiza una generación de un archivo en base a datos proporcionados.
- Evaluator: Genera una evaluación en base a datos proporcionados
  ![Container](assets/c4model/structurizr-Component-003.png)

**Menu Optimization**<br>
Los elementos presentes son:
- Controller: Controla un conjunto de funcionalidades.
- Analyzers: Analiza datos proporcionados para devolver un resultado.
- Adjuster: Ajusta un dato.
- Visualizer: Permite la visualización de un análisis.
  ![Container](assets/c4model/structurizr-Component-004.png)

**Client Management**<br>
Los elementos presentes son:
- Controller: Controla un conjunto de funcionalidades.
- Manager: Realiza una secuencia para llevar a cabo una acción.
  ![Container](assets/c4model/structurizr-Component-005.png)
### 4.7. Software Object-Oriented Design
El diseño orientado a objetos del software será esencial para nuestro proyecto. Estructuramos nuestro software de acuerdo a nuestras reglas de negocio para poder crear componentes que puedan ser entendibles para su desarrollo en un sistema real, y sean fáciles de modificar para nosotros.
#### 4.7.1. Class Diagrams
![Class Diagram](assets/OOdiagrams/classDiagram.png)
#### 4.7.2. Class Dictionary
| **Clase**            | **Nombre de Atributo** | **Descripción**                    | **Tipo de Dato** |
|----------------------|------------------------|------------------------------------|------------------|
| Business             | name                   | Nombre del negocio                 | String           |
| Business             | inventory              | Inventario del negocio             | Inventory        |
| Business             | sales                  | Ventas del negocio                 | Sales            |
| Employee             | id                     | Identificador del empleado         | String           |
| Employee             | name                   | Nombre del empleado                | String           |
| Employee             | productivityRate       | Tasa de productividad del empleado | Float            |
| AssistanceRegister   | dateRegister           | Fecha de registro de asistencia    | Date             |
| AssistanceRegister   | dateExit               | Fecha de salida de asistencia      | Date             |
| ProductivityAnalysis | period                 | Período de análisis                | String           |
| ProductivityAnalysis | hoursWorked            | Horas trabajadas                   | Float            |
| ProductivityAnalysis | performanceRate        | Tasa de rendimiento                | Float            |
| Period               | id                     | Identificador del periodo          | String           |
| Period               | employees              | Empleados del periodo              | Array            |
| Period               | datePeriod             | Fecha del periodo                  | Date             |
| SalesReport          | dateStart              | Fecha de inicio del reporte        | Date             |
| SalesReport          | dateEnd                | Fecha de fin del reporte           | Date             |
| SalesReport          | dishesSold             | Platos vendidos                    | Array            |
| Expense              | id                     | Identificador del gasto            | String           |
| Expense              | dateDone               | Fecha del gasto                    | Date             |
| Expense              | amount                 | Monto del gasto                    | Float            |
| Expense              | category               | Categoría del gasto                | String           |
| Menu                 | dishes                 | Platos del menú                    | Array            |
| Menu                 | dateMade               | Fecha de creación del menú         | Date             |
| Dish                 | name                   | Nombre del plato                   | String           |
| Dish                 | price                  | Precio del plato                   | Float            |
| Dish                 | quantity               | Cantidad de platos                 | Integer          |
| Inventory            | id                     | Identificador del inventario       | String           |
| Inventory            | resources              | Recursos del inventario            | Array            |
| Inventory            | quantity               | Cantidad de recursos               | Integer          |
| Inventory            | minimum                | Cantidad mínima de recursos fijado | Integer          |
| Items                | id                     | Identificador del item             | String           |
| Items                | name                   | Nombre del item                    | String           |
| Items                | quantity               | Cantidad del item                  | Integer          |
| Order                | id                     | Identificador de la orden          | String           |
| Order                | dateCreated            | Fecha de creación de la orden      | Date             |
| Order                | items                  | Items de la orden                  | Array            |
| Order                | total                  | Total de la orden                  | Float            |
| OrderItem            | name                   | Nombre del item de la orden        | String           |
| OrderItem            | price                  | Precio del item de la orden        | Float            |
| OrderItem            | quantity               | Cantidad del item de la orden      | Integer          |
| Table                | tableNumber            | Número de mesa                     | Integer          |
| Table                | capacity               | Capacidad de la mesa               | Integer          |
| Table                | available              | Disponibilidad de la mesa          | Boolean          |
| Client               | id                     | Identificador del cliente          | String           |
| Client               | name                   | Nombre del cliente                 | String           |
| Client               | tableAsssigned         | Mesa asignada al cliente           | int              |

### 4.8. Database Design
El diseño de la base de datos será fundamental para nuestro proyecto, ya que proporcionará la estructura subyacente para almacenar y gestionar los datos de manera eficiente y segura. Esto nos permitirá organizar los datos de manera lógica y coherente, facilitando su recuperación y manipulación en respuesta a las solicitudes de los usuarios.
#### 4.8.1. Database Diagram
![Database Diagram](assets/OOdiagrams/latteDB.png)

## Capítulo V: Product Implementation, Validation & Deployment <a id="cap5"></a>

## 5.1. Software Configuration Management
La gestión de la configuración del software es crucial para nuestro trabajo, ya que nos permite mantener un control preciso sobre los elementos de nuestro proyecto, como el código fuente, los documentos de diseño y los activos digitales. Esto garantiza que todos los miembros del equipo estén trabajando con la misma versión de los archivos y facilita la colaboración entre desarrolladores.

### 5.1.1. Software Development Environment Configuration

#### Project Management:

- [Google Meet](https://meet.google.com/):

  Se utilizó Google Meet para realizar reuniones virtuales con el equipo, permitiendo la comunicación en tiempo real y la colaboración en el proyecto.

- [Trello](https://trello.com/login):
  Trello es una aplicación de gestión de proyectos basada en tableros que permite organizar y asignar tareas a los miembros del equipo de manera visual y sencilla. Facilita el seguimiento de tareas individuales y en grupo mediante listas, tarjetas y tableros.  
  
  <img src="assets/trello.png"><br>

#### Requirement Management:
- [Miro](https://miro.com/):
  Utilizamos Miro para desarrollar nuestros As-Is Scenario Mapping, To-Be Scenario Mapping, User Journey Maps y Empathy Maps, lo que nos permitió visualizar y analizar la experiencia de los usuarios y los procesos actuales y futuros del proyecto.
    <img src="assets/As-Is admin.png"><br>

- [UXPressia](https://uxpressia.com/):  
  Utilizamos UXPressia para crear mapas de empatía, user journey maps y user personas, lo que nos permitió comprender mejor las necesidades y expectativas de los usuarios finales. 
   <img src="assets/Eduardo Ventura.png"><br>
    
- [Structurizr](https://structurizr.com/):  
    Utilizamos Structurizr para crear diagramas de arquitectura de software, lo que nos permitió visualizar y documentar la estructura de nuestro sistema y sus componentes. 

#### Product UX/UI Design:
- [Figma](https://www.figma.com/):  
  Figma es una herramienta de diseño colaborativo que permite a equipos de diseño trabajar juntos en tiempo real en la creación de wireframes, prototipos y mockups, facilitando el feedback y la iteración de ideas.  

- [LucidChart](https://www.lucidchart.com/pages/):  
  LucidChart es una herramienta de diagramación y colaboración visual en línea que permite la de diagramas de clase y modelado UML, lo que nos permitió diseñar la arquitectura de nuestro sistema y documentar las relaciones entre los componentes.
#### Software Development:
- [HTML5](https://developer.mozilla.org/es/docs/Web/HTML):  
  HTML5 es el estándar actual para la estructura de páginas web. Nos permite incluir componentes multimedia y gráficos, mejorando la interactividad y accesibilidad del contenido web.   


- [CSS](https://developer.mozilla.org/es/docs/Web/CSS):  
  CSS es el lenguaje de diseño utilizado para definir la presentación visual de documentos HTML. Se usa para estilizar elementos y asegurar una experiencia de usuario atractiva y uniforme.  

- [JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript):  
  JavaScript es un lenguaje de programación que permite implementar interactividad en páginas web. Es fundamental para añadir lógica dinámica a nuestros sitios web.  
 

- [WebStorm](https://www.jetbrains.com/webstorm/):  
  WebStorm es un entorno de desarrollo integrado (IDE) que ofrece soporte para JavaScript, TypeScript, HTML y CSS, mejorando la productividad de los desarrolladores mediante características avanzadas como la detección de errores en tiempo real y el autocompletado de código.  

#### Software Testing:
- **Lenguaje Gherkin**:  
  Gherkin es un Lenguaje Específico de Dominio (DSL) que permite escribir pruebas funcionales en un lenguaje accesible para todos los miembros del equipo. Se basa en la estructura **Given-When-Then** para definir escenarios de comportamiento esperado.

#### Software Documentation:
- [GitHub](http://github.com):  
  GitHub es una plataforma que facilita el versionado y la colaboración en el desarrollo de código. Proporciona herramientas para la revisión de código, seguimiento de problemas y documentación, asegurando que todos los miembros del equipo estén sincronizados.  

#### Software Deployment:
- **GitHub Pages**:
  GitHub Pages nos permite desplegar sitios web estáticos directamente desde un repositorio GitHub, lo que facilita el lanzamiento de versiones simples de productos sin necesidad de un entorno de servidor complejo.  
 

#### 5.1.2. Source Code Management

##### Landing Page Repository: [GitHub](https://github.com/Latte-WebApps/FoodSuiteLandingPage.git)

- **GitFlow Implementation:**<br>
    Utilizamos el flujo de trabajo GitFlow para organizar y gestionar las ramas de nuestro repositorio. Nos basamos en el flujo de trabajo tomando como referencia "A successful Git branching model" de Vincent Driessen.
    Este enfoque nos permite mantener un flujo de trabajo estructurado y colaborativo, con ramas dedicadas para nuevas características, correcciones de errores y lanzamientos estables.
    <br><img src="assets/gitflow.png"><br>

- **Master o Main branch**:  
  La rama principal de desarrollo del proyecto es la `Master branch`. En esta rama reside el código que actualmente se encuentra en producción.  
  **Notación**: `master` o `main`.

- **Develop branch**:  
  La rama `Develop` albergará las más recientes actualizaciones y cambios que serán incluidos en la próxima versión del proyecto. Esta rama sirve como un espacio para la integración y prueba continua de los cambios antes de ser fusionados con la rama `Master` para su despliegue en producción.  
  **Notación**: `develop`.

- **Release branch**:  
  La `Release branch` facilita la preparación de una nueva versión del producto. Esta rama permite la corrección de errores y la adición de mejoras, mientras que la rama `Develop` continúa recibiendo actualizaciones.
    - Debe derivarse de la rama `Develop`.
    - Debe fusionarse con las ramas `Develop` y `Master`.  
      **Notación**: `release`.

- **Feature branch**:  
  Las ramas de características (`Feature branches`) serán empleadas para desarrollar nuevas funcionalidades que se agregarán en la siguiente versión o en versiones futuras.
    - Debe derivarse de la rama `Develop`.
    - Debe fusionarse de vuelta a la rama `Develop`.  
      **Notación**: `feature`.

- **Hotfix branch**:  
  La `Hotfix branch` se emplea para resolver errores en la versión en producción del producto de manera inmediata.
    - Debe derivarse de la rama `Master`.
    - Debe fusionarse con las ramas `Develop` y `Master`.  
      **Notación**: `hotfix`.

- **Support branch**:  
  Se utiliza para tareas de mantenimiento prolongado, como soporte de versiones anteriores.

#### Conventional Commits:
[**Conventional Commits**](https://www.conventionalcommits.org/en/v1.0.0/) es una convención que estructura los mensajes de confirmación (commits) en un formato estándar y semántico. Este formato ayuda a comunicar claramente los cambios realizados en el código y facilita la generación automática de registros de cambios.

La estructura de un commit debe seguir las siguientes pautas:

```bash
git commit -m "<type>[optional scope]: <title>" -m "<description>"
```

**Tipos de Conventional Commits:**

```bash
1. feat: Describe una nueva funcionalidad o característica añadida al código.
2. fix: Indica una solución a un bug o problema.
3. docs: Se utiliza para cambios o mejoras en la documentación del código.
4. : Cambios relacionados con el formato del código, como espacios en blanco o sangría, sin afectar su funcionalidad.
5. refactor: Modificaciones en el código que no corrigen errores ni agregan nuevas características, sino que mejoran la estructura o legibilidad.
6. test: Indica la adición o modificación de pruebas unitarias o funcionales.
7. chore: Se utiliza para cambios en el proceso de construcción o tareas de mantenimiento que no están directamente relacionadas con el código.
8. perf: Describe mejoras de rendimiento en el código.
```

### 5.1.3. Source Code Style Guide & Conventions
Para el desarrollo del proyecto se utilizó como guideline de estilo  [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) y [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html), 
garantiando un código limpio, legible y consistente.

#### HTML
- **Use Lowercase Element Names**:  
  Es recomendable utilizar minúsculas para los nombres de los elementos HTML.
  ~~~
  <body>
      <p>This is a paragraph</p>
  </body>
  ~~~
- **Use Lowercase Attribute Names**:  
  Los nombres de los atributos HTML deben estar en minúsculas.
  ~~~
  <a href="https://www.example.com">Link</a>
  ~~~
- **Use Double Quotes for Attribute Values**:<br>
    Se recomienda utilizar comillas dobles para los valores de los atributos.
    ~~~
    <img src="image.jpg" alt="Image">
    ~~~
- **Omit Type Attributes for Style Sheets and Scripts**:<br>
    No es necesario incluir el atributo `type` para las hojas de estilo y los scripts.
    ~~~
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
    ~~~
#### CSS
- **Use Lowercase and Hyphens for Property Names**:<br>
    Los nombres de las propiedades CSS deben estar en minúsculas y separados por guiones.
    ~~~
    .example-class {
        background-color: red;
        font-size: 16px;
    }
    ~~~
- **ID and Class Name Style**:<br>
    Utilice nombres descriptivos y significativos para las clases y los IDs.
    ~~~
    #nav{}
    .header{}
    ~~~
- **Use Shorthand Properties**:<br>
    Se recomienda utilizar propiedades abreviadas para reducir la redundancia en el código.
    Por ejemplo CSS nos ofrece la propiedad `font` que nos permite definir en una sola línea el tamaño de la fuente, el tipo de fuente y el color.
    ~~~
    border-top: 0;
    font: 100%/1.6 palatino, georgia, serif;
    padding: 0 1em 2em;
    ~~~

#### JavaScript

- **Use Semicolons**:  
  Es recomendable utilizar punto y coma al final de cada instrucción en JavaScript.
  ~~~
  var x = 5;
  ~~~
- **Use `const` and `let`**:
    Se recomienda utilizar `const` para variables que no cambiarán su valor y `let` para variables que sí lo harán.
    ~~~
    const PI = 3.14159;
    let count = 0;
    ~~~
- **Declaring Variables**:  
  Es recomendable declarar todas las variables al principio de la función o bloque de código.
  ~~~
    const myName = 'Chris';
    console.log(myName);
    let myAge = '40';
    myAge++;
    console.log('Happy birthday!');
  ~~~
#### C#
- **Use PascalCase for Class Names**:  
  Los nombres de las clases deben seguir la convención PascalCase.
  ~~~
  public class MyClass
  {
      // Class members
  }
  ~~~
- **Use CamelCase for Method Names**:  
  Los nombres de los métodos deben seguir la convención camelCase.
  ~~~
  public void myMethod()
  {
      // Method body
  }
  ~~~
- **Use Explicit Access Modifiers**:
    Es recomendable utilizar modificadores de acceso explícitos en lugar de depender de los valores predeterminados.
    ~~~
    public class MyClass
    {
        private int myField;
        public void MyMethod()
        {
            // Method body
        }
    }
    ~~~
- **Comments and Documentation**:
    Es recomendable incluir comentarios descriptivos en el código para explicar su funcionamiento y propósito.
    ~~~
    // This method calculates the sum of two numbers
    public int CalculateSum(int a, int b)
    {
        return a + b;
    }
    ~~~
#### Language GHERKIN
- **Use Given-When-Then Structure**:  
  Es recomendable seguir la estructura Given-When-Then para escribir escenarios de prueba.
  ~~~
  Feature: Login
  Scenario: Successful Login
    Given the user is on the login page
    When the user enters valid credentials
    Then the user is redirected to the dashboard
  ~~~
- **Use Scenario Outlines for Data-Driven Tests**:
    Se recomienda utilizar Scenario Outlines para escribir pruebas basadas en datos.
    ~~~
    Feature: Login
    Scenario Outline: Invalid Login
      Given the user is on the login page
      When the user enters "<username>" and "<password>"
      Then an error message is displayed
      Examples:
        | username | password |
        | user1    | pass1    |
        | user2    | pass2    |
    ~~~
- **Use Tags for Categorization**:
    Es recomendable utilizar etiquetas para categorizar y organizar los escenarios de prueba.
    ~~~
    @login
    Feature: Login
    Scenario: Successful Login
      Given the user is on the login page
      When the user enters valid credentials
      Then the user is redirected to the dashboard
    ~~~
- **Add Comments for Clarity**:
    Se recomienda incluir comentarios en los archivos Gherkin para explicar el propósito y el contexto de los escenarios de prueba.
    ~~~
    # This scenario tests the login functionality
    Feature: Login
    Scenario: Successful Login
      Given the user is on the login page
      When the user enters valid credentials
      Then the user is redirected to the dashboard
    ~~~

#### 5.1.4. Software Deployment Configuration

En este proyecto, utilizamos GitHub Pages para desplegar la landing page y las aplicaciones web. GitHub Pages es un servicio de alojamiento web gratuito que permite publicar sitios web estáticos directamente desde un repositorio de GitHub.

Para configurar el despliegue de la landing page en GitHub Pages, seguimos los siguientes pasos:

1. **Crear un Repositorio de GitHub**:  
  Creamos un repositorio de GitHub para el proyecto de la landing page.
2. **Clonar el Repositorio**:  
  Clonamos el repositorio en nuestra máquina local utilizando Git.
3. **Crear la Estructura del Proyecto**:  
  Creamos la estructura de archivos y carpetas para la landing page, incluyendo el archivo `index.html` y los archivos CSS y JavaScript necesarios.
4. **Desplegar en GitHub Pages**:  
  Para desplegar la landing page en GitHub Pages, seguimos estos pasos:
    - Navegamos a la pestaña `Settings` del repositorio en GitHub.
    - En la sección `GitHub Pages`, seleccionamos la rama `master` como fuente para el despliegue.
    - Guardamos la configuración y esperamos a que GitHub Pages publique la landing page.
    - Una vez publicada, accedemos a la URL proporcionada por GitHub Pages para ver la landing page en línea.



### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint 1
##### 5.2.1.1. Sprint Planning 1
##### 5.2.1.2. Sprint Backlog 1
##### 5.2.1.3. Development Evidence for Sprint Review
##### 5.2.1.4. Testing Suite Evidence for Sprint Review
##### 5.2.1.5. Execution Evidence for Sprint Review
##### 5.2.1.6. Services Documentation Evidence for Sprint Review
##### 5.2.1.7. Software Deployment Evidence for Sprint Review
##### 5.2.1.8. Team Collaboration Insights during Sprint

## Conclusiones
* En el desarrollo de FoodSuit, los segmentos objetivos nos ayudaron a comprender lo que los administradores de restaurantes esperan de un producto de gestión de restaurantes. Esto nos permitió identificar las características clave que debemos incluir en FoodSuit para satisfacer sus necesidades. Gracias a esto, podemos ofrecer un producto como solución práctica y eficiente que promueve una organización cómoda de un restaurante.
* El diseño de entrevistas nos ha resultado útil para recopilar información valiosa sobre las necesidades y expectativas de los administradores de restaurantes. Nos permitió obtener información detallada sobre los problemas y desafíos que enfrentan en la gestión de sus restaurantes, lo que nos ayudó a identificar las características clave que deben incluirse en FoodSuit.
* Al evaluar los competidores, pudimos identificar las fortalezas y debilidades de sus productos, lo que nos permitió identificar oportunidades para mejorar y diferenciar FoodSuit. Esto nos ayudó a definir una propuesta de valor única y atractiva para nuestro producto, que destaca sus características clave y beneficios para los usuarios.
## Bibliografía

## Anexos
