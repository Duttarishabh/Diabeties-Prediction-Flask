**Diabetes Prediction Using Flask.** 
=> A Flask-based web application that predicts whether a person has diabetes based on their health parameters.
**Project Overview**
This project is an end-to-end machine learning application where:
This Project contains two Pipelines:
1. Training Pipeleine
2. Prediction Pipeline.
   In training pipeline there major
    4 **Steps**
   a. Data Ingestion: Reading the data from the specific source.
   b. Data Transformation: The EDA steps like cleaning the data, finding outliers, Normalizing the data, Feature extraction and Feature engineering.
   c. Model Trainer: This application is trained by using the Decision tree, Support vector tree and logistic classification machine learning algorithms.
   d. Model Evaluation: To evaluate the model like calculating the confusion matrix, precision.

In prediction Pipleline:
I have created the frontend page hosted on the Web API flask, which takes the data and fetch the information from the backend and predicts .

1. A trained model predicts diabetes likelihood.

2. A Flask API serves the model for real-time predictions.

3. The app is deployed on the AWS Beanstalk.

**Project Structure**
├── static/               # Stores CSS, JS, and images
├── templates/            # HTML templates for the Flask app
│   ├── index.html        # Main UI page
├── model/                # Pretrained model stored in .pkl file
├── app.py                # Main Flask application
├── requirements.txt      # Required dependencies
├── README.md             # Documentation
└── .gitignore            # Ignore unnecessary files
**Install Dependencies**
pip install -r requirements.txt
**Technologies Used**
Python

Flask

Scikit-learn

HTML, CSS (for UI)
**Run the Flask application**
python app.py

**How It Works**
The user enters their health details (e.g., glucose level, blood pressure).

The Flask app processes the input and passes it to the trained model.

The model predicts whether the person is diabetic or not.

The result is displayed on the UI.












# lab-flask

<!-- ![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png) -->


To run flask application 

```
python app.py
```


To access your flask application open new tab in and paste the url:
```
https://{your_url}.pwskills.app:5000/
```
