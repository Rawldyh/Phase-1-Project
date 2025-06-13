
# ✈️ Aircraft Accident Risk Analysis

**Overview**

This study analyzes over 60 years of U.S. civil aviation accident data to identify key risk factors associated with aircraft manufacturers, injury severity, and aircraft destruction. The ultimate goal is to generate business insights for a company that is aiming to invest in the aircraft industry.

---

## 📊 Project Structure

- **Data Source:** NTSB Aviation Accident & Incident Database  
- **Data Period:** 1962–2023  
- **Data Volume:** Around 90,000 records  
- **Tools Used:** Python, Pandas, Matplotlib, Jupyter Notebook, PowerPoint, Power BI

---

## 🎯 Business Problem

Identify the lowest risk aircraft to support safe and strategic entry into the aviation industry for companies looking forward to diversifying their portfolio.

**Key Questions:**
- Which aircraft makes are involved in the most accidents?
- How severe are these incidents in terms of injuries and damage?
- Are there makes with consistently higher fatality or destruction rates?
- Which ones seem less risky as an investment?

---

## 🧹 Data Cleaning and Preprocessing

- Standardized the `Event.Date` and created a `Year` column
- Normalized `Make` names and removed non-informative entries
- Converted injury columns to numeric and filled missing values
- Uniformized the data

---

## 📈 Exploratory Analysis

Key insights:
- CESSNA accounts for the largest share of accidents, followed by PIPER and BEECH
- Around 17% of reported accidents result in total aircraft destruction
- Most incidents result in no or minor injuries
- Fatal injuries are rare but strongly correlated with destruction

---

## 🔍 Manufacturer Risk Comparison

We evaluated the top 10 most frequent aircraft makes by:
- Average number of accidents per year
- Average number of fatal, serious, minor injuries
- Proportion of destroyed aircraft

This approach revealed statistically significant variation in risk profiles by make.

---

## 💼 Business Implications

- Some makes are good picks for revenue with manageable risk.
- Some are a high risk option
- Some fall into a moderate risk zone
- Other makes could be an option also
- The company should study cost, efficiency, and maintenance in order to compare safety with 
profitability.

---

## 🧾 Files Included

- `Final.ipynb`: Full Jupyter notebook with code, analysis, and findings
- `Presentation.pptx`: Executive-ready presentation
- `Aviation_Data.csv`: Dataset
- `Aviation accident analysis dashboard.pbix`: Power BI interactive dashboard
- `Dashboard.pdf`: Non-interactive Pdf version of the dashboard
- `README.md`: This file

---

## 📌 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/Rawldyh/Phase-1-Project.git
   ```

2. Open and run `Final.ipynb` in JupyterLab or VSCode

---
### ⚠️ Disclaimer
Parts of this project were developed with assistance from OpenAI's ChatGPT and Anaconda Assistant for debugging and enhancing the presentation. However, all analysis and recommendations were conducted independently by me.

## 📬 Contact
For questions or collaboration, contact rolddysurpris@gmail.com or www.linkedin.com/in/rolddy-surpris-8574b0265


