# NBA Tanking Analysis (Post-2019 Lottery Reform)

## Overview
**Dataset: https://www.kaggle.com/datasets/ismailperacha/nba-tanking-teams-2019-2025 (Own)**

The NBA changed its draft lottery system in 2019 to discourage tanking (intentionally losing for better draft picks).

This project analyzes whether those changes actually reduced the benefits of tanking by examining lottery teams and their outcomes over the next few seasons.

---

## Key Question
> After the 2019 lottery reform, does finishing with the worst record still help teams improve faster?

---

## Approach
- Focus on **lottery teams (seeds 1–14)** from 2018–19 onward  
- Group teams by level of tanking:
  - **Bottom 3** (extreme tanking)
  - **Mid Lottery**
  - **Fringe Lottery**
- Measure outcomes using:
  - **Time to playoffs**
  - **Playoff appearances within 3 years**
  - **Draft position vs future performance**

---

## Key Findings

- **Worst teams do not recover faster**  
  Bottom 3 teams take longer to reach the playoffs (~2.6 years) than mid and fringe lottery teams (~2.0 years)

- **Tanking does not accelerate success**  
  Extreme losing does not improve short-term outcomes

- **Teams are not stuck at the bottom**  
  Even the worst teams typically recover within a few years

---

## Interpretation

The results suggest that the NBA’s 2019 lottery reform may be achieving its goal of reducing tanking incentives.

While bad teams are still able to rebuild, finishing with the worst record no longer provides a strong advantage. Instead, teams with slightly better performance tend to return to competitiveness faster.

---

## Policy Insight

Recent proposals to further flatten lottery odds aim to continue reducing incentives for extreme tanking.

This analysis suggests:
- Tanking is already less effective than before  
- Further changes may reinforce this trend  
- However, overly reducing draft advantages could make rebuilding more difficult for struggling teams  

---

## Dataset
Includes:
- Team performance (wins, win %, rank)
- Lottery seed and actual draft pick
- Pick ownership (kept vs conveyed)
- Future outcomes (playoffs, years to recovery)

See `data_dictionary` for full column definitions.

---

## Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook

---

## Future Work
- Compare pre-2019 vs post-2019 outcomes
- Build predictive models for team success

---

## 📬 Contact
Open to feedback or collaboration on sports analytics and data science projects.
