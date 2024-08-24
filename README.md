# S-Mobile-Predicting-Customer-Churn

### Project Description:
In this project, I was tasked with predicting customer churn for S-Mobile, a leading cellphone carrier in Singapore. The primary goal was to develop a predictive model that could identify customers at risk of churning before they made any attempts to leave, allowing the company to implement proactive retention strategies. This project involved analyzing customer data, building machine learning models, and proposing actionable insights to reduce churn.

### Technology Stack:
- **Data Handling and Scripting**: Python, pandas, pyrsm
- **Machine Learning Models**: Logistic Regression, XGBoost, Random Forest, Neural Networks
- **Visualization and Evaluation**: Matplotlib, Partial Dependence Plots (PDP), Permutation Importance

### Key Accomplishments:

#### Data Integration and Preparation:
- **Data Loading**: Imported and processed a dataset containing 1 million rows and 25 variables describing customer characteristics and behavior.
- **Data Exploration**: Conducted exploratory data analysis (EDA) to understand the distribution of variables, focusing on key features like revenue, minutes of use, and customer service interactions.

#### Model Development and Analysis:
- **Logistic Regression**: Built and evaluated a logistic regression model as a baseline for predicting customer churn. Used the model to understand the relationship between explanatory variables and churn.
- **XGBoost Model**: Developed an XGBoost model, which demonstrated superior performance in predicting churn with an AUC score of 0.761 on the test set. The model was selected as the final predictive model due to its robustness and accuracy.
- **Random Forest and Neural Networks**: Experimented with Random Forest and Neural Networks as alternative models. The Random Forest model achieved an AUC score of 0.737, while the Neural Network model scored 0.719, both showing potential but not outperforming XGBoost.

#### Key Drivers of Churn:
- **Variable Importance**: Identified key drivers of churn using Permutation Importance and PDPs. Significant factors included:
  - **Equipment Usage Time (eqpdays)**: Customers with older handsets were more likely to churn.
  - **Months of Service (months)**: Newer customers had a higher churn risk.
  - **Overage Usage (overage)**: High overage minutes indicated dissatisfaction with current plans.
  - **Revenue**: Very low revenue customers exhibited higher churn rates.
  - **Customer Service Interactions (retcalls)**: Frequent retention calls were a strong indicator of churn.

#### Actionable Insights and Interventions:
- **Upgrade Incentives**: Proposed offering handset upgrades to customers with older devices to reduce churn.
- **Customized Plans**: Suggested developing personalized plans for customers frequently exceeding their usage limits.
- **Enhanced Customer Service**: Recommended improving customer service quality for those with frequent retention calls to increase satisfaction.
- **Occupation-Based Services**: Proposed tailored service offerings based on customer occupation to enhance relevance and engagement.

#### Economic Impact Analysis:
- **Customer Lifetime Value (CLV)**: Quantified the economic impact of proposed interventions using CLV analysis over a 5-year period.
  - **Retention Calls**: Implementing service improvements for customers with high retention call rates could increase CLV significantly.
  - **Handset Upgrades**: Offering upgrades to customers with older handsets demonstrated a substantial positive impact on CLV.
  - **Overage Management**: Customizing plans for customers with high overage usage resulted in increased CLV, reflecting better alignment of services with customer needs.

### Key Outcomes:
- **Improved Predictive Accuracy**: The XGBoost model provided a reliable and accurate prediction of customer churn, allowing for more effective targeting of retention strategies.
- **Actionable Business Insights**: The analysis identified critical factors influencing churn, enabling the development of targeted interventions to reduce churn and enhance customer loyalty.
- **Economic Viability**: CLV analysis confirmed the financial benefits of the proposed actions, supporting their implementation as part of S-Mobile’s proactive churn management strategy.
