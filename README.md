# Myntra Customer Analysis

## Objective

The objective of this analysis is to explore the MyntraCustomerData.csv dataset and provide actionable insights to optimize sales channels and increase profitability.

## Dataset Overview

The dataset contains customer information and numerical value columns, including:

- Avg_Session_Length: Average session of in-store style advice sessions.
- Time_on_App: Average time spent on the mobile app in minutes.
- Time_on_Website: Average time spent on the website in minutes.
- Length_of_Membership: Number of years the customer has been a member.
- Yearly_Amount_Spent: Amount spent in thousand dollars in a year.

## Exploratory Data Analysis

### Correlation Analysis

- A jointplot was created to compare the Time on Website and Yearly Amount Spent columns, revealing a moderate correlation.
- Another jointplot was generated for the Time on App and Yearly Amount Spent columns, indicating a stronger correlation compared to the website.
- A pairplot was utilized to explore relationships across the entire dataset.

### Linear Relationship Analysis

- A linear relationship was fitted between Length of Membership and Yearly Amount Spent, showing a positive correlation.

## Training and Testing Data

The data was split into training and testing sets, with numerical features assigned to X and the target variable (Yearly Amount Spent) to y. The split was performed using a test size of 30%.

## Model Training

A Linear Regression model was trained on the training data to predict the Yearly Amount Spent based on customer features.

## Model Evaluation

The model performance was evaluated using Root Mean Squared Error (RMSE), which was calculated to be 10.57.

## Residual Analysis

A histogram of the residuals was plotted, indicating a normal distribution.

## Recommendations

Based on the analysis conducted, here are actionable recommendations for optimizing sales channels and increasing profitability:

1. **Focus on Mobile App Optimization**: Prioritize optimizing the mobile app user experience to capitalize on its strong positive correlation with the yearly amount spent.

2. **Invest in Customer Retention**: Implement strategies to retain existing customers and encourage membership renewals, as length of membership has the highest positive impact on yearly amount spent.

3. **Continuous Monitoring and Analysis**: Regularly monitor customer behavior metrics and conduct frequent analyses to adapt strategies according to changing customer preferences.

4. **Explore Cross-Channel Integration**: Maintain a cohesive omnichannel experience by integrating the mobile app and website to provide a seamless customer journey.

5. **Test and Iterate**: Implement systematic testing of new strategies and features, such as A/B testing, to refine the customer experience and maximize conversion rates.

By implementing these recommendations, the company can leverage customer data insights to optimize sales channels, enhance customer satisfaction, and drive increased profitability over time.


## Contact
Name: **Jay Dilip Varma**  
Email: jay01varma@gmail.com  
LinkedIN: [jay01varma](https://www.linkedin.com/in/connect-wtih-jay-varma/)
