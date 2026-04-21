# Global Market Opportunity Analysis with Python

## 1. Problem & User
This project asks a simple business question: **which countries combine large market size and strong growth?**  
It is designed for **international business students and beginner market analysts** who want a clear, portfolio-ready example of Python-based economic analysis.

## 2. Data
- **Source:** Plotly Express built-in Gapminder dataset (country-level development indicators based on Gapminder)
- **Access date:** 20 April 2026
- **File used in this repository:** `data/gapminder_clean.csv`
- **Main variables:** country, continent, year, life expectancy, population, GDP per capita

## 3. Methods
This project uses Python for:
- loading and inspecting the dataset
- cleaning and selecting relevant columns
- creating an estimated `total_gdp_usd` variable
- aggregating continent-level indicators for 2007
- identifying the top markets by estimated total GDP
- measuring GDP per capita growth from 1997 to 2007
- building a simple **market opportunity matrix** using size and growth thresholds
- visualising results with matplotlib

## 4. Key Findings
- **Oceania** has the highest average GDP per capita in 2007, while **Europe** is the strongest large multi-country region.
- The **United States** is the largest market by estimated total GDP in the 2007 snapshot.
- Among countries with population above 20 million, **China** and **India** stand out for combining scale and strong growth.
- A simple size-growth screen identifies **China, India, and Korea, Rep.** as the main priority markets in this dataset.

## 5. Repository Structure
```text
README.md
notebook.ipynb
data/gapminder_clean.csv
figures/
requirements.txt
demo_video_script.md
reflection_report.docx
reflection_report.md
```

## 6. How to Run
1. Download or clone this repository.
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `notebook.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook from top to bottom.

## 7. Product Link / Demo
- **GitHub repository link:** [Replace with your GitHub repo link after uploading]
- **Demo video link:** [Replace with your 1–3 minute demo video link]

## 8. Main Output Figures
### Average GDP per Capita by Continent (2007)
![Continent GDP per capita](figures/continent_avg_gdp_per_capita_2007.png)

### Top 10 Markets by Estimated Total GDP (2007)
![Top markets](figures/top10_total_gdp_2007.png)

### Fastest GDP per Capita Growth (1997–2007, Population ≥ 20M)
![Fastest growth](figures/fastest_growth_1997_2007.png)

### Market Opportunity Matrix
![Opportunity matrix](figures/market_opportunity_matrix.png)

## 9. Limitations & Next Steps
- The dataset ends in 2007, so it is best used as a learning and portfolio project rather than a real-time decision tool.
- Estimated total GDP is a simplified measure and should not replace official national accounts.
- Future improvements could add newer World Bank or IMF data, industry-level indicators, and an interactive dashboard version.
AI used:Chat GDP
