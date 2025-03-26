# Aircraft Risk Analysis

## Overview

# Business Problem
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

### Objective
Identify the lowest-risk aircraft for the company’s new aviation division by analyzing safety, maintenance, operational costs, and accident history. The goal is to minimize financial and reputational risks while entering the aviation industry.

### Dataset
- **Source:** National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

- **Key Variables:**
  - Aircraft make, engine type, Flight phase, Event Date, Numbe of Engines.
  - Historical accident/incident rates, severity, and root causes.
  - Regional operational data (e.g., weather, air traffic density).

### Tools Used
- **Programming Language:** Python, Jupyter Notebook
- **Libraries:** Pandas, NumPy, matplotlib

---

## 📊 Key Insights

### Aircraft Make
- Aircrafts such as Cessna, Piper, Beech (each one over 5000) recorded a significant number of accidents and others such as Bitonti, Exp acft assn chapter 60 and William d durkee recorded significant number of accidents( 1 each)

### Engine Type Matters
- Aircrafts using reciprocating engines recorded very high number of accidents as compared to aircrafts using the restof the engines in the   Dataframe.
- Aircrafts using LR engines recorded the lowest number of accidents.

### Number of Engines
- Aircrafts running on one engine recorded the highest number of accidents as compared to aircrafts using multiple engines.

### Location Factor
- Most accidents that were recorded happened at Anchorage(over 400 accidents) folowed by Miami,Fairbanks, Houston with them recording almost similar number of accidents.

## 📈 Visualization Highlights

1. **Number of Accidents per Engine Type**  

   *Purpose:* Compare accident frequency across aircraft with running on different engine types. 
   
   *Insight:* Reciprocating engines are most likely to fail and cause accidents.  
   ![Plot](assets/Engines%20vs%20no%20of%20accidents.png)


2. **Top 20 Aircraft Makes by Number of Accidents** 

   *Purpose:* Highlight the top 20 makes of aircrafts that have recorded highest number of accidents.
   
   *Insight:* -Cessna, Piper and Beech are the top three aircraft makes and should be of less consideration when purchasing the aircrafts.
              - Bitonti, Exp acft assn chapter 60 and William d durkee should be considered in number of accidents per aircraft is to be                     considered
   ![Plot](assets/Top%2020%20Makes%20with%20highest%20number%20of%20accidents.png)


3. **Accident Severity Heatmap by Region**  

   *Purpose:* Visualize high-risk regions for fatal accidents.  
   
   *Insight:* - Anchorage,AK, Miami,Fairbanks, Houston had the highest number of accidents. This could be due to poor weather or other                      environmental factors.
              - It is advisable that aircrafts avoid such routes if possible.
   ![Plot](assets/Top%2020%20locations%20with%20highest%20number%20of%20accidents.png)

4. **Number of Accidents by Number of Engines in Aircraft**

   *Purpose:* Identify the optimal number of engines in aircrafts for safety. 
   
   *Insight:* Multiple engines are more safe than using one engine.  
   ![Plot](assets/Number%20of%20accidents%20per%20Number%20of%20engines.png)


---

## 🛠️ How to Reproduce

### Clone the Repository
```bash
git clone git@github.com:EngBrian/phase_1_project.git
