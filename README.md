# 🎬 Movie Success and ROI Analysis

Explore the factors that drive movie success and ROI, focusing on **financial performance**, **genre**, and **seasonal trends**. This project provides actionable insights for studios, investors, and analysts to optimize movie production and release strategies.

---

## 📌 Research Question / Objective

**Primary Question:**  
> What factors drive movie success and return on investment (ROI), considering financial performance, genre, and seasonal trends?

**Objective:**  
- Identify which genres perform best in specific seasons.  
- Provide actionable insights to maximize ROI.  
- Guide production and release scheduling using data-driven strategies.

---

## 🗂 Data and Methodology

**Data Source:**  
- TMDB dataset from Kaggle (~700,000 movies)  
- Features: budget, revenue, release dates, genres, etc.  
- Limitations: missing budgets, zero values, incomplete financial data for non-English films

**Data Cleaning & Preparation:**  
1. Removed incomplete/irrelevant entries  
2. Focused on key financial and categorical fields  
3. Calculated **profit** and **ROI**  
4. Extracted primary genres  
5. Added **release year** and **month** for seasonal trend analysis  

**Outcome:**  
Clean, reliable dataset ready for analyzing financial performance, genre impact, and seasonal trends.

---

## 📊 Key Visualizations & Insights

### 1️⃣ Movie Genres by Count Across Seasons
- Comedy, Action, and Drama dominate releases  
- Fall sees more variety (Thriller, Crime ~5%)  
- Drama peaks in fall/winter (awards season alignment)

![Genres by Season](images/genres_by_season.png)

---

### 2️⃣ Movie Revenue Distribution by Genre and Season
- Blockbuster genres: Action, Adventure, Animation  
- **Summer:** Revenue peaks due to holidays (>50% summer revenue)  
- **Winter:** Small surge with family-friendly and franchise releases  
- **Spring & Fall:** Lower revenue, niche titles dominate

![Revenue by Genre and Season](images/revenue_by_genre_season.png)

---

### 3️⃣ Movie Profit Distribution by Genre and Season
- Big hits earn most in summer  
- Low-budget films often deliver higher ROI relative to cost  
- **Optimal Strategy:** Balance blockbuster hits with smaller, high-ROI movies  
- **Spring:** Ideal for family films and high-ROI smaller releases

![Profit by Genre and Season](images/profit_by_genre_season.png)

---

## 💡 Key Insights

| Genre             | Recommended Season | Strategy                          |
|------------------|-----------------|----------------------------------|
| Comedy            | Year-round      | Reliable returns                  |
| Action/Adventure  | Summer          | Target blockbuster releases       |
| Animation/Family  | Winter holidays | Holiday family audience           |
| Smaller Films     | Spring/Fall     | Maximize ROI with low-budget hits |

**Summary:**  
- Align genre with season to maximize ROI  
- Balance big-budget hits with smaller high-return films  
- Data-driven scheduling reduces risk and boosts profitability

---

## 🔮 Future Research Directions
- Impact of marketing and streaming on revenue  
- Influence of audience and cultural trends  
- Role of franchises and sequels  
- Contribution of international and non-English films

---

## ✅ Conclusion
Data-driven insights allow studios to strategically plan production and release schedules, balancing big-budget blockbusters with smaller, high-ROI films. This approach minimizes risk, maximizes profitability, and delivers movies that align with seasonal audience demand.
