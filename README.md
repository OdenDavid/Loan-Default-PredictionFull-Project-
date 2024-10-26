# Loan-Default-PredictionFull-Project-
Loan Default Prediction + MLOPS (AWS)

Lendy: Machine Learning-based Loan Application System
===========================================================

Overview
-----------
Lendy is an innovative loan application system leveraging machine learning and AWS services to predict loan defaulters. This project streamlines the loan application process, ensuring efficient and data-driven decision-making.

Folder Structure
-------------------
`Lendy/
Consumer/
Dockerfile
handler.py
model.joblib
scaler.joblib
requirements.txt
Producer/
Producer.py
Loan Data/
loan_train.csv
loan_test.csv
Streamlit/
App.py
requirements.txt`

Components
------------
1. Consumer
Dockerfile: Docker configuration for consumer Lambda function
handler.py: Lambda function handler for prediction
model.joblib: Trained machine learning model
scaler.joblib: Data scaler for feature normalization
requirements.txt: Dependencies for consumer Lambda function
2. Producer
Producer.py: Lambda function handler for data processing
3. Loan Data
loan_train.csv: Training dataset for machine learning model
loan_test.csv: Testing dataset for machine learning model
4. Streamlit
App.py: Streamlit application for user interface
requirements.txt: Dependencies for Streamlit application
5. Project
Project.ipynb: Model Building

Technologies Used
--------------------
Python
Machine Learning (Random Forest, XGBoost)
AWS (API Gateway, Lambda, Kinesis Data Stream, ECR, SNS)
Streamlit
Docker

Getting Started
---------------
Clone the repository: git clone https://github.com/your-username/Lendy.git
Install dependencies: pip install -r requirements.txt (in respective folders)
Build Docker image: docker build -t lendy-consumer . (in Consumer folder)
Deploy AWS Lambda functions
Run Streamlit application: streamlit run App.py (in Streamlit folder)

Contributing
------------
Contributions are welcome! Please open an issue or submit a pull request.

License
-------
[DavidOden]

Author
--------
Feel free to customize this README to fit your needs!
Would you like me to add any specific sections or details?