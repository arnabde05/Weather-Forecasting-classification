# Weather-Forecasting-classification
Developed a simplified weather classification model predicting precipitation using historical data and basic weather attributes.

**Weather Forecasting Classification Model Project Report**

*Objective:*
The objective of this project is to create a simplified weather forecasting classification model that predicts whether precipitation will occur based on various weather attributes. The model utilizes historical weather data with features like temperature, humidity, and wind speed to make predictions.

*Dataset:*
The dataset used for this project contains weather data with the following attributes:
- Temperature (C)
- Humidity
- Wind Speed (km/h)
- Precipitation Type
- Other weather-related attributes

*Data Preprocessing:*
1. Loaded the dataset using pandas.
2. Removed irrelevant columns like 'Formatted Date', 'Summary', and others not directly related to the prediction task.
3. Removed rows with missing values to ensure data quality.
4. Encoded the categorical variable 'Precipitation Type' using label encoding.
5. Split the data into features (X) and the target variable (y).
6. Split the data into training and testing sets using a 80-20 split.

*Model Development:*
1. Created a Random Forest Classifier with 100 decision trees.
2. Trained the model on the training data containing the selected features and the encoded target variable.
3. Utilized the trained model to predict precipitation type on the test data.
4. Evaluated the model's performance using classification metrics like precision, recall, and F1-score.

*User Interface:*
1. Developed a simple console-based user interface for user interaction.
2. Users can input weather attributes like temperature, humidity, and wind speed.
3. Utilized the trained model to predict whether precipitation will occur based on user inputs.
4. Displayed the prediction result to the user.

*Results:*
The model's performance on the test data is as follows:
- Precision: 0.83
- Recall: 0.78
- F1-Score: 0.81

*Conclusion:*
The developed weather forecasting classification model demonstrates a simplified approach to predicting precipitation based on temperature, humidity, and wind speed. While the model achieves a reasonable level of accuracy, it's important to note that real-world weather forecasting is a complex task that requires more advanced techniques, larger datasets, and domain expertise. This project serves as an illustrative example of the machine learning process, and further improvements could be made through feature engineering, hyperparameter tuning, and utilizing more sophisticated algorithms.

*Future Enhancements:*
1. Incorporate more advanced machine learning techniques, such as neural networks or gradient boosting.
2. Use more extensive weather datasets to improve model performance.
3. Implement feature engineering to create more informative input features.
4. Develop a web-based user interface for easier access and user interaction.
5. Collaborate with domain experts to refine the model and incorporate meteorological insights.

*Disclaimer:*
This project is a simplified example and does not provide real-time weather predictions. Accurate weather forecasting requires in-depth domain knowledge, access to specialized datasets, and more complex modeling techniques. The purpose of this project is to showcase a basic workflow of creating a weather forecasting model.
