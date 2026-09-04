# 📊 Data Visualization & Titanic Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge" alt="Seaborn">
  <img src="https://img.shields.io/badge/EDA-Exploratory%20Analysis-2EA44F?style=for-the-badge" alt="EDA">
  <img src="https://img.shields.io/badge/Status-Completed-2EA44F?style=for-the-badge" alt="Status">
</p>

<p align="center">
  <b>A Python data-analysis project exploring demographic patterns and Titanic survival outcomes through data cleaning, EDA, statistical analysis, and visualization.</b>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-projects">Projects</a> •
  <a href="#-visualizations">Visualizations</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-insights">Insights</a>
</p>

---

## ✨ Overview

This repository contains two related Python data-analysis workflows:

### 🚢 Titanic Survival Analysis
Explores passenger information from the **Titanic dataset** to investigate patterns associated with survival using data cleaning, exploratory analysis, correlation analysis, and a range of statistical visualizations.

### 👥 Demographic Data Visualization
Explores demographic information through visualizations of **gender, age groups, and occupation**, using bar charts and histograms to identify distribution patterns.

The project focuses on turning raw tabular data into clear visual insights using a practical Python data-analysis workflow.

---

# 🚀 Projects

## 🚢 1. Titanic Survival Analysis

The Titanic analysis investigates factors associated with passenger survival using the Titanic dataset.

### 🧹 Data Cleaning

The analysis includes:

- Handling missing values in `Age`
- Handling missing values in `Embarked`
- Handling missing values in `Fare`
- Dropping the `Cabin` column because of extensive missing data

### 🔎 Exploratory Data Analysis

The project explores:

- Summary statistics of numerical variables
- Cross-tabulations
- Correlation analysis
- Relationships between passenger characteristics and survival

### 📊 Visual Analysis

The workflow includes:

- Count plots for survival by age, gender, passenger class, and embarkation port
- Box plots
- Violin plots
- Histograms
- Swarm plots
- Pie charts
- Correlation heatmaps

---

## 👥 2. Demographic Data Visualization

A Python visualization workflow focused on understanding demographic distributions.

### 📊 Bar Graphs

The analysis includes visualizations for:

- Gender distribution
- Occupation distribution
- Average age by occupation
- Gender distribution across age groups

### 📈 Histograms

The project also explores:

- Age distribution
- Age distribution by gender
- Age distribution with density estimation (KDE)
- Age-group distribution

---

# 🔄 Analysis Workflow

```text
              ┌─────────────────────┐
              │      Raw Data       │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │   Data Cleaning     │
              │ Missing Values      │
              │ Data Preparation    │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Exploratory Data    │
              │      Analysis       │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Statistical &       │
              │ Correlation Analysis│
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Data Visualization  │
              │ Charts & Plots      │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Visual Insights     │
              └─────────────────────┘
```

---

# 📈 Visualizations

## 🚢 Titanic Analysis

| Visualization | Purpose |
|---|---|
| 📊 Count Plots | Compare survival across categorical variables |
| 📦 Box Plots | Examine distribution and spread |
| 🎻 Violin Plots | Compare distributions across survival groups |
| 📈 Histograms | Explore numerical distributions |
| 🐝 Swarm Plots | Inspect individual observations |
| 🥧 Pie Charts | View survival proportions |
| 🔥 Heatmaps | Explore numerical correlations |

## 👥 Demographic Analysis

| Visualization | Purpose |
|---|---|
| 📊 Bar Charts | Compare demographic categories |
| 📈 Histograms | Explore age distributions |
| 📉 KDE Plots | Visualize estimated distribution density |
| 👥 Grouped Comparisons | Examine gender and age-group relationships |

---

# 💡 Insights Explored

The Titanic analysis investigates patterns such as:

- 👩 Differences in survival between female and male passengers
- 🎫 Differences in survival across passenger classes
- 🧒 Relationships between age and survival
- 💰 Relationships between fare levels and survival
- ⚓ Differences associated with embarkation ports

The demographic workflow investigates:

- 👥 Gender composition
- 🎂 Age distribution
- 💼 Occupation distribution
- 📊 Average age across occupations
- 👤 Gender distribution across age groups

> These are exploratory observations from the datasets and visual analysis, not causal conclusions.

---

# 🛠️ Tech Stack

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib">
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" alt="Seaborn">

</p>

---

# 📁 Repository Structure

```text
Data-Visualization-Project/
│
├── 📄 Demographic Data Visualization
├── 📄 Titanic Survival Analysis
├── 📊 Titanic.csv
├── 📊 sample.csv
└── 📄 README.md
```

> The repository currently contains the Titanic dataset and sample data alongside the analysis scripts shown in the project listing.

---

# ⚙️ Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Divakar1326/Data-Visualization-Project.git
cd Data-Visualization-Project
```

## 2️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

## 3️⃣ Run a Project

Run the relevant Python file from the repository:

```bash
python "<script-name>.py"
```

> Replace `<script-name>.py` with the actual Python filename in the repository.

---

# 📋 Expected Titanic Dataset Fields

The Titanic workflow expects fields such as:

```text
PassengerId
Survived
Pclass
Name
Sex
Age
SibSp
Parch
Ticket
Fare
Cabin
Embarked
```

---

# 🧠 What This Project Demonstrates

- 🧹 Data cleaning and missing-value handling
- 📊 Exploratory Data Analysis
- 📐 Basic statistical analysis
- 🔗 Correlation analysis
- 📈 Data visualization
- 🐼 Pandas-based data manipulation
- 🎨 Matplotlib and Seaborn visualization
- 🔍 Pattern discovery from real-world-style datasets

---

# 🌱 Learning Focus

This project was built to practice the complete path from **raw tabular data to interpretable visual insights**.

The emphasis is on understanding datasets, preparing them for analysis, selecting appropriate visualizations, and communicating patterns clearly.

---

# 🔮 Future Improvements

Potential extensions include:

- 📊 Add an interactive Streamlit dashboard
- 🔎 Add deeper statistical testing
- 🤖 Add a survival-prediction machine learning model
- 📈 Add interactive Plotly visualizations
- 🧪 Add reusable analysis functions
- 📦 Add a reproducible `requirements.txt`

---

# 👨‍💻 Author

## Divakar M

**B.Tech CSE — Artificial Intelligence & Data Science**

AI/ML • Generative AI • Python • Data Science

<p align="center">
  <a href="https://github.com/Divakar1326">
    <img src="https://img.shields.io/badge/GitHub-Divakar1326-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

---

<p align="center">
  ⭐ If you find this project useful, consider starring the repository.
</p>

<p align="center">
  <b>Turning Data into Visual Insights 📊</b>
</p>
