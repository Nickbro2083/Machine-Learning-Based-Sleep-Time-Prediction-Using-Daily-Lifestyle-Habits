# Machine Learning Based Sleep Time Prediction Using Daily Lifestyle Habits
This project is done by using Google Colaboratory.

Tools and libraries used: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

Machine Learning used in this project: KNN (K-Nearest Neighbors) regressor, Linear Regression, Random Forest Regressor, MLP (Multi-Layer Perceptron)

Data Preprocessing techniques used: Interquartile Range (IQR) for Outlier Detection, Feature Scaling, Data Cleaning and Feature Engineering

Download the dataset here: https://www.kaggle.com/datasets/govindaramsriram/sleep-time-prediction

# Summary
<p align="justify">This project develops a machine learning-based sleep time prediction system that estimates an individual's bedtime based on their daily lifestyle habits and behavioral patterns. The objective is to analyze how factors such as work schedules, screen time, physical activity, caffeine consumption, and other daily routines influence sleeping behavior, ultimately providing personalized sleep predictions and promoting healthier lifestyle management.</p>

# About this project
<p align="justify">The project follows a complete machine learning workflow, including data preprocessing, outlier detection, feature engineering, model training, and performance evaluation. The Interquartile Range (IQR) method was applied during preprocessing to identify and remove outliers, improving data quality and model reliability. Multiple regression algorithms were then implemented and compared to determine the most effective approach for predicting sleep time.</p>

<p align="justify">Linear Regression was used as a baseline model to capture linear relationships between lifestyle factors and sleep schedules. K-Nearest Neighbors (KNN) Regressor predicted sleep time by identifying individuals with similar daily habits and leveraging their sleep patterns. Random Forest Regressor was employed to model complex, non-linear relationships through an ensemble of decision trees, providing robust predictions and feature importance analysis. Additionally, a Multi-Layer Perceptron (MLP) neural network was used to learn deeper patterns and interactions among behavioral features that may influence sleeping habits.</p>

<p align="justify">The models were trained and evaluated using standard regression metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²). Experimental results demonstrated that machine learning techniques can effectively predict sleep schedules from daily lifestyle data, with the best-performing model achieving strong predictive accuracy. The project highlights the potential of data-driven approaches in personal health monitoring, sleep management, and lifestyle recommendation systems.</p>
