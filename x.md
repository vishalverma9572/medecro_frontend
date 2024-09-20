

# Table of Contents

1. **Introduction**
   - Introduction about Fusion
   - Purpose of the Module
   - Scope of the Module

2. **Use Case/Actor Description**

3. **Functional Requirements**
   - Use Case Diagram
   - Use Case Description
   - Other Functional Requirements
   - Other Constraints
     - User Interfaces
     - Software (Tech) Stack Used
     - Business Rules (if any)

4. **Non-Functional Requirements**
   - Module Dependencies with Other Fusion Modules
     - UI Level Dependencies
     - DB Level Dependencies
     - Module Level Dependencies

---

## 1. Introduction

This section provides a comprehensive overview of the **Software Requirements Specification (SRS)** document. It outlines the scope and key elements covered, while also presenting the purpose of this document, emphasizing its role in specifying the requirements for the software under consideration.

Additionally, abbreviations and definitions are provided to ensure clarity and understanding. This section serves as a guide for readers, offering a roadmap to navigate the subsequent details and specifications outlined in the SRS document.

### 1.1 Purpose

This document provides a detailed description of the requirements for the **HR-1 module** within the **Fusion** software. Its main purpose is to outline the system's objectives, constraints, and specifications. It serves as a proposal for customer approval and a reference guide for the development team, establishing a shared understanding among stakeholders regarding the envisioned functionalities of the HR-1 module within the Fusion software.

### 1.2 Product Scope

The HR-1 module manages various activities within the broader Fusion system. Some activities are managed by other software, while this module focuses on the following:

- CPDA (Cumulative Professional Development Allowance)
- LTC (Leave Travel Concession)
- Appraisal
- Leave Requests
- Service Record Management (SRM)

---

## 2. Definitions, Acronyms, and Abbreviations

| Term          | Definition                                                                           |
| ------------- | ------------------------------------------------------------------------------------ |
| **User**      | Someone who interacts with the application.                                           |
| **LTC**       | Leave Travel Concession                                                              |
| **CPDA**      | Cumulative Professional Development Allowance                                        |
| **Appraisal** | A formal assessment of the performance of an employee over a particular period.       |
| **Faculty**   | Teaching or research staff of university departments                                 |
| **Staff**     | Employees of the organization.                                                       |
| **Director**  | The person in charge of the organization.                                             |
| **Dealing Asstt.** | Responsible for managing receipts.                                             |
| **HOD**       | Head of Department                                                                   |
| **AR**        | Assistant Registrar                                                                  |
| **DR**        | Deputy Registrar                                                                     |
| **Stakeholder** | Anyone interacting with the system who is not a developer.                         |
| **Registrar** | Official responsible for keeping records.                                             |
| **SRM**       | Service Record Management                                                            |
| **SRS**       | Software Requirements Specification                                                  |
| **SR**        | Service Record                                                                       |
| **Admin**     | Assigns reviewers to applications.                                                   |

---

## 3. User/Actor Description

Three types of users interact with the system: **Faculty/Staff**, **HR Admin**, and **Approval Authorities** (Director/Registrar, HOD, Accountant). Each has different interactions and requirements.

### 3.1 Faculty/Staff

Faculty/Staff interact with the system to initiate various requests such as **Appraisal**, **CPDA**, **LTC**, **Leave Requests**, and **View Service Records**.

- **Role**: Applicants in submission processes for appraisal assessments, professional development activities, leave travel concessions, leave requests, and service record viewing.
- **General Functionalities**:
  - Log in to access respective functionalities.
  - Click on the relevant option (Appraisal, CPDA, LTC, Leave Request, View SR) to access the form.
  - Fill in the details and submit the form.
  - View requests page with a "Pending" status.

### 3.2 HR Admin

The HR Admin manages applications and service records for employees.

- **Role**: Assigns reviewers to applications and manages service records.
- **General Functionalities**:
  - Log in to access administrative functions.
  - Assign reviewers to applications by filling out a form.
  - Manage the list of application requests.
  - Manage and update employee service records.

### 3.3 Director/Registrar

The Director/Registrar reviews and approves/rejects requests for LTC and CPDA and can view service records of any employee.

- **Role**: Reviews LTC and CPDA requests.
- **General Functionalities**:
  - Log in to access respective functionalities.
  - View and process requests for approval or rejection.
  - View the status and remarks on profiles.

> Note: The Director manages requests from faculty, and the Registrar manages requests from staff.

### 3.4 HOD

The HOD handles the approval of **CPDA**, **LTC**, **Appraisal**, and **Leave Requests**.

- **General Functionalities**:
  - View request list.
  - Approve/Reject requests.
  - Forward approved CPDA applications to the Estt. Section.

### 3.5 Accountant

The Accountant manages audits, updates, and reconciles financial transactions related to LTC and CPDA.

- **Role**: Ensures accuracy and compliance with financial records.
- **General Functionalities**:
  - Conduct financial audits and implement corrective actions.
  - Record and update financial transactions.

---

## 4. Functional Requirements

### 4.1 Use Case Diagram
*(Placeholder for the use case diagram)*

### 4.2 Use Case Description
*(Placeholder for detailed use case descriptions)*

### 4.3 Other Functional Requirements
- User Interfaces for each actor.
- Tech Stack: Node.js, React, Django, PostgreSQL.
- Business Rules: Approvals and role-based restrictions.

---

## 5. Non-Functional Requirements

### 5.1 Module Dependencies

#### UI Level Dependencies
- Integration with common UI components of Fusion.

#### DB Level Dependencies
- Dependencies on shared databases for employee records.

#### Module Level Dependencies
- Integration with other HR and administration modules in the Fusion system.

---

