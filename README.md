# Delivery_Time_Prediction
Develops a predictive model for estimating food delivery times based on distance, preparation time, traffic, time of day, and weather, enhancing customer satisfaction and logistics for food delivery services like Swiggy.

💡 Motivation
Improving delivery time predictions helps optimize delivery logistics, manage customer expectations, and enhance user experience in food delivery.

🔧 Features
Data Processing: Preprocessed historical data and feature engineering for enhanced model accuracy.
Model Training: Linear Regression and Random Forest models; evaluated and saved the best model for deployment.
Real-Time Simulation: Conceptual integration of Kafka for real-time data ingestion.
API Deployment: Flask REST API for real-time predictions.

⚙️ Tech Stack
Python: Core programming and data processing
Scikit-Learn: Model training and evaluation
Flask: REST API deployment
Kafka (Conceptual): For real-time streaming simulation
SQL: For data extraction (simulated)

📂 Project Structure
data/: Contains synthetic dataset
notebooks/: Jupyter notebooks for data analysis and model training
app.py: Flask application to serve predictions
requirements.txt: Dependencies for the project

