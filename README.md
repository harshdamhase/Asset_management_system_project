# 🏢 Asset Management System

## Microsoft Dynamics 365 Business Central

---

## 📌 Project Overview

This project is a custom **Asset Management System** developed in **Microsoft Dynamics 365 Business Central** using **AL Language**.

The solution is designed to manage the complete asset lifecycle — from **registration and assignment to maintenance, return, replacement, history, and reporting**.

The main objective is to provide a centralized and structured solution for better:

- 🔍 Asset Visibility
- 👤 Accountability
- 📈 Asset Utilization
- 🔧 Maintenance Management
- 🔄 Lifecycle Tracking
- 📊 Reporting

---

# 🎯 Project Objectives

The main objectives of the Asset Management System are:

- 📋 Maintain a centralized Asset Master
- 👤 Track assets assigned to employees
- 🔄 Manage asset returns and reassignment
- 📊 Track current asset status
- 🔧 Manage asset maintenance activities
- ♻️ Manage asset replacement
- 🕒 Maintain asset activity and history
- 📑 Generate asset management reports
- 🔍 Improve asset visibility and traceability
- ⚡ Reduce manual asset tracking
- 📈 Support better management decisions

---

# 🚀 Key Features

## 1️⃣ Asset Master Management

The **Asset Master** acts as the central record for each organizational asset.

It stores important information such as:

- 🆔 Asset ID
- 📦 Item No.
- 🏷️ Asset Type
- 📝 Description
- 🔢 Serial No.
- 📅 Purchase Date
- 💰 Purchase Cost
- 🛡️ Warranty Expiry Date
- 📌 Asset Status
- 👤 Employee No.
- 👤 Employee Name

The Asset Master provides a single view of the asset and its current information.

---

## 2️⃣ Asset Registration

The system allows users to register assets in Business Central.

During registration, the asset can be linked with relevant item information and assigned a unique Asset ID.

### Process

```text
📦 Asset Information
        ↓
📝 Asset Registration
        ↓
🆔 Asset ID Generated
        ↓
📋 Asset Master Created
```

---

## 3️⃣ 👤 Asset Assignment

Assets can be assigned to employees directly from the Asset Management solution.

The system maintains:

- 👤 Employee No.
- 👤 Employee Name
- 🆔 Asset ID
- 📅 Assignment Date
- 📌 Asset Status
- 🕒 Assignment History

This improves accountability and makes it easy to identify the employee responsible for an asset.

---

## 4️⃣ 🔄 Asset Return & Reassignment

When an employee returns an asset, the system records the return and updates the asset status.

The asset can then become available for reassignment.

### Process

```text
👤 Assigned Asset
        ↓
↩️ Return Asset
        ↓
📌 Update Asset Status
        ↓
🟢 Available
        ↓
👤 Reassign Asset
```

---

## 5️⃣ 📊 Asset Status Tracking

The system tracks the current status of each asset.

Example statuses include:

- 🟢 Available
- 🔵 Assigned
- 🟠 Under Maintenance
- 🔴 Replaced
- ⚪ Returned

This provides users with clear visibility into the current state of organizational assets.

---

## 6️⃣ 🔧 Asset Maintenance Management

Maintenance activities can be recorded against individual assets.

Maintenance information can include:

- 🆔 Asset ID
- 📅 Maintenance Date
- 🔧 Maintenance Type
- 📝 Description
- ⚙️ Asset Condition
- 📌 Maintenance Status
- 💬 Remarks

This helps organizations maintain assets properly and improve asset reliability.

---

## 7️⃣ ♻️ Asset Replacement

The system supports replacement of assets when an existing asset needs to be replaced.

The replacement process helps maintain the relationship between the old and replacement assets and improves lifecycle visibility.

### Process

```text
📦 Existing Asset
        ↓
⚠️ Replacement Required
        ↓
♻️ Create Replacement Record
        ↓
📌 Update Asset Status
        ↓
🆕 Register Replacement Asset
```

---

## 8️⃣ 🕒 Asset History

Asset-related activities can be maintained as historical records.

The history can track:

- 👤 Assignment
- ↩️ Return
- 🔧 Maintenance
- ♻️ Replacement
- 📌 Status Changes
- 📝 Other Asset Activities

This provides better traceability and audit visibility.

---

## 9️⃣ 📑 Asset Management Reports

Custom reports can support:

- 👤 Employee-wise Asset Reports
- 📊 Asset Status Reports
- 📋 Asset Assignment Reports
- 🔧 Maintenance Reports
- 🕒 Asset History Reports
- 📈 Asset Management Analysis

---

# ⚡ Asset Master Actions

The Asset Master Card provides direct actions for common asset management activities:

```text
📋 Register Assets
       ↓
👤 Assign Asset
       ↓
↩️ Return Asset
       ↓
♻️ Replace Asset
       ↓
🔧 Maintain Assets
       ↓
📑 Asset Management Report
```

These actions allow users to perform asset-related operations directly from the Asset Master.

---

# 🛠️ Technical Implementation

The solution is developed using:

- 💼 Microsoft Dynamics 365 Business Central
- 💻 AL Language
- 🧑‍💻 Visual Studio Code
- 🗃️ Custom Business Central Tables
- 📄 Custom List & Card Pages
- ⚡ Page Actions
- 🔢 Enums
- ⚙️ Codeunits
- 🔔 Event Subscribers
- 📊 Reports
- 🎨 Report Layouts
- 🔗 Table Relations

---

# 📁 Project Structure

```text
AssetManagement/
│
├── 📂 Src/
│   │
│   ├── 📂 Tables/
│   │   ├── Asset Master
│   │   ├── Asset Assignment
│   │   ├── Asset History
│   │   ├── Asset Maintenance
│   │   ├── Asset Replacement
│   │   └── Asset Return
│   │
│   ├── 📂 Pages/
│   │   ├── Asset Master List
│   │   ├── Asset Master Card
│   │   └── Asset Management Pages
│   │
│   ├── 📂 Codeunits/
│   │   └── Asset Management Logic
│   │
│   ├── 📂 Enums/
│   │   ├── Asset Activity
│   │   ├── Asset Condition
│   │   ├── Maintenance Status
│   │   ├── Replacement Status
│   │   └── Asset Status
│   │
│   └── 📂 Reports/
│       ├── Employee Asset Report
│       └── Asset Management Reports
│
├── 📄 app.json
│
└── 📂 .vscode/
    └── launch.json
```

---

# 🔄 Main Business Process

```text
  Asset Registration
        ↓
  Asset Master
        ↓
  Asset Assignment
        ↓
  Asset Status Tracking
     ↓
  Maintenance / ↩️ Return
        ↓
  Replacement (if required)
        ↓
  Asset History
        ↓
  Asset Reports
```

---

# 💡 Business Benefits

### 🎯 Centralized Asset Tracking

All important asset information is maintained in one centralized Business Central solution.

###  Better Accountability

Employee-wise asset assignment provides clear ownership and responsibility.

###  Improved Asset Utilization

Users can easily identify available, assigned, maintained, returned, and replaced assets.

###  Better Maintenance Visibility

Maintenance activities can be tracked against individual assets.

###  Complete Lifecycle Visibility

The solution provides visibility from asset registration through assignment, maintenance, return, and replacement.

###  Reduced Manual Work

Centralized records and predefined actions reduce dependency on manual asset tracking.

---

# 🧠 Development Approach

The solution follows a modular **Business Central development approach**.

Business requirements were converted into:

- 🗃️ Custom Tables
- 🔗 Table Relations
- 📄 List & Card Pages
- ⚡ Page Actions
- 🔢 Enums
- ⚙️ Codeunits
- 🔔 Event Subscribers
- 📑 Reports
- 🧩 Business Logic

The solution is designed to be maintainable, scalable, and extendable for future business requirements.

---

# 🚀 Future Enhancements

Possible future enhancements include:

- 🔔 Automated Maintenance Reminders
- 📊 Power BI Asset Dashboard
- ✅ Asset Approval Workflows
- 📎 Document Attachments
- 📧 Automated Email Notifications

---

# ☁️ Deployment

The extension can be developed and tested in a **Microsoft Dynamics 365 Business Central Sandbox** using Visual Studio Code and the AL extension.

### Deployment Process

```text
💻 AL Development
        ↓
🔍 Compile & Validate
        ↓
☁️ Business Central Sandbox
        ↓
🧪 Unit Testing
        ↓
👥 User Acceptance Testing
        ↓
🚀 Production Deployment
```

---

# 🧰 Technologies Used

| Technology | Purpose |
|---|---|
|  Microsoft Dynamics 365 Business Central | ERP Platform |
|  AL Language | Custom Development |
|  Visual Studio Code | Development Environment |
|  Business Central Tables | Data Management |
|  Business Central Pages | User Interface |
|  Codeunits | Business Logic |
|  Enums | Status & Activity Management |
|  Reports | Asset Reporting |
|  Business Central Sandbox | Development & Testing |

---

# 📌 Project Outcome

The Asset Management System provides a centralized and structured approach to managing organizational assets within Microsoft Dynamics 365 Business Central.

### Key Outcomes

-  **Improved Asset Visibility**
-  **Better Accountability**
-  **Better Maintenance Management**
-  **Complete Asset Lifecycle Tracking**
-  **Improved Reporting & Decision-Making**

The solution also provides a strong foundation for future integration with:

- 📊 Power BI
- ⚡ Power Automate


---

# 👨‍💻 Project Focus

**Microsoft Dynamics 365 Business Central | AL Development | Asset Lifecycle Management | ERP Customization**

---

# Developed By

```
Harshda Mhase
```
