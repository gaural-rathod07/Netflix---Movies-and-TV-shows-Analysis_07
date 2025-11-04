# 🎬 Netflix Movies and TV Shows Analysis

A Jupyter Notebook analyzing the Netflix dataset to discover **trends in content distribution, genres, and release years** using **Python, Pandas, Seaborn, Matplotlib, and SQL**.

---

## 📘 Project Overview
This project explores the Netflix dataset to identify patterns in content type, genre preferences, and yearly growth trends.  
It demonstrates data cleaning, exploratory data analysis (EDA), and SQL integration within a Jupyter environment.

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, Matplotlib, Seaborn, SQLite  
- **Tools:** Jupyter Notebook, SQLAlchemy  

---

## 📂 Dataset Overview
- **Source:** [Kaggle — Netflix Movies & TV Shows Dataset](https://www.kaggle.com/shivamb/netflix-shows)  
- **Rows:** ~8,800  
- **Columns:** 12  
- **Fields include:** `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

> **Note:** Dataset used for educational purposes. Original dataset author credited above.

---

## 🧹 Data Cleaning
Key cleaning steps performed:
- Removed duplicates and trimmed whitespace from text fields.
- Converted `date_added` to `datetime`.
- Extracted `primary_genre` from `listed_in` (first genre).
- Parsed `duration` into `duration_num` and `duration_kind`.
- Handled missing values.

---

## 📊 Analysis & Visuals
The notebook contains the following sections and visualizations:
- **Type distribution:** Movies vs. TV Shows  
- **Content growth by year:** Titles added per year  
- **Top 10 genres:** Primary genre counts  
- **Country distribution:** Top countries by title count  
- **Duration analysis:** Movie length distribution and TV seasons  

Sample visuals (see `/Images` folder):  
- `top_genres.png`  
- `content_by_year.png`
- `movie_duration.png`

---

## 🛢 SQL Integration
- Data loaded into a local SQLite database (`netflix.db`) using SQLAlchemy.  
- Example SQL queries included:
  - Type distribution: Movies vs. TV Shows  
  - Top countries by content
  - Top 10 genres: Primary genre counts  
  - Titles added per year  
  - Movies longer than 120 minutes  

---

## ✅ Key Insights
- Netflix added significantly more content after **2015**, showing rapid global expansion.  
- The platform is dominated by **Movies**, with **Drama** and **Comedy** as top genres.  
- The **United States** contributes the largest share of titles.  
- Most movies are between **90–120 minutes**, while most TV shows have **1–3 seasons**.  

---

## 📁 Repository Structure

```
Netflix---Movies-and-TV-shows-Analysis_07/
│
├── Netflix-analysis.ipynb # Main Jupyter notebook (cleaning, EDA, SQL)
├── Images/ # Exported preview images (graphs, charts)
├── .gitignore
└── README.md
```

---

## 🏁 Project Goal
To analyze the Netflix dataset and uncover insights into how Netflix’s content library has evolved over time by type, genre, and geography.

---

🧑‍💻 Author

Analysis & Visualizations by: Gaural Rathod
📚 B.E. in Information Technology
💡 Aspiring Data Analyst | Python | Power BI | SQL

📌 *This project is intended for educational and portfolio purposes.*
