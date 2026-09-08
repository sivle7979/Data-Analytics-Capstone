```markdown
# Kenya Economic & Employment Intelligence Dashboard

**Data Analytics Capstone Project**

A complete end-to-end data analytics project that explores the relationship between Kenya’s economic performance, investment, unemployment, and inflation from 2015 to 2024.

---

## Business Problem

The Ministry of Labour and financial institutions need clear, data-driven insights into how Kenya’s economic growth relates to employment and inflation. This project delivers a structured analytical pipeline and an interactive dashboard to support better policy and financial decision-making.

---

## Project Objectives

- Collect and clean official economic data from KNBS and the World Bank
- Build a reliable analytical dataset (2015–2024)
- Perform Exploratory Data Analysis (EDA) and statistical analysis
- Store the data in PostgreSQL
- Create an interactive Power BI dashboard
- Document the full workflow in Jupyter notebooks

---

## Tools & Skills Demonstrated

| Area                    | Tools / Technologies                  |
|-------------------------|---------------------------------------|
| Data Collection         | Python, World Bank API / WDI, KNBS    |
| Data Cleaning & ETL     | Pandas, Jupyter Notebooks             |
| Statistical Analysis    | SciPy, Statsmodels                    |
| Database                | PostgreSQL                            |
| Dashboard               | Power BI                              |
| Version Control         | Git & GitHub                          |
| Documentation           | Markdown, Jupyter                     |

---

## Project Structure

```
Data-Analytics-Capstone/
│
├── notebooks/
│   ├── 01_python_postgresql_setup.ipynb
│   └── 02_knbs_national_accounts.ipynb
│
├── processed/
│   ├── kenya_economic_data_2015_2024.csv
│   ├── kenya_economic_dashboard_data.csv
│   └── Power Bi Trend Dashbord.pbix
│
├── raw/                          # Original source files (optional)
│
└── README.md
```

---

## Data Sources

| Source                          | Indicators Used                              | Years    |
|---------------------------------|----------------------------------------------|----------|
| KNBS Statistical Abstract 2025  | GDP (current prices), GDP growth, GFCF       | 2015–2024 |
| World Bank WDI                  | Unemployment rate, Consumer price inflation  | 2015–2024 |

**Final Dataset**
- 10 annual observations
- 6 variables
- Zero missing values

---

## Key Findings

1. **Strong economic expansion** – Nominal GDP more than doubled from KSh 6.88 trillion (2015) to KSh 16.22 trillion (2024).

2. **Job-poor growth** – Despite rising GDP and investment (GFCF), the unemployment rate nearly doubled (from ~2.8% to ~5.5%). Correlation between GDP level and unemployment: **r = 0.83** (p < 0.01).

3. **Investment closely tracks GDP** – Gross Fixed Capital Formation and GDP are almost perfectly correlated (**r = 0.99**).

4. **COVID impact** – GDP growth contracted by –0.3% in 2020, then rebounded strongly to 7.6% in 2021.

5. **Inflation volatility** – Peaks in 2017 (~8.0%) and 2022–23 (~7.7%), moderating to 4.5% in 2024.

6. **Regression insight** – The size of the economy (log GDP) explains ~78% of the variation in unemployment (R² = 0.777), while year-to-year growth rates show little association with unemployment.

---

## Analytical Pipeline Completed

```
Data Collection          ✅
Data Cleaning            ✅
Data Validation          ✅
Exploratory Data Analysis ✅
Statistical Analysis     ✅
PostgreSQL Storage       ✅
Power BI Dashboard       ✅
Documentation & GitHub   ✅
```

---

## How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/sivle7979/Data-Analytics-Capstone.git
   cd Data-Analytics-Capstone
   ```

2. Open the Jupyter notebooks in order:
   - `notebooks/01_python_postgresql_setup.ipynb`
   - `notebooks/02_knbs_national_accounts.ipynb`

3. The cleaned dataset is already available in:
   ```
   processed/kenya_economic_data_2015_2024.csv
   ```

4. Open the Power BI file:
   ```
   processed/Power Bi Trend Dashbord.pbix
   ```

---

## Dashboard

The Power BI dashboard visualises:
- GDP and GFCF trends
- GDP growth rate
- Unemployment rate
- Inflation rate
- Key performance indicators (KPIs)

---

## Author

**Data Analytics Capstone Project**  
GitHub: [sivle7979](https://github.com/sivle7979)

---

## License

This project is intended for educational and portfolio purposes.
```
