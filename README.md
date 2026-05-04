# CUSTOMER-CHURN-PREDICTION
**Overview**
Syriatel, a telecommunications company, faces a challenge of customer churn. Churn occurs when subscribers leave a service provider, which directly impacts the company's revenue and competitiveness. This project aims to build a machine learning classifier model to identify and predict customers who are likely to churn before they actually do. Such predictive ability allows SyriaTel to act proactively by applying preventive retention strategies-for example, offering targeted promotions, improving customer service, or addressing customer pain points promptly. The ultimate goal is to reduce customer churn, retain valuable customers and strengthen loyalty, which in turn improves customer satisfaction and helps SyriaTel maintain a stronger position in the telecommunications market.

**Business Understanding**

Customer churn poses a significant revenue-risk for SyriaTel and would want to reduce the churn by identifying the customers at risk early enough.There is need for a data-driven method to do the following:



**Business Objectives and Questions**

What is the estimated revenue at risk

Churn patterns

Which classification model can accurately be used to predict customer churn.

Which triggers are strongly associated with customer churn.

Practical Recommendations and insights from the analysis and model outcomes.

 **Data Understanding**

The dataset was from Kaggle. It provides an in-depth view of various aspects of customer behaviour and characteristics within SyriaTel, a telecommunications company. It contains subscriber demographics, service plans, usage patterns,billings charges and customer support interactions which are key indicators of customer churn and for building predictive models. 

The dataset contains 21 features (columns) and 3333 customer records(rows).

**Data Preparation**

Importing the necessary libraries
The main focus here is to ensure that the dataset is clean and reliable for further in-depth analysis. It entails checking for missing values, duplicates and outliers.

**Modeling  Approach**

The data-set was prepared for modelling by One Hot Encoding the Categorical features and scaling the numerical features. 
The data-set was then trained/ split with 70% of the data for training and 30% for testing.

We tested three models :

Logistic Regression - Simple Baseline Model
Decision Tree - Captures non- linear patterns
Random Forest - A robust model And reduces over-fitting.


**Decision Tree**

<img width="295" height="303" alt="image" src="https://github.com/user-attachments/assets/4bf97714-f442-4df8-b96c-6cbbf0e4ee5e" />


**ROC-AUC**

<img width="416" height="286" alt="image" src="https://github.com/user-attachments/assets/7ea85932-f8e9-42fe-8ada-3696a45fb50b" />

**Model Performance Comparison**

<img width="416" height="255" alt="image" src="https://github.com/user-attachments/assets/941ab8c5-cf53-40d0-8e0b-d3f168a68ff0" />




**Recommendations**

Feature Engineering: creation of new variables or combining the existing to improve prediction accuracy.
Hyperparameter Tuning : Use of optimization techniques  to fine tune model settings.
Feature Importance: Random Forest shows strong performance and clear interpretability. Key drivers -for example Customer service calls and International plan should be priorized in retention strategies.
Customer Retention Strategies: Direct interventions toward high-risk customers identified by all models.I.e service calls.

**Next Steps**

Expand the data-set to include demographics, tenure, service quality metrics
Balance churn vs non-churn data for non biased predictions.
Monitor model performance regularly
Scale deployment across regions.

