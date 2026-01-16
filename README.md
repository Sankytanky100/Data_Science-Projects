# Data Science Projects Portfolio

A curated set of data science notebooks spanning exploratory data analysis, statistical modeling, SQL analytics, and applied machine learning. Each notebook is self-contained and includes problem framing, methodology, and findings. This repository is meant to be recruiter-friendly: projects are easy to run, clearly documented, and organized by topic.

## Contents

| Project | Focus | Tools |
| --- | --- | --- |
| `Air_Quality_Using_R.ipynb` | Air quality exploration and modeling | R, tidyverse |
| `Analyze_Twitch_Gaming_Data_Using_SQL.ipynb` | SQL analysis of Twitch gaming data | SQL |
| `Attribution_Queries_Using_SQL.ipynb` | Marketing attribution queries | SQL |
| `Craigslist_Analysis_Linear_Regression.ipynb` | Regression modeling of Craigslist data | Python, scikit-learn |
| `Effect_of_Emergency_Weather_Systems_on_Transit_Times_Using_R.ipynb` | Transit-time analysis with weather impacts | R, ggplot2 |
| `Enhanced_Recovery_After_Surgery_Using_R.ipynb` | Healthcare outcomes analysis | R |
| `Exploratory_Data_Analysis.ipynb` | General EDA workflow | Python, pandas |
| `Farm_Yield_Using_R.ipynb` | Agricultural yield modeling | R |
| `Forest_Fires_(Multiple_Linear_Regression).ipynb` | Multiple linear regression | R |
| `Funnel_Metrics_with_SQL.ipynb` | Product funnel metrics | SQL |
| `Heart_Disease_Detection.ipynb` | Classification modeling | Python, scikit-learn |
| `NLP_Spam_Filtering.ipynb` | NLP classification | Python, scikit-learn |

## How to Run

### Jupyter (recommended)

1. Install Jupyter Notebook or JupyterLab.
2. Open the notebook you want to review.
3. Run cells top-to-bottom.

### Python environment (for Python notebooks)

These notebooks typically use the scientific Python stack:

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

### R environment (for R notebooks)

Install R and RStudio or use an R kernel in Jupyter. Common packages used include:

```r
install.packages(c("tidyverse", "ggplot2", "dplyr"))
```

## Notes for Reviewers

- Each notebook is structured to highlight the question, approach, and results.
- Code cells are organized to be reproducible without manual edits.
- Visuals are labeled to clearly communicate the insights.

If you’d like a specific project exported as a PDF or presented as slides, open an issue or reach out.

## Notebook Readiness Checklist

If you want every notebook to feel “job-ready,” make sure each includes:

- A short markdown overview (problem statement, data source, key questions).
- A requirements note (libraries + versions if possible).
- Clear data-loading steps (with paths or download links).
- Interpretable outputs (plots/tables with labels and brief written takeaways).
