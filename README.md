# Task 6: Data Visualization - Python Charts for Insights

**Domain:** Data Analysis (COVID-19 Trends)  
**Tools:** Python, Pandas, Matplotlib  
**Dataset:** [New York Times COVID-19 Data (GitHub)](https://github.com/nytimes/covid-19-data)

---

## 📌 Project Overview
This project analyzes the COVID-19 pandemic trends in the United States using Python. The goal is to maximize data storytelling through professional visualizations and derive meaningful insights regarding the spread and impact of the virus across different states.

## 📂 Files Included
- **`Task6_Visualization.ipynb`**: The main Jupyter Notebook containing all code, charts, and analysis.
- **`README.md`**: Project documentation (this file).

## 🚀 How to Run
1. **Open the Notebook**:
   - You can open `Task6_Visualization.ipynb` in **Google Colab**, **Jupyter Notebook**, or **VS Code**.
2. **Install Dependencies** (if running locally):
   ```bash
   pip install pandas matplotlib
   ```
3. **Run All Cells**:
   - The notebook automatically fetches the latest data from the NYT GitHub repository. No manual download is required.

## 📊 Visualizations Created
1. **Bar Chart**: 
   - *Top 10 US States by Total Cases*
   - Highlights the "hotspots" and most affected regions.
2. **Line Chart**: 
   - *Total US Cases Over Time*
   - Visualizes the pandemic's trajectory, showing distinct waves and growth rates.
3. **Histogram**: 
   - *Distribution of Deaths Across States*
   - Analyzes the skewness of mortality counts among states.
4. **Scatter Plot**: 
   - *Total Cases vs. Total Deaths*
   - Examines the correlation between infection rates and mortality figures.

## 💡 Key Insights
1. **Concentration of Impact**: A small number of high-density states (California, Texas, Florida, NY) account for a disproportionately massive share of national cases.
2. **Seasonal Patterns**: The infection rate was not linear; clear "waves" of steeper growth are visible during winter months (2020/2021).
3. **Strong Correlation**: There is a near-perfect positive linear relationship between cases and deaths, indicating that higher case counts universally strained mortality rates with few outliers.

---
*Submitted for Data Analyst Internship Task 6.*
