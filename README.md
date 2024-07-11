# Churn Analysis
 
# Introduction.

This project demonstrates a comprehensive analysis of customer churn of a telecom company using SQL and PowerBI and forecasting churn of new customers using machine learning techniques. The primary objectives were to identify factors influencing churn, build predictive models, and derive actionable insights. Key steps included data preprocessing, feature engineering, model selection, and evaluation. The project also emphasizes the importance of clear data visualization to communicate findings effectively. Tools and technologies used include Python, pandas, scikit-learn, and various visualization libraries.

# Data Sources and Preparation:

Utilized large datasets from various sources.  
EDA on the dataset to get familiar with the data.  
Performed extensive data cleaning and preprocessing to ensure accuracy and consistency.  
Engineered features for adequate analysis.  


# Methodology:
Cleaned the data using SQL.  
Built an extensive PowerBI dashboard for visualization of trends.  
Applied machine learning models for predictive analytics.
Conducted feature engineering to derive meaningful predictors of churn.
Used statistical techniques to validate model performance.
# Key Findings:
Identified critical factors influencing customer churn, including service quality, pricing, and customer engagement.
Demography: 
Imbalanced class in gender, with over 64% of the churned customer base being female.
Customers Aged 50 and older are more likely to churn and look for alternative service.  

Services:  
Perhaps the most important indicator of churning is the contract type. 
Customers that have spent around 12-18 months are least likely to churn.  
Month to month contract has a churn rate of 46.5%, more  than four times the rate of the second closest contrac type (one year contract).  
Customers that subscribe to Fibre Optics are more likely to churn compared to other internet type subscriptions.  
Subscriptions to services like internet, unlimited data, phone and paperless billing leads to a disproportionate amount of churn rate, with all being over 74%.  


Churn Reasons:  
Majority of churned customers went to a competitor becasue of better service.

![Summary](https://github.com/Tomi-unh/Churn-Analysis/assets/60202873/2977143f-388d-4ed9-a966-974f0bec8fb2)


# Forecast:
Developed predictive models with high accuracy, allowing for proactive churn management.  
Current forecast shows that month to month contract customers are most likely to churn with 352 of the predicted 364 churners being on month to month.  
Marriage status has no significant impact of churn rate.  

![predictions](https://github.com/Tomi-unh/Churn-Analysis/assets/60202873/24e8df88-5311-40f7-bbe2-bce0ec6a11eb)


# Recommendations:

Focus on improving service quality and customer engagement to reduce churn.
Implement targeted retention strategies at month to month customers to commit to a yearly contract.  
Targeted marketing at younger customers (less than 20 years old), as they are least likely to churn. 
17% of Customers who subscribe to premium support churn, as opposed to 83% of customers that don't, indicating the effectiveness of an adequate customer service. Offer the premium support to every customer free of charge.


# Tools and Technologies:
Python, pandas, scikit-learn for data analysis and modeling.  
PowerBI for presenting findings.  
