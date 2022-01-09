# Anomaly Detection

### *Task*: Study an influence of advertising for Ahmad tea in the TV show “What? Where? When?" on its sales.

### Data Description:
Sales data for three tea brands over the period form 2016-07-01 to 2016-11-30 is collected in the [file](https://github.com/Iryna-Alshakova/Portfolio/blob/main/Anomaly%20Detection/tea_demand.csv).  


*Brand id:*
* lipton — 29;
* ahmad — 178; 
* may — 5152.

### Solution:
1. Data scraping was performed for the TV-show release dates over the period form 2016-07-01 to 2016-11-30.   
2. The interquartile range for the number of sales was calculated, abnormally high values were assigned based on it. The influence of the advertising on the sales increase was estimated based on obtained data.
3. DBSCAN was applied in attempt to isolate abnormal values.
4. The SARIMAX model for predicting sales numbers after the TV-show broadcast was build. Predictions were compared to the actual data.
