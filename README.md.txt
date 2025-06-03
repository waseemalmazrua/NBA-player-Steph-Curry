# 🏀 Steph Curry Shot Probability Analysis

This project analyzes real NBA shooting data for Steph Curry to calculate and interpret a variety of probability metrics using Python. It was completed as part of the **Statistics for Data Analysis Nanodegree** from Udacity.

---

## Objective

To apply statistical concepts such as:
- Marginal Probability
- Conditional Probability (Future & Retrospective)
- Joint Probability
- Data Visualization

---

##  Dataset Summary

- **Total Shots:** 1434  
- **Made Shots:** 703  
- **Missed Shots:** 731  
- **3PT Attempts:** 786  
- **3PT Made:** 329  
- **Overall Accuracy:** 49.02%

---

##  Key Probabilities

### Basic Probabilities
- `P(Made)` = 0.49  
- `P(Missed)` = 0.51  
- `P(3PT)` = 0.55  
- `P(Made ∩ 3PT)` = 0.23  
- `P(Made | 3PT)` = 0.42

### Conditional – Future
- `P(Made | 4th Qtr)` = 0.49  
- `P(Made | Losing)` = 0.43  
- `P(Made | Last 2 min of Q4)` = 0.41

### Conditional – Retrospective
- `P(3PT | Made)` = 0.47  
- `P(4th Qtr | Made)` = 0.26

---

##  Visualizations

Each section includes visual aids:
- Bar chart for overall shooting stats  
- Pie chart of outcome probabilities  
- Conditional probabilities shown in grouped bar plots  

---

##  Tools Used

- Python  
- pandas  
- matplotlib  
- seaborn  
- Jupyter Notebook  
- Google Slides

---

## Conclusion

This project demonstrates how probability concepts can be applied to real-world sports data. Steph Curry shows a high volume of 3-point shots, but his accuracy slightly drops in high-pressure moments such as the last 2 minutes of the game.

---

