# Swire-CC-Innovative-Product-Demand-Forecasting

### Introduction & Business Problem
Launching limited edition products is crucial for beverage companies such as Swire to drive revenue growth, diversify the product portfolio, attract broader consumer categories, strengthen brand visibility and loyalty. These products will also cater to recent trends over prioritizing health and sustainability. Overall, product innovation is critical for staying relevant in a dynamic market, ultimately boosting revenue and sustaining long-term growth. Swire Coca-Cola is constantly introducing innovation products into the market but faces a challenge in optimizing production planning and inventory management. The company aims to accurately forecast the demand, identify the most profitable region and time periods for launching their planned limited edition products, using historical sales and market data of similar products along with customer demographic information to strike a balance between both out-of-stock and overproduction situations. 

### Project Goal & Solution Approach
There are 7 limited edition products that Swire plans to release in the near future and the goals of this project is to not only accurately forecast demand, time period of the year and best regions to launch these products but also justify the results. 

Below is the step by step approach:

1. Match and map the 7 innovative products provided by Swire with the historical data.
2. Depending on the product specifications and requirements, identify the best region, time period and the forecasted demand.
3. Use time series forecasting methods such as ARIMA, SARIMA and Prophet to forecast demand.
4. Split the data into train-test for model evaluation to justify the models used and results obtained.
5. Measure the model performance using error metrics like MAE, MAPE & RMSE by comparing the estimated demand with the actual values for the train and test sets.
6. Use the model to forecast demand, time period or region.

To solve the problem, various forecasting techniques including SARIMA, FB Prophet, and exponential smoothing were emplpyed to predict sales demand. Additionally, social media analytics and overage underage analysis was leveraged to gauge public perception of new flavors post-launch and provide a estimate of potential monetary loss due to Overage and opportunity loss due to underage.

### Contribution
I contributed in all aspects of the project starting with the business problem statement, null value analysis and data exploration, modeling with interpretations and visualizations and drafting the theoretical parts of the project. Additionally, I took the responsibility for assessing the business value proposition of underage and overage costs and integrated social media analytics into our analysis.

### Business Value
Our solution provides Swire with accurate forecasts, best time periods and regions to launch for the 7 products. Additionally, we went a step ahead and have provided the costs associated with all the possible worst case scenarios to facilitate decision making based on the risk appetite. Actionable insights to reduce overage and underage situations and strategy to leverage consumer opinions post launch have also been demonstrated. 

### Challenges & Limitations
Being a real world problem, one of the primary challenges throughout the project was the absence of real or observed values with the exact product attributes. The results would be questionable in such cases, but we have utilized techniques such as cross validation and train-test splits to validate the model and only then use the model for forecasting. 

Post product launch, relying on forecasts might not be accurate as demand in those stages would depend on consumer sentiment and perception of the product rather than model generated forecast that is dependent on past data. Moreover, consumer taste and health preferences changes with time and relying solely on forecasts from historic data is not a good idea. To overcome this challenge, we have advocated the need for using social media data especially post product launch and recalibrate forecasts. 

External factors beyond product and demographic attributes can potentially impact sales. For instance, for the closest matched product that was used for forecasts, if in the future Swire happens to have better marketing strategies and appealing packaging, this can shoot up sales much beyond the estimated sales.

### Takeaways and Lessons Learnt
This project provided valuable insights into the complexities and uncertainities of sales forecasting in the beverage industry. Having to work with limited edition products gave us an opportunity to extensively focus on data preparation and pre modelling analysis which generally is the case in real world analytics use cases. We learnt that based on the data being used, best model often changes and hence it is critical to always use multiple models to compare and interpret forecasts. Moreover, continuous adaptation to evolving market trends and need for integrating external data sources such as social media analytics enhanced the robustness of our forecasting models and is a vital lesson.
