# Car-Price-Prediction
The business objective was to predict the present the price of the car Year,based on features such as selling price, present  price, kilometers  driven,  fuel type, seller  type, transmission, owner.
In the first step EDA was performed with the help of seaborn and matplotlib libraries . The major insights that were drawn and also the correlation between different variables was also obtained.
The feature importance was find out using extra tree regressor and a graph of feature importance was plotted. After that all the categorical variables were converted into numeric variables with the help of dummy variables.
The data was split into test and train dataset  and  hyper parameter tuning was performed on random forest regressor using random search CV to obtain best parameters that yields low rmse.
The find model was built using the best parameters and dumped.
The model was deployed with flask framework and Flask API was created using heroku.

For EDA and Model Building refer- untitled.py
For deployment refer -app.py
Flask API  link- https://car-rate-prediction-api.herokuapp.com/predict
