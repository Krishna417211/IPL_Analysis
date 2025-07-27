# IPL_Analysis
# 🏏 IPL Match Analysis (Mini Dataset)

This project performs **Exploratory Data Analysis (EDA)** on a mini version of the **IPL Match Dataset**. We explore historical match trends, key statistics, and generate visual insights using **Pandas**, **NumPy**, and **Matplotlib/Seaborn**.

---

## 📁 Dataset

The dataset contains 21 IPL matches with the following details:

- Match ID, season, city, date
- Teams (team1, team2), toss winner & decision
- Match winner, result margin, target runs
- Player of the Match, match type, venue
- Umpires and match method information

---

## 🔍 Objectives

We explored the following questions:

1. **Which team has won the most matches?**
2. **Who has won the most ‘Player of the Match’ awards?**
3. **Distribution of toss decisions (bat/field)?**
4. **Which city hosted the most matches?**
5. **Which seasons saw the most matches?**
6. **Is there a correlation between winning the toss and winning the match?**
7. **What are the highest and lowest result margins?**
8. **Target score distribution and trend over the years?**
9. **Number of matches decided by Super Over?**
10. **Which umpire officiated the most matches?**

---

## 🧹 Data Cleaning

- Parsed date columns correctly
- Handled column name formatting
- Checked for nulls and data consistency

---

## 📊 Key Findings

- Some teams consistently dominate matches
- Majority of toss winners choose to **field first**
- Certain seasons/cities hosted more matches
- There is **partial correlation** between toss winner and match winner
- Target scores vary widely from **43 to 203 runs**
- Some matches were decided by **Super Over**
- Umpire participation varies greatly

---

## 📈 Visualizations

- Bar plots for most wins, player awards
- Countplots for toss decisions
- Line plots for target scores over time
- Correlation heatmap between toss and match results

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## 📌 Conclusion

This project helped us derive important insights from a small IPL dataset. With visualizations and statistics, we’ve highlighted patterns in team performance, player awards, match outcomes, and decision strategies.

---


## ⭐️ If you found this useful, please star this repository!

