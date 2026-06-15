# 📊 Data Visualization — Netflix Movies & TV Shows

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat-square&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-blue?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-teal?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-5.0-3F4F75?style=flat-square&logo=plotly)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📌 Project Overview

The goal was to transform raw data from the **Netflix Movies and TV Shows** dataset into meaningful visual formats — revealing insights about content trends, genre distribution, country-wise production, and ratings using Python's core visualization libraries.

---

## 🎯 Objectives

- Transform raw data into visual formats (charts, graphs, heatmaps)
- Use Matplotlib, Seaborn, and Plotly for diverse visualizations
- Design visuals that enhance understanding and reveal clear insights
- Craft a compelling data story to support decision-making
- Build a portfolio-ready, well-documented notebook

---

## 📁 Repository Structure

```
CodeAlpha_DataVisualization/
│
├── README.md                          ← You are here
├── netflix_visualization.ipynb        ← Main Jupyter Notebook
├── requirements.txt                   ← Python dependencies
│
├── charts/                            ← Exported chart images
│   ├── type_distribution.png
│   ├── content_growth.png
│   ├── top_countries.png
│   ├── genre_rating_heatmap.png
│   ├── movie_scatter.html             ← Interactive Plotly chart
│   └── wordcloud.png
│
└── data/
    └── netflix_titles.csv             ← Dataset (see source below)
```

---

## 📂 Dataset

**Netflix Movies and TV Shows**
- **Source:** [Kaggle — Shivam Bansal](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size:** 8,807 titles × 12 columns
- **Features:** title, type, director, cast, country, date_added, release_year, rating, duration, listed_in, description

---

## 📊 Visualizations Included

| # | Chart Type | Insight |
|---|---|---|
| 1 | Bar Chart | Movies vs TV Shows distribution |
| 2 | Line Chart | Content additions per year (2008–2021) |
| 3 | Horizontal Bar | Top 10 countries producing Netflix content |
| 4 | Heatmap | Genre vs Content Rating matrix |
| 5 | Scatter Plot (Interactive) | Movie duration vs Release year by rating |
| 6 | Word Cloud | Most common words in Netflix titles |
| 7 | Count Plot | Top genres on Netflix |
| 8 | Box Plot | Distribution of movie durations |

---

## 🔍 Key Insights

- **70%** of Netflix content is Movies; 30% is TV Shows
- Netflix saw peak content additions in **2019**, followed by a sharp drop in 2020 due to COVID-19 production halts
- The **United States** dominates content production, followed by **India** and the **United Kingdom**
- **TV-MA** (Mature Audiences) is the most common rating, suggesting Netflix targets adult viewers
- **Dramas and Comedies** are by far the most produced genres globally
- Average movie duration on Netflix is approximately **100 minutes**

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, manipulation |
| `matplotlib` | Base plotting and chart customization |
| `seaborn` | Statistical visualizations and heatmaps |
| `plotly` | Interactive scatter plots |
| `wordcloud` | Text-based word cloud visualization |
| `numpy` | Numerical operations |

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/omjoshi28/DataVisualization_Netflix-TV-Shows
cd DataVisualization_Netflix-TV-Shows
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download the dataset
Download `netflix_titles.csv` from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and place it in the `data/` folder.

### 4. Run the notebook
```bash
jupyter notebook netflix_visualization.ipynb
```

---

## 📋 Requirements

```
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
plotly>=5.11.0
wordcloud>=1.9.0
jupyter>=1.0.0

---

---

## 👤 Build By-

**Om Joshi**
- 🔗 LinkedIn: [https://linkedin.com/in/om-joshi028/]
- 💻 GitHub: [https://github.com/omjoshi28/DataVisualization_Netflix-TV-Shows]
- 📧 Email: omjoshi2807@gmail.com

---

*If you found this project helpful, please ⭐ star the repository!*
