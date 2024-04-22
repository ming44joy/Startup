Startup Success Prediction
==========================

Introduction
------------
This project utilizes R programming language and several libraries for data manipulation, visualization, and predictive modeling. The dataset used in this project contains information about startups, including their founding year, industry category, funding history, and eventual success status. The dataset used in this project is the "Startup Success Prediction" dataset obtained from Kaggle, it can be found here https://www.kaggle.com/datasets/manishkc06/startup-success-prediction 

Questions Explored
------------------
1.	What is the distribution and concentration of start-ups across different states?
2.	What is the distribution and concentration of start-ups across different categories?
3.	Are there any relationships between variables?
4.	Which industries have the highest and lowest success rates?
5.	What proportion of start-ups have been acquired versus closed?
6.	What are the counts of acquired and closed start-up companies for each state?
7.	Are there significant differences in the acquisition rates of start-ups across different states?
8.	Can we predict if a start-up will be successful (get acquired)?
9.	What features have the most significant impact on predicting start-up success?

Getting Started
---------------
To replicate the analysis and predictions, follow these steps:
1.	Clone the repository to your local machine.
2.	Install R and RStudio if not already installed.
3.	Install the required R packages specified in the code.
4.	Run the R scripts provided in the repository.

Data Preparation
----------------
The dataset was read from an Excel file and underwent several preprocessing steps, including converting binary variables to factors, dropping unnecessary columns, and handling missing values. Additionally, numerical variables were converted to integers, and NA values were imputed with zeros.

Exploratory Data Analysis (EDA)
-------------------------------
EDA was performed to understand the distribution of startups across different states and industries, identify relationships between variables, and analyze success rates across industries. The distribution of startups across states and industry categories was visualized using bar plots, and correlations between variables were explored using correlation matrices.

Statistical Analysis
--------------------
Statistical analysis was performed to uncover significant relationships and patterns within the data. This included exploring correlations between variables, such as funding rounds and success rates, to identify any notable trends. Additionally, Fisher's exact test was utilized to assess whether there were significant variations in acquisition rates across different states.

Predictive Modeling
-------------------
Three models were trained and evaluated: logistic regression, decision trees, and random forests. The random forest model performed the best, achieving high accuracy, sensitivity, and specificity. Variable importance analysis revealed that relationships, average number of participants, milestones, and top 500 status were the most influential features for predicting startup success.

Results and Discussion
----------------------
The results indicate that startup success can be predicted with reasonable accuracy using machine learning techniques. Important features identified in the analysis provide insights into factors that contribute to startup success. Further research could explore additional features and models to improve predictive performance.

In memory of my mother, Eleanor
-------------------------------
My mother recently passed and her favorite color was purple. To honor her I use purple in most of the visuals. 
