# heart-desease-preditive-analysis-using-ml

COMPANY: CODTECH IT SOLUTIONS

NAME: GOWTHAM A

INTERN ID: CT04DF538

DOMAIN: DATA ANALYTICS

DURATION: 4 WEEEKS

MENTOR: NEELA SANTHOSH KUMAR

# description

Project Overview: Heart Disease Prediction Web Application
Introduction
Heart disease remains one of the leading causes of mortality worldwide. Early detection plays a pivotal role in improving survival rates and enhancing patient outcomes. This project aims to develop a Heart Disease Prediction Web Application that allows users to input key medical parameters and receive a prediction regarding the likelihood of heart disease. The system uses a pre-trained machine learning model deployed via a user-friendly Flask web interface.

Objectives
The primary objectives of this project are:

To build an accessible and interactive tool for heart disease risk prediction.

To utilize machine learning for real-time inference based on clinical data.

To deliver a responsive web interface where users can enter health-related inputs.

To increase awareness and encourage proactive healthcare decisions.

Technologies Used
Python & Flask: Flask is used to create a lightweight server that handles user input and serves HTML pages.

HTML/CSS: Used for designing the front-end interface which includes form fields for health parameters.

NumPy: For handling numerical data as input to the model.

Pickle: To load the pre-trained model stored in a .pkl file.

Machine Learning Model: Trained separately (not shown in files), the model uses clinical features to predict the presence of heart disease.

User Interface and Input Collection
The front-end of the application is created using HTML and styled with embedded CSS. The form titled "Heart Disease Risk Checker" collects the following health parameters:

Age

Sex (Male/Female)

Chest Pain Type (Four categories)

Resting Blood Pressure

Cholesterol Level

Fasting Blood Sugar > 120 mg/dl (Yes/No)

Resting ECG Results

Maximum Heart Rate Achieved

Exercise Induced Angina (Yes/No)

ST Depression (Oldpeak)

Slope of ST Segment

The input form is visually appealing, responsive, and easy to use. A JavaScript alert confirms the user's submission for improved interaction.

Backend Functionality
The backend logic is implemented in app.py. When the user submits the form:

The input is captured via POST request.

The values are converted into a NumPy array in the required format.

A pre-trained ML model (model.pkl) is used to make predictions.

Based on the model's output (1 for disease, 0 for no disease), an appropriate message is returned to the user.

This allows users to get an instant prediction based on their health data.

Prediction Output
Once the form is submitted, users are redirected to a result page where the application displays a message such as:

“You have Heart Disease”

“You do not have Heart Disease”

This output is dynamically generated depending on the model's prediction.

Significance and Impact
This project demonstrates how machine learning and web technologies can combine to create meaningful healthcare tools. By simplifying the diagnostic process and providing accessible insights, the tool empowers users to make informed decisions. Although not a substitute for professional diagnosis, it serves as an initial risk screening method, especially useful in resource-limited settings.

Conclusion
The Heart Disease Prediction Web Application is a practical example of how artificial intelligence can enhance preventive healthcare. It integrates a pre-trained ML model into an easy-to-use web interface, enabling users to quickly assess their health risks. Future enhancements could include graphical feedback, historical tracking, and multilingual support to increase usability and reach.

# output

