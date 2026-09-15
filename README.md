# 🎮 GameSense – Gaming Performance & Player Well-Being Analytics

An end-to-end **Data Analytics project** where I used **Python and Power BI** to analyze gaming performance data, understand how health and lifestyle habits relate to in-game performance, and generate meaningful player insights.

---

## 🖼️ Final Dashboard

![GameSense Dashboard](dashboard/GameSense_Dashboard.png)

---

## 📌 Project Overview

In this project, I analyzed gamer performance and well-being data to understand:

- Overall player performance (win rate, APM, reaction time)
- The relationship between health habits (sleep, screen time) and performance
- Session activity and engagement patterns
- Performance differences across player segments
- Outliers and data distribution
- Key player performance indicators

I followed a complete data analytics workflow from start to finish:

**Raw Data → Data Cleaning → Exploratory Data Analysis → Visualization → KPI Analysis → Power BI Dashboard → Business Insights**

---

## 🎯 Project Objectives

The main objectives I set out to achieve in this project were to:

- Understand and inspect the raw gaming performance dataset
- Clean and prepare the data for analysis
- Handle missing and inconsistent values
- Perform exploratory data analysis on 2,500+ gaming records
- Analyze player performance (win rate, APM, reaction time)
- Analyze health and gaming behaviour (sleep, screen time, session length)
- Identify relationships between well-being and performance
- Perform outlier analysis
- Create meaningful player performance KPIs
- Build an interactive multi-page Power BI dashboard
- Document the complete analysis process

---

## 🔄 Project Workflow

```
Raw Dataset
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Missing Value & Outlier Analysis
     ↓
Data Transformation
     ↓
Exploratory Data Analysis
     ↓
Python Visualizations
     ↓
KPI Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
     ↓
Project Documentation
```

---

## 📂 Project Structure

> Placeholder layout — update the paths below to match your actual repo folders/files.

```
GameSense-Gaming-Performance-Player-Well-Being-Analytics/
│
├── Power BI/
│   └── GameSense_Dashboard.pbix
│
├── dashboard/
│   ├── Performance_Analysis.png
│   ├── Health_and_Gaming_Behaviour_Analysis.png
│   ├── Player_Performance_Overview.png
│   └── GameSense_Dashboard.png
│
├── data/
│   ├── cleaned/
│   │   └── GameSense_cleaned.csv
│   │
│   └── raw/
│       └── GameSense_raw.csv
│
├── documentation/
│   └── GameSense_Project_Documentation.pdf
│
├── python/
│   └── GameSense.ipynb
│
├── python_visualizations/
│   ├── Boxplot of Reaction Time.png
│   ├── Boxplot of Sleep Hours.png
│   ├── Boxplot of Session Duration.png
│   ├── Correlation Matrix.png
│   ├── Win Rate by Player.png
│   ├── APM vs Win Rate.png
│   ├── Sleep vs Performance.png
│   └── Screen Time vs Reaction Time.png
│
└── README.md
```

---

## 📊 Dataset

I used a gaming performance and player well-being dataset containing information about player sessions, in-game performance metrics, and health/lifestyle habits.

### Main Fields

| Object            | Description                                   |
| ----------------- | ---------------------------------------------- |
| `Player ID`        | Identifier of the player                       |
| `Session ID`        | Identifier of the gaming session               |
| `Win Rate`          | Percentage of matches won                      |
| `APM`               | Actions per minute during a session            |
| `Reaction Time`     | Player's average reaction time (ms)            |
| `Sleep Hours`       | Hours of sleep before the session               |
| `Screen Time`       | Total daily screen time                        |
| `Session Duration`  | Length of the gaming session                    |
| `Game Genre`        | Genre of the game played                        |
| `Date`               | Date of the session                            |

---

## 🧹 Data Cleaning

I performed all data cleaning using Python and Pandas.

My cleaning process included:

- Dataset structure inspection
- Data type checking
- Missing value analysis
- Duplicate record identification and removal
- Date conversion
- Data transformation
- Creation of analytical columns
- Outlier analysis
- Final data quality checks

---

## 🔎 Exploratory Data Analysis

I performed exploratory data analysis using:

- Pandas
- NumPy
- Matplotlib
- Seaborn

My analysis includes:

**🎮 Performance Analysis**

- Win rate distribution
- APM distribution and trends
- Reaction time analysis
- Top-performing players

**🩺 Health & Gaming Behaviour Analysis**

- Sleep hours vs performance
- Screen time vs reaction time
- Session duration patterns

**📦 Distribution & Outlier Analysis**

- Reaction time boxplot
- Sleep hours boxplot
- Session duration boxplot
- Correlation matrix

---

## 📊 Python Visualizations

I generated the following visualizations as part of the analysis:

| Object                              | Purpose                                                   |
| ------------------------------------ | ---------------------------------------------------------- |
| `Boxplot of Reaction Time`            | Identify reaction time distribution and outliers            |
| `Boxplot of Sleep Hours`              | Analyze sleep distribution and outliers                     |
| `Boxplot of Session Duration`         | Analyze session length distribution and outliers            |
| `Correlation Matrix`                  | Understand relationships between numerical variables         |
| `Win Rate by Player`                  | Compare win rate across players                              |
| `APM vs Win Rate`                     | Analyze the relationship between actions-per-minute and wins |
| `Sleep vs Performance`                | Analyze how sleep relates to in-game performance             |
| `Screen Time vs Reaction Time`        | Analyze how daily screen time relates to reaction speed       |

---

## 📌 Power BI Dashboard

I used the cleaned gaming data to build an interactive, multi-page Power BI dashboard.

### 📄 Dashboard Pages

| Page                                  | Purpose                                                            |
| --------------------------------------- | -------------------------------------------------------------------- |
| `Player Performance Overview`           | High-level summary of win rate, APM, and reaction time by player    |
| `Performance Analysis`                  | Deep dive into performance metrics and trends                       |
| `Health & Gaming Behaviour Analysis`    | Relationship between sleep, screen time, session length, and performance |

### 📊 Dashboard KPIs

| Object                | Type     | Purpose                                            |
| ----------------------- | -------- | ----------------------------------------------------- |
| `Average Win Rate`      | KPI Card | Overall win rate across all players                  |
| `Average APM`           | KPI Card | Average actions per minute                            |
| `Average Reaction Time` | KPI Card | Average reaction time in milliseconds                 |
| `Average Sleep Hours`   | KPI Card | Average sleep hours across players                    |
| `Total Sessions`        | KPI Card | Total number of gaming sessions analyzed               |

The individual page previews are available inside `dashboard/`, and a full dashboard preview image is available at `dashboard/GameSense_Dashboard.png`.

### 🎚️ Slicers

| Object          | Type   | Purpose                                    |
| ----------------- | ------ | --------------------------------------------- |
| `Player`           | Slicer | Filters the dashboard by individual player     |
| `Game Genre`       | Slicer | Filters the dashboard by game genre            |
| `Date`             | Slicer | Filters the dashboard by session date          |

The Power BI report is available at: `Power BI/GameSense_Dashboard.pbix`

---

## 🛠️ Tools & Technologies

| Object             | Usage                                  |
| ------------------- | ---------------------------------------- |
| `Python`             | Data analysis and cleaning               |
| `Pandas`             | Data manipulation                        |
| `NumPy`              | Numerical analysis                       |
| `Matplotlib`         | Visualization                            |
| `Seaborn`            | Visualization                            |
| `Jupyter Notebook`   | Python analysis                          |
| `Power BI`           | Dashboard and business intelligence       |
| `Power Query`        | Data transformation                      |
| `DAX`                | KPI calculations                         |
| `GitHub`             | Project repository and version control    |

---

## 📁 Data Files

**Raw Data** — `data/GameSense_raw.csv`
Contains the original dataset used for the project.

**Cleaned Data** — `data/GameSense_cleaned.csv`
Contains the processed dataset used for further analysis and dashboard development.

---

## 🐍 Python Analysis

The complete Python analysis is available in: `python/GameSense.ipynb`

The notebook covers:

- Importing libraries
- Loading the dataset
- Data inspection
- Data cleaning
- Missing value analysis
- Data transformation
- Exploratory data analysis
- Visualization
- Outlier analysis
- Final data validation

---

## 📄 Documentation

Detailed project documentation is available here: `documentation/GameSense_Project_Documentation.pdf`

The documentation walks through the full analysis process, visualizations, dashboard, findings, and conclusions.

---

## 💡 Business Insights

Through this analysis, I was able to answer important questions such as:

- Which players have the highest win rate and APM?
- How does sleep affect in-game performance?
- Does screen time correlate with reaction time?
- Which factors most strongly relate to win rate?
- Are there unusual performance or health values?
- What are the key player performance indicators?

These insights can support better decisions related to:

- Player coaching and training focus
- Health and well-being recommendations for players
- Identifying at-risk performance patterns
- Understanding what drives consistent wins

---

## 🚀 How to Run the Project

1. **Clone the repository**

```
git clone https://github.com/ajaykumar-mandoju/GameSense-Gaming-Performance-Player-Well-Being-Analytics.git
```

2. **Open the Python notebook**
   Navigate to `python/GameSense.ipynb` and open it using Jupyter Notebook, JupyterLab, or VS Code.

3. **Run the Python analysis**
   Run the notebook cells to reproduce the data cleaning, exploratory data analysis, and visualizations.

4. **Open the Power BI dashboard**
   Navigate to `Power BI/GameSense_Dashboard.pbix` and open the file using Microsoft Power BI Desktop.

---

## 🔮 Future Improvements

Some improvements to explore next:

- Adding predictive modeling for win rate
- Adding more advanced Power BI drill-through pages
- Automating data refresh
- Expanding the dataset with more players and sessions
- Deploying the dashboard as a web application

---

## 👨‍💻 Author

**Mandoju Ajay Kumar**
Data Analyst | Data Analytics Student

**Team:** Data Dynamos — Teja Sri, Ajay Kumar, Lahari
**Institution:** TEKS Academy

**Skills demonstrated in this project:** Python, Pandas, NumPy, Matplotlib, Seaborn, Power BI, Power Query, DAX, Exploratory Data Analysis, Data Cleaning, Data Visualization, Business Intelligence

### 🔗 Connect With Me

- **GitHub:** [ajaykumar-mandoju](https://github.com/ajaykumar-mandoju)
- **Email:** mandojuajaykumar@gmail.com

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.
