# 🏀 Team Performance Prediction using Probabilistic Machine Learning

**Author:** Mikhail Karimov  
**Affiliation:** FIT CTU, Prague  
**Keywords:** Collaborative Filtering, Context Filtering, Ensemble Methods, Recommendation Systems, Probabilistic ML  

---

## 🌟 Overview
This project explores how **recommendation system techniques** can be reimagined beyond traditional user–item domains - applying them to **team performance prediction** in NBA games.  

The core idea is to investigate how **Collaborative Filtering (CF)** and **Context-aware Filtering (CxF)** can be used, and combined, to predict match outcomes.  
Additionally, multiple **ensembling strategies** are tested to evaluate whether hybrid approaches can outperform individual models and which one is better.

---

## ⚙️ Technologies
- 🐍 Python  
- 📊 Pandas, NumPy, Scikit-learn  
- 📈 Matplotlib / Seaborn for visualization  
- 🧠 Jupyter Notebook  

---

## 🧩 Methodology
1. **Data Preparation:**  
   Cleaning, normalization, and transformation of NBA game statistics into a user–item matrix structure.  
2. **Collaborative Filtering:**  
   Implementation of matrix factorization (SVD, NMF) and neighborhood-based models to predict team outcomes.  
3. **Context-aware Filtering:**  
   Incorporating contextual variables (e.g., opponent strength, home/away bias, recent form).  
4. **Hybrid / Ensemble Approaches:**  
   Testing weighted and stacking-based combinations of CF and CxF models.  
5. **Evaluation:**  
   Models compared using RMSE and correlation metrics; analysis of bias–variance trade-offs and interpretability.  

---

## 📊 Results
The study demonstrates that **contextual features significantly improve predictive accuracy** over baseline CF models.  
Ensemble methods further stabilize results and balance variance, showing potential for **robust, explainable predictive systems** in sports analytics.

---

## 📁 Project Structure
```
├── NBA_Game_Prediction.ipynb # Main notebook with full implementation
├── Mikhail_Karimov_NBA_Team_Performance_Prediction_using_PML.docx # Scientific report
├── Mikhail_Karimov_PML_poster.docx # Academic poster
└── README.md # You are here
```

---

## 📚 References
1. Geetha, G., Safa, M., Fancy, C., & Saranya, D. (2018). A Hybrid Approach using Collaborative filtering and Content based Filtering for Recommender System. Journal of Physics Conference Series, 1000, 012101. https://doi.org/10.1088/1742-6596/1000/1/012101
2. Widayanti, R. (2023). Improving Recommender Systems using Hybrid Techniques of Collaborative Filtering and Content-Based Filtering. Journal of Applied Data Sciences, 4(3), 289–302. https://doi.org/10.47738/jads.v4i3.115
3. Thorat, P.B., Goudar, R.M. and Barve, S., 2015. Survey on collaborative filtering, content-based filtering and hybrid recommendation system. International Journal of Computer Applications, 110(4), pp.31-36.

---

## All used datasets can be found through the links:
1. https://www.kaggle.com/datasets/nathanlauga/nba-games?select=players.csv
2. https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats?resource=download&select=Advanced.csv

## Have a nice day,
Mikhail Karimov
