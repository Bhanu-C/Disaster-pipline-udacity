# Libraries Installation:
Use the standard pip installer to install libraries. (Python 3)

1. pip install pandas as pd
2. pip install numpy as np
3. pip install matplotlib 
4. pip install nltk
5. pip install pickle 
6. pip install sklearn
7. pip install seaborn

# Disaster Response Pipeline Project Udacity
In this course, I learned skills to expand the opportunities and potential as a data scientist.
Github link: 
Go to http://0.0.0.0:3001/

# Project Motivation:
In this project a web application is being made for mainly emergency purpose where a worker can input a new message and it will get classified in several categories. 

### Project Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/
