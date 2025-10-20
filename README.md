# First-Pitch-Analysis
A statistical analysis of first-pitch outcomes and pitch-type effectiveness in baseball.

# Statistical Analysis of First-Pitch Outcomes in Baseball ⚾

### Author: Benjamin Trivers  
**Tools Used:** R, ggplot2, dplyr  
**Date:** 2025  

---

## 📖 Overview
This project investigates whether the first pitch of an MLB at-bat is statistically more likely to be a strike or a ball, and which pitch types are most effective at generating first-pitch strikes.

The analysis challenges traditional baseball strategy that encourages hitters to "take the first pitch" by providing data-driven evidence to reevaluate this approach.

---

## 📊 Data Description
- **Observations:** ~200 first-pitch samples  
- **Variables:**  
  - `Result` — Pitch outcome (`K` = strike, `B` = ball)  
  - `Pitch` — Pitch type (e.g., 4-Seam Fastball, Sinker, Curveball, Slider)  

Data were manually collected from ESPN’s play-by-play logs of Baltimore Orioles games.

---

## 🧮 Statistical Methods
- One-sided binomial test to evaluate strike vs. ball proportions  
- Grouped pitch-type strike rate analysis (`K_rate`)  
- Visualizations created using `ggplot2`

---

## 📈 Key Findings
- First pitches are **significantly more likely** to be strikes than balls (p < 0.05).  
- **Fastballs** and **sinkers** show the highest first-pitch strike percentages.  
- Results suggest hitters may benefit from increased first-pitch aggressiveness.  

---

## 💻 Files Included
- `first_pitch_analysis.R` — R code used for analysis and visualization  
- `first_pitch_analysis_report.pdf` — Full written report  
- `data/` *(optional)* — Raw data (if included later)

---

## 🧠 Future Work
- Expand dataset across all MLB teams  
- Incorporate pitch location and swing/contact data from Statcast  
- Model run expectancy changes from first-pitch outcomes  

---

## 📬 Contact
**Benjamin Trivers**  
📧 btrivs@gmail.com  
🎓 B.S. Applied Statistics, University of Maryland, Baltimore County  
