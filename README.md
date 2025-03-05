# Bike_Sharing_Assignment
Observations & Insights
•	Seasonal Trends: Rentals go up in spring and summer and go down in autumn and winter.
•	Yearly Comparison: Rentals were greater in 2019 than they were in 2018.
•	Holidays and Working Days: Rentals are the highest on non-holidays and there is no significant difference between working and non-working days.
•	Weather Impact: Most rentals happen during clear or partially cloudy weather, followed by misty or cloudy weather. Rentals are lowest during light snow or rain.
Data Analysis
•	Outliers: There are outliers in normalized_windspeed and normalized_humidity, but not in total_count or normalized_temp.
•	Normality Check: Some discrepancies from normal are noted in the normal probability plot.
•	Correlation Matrix: Strong positive correlation between temp and atemp as well as total_count, casual, and registered. Casual and registered were cut from further analysis along with atemp.
Model & Evaluation
•	Dataset Split: 70% for training, 30% for testing.
•	Linear Regression
•	Training accuracy: 82.4%
•	R-squared: 0.81, 81% variance in the target is predicted.
•	Some variance in predictions is shown through cross-validation.
•	Testing Metrics
•	RMSE: 802.43
•	MAE: 595.24
•	Residual analysis: Few data points show finite variance in the residuals.

