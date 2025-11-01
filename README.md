# Power BI – Scheduled Refresh Demo

This repository demonstrates the process of **configuring Scheduled Refresh in Power BI**, enabling automated data updates for published reports and dashboards.  
The purpose of this demo is to showcase my understanding of Power BI’s refresh capabilities and their importance in maintaining up-to-date insights without manual intervention.

---

## ⚙️ Overview

Power BI Scheduled Refresh allows datasets published to the **Power BI Service** to automatically refresh from their original data sources.  
It ensures that dashboards and reports always reflect the latest data.

This demo outlines the **step-by-step setup** for enabling Scheduled Refresh for a dataset built in **Power BI Desktop** and published to the **Power BI Service**.

---

## 🧩 Step-by-Step Process

### 1️⃣ Prepare the Power BI Report
- Build a Power BI report in **Power BI Desktop**.
- Use a data source such as **Excel**, **SQL Server**, or **SharePoint**.
- Verify that your data loads correctly.

### 2️⃣ Publish the Report to Power BI Service
- Click **Publish** in Power BI Desktop and choose your workspace in Power BI Service.
- Ensure that the dataset appears under **Datasets + dataflows** in your workspace.

### 3️⃣ Configure Data Source Credentials
- In Power BI Service, go to:  
  **Workspace → Datasets + dataflows → Settings → Data source credentials**
- Re-enter the correct credentials if needed (especially if using on-premise data).

### 4️⃣ Enable Scheduled Refresh
- Go to **Dataset settings → Scheduled refresh**.
- Toggle **“Keep your data up to date”** to *On*.
- Set the **refresh frequency** (Daily / Weekly).
- Choose preferred **refresh time slots**.

### 5️⃣ Test and Verify
- Manually trigger a refresh using the **Refresh now** option.
- After successful refresh, verify that the latest data appears in your report.

> ✅ Tip: For on-premise data, install and configure a **Power BI Gateway** to enable connectivity between your data source and Power BI Service.

---

## 🕒 Example Gateway Connection (Illustrative)

> <img width="935" height="603" alt="add-to-gateway" src="https://github.com/user-attachments/assets/57395083-40d8-400b-a038-787da533cef2" />
> *(The included image is for illustrative purposes only. Actual setup can be replicated using Power BI Service.)

The image above represents a typical adding gateway setup in the Power BI Service interface

---

## 🧠 Key Learnings

- Scheduled Refresh eliminates manual refreshes and ensures consistent report updates.
- Gateways are essential when working with **on-premise** or **local Excel** sources.
- Refresh frequency and time slots should align with business reporting needs.
- You can monitor refresh activity in **Dataset → Refresh History**.
- Notifications can be enabled to alert on refresh failures.

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **Power BI Service**
- **Power BI Gateway (optional)**
- **Cloud or On-premise Data Sources**

---

## 🔒 Real-World Use Case

Scheduled Refresh is critical for maintaining live dashboards and operational analytics in:
- **Finance** (daily cash flow reports)  
- **Sales & Marketing** (real-time performance tracking)  
- **HR Analytics** (up-to-date workforce metrics)

---

