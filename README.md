# Megaline Statistical Analysis

A comprehensive statistical analysis project comparing two prepaid mobile plans (Surf and Ultimate) for Megaline telecom operator to determine which plan generates more revenue and optimize advertising budget allocation.

## Project Overview

This project analyzes customer behavior and revenue patterns from 500 Megaline clients during 2018. The analysis examines usage patterns (calls, messages, and internet data) across two prepaid plans to provide data-driven insights for the commercial department.

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

## Project Structure

```
statistical-analysis-project/
├── README.md                          # Project documentation
├── requirements.txt                   # Python dependencies
├── data/                             # Dataset files
│   ├── megaline_calls.csv           # Call records
│   ├── megaline_internet.csv        # Internet usage data
│   ├── megaline_messages.csv        # SMS records
│   ├── megaline_plans.csv           # Plan details
│   └── megaline_users.csv           # User information
└── notebooks/
    ├── statistical_analysis.ipynb   # Main analysis notebook
    └── statistical_analysis.html    # HTML export for viewing
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
jupyter notebook notebooks/statistical_analysis.ipynb
```

Alternatively, view the pre-rendered HTML file in your browser:
```bash
open notebooks/statistical_analysis.html
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