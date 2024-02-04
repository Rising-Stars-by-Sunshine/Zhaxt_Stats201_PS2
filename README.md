# Predict Stocks in China Using Machine Learning
## The Prediction Problem
### Research Question Formulation

Objective: Stocks in China which is probably different from those in the USA such as S&P 500

Significance: This project aims at briefly understanding the stock market in China since it is widely regarded as "unpredictable". The research problem would be as follows:

  How precise can the prediction be provided only values?

  What frequency performs better in the regression model, daily or weekly?

### Operational Measures

Variables: Y - stock values; X - previous values

Data Type: Time-series

### Hypothesis Development

Prediction Hypothesis: Previous daily values will affect the next return. A daily frequency performs better.

Justification: It corresponds to the reality that people decide whether to buy the stock from recent data. And data with daily frequency usually convey more information than weekly one.

Machine Learning Algorithm Selection: Regression.


## The Machine Learning Workflow
### Model Development

Data Processing: Read the csv file downloaded from database, then pick out the open values of the index as y-variable day by day or week by week.

### Results Presentation

Training and Testing: Construct the parameters of the linear regression by taking previous values. Values of previous 21 days / 3 weeks / 21 weeks would be the X-variable data.

Visualization: Scatter plot of real values + Linear plot of prediction (both in one figure)

### Model Evaluation

Evaluation Criteria: Mean square error.

Iterative Improvement: More days / weeks to be considered.
