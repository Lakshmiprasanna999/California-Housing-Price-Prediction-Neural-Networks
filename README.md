# California-Housing-Price-Prediction Neural-Networks

# Goal
This data pertains to the houses found in California state and some summary statistics about them based on the 1990 census data. The goal is to predict the price of the house. The purpose of this project is to explore dense neural network and basic machine learning modeling. I focused mainly on building different neural network models with different sizes of layers, different values of dropout and different number of layers.

# Libraries 
Numpy, Pandas, Matplotlib, Seaborn,Scikit-learn, 

# Steps performed
1. Collect the data
2. Clean the data
   2.a Get the summary statistics
   2.b Check for the missing values
   2.c Deal with missing vlaues
   2.d Check for outliers
   2.e Deal with outliers
   2.f Check for duplicate rows 
3. Explore the data with the help of visualization
   3.a Univariate Analysis
   3.b Correlation Matrix and Heatmap
4. Feature Engineering
   4.a Create Dummy Varibles
   4.b Perform min/max normalization on the numeric columns
5. Split the data to Train and Test (80, 20)
6. Modeling and Evaluation

# Implemented Models and their RMSE
1. Linear Regression    - 68423.57439411113
2. Decision Tree Model  - 70242.1646810371
3. Random Forest Model  - 65951.53264620395
4. Dense Neural Network Architecture 1 - 63019.11825607181
5. Dense Neural Network Architecture 2 - 73369.41033862687
6. Dense Neural Network Architecture 3 - 64266.68416311362

# Insight
1. The variables Median Income, Housing Median Age and Ocean Proximity Inland have high importance in predicting the median house price. 
2. Dense Neural Network model with three layers each with 64 hidden units(Activation Function:'RELU') is found to be performing well(low RMSE value) compared to other models.
