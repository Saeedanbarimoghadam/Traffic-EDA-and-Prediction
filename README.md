# Traffic EDA-and Prediction

1. Exploratory Data Analysis (EDA)
Data Overview: The dataset contained 2976 entries with columns such as Time, Date, Day of the week, CarCount, BikeCount, BusCount, TruckCount, Total Traffic, and Traffic Situation. There were no missing values in the dataset.


Visualizations:
Histograms and boxplots were generated to visualize traffic patterns by day and time.
A time series line plot was used to depict average vehicle counts over time.
Traffic situation categories were also plotted against total vehicle counts, providing insight into normal, heavy, and high traffic situations.


3. Feature Engineering
Extracted additional features from the Time column, such as hour, minute, and AM/PM, to add temporal context to the predictions.
Converted categorical variables like Day of the week and Traffic Situation into numerical formats to prepare the data for machine learning models.


5. Traffic Situation Prediction
Models Used: Several classifiers were employed for prediction:
Logistic Regression
Random Forest Classifier
Support Vector Machine (SVC)
XGBoost Classifier
AdaBoost Classifier
Voting Classifier: A voting classifier was used to combine the strengths of multiple models, achieving an accuracy of 94.46%.
Individual Model Performance:
Random Forest and XGBoost performed exceptionally well, with accuracies of 99.66% and 100%, respectively.
Logistic Regression and SVC also provided decent accuracies, while AdaBoost struggled with a lower performance.


6. Conclusion
The analysis and modeling successfully predicted traffic situations with high accuracy using ensemble methods. The Random Forest and XGBoost models demonstrated superior performance, making them ideal for this type of prediction task.
This project effectively combined EDA, feature engineering, and predictive modeling to explore and forecast traffic conditions based on vehicle data.
