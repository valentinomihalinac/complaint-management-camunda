Customer Complaint Management – Camunda 7
A process-oriented application prototype developed as a university team project for the Process-Service Architectures course at the Faculty of Organization and Informatics (FOI), University of Zagreb.
The project demonstrates how customer complaints can be modeled and processed using BPMN 2.0 and Camunda 7, with task forms, process variables, decision gateways, and execution in a Camunda development environment.
Project Overview
The process begins when a customer submits a complaint related to an order or an individual product. A key account manager reviews and analyzes the complaint, makes a decision, and—if it is approved—proposes a resolution. The customer can then accept or reject the proposed resolution.
Main Process Steps
1. Submit and receive a complaint.
2. Analyze the complaint.
3. Approve, reject, or request additional information.
4. If additional information is needed, return the complaint to the customer for revision.
5. If approved, choose a resolution: product replacement, refund, or repair.
6. Let the customer accept or reject the proposed resolution.
7. If the customer accepts the proposed resolution, implement it and notify the customer; otherwise, the process ends without implementation.
8. If the complaint itself is rejected during review, issue a rejection notice and end the process.
Process Roles
- Customer – submits or revises a complaint and decides whether to accept the proposed resolution.
- Key Account Manager – receives and analyzes complaints, makes decisions, selects and implements resolutions, and notifies the customer.
Features and Business Rules
- BPMN 2.0 workflow with 10 activities and 2 decision gateways, as described in the project documentation.
- Forms for entering and reviewing complaint information during process execution.
- Decision-based routing for approved, rejected, or returned complaints.
- Each complaint is associated with one order and may concern an individual product or the entire order.
- A proposed resolution proceeds to implementation only if accepted by the customer.
- A supporting entity–relationship (ER) model documents the information required for complaint processing.
Tools and Technologies
- Camunda 7 – workflow execution and user tasks
- Camunda Modeler / Form Builder – BPMN process and form design
- BPMN 2.0 – business process modeling notation
- Camunda Tasklist – execution and completion of user tasks
- draw.io – ER data model diagram
Repository Contents
- [`camunda7-project.zip`](camunda7-project.zip) – BPMN model and associated form files
- [`documentation.pdf`](documentation.pdf) – complete report, including the process model, ER diagram, forms, business rules, and execution examples
How to Explore the Project
1. Download and extract camunda7-project.zip.
2. Open the included BPMN model with a Camunda 7-compatible Modeler.
3. Review the BPMN diagram, task configurations, and associated forms.
4. To execute the prototype, use a configured Camunda 7 environment and deploy the model together with its required form resources.
5. Follow the process through Camunda Tasklist. The documentation provides examples of different decision paths.
Note: This is an academic prototype, not a standalone production application. The repository contains the process and form artifacts; running them requires a suitable Camunda 7 environment.

Project Team
- Ivan Nizek
- Valentino Mihalinac
- Mateo Mihalic
Faculty of Organization and Informatics (FOI), University of Zagreb
Year: 2026
