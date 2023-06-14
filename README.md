# Mielage-Prediction :
1.The code aims to build a mileage prediction model using linear regression.

2.The dataset is loaded from a provided URL using pd.read_csv().

3.Data exploration is performed to gain insights into the dataset, including checking the first few rows, the number of unique values, data types, and missing values.

4.Data visualization is conducted using scatter plots and regression plots to understand the relationships between variables.

5.Data preprocessing is carried out by dropping rows with missing values and standardizing the feature variables.

6.The target variable ('mpg') and feature variables ('displacement', 'horsepower', 'weight', 'acceleration') are defined.

7.The dataset is split into training and testing sets with a 70:30 ratio using train_test_split().

8.A linear regression model is created using LinearRegression() and trained on the training data using fit().

9.The model's performance is evaluated on the testing data using metrics such as mean absolute error, mean absolute percentage error, and R-squared score.

10.To enhance the model, polynomial features with degree 2 and interaction terms are created using PolynomialFeatures().

11.The transformed features are used to train the linear regression model again.

12.Predictions are made on the transformed testing data.

13.The performance of the polynomial model is evaluated using the same metrics as before.

The code provides insights into the data, builds and evaluates a linear regression model, and enhances it by introducing polynomial features.
