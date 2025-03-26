# 💰 Expense Tracker App - Salesforce (No Code Project)

A beginner-friendly Salesforce project built without using VS Code or any custom code. This app helps track and manage personal or organizational expenses with categorized reporting, validation, and automation.

---

## 📌 Features

- 🔧 **Custom Object**: `Expense`
- 💲 **Fields**: 
  - `Amount` (Currency)
  - `Expense Date` (Date)
  - `Category` (Picklist: Food, Travel, Shopping, Education, Entertainment)
  - `Status` (Picklist: Pending, Approved, Rejected)
  - `User` (Lookup to User)
- 🚫 **Validation Rule**: Prevents saving negative amounts
- 📊 Reports:
  - Monthly expenses report
  - Expenses grouped by category or user
- 📈 Dashboard:
  - Donut chart for category-wise expense distribution
  - Funnel chart showing expense volume by category
  - Bar chart displaying user-wise expense submissions
- 🔁 **Optional Flow**:
  - Sends an email when an expense is approved

---

## 🧠 Project Summary

> Developed a no-code **Expense Tracker App** using Salesforce's UI tools only. Implemented custom objects, validation logic, and analytics dashboards to manage and visualize user expenses. Ideal for Admin portfolio and interview discussion.

---

## 🛠️ Tools & Technologies

- Salesforce Developer Org (Classic/Lightning)
- Object Manager
- Validation Rules
- Report Builder
- Dashboard Builder
- Flows (optional)

---

## 🚀 How to Set Up

1. Log in to your Salesforce Developer Org
2. Go to **Setup → Object Manager** → Create the `Expense` object
3. Add custom fields as listed in the features section
4. Add a validation rule: `Amount < 0`
5. Build reports and dashboards from the App Launcher
6. (Optional) Create a Record-Triggered Flow to send an email on approval

---

🔗 Useful Links

- [Get Free Salesforce Developer Org](https://developer.salesforce.com/signup)
- [Salesforce Object Creation Guide](https://help.salesforce.com/s/articleView?id=sf.build_create_custom_object.htm)
- [Trailhead - Create Reports and Dashboards](https://trailhead.salesforce.com/en/content/learn/modules/reports_dashboards)

---

📣 Author

**Rimjhim Saxena**  
Fresher Salesforce Developer  
Connect on [LinkedIn]((https://www.linkedin.com/in/rimjhim-saxena-5063a4222/)/) | Trailblazer: Ranger Rank

---

## ✅ License

This project is open for educational use. Customize and build upon it freely.

