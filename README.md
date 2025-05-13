# 🌍 COVID-19 Global Data Tracker

A data analysis and visualization project that tracks global COVID-19 trends—cases, deaths, recoveries, and vaccinations—across countries and time. This project explores real-world data using Python to generate insights and compelling visual narratives.

---

## 📌 Project Overview

In this project, I built a data analysis notebook that:
- Cleans and processes COVID-19 global data,
- Performs exploratory data analysis (EDA),
- Visualizes key metrics such as case growth, death tolls, and vaccination progress,
- Compares trends across three countries(Kenya, Uganda and Tanzania),
- Presents findings using graphs, charts, and chloropleth maps.

---

## 🚩 Objectives

✅ Import and clean global COVID-19 data  
✅ Analyze time trends (cases, deaths, vaccinations)  
✅ Compare metrics across countries/regions  
✅ Visualize data with interactive charts and a choropleth map  
✅ Communicate insights in a well-documented Jupyter Notebook  

---

## 🛠️ Tools & Libraries

- `pandas` for data loading and manipulation  
- `matplotlib` & `seaborn` for static visualizations  
- `plotly.express` for interactive choropleth maps  
- `Jupyter Notebook` for interactive analysis and reporting  

---

## 🗂️ Project Structure

### 1️⃣ Data Collection  
**Source**: [Our World in Data (OWID)](https://www.kaggle.com/datasets/georgesaavedra/covid19-dataset)  
File used: `owid-covid-data.csv`

### 2️⃣ Data Loading & Exploration  
- Loaded data using `pandas.read_csv()`  
- Explored structure, columns, and missing values  
- Key columns analyzed: `date`, `location`, `total_cases`, `total_deaths`, `new_cases`, `total_vaccinations`, etc.

### 3️⃣ Data Cleaning  
- Focused on specific countries - Kenya, Uganda and Tanzania
- Handled missing values and converted date fields  
- Filtered and formatted the dataset for clean analysis

### 4️⃣ Exploratory Data Analysis (EDA)  
- Visualized total and daily cases over time  
- Analyzed death rates  
- Compared trends between countries  
- Plotted top countries by total cases

### 5️⃣ Vaccination Analysis  
- Tracked cumulative vaccinations  
- Compared percentage of population vaccinated  
- Displayed progress with line and optional pie charts

### 6️⃣ Choropleth Map (Interactive 🌐)  
- Built using `plotly.express`  
- Visualized total cases by country  
- Utilized ISO country codes and latest available data

### 7️⃣ Insights & Reporting  
- Summarized findings using markdown cells  
- Highlighted anomalies, patterns, and key takeaways  
- Delivered a clean, presentation-ready report in Jupyter Notebook

---

## 📊 Sample Visuals

- Line charts showing COVID-19 cases/deaths over time  
- Bar plots comparing countries  
- Choropleth map showing global case density  
- Vaccination rollout charts

---

## 📁 Deliverables

- 📓 `COVID19_Data_Tracker.ipynb`: Interactive notebook with code, visuals, and narrative  
- 🌐 Interactive choropleth map for global view  

---

## 💡 Key Insights

1. High case density: North America, Europe, and parts of South America.

2. Low case density but potentially underreported: Many African and Southeast Asian countries.

3. From the choropleth visualization, it’s evident that Kenya had one of the higher reported case densities in East Africa.Tanzania appeared lower, but this could be due to underreporting, especially in early phases of the pandemic.

---

## 🚀 How to Run

1. Clone this repository.
2. Download `owid-covid-data.csv` from [Our World in Data](https://www.kaggle.com/datasets/georgesaavedra/covid19-dataset).
3. Open the notebook `COVID19_Global_Data_Tracker.ipynb` in Jupyter.
4. Run cells step-by-step and explore the results.

