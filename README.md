# Global Layoffs Data Analysis Project

## Overview

This project involves analyzing a dataset that tracks layoffs across companies worldwide. The dataset includes information about the company name, location, layoff dates, total employees laid off, the percentage of workforce laid off, industry type, company stage, and funds raised.

The objective is to:
- **Clean the dataset** to ensure consistency and accuracy.
- **Perform Exploratory Data Analysis (EDA)** to identify trends, patterns, and insights regarding layoffs across various industries, countries, and company stages.

## Project Structure

The project consists of three main components:
1. **Data Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Insights and Conclusion**

### 1. Data Cleaning

The raw dataset contained various inconsistencies and missing values, which needed to be addressed to ensure accurate analysis. The cleaning process involved:
- **Handling missing values**: Some rows had missing data in key columns like `percentage_laid_off` and `funds_raised`. These missing values were either filled or excluded from the analysis based on the context.
- **Removing duplicates**: Duplicate records were identified and removed to avoid skewed results.
- **Standardizing formats**: The `date` field was standardized to ensure consistent date formats across the dataset. Other fields such as `location` and `industry` were also cleaned to maintain consistency in naming.
- **Outlier detection**: Extreme outliers in the `total_laid_off` and `percentage_laid_off` fields were identified, though some outliers (like startups laying off 100% of their workforce) were kept for analysis as they were valuable for insights.
  
### 2. Exploratory Data Analysis (EDA)

Once the data was cleaned, the focus shifted to uncovering trends and insights. The key areas explored in the EDA process included:
- **Biggest layoffs by company**: Identifying companies that had the largest total number of employees laid off during the dataset’s time period.
- **Layoff percentages**: Analyzing the percentage of the workforce laid off to understand which companies and industries were most impacted.
- **Industry-wise analysis**: Investigating which industries experienced the most layoffs, with particular focus on sectors like tech, retail, and finance.
- **Country and location trends**: Analyzing layoffs by country and location to see how different regions were affected.
- **Yearly trends**: Examining layoffs by year to see how they trended over time, which can offer insights into global economic conditions.
- **Company stage**: Investigating how different stages of company growth (e.g., startup, established) affected layoff patterns, with insights into how smaller, early-stage companies were disproportionately impacted.
  
### 3. Key Insights and Conclusion

From the analysis, the following insights were gathered:
- **Industries like technology and startups were hit hardest** by layoffs, with some companies laying off their entire workforce.
- **Larger, established companies** contributed significantly to the total number of layoffs, but they had lower layoff percentages, indicating more stability compared to startups.
- **Global economic trends** such as the pandemic or financial downturns were reflected in spikes in layoffs, particularly in specific years.
- **Certain countries and regions** were more affected, which could be linked to the local economy, government policies, or concentration of specific industries.

Overall, the project highlighted the major impact of layoffs on global industries, with insights into the factors driving these layoffs and how companies across different sectors responded.

## How to Use the Project

The project includes three files within the `MySQL` folder:
- **Data Cleaning**: Contains the processes followed to clean and preprocess the dataset for analysis.
- **EDA**: This file focuses on analyzing the cleaned data to uncover trends and patterns related to layoffs.
- **Layoffs Data**: The dataset containing the raw information used in the project.

To run this project, you can execute the SQL queries provided in the files using any MySQL environment.

## Presentation

A PowerPoint presentation summarizing the analysis and findings is included in this repository. This presentation provides a visual overview of the project and the insights derived from the data.

## Conclusion

The analysis provided a clear understanding of how layoffs have impacted different industries, companies, and regions across the globe. Through detailed data cleaning and EDA, key insights were derived about the largest layoffs, trends by year, industry, and location, and the overall effect of these layoffs on companies of different sizes and stages.


## Acknowledgment

This project was inspired by [Alex The Analyst's](https://www.youtube.com/c/AlexTheAnalyst) YouTube tutorial on data analysis. While I followed some of the steps from his tutorial, I expanded on the project by adding additional queries and insights to further analyze the dataset, making this project a unique learning experience.

