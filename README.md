<center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Fundamentos de Arquitectura de Software - NRC6331</strong><br>
    <strong>Profesor: Jorge Luis Delgado Vite</strong><br>
    <br>Final Project Report
</p>

<center>

### Startup: **SuitsUPC**
#### Product: **LawConnect**

</center>

#### <center>Team  Members:</center>

<center>

| Member                             | Code       |
|------------------------------------|------------|
| Johan Jorge Quiñones Tintaya       | U202113656 |
| Stephano Renan Valdivia Quispe     |  |
| Diego Rodrigo Pumahualcca Garcia   |  |
|        |  |
|        |  |

<br> Julio 2025
</center>  


## Registro de Versiones del Informe  
| Version | Fecha      | Autor                              | Descripción de Modificación                      |
|---------|------------|------------------------------------|--------------------------------------------------|
| 1.0.0   | 07/09/2025 | Johan Jorge Quiñones Tintaya       | Desarrollo parcial del **Capítulo I**            |

## Project Report Collaboration Insights  
**TB1:**  
En esta entrega el equipo definió las bases del tema que se trabajará en el ciclo, sus segmentos objetivo, Lean UX, requisitos y bounded contexts.

***Figura 4.*** Commits del reporte TB1, mostrando la colaboración del equipo en el desarrollo inicial del proyecto.

<img src="" alt="Commits TB1 Report" width="600"/>


## Contenido

[Registro de Versiones del Informe](#registro-de-versiones-del-informe)  
[Project Report Collaboration Insights](#project-report-collaboration-insights)  
[Student Outcome](#student-outcome) 

## Contenido

[Registro de Versiones del Informe](#registro-de-versiones-del-informe)  
[Student Outcome](#student-outcome)  

[Capítulo I: Introducción](#capítulo-i-introducción)  
[1.1. Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1. Nombre del producto](#121-nombre-del-producto)  
[1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)  
[1.2.3. Lean UX Process](#123-lean-ux-process)  
[1.2.3.1. Lean UX Problem Statement](#1231-lean-ux-problem-statement)  
[1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)  
[1.2.3.3. Lean UX Hypothesis](#1233-lean-ux-hypothesis)  
[1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)  

[1.3. Segmentos objetivo](#13-segmentos-objetivo)  

[Capítulo II: Requirements & Analysis](#capítulo-ii-requirements--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. Empathy Maps](#233-empathy-maps)  
[2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)  

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)  
[3.2. User Stories](#32-user-stories)  
[3.3. Impact Map](#33-impact-map)  
[3.4. Product Backlog](#34-product-backlog)  


[Capítulo IV: Product Architecture Design](#capítulo-iv-product-architecture-design)  
[4.1. Design Concepts, ViewPoints & ER Diagrams](#41-design-concepts-viewpoints--er-diagrams)  
[4.1.1. Principles Statements](#411-principles-statements)  
[4.1.2. Approaches Statements, Architectural Styles & Patterns](#412-approaches-statements-architectural-styles--patterns)  
[4.1.3. Context Diagram](#413-context-diagram)  
[4.1.4. Approach driven ViewPoints Diagrams](#414-approach-driven-viewpoints-diagrams)  
[4.1.5. Relational/Non Relational Database Diagram](#415-relationalnon-relational-database-diagram)  
[4.1.6. Design Patterns](#416-design-patterns)  
[4.1.7. Tactics](#417-tactics)  

[4.2. Architectural Drivers](#42-architectural-drivers)  
[4.2.1. Design Purpose](#421-design-purpose)  
[4.2.2. Primary Functionality (Primary User Stories)](#422-primary-functionality-primary-user-stories)  
[4.2.3. Quality Attribute Scenarios](#423-quality-attribute-scenarios)  
[4.2.4. Constraints](#424-constraints)  
[4.2.5. Architectural Concerns](#425-architectural-concerns)  

[4.3. ADD Iterations](#415-add-iterations)  
[4.3.X. Iteration N: &lt;Iteration Name&gt;](#43x-iteration-n-iteration-name)   
[4.3.X.1 Architectural Design Backlog N](#43x1-architectural-design-backlog-n)  
[4.3.X.2 Establish Iteration Goal by Selecting Drivers](#43x2-establish-iteration-goal-by-selecting-drivers)  
[4.3.X.3 Choose One or More Elements of the System to Refine](#43x3-choose-one-or-more-elements-of-the-system-to-refine)  
[4.3.X.4 Choose One or More Design Concepts That Satisfy the Selected Drivers](#43x4-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)  
[4.3.X.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#43x5-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)  
[4.3.X.6 Sketch Views (C4 & UML) and Record Design Decisions](#43x6-sketch-views-c4-uml-and-record-design-decisions)  
[4.3.X.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)](#43x7-analysis-of-current-design-and-review-iteration-goal-kanban-board)  


[Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)  
[5.1. Testing Suites & General Patterns](#51-testing-suites--general-patterns)  
[5.1.1. Backend Application Core Testing Suite](#511-backend-application-core-testing-suite)  
[5.1.2. Pattern Based Backend Applications](#512-pattern-based-backend-applications)  
[5.1.3. Pattern Based Custom Software Library](#513-pattern-based-custom-software-library)  
[5.1.4. Framework Pattern Driven Refactoring Report](#514-framework-pattern-driven-refactoring-report)  

[5.2. Software Configuration Management](#52-software-configuration-management)  
[5.2.1. Software Development Environment Configuration](#521-software-development-environment-configuration)  
[5.2.2. Source Code Management](#522-source-code-management)  
[5.2.3. Source Code Style Guide & Conventions](#523-source-code-style-guide--conventions)  
[5.2.4. Software Deployment Configuration](#524-software-deployment-configuration)  

[5.3.1 Sprint 1](#531-sprint-1)  
[5.3.1.1 Sprint Backlog 1](#5311-sprint-backlog-1)  
[5.3.1.2 Development Evidence for Sprint Review](#5312-development-evidence-for-sprint-review)  
[5.3.1.3 Testing Suite Evidence for Sprint Review](#5313-testing-suite-evidence-for-sprint-review)  
[5.3.1.4 Execution Evidence for Sprint Review](#5314-execution-evidence-for-sprint-review)  
[5.3.1.5 Microservices Documentation Evidence for Sprint Review](#5315-microservices-documentation-evidence-for-sprint-review)  
[5.3.1.6 Software Deployment Evidence for Sprint Review](#5316-software-deployment-evidence-for-sprint-review)  
[5.3.1.7 Team Collaboration Insights during Sprint](#5317-team-collaboration-insights-during-sprint)  
[5.3.1.8 Kanban Board](#5318-kanban-board)  

[5.3.2 Sprint 2](#532-sprint-2)  
[5.3.2.1 Sprint Backlog 2](#5321-sprint-backlog-2)  
[5.3.2.2 Development Evidence for Sprint Review](#5322-development-evidence-for-sprint-review)  
[5.3.2.3 Testing Suite Evidence for Sprint Review](#5323-testing-suite-evidence-for-sprint-review)  
[5.3.2.4 Execution Evidence for Sprint Review](#5324-execution-evidence-for-sprint-review)  
[5.3.2.5 Microservices Documentation Evidence for Sprint Review](#5325-microservices-documentation-evidence-for-sprint-review)  
[5.3.2.6 Software Deployment Evidence for Sprint Review](#5326-software-deployment-evidence-for-sprint-review)  
[5.3.2.7 Team Collaboration Insights during Sprint](#5327-team-collaboration-insights-during-sprint)  
[5.3.2.8 Kanban Board](#5328-kanban-board)  

[5.3.3 Sprint 3](#533-sprint-3)  
[5.3.3.1 Sprint Backlog 3](#5331-sprint-backlog-3)  
[5.3.3.2 Development Evidence for Sprint Review](#5332-development-evidence-for-sprint-review)  
[5.3.3.3 Testing Suite Evidence for Sprint Review](#5333-testing-suite-evidence-for-sprint-review)  
[5.3.3.4 Execution Evidence for Sprint Review](#5334-execution-evidence-for-sprint-review)  
[5.3.3.5 Microservices Documentation Evidence for Sprint Review](#5335-microservices-documentation-evidence-for-sprint-review)  
[5.3.3.6 Software Deployment Evidence for Sprint Review](#5336-software-deployment-evidence-for-sprint-review)  
[5.3.3.7 Team Collaboration Insights during Sprint](#5337-team-collaboration-insights-during-sprint)  
[5.3.3.8 Kanban Board](#5338-kanban-board)  

[5.3.4 Sprint 4](#534-sprint-4)  
[5.3.4.1 Sprint Backlog 4](#5341-sprint-backlog-4)  
[5.3.4.2 Development Evidence for Sprint Review](#5342-development-evidence-for-sprint-review)  
[5.3.4.3 Testing Suite Evidence for Sprint Review](#5343-testing-suite-evidence-for-sprint-review)  
[5.3.4.4 Execution Evidence for Sprint Review](#5344-execution-evidence-for-sprint-review)  
[5.3.4.5 Microservices Documentation Evidence for Sprint Review](#5345-microservices-documentation-evidence-for-sprint-review)  
[5.3.4.6 Software Deployment Evidence for Sprint Review](#5346-software-deployment-evidence-for-sprint-review)  
[5.3.4.7 Team Collaboration Insights during Sprint](#5347-team-collaboration-insights-during-sprint)  
[5.3.4.8 Kanban Board](#5348-kanban-board)  

[5.4. Microservices Deployment](#54-microservices-deployment)  
[5.4.1. Cloud Architecture Diagram](#541-cloud-architecture-diagram)  
[5.4.2. Cloud Architecture Deployment (AWS, Microsoft Azure or Google Cloud)](#542-cloud-architecture-deployment-aws-microsoft-azure-or-google-cloud)  

[Conclusiones](#conclusiones)  
[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  
[Video About-the-Team](#video-about-the-team)  
[Referencias Bibliográficas](#referencias-bibliográficas)  
[Anexos](#anexos)  
[Links](#links)


## Student Outcome

ABET - EAC - Student Outcome 7 

Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Integrante</th>
      <th>Entrega</th>
      <th>Acciones realizadas</th>
      <th>Conclusión general</th>
    </tr>
  </thead>
  <tbody>
    <!-- Criterio 1 -->
    <tr>
      <td rowspan="30"><b>Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.</b></td>
      <!-- Johan -->
      <td rowspan="6"><b>Johan Jorge Quiñones Tintaya</b></td>
      <td>TB1</td>
      <td>...</td>
      <td rowspan="20" style="vertical-align: top;">...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- Stephano -->
    <tr>
      <td rowspan="6"><b>Stephano Renan Valdivia Quispe</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- Diego -->
    <tr>
      <td rowspan="6"><b>Diego Rodrigo Pumahualcca Garcia</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- 4 -->
    <tr>
      <td rowspan="6"><b>Integrante 4</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- 5 -->
    <tr>
      <td rowspan="6"><b>Integrante 5</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <tr></tr>
    <!-- Criterio 2 -->
    <tr>
      <td rowspan="30"><b>Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.</b></td>
      <!-- Johan -->
      <td rowspan="6"><b>Johan Jorge Quiñones Tintaya</b></td>
      <td>TB1</td>
      <td>...</td>
      <td rowspan="20" style="vertical-align: top;">...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- Stephano -->
    <tr>
      <td rowspan="6"><b>Stephano Renan Valdivia Quispe</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- Diego -->
    <tr>
      <td rowspan="6"><b>Diego Rodrigo Pumahualcca Garcia</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- 4 -->
    <tr>
      <td rowspan="6"><b>Integrante 4</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
    <!-- 5 -->
    <tr>
      <td rowspan="6"><b>Integrante 5</b></td>
      <td>TB1</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB2</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB3</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TB4</td>
      <td>...</td>
    </tr>
    <tr>
      <td>TF</td>
      <td>...</td>
    </tr>
  </tbody>
</table>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile
### 1.2.1. Nombre del producto
### 1.2.2. Antecedentes y problemática
### 1.2.3. Lean UX Process
#### 1.2.3.1. Lean UX Problem Statement
#### 1.2.3.2. Lean UX Assumptions
#### 1.2.3.3. Lean UX Hypothesis
#### 1.2.3.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. Empathy Maps
### 2.3.4. As-is Scenario Mapping

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Map
## 3.4. Product Backlog

# Capítulo IV: Product Architecture Design
## 4.1. Design Concepts, ViewPoints & ER Diagrams
### 4.1.1. Principles Statements
### 4.1.2. Approaches Statements, Architectural Styles & Patterns
### 4.1.3. Context Diagram
### 4.1.4. Approach driven ViewPoints Diagrams
### 4.1.5. Relational/Non Relational Database Diagram
### 4.1.6. Design Patterns
### 4.1.7. Tactics

## 4.2. Architectural Drivers
### 4.2.1. Design Purpose
### 4.2.2. Primary Functionality (Primary User Stories)
### 4.2.3. Quality Attribute Scenarios
### 4.2.4. Constraints
### 4.2.5. Architectural Concerns

## 4.3. ADD Iterations
### 4.3.X. Iteration N: &lt;Iteration Name&gt;
#### 4.3.X.1 Architectural Design Backlog N
#### 4.3.X.2 Establish Iteration Goal by Selecting Drivers
#### 4.3.X.3 Choose One or More Elements of the System to Refine
#### 4.3.X.4 Choose One or More Design Concepts That Satisfy the Selected Drivers
#### 4.3.X.5 Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces
#### 4.3.X.6 Sketch Views (C4 & UML) and Record Design Decisions
#### 4.3.X.7 Analysis of Current Design and Review Iteration Goal (Kanban Board)

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Testing Suites & General Patterns
### 5.1.1. Backend Application Core Testing Suite
### 5.1.2. Pattern Based Backend Applications
### 5.1.3. Pattern Based Custom Software Library
### 5.1.4. Framework Pattern Driven Refactoring Report

## 5.2. Software Configuration Management
### 5.2.1. Software Development Environment Configuration
### 5.2.2. Source Code Management
### 5.2.3. Source Code Style Guide & Conventions
### 5.2.4. Software Deployment Configuration

## 5.3.1 Sprint 1
### 5.3.1.1 Sprint Backlog 1
### 5.3.1.2 Development Evidence for Sprint Review
### 5.3.1.3 Testing Suite Evidence for Sprint Review
### 5.3.1.4 Execution Evidence for Sprint Review
### 5.3.1.5 Microservices Documentation Evidence for Sprint Review
### 5.3.1.6 Software Deployment Evidence for Sprint Review
### 5.3.1.7 Team Collaboration Insights during Sprint
### 5.3.1.8 Kanban Board

## 5.3.2 Sprint 2
### 5.3.2.1 Sprint Backlog 2
### 5.3.2.2 Development Evidence for Sprint Review
### 5.3.2.3 Testing Suite Evidence for Sprint Review
### 5.3.2.4 Execution Evidence for Sprint Review
### 5.3.2.5 Microservices Documentation Evidence for Sprint Review
### 5.3.2.6 Software Deployment Evidence for Sprint Review
### 5.3.2.7 Team Collaboration Insights during Sprint
### 5.3.2.8 Kanban Board

## 5.3.3 Sprint 3
### 5.3.3.1 Sprint Backlog 3
### 5.3.3.2 Development Evidence for Sprint Review
### 5.3.3.3 Testing Suite Evidence for Sprint Review
### 5.3.3.4 Execution Evidence for Sprint Review
### 5.3.3.5 Microservices Documentation Evidence for Sprint Review
### 5.3.3.6 Software Deployment Evidence for Sprint Review
### 5.3.3.7 Team Collaboration Insights during Sprint
### 5.3.3.8 Kanban Board

## 5.3.4 Sprint 4
### 5.3.4.1 Sprint Backlog 4
### 5.3.4.2 Development Evidence for Sprint Review
### 5.3.4.3 Testing Suite Evidence for Sprint Review
### 5.3.4.4 Execution Evidence for Sprint Review
### 5.3.4.5 Microservices Documentation Evidence for Sprint Review
### 5.3.4.6 Software Deployment Evidence for Sprint Review
### 5.3.4.7 Team Collaboration Insights during Sprint
### 5.3.4.8 Kanban Board

## 5.4. Microservices Deployment
### 5.4.1. Cloud Architecture Diagram
### 5.4.2. Cloud Architecture Deployment (AWS, Microsoft Azure or Google Cloud)

# Conclusiones
# Conclusiones y recomendaciones
# Video About-the-Team
# Referencias Bibliográficas
# Anexos
# Links