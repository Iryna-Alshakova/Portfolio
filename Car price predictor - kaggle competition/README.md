# Car Price Prediction
*Link: https://www.kaggle.com/c/sf-dst-car-price-prediction/overview*  
### *Task*: build a model that predicts the value of a car based on its characteristics

### Description:
Imagine that you work for a company that sells used cars. The main task of the company and its managers is to find profitable offers as quickly as possible (in other words, buy below the market, and sell above the market).

You are tasked with creating a model that will predict the value of a car based on its characteristics.
If our model works well, then we can quickly identify great deals (when the desired seller price is below the predicted market price). This will significantly speed up the work of managers and increase the company's profits.

### Solution
A dataset with various characteristics of vehicles without prices was provided. Prices had to be predicted using the generated model.
The accuracy of the model was evaluated with the MAPE metric.

The training dataset was derived from the auto.ru website. The data for the cars of only those brands that were present in the testing dataset was collected.

The collected data has been cleared. Additional features have been generated.

When searching for a predictive model, sklearn models, which were determined as the most optimal using Lazy Predict, as well as CatBoostRegressor were tested.

### Content
[Scraping](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Car%20price%20predictor%20-%20kaggle%20competition/Data%20Scraping.ipynb)    
[Data processing](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Car%20price%20predictor%20-%20kaggle%20competition/Car%20price%20data.ipynb)  
[Choice of sklearn models](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Car%20price%20predictor%20-%20kaggle%20competition/LazzyPredict.ipynb)  
[Prediction model](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Car%20price%20predictor%20-%20kaggle%20competition/Prediction%20model.ipynb)



# Car Price Prediction (Part 2)
*Link: https://www.kaggle.com/c/sf-dst-car-price-prediction-part2* 

### Solution
The model included both machine learning algorithm (*CatBoostRegressor*) and neural networks (*NLP* and *CV*).
Text of the car description was preprocessed with the application of lemmatization and removing stop-words.
Augmentation was applied when images were processed.
Final results were obtained by blending the results of CatBoostRegressor and neural network.

Additionally, a neural network with skip connections was tested. That model has proven to converge much faster compared to the original, although accuracy was somewhat lower.

[Model with NN](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Car%20price%20predictor%20-%20kaggle%20competition/car_price_predictor_2.ipynb)

