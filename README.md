# Business Understanding

### Problem Statement
The telecommunications company is facing challenges with customer retention and churn. The company's data analytics team is tasked with building a machine learning model to analyze churn trends. The objective is to identify the factors that influence customers to either remain loyal or leave the service.

### Goal and Objectives
#### Goal:
To determine the aspects of the telecommunications company's service that contribute to customer churn and develop strategies to improve customer retention.

#### Objectives:
Analyze customer data to identify patterns and factors associated with churn.
Build a robust machine learning model to predict customer churn.
Provide actionable insights to the company's management to enhance service delivery and customer satisfaction.

#### Stakeholders
##### Executive Board:
Makes strategic decisions based on insights from the churn analysis.
##### Board of Directors:
Oversees the overall performance and strategic direction of the company.
##### Senior Management:
Responsible for service delivery and ensuring financial performance.

#### Key Metrics and Success Criteria
##### Churn Rate:
Percentage of customers who leave the service within a specific period.
##### Model Accuracy:
The percentage of correct predictions made by the machine learning model.
##### Precision and Recall:
Metrics to evaluate the performance of the churn prediction model.
##### Customer Lifetime Value (CLV): 
Measure of the total value a customer brings to the company over their entire relationship.

#### Success Criteria:
Achieving a high accuracy, precision, and recall in the churn prediction model.
Providing actionable insights that lead to a measurable decrease in churn rate.
Enhancing customer satisfaction and retention through targeted interventions based on model predictions.

#### Hypotheses
##### Hypothesis 1:
Null Hypothesis: The total charges or monthly charges incurred by a customer have a direct effect on the churn rate.
Alternate Hypothesis: The total or monthly charges incurred by a customer have no direct effect on the churn rate.

##### Hypothesis 2:
Null Hypothesis: Customers on month-to-month subscriptions are more likely to churn compared to those on annual subscriptions.
Alternate Hypothesis: Customers on month-to-month subscriptions are less likely to churn compared to those on annual subscriptions.

#### Analytical Questions
Demographics:
What is the distribution of age, gender, relationship status, and dependents among customers who churn versus those who do not?
Are there specific demographic segments with significantly higher churn rates?

Usage Patterns:
How does feature usage correlate with churn? Are there specific features whose usage (or lack thereof) is predictive of churn?
Which streaming service is most preferred among the customers – streaming movies or TV shows? Do the streaming habits of customers affect customer retention or churn?

#### Scope and Constraints
##### Scope:
The project will use three datasets for training, evaluating, and testing the machine learning model.
Focus on classification models to predict customer churn and identify key factors influencing retention.
##### Constraints:
Limited to the data provided by the company (first 3000 records in a database, second 2000 records in a CSV file, and final 2000 records in an Excel file).
Read-only access to the database.
