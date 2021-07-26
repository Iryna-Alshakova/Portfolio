# Car Price Prediction
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
[Scraping](https://github.com/Iryna-Alshakova/skillfactory_rsd/blob/main/module_6/Data%20Parsing.ipynb)    
[Data processing](https://github.com/Iryna-Alshakova/skillfactory_rsd/blob/main/module_6/Car%20price%20data.ipynb)  
[Choice of sklearn models](https://github.com/Iryna-Alshakova/skillfactory_rsd/blob/main/module_6/LazzyPredict.ipynb)  
[Prediction model](https://github.com/Iryna-Alshakova/skillfactory_rsd/blob/main/module_6/Prediction%20model.ipynb)

