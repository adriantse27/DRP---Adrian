# Disaster Response Pipeline Project
This project is to classify disaster response messages through machine learning. 

## Content
- Data
  - Data is stored into two csvs 
  - disaster_categories.csv and disaster_messages.csv (dataset)
  - DisasterResponse.db: created database from transformed and cleaned data.
- Models
  - train_classifier.py: includes the code necessary to load data, transform it using natural language processing, run a machine learning model using GridSearchCV and train it. Basic usage is python train_classifier.py DATABASE_DIRECTORY SAVENAME_FOR_MODEL  
- App
  - run.py: Flask app and the user interface used to predict results and display them.
  - templates: folder containing the html templates

## Example:
ETL
Run python data/process_data.py using data/disaster_messages.csv , data/disasters_categories.csv ,data/DisastersMessage.db

To run ML pipeline that trains classifier and saves python
Run models/train_classifier.py
Pickle File: model.pkl

Run python run.py

Go to http://0.0.0.0:3001/ or localhost:3001

## About
Udacity project, data was provided by figure eight.