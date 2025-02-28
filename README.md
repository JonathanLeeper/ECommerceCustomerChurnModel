# CustomerChurnPredictionModel
This project aims to predict customer churn in an e-commerce business using machine learning techniques. By analyzing customer behavior and transaction data, we will build a model that identifies customers at risk of leaving, allowing retention strategies to be put into place if need be. After my first two projects for this final course, I felt it was necessary to dig deeper into data science as a whole and put myself in a realm where I have not completed a project in a similar vein before.
## Business Problem
Customer churn is a large issue in the e-commerce industry, as retaining customers is more cost-effective than acquiring new ones. This project seeks to answer a few questions with a business approach. What factors contribute most to customer churn, & how can businesses use this information to improve customer retention?
By addressing these questions, businesses can proactively target at-risk customers with personalized incentives and marketing strategies.
## Background/History
Customer churn prediction has long been a focal point in industries like telecommunications, banking, and retail. With the rise in e-commerce, businesses now face intense competition, making customer loyalty harder to maintain. Predictive analytics and machine learning have become essential tools in identifying churn by analyzing historical customer data, purchasing behaviors, and engagement patterns. By leveraging historical data, businesses can implement proactive strategies.
## Data Explanation
For this data, we will be using the Ecommerce Customer Churn Analysis dataset created by Ankit Verma from Kaggle. Within this data, we have customer demographics, transaction history, engagement metrics, and churn status. Using this dataset, I plan to clean the data, encode the data into variables, & importing data into models.
## Methods
For the methods used within this dataset, we will be focusing on exploratory data analysis at first glance, while then implementing different machine learning models with model evaluation to determine the trends, outliers, and correlations within the data. Logistic regression, decision tree, and random forest models will be important throughout this data, as well as accuracy, recall, and F1-Score for our model evaluation.
## Analysis
The EDA will uncover important trends, such as the impact of cashback offers on retention or how complaints affect churn. Machine learning models will then be trained to predict churn, with feature importance analysis highlighting which factors contribute most to customer departures.
Within the three models selected, we were able to determine the outcomes of each of the models, and which would be the strongest for the the dataset in question. Using our confusion matrix and classification reports, we were able to determine that logistic regression was not strong in regards to recall, but decision tree and random forest were strong and could be strengthened using fine-tuning.
 
## Conclusion
Through this project, we aim to provide actionable insights into customer churn patterns within e-commerce. By understanding the key drivers behind churn and effectively predicting at-risk customers, businesses can implement data-driven strategies to improve retention. As we determined that random forest and decision tree were stronger models, it was then meant to fine-tune them, which we did using hyperparameters and GridSearchCV to determine the best models for our dataset.
## Assumptions
The dataset accurately represents real-world customer behavior, churn is defined consistently across the dataset, & external factors are not influencing customer behavior in a way not captured by the dataset.
## Limitations
One limitation that is a part of this data that may skew results is data imbalance, as churned customers are likely underrepresented, potentially skewing model performance. This is due to the fact that the dataset had less churned customers than non-churned.

## Challenges
For the challenges within this model, it will prove difficult to find the most predictive variables without overfitting, interpreting the model and its results, and ensuring privacy if this model were expanded to a dataset using customer information.
When using this model in its finality, we were able to accurately predict the goals and where we could expand our models, and after fine-tuning, we came away with better numbers for each of the models.
 
## Future Uses/Additional Applications
There are many ways that this can be implemented for future uses and additional applications used from this model:
•	Personalized Marketing: Use predictive insights to tailor marketing campaigns.
•	Customer Segmentation: Group customers based on churn risk and behavior patterns.
•	Product Recommendations: Suggest products that align with loyal customers’ preferences.

## Ethical Assessment
For the ethical assessment of this model, it is important to mitigate bias throughout the data, showcase correct privacy compliance using this data, and ensure transparency with potential stakeholders and those that are necessary to know this information.
It is also important to know that within this project, random forest was the chosen model for finality and plugging in – this is due to the fact that it had 99% precision on correctly determining churned customers, which would in turn create a better way to determine if those customers were to churn and could target our marketing and goals towards them.
