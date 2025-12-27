# Automated Network Request Management System

## 📌 Project Overview
The **Automated Network Request Management System** is a ServiceNow-based solution designed to modernize the lifecycle of network service requests by replacing manual workflows with digital automation. By leveraging the Service Catalog for centralized intake and Flow Designer for orchestration, the project streamlines approval and fulfillment processes. This system enhances operational efficiency and governance by providing real-time visibility, automated SLA tracking, and a transparent audit trail for all network operations.

## 🚀 Problem Statement
Prior to this implementation, network requests were handled manually via emails or spreadsheets. This led to:
* High turnaround times for service fulfillment.
* Lack of transparency regarding request status.
* Increased risk of human error and data inconsistency.
* Difficulty in auditing and tracking approvals.

## 💡 Solution & Key Features
This project addresses these challenges by implementing a robust automated architecture within ServiceNow:

* **Automated Workflow:** Manual request handling was replaced with an automated flow using **Flow Designer**, ensuring streamlined approvals, timely notifications, and uncompromised data integrity.
* **Self-Service Portal:** A user-friendly **Service Catalog Item** allows users to submit network requests with specific variable inputs (e.g., Bandwidth, Access Type, Location).
* **Approval Logic:** Configured logic to automatically route requests to the appropriate managers or technical leads based on the request type.
* **SLA Tracking:** Integrated Service Level Agreements (SLAs) to monitor response and resolution times.
* **Notifications:** Automated email triggers keep stakeholders informed at every stage of the lifecycle.

## 🛠️ Tech Stack
* **Platform:** ServiceNow (PDI)
* **Automation:** Flow Designer / Workflow Editor
* **Interface:** Service Catalog & Service Portal
* **Scripting:** JavaScript (Client Scripts, Business Rules - *if applicable*)
* **Data Management:** Tables, CMDB (Configuration Management Database)

## 🔄 Process Flow
1.  **Submission:** User submits a request via the Service Portal.
2.  **Validation:** System validates input data using UI Policies/Client Scripts.
3.  **Approval:** Request is routed for approval (Manager/Admin).
4.  **Fulfillment:** Upon approval, tasks are automatically created for network engineers.
5.  **Closure:** Once tasks are completed, the request is closed and the user is notified.



## 📦 How to Use
1.  Import the Update Set XML into your ServiceNow instance.
2.  Navigate to **Service Catalog > Network Services**.
3.  Select **"New Network Request"** (or your specific catalog item name).
4.  Fill in the form and click **Submit**.
5.  Impersonate an Approver to test the workflow logic.

## 👤 Author
* **Prasanna R S** - *Full Stack Developer / ServiceNow Enthusiast*


---
*This project is for educational/portfolio purposes, demonstrating ServiceNow administration and development capabilities.*
