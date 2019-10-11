# Time-Series-of-Price-Anomaly-Detection-Using-Auto-Encoders
Simple auto encoder code for detection the Anomaly for a hotel price detection using the Expedia data set from kaggle competition 
## Model  ##
Auto encoder <br>
Auto encoder is trained with the normal data set .Here the input and output for the model is same for the auto encoder <br>
Once the model is trained we will test the model with the normal test set and Anomaly test set <br>

## Anomaly ## 

![image](https://user-images.githubusercontent.com/25486846/66674665-0e586880-ec29-11e9-957c-eddc5efd1e6a.png) <br>
Anomaly are selected based on theanomalies will be outside the interval mean - 3 * Standard deviation and mean + 3 * Standard deviation <br>
## Data ## 
Here Data is extracted from the expedia dataset only one hotel is selected and that too USA location. So we will clear understanding of tax and exchange rate <br>
Data filter.csv is the data file extracted from the expedia kaggle competition <br>
