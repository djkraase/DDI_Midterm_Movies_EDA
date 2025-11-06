# 🎬 Movie Success and ROI Analysis

Explore the factors that drive movie success and ROI, focusing on **financial performance**, **genre**, and **seasonal trends**. This project provides actionable insights for studios, investors, and analysts to optimize movie production and release strategies.

---

## 📌 Research Question / Objective

**Primary Question:**  
> _What factors drive movie success and return on investment (ROI), considering financial performance, genre, and seasonal trends?_

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
_Which genres are most popular to produce, most profitable, and generate the highest revenue?_
- 🎭 **Comedy**: Highest ROI & most movies produced  
- 💥 **Action / Adventure / Animation**: Top in revenue 
- 😱 **Horror**: Moderate in both revenue & ROI  
- 🎬 **Documentary / Drama**: High ROI but few movies produced and vice-versa

<img width="1176" height="784" alt="3 0 Genre Landscape_Count, Relative ROI, Revenue" src="https://github.com/user-attachments/assets/b303babc-b4b1-4e26-bdcb-b4c20f71a454" />

---

### 2️⃣ Movie Genres by Count Across Seasons

_Which genres are released in each season, and does the genre mix vary across the year?_
- Comedy, Action, and Drama dominate releases  
- Fall sees more variety (Thriller, Crime ~5%)  
- Drama peaks in fall/winter (awards season alignment)

<img width="1182" height="784" alt="4 7 Movie Genres Distributed by Seasons" src="https://github.com/user-attachments/assets/76c16744-cb3c-4d57-b1a5-119df1621f4a" />

---

### 3️⃣ Movie Revenue Distribution by Genre and Season
  
_How do different movie genres contribute to seasonal variations in box office revenue?_
- Blockbuster genres: Action, Adventure, Animation  
- **Summer:** Revenue peaks due to holidays (>50% summer revenue)  
- **Winter:** Small surge with family-friendly and franchise releases  
- **Spring & Fall:** Lower revenue, niche titles dominate

<img width="1174" height="784" alt="4 8 Movie Revenue Distribution by Genre and Season" src="https://github.com/user-attachments/assets/a3e003b8-9b5c-4647-86cf-ceadcd8f4928" />

---

### 4️⃣ Movie Profit Distribution by Genre and Season
_How does movie profitability vary by genre and season, and what strategies maximize returns?_
- Big hits earn most in summer  
- Low-budget films often deliver higher ROI relative to cost  
- **Optimal Strategy:** Balance blockbuster hits with smaller, high-ROI movies  
- **Spring:** Ideal for family films and high-ROI smaller releases

<img width="1160" height="784" alt="4 9 Movie Profit Distribution by Genre and Season" src="https://github.com/user-attachments/assets/8668b3e7-b6a3-487e-a32a-6ad0c64fb14c" />

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
