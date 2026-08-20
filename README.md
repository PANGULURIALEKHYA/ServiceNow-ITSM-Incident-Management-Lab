# ServiceNow ITSM Incident Management Lab

| **Title** | **ServiceNow ITSM Incident Management Lab** |
|---|---|
| **Description** | Hands-on ITSM project demonstrating incident management, SLA tracking, knowledge management, escalation workflows, and operational reporting using ServiceNow. |
| **Author** | Alekhya Panguluri |

---

# Introduction

This project demonstrates hands-on experience with ServiceNow IT Service Management (ITSM) workflows in a ServiceNow Developer Instance.

The lab simulates common enterprise IT support activities, including incident creation, categorization, prioritization, assignment, troubleshooting, resolution, SLA monitoring, knowledge management, incident escalation, and operational reporting.

---

# Skills Used

- ServiceNow ITSM
- Incident Management
- Incident Lifecycle Management
- Incident Categorization
- Impact and Urgency Assessment
- Priority Management
- Assignment Groups
- Incident Troubleshooting
- Work Notes and Documentation
- Incident Resolution
- Incident Reopening and Escalation
- SLA Monitoring
- Knowledge Management
- Knowledge Base Creation
- ServiceNow Reporting

---

# Project Objectives

The main objectives of this lab were to:

- Understand the complete incident management lifecycle
- Create and manage realistic IT support incidents
- Categorize incidents based on the reported issue
- Determine priority using impact and urgency
- Assign incidents to appropriate support teams
- Document troubleshooting activities using work notes
- Resolve incidents and document resolution information
- Reopen and escalate recurring incidents
- Monitor Service Level Agreements (SLAs)
- Create reusable Knowledge Base documentation
- Generate operational incident reports

---

# Lab Environment

| **Component** | **Details** |
|---|---|
| Platform | ServiceNow |
| Environment | ServiceNow Developer Instance |
| Primary Module | Incident Management |
| Additional Modules | Knowledge Management, SLA Management, Reporting |
| Project Type | Hands-on ITSM Administration Lab |

---

# Incident Scenarios

Five realistic IT support incidents were used during the project:

| **Incident** | **Scenario** | **Category** |
|---|---|---|
| INC0010001 | Unable to connect to corporate VPN | Network |
| INC0010002 | Employee account locked after multiple failed login attempts | Password Reset |
| INC0010003 | Microsoft Outlook fails to open on employee laptop | Software |
| INC0010004 | Unable to access internal company website | Network |
| INC0010005 | Employee laptop is not connecting to external monitor | Hardware |

These scenarios provided hands-on practice with different categories, priorities, assignment groups, troubleshooting procedures, and resolutions.

---

# Incident Management

The complete incident management workflow was practiced during the lab.

Activities included:

- Recording caller information
- Creating short and detailed incident descriptions
- Selecting categories and subcategories
- Setting impact and urgency
- Reviewing calculated priority
- Selecting assignment groups
- Assigning incidents to technicians
- Recording troubleshooting activities
- Updating incident states
- Documenting resolution information
- Confirming restoration of service

---

# VPN Incident Investigation and Resolution

A corporate VPN connectivity incident was used to demonstrate the complete incident lifecycle.

The incident was categorized as a **Network / VPN** issue and assigned to the Network support team.

Troubleshooting identified cached VPN credentials as the issue.

The cached credentials were cleared and the user re-authenticated using the current account password. The VPN connection was successfully restored and access to internal company resources was confirmed.

---

# Incident Resolution

Resolution information was documented directly within the incident record.

The resolution process included:

- Selecting the appropriate resolution code
- Recording detailed resolution notes
- Identifying the resolver
- Recording the resolution timestamp
- Confirming successful service restoration

This demonstrates the importance of maintaining accurate incident history and resolution documentation.

---

# Incident Reopening and Escalation

The Microsoft Outlook incident was used to simulate a recurring technical problem.

After the initial resolution, the issue returned and the incident was reopened.

The incident was then:

- Returned to an active state
- Reassigned from the Help Desk to the Software support group
- Assigned to a Software support technician
- Updated with escalation work notes
- Continued for further investigation

This demonstrates an escalation workflow when first-line troubleshooting does not permanently resolve an issue.

---

# SLA Management

Service Level Agreement information was reviewed for incident records.

The SLA information included:

- SLA definition
- Target
- Stage
- Business time remaining
- Business elapsed time
- Business elapsed percentage
- Start time
- Stop time

This demonstrates how support teams use ServiceNow to monitor incidents against defined service targets.

---

# Knowledge Management

A Knowledge Base article was created for:

## Troubleshooting Corporate VPN Connection Issues

The article contains:

- Purpose
- Symptoms
- Troubleshooting steps
- Resolution guidance
- Escalation instructions

Creating reusable knowledge documentation helps support teams resolve recurring incidents consistently and efficiently.

---

# Operational Reporting

Three ServiceNow reports were created to analyze incident data.

### Incidents by Category

A report was created to visualize incident distribution across categories such as Software, Hardware, Network, Password Reset, Database, and Inquiry / Help.

### Incidents by Priority

A report was created to analyze incident volume according to priority levels.

### Incidents by State

A report was created to analyze incidents across lifecycle states including New, In Progress, On Hold, Resolved, and Closed.

These reports demonstrate how incident data can be transformed into useful operational information.

---

# Project Evidence

The `screenshots` folder contains evidence captured during the hands-on lab, including:

1. Incident Management Overview
2. VPN Incident Details
3. VPN Incident Resolution
4. VPN Troubleshooting Knowledge Article
5. Priority 3 Resolution SLA
6. Reopened and Escalated Incident
7. Escalation Work Notes
8. Incidents by Category Report
9. Incidents by Priority Report
10. Incidents by State Report

---

# Repository Structure

```text
ServiceNow-ITSM-Incident-Management-Lab/
│
├── README.md
│
├── docs/
│   ├── README.md
│   └── ServiceNow_ITSM_Incident_Management_Project_Report.pdf
│
└── screenshots/
    ├── README.md
    ├── 01-Incident-Management-Overview
    ├── 02-VPN-Incident-Details
    ├── 03-VPN-Incident-Resolution
    ├── 04-Knowledge-Article-VPN-Troubleshooting
    ├── 05-Task-SLA-Priority3-Resolution
    ├── 06-Incident-Reopened-Escalated
    ├── 07-Escalation-Work-Notes
    ├── 08-Incidents-by-Category-Report
    ├── 09-Incidents-by-Priority-Report
    └── 10-Incidents-by-State-Report
