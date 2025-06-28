# 🦠 COVID-19 Data Analysis Case Study

This project presents a comprehensive exploratory data analysis (EDA) of **COVID-19 Confirmed**, **Deaths**, and **Recovered** cases globally using Python and Jupyter Notebook. It focuses on time-series trends, country-wise comparisons, and metrics such as recovery and death rates.

---

## 📁 Project Structure

- `case_study.ipynb` – Main notebook performing:
  - Data cleaning and imputation
  - Country-wise and date-wise aggregations
  - Monthly and yearly visualizations
  - Comparative analysis across countries
- Datasets used:
  - `covid_19_confirmed.csv`
  - `covid_19_deaths.csv`
  - `covid_19_recovered.csv`

---

## 🧠 Objectives

- Analyze global COVID-19 spread patterns from 2020 to mid-2021
- Identify countries with the highest and lowest number of confirmed cases, deaths, and recoveries
- Understand monthly and yearly trends
- Evaluate recovery and death rates in specific countries (e.g., US, India, Brazil)

---

## 📊 Key Insights

- **US** has the highest number of confirmed cases and deaths
- **India** has the highest number of recoveries
- **May 2021** recorded the peak number of deaths and recoveries
- Countries like **Micronesia** and **Kiribati** reported negligible or zero cases/deaths
- **Canada** had a high recovery rate in late 2020
- **France** saw the highest single-day spike in April 2021

---

## 📌 Technologies Used

- **Python**: `pandas`, `matplotlib`, `datetime`
- **Jupyter Notebook** for interactive analysis
- CSV-based datasets for time series analysis

---

## 📈 Visualizations Included

- Yearly and Monthly bar charts for:
  - Confirmed cases
  - Deaths
  - Recoveries
- Line plots showing trends for:
  - US, Italy, Brazil over months
- Bar plots comparing:
  - Top and bottom 10 countries by recoveries
  - Death rates per region (e.g., Canada)
  - Total Deaths over time in US
  - Confirmed cases in China Month wise
  - Datewise Highest Confirmed cases
---

## 🗂️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/covid19-case-study.git
   cd covid19-case-study
   ```

2. Install the required Python packages:
   ```bash
   pip install pandas matplotlib
   ```

3. Ensure your dataset files (`.csv`) are in the same directory or update file paths in the notebook.

4. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook case_study.ipynb
   ```

---

## 🔍 Future Enhancements

- Interactive dashboards (using Plotly or Dash)
- Include vaccination data
- Deploy as a web app

---

## 👤 Author

**Soumya Choudhury**  
_Data Science Enthusiast passionate about real-world analytics._
