# 📈 Compound Growth Engine (CGE): CX Retention & Cross-Sell Analytics

An end-to-end data science and analytics project that simulates a B2B SaaS ecosystem to drive smarter customer retention, cross-sell, and support prioritization decisions. Built using Python, SQL, and machine learning, this project models customer health beyond simple churn prediction—delivering actionable “Next Best Actions” for CX, CSM, and Sales teams.

---

## 🔍 Project Snapshot

The Compound Growth Engine (CGE) analyzes a multi-product SaaS environment where customer behavior evolves over time through subscriptions, product usage, and support interactions. Instead of treating churn as a single-table classification problem, CGE creates a unified customer health framework that identifies churn risk, expansion readiness, and escalation threats—transforming analytics into operational decision support.

The final output is an account-level action recommendation that helps teams decide where to intervene, support, upsell, or monitor.

---

## 🛠 Tech Stack

- **Python (Jupyter Notebook)** – Feature engineering, modeling, and simulation  
- **SQL (SQLite)** – Data modeling, CTE-based aggregation, and Golden Record creation  
- **Machine Learning** – XGBoost, Random Forest, Truncated SVD  
- **CSV Outputs** – Actionable model results for BI tools and CX workflows  

---

## 🔑 Key Features

- Designed a realistic multi-table B2B SaaS data model (accounts, subscriptions, usage, tickets, churn)
- Engineered a unified **Golden Record** with ~30 customer health features
- Modeled **churn risk**, **cross-sell readiness**, and **escalation risk** simultaneously
- Built hybrid scoring systems combining ML outputs and business rules
- Converted predictive scores into clear **Next Best Action** recommendations
- Delivered analyst- and CX-friendly CSV outputs for downstream BI or operational use

---

## 📊 Analytics & Modeling Highlights

### Customer Health & Feature Engineering
- Modeled onboarding phase and early-stage friction
- Captured engagement trends using usage velocity (7-day / 30-day)
- Quantified escalation intensity using ticket volume, priority, and resolution signals
- Created a composite churn risk score blending behavioral, financial, and support signals

### Machine Learning Models
- **Churn Prediction**: XGBoost with imbalance handling and PR-AUC evaluation  
- **Cross-Sell Propensity**: Hybrid collaborative filtering + business-rule scoring  
- **Escalation Risk**: Random Forest classifier for near-term support risk detection  

### Action Layer
- Translated model outputs into intuitive actions such as:
  - **Urgent: Rescue Call**
  - **Proactive Support**
  - **Upsell Meeting**
  - **Check-in Call**
  - **Monitor**
- Produced a consolidated CX action list for prioritization and planning

---

## 🚦 How to Use

- Clone or download the repository  
- Run the Jupyter notebooks to generate features and model outputs  
- Explore CSV outputs:
  - `crosssell_opportunities.csv`
  - `escalation_risks.csv`
  - `csm_action_list.csv`
- Plug results into BI tools, CX dashboards, or CRM workflows

---

## 👤 Author

### **Rachna Nair**  
💼 LinkedIn: https://www.linkedin.com/in/rachna-nair10/
