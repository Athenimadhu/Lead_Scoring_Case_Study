# Lead_Scoring_Case_Study

## Problem Statement
X Education, an online education company, aims to improve its lead conversion rate. Despite attracting many leads, the company's conversion rate remains low (around 30%). The company wants to identify potential leads, or 'Hot Leads', with a higher likelihood of conversion. This will allow the sales team to focus efforts on promising leads, leading to a more efficient conversion process. The company requires a lead scoring model that assigns a score between 0 and 100 to each lead, indicating the conversion likelihood. The target is to achieve a lead conversion rate of around 80%.

## Background
X Education caters to industry professionals seeking online courses. Prospective customers visit the website, browse courses, fill forms, and leave contact details, becoming leads. Sales efforts include calls, emails, etc., converting some leads. The challenge is to identify Hot Leads for increased conversion rates.

## Data
A dataset with around 9000 data points includes attributes like Lead Source, Total Time Spent on Website, Last Activity, etc. The 'Converted' column indicates past lead conversion (1 = converted, 0 = not converted). Data cleaning handles missing values and categorical variables with a 'Select' level.

## Goals
1. Build a logistic regression model to assign lead scores (0-100) for potential leads.
2. Address future adjustments in the model to meet changing company requirements.

## Approach
1. Data Cleaning: Handle missing values, categorical variables, and prepare the dataset.
2. Exploratory Data Analysis: Understand data patterns and relationships.
3. Feature Engineering: Create lead score using logistic regression model.
4. Model Evaluation: Assess model performance and adjust for future requirements.
5. Documentation: Provide Jupyter notebook, word document, presentation, and summary report.

## Results
The lead scoring model identifies potential leads for improved conversion rates. The lead score helps prioritize sales efforts towards Hot Leads. The solution includes comprehensive documentation, analysis, and recommendations for future model adjustments.

## Repository Structure
 `Lead Scoring Assignment.ipynb`: Jupyter notebook containing data analysis, model building, and evaluation.
  `Lead Scoring Assignment Q&A.pdf`: Word document with detailed solutions to case study questions.
 `Lead Scoring Assignment Presentation.pdf`: Concise presentation summarizing analysis, insights, and recommendations.
 `Lead Scoring Assignment Summary.pdf`: A summary report outlining the assignment process and key learnings.

For more details, refer to the data dictionary provided in the 'Leads.csv', 'Leads Data Dictionary.xlsx',  folder and address categorical variable 'Select' levels. The repository comprehensively addresses the lead scoring case study, enabling X Education to enhance lead conversion rates.
