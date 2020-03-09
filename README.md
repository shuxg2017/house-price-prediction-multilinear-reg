# Multi Linear Regression for House Price Prediction
## Overview
We used house price dataset to train a multi linear regression model. <br>
In our final result, r_square = 0.725, and accuracy = 80%. <br>
In other words, our model can capture 72.5% of the variability from the actual house price. <br>
our model can capture 80% of the actual house price. <br>

## Process
1. Data Clean
2. Feature Selection
3. Optimize Feature Selection by Using Regression Model
4. Use the Best Features for the Model

## Dataset
Number of samples: 60,000<br>
Each sample: 49 features<br>
Dataset split: 70% training, 30% testing<br>
<br>
## Figures and Results
### Correlation Coefficient Bar 

Best features for this multilinear regression model.<br>

![Best Selected Features](/figures/best_features.png)


### Performance

If all the points lay on 45 degree straight line, <br>
the model is considered as perfect.<br>

![Performance](/figures/performance.png)

The error looks like normally distributed.<br>
This is a good sign.<br>

![Residual](/figures/residual.png)

### Relation Between Longitude, Latitude and SalePrice

With latitude increase, house price generally increases.<br>
With longitude decrease, house price generally decreases.<br>

![Map](/figures/lon_lat_price.png)
