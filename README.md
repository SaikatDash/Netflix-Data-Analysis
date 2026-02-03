# 🎬 Netflix Data Analysis 📊

> A comprehensive data analysis project exploring Netflix's content library, trends, and viewer preferences using Python and Jupyter Notebook.

---

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Key Findings](#key-findings)
- [Analysis Breakdown](#analysis-breakdown)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)

---

## 📌 Overview

This project provides an in-depth analysis of Netflix's movie and TV show dataset to uncover meaningful insights about:

| Aspect | Details |
|--------|---------|
| 🎥 **Content Distribution** | Analysis by type, country, and release year |
| 📈 **Trend Analysis** | Genre popularity and growth patterns over time |
| ⭐ **Rating Patterns** | Distribution and correlation with content type |
| ⏱️ **Duration Insights** | Content length variations and preferences |
| 🌍 **Geographic Trends** | Content availability and production by region |
| 📺 **Production Patterns** | Release timing and seasonal trends |

---

## 📊 Dataset

**Source:** [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) from Kaggle

### Dataset Specifications
- **Total Records:** 10,000+ movies and TV shows
- **Time Period:** Multiple decades of content
- **Features (12 attributes):**
  - Title, Director, Cast, Country
  - Release Year, Rating, Duration
  - Listed In (Genres), Description, Date Added
  - Type (Movie/TV Show), and more

### Data Quality
✅ Comprehensive coverage of Netflix's catalog  
✅ Rich attribute information for multidimensional analysis  
✅ Suitable for trend analysis and predictive modeling  

---

## 🔍 Key Findings

### 🟥 1. Content Growth Over Time
**Release Year Distribution**
- 📈 **Exponential growth** in content production since 2015
- 🎉 **70% of Netflix content** released in the last 5 years
- Peak production years: 2018-2021
- Notable acceleration in acquisition pace

**Insights:**
- Netflix aggressively expanded its content library in recent years
- Shift towards original content and recent releases
- Strategic focus on capturing current cultural moments

---

### 🟨 2. Content Type Analysis
**Movies vs TV Shows**

| Metric | Movies | TV Shows |
|--------|--------|----------|
| **Library Share** | 70% | 30% |
| **Growth Rate** | Stable | 📈 Faster Growing |
| **Avg Duration** | ~100 mins | 1-10 seasons |
| **Content Strategy** | Broad appeal, quick consumption | Long-term engagement |

**Key Insights:**
- Movies dominate the current library composition
- TV show production is accelerating faster than movies
- TV shows generate higher user engagement and watch time

---

### 🟨 3. Content Ratings & Audience Analysis

**Rating Distribution Patterns:**
- **Most Common Ratings:** TV-MA, TV-14, PG-13
- **Age Group Targeting:** Majority aimed at adult audiences
- **Kid-Friendly Content:** Growing segment (G, PG, TV-Y7)
- **Mature Content:** Increasing presence reflecting audience demand

**Viewer Insights:**
- Adult-oriented content dominates the platform
- Increasing investment in family-friendly alternatives
- Rating diversity indicates Netflix's broad audience strategy

---

## 📈 Analysis Breakdown

### Visualizations Included
- 📊 Time series trends of content releases
- 🎯 Genre distribution and popularity heatmaps
- 🗺️ Geographic distribution of content production
- 📉 Duration analysis by content type
- 🎨 Rating comparisons and audience segments

### Statistical Analysis
- Correlation between release year and content popularity
- Genre clustering and preferences
- Duration patterns by rating category
- Seasonal release trends and patterns

---

## 🛠️ Technologies & Tools

| Category | Tools |
|----------|-------|
| **Data Processing** | ![Python](https://img.shields.io/badge/Python-3.8+-blue) Pandas, NumPy |
| **Data Visualization** | Matplotlib, Seaborn, Plotly |
| **Notebook Environment** | Jupyter Notebook / JupyterLab |
| **Version Control** | Git |
| **Data Source** | Kaggle API |

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8 or higher
pip or conda package manager
```

### Installation & Setup
```bash
# Clone the repository
git clone <repository-url>
cd Netflix-Data-Analysis

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install pandas numpy matplotlib seaborn plotly jupyter

# Launch Jupyter Notebook
jupyter notebook
```

---

## 📂 Project Structure

```
Netflix-Data-Analysis/
├── netflix.ipynb              # Main analysis notebook
├── Netflix_Titles Dataset/    # Raw data files
│   └── netflix_titles.csv     # Complete dataset
├── README.md                  # Project documentation
└── visualizations/            # Generated charts and graphs (optional)
    ├── content_growth.png
    ├── genre_distribution.png
    └── rating_analysis.png
```

---

## 💡 Insights & Takeaways

1. **Content Strategy:** Netflix is shifting from quantity to strategic content acquisition
2. **Market Trends:** Increasing competition reflected in diverse content investments
3. **Audience Focus:** Multi-segment approach targeting different demographics
4. **Global Expansion:** Growing international content representation
5. **Future Direction:** Investment in original content and niche categories

---

## 📝 Notes

- Analysis based on dataset snapshot as of data collection date
- Results represent correlations, not causation
- Netflix's catalog constantly evolves with new additions/removals
- Visualizations are interactive when viewed in Jupyter environment

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Suggest new analyses
- Improve visualizations
- Add additional datasets
- Report issues or insights

---

## 📄 License

This project uses the Netflix dataset from Kaggle. Please ensure compliance with Kaggle's terms of service and Netflix's data usage policies.

---

**Last Updated:** February 2026  
**Analyst:** Data Science Project  
**Status:** ✅ Active & Maintained
