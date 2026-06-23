# 🚗 Motor Vehicle Theft Detailed Analysis (2021–2022)

## 📌 Project Overview
This project provides an in-depth data analysis of motor vehicle thefts to identify key patterns, vulnerable vehicle profiles, and year-over-year (YoY) theft trends. By analyzing vehicle types, model years, and brand data, this dashboard is designed to answer critical business and security questions for stakeholders such as law enforcement, insurance companies, and policy-makers.

**Dashboard Live View / File:** [Link to your Novypro/Tableau Public OR mention the file in the `/dashboards` folder]

## 📊 Dataset Context
* **Source:** [Maven Analytics Data Playground](https://mavenanalytics.io/data-playground/motor-vehicle-thefts)
* **Original Data Origin:** New Zealand Police Department's vehicle of interest database.
* **Timeline Analyzed:** 2021 – 2022.
* **Records:** 4,550 recorded theft incidents.

## 🛠️ Tools Used
* **Data Visualization & Analytics:** Power BI (or mention Tableau/Excel if used instead)
* **Data Cleaning & Processing:** Power Query / DAX

## 💡 Key Business Questions Addressed
1. What is the total volume of vehicle thefts, and how is it trending year-over-year?
2. Which vehicle brands and specific vehicle types are most frequently targeted?
3. What is the demographic profile of a stolen vehicle (e.g., Average Age, Standard vs. Luxury)?
4. Which specific manufacturing years (Model Years) carry the highest risk of theft?

## 📈 Key Findings & Insights

### 1. The 2022 Theft Surge
Theft activity accelerated dramatically between the two observed tracking periods. There was a **~73% increase in vehicle thefts in 2022** (2.89K incidents) compared to 2021 (1.67K incidents). This sharp upward trajectory indicates an escalating systemic issue.

### 2. The "Legacy Security" Vulnerability Window
The historical manufacturing year of the vehicle is one of the strongest predictors of theft risk. The data forms a classic bell curve that peaks sharply around vehicles manufactured between **1998 and 2005**, with the highest peak hitting the year **2000**. The average age of a stolen vehicle is **16.4 years**, confirming that modern anti-theft tech (transponder keys, engine immobilizers) acts as an effective deterrent. 

### 3. Vehicle Segment Risk Profile
* **Standard vs. Luxury:** **94.11%** of all thefts are Standard Class vehicles. Luxury vehicles account for just 5.24%.
* **Top Targets:** In the overall fleet, **Yamaha** dominates the theft charts, indicating a severe vulnerability for motorcycles, scooters, and powersports. 
* **Passenger Vehicle Shift:** When filtering out powersports to look specifically at Hatchbacks, traditional automakers emerge as the highest risk, led by **Toyota**, Suzuki, and Volkswagen. 

## 🚀 Strategic Recommendations
1. **Targeted Anti-Theft Campaigns:** Law enforcement and municipalities should focus public awareness campaigns on owners of early-2000s models, educating them on the necessity of physical security options (steering wheel locks, kill switches).
2. **Insurance Incentives:** Insurance providers should consider offering premium discounts for policyholders who retrofit older standard-class assets (1998-2005) with aftermarket security layers.
3. **Investigate the Powersport Black Market:** The disproportionate volume of Yamaha thefts suggests an active market for stolen motorcycle parts. Focus should be placed on secondary markets dealing in these components.

## 📂 How to Use This Repository
1. Clone the repository: `git clone https://github.com/YourUsername/VEHICLE-THEFT-ANALYSIS-REPORT-2021-2022-.git`
2. The raw dataset is available in the `data/` folder.
3. Open the `.pbix` file in the `dashboards/` folder using Power BI Desktop to interact with the visualisations.

---
*Created by [Your Name] - Connect with me on [LinkedIn](#)!*
