🚀 Intake360 – Salesforce Intake Automation System
📌 Overview

Intake360 is a Salesforce-based intake management system built using Experience Cloud, Flow Automation, and Custom Objects.
It enables users to submit structured intake requests through a portal, automatically process them, and update status using backend automation.

🧩 Problem Statement

Organizations often handle intake requests manually via emails or spreadsheets, leading to:

Delays in processing
Lack of visibility
No standardized intake format

Intake360 solves this by providing a centralized digital intake portal with automation.

⚙️ Architecture
1. Experience Cloud (UI Layer)
Public portal built using Experience Builder
Intake form embedded using Screen Flow
2. Screen Flow (User Input)
Collects intake details from users
Creates Intake records in Salesforce
3. Record-Triggered Flow (Automation)
Automatically updates Status field to “New”
Handles backend processing logic
4. Custom Object
Intake__c stores all intake records
🔄 Process Flow
User submits intake form via Experience Cloud
Screen Flow captures input and creates record
Record-triggered Flow runs automatically
Status is updated to "New"
Record becomes available for internal processing
🛠️ Tech Stack
Salesforce Lightning Platform
Flow Builder (Screen + Record-triggered Flows)
Experience Cloud
Git & GitHub
📸 Demo

👉 Add your video link here (Loom / YouTube / Google Drive)