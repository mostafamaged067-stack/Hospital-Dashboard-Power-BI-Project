🏥 **Hospital Dashboard – Power BI Project**

📌 **Project Overview**  
This project analyzes hospital data to evaluate key performance indicators (KPIs) related to patient visits, satisfaction, and waiting time.  
The dashboard provides insights into how different factors — such as gender, age group, and department referrals — impact hospital performance over time.

---

📊 **Data Model Overview**  
The data model follows a **Star Schema** structure:  
- **Fact Table:** Fact_Hospital_Data (contains Patient ID, Date, Satisfaction Score, Wait Time, etc.)  
- **Dimension Tables:**  
  • DimPatient (Patient demographics: Age, Gender)  
  • DimDepartment Referral (Referral type)  
  • DimRace (Patient race)  
  • DimData & DimDate2 (Time dimensions)  
  • Measuress (calculated DAX measures for KPIs)  

This model enables accurate relationships and efficient DAX calculations across multiple dimensions.

---

📈 **Dashboard Insights & Features**

1️⃣ **Patient Visits:**  
   • Total Visits: **519**  
   • Growth: **+10.66%**  

2️⃣ **Average Wait Time:**  
   • Value: **35.81 minutes**  
   • Growth: **+2.18%**  

3️⃣ **Average Satisfaction Score:**  
   • Score: **4.97 / 5**  
   • Growth: **+3.07%**  

4️⃣ **Gender Distribution:**  
   • Female: **254 patients**  
   • Male: **262 patients**

5️⃣ **Detailed Visuals:**  
   • Monthly trend of patient visits by gender  
   • Comparison of patient visits by age groups (Adults, Older, Children, Young)  
   • Interactive monthly filters for time-based insights  

---

🧠 **Tools & Techniques**  
🟡 **Power BI** – Data visualization and dashboard creation  
⚙️ **Transform Data** – Data cleaning and preparation  
🧮 **DAX** – Measures for KPIs (Satisfaction Score, Wait Time, Growth Rate, etc.)  
📊 **Data Modeling** – Star schema design for accurate analytics  

---

🎯 **Project Outcome**  
The Hospital Dashboard provides an analytical overview of healthcare service efficiency and patient satisfaction trends.  
It enables hospital management to monitor performance, identify improvement areas, and make data-driven operational decisions.

---

📍 **Project Source**  
Developed as part of the **Digital Egypt Pioneers Initiative (DEPI)**  
Created by **Mostafa Maged**
