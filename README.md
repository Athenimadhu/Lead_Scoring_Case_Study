# Lead_Scoring_Case_Study

## Problem Statement
X Education, an online education company, aims to improve its lead conversion rate. Despite attracting many leads, the company's conversion rate remains low (around 30%). The company wants to identify potential leads, or 'Hot Leads', with a higher likelihood of conversion. This will allow the sales team to focus efforts on promising leads, leading to a more efficient conversion process. The company requires a lead scoring model that assigns a score between 0 and 100 to each lead, indicating the conversion likelihood. The target is to achieve a lead conversion rate of around 80%.

## Background
X Education offers online courses to industry professionals. Prospective leads visit the website, browse courses, and may fill forms, watch videos, or provide contact details. Leads are obtained through website visits, referrals, and interactions. Sales teams engage leads, attempting conversion through calls and emails. The current process lacks efficiency, leading to the need for accurate lead scoring

## Data
A dataset with around 9000 data points includes attributes like Lead Source, Total Time Spent on Website, Last Activity, Total Visits, etc. The 'Converted' column indicates past lead conversion (1 = converted, 0 = not converted). Data cleaning handles missing values and categorical variables with a 'Select' level.

## Goals
1. Build a logistic regression model to assign lead scores (0-100) for potential leads.
2. Address future adjustments in the model to meet changing company requirements.
3. Prioritize 'Hot Leads' for effective communication and improved conversion rates.

## Approach
1. Data Cleaning: Handle missing values, categorical variables, and prepare the dataset.
2. Data Preparation: Create dummy features for categorical variables, split data, and perform feature scaling.
3. Exploratory Data Analysis: Understand data patterns and relationships.
4. Feature Engineering: Create lead score using logistic regression model.
5. Model Evaluation: Assess model performance and adjust for future requirements.
6. Documentation: Provide Jupyter notebook, word document, presentation, and summary report.

## Results
The lead scoring model identifies potential leads for improved conversion rates. The lead score helps prioritize sales efforts towards Hot Leads. The solution includes comprehensive documentation, analysis, and recommendations for future model adjustments.

## Repository Structure
- `Lead Scoring Assignment.ipynb`: Jupyter notebook containing  data analysis, model building, and evaluation.
- `Lead Scoring Assignment Q&A.pdf`: Detailed solutions to case study questions in a PDF document.
- `Lead Scoring Assignment Presentation.pdf`: Concise presentation summarizing analysis, insights, and recommendations.
- `Lead Scoring Assignment Summary.pdf`: A 500-word summary report outlining the assignment process and key learnings.

For more details, refer to the data dictionary provided in the 'Leads.csv', 'Leads Data Dictionary.xlsx',  folder and address categorical variable 'Select' levels. The repository comprehensively addresses the lead scoring case study, enabling X Education to enhance lead conversion rates.
