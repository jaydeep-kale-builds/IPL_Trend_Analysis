IPL Trend Analysis

An end-to-end **Data Analytics project** analyzing IPL ball-by-ball data from **2008–2023**. The project covers data loading, cleaning, exploratory data analysis (EDA), feature engineering, statistical analysis, and interactive visualization using **Power BI**.

Problem Statement

The IPL is a fast-paced T20 league, and understanding match trends can be complex. This project analyzes **ball-by-ball data (2008–2023)** to explore **batting, bowling, match results, and venue impact** using **Exploratory Data Analysis (EDA)** to uncover key insights.

Overview

The goal of this project is to transform raw IPL data into meaningful insights by following a complete data analytics workflow.

The analysis focuses on:

🏏 Batting performance and run-scoring trends
🎯 Bowling performance and efficiency
🏆 Team and match performance
🟠 Orange Cap winners across seasons
🏟️ Venue impact on match outcomes
📈 Season-wise IPL trends
📊 Player-level performance
🔍 Identifying patterns and relationships within the data

The final insights are presented through an **interactive Power BI dashboard**.

Dataset

The project uses "IPL ball-by-ball data from 2008 to 2023".

The dataset contains information related to:

* Match and season
* Teams
* Players
* Batsmen and bowlers
* Runs scored
* Balls bowled
* Wickets
* Boundaries
* Match results
* Venues
* Toss information
* Extras and other match-level details

The raw dataset was cleaned and transformed before performing analysis.

Tools & Technologies

| Tool                 | Purpose                         |
| -------------------- | ------------------------------- |
| **Python**           | Data analysis and preprocessing |
| **Pandas**           | Data manipulation and cleaning  |
| **NumPy**            | Numerical operations            |
| **Matplotlib**       | Data visualization              |
| **Seaborn**          | Statistical visualization       |
| **Jupyter Notebook** | Analysis and experimentation    |
| **Power BI**         | Interactive dashboard           |
| **DAX**              | Measures and calculated metrics |

Project Steps

1. Data Loading

The IPL dataset was loaded into Python using **Pandas** for further analysis.

2. Data Cleaning

The dataset was examined and cleaned to improve data quality.

Key activities included:

* Handling missing values
* Removing duplicate records
* Checking inconsistent values
* Correcting data types
* Standardizing columns
* Validating the dataset

3. Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset and identify meaningful patterns.

Analysis included:

* Descriptive statistics
* Univariate analysis
* Bivariate analysis
* Trend analysis
* Correlation analysis
* Team performance analysis
* Player performance analysis
* Batting and bowling analysis

4. Feature Engineering

Additional features and metrics were created to make the analysis more meaningful.

Examples include:

* Total Runs
* Total Wickets
* Total Balls Bowled
* Economy Rate
* Strike Rate
* Dot Ball %
* Win Percentage
* Total Sixes
* Orange Cap Runs
* Season-wise performance metrics

5. Data Visualization

Python libraries such as **Matplotlib** and **Seaborn** were used to visualize trends and relationships in the data.

6. Power BI Dashboard

The cleaned and transformed data was used to create an interactive **Power BI dashboard** with KPIs, charts, tables, and filters.

Dashboard

The Power BI dashboard is divided into multiple analytical sections:

🏏 IPL Overview

Provides a high-level summary of IPL performance, including:

* Total Matches
* Total Runs
* Total Wickets
* Total Sixes
* Total Dot Balls
* Season-wise run trends
* Top run scorers
* Top wicket takers
* Team-wise run analysis

Team & Match Analysis

Analyzes:

* Matches played by teams
* Matches won
* Win percentage
* Team performance comparison
* Team-wise trends

Batting Analysis

Analyzes:

* Top run scorers
* Strike rates
* Total sixes
* Balls faced
* Orange Cap winners
* Orange Cap runs by season

Bowling Analysis

Analyzes:

* Top wicket takers
* Economy rate
* Total balls bowled
* Dot ball percentage
* Bowling strike rate
* Bowler performance

Interactive filters such as **Year** and **Team/Bowler** allow users to explore the data dynamically.

Results & Insights

The analysis helps identify important IPL trends, including:

* Changes in run-scoring patterns across seasons
* Consistent high-performing batsmen and bowlers
* Season-wise Orange Cap winners
* Differences in team performance
* Bowling efficiency and economy trends
* Impact of venues on match outcomes
* Relationship between batting and bowling metrics
* Team-wise and player-wise performance patterns

The Power BI dashboard makes these insights easier to explore through interactive visualizations and filters.

How to Run

1. Clone the Repository

```bash
git clone https://github.com/your-username/ipl-trend-analysis.git
```

### 2. Navigate to the Project Folder

```bash
cd ipl-trend-analysis
```

### 3. Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open the analysis notebook and run the cells sequentially.

### 5. Open the Power BI Dashboard

Open the `.pbix` file using **Microsoft Power BI Desktop** to explore the interactive dashboard.

---

## 📁 Project Structure

```text
IPL-Trend-Analysis/
│
├── dataset/
│   └── IPL_Ball_by_Ball_Data.csv
│
├── notebooks/
│   └── IPL_Trend_Analysis.ipynb
│
├── powerbi/
│   └── IPL_Performance_Dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Statistical Analysis
* Data Visualization
* Pandas & NumPy
* Matplotlib & Seaborn
* Power BI Dashboard Development
* DAX
* Data Storytelling
* Business Insight Generation

Project Objective

This project demonstrates an **end-to-end data analytics workflow**, from working with raw ball-by-ball data to creating an interactive dashboard that communicates meaningful insights.

**Raw Data → Data Cleaning → EDA → Feature Engineering → Analysis → Visualization → Power BI Dashboard → Insights**
