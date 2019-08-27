# disastor-response-pipeline

## 1. Installation

Python versions 3.0

**Python Libraries:**
- Pandas.
- Scikit-learn.
- numpy.
- matplotlib.
- nltk

## 2. Project Motivation

In this project, analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages.Then creat a machine learning pipeline to categorize these events to send the messages to an appropriate disaster relief agency.It will include a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data. 

## 3. File Descriptions
### Installing
Clone this GIT repository:

git clone https://github.com/fatimahM9/disastor-response-pipeline.git

### Executing Program:
1- Run the following commands in the project's root directory to set up your database and model.

  - To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv      data/disaster_categories.csv data/DisasterResponse.db

  - To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl

2- Run the following command in the app's directory to run your web app. python run.py

3- Go to http://0.0.0.0:3001/

## 4. Screenshot

## 5. Results

The main findings of the code can be found [here]().

## 6. Licensing, Authors, Acknowledgements

This project is made for a [udacity](udacity.com).Credit goes to [Figure Eight](www.figure-eight.com) for the data.
