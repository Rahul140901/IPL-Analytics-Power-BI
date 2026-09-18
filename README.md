# 🏏 IPL Analytics Dashboard (2008–2025)

An interactive **Power BI dashboard** developed to analyze Indian Premier League (IPL) data from **2008 to 2025**, covering team performance, player statistics, season-wise achievements, and tournament results.

---

## 📊 Dashboard Preview

![IPL Analytics Dashboard](Images/IPL%20Analysis%20Dashboard.png)

---

## 📌 Project Overview

This project transforms IPL match-level and ball-by-ball data into an interactive **Power BI dashboard**.

The dashboard provides season-wise analysis of IPL teams and players, allowing users to explore tournament results, batting and bowling performances, boundary statistics, and points-table standings.

All major KPIs and player statistics dynamically update based on the selected IPL season.

---

## ✨ Dashboard Features

- 🏆 Champion and Runner-Up
- 🟠 Orange Cap – Highest Run Scorer
- 🟣 Purple Cap – Highest Wicket Taker
- 6️⃣ Most Sixes
- 4️⃣ Most Fours
- 🎯 Total Dot Balls
- 💯 Centuries
- 🏏 Half-Centuries
- 📅 Matches Played
- 👥 Total Teams
- 📋 Season-wise Points Table
- 🔍 Interactive Season Filter (2008–2025)
- 🖼️ Dynamic Player and Team Images

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Dynamic measures and KPI calculations
- **Data Modeling** – Relationships between multiple IPL datasets
- **CSV** – Source data storage

---

## 📂 Dataset

The project uses multiple datasets containing match-level, ball-by-ball, player, and team information.

### Main Datasets

- `Ball_by_ball_data.csv` – Delivery-level IPL match data
- `IPL_Matches_data.csv` – Match-level IPL information
- `Player_data_Updated.csv` – Player details and related information
- `Teams_data.csv` – IPL team information

The `Data/Images/` folder contains supporting image assets used in the Power BI dashboard.

---

## 📊 Key Analysis

### 🏆 Team Analysis

- Season Champion
- Season Runner-Up
- Matches Played
- Wins and Losses
- Points Table
- Team standings by season

### 🏏 Batting Analysis

- Orange Cap winner
- Highest run scorer
- Most Sixes
- Most Fours
- Centuries
- Half-Centuries

### 🎯 Bowling Analysis

- Purple Cap winner
- Highest wicket taker
- Dot-ball analysis
- Season-wise bowling performance

---

## ⚙️ Data Preparation

The raw datasets were cleaned and transformed using **Power Query** before being loaded into the Power BI data model.

Key data preparation steps included:

- Handling missing values
- Correcting data types
- Standardizing season values
- Cleaning team and player information
- Preparing match-stage information
- Creating relationships between match, player, team, and ball-by-ball datasets

---

## 🧮 DAX & Data Modeling

Custom **DAX measures** were created to dynamically calculate important IPL statistics, including:

- Champion
- Runner-Up
- Orange Cap Player
- Purple Cap Player
- Most Sixes
- Most Fours
- Matches Played
- Wins
- Losses
- Points
- Centuries
- Half-Centuries
- Dot Balls

These measures dynamically respond to the selected IPL season.

---

## 📁 Repository Structure

```text
IPL-Analytics-Power-BI/
│
├── Data/
│   ├── Ball_by_ball_data.csv
│   ├── IPL_Matches_data.csv
│   ├── Player_data_Updated.csv
│   ├── Teams_data.csv
│   └── Images/
│       └── Dashboard supporting images
│
├── Images/
│   └── IPL Analysis Dashboard.png
│
├── IPL Analysis Dashboard.pbix
│
└── README.md
```

---

## 💡 Skills Demonstrated

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- KPI Development
- Dashboard Design
- Data Visualization
- Sports Data Analytics

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `IPL Analysis Dashboard.pbix` using **Power BI Desktop**.
3. Use the season slicer to select an IPL season from **2008 to 2025**.
4. Explore the dynamically updated team and player statistics.

---

## 👤 Author

### Rahul Shewale

**Aspiring Data Analyst**

**Skills:** Power BI | SQL | Excel | Tableau | Data Analytics

- GitHub: [Rahul140901](https://github.com/Rahul140901)
- LinkedIn: [Rahul Shewale](https://www.linkedin.com/in/rahul-shewale-190039315/)

---

⭐ If you found this project useful, feel free to star the repository.
