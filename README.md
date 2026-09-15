# 🎮 GameSense – Gaming Performance & Player Well-Being Analytics

An end-to-end **Data Analytics project** where I used **Python and Power BI** to analyze gaming performance data, understand how health and lifestyle habits relate to in-game performance, and generate meaningful player insights.

---
# 📊 Power BI Dashboard

The GameSense Power BI dashboard provides insights into player demographics, gaming performance, gaming behaviour, and player well-being.

---

## 🎮 Game Sense Overview

![Game Sense Overview](./Dashboard/Game%20Sense%20over%20view.png)

---

## 🏆 Game Sense Performance Analysis

![Game Sense Performance Analysis](./Dashboard/Game%20Sense%20Performance%20Analysis.png)

---

## ❤️ Game Sense Health & Gaming Behaviour Analysis

![Game Sense Health & Gaming Behaviour Analysis](./Dashboard/Game%20Sense%20Health%20%26%20Gaming%20Behaviour%20Analysis.png)

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
```

---

## 📂 Project Structure

```
GameSense-Gaming-Performance-Player-Well-Being-Analytics/
│
├── Dashboard/
│   ├── Game Sense Health & Gaming Behaviour Analysis.png
│   ├── Game Sense Performance Analysis.png
│   └── Game Sense over view.png
│
├── data/
│   ├── gameSense_cleaned.xlsx
│   └── game_sense_raw.csv
│
├── power bi/
│   └── GameSense.pbix
│
├── python/
│   └── GameSense.ipynb
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

**Raw data:** `data/game_sense_raw.csv`
**Cleaned data:** `data/gameSense_cleaned.xlsx`

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

## 📌 Power BI Dashboard

I used the cleaned gaming data (`data/gameSense_cleaned.xlsx`) to build an interactive, multi-page Power BI dashboard.

### 📄 Dashboard Pages

| Page                                                      | Purpose                                                                    |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `Game Sense over view`                                       | High-level summary of win rate, APM, and reaction time by player               |
| `Game Sense Performance Analysis`                            | Deep dive into performance metrics and trends                                  |
| `Game Sense Health & Gaming Behaviour Analysis`              | Relationship between sleep, screen time, session length, and performance        |

### 📊 Dashboard KPIs

| Object                | Type     | Purpose                                            |
| ----------------------- | -------- | ----------------------------------------------------- |
| `Average Win Rate`      | KPI Card | Overall win rate across all players                  |
| `Average APM`           | KPI Card | Average actions per minute                            |
| `Average Reaction Time` | KPI Card | Average reaction time in milliseconds                 |
| `Average Sleep Hours`   | KPI Card | Average sleep hours across players                    |
| `Total Sessions`        | KPI Card | Total number of gaming sessions analyzed               |

Page preview images are available inside `Dashboard/`.

### 🎚️ Slicers

| Object          | Type   | Purpose                                    |
| ----------------- | ------ | --------------------------------------------- |
| `Player`           | Slicer | Filters the dashboard by individual player     |
| `Game Genre`       | Slicer | Filters the dashboard by game genre            |
| `Date`             | Slicer | Filters the dashboard by session date          |

The Power BI report is available at: `power bi/GameSense.pbix`

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
   Navigate to `power bi/GameSense.pbix` and open the file using Microsoft Power BI Desktop.

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
