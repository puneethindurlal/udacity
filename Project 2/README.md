# Disaster Response Pipeline Project

This project is written in python to satisfy the requirements for a udacity data science course assignment. 
The project is a web app that automatically classifies text messages during disasters to different categories to aid in disaster management. 

The project is broken down into 3 parts:
1. Extract, Transform & Load (ETL) pipeline to clean and store data for machine learning. 
2. Machine Learning (ML) pipeline to train and save a classifier model to classify text messages. 
3. A web app using flask to allow for interactive classification of new text messages, based on the machine learning classifier model. 

### Packages Needed:
1. Flask
2. SQL Alchemy
3. pandas
4. numpy
5. sklearn
6. nltk

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/
