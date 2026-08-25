# ServiceNow Incident Lifecycle Automation

## Project Overview

This project demonstrates an end-to-end **Incident Management lifecycle in ServiceNow** using Service Operations Workspace.

The project focuses on automating and standardizing the incident-handling process, from incident creation and classification to escalation, knowledge integration, SLA tracking, emergency change management, child-incident management, and final resolution.

The primary scenario used in this project is a **Corporate VPN connectivity issue** reported by a user working from home.

---

##  Project Objectives

* Create and classify incidents in ServiceNow.
* Configure and manage a Corporate VPN service offering.
* Integrate Knowledge Management for troubleshooting guidance.
* Reassign and escalate incidents to appropriate support teams.
* Track incidents through Level 2 investigation.
* Create and manage emergency change requests when required.
* Create and manage related child incidents.
* Track response and resolution SLAs.
* Generate Knowledge Articles from resolved incidents.
* Maintain complete activity history and resolution documentation.

---

## ServiceNow Capabilities Used

* Service Operations Workspace
* Incident Management
* Incident Classification and Prioritization
* Assignment and Escalation
* Knowledge Management
* Agent Assist / Knowledge Integration
* Change Management
* Emergency Change Management
* Child Incident Management
* Related Records
* Task SLA Tracking
* Incident Resolution and Activity Auditing

---

## Incident Lifecycle

The project follows the following implementation flow:

1. Requirement Analysis & Planning
2. Create New Service and Service Offering
3. Incident Record Creation
4. Incident Classification
5. Knowledge Integration
6. Reassignment & Escalation
7. Incident Tracking by Level 2
8. Emergency Change Request Creation
9. Incident Resolution
10. Knowledge Creation
11. SLA & Related Record Validation
12. Testing & Deployment

---

## Primary Incident Scenario

**Incident:** INC00100004
**Issue:** Unable to connect to Corporate VPN from home office

The incident demonstrates a complete workflow including:

* Incident creation
* Classification and prioritization
* Assignment to support teams
* Knowledge-based troubleshooting
* Level 2 investigation
* Related child incident
* Emergency change integration
* On Hold state with **Awaiting Change**
* Incident resolution
* Knowledge creation
* SLA validation

---

##  Key Implementation Areas

### 1. Service & Service Offering

A **Corporate VPN** service offering was configured under **Remote Access** with the required operational and business-criticality settings.

### 2. Incident Creation

A VPN connectivity incident was created with structured information including the caller, service, description, assignment details, and SLA information.

### 3. Classification & Escalation

The incident was classified using impact, urgency, priority, category, service, and configuration-item information. Assignment and escalation activities were tracked through the activity history.

### 4. Knowledge Integration

Knowledge guidance was integrated into the incident-handling process to support troubleshooting. The project also demonstrates creating a reusable Knowledge Article from the incident.

### 5. Level 2 Investigation

The incident was tracked through Level 2 support using assignment information, activity history, configuration-item context, and related records.

### 6. Emergency Change Management

When an emergency change was required, the incident was placed **On Hold** with the reason **Awaiting Change**. The corrective action was documented in the resolution history.

### 7. Child Incident Management

A related child incident, **INC00100005**, was created and resolved based on the parent incident resolution.

### 8. SLA Validation

Task SLA records were validated through Related Records to verify response and resolution tracking.

---

## Testing & Validation

The following areas were validated during testing:

| Test Area                | Validation                           |
| ------------------------ | ------------------------------------ |
| Incident Lifecycle       | State transitions and resolution     |
| Escalation               | Ownership and support-team changes   |
| Change Integration       | Emergency change related to incident |
| Knowledge Creation       | Article created and visible          |
| Child Incidents          | Child incident linked and resolved   |
| SLA Tracking             | Response and resolution SLAs visible |
| Multi-Team Collaboration | Activities traceable across teams    |

---

## Results

The project successfully demonstrates:

* Structured incident creation and classification.
* Service and service-offering configuration.
* Knowledge integration for troubleshooting.
* Assignment and escalation across support teams.
* Emergency change integration.
* Parent and child incident management.
* Incident resolution and activity tracking.
* Knowledge Article creation.
* SLA visibility and validation.
* End-to-end incident lifecycle testing.

---

## Project Documentation

Detailed implementation steps, screenshots, validation evidence, and results are available in:

[View Project Documentation](./ServiceNow_Incident_Lifecycle_Automation_Documentation.pdf)

---

## Skills Demonstrated

* ServiceNow Incident Management
* Service Operations Workspace
* Incident Classification & Prioritization
* Assignment & Escalation
* Knowledge Integration
* Knowledge Article Creation
* Change Management Integration
* Child Incident Management
* Related Lists & Task Relationships
* SLA Tracking & Validation
* Incident Resolution
* Activity Auditing
* End-to-End Workflow Testing

---

## Project Author

**Uppugandla Manjeera**

**Project:** Incident Lifecycle Automation in ServiceNow
