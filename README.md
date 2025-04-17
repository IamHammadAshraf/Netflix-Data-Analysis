
# 🍿 Netflix Data Analysis using Python

An exploratory data analysis (EDA) project on the **Netflix Movies and TV Shows dataset**, leveraging Python visualization libraries to extract insights on content trends, genres, countries, actors, and more.

---

## ✅ Features

- Clean and preprocess missing values
- Visualize distribution of **Movies vs TV Shows**
- Analyze **release trends** over time
- Discover **top content-producing countries**
- Explore **popular genres** using word clouds
- Understand **duration patterns** for movies and TV shows
- Track **content addition trends** by year and month
- Evaluate **rating distribution**
- Identify **top actors** featured on Netflix

---

## 📦 Dependencies

Install the required packages:

```bash
pip install pandas seaborn matplotlib plotly wordcloud
```

---

## 📊 Dataset

- Source: [Netflix Dataset on GitHub](https://github.com/krishnaik06/netflix-data-analysis/blob/main/netflix_titles.csv)
- Fields: `title`, `type`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🔍 Analysis Breakdown

### 1️⃣ Setup & Data Loading
- Load dataset directly from GitHub
- Install and import essential libraries

### 2️⃣ Data Cleaning
- Fill missing values in `country`, `cast`, and `director`
- Convert `date_added` to datetime
- Extract `year_added` for time-based analysis

### 3️⃣ Content Overview
- Compare count of Movies vs TV Shows

### 4️⃣ Release Trends
- Plot how content release evolved over the years

### 5️⃣ Country Analysis
- Identify top 10 countries producing Netflix content

### 6️⃣ Genre Analysis
- Generate a word cloud for genres in `listed_in`

### 7️⃣ Duration Analysis
- Movie length distribution
- TV show season count analysis

### 8️⃣ Addition Trends
- Content added per year and per month

### 9️⃣ Rating Analysis
- Distribution of content ratings (e.g., TV-MA, PG)

### 🔟 Cast Analysis
- Most frequent actors on Netflix (Top 20)

---

## 📈 Sample Visuals

<img src="https://i.imgur.com/9u8r1cZ.png" width="600" alt="Movies vs TV Shows">
<br>
<img src="https://i.imgur.com/DJbktAV.png" width="600" alt="Word Cloud for Genres">

---

## 🎯 Why This Project?

- Great for beginners to practice EDA and data visualization
- Real-world dataset with practical insights
- Covers various aspects: time-series, categorical, and text data

---

**Just run the notebook and start exploring the world of Netflix!**

```python
# Example: Get top 5 countries
df['country'].value_counts().head()
