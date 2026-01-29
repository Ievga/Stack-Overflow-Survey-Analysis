# Stack-Overflow-Survey-Analysis
This project explores the **Stack Overflow Annual Developer Survey** to identify key drivers of the professional success in the tech industry. In my analysis I focused on compensation, education path, and the remout working specialists to provide data-driven insights for developers and recuters.

## Data Analysis Process
The full analysis, including data cleaning and insights, can be found in the Jupyter Notebook:
👉 [View Full Analysis (Jupyter Notebook)](Stack_Overflow_Analysis.ipynb)

## Data Source
The dataset used in this project is sourced from the **Stack Overflow Developer Survey**. 
You can find the official datasets here: [Stack Overflow Survey Data](https://insights.stackoverflow.com/survey) Please download the dataset from the official site and place it in our data folder.

## Tech Stack
**Language:** Python
**Library:** Pandas (Data Manipulation), NumPy (Statistical Analysis)
**Environment:** Jupiter Notebook

## Key Analysis Stages & Methodology
**1.Data exploration & Validation:**
* Filtered columns with high response rates and handled missing values (NaN).
* Performed a **Data Quality Audit** to ensure integrity before analysis.
**2.Completion Rate Analysis:**
* Calculating the "fill rate", the most filled columns (Top 15), the highest completion level in the survey.
**3.Statistical Profiling:**
* Analyzed work expirience using **Mean, Median, Mode**.
* Identified a **Bimodal Distribution** and a **Right-Skewed**  distribution in expirience.
**4.Remout WorkTrends:**
* CaCalculating the amount of the remout working specialists.
**5.Python Popularity Audit:**
* Calculate the percentage of Python popularity among respondents.
**6.Education Path Analysis:**
* Exploring the shift between formal university degrees and online learning/self-taught routes.
**7.Geographical Compensation Analysis for Python Developers:**
* Calculating mean and median salaries across countries to identify top 15-paying regions.
**8.Analysis of Education Among Top-Earning Specialists:**
* Identified Education level of the Top 5-earning specialists.
* A fascinating result: The highest-paid specialist in the database does not hold a formal university degree in CS.
**9.Determination of Python Popularity Across Age Categories**
* Ensuring we are working with the dataframe correctly (Using .loc[:]).
* Calculating **Percentage** of **Python** popularity across age categories.
**10.Industry & High-Earner Profiling:** 
* Using **75th Percentiles (Quantiles)** to analyze where the most successful specialists work (Fintech, Healthcare, etc.).

## Key Findings & Insights
**The "Self-Taught" Phenomenon:** My analysis proved that some of the highest-paid individuals in the database hold no formal CS degree, emphasizing the value of skills over diplomas.
**Python's Stability:** Python maintains a dominant position across all age groups, demonstrating it's not just a "trend" but a core industry standard.
**Skewed Distributions:** 
The results are expected for the high pay/remote work combination:
* Software Development is the most flexible industry for remote opportunities and a classic leader in compensation.
* Fintech: High salaries are driven by significant responsibility and strict personal data security requirements.
* Healthcare: High demand due to personal data management and the need to collect, process,
and store vast amounts of critical information.

## How to Run
Clone the repository.
Install dependencies: pip install pandas numpy
Run Stack_Overflow_Analysis.ipynb.


