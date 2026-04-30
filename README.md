# NBA Lottery Reform & Team Recovery Analysis

## Overview

**Dataset: https://www.kaggle.com/datasets/ismailperacha/nba-tanking-teams-2019-2025 (Own)**

The NBA has explored changes to its draft lottery system to discourage tanking, including proposals to further flatten lottery odds.

A common concern is that reducing draft advantages for the worst teams could make it harder for them to rebuild, potentially trapping them at the bottom of the standings.

This project examines whether that concern is valid.

---

## Key Question
> Do bottom NBA teams get stuck at the bottom, or do they recover within a reasonable timeframe under the current lottery system?

---

## Approach
- Focus on **NBA lottery teams (seeds 1–14)** from 2018–19 onward  
- Group teams into tiers:
  - **Bottom 3** (worst records)
  - **Mid Lottery**
  - **Fringe Lottery**
- Track how long it takes teams to return to the playoffs

---

## Key Findings

- **Most teams recover quickly**  
  The majority of teams return to the playoffs within **1–3 years**

- **Bottom teams are slower—but not stuck**  
  Bottom 3 teams take ~**2.6 years** on average, compared to ~**1.9 years** for other lottery teams

- **Recovery happens across all tiers**  
  Over time, nearly all teams reach the playoffs regardless of starting position

---

## Interpretation

While worse teams do take slightly longer to recover, they are not trapped at the bottom. Most teams return to competitiveness within a reasonable timeframe.

This suggests that the current lottery system—despite reducing incentives for extreme tanking—still allows teams to rebuild effectively.

---

## Policy Insight

Recent NBA proposals aim to further flatten lottery odds.

This analysis suggests:
- Teams are already able to recover without relying heavily on top draft odds  
- Further flattening may not trap bottom teams  
- However, it could shift how teams approach rebuilding strategies  

---

## Dataset
Includes:
- Team performance (wins, win %, rank)
- Lottery seed and draft outcomes
- Time to playoff appearance
- Tier classification (Bottom 3, Mid, Fringe)

---

## Visualizations
- Distribution of years to playoffs  
- Recovery time by lottery tier  
- Cumulative recovery rates over time  

---

## Tools Used
- Python (Pandas, NumPy)
- Seaborn / Matplotlib
- Jupyter Notebook

---

## Future Work
- Compare pre-2019 vs post-2019 recovery timelines  
- Analyze long-term success beyond playoff appearances  
