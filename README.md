# Customer Complaint Management | Camunda 7
A process-oriented application prototype for handling customer complaints, developed as a team project for the Process-Service Architectures course at the Faculty of Organization and Informatics (FOI), University of Zagreb.
The project demonstrates BPMN 2.0 process modeling, user-task forms, business rules, and workflow execution in Camunda 7.
Project Overview
The process starts when a customer submits a complaint about an order or an individual product. A key account manager reviews and analyzes the request, decides whether to approve, reject, or return it for revision, and proposes a resolution if the complaint is approved.
The customer then decides whether to accept the proposed resolution. Accepted resolutions are implemented and the customer is informed of the outcome.
Process Flow
1. Submit complaint – the customer provides the order number and describes the problem.
2. Receive and analyze – the key account manager records and evaluates the complaint.
3. Decide on the complaint – approve, reject, or request a revision.
4. Handle the decision:
   - Revision: the customer updates the complaint and it returns for review.
   - Rejection: a rejection notice is issued and the process ends.
   - Approval: a resolution is proposed: product replacement, refund, or repair.
5. Customer decision – the customer accepts or rejects the proposed resolution.
6. Complete the process – if accepted, the resolution is carried out and the customer is notified; otherwise, the process ends without implementation.
Process Roles
- Customer: submits and revises complaints; accepts or rejects proposed resolutions.
- Key Account Manager: receives, analyzes, and decides on complaints; proposes and carries out resolutions; informs the customer.
Key Features
- BPMN 2.0 model with 10 activities and 2 decision gateways.
- Camunda forms connected to user tasks.
- Conditional workflow paths for approval, rejection, and revision.
- Complaint linked to one order, concerning an individual product or the entire order.
- Customer approval required before implementing the proposed resolution.
- Supporting entity–relationship (ER) data model and documented business logic.
- Prototype execution demonstrated through Camunda task forms.
Tools and Technologies
- Camunda 7 – workflow modeling and execution
- Camunda Modeler and Form Builder – process and form design
- BPMN 2.0 – business process notation
- Camunda Tasklist – user-task handling
- draw.io – ER data modeling

Viewing and Running the Prototype
1. Download and extract Obraditi reklamaciju.zip.
2. Open the BPMN file in a Camunda 7-compatible modeler and inspect the associated forms.
3. Read the PDF for the process description, ER model, and examples of different execution paths.
4. To run the workflow, deploy the required process and form resources to a configured Camunda 7 environment and complete user tasks through Tasklist.
Note: This is an academic prototype, not a production-ready application. It requires a separately configured Camunda 7 environment for execution.

Project Team
- Ivan Nizek
- Valentino Mihalinac
- Mateo Mihalic
Faculty of Organization and Informatics (FOI), University of Zagreb
Year: 2026
