# Salifort Motors: Predictive Model for Employee Turnover
Full Notebook Link: https://github.com/keithchhh/HR-Predictive-Modelling/blob/main/Final%20Analysis%20-%20HR%20Prediction_%20Salifort%20Motors.ipynb

**Objective:** Design a model that predicts whether an employee will leave the company based on their job title, department, number of projects, average monthly hours, and any other relevant data points. This is the Capstone Project for the Google Advanced Data Analytics Certificate.

**Key Findings:**
**XGBoost, Decision Trees, Random Forest, KNN and Logistic Regression** was used to predict employee turnover, with XGBoost resulting in a 96-98% accuracy.

<div align="center">
<img width="455" alt="image" src="https://github.com/keithchhh/HR-Predictive-Modelling/assets/145700071/5cc93d48-553b-4fb6-95b1-44f127029e92">
</div>
-

**Understanding Correlations and Feature Importance** was key to coming up with strategic recommendations to increase employee retention.

<img width="347" alt="image" src="https://github.com/keithchhh/HR-Predictive-Modelling/assets/145700071/00dfb69e-5d6c-4c21-a474-4d1b73cd2c2b">
<img width="443" alt="image" src="https://github.com/keithchhh/HR-Predictive-Modelling/assets/145700071/cbb1b1cd-a1f6-41ba-992f-48d83ffc22c5">

**The analysis was supplemented with investigation into relationships between variables**

<img width="434" alt="image" src="https://github.com/keithchhh/HR-Predictive-Modelling/assets/145700071/902c16df-6d24-4602-ae7f-4d802c8c5296">
<img width="358" alt="image" src="https://github.com/keithchhh/HR-Predictive-Modelling/assets/145700071/4b87de12-97e4-4d23-9f25-330b57095a2c">

These images show the satisfaction of employees drops when the projects taken exceed 5, and there is a signifcant drop in satisfaction for employees that have stayed for 4 years.

**Ultimately, 10 recommendations were given based on the significant contributing factors:**

**Time_spend_company :** Employees that have stayed for 4 years have very low satisfaction scores, resulting in a loss of experienced workers.

1. Launch an investigation into why employees that have stayed with Salifort for 4 years have very low satisfaction scores.
2. Reward employees that have stayed longer with the company with higher compensation / perks
Satisfaction_level: Employees with less than 0.5 indicated on the satisfaction survey are at a high risk of leaving the company.
3. Managers should reach out to employees that have high risk of turnover, constructively consult them on areas to improve satisfaction eg workload, training and development etc

**Number_of_project:** Employees that work more than 5 projects have a significant deterioration of work satisfaction

5. Limit the number of projects employees work on to a maximum of 5

**Average_monthly_hours:** Employees that exceed more than 250 hours a month have a high rate of turnover due to burnout or inadequate compensation.

6. To address overwork by employees, managers should re-evaluate project timelines and create a manageable working schedule for employees.
7. Managers can consider hiring more employees to prevent overwork current teams.
8. An investigation must be conducted on whether employeees are compensated fairly for overtime work
9. A working culture of reducing overtime work must be put in place to reduce pressure to outperform.

**Last_evaluation_score:** Higher evaluation scores are largely correlated to employees working longer hours at the company

9. Managers should evaluate processes that are tedious and take large amounts of time, and identify methods to remove inefficient procedures.
10. An investigation into the manager's evaluation process should be conducted, with the evaluation process focusing more on work outcomes and not on time spent on the task.

-
-
-
-


**PACE Framework (Plan - Analyze - Construct - Execute)**
## Planning
To address employee turnover at Salifort Motors, this notebook will build a model to predict whether an employee will leave or stay based on different data points.
**Objectives**
1. **Identify Key Factors:** Use statistical and machine learning techniques to identify the primary factors that contribute to employee turnover.
2. **Predict Employee Turnover:** Build and validate predictive model to determine likelihood of employee turnover.
3. **Develop Retention Strategies:** Formulate strategies to improve employee satisfaction and retention.
## Analyze
In the analyze stage, the features contributing to employee turnover will be explored in depth, conducting tasks not limited to:
1. Understanding Data for Accurate Predictions
2. Data Exploration and Structuring
3. Exploring Predictor Variables
4. Feature Engineering
## Construct
Using the features we have selected, the model predicting employee turnover can be constructed. This will include steps:
1. Constructing the classification model
2. Hyperparameter Tuning
3. Model Training
4. Cross-Validation
## Execute
Lastly, we will evaluate the model performance in the execute stage, fine-tuning necessary areas before reiterating the steps to construct a more accurate classification model.
