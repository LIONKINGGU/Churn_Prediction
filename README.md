
# PowerCo Customer Churn Prediction 
# Objective: Predict customer churn and identify key drivers.
# Data: Customer and price data from PowerCo.

# Key Findings: 
High churn rates in specific segments, impact of price changes.

# Exploratory Data Analysis:
Identified key statistics and distributions of features.
Most customers are relatively new, with a significant drop-off in customer numbers after 4-6 years.

# Feature Engineering Insights:
Customers with higher electricity consumption and longer tenure are less likely to churn.
Price increases, especially in off-peak hours, can trigger churn.

# Model Performance:
Achieved an accuracy of 89.98% with the RandomForestClassifier.
Key features influencing churn include margin gross power electricity and net margin.

# Correlation Analysis:
Weak correlation between price differences and churn, suggesting other factors are more significant drivers.
