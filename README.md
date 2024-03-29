# Healthcare Price Prediction Model
*****
## SUMMARY
This capstone project in one of the classes in my master program is about the prediction model related to the healthcare price. <br>
R code is available on the link [Code](https://github.com/joyinning/r_healthcare_price_prediction/blob/main/Healthcare_price_prediction_112022.md)
<br>
<br>
**1. Class Information and Duration** <br>
- Class Information: IST 687 Introduction to Data Science at Syracuse University (Fall 2022) <br>
- Duration: November ~ December 2022 <br>

**2. Goal** <br>
- To make the best prediction model on whether or not a healthcare cost of a customer will be expensive <br>
- To deliver the results with shiny apps website <br>
- To generate actionable insights for HMO on how to lower the cost of healthcare <br>

**3. Process (Based on the OESMN pipeline)** <br>
- Data Cleaning <br>
- Exploratory Data Analysis with Visualization <br>
- Data Modeling (Prediction) <br>

**4. Results** <br> 
The prediction model simulation in Shiny Apps [Link](https://haotianshen.shinyapps.io/FinalProj/?_ga=2.151311673.1694501232.1670083961-1568296780.1670083961) <br>
- This model contains the following predictors and machine learning algorithm. <br>
  - Predictors: age, bmi, smoker, exercise, expensive <br>
  - Algorithm: Decision Tree <br>
  - Accuracy: 96.84% <br>
  - Sensitivity: 98.11% <br>
- Note 1)The simulation require the train and test dataset as input. Find on the [Link]() <br>
- Note 2)The expensive predictor indicates whether or not the healthcare cost of each customer is expensive based on the boundary, $12,282. <br>

**5. Business Suggestions** <br> 
- Only certain factors are needed to build a model with great sensitivity, and therefore the cost for collecting and processing the less significant data could be saved. <br>
- Certain groups of people tend to be overcharged. Therefore, campaigns like smoking cessation programs (i.e. targeting smokers), regular yoga sessions (i.e. targeting less active group) could be initiated to promote healthy lifestyle. <Br>
- Differences among States have brought our attention to how income level, tax, and socioeconomics statues might affect health cost. Our suggestion is that a nationwide standard to be set for maximum cost in healthcare. <br>

*****
