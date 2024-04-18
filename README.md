# Swire-CC-Innovative-Product-Demand-Forecasting

### Introduction & Business Problem
Launching innovative products is crucial for beverage companies such as Swire to drive revenue growth, diversify the product portfolio, attract broader consumer categories, and strengthen brand visibility and loyalty. These products will also cater to recent trends over prioritizing health and sustainability. Innovative products also boosts profit as these are offered at premium pricing. Overall, product innovation is critical for staying relevant in a dynamic market, ultimately boosting revenue and sustaining long-term growth. Swire Coca-Cola is constantly introducing innovation products into the market. Swire Coca-Cola faces a business challenge in optimizing production planning and inventory management for its innovative beverage segment. The company aims to accurately forecast the demand, identify the most profitable region and time periods for launching their planned new products, using historical sales and market data of similar products along with customer demographic information to strike a balance between both out-of-stock and overproduction situations. 

### Project Goal & Solution Approach
The goals of this project are as follows:

Match and map the 7 innovative products provided by Swire with the historical data.
Depending on the question, identify the best region, time period and the forecasted demand.
Use time series forecasting methods such as ARIMA, SARIMA and Prophet to forecast demand.
Split the data into train-test for model evaluation to justify the models used and results obtained.
Measure the model performance using error metrics like MAE, MAPE & RMSE by comparing the estimated demand with the actual values for the train and test sets.
Use the model to forecast demand, time period or region.

To solve the problem employed various forecasting techniques, including SARIMA, FB Prophet, and exponential smoothing, to predict sales demand. Additionally, we leveraged social media analytics to gauge public perception of new flavors post-launch.

### Contribution
My contribution involved framing the business problem statement, modeling with interpretations and visualizations, utilizing the Prophet model, drafting the introduction section, and performing data preparation. I also conducted analysis with interpretations, introduced project objectives, described the data, addressed missing values, and provided modeling insights. Additionally, I contributed to assessing the business value proposition of underage and overage costs and explored the integration of social media analytics.

### Business Value
Our solution provides Swire with actionable insights to reduce overage and underage situations. We have provided Swire with the costs associated with these two worst case scenarios which will help Swire in decision making based on risk appetite. Also, by integrating social media analytics, Swire gains a deeper understanding of consumer preferences and can adjust production based on consumer sentiment towards the product.

### Challenges
Being a real world problem, one of the primary challenges throughout the project was the absence of real or observed values for the product with exact product attribute. The results would be questionable, but we have utilized techniques like cross validation and train-test splits to validate the model and only then use the model for forecasting. Also, post product launch, relying on forecasts might not be accurate as demand in those stages would depend on consumer sentiment and perception of the product. Moreover, consumer taste and health preferences changes with time and relying solely on forecasts from historic data is not a good idea. To overcome this challenge, we have advocate for leveraging social media analytics post product launch and recalibrate forecasts. 

### Lessons Learned
This project provided valuable insights into the complexities of sales forecasting in the beverage industry. We learned the importance of flexibility in modeling techniques and the need for continuous adaptation to evolving market trends. Additionally, integrating external data sources such as social media analytics enhanced the robustness of our forecasting models.
