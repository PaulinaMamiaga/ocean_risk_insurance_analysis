![Header](./Visuals/header_readme.png)
>
>
>
> # Risk Factors for Ocean Activities -  Insights for Insurance Pricing

<details>
  <summary><strong>📑 Table of Contents</strong></summary>

  - [Project Overview](#project-overview)
  - [Objectives](#objectives)
  - [Dataset](#dataset)
  - [Data Cleaning Process](#data-cleaning-process)
  - [Analysis Notebooks](#analysis-notebooks)
  - [Key Insights](#key-insights)
  - [Business Impact](#business-impact)
  - [Limitations](#limitations)
  - [Team](#team)

</details>

> ## Project Overview

🔓 *“Imagine you’re a traveler planning a surfing trip to Australia. You buy a standard insurance policy, but behind the scenes, the insurer has no idea that your activity, destination, and travel season all dramatically increase your risk.
That’s where our analysis comes in.”*

>This project analyzes shark incident data over the last 50 years to understand how activity type, seasonality, geography, and age influence risk levels. The goal is to demonstrate data cleaning, exploratory data analysis, and risk interpretation from a business perspective (insurance industry).


>As part of the Ironhack Data Analytics Bootcamp. The project focuses on transforming raw shark incident data into actionable insights that could support risk assessment and pricing decisions within an insurance company.

<details>
<summary><strong>🚀 Built With</strong></summary>

--------
For this project we use:
- <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
- <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
- <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
- <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" />
- <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logoColor=white" />
- <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
- <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
- <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" />
- <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
- <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
- <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />

</details>









> ## Objectives
- Clean and preprocess inconsistent shark incident records  
- Analyze patterns in activity, age, seasonality, geography, and injury types  
- Extract insights relevant for insurance pricing and coverage design  
- Build a structured analytical framework: Hypothesis → Insight → Interpretation → Implication → Business Impact → Limitation  

<details>
  <summary><strong>📊 Dataset</strong> (click to expand)</summary>
  <br>

Source: Global Shark Attack File (GSAF),  
https://www.sharkattackfile.net/incidentlog.htm

The dataset required extensive cleaning due to:

- Missing or inconsistent age values  
- Unstandardized activity labels  
- Mixed date formats  
- Country and location inconsistencies  

</details>

<details>
  <summary><strong>🧹 Data Cleaning Process</strong> (click to expand)</summary>
  <br>

- [Shark-attacks-Years-Countries-Sex-Fatal.ipynb](Notebooks/Shark-attacks-Years-Countries-Sex-Fatal.ipynb)
- [Shark-attacks-State-Activity.ipynb](Notebooks/Shark-attacks-State-Activity.ipynb)
- [Shark-attacks-Date-Injury.ipynb](Notebooks/Shark-attacks-Date-Injury.ipynb)
- [Shark-attacks-Age.ipynb](Notebooks/Shark-attacks-Age.ipynb)

</details>



> ## Key Insights & Visuals

This section summarizes the main analytical insights of the project, supported by visualizations.  
Each chart links a **hypothesis** to an **interpretation** that could be relevant for insurance risk and pricing.

---

### 1. Activity Risk - Which Ocean Activities Are Most Exposed?

**Hypothesis:**  
High-risk ocean activities such as surfing, diving, and swimming significantly increase the probability of shark incidents.

![Activity Risk Chart](./Visuals/activity_risk_chart.png)

**Insight:**  
Activities like surfing, swimming, and diving concentrate the majority of recorded incidents, indicating higher exposure levels compared to other activities.

**Implication for insurance:**  
These activities should be classified as **high-risk categories** and priced accordingly in travel and sports insurance products.

---

### 2. Seasonal Risk - When Is the Risk Higher?

**Hypothesis:**  
Shark incidents increase significantly during summer; therefore, seasonal pricing should be applied to travel insurance policies.

![Seasonal Risk Chart](./Visuals/seasonal_risk_chart.png)

**Insight:**  
Summer clearly shows the highest number of incidents, which is consistent with increased human activity and possible behavioral patterns in sharks.

**Implication for insurance:**  
A **Seasonal Pricing Model** could increase premiums for summer periods to reflect higher risk and protect against seasonal claim spikes.

---

### 3. Geographic Risk - Where Are Incidents More Frequent?

**Hypothesis:**  
Shark incident frequency varies significantly by country, so insurance pricing should be adjusted by region.

![Geographic Risk Chart](./Visuals/geographic_risk_chart.png)

**Insight:**  
Countries such as the USA, Australia, South Africa, Brazil, and the Bahamas show the highest concentration of incidents.

**Implication for insurance:**  
Policies covering trips to these **high-risk destinations** may require **regional premium adjustments** or specific ocean-activity riders.

---

### 4. Age Risk - Who Is Most at Risk?

**Hypothesis:**  
Young adults (ages 18–45) have the highest exposure to ocean activity risk and should receive age-adjusted premiums.

![Age Risk Chart](./Visuals/age_risk_chart.png)

**Insight:**  
The 18–45 age group represents the majority of incidents, reflecting higher participation in high-exposure ocean activities.

**Implication for insurance:**  
Introducing **age-based risk pricing** can improve premium accuracy and reduce cross-subsidization between age groups.

---

![Business Impact](./Visuals/business_impact.png)

> ## Business Impact (Hypothetical)

The insights from this project can support **risk-based decision making** in the insurance industry.  
Although no real financial calculations were performed (due to lack of pricing and claims data), the analysis suggests several potential areas of business impact:

- **Activity-based pricing**  
  High-risk activities (e.g. surfing, diving, swimming) could be priced differently from low-risk ocean uses, improving alignment between exposure and premium.

- **Seasonal pricing strategies**  
  Higher risk during summer could justify seasonal adjustments to travel insurance products, helping to protect the company against peak claim periods.

- **Geographic pricing and product design**  
  Countries with a historically higher concentration of incidents (e.g. USA, Australia, South Africa, Brazil, Bahamas) could be treated as high-risk destinations, leading to:
  - Regional premium adjustments  
  - Destination-specific riders or add-ons  
  - Specialized products (e.g. “surf insurance” for certain regions)

- **Age-based risk segmentation**  
  Since the 18–45 age group appears as the most exposed, age-based pricing rules could increase accuracy and reduce cross-subsidization across demographics.

> ### Display: https://drive.google.com/file/d/1hXUZTB5mja6TO1MkX02xT1OqyzZl4jCO/view?usp=sharing


---

### Important Disclaimer: Hypothetical Nature of Business Impact

The **Business Impact described here is hypothetical** and intended for educational purposes only.

The dataset used in this project does **not** contain:
- Policy premium values  
- Claims history or claim costs  
- Loss ratios or profitability metrics  
- Portfolio composition (number of policies per product, region, or customer segment)  
- Customer-level financial information  

Because of this, it is **not possible** to compute real financial impact (e.g. profit increase, claim cost reduction) based solely on the shark incident dataset.

What we provide instead is:
- **Qualitative impact**: how the insights *could* be used by an insurance company  
- **Guidance**: where pricing and underwriting teams might focus their efforts

---

### What Would Be Needed for a Real Financial Impact Analysis

To move from **hypothetical** to **quantitative** Business Impact, the company would need to combine this risk analysis with internal financial data, including for example:

- Historical **premium tables** per product, activity, region, and season  
- **Frequency and severity of claims** for relevant ocean-activity products  
- **Average claim cost** by severity (fatal, non-fatal, minor injury)  
- **Customer portfolio distribution** (by age, activity, destination, season)  
- **Underwriting rules and actuarial models** currently in use  
- **Loss ratios and profitability indicators** for ocean-related coverage  

Integrating these data sources would allow:
- Simulation of pricing scenarios  
- Estimation of future losses under different risk assumptions  
- Calculation of expected changes in revenue and profit

---

### Multidisciplinary Collaboration (Real-World Context)

In a real insurance company, a robust Business Impact study would be carried out by a **multidisciplinary team**, typically involving:

- **Risk Management Analysts**  
  Identify and validate the key risk drivers (activity, season, geography, age).

- **Data Analysts / Data Scientists**  
  Clean and model the data, test hypotheses, and quantify risk segments.

- **Actuarial & Pricing Teams**  
  Translate risk patterns into pricing structures, expected-loss models, and premium recommendations.

- **Business Intelligence (BI) Experts**  
  Estimate revenue impact, profitability, and scenario outcomes (e.g. “what happens if we increase premiums for high-risk activities?”).

- **Underwriters**  
  Adjust coverage limits, exclusions, and policy conditions according to risk segmentation.

---

### Recommendation for Future Work

As a next step, this project could be extended by:

1. **Connecting with actuarial and pricing teams** to obtain anonymized financial and claims data.  
2. **Building a simple pricing simulation model** that applies different premium levels by activity, season, region, and age.  
3. **Comparing scenarios** (current pricing vs. risk-adjusted pricing) to estimate potential changes in:
   - Premium income  
   - Expected claims cost  
   - Profitability by segment  

This would transform the project from a **risk insight analysis** into a **full business-impact and pricing optimization case**.

![Limitatios & Next Steps](./Visuals/limitations_nextsteps.png)
>
> ## Limitations & Next Steps

### Limitations

This project provides valuable insights into **risk patterns** for ocean activities, but it is important to recognize several limitations:

#### 1. Dataset Limitations

- The dataset includes only **reported** shark incidents, which may not fully represent all real-world events.  
- Some countries and activities may be **underreported**, creating potential bias in geographic and activity-based conclusions.  
- **Age, activity, and location fields** sometimes contain missing or inconsistent values, even after cleaning and standardization.  
- The dataset does **not** include any **financial, pricing, or claims data**, which prevents real monetary impact calculations.

#### 2. Analytical Limitations

- The analysis focuses on **descriptive and exploratory** insights rather than predictive modeling.  
- Risk is evaluated based on **historical frequency**, not on future probability forecasts or combined risk scores.  
- Business Impact is presented as **qualitative and hypothetical**, since no internal insurance data (premiums, claim amounts, loss ratios) was available.  
- The project does not consider other important factors such as:
  - Customer behavior (e.g. experience level, safety training)  
  - Environmental variables beyond season (e.g. water temperature, distance from shore)  

---

### Next Steps

To strengthen and extend this project, the following directions are recommended:

#### 1. Data Enrichment

- Integrate **internal insurance data** (premiums, claims, loss ratios, portfolio size) to connect risk patterns with real financial outcomes.  
- Combine shark incident data with **external environmental datasets** (e.g. sea temperature, distance to coast, tourism intensity).  
- Refine **age and activity groups** for more granular risk segmentation.

#### 2. Advanced Modeling

- Develop a **risk scoring model** that estimates incident likelihood by activity, season, region, and demographic group.  
- Explore **classification models** (e.g. logistic regression, tree-based models) to predict incident severity or risk level.  
- Test different **pricing scenarios** based on risk scores and compare their potential impact on expected losses and premiums.

#### 3. Business Integration

- Collaborate with **Risk Management, Actuarial, Pricing, and BI teams** to validate assumptions and design realistic pricing strategies.  
- Build a **dashboard** (e.g. in Tableau, Power BI, or a Python web app) to allow stakeholders to explore risk patterns interactively.  
- Translate analytical outputs into **clear documentation and playbooks** for underwriters and product managers.

#### 4. Educational Value

From a learning perspective, this project can be extended in future bootcamp or individual work by:

- Deepening **data cleaning and feature engineering** techniques.  
- Practicing **storytelling with data**, focusing on how to communicate insights to non-technical stakeholders.  
- Expanding the **Business Impact section** once financial data is available, turning this into a complete insurance pricing case study.

---

Overall, this project should be seen as a **solid first step**: it transforms raw incident data into structured insights and a clear framework for decision-making. With additional data and cross-functional collaboration, it could evolve into a **fully operational tool** for risk-based insurance pricing and product design.

> ## 🤝 Contributions
Every contribution is more than a line of code - 
it’s a step toward a world where data tells stories, guides decisions, and brings humanity and intelligence closer together.
If something here sparks your curiosity, inspires you, or makes you think “This could be even better,” then you’re already part of the journey.
 Your ideas, suggestions, and improvements are genuinely welcome.

**You can contribute in two simple ways:**

### 🌱 Have an idea to improve something?
- Open an issue with the enhancement tag and share your suggestion.
>
- Or, if you prefer building directly, go ahead and create your enhancement.

### 🔧 Recommended Contribution Workflow
>
1. Fork the repository
>
2. Create a branch for your feature:
> *git checkout -b feature/YourImprovement*
>
3. Commit your changes with a clear, intentional message:
> *git commit -m "Enhancement: short description of your contribution*
>
4. Push your changes:
> *git push origin feature/YourImprovement*
>
5. Open a Pull Request and let’s refine it together
>
>
-----
⭐ If this project adds value to your journey, feel free to leave a star.
 Small gestures help this exploration grow, reach further, and inspire new ideas.
Thank you for being part of this story.










