# Global Socioeconomic Development Dashboard

## 📊 Project Overview

The **Global Socioeconomic Development Dashboard** is an interactive Power BI project that analyzes economic and socioeconomic development across countries using **World Bank World Development Indicators (WDI) 2022 data**.

The dashboard combines indicators related to economic prosperity, health, digital connectivity, education, and employment to provide a comparative view of development across countries.

---

## 🎯 Objectives

The main objectives of this project are to:

- Compare economic and socioeconomic indicators across countries.
- Examine the relationship between GDP per capita and development outcomes.
- Analyze relationships between income, life expectancy, internet usage, education, and unemployment.
- Develop a composite **Development Score** for cross-country comparison.
- Rank countries according to their overall development performance.
- Allow users to explore the development profile of individual countries.

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures, calculations, KPIs, and Development Score
- **Microsoft Excel** – Source data handling
- **World Bank WDI 2022** – Dataset

---

## 📁 Dataset

The project uses **World Bank World Development Indicators (WDI) 2022** data.

Key indicators used include:

- GDP per capita
- Life expectancy
- Internet usage
- Unemployment rate
- Education expenditure

The data was cleaned and transformed using Power Query before being used for analysis and visualization.

---

## 📈 Dashboard Structure

### Page 1 – Global Development Indicators

Provides an overview of global development indicators using:

- Average GDP per capita
- Average life expectancy
- Average internet usage
- Average unemployment rate
- Global GDP per capita map
- GDP per capita vs. life expectancy analysis
- Country-level filtering
- Key insights

### Page 2 – Economic and Social Relationships

Explores relationships between major development indicators using scatter plots:

- GDP per capita vs. life expectancy
- GDP per capita vs. unemployment
- GDP per capita vs. internet usage
- Education expenditure vs. life expectancy

These visualizations help identify patterns and differences across countries.

### Page 3 – Development Ranking

Ranks countries using a composite **Development Score**.

The page includes:

- Average Development Score
- Highest Development Score
- Lowest Development Score
- Number of countries analyzed
- Country development ranking
- Key takeaways

The Development Score combines five dimensions:

**Development Score = (GDP Score + Life Expectancy Score + Internet Score + Education Score + Employment Score) / 5**

This provides a broader measure of development rather than relying only on GDP.

### Page 4 – Country Development Profile

Provides an interactive country-level analysis.

Users can select a country and examine:

- Development Score
- Development Rank
- GDP per capita
- Life expectancy
- Internet usage
- Unemployment rate
- Education expenditure
- Individual development component scores
- Difference between the selected country's score and the global average

---

## 🔍 Key Insights

The dashboard highlights several broad patterns:

- Countries with higher GDP per capita generally tend to have higher life expectancy.
- Internet usage varies substantially across countries, indicating differences in digital connectivity.
- Economic prosperity alone does not fully explain socioeconomic development.
- Countries differ considerably in their overall development performance.
- A composite development measure provides a broader perspective than GDP per capita alone.
- Development outcomes reflect multiple dimensions including health, education, employment, and digital access.

---

## 📂 Project Structure

```text
Global-Socioeconomic-Development-Dashboard/
│
├── Data/
│   └── WDI_2022_Data.csv
│
├── Global_Development_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md