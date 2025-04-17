## 🌱 ESG S&P 500 Risk Insights

📈  This project taught me how to combine quantitative measures (like scores) with qualitative flags (like controversy levels) to reveal deeper business risks. I was especially interested in how these two can influence the Total ESG Risk Scores across companies in the S&P 500, with a focus on the Energy and Healthcare sector

📈  It also showed me how advanced visual storytelling can bring to light patterns and exceptions that raw tables alone can’t communicate.

📈  The data came from a CSV file, downloaded from Kaggle.com, which I cleaned and explored in Excel and then visualised in Tableau Public.


### 🔍 Understanding the dataset & Objective
📌 Research Question: How do ESG Risk Levels vary between companies in the Energy and Healthcare sectors when accounting for controversy levels and Social Risk Scores?

📌 Hypothesis: Companies in the Energy sector are more likely to be classified in higher ESG Risk Levels due to their higher controversy levels and lower Social Risk Scores, despite their strong environmental ESG scores. In contrast, companies in the Healthcare sector, which may have lower controversy levels and higher Governance ESG scores, will be classified in lower ESG Risk Levels.

---

### 🔧 Tools Used

![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

### 📁 Project Breakdown

#### 1️⃣ Python Analysis
- Data cleaning, merging, and exploration using Pandas
- ESG score distribution, sector-based insights
- [View Notebook →](./python-analysis/esg_analysis.ipynb)

#### 2️⃣ Excel Dashboard
- Initial data cleanup, calculation of sector-wise metrics
- Interactive slicers for sector-based filtering
- Conditional formatting to flag high-risk scores
- [View Excel File →](./excel-analysis/ESG-Insights-Dashboard.xlsx)

#### 3️⃣ Tableau Dashboard
- Uncovering Sector-Wide Disparities & Hidden Anomalies
- Advanced dashboards with custom filters, visual storytelling, and outlier detection
- Includes:
- ESG Risk by Sector and Controversy Heatmap
- ESG Risk Decomposition by Sector (Scatterplots)
- Boxplot of ESG Risk Distribution with Outliers
- Bubble Chart Showing ESG Risk vs. Controversy Anomalies
- Linked charts with interactivity
- [[Tableau Public Dashboard →](#)](https://public.tableau.com/app/profile/ela.maria.vultur/viz/ESGSP500riskinsights/Dashboard2)

---

### 📈 Final Static Visuals & Some Insights
Tableau Dashboard:
![Screenshot 2025-03-21 110302](https://github.com/user-attachments/assets/86aa8e7d-7cdc-4f30-98f4-782c24a41359)
![Screenshot 2025-04-17 180219](https://github.com/user-attachments/assets/19de40db-c4b7-4ba5-9728-18a17ece6353)
Additional:
![Screenshot 2025-04-17 010726](https://github.com/user-attachments/assets/e39ad620-fe45-4a04-8a3a-f3a6e07f17af)
![Screenshot 2025-04-17 180651](https://github.com/user-attachments/assets/3eb2831a-06b3-45d5-919c-cd16f417dd39)
![Screenshot 2025-04-17 010406](https://github.com/user-attachments/assets/86c9b249-f984-4304-b145-fa8d9feeb7b7)
![Screenshot 2025-04-17 012611](https://github.com/user-attachments/assets/bfd24fe6-257b-4306-9c41-c0fc5a7ef8a2)


📌 Some Insights:
💡Investment ESG risk is sector-skewed — Energy and Utilities are high-risk outliers.
* Energy sector’s high score implies systemic ESG challenges, likely driven by environmental concerns like emissions, reliance on fossil fuels, the usage of coal, and regulatory exposure.

* Utilities also show elevated risk, potentially due to environmental impacts (e.g., power generation), aging infrastructure, or poor governance practices.

* Healthcare’s low score is interesting, which can imply either proactive ESG compliance, reduced environmental impact, or more stable governance.

* Real Estate scoring low might indicate newer compliance initiatives or improved sustainability in commercial properties.

This visualization could guide sustainable investors or ESG fund managers in reallocating sector exposure.
📊 Trends / patterns  
🗺️ Maps  
📈 Time series  
📉 Before/after comparisons
*(Include a few dashboard or chart screenshots here)*

---


### 📊 Here are some of the key insights I uncovered:* 🧠
Energy sector companies exhibit more volatility in ESG risk scores. Many companies have high ESG risk despite low controversy levels, which is atypical.
Healthcare sector companies show tighter ESG risk distributions with fewer outliers. Their strong governance scores and moderate social risk correlate with lower ESG risk.

🔎 1. Unexpected Anomalies
Some Energy sector companies had low controversy levels but high ESG risk scores, which is counterintuitive—typically, low controversy implies lower risk.

For example, companies like Wells Fargo & Co. stood out, having high ESG risk scores despite low controversy levels, flagging possible governance or social issues not captured by controversy ratings alone. Also, Hasbro, Inc. had surprisingly low ESG risk in comparison to its moderate controversy peers.
Thermo Fisher Scientific was another standout in low controversy with above-average ESG risk.

🔍 2. Sector Disparities
Using a boxplot, I showed how Energy and Financial Services sectors had the widest spread and highest median ESG risk, while Technology and Healthcare tended to have lower ESG risk overall.

This suggests investors and compliance officers might need to treat ESG risk differently across sectors instead of applying a uniform scoring logic.

📊 3. Risk Decomposition
I decomposed ESG risk into Environmental, Social, and Governance sub-scores and visualised how these influence total ESG risk.

Healthcare companies often had lower social risk scores, which brought down their total ESG risk despite mixed performance in Environmental and Governance metrics.

Energy companies, in contrast, had high environmental scores, but their governance and social risk scores were weaker, pulling up their total ESG risk.

💥 4. Visual Patterns and Outliers
I used bubble charts to plot companies by controversy level vs total risk and highlighted companies that deviated from the expected trend (low controversy = low risk).



---
## 📚 License
This project is licensed under the MIT License.

## 👩‍💻 Author

Ela Maria Vultur  
Feel free to connect if you want to collaborate or have feedback!

