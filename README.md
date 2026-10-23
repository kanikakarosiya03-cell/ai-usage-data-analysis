# AI Usage, Productivity & Satisfaction Analysis

### Exploring the Relationship Between AI Usage, Productivity, Time Savings, and User Satisfaction

## About the Project

How is daily AI usage related to productivity, time savings, and user satisfaction?

This project explores AI usage patterns among students and professionals through data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization using Python.

The goal is to discover meaningful patterns in the dataset and understand how reported AI usage relates to productivity, satisfaction, and time savings.

## Project Objectives

* Analyze AI usage patterns among different user groups.
* Explore the relationship between daily AI usage and productivity scores.
* Investigate the relationship between AI usage and reported time savings.
* Examine the association between AI usage and user satisfaction.
* Identify popular AI tools and common AI usage purposes.
* Communicate findings through clear and informative visualizations.

## Tools & Technologies

* **Python** — Data analysis and programming
* **Pandas** — Data cleaning and manipulation
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook** — Analysis and documentation

## Dataset

The dataset contains information about AI usage among students and professionals.

It includes attributes such as:

* Age, gender, country, and profession
* Education level and user type
* AI tools and their purposes
* Daily AI usage hours
* Monthly AI costs
* Productivity, accuracy, and satisfaction scores
* Reported weekly time savings
* Willingness to recommend AI tools

**Dataset size after duplicate removal:** 288 rows and 19 columns.

The dataset is synthetic, so the findings describe patterns within the available data and should not be treated as representative of all real-world AI users.

**Dataset source:** AI Usage and Impact on Students and Professionals — Kaggle.

## Project Workflow

### 1. Data Inspection

* Loaded the dataset into Pandas.
* Examined the dataset's structure, column names, data types, and summary statistics.
* Identified missing values, inconsistent category labels, and duplicate records.

### 2. Data Cleaning

* Handled missing values using appropriate imputation methods.
* Converted numerical fields to appropriate data types.
* Standardized inconsistent category labels.
* Removed 12 duplicate records, reducing the dataset from 300 to 288 rows.
* Checked the cleaned data using summary statistics and missing-value checks.

### 3. Exploratory Data Analysis

* Examined the distribution of AI tools and usage purposes.
* Compared AI usage across user types.
* Investigated relationships between AI usage, productivity, and time savings.
* Compared productivity scores across AI tools.
* Explored correlations among numerical variables.

### 4. Data Visualization

Created seven visualizations to explore patterns and communicate findings:

1. AI Tool Popularity
2. AI Usage by User Type
3. AI Usage vs. Productivity
4. AI Usage Purposes
5. Productivity Scores Across AI Tools
6. Correlation Heatmap
7. AI Usage vs. Time Saved

## Key Findings

### 1. AI Usage and Time Savings

A positive correlation of approximately **0.739** was observed between daily AI usage and reported weekly time savings.

This was the strongest of the three examined relationships.

### 2. AI Usage and Productivity

A positive correlation of approximately **0.637** was observed between daily AI usage and productivity scores.

Within this dataset, higher reported AI usage tended to be associated with higher productivity scores.

### 3. AI Usage and Satisfaction

A positive correlation of approximately **0.419** was observed between daily AI usage and satisfaction scores.

This relationship was weaker than the relationships with time savings and productivity.

### 4. Average Daily AI Usage

The average daily AI usage was approximately **2.92 hours**.

### 5. User Satisfaction

The average satisfaction score was approximately **6.13**.

### 6. Willingness to Recommend AI

Approximately **60.76%** of records indicated that users would recommend AI tools.

*Note: Correlation does not imply causation. These results reflect the analyzed dataset and do not establish that increased AI usage directly causes greater productivity, time savings, or satisfaction.*

## Skills Demonstrated

Through this project, I practised:

* Data cleaning and preprocessing
* Handling missing values and duplicate records
* Data type conversion and category standardization
* Exploratory data analysis
* Descriptive statistics
* Correlation analysis
* Data visualization using Matplotlib and Seaborn
* Interpreting and communicating analytical findings

## Project Structure

```text
ai-usage-data-analysis/
│
├── AI_Usage_Data_Analysis.ipynb
└── README.md
```

## Conclusion

This project helped me apply Python-based data analysis techniques to explore AI usage patterns and their relationships with productivity, reported time savings, and user satisfaction.

By working through data cleaning, exploratory analysis, correlation analysis, and visualization, I gained practical experience in transforming raw data into understandable insights.

This project represents my continued learning and development in **Python, data analysis, and data visualization**.

---

**Author:** Kanika Karoshia

**Focus Areas:** Python | Data Analysis | Exploratory Data Analysis | Data Visualization
