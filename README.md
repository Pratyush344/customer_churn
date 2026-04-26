# 📉 Customer Churn Analysis  
End-to-end data analytics project focused on understanding and reducing customer churn using Python, SQL, and Power BI.

---

## 📌 Project Overview  
This project analyzes telecom customer data to identify key factors driving customer churn. By examining customer demographics, service usage, subscription details, and billing behavior, the analysis uncovers patterns that help businesses improve customer retention and maximize customer lifetime value.

The dataset consists of **7,000+ customer records**, including detailed information on services, contracts, and payment behavior.

---

## 🎯 Business Objectives  
- Identify key drivers contributing to customer churn  
- Compare behavior between churned and retained customers  
- Analyze the impact of contract type, tenure, and services on churn  
- Detect high-risk customer segments likely to churn  
- Provide actionable strategies to improve retention  

---

## 🗂 Dataset Description  

### 👤 Customer Information  
- Customer ID  
- Gender  
- Senior Citizen  
- Partner  
- Dependents  

### 📞 Services & Usage  
- Phone Service  
- Multiple Lines  
- Internet Service  
- Online Security  
- Online Backup  
- Device Protection  
- Tech Support  
- Streaming TV & Movies  

### 📄 Subscription Details  
- Contract Type (Month-to-month, One year, Two year)  
- Tenure  

### 💳 Billing & Payments  
- Monthly Charges  
- Total Charges  
- Payment Method  
- Paperless Billing  

### 🎯 Target Variable  
- Churn (Yes / No)  

---

## 🔍 Analysis Workflow  

### 1️⃣ Data Cleaning & Preparation  
- Converted **Churn column** from categorical to numerical (Yes = 1, No = 0)  
- Fixed **TotalCharges datatype** (object → float)  
- Handled missing and blank values  
- Standardized categorical variables  
- Prepared dataset for SQL and Python-based analysis  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Churn distribution analysis  
- Tenure vs churn relationship  
- Monthly charges vs churn analysis  
- Contract type comparison  
- Service usage impact on churn  

### 3️⃣ Churn Behavior Analysis  
- Identified high churn among low-tenure customers  
- Compared churn rates across contract types  
- Analyzed impact of value-added services  
- Studied relationship between payment methods and churn  

---

## 📈 Key Insights  
- Customers with **month-to-month contracts** show the highest churn rate  
- **Low-tenure customers** are more likely to churn early  
- Lack of **online security, backup, and tech support** increases churn probability  
- Higher monthly charges are associated with increased churn risk  
- Long-term contracts significantly improve customer retention  

---

## 💡 Business Recommendations  
- Encourage customers to switch to **long-term contracts**  
- Offer **bundled services** (security, backup, support)  
- Implement **early retention strategies** for new customers  
- Optimize pricing strategies for high monthly charge segments  
- Provide targeted incentives for high-risk churn groups  

---

## 🧠 Key Learnings  
- Importance of data cleaning (especially datatype corrections like TotalCharges)  
- Understanding churn behavior in subscription-based business models  
- Identifying key drivers using multiple features  
- Translating data insights into actionable business strategies  
- Hands-on experience with real-world telecom datasets  

---

## 🛠 Tools & Technologies Used  
- **Python** – Pandas, NumPy, Matplotlib, Seaborn  
- **SQL** – Data querying, joins, aggregations  
- **Power BI** – Dashboard creation and visualization  
- **Jupyter Notebook** – Data analysis workflow  
- **Git & GitHub** – Version control and documentation  

---

## 📊 Future Improvements  
- Build a **machine learning churn prediction model**  
- Apply classification algorithms (Logistic Regression, Random Forest)  
- Perform feature importance analysis  
- Deploy a real-time churn monitoring dashboard  

---

## 📌 Overall Understanding  
This project demonstrates how telecom businesses can proactively reduce customer churn by leveraging data-driven insights. By analyzing customer behavior, service usage, and subscription patterns, companies can design targeted retention strategies and improve long-term profitability.

---

## 📫 Contact  
📧 Email: pratyushsingh0220@gmail.com  
🔗 LinkedIn: [Pratyush Singh](https://www.linkedin.com/in/pratyush344)
