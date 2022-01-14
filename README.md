# SNOW-ITIL
https://www.servicenow.com/products/itsm/what-is-itil.html
https://docs.servicenow.com/bundle/rome-servicenow-platform/page/product/configuration-management/concept/c_ITIL.html

ITIL (acronym for Information Technology Infrastructure Library) is a set of detailed practices for IT service management (ITSM) that focuses on aligning IT services with the needs of business.

-Developed in 1980s in UK in response to growing dependence on IT.
-Systematic approach to high quality IT Service Delivery.
-Public Body for the knowledge of Service Management best practices.
-Helps organizations to improve service levels and reduce the cost of IT operations.
-A framework, defining ten interlocking processes for Service Support and Service Delivery.

![image](https://user-images.githubusercontent.com/12488769/148669005-56f28cdf-fbd2-4d8c-a277-40db21c46f83.png)

![image](https://user-images.githubusercontent.com/12488769/148669009-90f69911-e50e-4496-86bd-9d1715673799.png)

## Roles
Roles: are defined as collections of specific responsibilities and privileges. Roles may be held by individuals or teams. Individuals and teams may hold more than one role.

ITIL emphasizes a number of standard roles include, most importantly:
Service Owner: Accountable for the overall design, performance, integration, improvement and management of a single service.
Process Owner: Accountable for the overall design, performance, integration, improvement and management of a single process.
Service Manager: Accountable for the development, performance and  improvement of all service in a environment.
Product Manager: Accountable for the development, performance and  improvement of the entire product.

## The Service Lifecycle
Service Strategy
Strategy generation
Financial management
Service portfolio management
Demand management

Service Design
Capacity, Availability, Info Security Management
Service level & Supplier Management

Service Transition
Planning & Support
Release & Deployment
Asset & Config management
Change management
Knowledge Management

Service Operation
Problem & Incident management
Request fulfilment
Event & Access management

Continual Service Improvement
Service measurement & reporting
7-step improvement process


![image](https://user-images.githubusercontent.com/12488769/148669044-3f961208-df04-4309-a398-f1c58251e1dc.png)

## Service Strategy
What are we going to provide?
Can we afford it?
Can we provide enough of it?
How do we gain competitive advantage?
Perspective
Vision, mission and strategic goals
Position
Plan
Pattern
Must fit organisational culture

## Service Strategy 4 activities
![image](https://user-images.githubusercontent.com/12488769/148669060-9190680f-f9d4-4829-b6d5-fbe07789cc6c.png)

## Service Assets
Resources
Things you buy or pay for
IT Infrastructure, people, money


Capabilities
Things you grow
Ability to carry out an activity
Transform resources into Services

## Demand 
Ensures we don’t waste money with excess capacity
Ensures we have enough capacity to meet demand at agreed quality


## How are we going to provide it
How are we going to provide it?
How are we going to build it?
How are we going to test it?
How are we going to deploy it?
![image](https://user-images.githubusercontent.com/12488769/148669124-8df6106e-7505-4c50-8b46-83a202f08913.png)


## Processes in service design
Availability Management
Capacity Management
ITSCM (disaster recovery)
Supplier Management
Service Level Management
Information Security Management
Service Catalogue Management
![image](https://user-images.githubusercontent.com/12488769/148669146-3d8967bd-22d1-4ca9-9b59-2b55cf433fb4.png)

## Service level management
Agreements

Service Level Agreements (Service Provider and Customer)
Operational Level Agreements (Internal between two teams)
Underpinning Contracts (Vendor and Service Provider)

Success of SLM (KPIs)
How many services have SLAs?
How does the number of breaches of SLA change over time (we hope it reduces!)?

## SLA may have
![image](https://user-images.githubusercontent.com/12488769/148669170-6d55fda7-e71e-4af3-a99a-483bd72c123c.png)

## Capacity, time, cost
= This is capacity management
- Balances Cost against Capacity so minimises costs while maintaining  quality of service

## ITSCM
- IT Service Continuity Management
= Ensures resumption of services within agreed timescale
= Business Impact Analysis informs decisions about resources
E.g. Stock Exchange can’t afford 5 minutes downtime but 2 hours downtime probably wont badly affect a departmental accounts office.

### Information Security Management
- Confidentiality
Making sure only those authorised can see data
= Integrity
Making sure the data is accurate and not corrupted
= Availability
Making sure data is supplied when it is requested

## Service Transition
- Build
- Deployment
- Testing
- User acceptance
- Bed-in

## Good service transition
- Set customer expectations
- Enable release integration
- Reduce performance variation
- Document and reduce known errors
- Minimise risk
- Ensure proper use of services

## Change Management and Types
Change Management helps organizations understand and work minimize risks of changes to the IT environment. It is essentially a process for managing the people-side of change. 

- Normal
Non-urgent, requires approval
- Standard
Non-urgent, follows established path, no approval needed
- Emergency
Requires approval but too urgent for normal procedure

## Change Advisory Board
- Change Manager (VITAL)
- One or more of
* Customer/User
* User Manager
* Developer/Maintainer
* Expert/Consultant
* Contractor
- CAB considers the 7 Rs
Who RAISED?, REASON, RETURN, RISKS, RESOURCES, RESPONSIBLE, RELATIONSHIPS to other changes

## Release management
- Release is a collection of authorised and tested changes ready for deployment
- A rollout introduces a release into the live environment
- Full Release
e.g. Office 2007
- Delta (partial) release
e.g. Windows Update
- Package
e.g. Windows Service Pack

## Phased or Big Bang
- Phased release is less painful but more work
- Deploy can be manual or automatic
= Automatic can be push or pull
- Release Manager will produce a release policy

## Service Operation
- Incident Management
- Problem Management
- Event Management
- Request Fulfilment
- Access Management

## Service Operation Functions
- Service Desk
- Technical Management
- IT Operations Management
- Applications Management

## Incident management
- Deals with unplanned interruptions to IT Services or reductions in their quality
- Failure of a configuration item that has not impacted a service is also an incident (e.g. Disk in RAID failure)
- Reported by:
* Users
* Technical Staff
* Monitoring Tools

## Event Management
3 Types of events
- Information
- Warning
- Exception
Can we give examples?
Need to make sense of events and have appropriate control actions planned and documented

## Problem Management
- Aims to prevent problems and resulting incidents
= Minimises impact of unavoidable incidents
= Eliminates recurring incidents
- Proactive Problem Management
* Identifies areas of potential weakness
* Identifies workarounds
- Reactive Problem Management
* Indentifies underlying causes of incidents
* Identifies changes to prevent recurrence

## Access Management
### Right things for right users at right time

### Concepts
- Access
- Identity (Authentication, AuthN)
- Rights (Authorisation, AuthZ)
- Service Group
- Directory

## Service Desk
### Local, Central or Virtual
### Examples?
### Single point of contact
### Skills for operators
- Customer Focus
- Articulate
- Interpersonal Skills (patient!)
- Understand Business
- Methodical/Analytical
- Technical knowledge
- Multi-lingual
### Service Desk often seen as the bottom of the pile
- Bust most visible to customers so important to get right!

## Continual Service Improvement
- Focus on Process owners and Service Owners
- Ensures that service management processes continue to support the business
- Monitor and enhance Service Level Achievements
- PDCA (Plan – Do – Check – Act)

## Service Measurement
### Technology (components, MTBF etc)
### Process (KPIs  - Critical Success Factors)
### Service (End-to end, e.g. Customer Satisfaction)
### Why?
- Validation – Soundness of decisions
- Direction – of future activities
- Justify – provide factual evidence
- Intervene – when changes or corrections are needed











