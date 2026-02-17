# CS 4379G — Assignment 1: Netflix Titles Analysis

**Author:** Aleena  
**Course:** CS 4379G — Data Analysis & Visualization  
**Instructor:** Dr. Aniruddha Bora

## Overview

This repository contains a reproducible analysis of the Netflix Movies and TV Shows dataset. It answers these research questions-

1. How has the number of titles added to Netflix changed over time (by year)?
2. Do Movies and TV Shows differ in typical duration or in ratings distribution?

## Key Findings

- Netflix title additions peaked around 2019, then declined — likely due to strategic shifts toward originals and licensing changes.
- Movies make up ~70% of the catalog, but TV Show additions have grown significantly over time.
- The typical movie is about 98 minutes long; most TV Shows are single-season.
- TV Shows skew heavily toward mature (TV-MA) ratings compared to Movies, which are spread across a wider range of audience ratings.

## How to Run

1. Clone this repository.
2. Ensure you have Python 3.8+ with `pandas`, `numpy`, and `matplotlib` installed:
   ```
   pip install pandas numpy matplotlib
   ```
3. Place `netflix_titles.csv` in the same directory as the notebook (or download it from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)).
4. Open `notebooks/analysis.ipynb` in Jupyter and run **Kernel → Restart & Run All**.

## Repository Structure

```
├── README.md
├── .gitignore
└── notebooks/
    └── analysis.ipynb
```

## Dataset Citation

Dataset provided by the instructor. Originally from Kaggle:  
Shivam Bansal, "Netflix Movies and TV Shows," 2021.  
https://www.kaggle.com/datasets/shivamb/netflix-shows
