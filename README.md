# Bike Shareing Assignment
> Outline a brief description of your project.


## Table of Contents
* [Observation and Insights](#general-information)
* [Model Evaluvation](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Observation And Insights
•	Seasonal Trends: Rentals go up in spring and summer and go down in autumn and winter.
•	Yearly Comparison: Rentals were greater in 2019 than they were in 2018.
•	Holidays and Working Days: Rentals are the highest on non-holidays and there is no significant difference between working and non-working days.
•	Weather Impact: Most rentals happen during clear or partially cloudy weather, followed by misty or cloudy weather. Rentals are lowest during light snow or rain.
Data Analysis
•	Outliers: There are outliers in normalized_windspeed and normalized_humidity, but not in total_count or normalized_temp.
•	Normality Check: Some discrepancies from normal are noted in the normal probability plot.
•	Correlation Matrix: Strong positive correlation between temp and atemp as well as total_count, casual, and registered. Casual and registered were cut from further analysis along with atemp.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions and Model Evaluvation
-Dataset Split: 70% for training, 30% for testing.
-Linear Regression
•	Training accuracy: 82.4%
•	R-squared: 0.81, 81% variance in the target is predicted.
-Some variance in predictions is shown through cross-validation.
•	Testing Metrics
•	RMSE: 802.43
•	MAE: 595.24
•	Residual analysis: Few data points show finite variance in the residuals.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by https://github.com/aishualexaj - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
