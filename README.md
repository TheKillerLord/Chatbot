# UNM Cafeteria ChatBot

## Project Description
This project is about making an AI chatbot to help both students and staffs to order food from UNM Cafeteria. There will be a program where the chatbot with interact with the user while also providing the user the available food from the stalls that are available in UNM Cafeteria, displaying the types of food under which categories, the prices and the option for delivery or dine in.

## Prequisites 
````
pip install nltk, pickle, numpy, json, time, random, pandas, tensorflow, keras
````

## About files
* intents.json - The data file which has predefined patterns and responses.
* main.py - This python file is to use the program to display menu and order.
* classes.pkl - This pickle file is where it contains the list of categories.
* words.pkl - This pickle file is where it store the words Python object that contains a list of our vocabulary.
* chatbot_model.h5 - This is the trained model that contains information about the model and has weights of the neurons.
* original_food_liust.xlsx - This Excel File is use to refer back to the original food list and update it if neccessary.
* takeOrder.py - This python file is where we let the user to interact with the chatbot by replying question or ordering food.
* training.py - This python file is where we wrote our script to build the model and train our chatbot.

