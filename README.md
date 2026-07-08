# 🏥 Centralized GP Referral Management System (CRMS)

> **End-to-End Business Analysis & Hybrid SDLC Portfolio Case Study**
>
> **Status:** 🟢 Final Draft for Deployment
> **Domain:** HealthTech / Clinical Workflow Automation / Enterprise Systems
> **Market Context:** Australian Healthcare System 

> **Author:** Hoang Nguyen Duy Anh — Business Analyst

---

<p align="center">
  <img src="https://img.shields.io/badge/Role-Business%20Analyst-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Enterprise%20Systems%20%26%20Interoperability-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Methodology-Hybrid%20%28Waterfall%20%2B%20Agile%29-orange?style=for-the-badge" />
</p>

## 📌 Executive Summary

The **Centralized GP Referral Management System (CRMS)** is an enterprise-grade digital ecosystem architected for a large-scale hospital network (comprising 4 major hospitals, 16,000 medical staff, and approximately 1,000 beds). The system systematically eradicates the operational inefficiencies of manual General Practitioner (GP) referral workflows into specialized hospital clinical pathways.

This repository serves as a **professional Business Analysis portfolio artifact**. It was independently designed to demonstrate a comprehensive BA skillset across the entire Software Development Life Cycle (SDLC)—from initial problem diagnosis and stakeholder governance to advanced process modeling, formal requirements specification (BRD/FR/NFR), and end-to-end traceability mapping.

### 🎯 Process Transformation: As-Is vs. To-Be

| ⛔ Current State (The Problem) | ✅ Future State (The CRMS Solution) |
| :--- | :--- |
| **Manual & Fragmented Referrals:** GPs rely on handwritten forms, faxes, or isolated emails with non-standardized clinical data. | **Digital e-Referral Portal:** Mandatory data validation and structured input fields ensuring complete clinical datasets prior to submission. |
| **Overloading & Duplicate Triaging:** Cross-hospital duplicate submissions inflate waiting lists, leading to uneven hospital resource utilization. | **Automated Allocation Engine:** Real-time capacity scanning and routing recommendations matched to hospital workload under 5 seconds. |
| **Untraceable Referral Status:** Complete lack of visibility for both GPs and patients post-submission, requiring tedious manual follow-up calls. | **Real-Time Transparency:** 100% end-to-end status tracking via unique transaction IDs with instant automated SMS/Email notifications. |
| **Data Governance Risks:** Decentralized patient records maintained in local Excel sheets, lacking audit logs and formal encryption. | **Healthcare-Grade Security:** Strict PHI data encryption in transit and at rest, backed by immutable, non-modifiable system Audit Logs. |

---

## 🏗️ Project Artifacts & Deliverables

The business analysis documentation pack is structured according to international professional standards across the project lifecycle:

### 📘 1. Problem Statement & Planning
* **Macro Context:** Optimizing operational efficiency within the Australian healthcare network by leveraging IT infrastructure to reduce costs and enhance patient care delivery.
* **Hybrid Delivery Framework:**
  * *Requirements Inception & System Architecture:* Managed via **Waterfall** methodology to freeze cross-hospital data structures and ensure absolute compliance with **HL7/FHIR** interoperability and data security guidelines.
  * *Solution Implementation:* Driven via **Agile/Scrum** to break down the product backlog (GP Portal, Core Engine, Dashboard) into iterative 2-week sprints for continuous UI/UX optimization based on clinical user testing feedback.
* **Stakeholder Governance:**
  * **RACI Matrix:** Explicit mapping of Responsibility (R) and Accountability (A) across GPs, Patients, Specialty Coordinators (SCs), and System Administrators.
  * **Stakeholder Engagement Log:** Deep-dive analysis profiling core operational pain points, functional needs, and targeted system improvements.

### 🧩 2. Requirements Analysis & Process Modelling
* **Business Objectives (BO):** Quantitative definition of 4 core pillars (95% automated triage compliance, 100% real-time tracking interface, 99.9% data linkage accuracy, and <48-hour end-to-end response times).
* **Business Rules (BR):** Rigid operational rules governing referral validity, PHI protection, immutable logs, and a sophisticated **Master Patient Index (MPI) Algorithm** utilizing specific confidence score thresholds: automated linkage (>95%), manual matching review queue (80% - 95%), or new identity creation (<80%).
* **Functional & Non-Functional Requirements (FR/NFR):** Rigorous technical specifications detailing system behaviors (e.g., 2-day SLA escalation alerts, page load times < 2.0s under a concurrent load of 2,000 users, and a 99.9% system uptime SLA).
* **Transition Requirements (TR):** A comprehensive organizational change management plan covering micro-learning materials (<3 min video tutorials), a parallel running deployment phase to mitigate operational downtime risks, and a 24/7 dedicated hypercare support team during the initial 4-week go-live window.
* **Process Modelling (BPMN):** Detailed current state (**As-Is Process Flow**) and future optimized state (**To-Be Process Flow**) maps highlighting administrative bottleneck elimination.

### 📝 3. Agile Artifacts (User Stories & Acceptance Criteria)
* **User Stories:** 9 standardized agile user stories representing target personas across GPs, Specialty Coordinators (SCs), and Patients.
* **Acceptance Criteria (Gherkin Format):** Rigorous `Given - When - Then` scenarios establishing clear definitions of done (DoD) for automated error validation flags, auto-save drafts, live real-time status updates, and history log query filtering.

### 📊 4. Requirements Traceability Matrix (RTM)
* A comprehensive, end-to-end matrix linking **Business Requirements ➔ Functional/Non-Functional Requirements ➔ Transition Requirements ➔ Test Cases**. This artifact guarantees zero requirement leakage and ensures every business scope item is formally validated with assigned technical priorities.

### 🧪 5. Solution Implementation & Evaluation
* **Pilot Implementation Strategy:** A controlled, lean 1-week deployment plan (Monday through Saturday) engaging a representative user cohort: 10 active GPs, 2 Senior Specialty Coordinators, and a dedicated IT Hypercare team to capture real-world operational insights.
* **UAT Test Cases (TC001 - TC009):** Meticulously designed user acceptance test scripts detailing pre-conditions, procedural execution steps, and precise expected results for status transitions, capacity allocation routing, system audit trails, data input validations, and a Mock Clock framework to test escalation alert triggers.
