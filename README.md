# Urban Mobility and Economic Productivity in Latin American Cities (2024)

## 📌 Project Overview
This project analyzes the relationship between urban mobility and economic productivity in major Latin American cities during 2024. Using traffic congestion indicators and economic data, the analysis explores whether high congestion levels and longer travel delays are associated with lower economic performance at the city level.

The project was developed as part of a data analytics portfolio and follows a business-oriented approach, simulating an analysis for a regional development institution.

---

## 🎯 Business Questions
The analysis is guided by three core business questions:

1. Which Latin American cities exhibit **high congestion combined with low economic productivity**?
2. Which cities show the **strongest combined performance**, balancing efficient mobility with a strong economic profile?
3. Which mobility-related variables appear to be **most strongly associated with urban economic development**?

---

## 🧠 Executive Summary
This analysis evaluates the relationship between urban mobility—measured through traffic congestion and travel delays—and economic productivity, represented by GDP per capita, in Latin American cities during 2024. The primary objective is to assess whether higher congestion levels are associated with lower productivity, providing insights relevant for transport infrastructure investment decisions.

The dataset covers 15 cities across 7 Latin American countries (Brazil, Colombia, Argentina, Peru, Mexico, Uruguay, and Chile), using mobility indicators from TomTom and economic data from OECD-related sources. After cleaning, standardizing, and integrating the data through an inner join, exploratory analysis was conducted using distribution plots and city-level comparisons.

The results do not indicate a strong linear relationship between congestion and GDP per capita across all cities. However, clear patterns emerge at the city level. Bogotá and Lima stand out as cities combining high congestion levels with relatively low GDP per capita, making them critical cases for policy attention. In contrast, cities such as Buenos Aires show moderate-to-high congestion but significantly higher productivity, suggesting a stronger economic capacity to absorb mobility inefficiencies.

These findings highlight the importance of targeting mobility investments where congestion coincides with lower economic resilience, rather than assuming a uniform impact across cities.

---

## 📊 Data Sources
- **Traffic and mobility indicators**: TomTom Traffic Index (2024)
- **Economic indicators**: OECD-related city-level economic data
- **Geographic scope**: 15 cities across Latin America
- **Time scope**: Year 2024 only

---

## 🧹 Methodology (High Level)
1. Data cleaning and standardization (column names, numeric formats, year extraction).
2. Aggregation at the city–year level using average mobility indicators.
3. Integration of mobility and economic datasets using an inner join.
4. Exploratory validation through distributions, outlier detection, and visual comparisons.
5. City-level analysis focused on congestion intensity and GDP per capita.

---

## 🔍 Key Insights
- High congestion does not uniformly imply low economic productivity across all cities.
- **Bogotá and Lima** emerge as critical cases where high congestion coincides with lower GDP per capita.
- Some cities maintain relatively high productivity despite congestion, indicating differing levels of economic resilience.
- Mobility inefficiency appears to act as a structural constraint mainly in cities with weaker economic profiles.

---

## ⚠️ Limitations
- The analysis is cross-sectional and limited to a single year (2024).
- No causal relationships are established—only observed associations.
- The number of cities is limited, which constrains statistical generalization.
- Other relevant variables (public transport quality, urban density, governance factors) are not included.

---

## 🚀 Recommendations and Next Steps
- Prioritize **Bogotá** as a key candidate for mobility-focused infrastructure investment.
- Consider **Lima** as a secondary priority city for congestion mitigation strategies.
- Extend the analysis to multiple years to assess temporal trends.
- Complement exploratory findings with formal correlation or regression analysis.
- Incorporate public transport and urban form variables to deepen policy insights.

---

## 🛠️ Tools and Technologies
- Python
- Pandas
- Matplotlib / Seaborn
- Google Colab

---

## 📁 Repository Structure

urban-mobility-productivity-2024/
│
├── urban_mobility_economic_productivity_LATAM_2024.ipynb
├── data/
│   └── ladb_mobility_economy_2024_clean.csv
└── README.md


---

## 👤 Author
**Steven Ojeda**  
Data Analyst | Urban Mobility & Economic Analysis  
🔗 LinkedIn: https://www.linkedin.com/in/steven-ojedac/
