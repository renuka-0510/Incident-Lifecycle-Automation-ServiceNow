# Incident Lifecycle Automation in ServiceNow

## Project Overview

This project demonstrates a complete Incident Management lifecycle automation in ServiceNow.

Service Desk agents can log and classify incidents, leverage knowledge articles for faster resolution, escalate incidents to Level 2 teams, initiate emergency change processes, manage child incidents, and document final resolutions.

The integration between Incident, Change, Knowledge, and SLA modules ensures structured issue management, improved SLA adherence, and better IT service delivery.

---

## Project Objectives

The main objective of this project is to demonstrate an end-to-end Incident Management workflow in ServiceNow, including:

- Incident creation and classification
- Knowledge article integration
- Incident escalation and reassignment
- Multi-team collaboration
- Configuration Item updates
- Emergency change integration
- Child incident creation and management
- Incident resolution
- Knowledge article creation
- SLA tracking

---

## Incident Lifecycle Workflow

The project follows the complete incident lifecycle:

1. Requirement Analysis and Planning
2. Service and Service Offering Creation
3. Incident Record Creation
4. Incident Classification
5. Knowledge Integration
6. Reassignment and Escalation
7. Incident Tracking by Level 2 Team
8. Emergency Change Integration
9. Child Incident Creation
10. Incident Resolution
11. Knowledge Article Creation
12. Final Validation

---

## Key Features Implemented

### 1. Incident Creation

An incident was created for a Corporate VPN connectivity issue.

**Incident:** INC0010001

**Short Description:**
Unable to connect to Corporate VPN from home office.

**Issue Description:**
The user was able to connect previously but later received an authentication error while connecting to the Corporate VPN.

---

### 2. Incident Classification

The incident was classified using:

- Service
- Configuration Item
- Impact
- Urgency
- Priority

This ensures proper categorization and routing of the incident.

---

### 3. Knowledge Integration

ServiceNow Knowledge Management was used to search for relevant knowledge articles.

A knowledge article related to VPN configuration was attached to the incident to assist with troubleshooting and resolution.

---

### 4. Reassignment and Escalation

The incident was reassigned to appropriate users and teams for further investigation.

Watch lists and work note lists were also used to ensure required users could track incident updates and resolution progress.

---

### 5. Configuration Item Update

The Configuration Item was updated from:

**ThinkStation S20**

to:

**PowerEdge**

This reflected the correct infrastructure component involved in the incident.

---

### 6. Change Integration

The incident was temporarily placed On Hold with:

**On Hold Reason:** Awaiting Change

This demonstrated integration between Incident Management and the Change Management process.

---

### 7. Child Incident Management

A child incident was created under the parent incident.

**Child Incident:** INC0010002

**Short Description:**
Unable to connect to Corporate VPN

The child incident was linked to the parent incident and later automatically resolved based on the parent incident resolution.

---

### 8. Incident Resolution

The following resolution details were documented:

**Probable Cause:**

PowerEdge service was suspended and required restart.

**Resolution Code:**

Workaround provided

**Resolution Notes:**

Restarted VPN-SRV-02 service as per emergency change request.

The parent incident was successfully resolved.

---

### 9. Knowledge Article Creation

A new knowledge article was created after resolving the incident.

Knowledge Base:

**IT**

Template:

**Standard**

The knowledge article was linked with the incident for future reference and faster resolution of similar incidents.

---

### 10. SLA Tracking

Task SLAs were monitored through the Related Records section.

The project verified:

- Response SLA tracking
- Resolution SLA tracking
- SLA completion status
- SLA progress visibility

---

## Final Validation

The following items were successfully verified:

- Parent incident state is Resolved
- Child incident state is Resolved
- Activity log shows resolution triggered by the parent incident
- Knowledge article was created and linked
- Child incident relationship is visible
- SLA tracking is visible
- Multi-team collaboration was demonstrated

---

## Technologies Used

- ServiceNow
- Incident Management
- Service Operations Workspace
- Knowledge Management
- Change Management
- Service Level Agreements (SLA)

---

## Skills Demonstrated

- IT Service Management (ITSM)
- Incident Management
- ServiceNow Workspace Navigation
- Knowledge Management
- Change Management Integration
- SLA Monitoring
- Incident Escalation
- Child Incident Management
- Multi-team Collaboration

---

## Conclusion

This project demonstrates a complete Incident Lifecycle Automation workflow in ServiceNow.

The workflow integrates Incident Management, Knowledge Management, Change Management, Child Incident Management, and SLA tracking to provide a structured approach to IT service issue resolution.

The project shows how ServiceNow can help organizations improve incident handling, collaboration, knowledge sharing, SLA compliance, and overall IT service delivery.
