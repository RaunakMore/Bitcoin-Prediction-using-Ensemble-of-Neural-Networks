
INTRODUCTION:

The primary goal is address the challenge of prediction of volatile Bitcoin prices using deep learning models which is an open ended system. Accurate predictions of these prices can lead better planning for investors, buyers and financial analysts. Usage of an Ensemble of Neural Networks for prediction of Bitcoin Amount using Historical Data Comparing it to Naïve forecast which forms as baseline for performance comparison of the neural networks Core idea behind usage of Neural Network for creation of ensemble model is that we use 3 different loss function mae, mse and mape to generate sequential models with 2 dense layers with 128 neurons each. Since the initial weight assignment is random we can get better confidence levels when looking at predictions as we take the median of these models.

CONCLUSION:

Naïve Forecast
This forms as our baseline model to compare performance of ensemble model to.
As this model works by assigning predicted value to previously known value the forecast results are pretty accurate with a sort of lag in predicted curve.
So while mean Bitcoin value is 35526$, and average prediciton is off by 763$(MAE) we can say the prediction is good enough

Ensemble Forecast	
For predictions using this model , we go with 95% confidence prediction interval by plotting a range of bitcoin amount rather than 1 value.
We do this by multiplying the value predicted by 1.96 as its seen 95% values fall under 1.96 standard deviations of the mean then adding and substracting it from the predictied value to get a upper and lower boundary value
