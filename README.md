# 📊 Customer Complaints Service Quality Analytics

A Power BI dashboard designed to analyze customer complaints, identify major complaint drivers, and evaluate service-quality and response performance across products, issues, geography, channels, and complaint status.

---

## 🎯 Business Objective

Customer complaint data can become difficult to act on when it is viewed only as a list of individual cases.

This project transforms complaint records into a structured analytical view designed to answer key business questions:

* Which products generate the most complaints?
* Which issues and sub-issues are driving complaint volume?
* How does complaint activity vary across states and submission channels?
* How effectively is the company responding to complaints?
* What proportion of complaints are timely, in progress, or otherwise resolved?
* Which areas require deeper investigation?

The objective is not only to identify **where complaint volume is high**, but also to provide a structured path to investigate **what is driving that volume**.

---

## 📌 Dashboard Overview

The report is organized into multiple analytical views, moving from high-level monitoring to detailed investigation.

### 1. Executive Overview

Provides a high-level view of complaint volume and service-quality indicators, including:

* Total complaints
* Number of states covered
* Number of products
* Average complaints submitted per day
* In-progress complaints
* Timely response percentage
* Complaint trend over time
* Complaint volume by product
* Complaint volume by issue
* Company response distribution

### 2. Complaint Drivers & Root Cause

Moves from overall complaint volume into deeper analysis of complaint drivers.

Key analysis includes:

* Product-level complaint analysis
* Product → Issue drill-down
* Issue contribution using a treemap
* Decomposition Tree analysis
* Analysis across Product, Issue, Sub-product and Sub-issue
* Interactive Product, State and Date filters

The purpose is to move from:

**"What is happening?" → "What is driving it?"**

### 3. Geographic & Channel Analysis

Examines how complaint activity varies across:

* States
* Submission channels
* Products
* Dates
* Company response

This allows complaint concentration and channel-level patterns to be investigated rather than relying only on an overall complaint total.

### 4. Response & Resolution Performance

Focuses on how complaints are handled and responded to.

The analysis includes:

* Company response to the customer
* Response status distribution
* Complaint trends
* Product and state filtering
* Date-based analysis

This view helps evaluate the service-quality side of the complaint process rather than focusing only on complaint volume.

### 5. Detail / Drill-through Analysis

A dedicated drill-through page provides a deeper investigation after selecting a relevant **State, Product, or Issue**.

The detailed view includes metrics such as:

* Total complaints
* Timely response percentage
* In-progress complaint percentage
* Average delay in receiving complaints
* Monetary relief / non-monetary relief indicators
* Year-over-year complaint growth
* Average complaints per day

This allows a user to move from a high-level dashboard finding to a more focused investigation.

---

## 🔎 Analytical Approach

The project follows a structured business-analysis workflow rather than presenting disconnected visuals.

**Complaint Volume → Product → Issue → Root Cause → Geography / Channel → Response Performance → Detailed Investigation**

This approach is designed to help a business user move from a high-level KPI to the dimensions behind that KPI and identify areas that may require further investigation.

---

## 🛠️ Tools & Techniques

### Tools

* Microsoft Power BI Desktop
* Power Query
* DAX

### Power BI Techniques

* Data preparation and transformation
* Data modeling
* Dimension and fact-style table structure
* DAX measures and KPIs
* Interactive slicers and filtering
* Drill-through navigation
* Treemap analysis
* Decomposition Tree
* Time-series analysis
* Geographic analysis
* Channel analysis

---

## 📈 Key Analytical Themes

| Theme                 | Business Question                                                 |
| --------------------- | ----------------------------------------------------------------- |
| **Complaint Volume**  | Where are complaints concentrated?                                |
| **Complaint Drivers** | Which products and issues contribute most?                        |
| **Service Quality**   | Are complaints being handled and responded to effectively?        |
| **Investigation**     | Which state, product, issue, or sub-issue deserves deeper review? |

---

## 💡 Business Value

The dashboard is designed to support a practical investigation workflow.

Instead of stopping at the highest-level complaint count, a user can drill into the dimensions behind that volume and identify specific:

* Products
* Issues
* Sub-products
* Sub-issues
* Locations
* Submission channels
* Response patterns

This makes the report useful not only for **monitoring complaint volume**, but also for identifying areas that may require further business investigation and service-quality improvement.

---

## 📂 Project Files

The repository will contain:

* Power BI report file (`.pbix`)
* Dashboard screenshots
* Data model documentation
* Project documentation

---

## 👤 Author

**Soham Das**

Data & BI Analyst

[LinkedIn](https://www.linkedin.com/in/sohamdasofficial/) • [GitHub](https://github.com/Soham-Das-analyst)
