# AI Job Market Analysis (2025–2026)

An exploratory data analysis of 1,500 AI job listings across 14 countries, examining salary trends, in-demand skills, remote work patterns, and the emerging LLM job market.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Key Findings

- **Median AI salary is $180k**, with Architecture roles topping out at $238k and Lead-level positions earning 64% more than Entry-level.
- **Python appears in 62.8% of all listings** — the single most in-demand skill across the board.
- **ML Operations is the fastest-growing category** at 55.4% YoY demand growth, signalling a shift from model building to production deployment.
- **LLM-specific roles** show a modest salary premium ($191k vs $180k) but significantly higher demand growth (42.4% vs 21.5% YoY).
- **Hybrid work dominates** at 45.7%, followed by Fully Remote (29.7%) and On-site (24.6%).

## Dataset

- **Source:** [AI Job Market Global 2025–2026](https://www.kaggle.com/datasets/atharvasoundankar/ai-job-market-global-2026) (Kaggle)
- **Size:** 1,500 rows × 25 columns
- **Coverage:** 14 countries, 12 industries, 12 job categories, 25 unique job titles
- **Note:** This dataset is likely synthetic — distributions are unusually even across categories. Findings should be treated as illustrative of plausible trends.

## Analysis Structure

| Section | Description |
|---------|-------------|
| Data Overview & Quality Check | Shape, types, nulls, duplicates, unique values |
| Data Cleaning & Preparation | Feature engineering — labels, skills parsing, date columns |
| Salary Analysis | Distribution, by experience, job category, and company size |
| Skills Analysis | Top skills, salary by skill, skill count vs pay |
| Geographic & Remote Work | Salary by country, remote work distribution and trends |
| Demand & Growth Trends | Category growth rates, demand vs salary, AI premium by industry |
| LLM Roles Deep Dive | LLM vs Non-LLM comparison across salary, demand, and skills |
| Key Takeaways | Summary of findings and limitations |

## Visualisations

The notebook generates **16 charts** including:
- Salary distribution histograms and box plots
- Horizontal bar charts for median salary by category and country
- Violin plots for company size salary comparison
- Pie charts and stacked bars for remote work analysis
- Scatter plots for demand score vs salary
- Side-by-side skill comparisons (LLM vs Non-LLM)
- Correlation heatmap across all numerical features

## Tech Stack

- **Python 3.x**
- **pandas** — data manipulation and aggregation
- **matplotlib** — base plotting and customisation
- **seaborn** — statistical visualisations
- **numpy** — numerical operations

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Devashree2204/AI-job-market-analysis.git
   cd ai-job-market-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook ai_jobs_analysis.ipynb
   ```

> Make sure `ai_jobs_market_2025_2026.csv` is in the same directory as the notebook.

## Project Structure

```
ai-job-market-analysis/
├── ai_jobs_analysis.ipynb          # Main analysis notebook
├── ai_jobs_market_2025_2026.csv    # Dataset
├── README.md
├── requirements.txt
└── .gitignore
```

## Author

**Devshree** — Aspiring Data Analyst

---
*Built as a portfolio project to demonstrate exploratory data analysis and data visualisation skills.*
