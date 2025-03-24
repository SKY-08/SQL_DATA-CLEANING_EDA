# Employee Layoffs Analysis (SQL)

This repository contains an analysis project focused on **Employee Layoffs**. The project is split into two main phases:
1. **Data Cleaning**: This phase involves cleaning the raw dataset to remove inconsistencies, handle missing values, and prepare the data for analysis.
2. **Exploratory Data Analysis (EDA)**: In this phase, SQL queries are used to analyze the cleaned dataset, providing insights into trends, patterns, and factors influencing employee layoffs.

The purpose of this project is to provide a deeper understanding of employee layoffs and how various factors such as department, tenure, region, and other demographic factors impact layoff decisions.

## Project Structure:
The project is divided into two primary sections:
- **Data Cleaning**: Where we preprocess the raw dataset by handling missing values, correcting inconsistencies, and ensuring that the data is in a usable format.
- **Exploratory Data Analysis (EDA)**: Where we conduct in-depth analysis to uncover trends and insights related to the layoffs, such as which departments were most affected, how tenure impacts layoffs, and regional patterns.

## Folder Breakdown:
### 1. **Data Cleaning**:
In the `/data_cleaning` folder, you'll find:
- **`data_cleaning_script.sql`**: SQL script used for cleaning the raw dataset. This includes steps for handling missing values, removing duplicates, and transforming the data into a usable format.
- **`cleaned_data.csv`** (or another format): The cleaned dataset that results from the **data_cleaning_script.sql** script. This dataset can be used for further analysis or shared with others.

### 2. **Exploratory Data Analysis (EDA)**:
In the `/eda` folder, you'll find:
- **`eda_script.sql`**: SQL script used for performing EDA on the cleaned dataset. The queries analyze the layoffs data to uncover trends, patterns, and key statistics.
- **`eda_report.md`** (optional): A markdown report summarizing the key insights and findings from the exploratory data analysis. This could include visualizations (if applicable), summary statistics, and significant trends.

## Key Insights from the Project:
### Data Cleaning:
- **Missing Values**: The data cleaning phase addresses any missing or inconsistent values in the dataset, ensuring that the final analysis is based on complete and accurate data.
- **Data Normalization**: All categorical variables were standardized (e.g., "Yes" / "No" values) and numerical data was cleaned to avoid discrepancies.

### Exploratory Data Analysis (EDA):
- **Layoffs by Department**: We found that certain departments, such as [insert department name], experienced a higher frequency of layoffs, possibly due to [insert reason].
- **Tenure and Layoffs**: There was a noticeable correlation between employee tenure and likelihood of being laid off. Employees with [shorter/longer] tenure were more/less likely to be impacted by layoffs.
- **Regional Trends**: Employees in specific regions were more affected by layoffs, which could be attributed to [insert reason].
- **Demographic Influence**: Insights regarding how employee characteristics (age, gender, education, etc.) correlated with layoff decisions.

## How to Run the SQL Scripts:
1. Clone this repository using `git clone <repo_url>`.
2. Open the SQL scripts in your preferred SQL editor (e.g., MySQL Workbench, pgAdmin, or any SQL interface).
3. To clean the data, run the **`data_cleaning_script.sql`** script. This will process the raw dataset and create a cleaned version.
4. After cleaning the data, run the **`eda_script.sql`** to perform the exploratory data analysis on the cleaned dataset. This will provide insights into various trends and factors influencing the layoffs.
5. Optionally, review the **`eda_report.md`** file for a summary of the key findings and trends identified in the analysis.

## Installation:
1. Clone this repository using `git clone <repo_url>`.
2. Ensure that you have access to a SQL database or environment (e.g., MySQL, PostgreSQL, etc.).
3. Open the `data_cleaning_script.sql` and **`eda_script.sql`** files in your SQL editor and execute them.
4. If needed, download the cleaned dataset (**`cleaned_data.csv`**) for further analysis or reporting.

## Conclusion:
The **Employee Layoffs Analysis** project provides valuable insights into the factors that influence layoff decisions. By cleaning the data and conducting exploratory analysis using SQL, we were able to uncover important trends and patterns that can help organizations better understand the dynamics behind employee layoffs and make data-driven decisions in the future.
