# Economic-Efficiency-of-Investments-in-Rhythmic-Gymnastics
Term paper (co-authored with Sofia Sukhorukova), HSE University, 2025

# Economic Efficiency of Investments in Rhythmic Gymnastics

Term paper (co-authored with Sofia Sukhorukova), HSE University, 2025

## Overview

This project studies whether parental financial investment in children's rhythmic 
gymnastics training (St. Petersburg and Leningrad Region) translates into higher 
satisfaction with that investment, and what factors actually drive perceived return 
on investment (ROI).

## Data

- Original survey data collected by the authors via gymnastics clubs, parent 
  networks, and social media groups
- Sample: 41 fully completed responses from parents of gymnasts (ages 4–18+)
- Variables: expenditure (monthly/annual), income level, motivational factors 
  (importance of health, discipline, career, university admission, status), 
  training background (age, experience, level, place of training), and 
  self-reported satisfaction (1–10 scale)

## Method

- Descriptive statistics and visualizations (distributions, boxplots, coefficient 
  of variation across spending categories)
- Pearson correlation analysis with VIF-based multicollinearity screening
- Two OLS regression models: (1) determinants of satisfaction, (2) determinants 
  of total annual expenditure, both with stepwise variable selection
- One-way ANOVA comparing satisfaction across spending clusters
- K-means clustering to segment families by investment style (percentage of 
  budget vs. total annual spending)

## Key Findings

- Financial spending (total annual expenditure, % of family budget) was not a 
  significant predictor of parental satisfaction
- Satisfaction was driven instead by non-material values — importance of health 
  (β ≈ 1.13, p < 0.05) and discipline (β ≈ 1.13, p < 0.10)
- Cluster analysis identified three family investment profiles, but satisfaction 
  did not differ significantly across them (ANOVA: p = 0.857)
- 63% of families reported financial difficulties, but this rarely led to pausing 
  (7.3%) or stopping (0% for purely financial reasons) — consistent with an 
  "escalation of commitment" pattern

## Files

- Full paper, data and analysis notebook: [Google Drive](https://drive.google.com/drive/folders/1wrMGzDIQgziFV1n4wxiZwiYMkL4OpW9E?usp=sharing)

## Tools

Python 3.10 (pandas, numpy, seaborn, matplotlib, statsmodels, scipy.stats)
