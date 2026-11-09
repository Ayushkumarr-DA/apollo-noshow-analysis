# Apollo Hospitals - Appointment No-Show & Patient Engagement Analysis

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on patient appointment data for Apollo Hospitals. The objective is to surface actionable business insights regarding booking behaviors, no-show patterns, reminder effectiveness, and the resulting financial impact of missed appointments.

## 📊 Dataset Details
- **Fact Table (`apollo_appointments_fact.csv`):** 75,000 rows containing granular appointment logs, booking channels, lead times, patient demographics, and financial tracking.
- **Dimension Table (`apollo_doctors_dim.csv`):** 320 rows detailing doctor specialties, experience levels, ratings, and standard consultation fees.

## 🛠️ Tech Stack & Methodology
- **Language:** Python
- **Libraries:** Pandas (Data manipulation), Matplotlib & Seaborn (Data visualization)
- **Environment:** Jupyter Notebook (Google Colab)
- **Data Handling:** Filtered 'Scheduled' appointments for accurate dropout rate calculation; scoped revenue and service quality metrics strictly to 'Completed' appointments per business rules.

## 💡 Key Analytical Milestones
1. **Business Overview:** Analyzed 2022-2024 volume trends and booking channel distributions (Apollo App vs. Walk-ins vs. Website).
2. **No-Show Analysis:** Identified specialties and city tiers with the highest dropout risks, and visualized the direct correlation between longer booking lead times and increased no-show probability.
3. **Engagement Effectiveness:** Proved mathematically that layered patient reminders (SMS + WhatsApp + Call) drastically reduce no-show rates compared to zero intervention. 
4. **Demographic Segmentation:** Evaluated dropout risks by age group, gender, and chronic condition status, utilizing box plots to map age distributions across critical specialties like Paediatrics and Psychiatry.
5. **Financial Performance:** Calculated the total estimated revenue lost to no-shows and analyzed the out-of-pocket payment differences between insured and uninsured patients.
6. **Doctor Utilisation:** Joined the fact and dimension tables to evaluate wait times, utilization percentages, and the relationship between a doctor's years of experience and their consultation fees.

## 📁 Repository Contents
* `Apollo_NoShow_Analysis.ipynb`: The complete, documented Python code and visual outputs.****
