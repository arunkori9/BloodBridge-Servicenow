# 🩸 BloodBridge – Bridging Donors, Hospitals & Patients

BloodBridge is a low-code healthcare workflow application developed using the ServiceNow platform.

The application is designed to help connect blood donors, hospitals, and patients through centralized records, workflow automation, donor matching, and notifications.

---

## 📌 Problem Statement

Finding a suitable blood donor during an emergency can be time-consuming and difficult.

Hospitals may depend on manual communication and existing records to identify suitable donors. BloodBridge aims to provide a centralized system for managing donor information and blood requests.

---

## ✅ Solution Overview

BloodBridge provides a centralized ServiceNow-based application for managing blood donation requests and donor information.

### Key Capabilities

- Donor registration
- Blood group information management
- Blood request creation
- Donor and request matching
- Request tracking
- Workflow-based processing
- Notifications
- Role-based access

---

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Platform | ServiceNow |
| Application Development | App Engine Studio |
| Workflow Automation | Flow Designer |
| Database | ServiceNow Tables |
| User Interface | ServiceNow UI |
| Notifications | ServiceNow Notifications |
| Access Control | Roles & Policies |

---

## 🗂️ Data Model

| Table / Data | Purpose |
|---|---|
| Donor | Stores donor information and blood group |
| Hospital | Stores hospital/requester information |
| Blood Request | Stores blood requirement details |
| Match / Request Status | Tracks donor matching and request progress |

---

## 🔄 Workflow

A typical workflow can be represented as:

**Hospital / Patient**  
↓  
**Creates Blood Request**  
↓  
**System checks donor information**  
↓  
**Matching donor identified**  
↓  
**Request processed**  
↓  
**Notification sent**  
↓  
**Donor / Hospital informed**

---

## 👥 Roles & Access

| Role | Responsibilities |
|---|---|
| Admin | Manage application records and workflows |
| Hospital | Create and track blood requests |
| Donor | Maintain donor information and availability |

---

## 📊 Key Features

- 🩸 Donor information management
- 🏥 Hospital request management
- 🔍 Blood group-based donor matching
- 🔄 Workflow automation
- 📧 Notification support
- 📋 Centralized record management
- 🔐 Role-based access
- 📊 Request status tracking

---

## 🔮 Future Enhancements

- Live donor location using Maps APIs
- SMS notification support
- Mobile-friendly interface
- Urgency-based request prioritization
- Donor eligibility verification
- Improved donor availability tracking
- Reports and dashboards

---

## 👨‍💻 Developed By

**Arun Kori**

B.Tech – CSE

---

## 📌 Project Note

This project was developed as a low-code application using the ServiceNow platform.

The ServiceNow application, tables, forms, workflows, and configurations are maintained within the ServiceNow environment. This GitHub repository is primarily intended to provide project documentation and an overview of the application.

No traditional frontend/backend source code is stored in this repository.
