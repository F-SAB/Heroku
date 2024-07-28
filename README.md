# Fish Weight Prediction Application

## Overview
The Fish Weight Prediction Application is a web-based tool that predicts the weight of a fish based on input parameters such as species, length, height, and width. This application utilizes a regression machine learning model built with `scikit-learn` and is deployed using Flask on Heroku.

## Problem Statement
The task is to predict the weight of fish based on features such as species, length, height, and width. This is approached as a regression problem where the goal is to accurately predict the weight of the fish.

## Dataset
The dataset used for building the model is the Fish Market dataset available on Kaggle: [Fish Market Dataset](https://www.kaggle.com/aungpyaeap/fish-market).

## Features
- Input form for fish species and measurements
- Predicts the weight of the fish based on the inputs
- Deployed on Heroku for easy access

## Dependencies
- Flask
- scikit-learn
- numpy
- gunicorn
- blinker
- click
- colorama
- itsdangerous
- Jinja2
- joblib
- MarkupSafe



## Files in the Repository
- `model_building.ipynb`: Jupyter notebook for model building.
- `model.pkl`: Saved model file.
- `app.py`: Python code for the Flask API.
- `Fish.csv`: Dataset used for training the model.
- `templates/input.html`: HTML file for the input form.
- `templates/result.html`: HTML file for displaying the prediction result.
- `requirements.txt`: List of dependencies.


## Acknowledgements
- The Fish Market dataset was obtained from Kaggle: [Fish Market Dataset](https://www.kaggle.com/aungpyaeap/fish-market).
- The application was built using Flask and scikit-learn.


