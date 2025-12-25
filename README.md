# Workplace Satisfaction Survey – Exploratory Data Analysis Project

## Project Overview
This project analyzes a **Workplace Satisfaction Survey dataset** using Python to demonstrate core data analysis skills, including data cleaning, exploratory data analysis (EDA), statistical summaries, and data visualization. The project applies key concepts covered throughout the course and presents insights through both a written report and a PowerPoint presentation.

The analysis focuses on understanding individual variables, exploring relationships between variables, and applying principles of visual analytics to support meaningful interpretations.

---

## Project Objectives
The main objectives of this project are to:

- Apply Python programming structures (e.g., list comprehensions and loops)
- Use **Pandas** as the primary data structure for data manipulation
- Read and write data efficiently using Python
- Clean data by handling missing values and duplicates
- Generate descriptive statistics
- Perform exploratory data analysis (EDA)
- Analyze categorical and numerical variables
- Examine relationships between pairs of variables
- Conduct basic statistical tests where appropriate
- Visualize data using **Matplotlib** and Pandas plotting functions
- Present findings clearly through tables, graphs, and summaries

---

## Dataset Description
- **Dataset Name:** Workplace Satisfaction Survey Data  
- **File Format:** Excel (.xlsx)  
- **Description:**  
  This dataset contains survey responses related to employees’ workplace satisfaction, demographics, and job-related characteristics. The data was collected to better understand factors that may influence employee satisfaction and workplace experiences.

---

## Tools and Libraries Used
- **Python 3**
- **Jupyter Notebook**
- **Pandas** – data structures and data analysis
- **NumPy** – numerical computations
- **Matplotlib** – data visualization
- **Seaborn** – enhanced visualizations (if applicable)

---


---

## Data Analysis Workflow

### 1. Initial Data Preparation
- Loaded the dataset using Pandas
- Inspected the data using:
  - `head()`
  - `info()`
  - `describe()`
  - `isnull().sum()`
- Renamed columns for clarity and consistency
- Dropped unnecessary columns and rows using `drop()`
- Identified and handled missing values
- Checked for and removed duplicate records
- Explored unique values for each variable using loops

---

### 2. Descriptive Statistics
- Calculated key statistics including:
  - Mean
  - Median
  - Standard deviation
  - Minimum and maximum values
- Used descriptive statistics to understand variable distributions and identify potential outliers

---

### 3. Analysis of Individual Variables

#### Categorical Variables
- Created frequency and percentage tables using `pd.crosstab()`
- Included total sample size (n) in all tables
- Visualized distributions using bar charts and pie charts
- Applied principles of visual analytics to enhance interpretability

#### Numerical Variables
- Examined distributions using:
  - Histograms
  - Boxplots
- Verified minimum and maximum values using `describe()`
- Created categorized versions of numerical variables when appropriate
- Visualized categorized numerical variables using histograms

---

### 4. Analysis of Variable Pairs

#### Two Categorical Variables
- Used crosstabulations to explore relationships
- Calculated percentages using normalization
- Visualized relationships using grouped bar charts
- Made cautious, observational interpretations of results

#### Numerical and Categorical Variables
- Compared numerical distributions across categorical groups
- Used boxplots and grouped summary statistics

---

### 5. Data Visualization
- Created visualizations using Matplotlib and Pandas plotting functions
- Customized graphs by:
  - Adding titles and axis labels
  - Adjusting figure sizes
  - Modifying colors and styles
- Ensured all graphs clearly displayed frequencies, counts, and percentages

---

## Key Findings
- Identified patterns in workplace satisfaction across demographic and job-related variables
- Observed meaningful trends in satisfaction levels among different employee groups
- Highlighted relationships that may inform organizational decision-making

*Detailed results and interpretations are presented in the final report and PowerPoint presentation.*

---

## Deliverables
- **Jupyter Notebook:** Complete data cleaning, analysis, and visualization
- **Final Report:** Detailed methodology, findings, and conclusions
- **PowerPoint Presentation:** Summary of analysis using the provided template

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Masterofnone-92/-Work_Place_Satisfaction_Survey_Data_Analysis_Project.git

