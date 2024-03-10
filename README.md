# Airbnb Europe Price Prediction
[Code](https://github.com/SoumyaO/airbnb-europe-price-prediction/blob/main/Group%2016_AML_final%20courswork.ipynb) | [Presentation](https://github.com/SoumyaO/airbnb-europe-price-prediction/blob/main/Group16_Presentation.pptx)

### Contributors
[Linh Nguyen](https://github.com/jill-data)  
[Soumya Ogoti](https://github.com/SoumyaO)  
[Wenxu Tian](https://github.com/Wayne599)  
[Hang Su](https://github.com/Hangbiob)  
[Chuqiao Xiao](https://github.com/XShawn1)

## Description
A comprehensive examination of Airbnb prices in popular European cities is undertaken in this project. By employing spatio econometric methods, we predict the prices of Airbnb listings from their attributes.

The [dataset](https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities) consists of prices of Airbnb listings in 10 cities across Europe. For each listing attributes include room types, cleanliness, satisfaction ratings, number of bedrooms, distance from city centre and more.

## Methodology
Data cleaning and exploratory data analysis is performed on the dataset. 

Different Machine Learning models to predict the airbnb prices are explored and compared against each other. These include the following.
- Decision Trees
- Random Forest
- XGBoost
- Linear Regression
- Ridge Regression
- Lasso Regression
- Neural Networks: Multi Layer Perceptron
- Neural Netowrks: Autoencoder

Techniques such as feature selection, target variable log-transformation and hyperparameter tuning are employed to improve model performance.

The neural networks were implemented using the Tensorflow framework and hyperparameter tuning was done using the KerasTuner library.

Among the models the XGBoost model with feature selection stood out with the highest predictive accuracy due to its built-in feature selection and ability to capture non-linear relationships.

This analysis can be used to get insights into the pricing strategy based on identified significant features like number of bedrooms, location etc. Based on the importance of the attributes (feature importance), owners can focus on improving the aspects that have the most impact on the price and make valuable investment decisions to increase their return on investment.