# 📌 CRM Application for Jewel Management – Developer

## 📖 Project Overview

This project is a **Salesforce-based CRM solution** designed for jewelry businesses to manage their core operations in a **centralized and automated** way. The system manages **customer records, jewelry items (Gold & Silver), customer orders, billing, and pricing history**, along with **automation flows, Apex triggers, validation rules, and dashboards**.

It was developed as part of the **SmartBridge Virtual Internship (May–June 2025)** with a focus on:

* **Automation** – Reducing manual effort in billing and notifications.
* **Usability** – Providing simple Lightning pages with structured layouts.
* **Role-based Access** – Ensuring data security for Goldsmiths, workers, and managers.
* **Reporting & Dashboards** – Helping stakeholders with decision-making using real-time KPIs.

---

## 🎯 Key Features

### 🔹 Custom Objects

1. **Jewel\_Customer\_\_c** – Stores customer information (Name, Email, Contact, Address).
2. **Item\_\_c** – Holds jewelry details such as ornament type, weight, KDM charges, making charges.

   * Includes **Record Types** for **Gold** and **Silver** items with custom **Page Layouts**.
3. **Customer\_Order\_\_c** – Connects customers and items, tracks order details (Order Date, Status).
4. **Billing\_\_c** – Auto-calculates total and paid amount; linked with Jewel\_Customer and Item.
5. **Price\_\_c** – Maintains date-wise gold and silver rate history for reference in billing.

---

### 🔹 Automation & Backend

* **Flows** –

  * Record-Triggered Flow for sending automated **email confirmation** to customers when billing is generated or updated.
  * Auto-fill billing amount using item and order data.

* **Validation Rules** –

  * Prevent incorrect data entry (e.g., invalid weight, blank fields, logical constraints).

* **Apex Trigger** –

  * Ensures business rules are followed, such as validating item availability or enforcing payment checks.

---

### 🔹 Security & Access Control

* **Profiles & Roles** –

  * Goldsmith Profile and Worker Profile with restricted access.
  * Worker role reports to Goldsmith for hierarchical control.

* **Permission Sets** –

  * Extended access for Workers to use both Gold and Silver record types.

---

### 🔹 Reports & Dashboards

* **Reports** –

  * *Item with Billing* (links item details with generated bills).
  * *Billing with Item and Customer Order* (full order-to-payment visibility).

* **Dashboards** –

  * *Jewelry Business Overview* – KPIs like total sales, active customers, orders by type.
  * *Customer & Order Insights* – Trends, inventory usage, and customer order statistics.

---

## 📊 Data Flow (Simplified)

1. **Customer** selects an **Item** → Creates a **Customer Order**.
2. Order details + Pricing data → Generates a **Billing Record**.
3. **Automation** triggers email confirmation and updates dashboards.

---

## 🧪 Testing & Validation

* **Functional Testing** – CRUD operations on all objects, flow execution, Apex trigger validation.
* **Performance Testing** – Tested with multiple records for billing and orders.
* **Security Testing** – Verified access control using roles and permission sets.
* **Email Logs** – Confirmed delivery of automated email notifications.

---

## ✅ Advantages

* Centralized customer and inventory management.
* Automation reduces manual errors in billing & order handling.
* Secure access via profiles and roles.
* Real-time business insights with dashboards.

## ⚠️ Limitations

* Limited external integrations (no SMS gateway).
* Initial learning curve for new users unfamiliar with Salesforce UI.

---

## 📂 Repository Contents

* `/Docs` – Project documentation (Design, Planning, Testing, Final Report).
* `/Flows` – Screenshots/exports of Salesforce Flows.
* `/Triggers` – Apex trigger code and handlers.
* `/Reports` – Report and dashboard snapshots.
* `/Demo` – Project demo video link.

---

## 🔗 Demo & Links

* **GitHub Repo**: *\[Your Repo Link]*
* **Demo Video**: *\[YouTube/Drive Link]*
