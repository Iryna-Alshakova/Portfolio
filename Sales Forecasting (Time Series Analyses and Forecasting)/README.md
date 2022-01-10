# Sales Forecasting

### Data Description:
Initial sales data can be downloaded from https://drive.google.com/file/d/1DC0P2h4pQcOursxYOXWqwg54ayX83uFD/view?usp=sharing.  
Herein all sales were [summarized by date](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Sales%20Forecasting%20(Time%20Series%20Analyses%20and%20Forecasting)/Processed%20Dataset.ipynb) and saved as a [all_sales.csv](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Sales%20Forecasting%20(Time%20Series%20Analyses%20and%20Forecasting)/all_sales.csv).   
We also used [holidays information](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Sales%20Forecasting%20(Time%20Series%20Analyses%20and%20Forecasting)/holidays_events.csv) in our model. 

### Solution:
Two approaches were studied:
1) [FPProphet](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Sales%20Forecasting%20(Time%20Series%20Analyses%20and%20Forecasting)/Sales%20Forecasting%20-%20FPProphet.ipynb)
2) [Gradient Boosting](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Sales%20Forecasting%20(Time%20Series%20Analyses%20and%20Forecasting)/Sales%20Forecasting%20-%20gradient%20boosting.ipynb) (XGBoost, CatBoost)

### The best results:
*Model:* FPProphet.Prophet    
*Mean absolute percentage error:* 20.8%

*Model:* XGBoost    
*Mean absolute percentage error:* 18.4%
