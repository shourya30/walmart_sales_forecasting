# Time-Series Forecasting using ARIMA and Exponential Smoothing

## Problem Statement

Walmart, a leading retail corporation, operates 45 stores across various regions, each comprising multiple departments. They have provided weekly sales data for these departments, aiming to forecast department-wise sales per store. Throughout the year, Walmart conducts promotional markdown events, especially before major holidays like Christmas, Thanksgiving, Super Bowl, and Labor Day. Sales during these holiday weeks are weighted five times more in evaluations than non-holiday weeks. A challenge lies in modeling the impact of markdowns during these holidays, given the incomplete historical data.​

## Proposed Solution

The proposed system aims to address the challenge of predicting department-wise sales for each store on a weekly basis. This involves leveraging data
analytics and machine learning techniques to forecast demand patterns accurately. The solution will consist of the following components:

1. **Data Collection**
- Gather historical data on department-wise sales, including time, date, location, and other relevant factors.
- Utilize real-time data sources, such as events, and holidays, to enhance prediction accuracy.

2. **Data Preprocessing**
- Clean and preprocess the collected data to handle missing values, outliers, and inconsistencies.
- Feature engineering to extract relevant features from the data that might impact bike demand.

3. **Machine Learning Algorithm**
- Implement a machine learning algorithm, such as a time-series forecasting model , ARIMA, to predict weekly sales based on historical patterns.
- Consider incorporating other factors like month of the year, day of the week, and special events to improve prediction accuracy.

4. **Deployment**
- Develop a user-friendly interface or application that provides real-time predictions for weekly sales at different dates..
- Deploy the solution on a scalable and reliable platform, considering factors like server infrastructure, response time, and user accessibility.

5. **Evaluation**
- Assess the model's performance using appropriate metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), or other relevant
metrics.
- Fine-tune the model based on feedback and continuous monitoring of prediction accuracy.
  
## Conclusion

- In conclusion, some departments has higher sales, on average others can be best. It shows us, some departments has effect on sales on some seasons like Thanksgiving.
- It is same for stores, means that some areas has higher seasonal sales.
- Stores has 3 types as A, B and C according to their sizes. Almost half of the stores are bigger than 150000 and categorized as A. According to type, sales of the stores are changing.
- As expected, holiday average sales are higher than normal dates.
- Top 4 sales belongs to Christmas, Thanksgiving and Black Friday times. Interestingly, 22th week of the year is the 5th best sales. It is end of May and the time when schools are closed.
- Christmas holiday introduces as the last days of the year. But people generally shop at 51th week. So, when we look at the total sales of holidays, Thanksgiving has higher sales between them which was assigned by Walmart. But, when we look at the data we can understand it is not a good idea to assign Christmas sales in data to last days of the year. It must assign 51th week.
- January sales are significantly less than other months. This is the result of November and December high sales. After two high sales month, people prefer to pay less on January.
- CPI, temperature, unemployment rate and fuel price have no pattern on weekly sales.
