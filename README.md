
# 📊 Netflix Content Analysis Dashboard

This project analyzes the Netflix content dataset and provides insights using Tableau visualizations and Python preprocessing.

## 📁 Project Structure

```
netflix_dashboard_project/
│
├── README.md                       ← This file
├── netflix_cleaned.csv            ← Cleaned dataset used for Tableau and analysis
├── raw_data/
│   └── netflix1.csv               ← Original unprocessed dataset
├── notebooks/
│   └── clean.ipynb                ← Jupyter notebook with cleaning steps
├── plots/
│   └── netflix_dashboard.png      ← Screenshot of the final Tableau dashboard
```

## 🔧 Tools Used

- **Python**: Data Cleaning
- **Pandas, NumPy**
- **Tableau Public**: Data Visualization

## 📈 Dashboard Highlights

- Most common genre: **Dramas**
- Avg. movie duration: **87 minutes**
- Peak content year: **2018**
- Top country: **United States**
- Content release trends and rating distribution

## 📌 How to Use

1. View the Jupyter Notebook in `/notebooks/clean.ipynb` for data cleaning.
2. Load `netflix_cleaned.csv` in Tableau or Excel to explore.
3. See the dashboard screenshot in `/plots/netflix_dashboard.png`.

## 🗃️ Data Source

Public Netflix dataset (from Kaggle or similar).

---
## 📊 Visualizations

Below is the Tableau dashboard created from the cleaned Netflix dataset. It reveals key trends in content production, genre distribution, and viewer accessibility.

### 🖼️ Netflix Content Dashboard

<img src="plots/netflix_dashboard.png" alt="Netflix Dashboard" width="700"/>

This dashboard provides the following insights:

- 📅 **Content Added Over Time**: A bar chart or timeline showing the number of shows/movies added each year, peaking around 2018.
- 🎭 **Genre Distribution**: A pie or bar chart showing the most common genres. Dramas, Comedies, and Documentaries are most frequent.
- 🌍 **Top Producing Countries**: Identifies which countries contribute most content to Netflix, with the United States leading.
- 🕒 **Content Duration**: A histogram showing distribution of movie durations (most fall under 100 minutes).
- 📈 **Type Breakdown**: A split of content by type (Movies vs TV Shows) to understand platform focus.

> This visualization helps content analysts, marketers, and developers understand Netflix’s global content strategies and genre focus.

---
