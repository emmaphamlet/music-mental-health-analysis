# Music and Mental Health: Exploring How Music Consumption Relates to Well-Being

A data analysis project examining relationships between music listening behaviors and self-reported mental health outcomes using Python, visualization, and statistical testing.

---

## Overview

This project explores how music listening behaviors relate to self-reported well-being metrics. The analysis investigates whether music genre preference, listening duration, listening while working, and musician status are associated with differences in anxiety and depression scores.

The project focuses on exploratory data analysis, statistical testing, and careful interpretation of correlational results.

---

## Research Questions

1. Do individuals who prefer calmer music genres report lower anxiety or depression scores than those who prefer high-energy genres?
2. Is there a relationship between hours spent listening to music per day and anxiety levels?
3. Does listening to music while working relate to anxiety or depression scores?
4. Do instrumentalists or composers report different mental health outcomes?

---

## Key Findings

- Calm genre listeners showed slightly lower average anxiety and depression scores, but differences were **not statistically significant**.
- A slight positive relationship was observed between hours of music listening and anxiety scores.
- Participants who listened to music while working reported slightly higher anxiety and depression on average.
- Composers showed slightly higher depression scores compared to non-composers.

These findings are **correlational** and should not be interpreted as causal relationships.

---

## Methods

- Data cleaning and validation using pandas
- Exploratory Data Analysis (EDA)
- Visualization using seaborn, matplotlib, and Plotly
- Assumption testing (Shapiro-Wilk and Levene’s tests)
- Non-parametric hypothesis testing using the Mann–Whitney U test

---

## Tools & Technologies

Python • pandas • NumPy • seaborn • matplotlib • Plotly • SciPy • Jupyter Notebook

---

## Dataset

Dataset: Music and Mental Health Survey Results  
Source: Kaggle (original survey collected by Catherine Rasgaitis)

The dataset contains self-reported metrics and convenience sampling from online communities, which limits generalizability.

The dataset is not included in this repository.

---

## Running the Project

```bash
pip install -r requirements.txt
jupyter notebook
