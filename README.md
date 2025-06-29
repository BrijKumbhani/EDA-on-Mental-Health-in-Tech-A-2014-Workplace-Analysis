# EDA on Mental Health in Tech: A 2014 Workplace Analysis

This project presents a detailed Exploratory Data Analysis (EDA) of mental health in the technology sector, based on the 2014 workplace mental health survey conducted by Open Sourcing Mental Illness (OSMI). The goal is to provide insights that can help organizations understand patterns in treatment-seeking behavior, workplace support, and employee perceptions regarding mental health, guiding data-driven improvements in workplace policies.

## Project Objectives

* Explore demographic, workplace, and mental health treatment patterns among tech workers.
* Analyze relationships between workplace characteristics and employee mental health outcomes.
* Provide actionable insights for companies to improve mental health support systems.
* Meet deployment-grade standards by ensuring clean, well-commented, production-ready code that runs top-to-bottom without errors.

## Key Features of This Project

* **Data Cleaning & Wrangling:**

  * Removed duplicate entries and age outliers.
  * Standardized gender categories.
  * Handled missing values using appropriate imputation strategies.
  * Converted categorical variables to `category` dtype for efficiency.

* **Visualization & Insights:**

  * 15 high-quality, logical, and meaningful charts (following UBM rule: Univariate, Bivariate, Multivariate).
  * Each chart includes rationale, insights, and business impact analysis.
  * Required charts such as Correlation Heatmap and Pair Plot are included.

* **Deployment Ready:**

  * Exception handling in all code blocks.
  * Notebook runs cleanly in one go without errors.
  * Well-structured, commented code for ease of understanding and reuse.

* **Business Impact Focus:**

  * Insights geared toward helping organizations create inclusive and supportive mental health strategies.
  * Identified gaps in mental health benefits, treatment-seeking behavior, and employee perceptions.

## Project Structure

```
├── EDA-on-Mental-Health-in-Tech-A-2014-Workplace-Analysis/
│   ├── EDA_Notebook.ipynb      # Complete EDA notebook with charts, insights, and business analysis
│   ├── survey.csv              # Dataset used (uploaded via Google Drive or local path)
│   ├── README.md               # This file
└── ...
```

## Key Insights

* Most respondents are between their mid-20s and early 40s, with a majority identifying as male.
* Larger companies are more likely to offer mental health benefits.
* A significant portion of respondents have sought mental health treatment, but barriers such as fear of negative workplace consequences persist.
* No strong relationship between age or gender and treatment-seeking behavior, highlighting the need for inclusive programs.

## Future Scope

* Extend analysis with more recent datasets for trend analysis.
* Build predictive models to identify key drivers of treatment-seeking behavior.
* Conduct sentiment analysis on open-ended comments for qualitative insights.
* Develop interactive dashboards for real-time data exploration.

## How to Run

1. Clone this repository:

   ```
   git clone https://github.com/BrijKumbhani/EDA-on-Mental-Health-in-Tech-A-2014-Workplace-Analysis.git
   ```
2. Open the notebook `EDA_Notebook.ipynb` in Jupyter or Google Colab.
3. Ensure the dataset (`survey.csv`) is available in the appropriate path or update the file path accordingly.
4. Run all cells sequentially to reproduce the analysis.

## Author

**Brij Kumbhani**
[GitHub Profile](https://github.com/BrijKumbhani)

## License

This project is open source and available under the MIT License (if applicable — add LICENSE file if you want to include this).

## Acknowledgments

* Visualization libraries: Seaborn, Matplotlib, Plotly
* Tools: Python, Jupyter, Google Colab
* Thanks to open source contributors for maintaining the libraries used in this project
