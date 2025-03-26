# Aircraft Risk Analysis

## Overview

### Objective
Identify the lowest-risk aircraft for the company’s new aviation division by analyzing safety, maintenance, operational costs, and accident history. The goal is to minimize financial and reputational risks while entering the aviation industry.

### Dataset
- **Source:** Aviation safety databases (e.g., NTSB, FAA), manufacturer reports, and operational cost repositories.
- **Key Variables:**
  - Aircraft model, age, and engine type.
  - Historical accident/incident rates, severity, and root causes.
  - Maintenance frequency, cost per flight hour, and downtime.
  - Regional operational data (e.g., weather, air traffic density).

### Tools Used
- **Programming Language:** Python, Jupyter Notebook
- **Libraries:** Pandas, NumPy, Seaborn, Plotly, Scikit-learn

---

## 📊 Key Insights

### Safety-Cost Tradeoff
- **Older aircraft (15+ years):** 25% higher incident rates but 12% lower acquisition costs.
- **Newer models (e.g., Airbus A320neo):** 40% fewer incidents but require 18% higher upfront investment.

### Engine Type Matters
- **Turboprop engines:** 30% lower maintenance costs but more prone to weather-related incidents in high-altitude regions.
- **Jet engines:** Perform better on high-traffic routes but incur 22% higher fuel costs.

### Regional Risk Hotspots
- **Tropical regions:** Aircraft face 50% more corrosion-related maintenance issues.
- **High-altitude airports (e.g., Denver, Bogotá):** 15% higher engine failure rates.

---

## 📈 Visualization Highlights

1. **Aircraft Incident Rates by Age and Engine Type**  
   *Purpose:* Compare incident frequency across aircraft age groups and engine types.  
   *Insight:* Turboprops under 10 years old had the lowest risk-to-cost ratio.  
   ![Plot]("C:\Users\user\Documents\Flatiron\phase_1_project\phase_1_project\assets\Engines vs no of accidents.png")


2. **Maintenance Cost Distribution by Model**  
   *Purpose:* Highlight cost variability across top aircraft models.  
   *Insight:* Boeing 737-800 had the most predictable maintenance costs (±$150/hr), ideal for budgeting.  
   ![Maintenance Cost Box Plot](assets/plot2.png)

3. **Accident Severity Heatmap by Region**  
   *Purpose:* Visualize high-risk regions for fatal accidents.  
   *Insight:* Southeast Asia had 3× higher severe accident rates due to monsoon weather.  
   ![Regional Severity Heatmap](assets/plot3.png)

4. **Operational Cost vs. Safety Score Scatter Plot**  
   *Purpose:* Identify optimal aircraft balancing cost and safety.  
   *Insight:* Airbus A220 and Embraer E190 clustered in the "Low Cost, High Safety" quadrant.  
   ![Cost vs. Safety Scatter Plot](assets/plot4.png)

---

## 🛠️ How to Reproduce

### Clone the Repository
```bash
git clone https://github.com/your-username/aircraft-risk-analysis.git
