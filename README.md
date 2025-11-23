# Hospital-system

![Uploading image.png…](https://www.bing.com/th/id/OIP.yTPvVIru55w__ORYni4WygHaEK?w=228&h=211&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2)

## The Analysis Phase in Software Development

| Step | Description |
|------|-------------|
| Requirement Gathering | Collect all functional and non-functional requirements from stakeholders. |
| Requirement Analysis | Study, clarify, and refine requirements to ensure they are complete and feasible. |
| Feasibility Study | Evaluate technical, financial, and operational feasibility of the project. |
| System Modeling | Create diagrams (DFD, use cases, ERD) to visualize system behavior and data flow. |
| Requirement Documentation | Prepare SRS (Software Requirements Specification) as a formal record of requirements. |
| Validation & Review | Review requirements with users and stakeholders to confirm accuracy and completeness. |

## Product Backlog Development – Hospital System (Short Table)

| Topic                                | Description |
|-------------------------------------|-------------|
| What is a Product Backlog?          | A prioritized list of all features, enhancements, and requirements needed for the hospital system. |
| Purpose of Product Backlog          | Helps the team understand what to build, in what order, and why; ensures transparency and alignment. |
| How to Create a Backlog             | Identify user needs, gather requirements, write user stories, define priorities, and estimate effort. |
| Structuring the Backlog             | Organize items by epics, user stories, priority, business value, and dependencies. |
| Prioritization Techniques           | MoSCoW (Must/Should/Could/Won’t), Value vs. Effort, Kano Model, WSJF (Weighted Shortest Job First). |
| Backlog Refinement                  | Regularly updating, splitting stories, improving clarity, and re-estimating based on feedback. |
| Maintenance Importance              | Ensures backlog stays accurate, manageable, and aligned with hospital workflow needs. |

# Hospital System User Stories

| ID  | User Story                                                                 | Priority | Story Points | Acceptance Criteria                                                                 |
|-----|---------------------------------------------------------------------------|---------|--------------|------------------------------------------------------------------------------------|
| US1 | As a patient, I want to register online, so that I can book appointments. | High    | 5            | Patient can create an account and log in successfully.                             |
| US2 | As a patient, I want to book an appointment, so that I can see a doctor. | High    | 8            | Patient can select doctor, date, and time; receives confirmation notification.     |
| US3 | As a doctor, I want to view my schedule, so that I can manage appointments. | High | 5            | Doctor can see all upcoming appointments with patient details.                     |
| US4 | As a nurse, I want to update patient vitals, so that medical records stay current. | Medium | 3         | Nurse can record vitals for a patient and save them in the system.                 |
| US5 | As an admin, I want to manage staff accounts, so that the hospital database is accurate. | Medium | 5        | Admin can add, edit, or remove staff accounts.                                     |
| US6 | As a patient, I want to view my medical history, so that I can track my treatments. | High  | 5           | Patient can see past appointments, diagnoses, and prescriptions.                   |
| US7 | As a doctor, I want to add prescriptions, so that patients can get medications. | High  | 5           | Doctor can add prescriptions linked to a patient’s profile.                        |
| US8 | As a patient, I want to receive appointment reminders, so that I don’t miss visits. | Medium | 3          | Patient receives email/SMS reminders before appointments.                           |
| US9 | As an admin, I want to generate reports, so that hospital performance can be tracked. | Medium | 8          | Admin can generate daily, weekly, and monthly reports for patients and staff.      |
| US10| As a patient, I want to pay bills online, so that I can avoid long queues. | High    | 5            | Patient can pay invoices securely using multiple payment options.                  |
| US11| As a lab technician, I want to upload test results, so that doctors and patients can access them. | Medium | 5       | Lab results are uploaded and linked to the correct patient profile.                |
| US12| As a patient, I want to download test results, so that I can share them with other doctors. | Medium | 3       | Patient can download lab reports in PDF format.                                     |
| US13| As a receptionist, I want to check-in patients, so that appointment workflow is smooth. | High  | 3           | Receptionist can mark patients as arrived and update appointment status.           |

## Weighting and Estimation – Hospital System

| User Story ID | User Story Description                                      | Complexity (1-5) | Priority (High/Medium/Low) | Business Value (1-5) | Story Points |
|---------------|------------------------------------------------------------|-----------------|---------------------------|---------------------|--------------|
| US001         | As a doctor, I want to view patient medical history so that I can provide accurate treatment. | 3               | High                      | 5                   | 8            |
| US002         | As a nurse, I want to record patient vitals so that doctors can monitor their health.      | 2               | High                      | 4                   | 5            |
| US003         | As an admin, I want to manage doctor schedules so that appointments are organized.        | 3               | Medium                    | 3                   | 5            |
| US004         | As a patient, I want to book appointments online so that I can avoid waiting in queues.   | 2               | High                      | 4                   | 3            |
| US005         | As a lab technician, I want to upload test results so that patients and doctors can access them. | 3        | Medium                    | 4                   | 5            |
| US006         | As an admin, I want to generate billing reports so that financial management is easier.   | 4               | Medium                    | 3                   | 8            |
| US007         | As a patient, I want to receive reminders for my appointments so that I don’t forget them.| 2               | Low                       | 3                   | 3            |
| US008         | As a doctor, I want to prescribe medications electronically so that pharmacy processing is faster. | 3       | High                      | 5                   | 5            |
| US009         | As a nurse, I want to track patient medication schedules so that doses are not missed.   | 2               | Medium                    | 4                   | 3            |
| US010         | As an admin, I want to manage hospital inventory so that supplies are always available.   | 4               | High                      | 4                   | 8            |

**Notes:**  
- **Complexity:** 1 = very simple, 5 = very complex  
- **Business Value:** 1 = low, 5 = high  
- **Story Points:** Weighted based on complexity, priority, and business value  
