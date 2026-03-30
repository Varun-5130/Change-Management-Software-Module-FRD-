# 📄 Change Management System - FRD (Pharmaceutical Industry)

## 📌 Overview

This repository contains a **Functional Requirement Document (FRD)** for a Change Management System designed for the pharmaceutical industry.

The system ensures **GMP compliance**, maintains **audit trails**, and supports a structured **change lifecycle workflow** from request submission to closure.

---

## 🎯 Objectives

* Ensure compliance with **Good Manufacturing Practices (GMP)**
* Provide **complete traceability** of changes
* Enable **multi-level approval workflows**
* Maintain **audit trails and transparency**

---

## 👥 User Roles

* **Admin** – Manages system configurations and users
* **Requester** – Submits change requests
* **Reviewer** – Performs impact and risk assessment
* **QA Approver** – Approves or rejects changes
* **Auditor** – Reviews audit logs and reports

---

## ⚙️ Key Features

### 🔐 Authentication

* Secure login system
* Role-based access control
* Session timeout handling

### 📝 Change Request Management

* Auto-generated Change ID
* Mandatory fields validation
* Document attachment support
* Edit before submission

### ⚠️ Impact Assessment

* Risk classification (Low, Medium, High)
* Identification of impacted systems/departments

### 🔄 Workflow & Approval

* Multi-level approval process
* Status tracking (Draft → Submitted → Approved → Implemented → Closed)
* Rejection with comments

### 📊 Audit Trail

* Tracks all user actions with timestamps
* Ensures data integrity and traceability

### 🔔 Notifications

* Email alerts for approvals and updates
* Dashboard notifications for pending tasks

### 📜 Compliance

* Electronic signatures
* Audit readiness support

---

## 🔁 Workflow

The system follows a structured workflow:

**Requester → Reviewer → QA Approval → Implementation → Closure**

The workflow diagram is included in the FRD document.

---

## ✅ Acceptance Criteria

* Mandatory fields must be completed before submission
* All approvals must be logged with timestamp and user ID
* Audit logs must be non-editable

---

## 🏃 Sprint Plan (Agile Approach)

### Sprint 1: Authentication & Dashboard

* Login UI
* Role management
* Dashboard setup

### Sprint 2: Change Request Module

* Form UI
* Database schema
* Validation logic

### Sprint 3: Workflow & Approval

* Approval engine
* Status tracking
* Notifications

### Sprint 4: Audit & Testing

* Audit logs
* Compliance validation
* System testing

---

## 🖥️ Mock Screens

* Login Screen
* Dashboard
* Change Request Form
* Approval Screen

---


## 👨‍💻 Author
**Varun S**
