# MasterControlSoloWork
## See https://github.com/cjcall99/Group-5-Capstone-MasterControl for full group project repository 

This repository contains my R Markdown and HTML files for the exploratory data analysis and modeling conducted for MasterControl’s manufacturing (Mx) and quality (Qx) product lines. The final deliverable was completed as part of a four person team for a Master’s Capstone practice project.

## Summary of Objective & Business Problem

MasterControl offers two primary product lines: Qx (quality management) and Mx (manufacturing operations). While Qx has longer marker presence and demonstrates strong performance, Mx is new and underperforms with a lower sales lead progression rate. The business problem addressed in this project is: What leads are most likely to convert for the Mx product? The goal is to improve Mx lead progression by identifying leads with high potential for progression and refining marketing targeting strategies.

## Solution

We developed predictive models to identify which leads are most likely to progress in the sales pipeline for the Mx product. By leveraging data (ex: company size, industry, manufacturing model) and buyer characteristics (ex: job title, seniority), the model helps prioritize high-quality leads. This enables MasterControl to move away from broad, inefficient targeting and instead focus on accounts and personas with the highest likelihood of conversion.

## My Contributions

My primary contributions focused on data cleaning and model development. Each team member developed their own code, and it was compiled to provide the optimal outcome. I prepared my dataset by addressing missing values and standardizing variables such as job titles for analysis. I then built multiple models to evaluate predictive performance, including logistic regression, XGboost, and a random forest model. 

## Business Value

This model served a foundation for my contribution to the group project. After compiling the other teams files, we were able to find the best model and approach. This model allows MasterControl to prioritize leads based on predicted conversion likelihood. By setting an appropriate decision threshold, the company can balance targeting high-probability accounts while maintaining sufficient market coverage. This leads to improved sales efficiency, higher Mx conversion rates, and better allocation of sales resources. Additionally, the model supports identification of cross-sell opportunities among existing Qx customers who are strong candidates for Mx.

## Difficulties

Some challenges encountered and addressed include:

Managing missing and inconsistent data 
Standardizing thousands of unique job titles into meaningful categories
Ensuring models were reproducible and generalizable
Translating model outputs into actionable business recommendations for targeting and segmentation
Coordinating collaborative work while maintaining consistent code structure

## Key Takeaways

This project strengthened my ability to:

Clean and preprocess complex, real business data
Build and compare multiple predictive models
Evaluate model performance and apply results in a business context
Translate analytical outputs into actionable sales and marketing strategies
Identify high  customer segments and ideal customers
Collaborate effectively within a team to produce reproducible insights

## Repository Contents
-'April Master Control -EDA.Rmd'
R Script, Exploratory Data Analysis, initial data cleaning and data insights 

-'April-Master-Control--EDA.html' 
HTML file of Exploratory Data Analysis

-'Modeling-Mastercontrol_April-Add.Rmd' 
R Markdown file containing my initial predictive modeling workflow and model evaluation.

-'Modeling-Mastercontrol_April-Add.html' 
HTML file containting my intial predictive modeling workflow and model evaluation.

-'README.md'
Project documentation describing the business problem and project insights
