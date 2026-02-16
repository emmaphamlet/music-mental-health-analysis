# Music and Mental Health: Exploring How Music Consumption Relates to Well-Being

A data analysis project examining relationships between music listening habits and self-reported mental health outcomes using Python, visualization, and statistical testing.

> **Note:** This project uses survey data with self-reported mental health scores. Findings are **correlational** and should not be interpreted as causal.

## Overview
This project explores how music listening behaviors relate to self-reported well-being metrics. It investigates whether music genre preference, listening duration, listening while working, and musician status are associated with differences in anxiety and depression scores.

## Research Questions
1. Do individuals who prefer calmer music genres report lower anxiety or depression scores than those who prefer high-energy genres?
2. Is there a relationship between hours spent listening to music per day and anxiety levels?
3. Does listening to music while working relate to anxiety or depression scores?
4. Do instrumentalists or composers report different mental health outcomes?

## Dataset
**Dataset:** Music and Mental Health Survey Results  
**Source:** Kaggle (original survey collected by Catherine Rasgaitis)

The dataset includes (examples):
- Preferred genre
- Hours per day listening to music
- Listening while working behavior
- Instrumentalist / Composer status
- Self-reported anxiety and depression scores

**Limitations:** self-report bias, convenience sampling (online communities), and non-representative demographics.

### Where to put the CSV
Place your CSV here (not committed by default):
```
data/mxmh_survey_results.csv
```

## Methods
- Data loading, cleaning, and validation (pandas + assertions)
- Exploratory Data Analysis (EDA)
- Genre categorization into **Calm** vs **High Energy**
- Visualization (seaborn/matplotlib + Plotly)
- Assumption checking (e.g., Shapiro-Wilk, Levene’s)
- Non-parametric hypothesis testing (Mann–Whitney U) when normality is violated

## Key Findings (from the notebook)
- Calm genre listeners showed slightly lower average anxiety and depression, but differences were not statistically significant.
- A slight positive relationship was observed between hours of music listening and anxiety.
- Participants who listened to music while working reported slightly higher anxiety and depression on average.
- Composers showed slightly higher depression scores compared to non-composers.

## Tools & Technologies
- Python
- pandas, NumPy
- seaborn, matplotlib
- Plotly
- SciPy
- Jupyter Notebook

## How to Run
1. Clone the repository
2. (Optional but recommended) Create a virtual environment
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Add the dataset file:
```bash
# copy your CSV into:
data/mxmh_survey_results.csv
```
5. Launch Jupyter:
```bash
jupyter notebook
```
6. Open:
```
notebooks/music_mental_health_analysis.ipynb
```

## Future Improvements
- Use more representative datasets and larger samples
- Control for demographics (age, gender, etc.) if available
- Try additional models (e.g., regression with controls)
- Add clearer effect sizes and confidence intervals

## License
This repository contains code and analysis. The dataset may have its own license/terms via Kaggle; check before redistributing it.
