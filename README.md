
# 💎 CRM Application for Jewel Management – (Developer)

## 📌 Project Overview

This project is a **Salesforce-based CRM system** designed to streamline jewelry business operations. It helps manage **Jewel Customers, Items (Gold/Silver), Orders, Billing, Pricing**, and provides real-time insights via **Reports & Dashboards**. The system uses a combination of **custom objects**, **automation tools (Flows, Validation Rules, Triggers)**, and **UI customizations**.

> 🚀 Developed by Team ID: `LTVIP2025TMID29987`.

---

## 👥 Team Members

- **Korrayi Sravya** (Team Leader)
- Dinesh Ketana
- Bonikala Dhamodhar
- Appalabattula Yaswanthsai

---

## 🧩 Features

- ✅ **Jewel Customer Management** (Add/View/Delete)
- ✅ **Item Management** (Separate layouts for Gold & Silver)
- ✅ **Customer Order Tracking**
- ✅ **Dynamic Billing** with auto-calculations
- ✅ **Automated Email Notifications** via Flows
- ✅ **Reports & Dashboards** for business insights
- ✅ **Field Dependencies** (e.g., Priority → Expected Days of Return)
- ✅ **Validation Rules** and **Triggers** for Data Integrity

---

## 🔧 Technologies Used

- Salesforce (Lightning Platform)
- Apex (Triggers)
- Flows (Record-Triggered Automation)
- Lightning App Builder
- Reports & Dashboards
- Google Sheets, Trello (Planning Tools)

---

## 🗃️ Custom Objects

| Object Name         | Description                                |
|---------------------|--------------------------------------------|
| Jewel Customer      | Stores customer data                       |
| Item                | Manages inventory of gold/silver items     |
| Price               | Holds pricing per gram and ornament type   |
| Customer Order      | Tracks customer orders                     |
| Billing             | Generates bills with calculated values     |

---

## 🧠 Key Formula Fields

- **Total Amount** = (Weight × Price) + KDM Charges + Making Charges + Stone Charges
- **Paying Amount** = Auto-filled from related Payment or Order object
- **Remaining Amount** = Total – Paid

---

## 📈 Reports & Dashboards

- 📊 **Item with Billings Report**
- 📊 **Billing with Item and Customer Report**
- 📊 **Sales Overview Dashboard**

---

## ⚙️ Automation

- **Record-Triggered Flow**: Sends email to customer on Billing creation
- **Validation Rules**: Prevent incomplete or incorrect entries
- **Apex Trigger**: Custom logic on Item creation


## 🎬 Demo & Resources

* **📽️ Demo Video**: [Watch on Google Drive](https://drive.google.com/your-demo-link)
* **📊 Dataset**: Data entered manually via Lightning App
* **📎 Documentation**: Included in `/docs` folder or shared during review

---

## 🚀 Deployment

1. Use a Salesforce Developer Org or Playground.
2. Import objects via Object Manager.
3. Configure fields and relationships.
4. Add flows, triggers, and dashboards.
5. Deploy using Change Set or metadata API (optional).

---

## 📅 Agile Planning Summary

* **Methodology**: Agile (2 Sprints)
* **Velocity**: 12 Story Points per Sprint
* **Tools Used**: Trello, Google Sheets, Salesforce Kanban
* **Status**: ✅ 100% Functional & Performance Tested

---

## 📌 Future Enhancements

* Integrate **Payment Gateway**
* Add **Mobile Interface** using LWC or Salesforce Mobile App
* Multi-branch support for large jewelers
* Role-based access control for staff and admin

---

## 📜 License

This project is for educational/demo purposes only. All assets used are either open-source or created by the team.

---

```

Let me know if you'd like me to **customize it more** or help you add badges, diagrams, or GitHub Actions!
```
