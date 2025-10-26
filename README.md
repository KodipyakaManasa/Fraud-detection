# Fraud detection using SVM
This project is a Medical Insurance Fraud Detection System implemented as a web application. The system leverages machine learning models, including XGBoost, to identify fraudulent claims and provides an intuitive interface for real-time fraud detection. The application is developed using Python, JavaScript, and Jupyter Notebook, with a structured backend and frontend framework.

# Features
- Machine Learning Integration: Utilizes XGBoost for fraud detection with pre-trained models.
- Interactive Web Interface: Built using Flask and customizable templates.
- Data Handling: Supports CSV and Excel files for claim processing.
- Visualization: Provides analytical insights and visualizations for detected fraud patterns.
- Dynamic Reports: Offers detailed claim evaluations for better decision-making.

# Project Structure
- Bills: Sample bills or related datasets.
- static: Static assets like CSS, JS, and images.
- templates: HTML templates for the frontend.
- Testfile.xlsx: Test data for the system.
- Train-1542865627584.csv: Training data for the ML model.
- Train_Beneficiarydata(Test).xlsx: Additional test data.
- Train_Beneficiarydata.csv: Beneficiary data for training.
- Untitled1.ipynb: Jupyter Notebook for data analysis.
- requirements.txt: Python dependencies.
- run.py: Main entry point to run the Flask app.
- xgboost_model.pkl: Pre-trained XGBoost model.

# Dataset
- The project uses the following datasets:
- Train-1542865627584.csv: Dataset used to train the fraud detection model.
- Testfile.xlsx and Train_Beneficiarydata(Test).xlsx: Test datasets for validation purposes.
- xgboost_model.pkl: Pre-trained XGBoost model for fraud detection.

# Machine Learning Model
The system employs XGBoost, a robust gradient-boosting algorithm, for detecting fraudulent claims. Key highlights:
- Preprocessing: Data preprocessing includes handling missing values, feature engineering, and scaling.
- Evaluation Metrics: Accuracy, precision, recall, and F1-score are used for evaluating model performance.
- Optimization: The model is fine-tuned for optimal performance using hyperparameter tuning.

#  Frontend
- HTML/CSS: Used for layouts and styling.
- JavaScript: Adds interactivity to the application.
- Static Files: Assets like CSS, JS, and images are stored in the static/ folder.
- Templates: Dynamic HTML templates are stored in the templates/ folder.

# Backend
- File Uploads: Supports uploading .csv and .xlsx files for analysis.
- Predictions: Utilizes the trained XGBoost model to predict fraudulent claims.
- Real-Time Fraud Detection: Automatically flags suspicious claims and generates dynamic reports.

# Usage
- Open the application in your browser.
- Upload a claim file (.csv or .xlsx).
- The system will analyze the claims and highlight potential fraud.
- Download detailed analysis reports for further investigation.
