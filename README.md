# 🎬 Netflix Data Analysis Project (EDA + Visualization)

## Project Overview

Netflix, being one of the biggest streaming platforms globally, provides a rich dataset of movies and TV shows. This project involves **exploratory data analysis (EDA)** on Netflix’s catalog to uncover hidden patterns, trends, and actionable insights using Python and visualization libraries.

---

## Dataset Description

-  **Source**: Kaggle Netflix Dataset  
-  **Format**: CSV  
-  **Total Entries**: ~7,800  

---

## Objectives

- Understand the content distribution on Netflix.
- Analyze trends over the years.
- Clean missing values and handle duplicates.
- Identify popular content types and audience segments.

---

## Data Cleaning

- Converted `date_added` to datetime format.
- Handled missing values in columns like `director`, `cast`, `country`.
- Removed duplicates and unnecessary whitespace.
- Created new columns such as `year_added`, `month_added`.

---

## Exploratory Data Analysis (EDA)

###  Questions Explored:
- What is the most frequent genre in the dataset?
- What genres has highest votes?
- What movie got the highest popularity? what's its genre?
- What movie got the lowest popularity? what's its genre?
- Which year has the most filmmed movies?

---

## Key Insights

- Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres.
- we have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the highest popularity among fans by being having more than 18.5% of movies popularities.
- Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action , Adventure and Sience Fiction .
- The united states, thread' has the highest lowest rate in our dataset and it has genres of music , drama , 'war', 'sci-fi' and history`.
- year 2020 has the highest filmming rate in our dataset.

---

## Tools and Technologies Used

| Tool/Library | Use |
|--------------|-----|
| Python | Programming language |
| Pandas | Data loading & preprocessing |
| Matplotlib & Seaborn | Visualizations |
| Plotly | Interactive plots |
| WordCloud | Genre and actor tag clouds |
| Jupyter Notebook | Development environment |

---

## How to Run

```bash
1. Clone this repository
2. Install dependencies (pandas, matplotlib, seaborn, etc.)
3. Launch Jupyter Notebook and open `netflix_analysis.ipynb`
4. Run all cells to explore data, graphs, and insights


