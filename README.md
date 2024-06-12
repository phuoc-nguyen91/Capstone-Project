# Salifort Motors Employee Satisfaction and Retention Enhancement Project

## Project Overview

Salifort Motors' HR department is dedicated to improving employee satisfaction and retention. Leveraging a wealth of employee data, this project aims to provide data-driven suggestions to answer a crucial question: "What factors are likely to drive employees to leave the company?"

## Project Objectives

This project has two primary objectives:

1. **Data Analysis**: We will thoroughly explore the HR dataset, uncovering insights into the factors influencing employee attrition. By gaining a deep understanding of the data, we can provide valuable data-driven recommendations.

2. **Predictive Modeling**: To proactively manage employee retention, we will build a predictive model capable of assessing the likelihood of an employee leaving the company. This model will help identify key contributing factors for improvement.

## Why It Matters

Employee retention is a pivotal concern for organizations due to the substantial costs associated with recruitment, training, and onboarding of new employees. Enhancing employee satisfaction and reducing attrition can significantly impact a company's bottom line.

Throughout this project, we will employ data-driven approaches to assist Salifort Motors in making informed decisions that promote both employee well-being and organizational success.

## Project Planning: Key Considerations

### Stakeholders

Our primary stakeholders are Salifort Motors' HR department, seeking data-driven insights to enhance employee satisfaction and retention.

### Project Objectives

We aim to:

- Understand factors influencing employee attrition.
- Build a predictive model for employee retention.
- Provide actionable recommendations to enhance retention.

### Resources Used

- Dataset: https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv
- Data analytics tools (e.g., Python, Jupyter Notebook)
- Data visualization libraries (e.g., Matplotlib, Seaborn)
- Machine learning libraries (e.g., Scikit-Learn)

### Ethical Considerations

Handling employee data requires upholding privacy and data security standards. Anonymizing and protecting sensitive information is paramount. We'll ensure our analysis and recommendations are fair and non-discriminatory.

## Execution Stage

### Summary of Model Results

In our model evaluation, we observed notable results:

- **Logistic Regression**: Delivered respectable performance on the test set with an accuracy around 80% to 83%. However, performance in predicting employees who left was not as impressive.

- **Tree-based Machine Learning**: After feature engineering, our decision tree model exhibited promising results, with an AUC score of 95.87% and strong precision, recall, and f1-score.

- **Random Forest**: Outperformed other models with an impressive accuracy of 96.2% and a strong AUC score of 94%. This model excelled in identifying employees at risk of attrition.

## Additional Information

For more extensive information, detailed analysis, and comprehensive explanations, please refer to the accompanying Jupyter Notebook (`Capstone Project - Employee churn.ipynb`) provided in this repository.

This Jupyter Notebook contains in-depth explorations, code walkthroughs, visualizations, and further insights into the project. It serves as a valuable resource for those seeking a deeper understanding of the data, analysis, and methodologies used in this project.
