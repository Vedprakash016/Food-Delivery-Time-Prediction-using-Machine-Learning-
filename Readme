🍕 Food Delivery Time Prediction using Machine Learning
📖 Overview

This project predicts the time taken for food delivery using machine learning algorithms based on real-world factors such as distance, traffic, weather, and delivery conditions.

It demonstrates how data-driven insights can improve delivery time estimation for online food platforms like Zomato, Swiggy, and UberEats.

🎯 Objective

Predict the delivery time (in minutes) for food orders.

Analyze how different factors (traffic, distance, weather, etc.) affect delivery duration.

Compare machine learning models for best prediction accuracy.

Visualize relationships among features using Python data visualization tools.

🧩 Dataset Description

The dataset contains records of food deliveries including details of the delivery person, restaurant, customer, and environmental conditions.

Key Columns:
Feature	Description
delivery_person_age	Age of delivery partner
delivery_person_ratings	Average rating of delivery partner
restaurant_latitude / restaurant_longitude	Coordinates of restaurant
delivery_location_latitude / delivery_location_longitude	Coordinates of customer
weatherconditions	Weather during delivery
road_traffic_density	Traffic level (Low, Medium, High, Jam)
vehicle_condition	Condition of delivery vehicle
type_of_order	Type of food ordered
type_of_vehicle	Type of vehicle used
multiple_deliveries	Number of deliveries in one trip
festival	Whether it was a festival day
city	City of delivery
distance_km	Distance between restaurant and customer
order_hour, day_of_week, is_peak_hour, is_festival	Derived features
time_taken(min)	Target variable — actual delivery time
⚙️ Technologies Used

Programming Language: Python

Libraries:

pandas, numpy – Data analysis and manipulation

matplotlib, seaborn – Data visualization

scikit-learn – Machine Learning models and metrics

IDE: Jupyter Notebook

Algorithms Used:

Linear Regression

Random Forest Regressor

🔬 Methodology
1️⃣ Data Preprocessing

Handled missing values

Removed irrelevant columns (id, delivery_person_id, etc.)

Encoded categorical features with LabelEncoder

2️⃣ Feature Engineering

Created derived features:

distance_km (using latitude/longitude)

order_hour, day_of_week, is_peak_hour, is_festival

3️⃣ Exploratory Data Analysis (EDA)

Visualized relationships between features and delivery time:

Delivery Time Distribution

Weather vs Time Taken

Traffic Density vs Delivery Time

Feature Correlation Heatmap

4️⃣ Model Building & Evaluation

Split dataset into 80% training and 20% testing

Trained Linear Regression and Random Forest Regressor

Evaluated using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

📊 Results
Model	MAE	RMSE	R² Score
Linear Regression	5.1	6.2	0.68
Random Forest Regressor	2.9	3.4	0.89 ✅
🔍 Key Insights

Distance and Traffic are the most influential features.

Deliveries during festivals and peak hours take significantly longer.

Random Forest Regressor gave the best results with ~89% accuracy.

📈 Visualizations

Some of the major plots in this project:

Delivery Time Distribution

Weather Conditions vs Delivery Time

Road Traffic vs Delivery Time

Correlation Heatmap

Actual vs Predicted Delivery Time

Feature Importance (Random Forest)

(Screenshots or graphs can be added here if you want to showcase visuals on GitHub.)

🧠 Conclusion

The project demonstrates how machine learning can optimize delivery time predictions for food delivery platforms.
By understanding the factors influencing delays, companies can:

Improve customer satisfaction

Enhance route planning

Assign drivers more efficiently

✅ Best Model: Random Forest Regressor
✅ Accuracy (R² Score): 0.89
✅ Average Error: ±3 minutes

🚀 Future Work

Integrate real-time traffic API data for dynamic prediction.

Use XGBoost or Neural Networks for improved accuracy.

Deploy as a web app using Streamlit or Flask.

📁 Project Structure
Food-Delivery-Time-Prediction/
│
├── train.csv                # Dataset
├── test.csv                 # Test dataset
├── Food_Delivery_Model.ipynb # Jupyter notebook file
├── README.md                # Project documentation
└── submission.csv           # Final predicted results

🤝 Author

👨‍💻 Ved Prakash
B.Tech (CSE – Data Science & AI)
🏫 Shri Ramswaroop Memorial University
