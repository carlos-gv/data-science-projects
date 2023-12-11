
# Energy Consumption Forecasting

In this proyect we re going to use a machine learning algorithm for an implementation of a gradient-boosting decision trees, XGBoost. Along with the ML algorithm, we use a time series cross validation tecnique to make a more reliable model. In the end, we created a model that can predict one year in the future, and save it so it can be used in other pc.


### Implementation

1. Preprosseing the data.
2. Create a model with a manually split training data.
3. Use a cross validation tecnique to get better results out of the training of the model.
4. Predict one year in the future for the given data set
5. Save the model in a json file so it can be imported and used right away.


### Conclusion
After training our model and forecasting for one year in the future, we compared the forecasted data vs the data we already have for a year interval. We found a similar behaviour, as expected. This data set clearly followed a seasonal pattern, and our model was able to predict it in a good maner. Although more features can be added to have more precise predictions, to a first approach, our implementation gave very good results.


## Features

- Use of XGBoost algorithm.
- Use of cross validation techniques.
- Make the model easily available to reuse.


**Tecnologies used:** Python, Pandas, scikit-learn, Seaborn, NumPy, Matplotlib, Time Series Split
