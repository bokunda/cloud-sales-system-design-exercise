# Cloud Sales System - System Design Exercise
This is a solution for the Cloud Sales System Design exercise. 

The focus was on:
- Infrastructural HLA
- Architectural HLA
- Data modeling
- Deep diving into one of the components

## Infrastructural HLA
In requirements, there was a statement that the solution will serve customers in **Europe** and **APAC** (Asia Pacific) regions. 
This means that the focus should be on **multi-region** design.

![Infrastructural HLA Diagram](system-design/CloudSalesSystem.hla.io-Infrastructure-HLA.drawio.png "Infrastructual HLA Diagram")

### Follow the Sun pattern
TODO:

### Auto-Scaling
TODO:

### Database
TODO:

### Logs (Datadog)
TODO:

### Final stack
TODO:

## Architectural HLA
Here, the focus was on service segregation, so all major parts are in separate services. The database is shared between resources.

![Architectural HLA Diagram](system-design/CloudSalesSystem.hla.io-Services-HLA.drawio.png "Architectural HLA Diagram")

### Technical stack
- Amazon API Gateway
- Kubernetes
- Docker
- .NET Web API
- .NET Service Workers
- S3 Buckets
- Amazon Aurora DB
- Datatod

## Deep Dive
TODO:

### Order Service
TODO:

#### Create Order
Creating order is one of the most complex operations in the system so that action is used for the "Deep Dive" part.
![Deep Dive Order Service - Create Order Diagram](system-design/CloudSalesSystem.hla.io-Order-Service-Deep-Dive.drawio.png "Deep Dive Order Service - Create Order Diagram")

## Data Model
![Data Model Diagram](system-design/CludSalesSystem_DB.png "Data Model Diagram")
