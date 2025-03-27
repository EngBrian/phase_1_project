# Aviation Risk Assessment for Aircraft Acquisition

## Business Problem
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

### Objective
-Determine the safest aircraft for the company's new aviation division by evaluating safety records, accident history, operational             locations, and engine performance. The objective is to reduce financial and reputational risks while establishing a presence in the         aviation industry.

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
- **High Accident Makes:** Aircraft makes like Cessna, Piper, and Beech each recorded over 5,000 accidents.
- **Low Accident Makes:** In contrast, Bitonti, Exp ACFT Assn Chapter 60, and William D. Durkee recorded significantly fewer accidents (only    1 each).

### Engine Type Matters
- **Reciprocating Engines:** Aircraft using reciprocating engines showed a very high number of accidents compared to other engine types.
- **LR Engines:** Aircraft equipped with LR engines recorded the lowest accident numbers.

### Number of Engines
- **Single-Engine Risk:** Aircraft running on a single engine had the highest accident counts, whereas those with multiple engines fared        better.

### Location Factor
- **High-Risk Regions:** Anchorage experienced the most accidents (over 400), followed by Miami, Fairbanks, and Houston, which recorded         similar accident numbers.


## 📈 Visualization Highlights

1. **Number of Accidents per Engine Type**  

   *Purpose:* Compare accident frequency across aircraft with running on different engine types. 
   
   *Insight:* Reciprocating engines are most likely to fail and cause accidents.
   
   ![Plot](assets/Engines%20vs%20no%20of%20accidents.png)


2. **Top 20 Aircraft Makes by Number of Accidents** 

   *Purpose:* Showcase the top 20 aircraft manufacturers with the highest accident counts
   
   *Insight:* - Cessna, Piper, and Beech emerge as the three most accident-prone makes and should be approached with caution during                         procurement. In contrast, Bitonti, Exp ACFT Assn Chapter 60, and William D. Durkee demonstrate relatively better safety                     records and merit consideration.
   
   ![Plot](assets/Top%2020%20Makes%20with%20highest%20number%20of%20accidents.png)

3. **Accident Severity Bar Chart by Region**

   *Purpose:* Map out regions with high fatal accident risks. 
   
   *Insight:* - Anchorage, Miami, Fairbanks, and Houston show the highest accident frequencies—likely due to adverse weather or other                       environmental factors. It's recommended to avoid routes through these areas when possible.
   
   ![Plot](assets/Top%2020%20locations%20with%20highest%20number%20of%20accidents.png)

4. **Accidents by Engine Count in Aircraft**

   *Purpose:* Determine the safest engine configuration for aircraft. 
   
   *Insight:*Aircraft with multiple engines tend to be safer compared to those with a single engine.
   
   ![Plot](assets/Number%20of%20accidents%20per%20Number%20of%20engines.png)
   
5. **Flight Purpose and Engine Count**

   *Purpose*: Determine the typical number of engines employed by aircraft serving various flight purposes.
   
   *Insight*:  Business/commercial aircraft average six engines, a detail that should influence acquisition decisions.
   
  ![Plot](assets/Number%20of%20engines%20per%20aircraft%20purpose.png)



---

# Recommendations

1. *Select Low-Risk Aircraft Makes*: Avoid high-accident aircraft manufacturers like Cessna, Piper, and Beech. Instead, prioritize makes with fewer recorded incidents for improved safety and reliability.

2. *Choose Multi-Engine Aircraft for Safety*: Single-engine aircraft have the highest accident rates. Investing in multi-engine planes reduces failure risks and enhances operational safety.

3. *Mitigate Risks in High-Accident Regions*: Anchorage, Miami, Fairbanks, and Houston report the most accidents. Implement stricter safety protocols, advanced training, and better maintenance strategies when operating in these areas.

---

## 🛠️ How to Reproduce

### Clone the Repository
```bash
git clone git@github.com:EngBrian/phase_1_project.git
