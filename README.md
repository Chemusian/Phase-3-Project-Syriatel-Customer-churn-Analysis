SYRIATEL PREDICTIVE ANALYSIS OF CUSTOMER CHURN

Student Name: Winny Chemusian

PROJECT PHASE 3

Overview

SyriaTel, a telecommunications company bases in Damascus Syria, encounters a notable obstacle in curtailing customer churn, which can detrimentally affect its revenue and overall profitability. The telecommunications industry is highly competitive, with companies vying for market share and profitability. Customer retention is crucial for sustained success, as high churn rates can significantly impact revenue and profitability. Understanding its market position, customer demographics, and competitive environment is essential for devising effective churn prediction strategies.Identifying common indicators such as usage patterns, billing history, and customer service interactions is crucial for predicting and preventing churn.Different customer segments may exhibit varying churn behaviors. Understanding these differences allows for targeted retention efforts and personalized marketing strategies tailored to specific customer groups.

Business stakeholders

The primary stakeholder in this project is SyrialTel, a telecommunications company based in Damascus, Syria. Their core interest lies in understanding the patterns and reasons behind customer churn. SyrialTel can take proactive measures to retain customers by comprehensively understanding why customers leave. This includes improving service quality, enhancing customer support, and offering tailored solutions to address customer needs. By leveraging data-driven insights, SyrialTel can make informed decisions, tailor services, and allocate resources effectively to reduce churn. This proactive approach not only improves customer satisfaction but also improves customer satisfaction and leads to financial savings by minimizing revenue loss associated with customers discontinuing their services.

Objectives

- The primary objectives of this project are as follows:

- To Build a classification model to predict customer churn for SyriaTel.

- To Identify the key factors influencing customer churn.

- To Provide insights and recommendations to SyriaTel for effective churn management.

Project Methodology

The CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology is a widely used framework for data mining projects, and it can be effectively applied to customer churn analysis. The methodology consists of six phases: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment.
The processes to be undertaken in this project are:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis
- Data Preparation
- Modelling
- Evaluation
- Conclusion

  
Data Description 

The data utilized for this project has been sourced from Kaggle. The dataset contains 3333 entries and 21 columns, including information about the state, account length, area code, phone number, international plan, voice mail plan, number of voice mail messages, total day minutes, total day calls, total day charge, total evening minutes, total evening calls, total evening charge, total night minutes, total night calls, total night charge, total international minutes, total international calls, total international charge, customer service calls and churn.

Methodology

The project followed these steps:

Data Preprocessing 

Handled missing values, encoded categorical variables, and scaled numerical features.
Model Training and Evaluation: Used various classification algorithms to train and evaluate models.
Model Comparison: Compared models using metrics such as precision, recall, F1 score, accuracy, and ROC AUC score.
Final Model Selection: Selected the best-performing model for deployment.

Model Evaluation

Model	Precision	Recall	F1 Score	Accuracy	ROC AUC Score
Logistic Regression	0.683946	0.736937	0.709454	0.706140	0.786611
Tuned Decision Tree	0.856031	0.792793	0.823199	0.834211	0.896809
RandomForestClassifier	0.936920	0.909910	0.923218	0.926316	0.977545
Gradient Boosting	0.940325	0.936937	0.938628	0.940351	0.983907
K-Nearest Neighbour	0.782544	0.953153	0.859464	0.848246	0.940756

Final Model Selection

Gradient Boosting was chosen as the final model due to its superior performance across all evaluation metrics, particularly its high ROC AUC score of 0.983907, indicating excellent predictive capabilities.

Recommendations

- Focus retention strategies on high-usage customers and those with frequent customer service interactions. e.g. offering discounts and incentives.

- Investigate the low adoption of international and voice mail plans to understand customer needs and improve these offerings e.g. offering more affordable international plans, or making it easier for customers to sign up for international plans.

- Provide proactive support to customers making frequent customer service calls to improve their experience and satisfaction.

- Monitor and analyze usage patterns to detect early signs of potential churn and act accordingly.

Next steps

- Deploying the model: Implement the churn prediction model into the operational environment to start making real-time predictions on customer churn, enabling proactive retention strategies.

- Monitor and update the model: Continuously track the model's performance and accuracy over time, ensuring it remains effective in predicting churn, and regularly update it with new data to maintain relevance and accuracy.

- Interpreting the model insights: Analyze the model's predictions and identify the key factors influencing customer churn, providing valuable insights for targeted retention efforts and strategic decision-making.

- Collecting more diverse data: Expand the dataset by gathering a wider range of customer attributes, behaviors, and interactions to enhance the model's predictive capabilities and capture more nuanced patterns of churn behavior.
- To develop targeted retention strategies based on the insights gained from high
