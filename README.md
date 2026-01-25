# Megaline Statistical Analysis

A comprehensive statistical analysis project comparing two prepaid mobile plans (Surf and Ultimate) for Megaline telecom operator to determine which plan generates more revenue and optimize advertising budget allocation.

## Project Overview

**Business Context:** Determining which mobile plan generates more revenue to guide marketing investment decisions.

This project analyzes customer behavior and revenue patterns from 500 Megaline clients during 2018. The analysis examines usage patterns (calls, messages, and internet data) across two prepaid plans to provide data-driven insights for the commercial department.

## What This Demonstrates

### Learning Challenge
- Statistical hypothesis testing was a new concept
- Understanding telecommunications metrics (calls, messages, data usage)
- Learning probability distributions and significance testing

### Problem-Solving Process
1. **Domain Research**: Studied telecom business models to understand what metrics matter
2. **Statistical Planning**: Used Copilot to understand which statistical tests are appropriate
3. **Systematic Analysis**: Analyzed calls, messages, and internet usage across 5 datasets
4. **Business Translation**: Converted statistical findings (p-values, confidence intervals) into "should we invest more in Plan A or Plan B?"

### Professional Outcome
- Provided a clear, data-driven recommendation that executives could use for budget allocation
- Demonstrated ability to apply academic concepts (statistics) to practical business decisions
- Created reproducible analysis that could be updated with new data

### Tools Utilized
- VS Code with GitHub Copilot for development
- Jupyter Notebook for interactive analysis
- Git/GitHub for version control

### Key Questions Addressed:
- Which prepaid plan (Surf or Ultimate) brings in more revenue?
- How do customer usage patterns differ between plans?
- Are there significant revenue differences between geographic regions?
- What recommendations can guide advertising budget allocation?

## Key Findings

The analysis reveals statistically significant differences in revenue between the Surf and Ultimate plans, providing actionable insights for marketing strategy optimization. Detailed findings and visualizations are available in the Jupyter notebook.

## Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **SciPy** - Statistical hypothesis testing
- **Jupyter Notebook** - Interactive development environment

## Repository Structure

```
statistical-analysis-project/
│
├── README.md
├── requirements.txt
├── index.html
├── statistical_analysis.ipynb
└── data/
    ├── megaline_calls.csv
    ├── megaline_internet.csv
    ├── megaline_messages.csv
    ├── megaline_plans.csv
    └── megaline_users.csv
```

## Analysis Workflow

1. **Data Loading & Exploration** - Import and examine datasets from multiple sources
2. **Data Cleaning** - Handle missing values, correct data types, and prepare data
3. **Feature Engineering** - Calculate monthly usage metrics and revenue
4. **Exploratory Analysis** - Analyze customer behavior patterns
5. **Statistical Testing** - Hypothesis testing to validate findings
6. **Conclusions** - Data-driven recommendations

## How to Run

### Prerequisites
```bash
python 3.7+
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vfoster-code/statistical-analysis-project.git
cd statistical-analysis-project
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook statistical_analysis.ipynb
```

Alternatively, view the pre-rendered HTML file in your browser:
```bash
open index.html
```

## Dataset Description

The analysis uses five interconnected datasets:

- **megaline_plans.csv** - Plan specifications and pricing
- **megaline_users.csv** - Customer demographic information
- **megaline_calls.csv** - Call duration records
- **megaline_messages.csv** - SMS message counts
- **megaline_internet.csv** - Mobile data usage

## Methodology

Statistical hypothesis testing using:
- **t-tests** for comparing mean revenues between groups
- **Significance level (α)**: 0.05
- Null and alternative hypothesis formulation
- P-value interpretation for decision making

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Statistical hypothesis testing
- Data visualization
- Business insights interpretation
- Python programming for data science

## License

This project was completed as part of the TripleTen AI/ML Engineering program.

## Author

**Victor Foster**
- GitHub: [@vfoster-repo](https://github.com/vfoster-repo)
- LinkedIn: [Victor Foster](https://linkedin.com/in/vfoster-connect)
- Email: victorfoster@hotmail.com

## Acknowledgments

- TripleTen  AI/ML Engineering Program Sprint 4 "Statistical Data Analysis"

---

If you found this project helpful, please consider giving it a star!