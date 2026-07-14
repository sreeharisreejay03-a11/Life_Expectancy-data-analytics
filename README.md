# Life_Expectancy-data-analytics
Data analytics project
# 🌍 Life Expectancy Data Analysis

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on the World Health Organization (WHO) Life Expectancy dataset. The objective is to understand the factors that influence life expectancy across different countries and years by applying data cleaning, visualization, and statistical analysis techniques.

The project was developed using Python and focuses on uncovering meaningful insights from health, economic, and social indicators.

---

## 🎯 Objectives

- Analyze global life expectancy trends.
- Identify factors affecting life expectancy.
- Handle missing values and inconsistent data.
- Detect and analyze outliers.
- Perform exploratory data analysis using various visualizations.
- Generate meaningful insights from the dataset.

---

## 📂 Dataset
https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who
The dataset contains information about multiple countries over several years, including:

- Country
- Year
- Status (Developed/Developing)
- Life Expectancy
- Adult Mortality
- Infant Deaths
- Alcohol Consumption
- Percentage Expenditure
- Hepatitis B
- Measles
- BMI
- Under-five Deaths
- Polio
- Total Expenditure
- Diphtheria
- HIV/AIDS
- GDP
- Population
- Thinness (1–19 years)
- Thinness (5–9 years)
- Income Composition of Resources
- Schooling

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset inspection
- Missing value analysis
- Missing value imputation
- Duplicate value checking
- Descriptive statistics
- Outlier detection using IQR
- Correlation analysis
- Feature distribution analysis

---

## 📈 Visualizations

The notebook contains several visualizations including:

- Histograms
- Bar Charts
- Pie Charts
- Boxplots
- Scatter Plots
- Line Charts
- Correlation Heatmap

These visualizations help understand:

- Distribution of features
- Country-wise comparisons
- Relationship between variables
- Detection of outliers
- Trends over time

---

## 🔍 Key Insights

- Developed countries generally have higher life expectancy than developing countries.
- Higher GDP and increased schooling are positively associated with life expectancy.
- HIV/AIDS and Adult Mortality show a negative relationship with life expectancy.
- Population contains extreme values due to naturally large populations in countries like India and China; these were treated as valid observations rather than errors.
- Missing values were handled using appropriate imputation techniques to preserve data quality.

---

## 📁 Project Structure

```
Life-Expectancy-Data-Analysis/
│
├── life.ipynb
├── README.md
└── dataset.csv
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Life-Expectancy-Data-Analysis.git
```

2. Navigate to the project folder

```bash
cd Life-Expectancy-Data-Analysis
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the notebook

```bash
jupyter notebook
```

---

## 📌 Results

The analysis demonstrates that healthcare, education, economic development, and disease prevalence significantly influence life expectancy across countries. The project provides valuable insights through statistical analysis and data visualization, making it useful for understanding global health patterns.

---

## 📚 Future Improvements

- Build predictive machine learning models for life expectancy.
- Create an interactive dashboard using Streamlit or Power BI.
- Develop geographical visualizations using Plotly or Folium.
- Perform feature engineering for deeper analysis.
