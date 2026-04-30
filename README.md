# US Macroeconomic Analysis Post-COVID (2021–2025)  

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/matplotlib-%2345818e.svg?style=for-the-badge&logo=matplotlib&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Kaggle](https://img.shields.io/badge/kaggle-%23318CE7.svg?style=for-the-badge&logo=kaggle&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)  

Welcome to my US Macroeconomic Analysis Portfolio Project! In this project, I conduct a comprehensive analysis of the United States economy during the post-COVID era (2021–2025). Using data directly from the Federal Reserve Economic Data (FRED) API, I examine the intricate relationships between inflation, monetary policy, and labor market resilience.  

## Project Scope
The focus of this project is to analyze the "immaculate disinflation" and the Federal Reserve's tightening cycle. By examining 25 different macroeconomic indicators, I aim to provide insights into why a recession failed to materialize despite a 26-month yield curve inversion and how structural shifts have impacted the labor market.  

## Reports
**Interactive Power BI Dashboard:** A multi-page dashboard visualizing inflation snapshots, Fed policy stance, and labor market recovery.
**Comprehensive Python Notebook:** Detailed analysis including SQL queries, OLS regression, and machine learning models.

## Project Structure
### Data Collection
To ensure high-fidelity analysis, data was pulled directly from the St. Louis Fed FRED API. The dataset includes 25 series across five categories:
- **Output & Growth:** Real GDP, Industrial Production.
- **Labour Market:** Unemployment Rate, Nonfarm Payrolls, JOLTS Job Openings.
- **Inflation & Prices:** CPI, Core CPI, PCE, PPI.
- **Monetary Policy:** Federal Funds Rate, M2 Money Supply.
- **Financial Conditions:** 10Y and 2Y Treasury Yields, VIX Volatility Index.

### Data Cleaning and Preprocessing
The project utilized Python (Pandas) for data wrangling and SQLite for advanced macro summaries. Key steps included:
- Standardizing 60 months of data (Jan 2021 – Dec 2025).
- Deriving economically meaningful variables like Real Fed Funds Rate and Yield Spreads.
- Handling time-series lags to respect causality in regression models.

## Exploratory Data Analysis (EDA)
EDA was performed to identify structural breaks and trends in the post-pandemic landscape.
- **Correlation Analysis:** A Pearson Correlation Matrix was used to identify the strongest leads for inflation.
- **Labor Market Dynamics:** Analysis of the Phillips Curve to estimate the post-COVID NAIRU.
- **Monetary Stance:** Evaluation of the Taylor Rule to determine if the Fed was "behind the curve".

## Predictive Models
- **ARIMA(0,2,1):** Used for 12-month inflation forecasting, achieving a MAPE of 5.97% on hold-out data.
- **XGBoost Classifier:** Built to assess the probability of high inflation (CPI > 3%) based on 11 leading indicators, including consumer sentiment and yield spreads.

## Insights and Conclusions
The Taylor Rule Gap: The Fed was approximately 6 percentage points behind the Taylor Rule prescribed rate in 2021–2022.
- **Real Rates:** The real Fed Funds Rate hit -4.47% in 2022, the most stimulative stance since the 1970s.
- **The Inversion Paradox:** The yield curve remained inverted for 26 months (July 2022 – August 2024) without a recession materializing.
- **Structural Labor Shifts:** Post-COVID NAIRU is estimated at 4.41%, higher than the pre-pandemic 4.0%.

## Visualizations
The project findings are supported by several key visualizations:
- **Macro Landscape:** Combined view of CPI, Fed Funds Rate, and Unemployment.
- **Policy Stance:** Taylor Rule vs. Actual Fed Policy.
- **Yield Curve:** 10Y vs. 2Y Treasury spread analysis.
- **Inflation Forecast:** ARIMA model predictions with 95% confidence intervals.

## Challenges and Limitations
- **Sample Size:** The post-COVID era provides a relatively short time series (48–60 months) for complex machine learning models like XGBoost, which ideally require larger datasets for high-confidence binary classification.
- **Structural Breaks:** The unique nature of the pandemic recovery makes historical comparisons (e.g., pre-2020 NAIRU) difficult to apply directly.

## Key Questions Explored
Q1. Was the Fed too loose for too long?  
Yes, the Taylor Rule analysis shows a significant gap in 2021–2022.  

Q2. Is a recession still coming?  
Despite the long yield curve inversion, labor resilience and "immaculate disinflation" suggest a soft landing.

Q3. Where is inflation heading?  
Models suggest inflation may re-accelerate toward ~3.4% by late 2026 if policy eases prematurely.

## Summary of Findings
- Delayed tightening caused inflation to run deeper than necessary.
- The Fed achieved a rare "soft landing" — halving inflation without a recession.
- Monitor M2 Growth and Real Fed Funds Rate as primary leading indicators for future inflation.  

## Author
- <b>©2026 Gaurav Kamble.  
- <b>[LinkedIn](https://www.linkedin.com/in/gaurav-kamble/)</b>
- <b>[Tableau Public](https://public.tableau.com/app/profile/datagaurav/vizzes)</b>
- <b>[Kaggle](https://www.kaggle.com/justgk)</b>
- <b>[Email](mailto:gauravksse@gmail.com)</b>
