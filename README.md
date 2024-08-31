<div align="center">

## Universidad Peruana de Ciencias Aplicadas

![logo](assets/upc_logo.png)

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

| Versión | Fecha | Autores | Descripción de modificación |
| - | - | - | - |
| 1 | 20/08/2024 | | |

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
#### 1.2.1 Antecedentes y problemática
#### 1.2.2 Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
##### 1.2.2.2. Lean UX Assumptions
##### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.4. Lean UX Canvas
### 1.3. Segmentos objetivo


## Capítulo II: Requirements Elicitation & Analysis <a id="cap2"></a>

### 2.1. Competidores
Identificamos tres competidores, cuyos productos son similares directamente o indirectamente a lo que nosotros queremos ofrecer.
1. **Restaurant\.pe**: Es un software para restaurantes que optimiza la gestión del restaurante mediante funcionalidades como un menú online, una plataforma para pedidos y emisión de comprobantes, visualizar ventas y stock, facturación electrónica, entre otros. Ofrece una interfaz amigable, es multiplataforma y puede funcionar con o sin conexión a internet.<br>
<img src="assets/Restaurant.pe_logo.png" alt="Logo Restaurant.pe" width="150"><br>

2. **El Tenedor**: Es un software para restaurantes y personas que buscan restaurantes donde comer. La aplicación almacena la carta del restaurante e información pública como reseñas, ubicación, etc. Permite a las personas reservar mesas del restaurante que disponga de esta aplicación para facilitar la atención.<br>
<img src="assets/ElTenedor_logo.png" alt="Logo El Tenedor" width="150"><br>

3. **Rest\.pe**: Es un software para restaurantes que optimiza la gestión del restaurante y capacita a los trabajadores para aumentar la eficacia del entorno laboral. Aparte de las funcionalidades básicas para un restaurante, presenta múltiples funcionalidades como publicidad local, recetarios, cocina smart, entre otros. Este software es customizable por empresa, por lo que se adapta a lo que la empresa desea según contrato.<br>
<img src="assets/Rest.pe_logo.png" alt="Logo Rest.pe" width="150"><br>

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
### 2.2. Entrevistas.
Las entrevistas siguientes nos sirven para conocer lo que los clientes esperan de un producto, qué experiencias tuvieron con productos similares y qué tipo de decisiones nosotros tenemos que tomar. Al analizar estas entrevistas, nosotros tendremos una idea de cómo desarrollar nuestro producto de manera que ésta se adapte a lo que el cliente desea.
#### 2.2.1. Diseño de entrevistas
#### 2.2.2. Registro de entrevistas
#### 2.2.3. Análisis de entrevistas
### 2.3. Needfinding
#### 2.3.1. User Personas
#### 2.3.2. User Task Matrix
#### 2.3.3. User Journey Mapping
#### 2.3.4. Empathy Mapping
#### 2.3.5. As-is Scenario Mapping
### 2.4. Ubiquitous Language


## Capítulo III: Requirements Specification <a id="cap3"></a>

### 3.1. To-Be Scenario Mapping
### 3.2. User stories

###### User Epics

| Epic ID | Título                              | Descripción                                                                                       |
|---------|-------------------------------------|---------------------------------------------------------------------------------------------------|
| EP001   | Optimización del Registro y Control de Finanzas | Implementar un sistema automatizado para registrar y controlar las finanzas del restaurante, incluyendo pedidos, gastos, e informes financieros. |
| EP002   | Mejora en la Gestión de Pedidos y Asistencia | Desarrollar una solución para registrar pedidos desde dispositivos móviles, marcar horas de trabajo y calcular automáticamente las horas trabajadas. |
| EP003   | Análisis y Optimización del Desempeño del Restaurante | Proporcionar herramientas para analizar la productividad del personal, ventas de platos y optimización del menú basada en datos. |
| EP004   | Gestión de Recursos                  | Facilitar la organización y disponibilidad de los recursos necesarios para el funcionamiento del restaurante, incluyendo inventario, asistencia, turnos y administración de mesas. |
| EP005   | Optimización y Adaptación Técnica de la Landing Page | Optimizar y adaptar la landing page para mejorar el rendimiento, la accesibilidad y la experiencia del usuario. |


<br>

###### User Stories for Administrators

| Epic / Story ID | Título                              | Descripción                                                                                                          | Criterios de Aceptación                                                                                                          | Relacionado con (Epic ID) |
|-----------------|-------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| US-01           | Registro Automático de Pedidos      | Como administrador, quiero registrar automáticamente los pedidos para reducir errores y mejorar la precisión.         | **Escenario 1: Registro exitoso**<br>**Dado** que se realiza un pedido<br>**Cuando** se ingresa al sistema<br>**Entonces** el pedido se registra automáticamente.<br>**Escenario 2: Registro fallido**<br>**Dado** que ocurre un error en el sistema<br>**Cuando** se ingresa un pedido<br>**Entonces** el sistema informa que el registro ha fallado y no se guarda el pedido. | EP001                    |
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
### 3.4. Product Backlog

## Capítulo IV: Product Design <a id="cap4"></a>

### 4.1. Style Guidelines
#### 4.1.1. General Style Guidelines
#### 4.1.2. Web Style Guidelines
### 4.2. Information Architecture
#### 4.2.1. Organization Systems
#### 4.2.2. Labeling Systems
#### 4.2.3. SEO Tags and Meta Tags
#### 4.2.4. Searching Systems
#### 4.2.5. Navigation Systems
### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
#### 4.3.2. Landing Page Mock-up
### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes
#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
#### 4.4.4. Web Applications User Flow Diagrams
### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Software Architecture Context Diagram
#### 4.6.2. Software Architecture Container Diagrams
#### 4.6.3. Software Architecture Components Diagrams
### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
#### 4.7.2. Class Dictionary
### 4.8. Database Design
#### 4.8.1. Database Diagram


## Capítulo V: Product Implementation, Validation & Deployment <a id="cap5"></a>

### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
#### 5.1.2. Source Code Management
#### 5.1.3. Source Code Style Guide & Conventions
#### 5.1.4. Software Deployment Configuration
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

## Bibliografía

## Anexos
