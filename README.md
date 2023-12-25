Taxi Fare Prediction Using Spark MLlib
Overview:
This project focuses on predicting taxi fares in a city using Spark's MLlib. Two different models are developed to predict fares based on trip distance and trip duration. Additionally, Spark operations are employed to compute average tip amounts and determine peak trip hours.

Project Structure:
Dataset: The data used for this project contains information about taxi trips, including trip distance, trip duration, fare amount, and tip amount.

Models:

Model M1: Predicts taxi fare based solely on trip distance.
Model M2: Predicts taxi fare based on trip distance and trip duration in minutes.
Tasks:

Predict fare for specific trip distances and durations.
Compute average tip amount.
Determine peak trip hours in the city.
Compare Spark's performance by dividing the data into varying percentages.
Instructions:
Environment Setup: Ensure you have Apache Spark and PySpark installed in your environment.

Dataset: The dataset used for this project should be downloaded and placed in the appropriate directory. Make sure the dataset format is compatible with Spark.

Code Execution:

Execute the Spark scripts (m1_prediction.py and m2_prediction.py) to build and evaluate the models.
Run average_tip_amount.py to compute the average tip amount.
Execute peak_trip_hours.py to determine the peak trip hours in the city.
Run spark_performance_comparison.py to compare Spark's performance with varying data percentages.
Results:
Model M1:

Predicted fare for a 20-mile trip: [Fare Amount]
Model M2:

Predicted fare for a 14-mile trip that took 75 minutes: [Fare Amount]
Fare comparison for specific trips: [Comparison Result]
Average Tip Amount: [Average Tip Amount Value]

Peak Trip Hours: The city experiences the most number of trips during [Specific Hour Range].

Spark Performance Comparison: Detailed results comparing Spark's performance with different data percentages are available in the respective script output files.

Conclusion:
This project demonstrates the application of Spark MLlib for predicting taxi fares based on trip distance and duration. Additionally, it provides insights into average tip amounts and peak trip hours in the city.

