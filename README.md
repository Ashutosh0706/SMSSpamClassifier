# SMSSpamClassifier
This is a SMS Spam Classifer machine learning model. It will predict Spam or Not Spam messages based on the imput provided to it. 
I have used Naive Bayesain Algorithm which is a Classification Algorithm in ML. 
I have provided end to end code for this project. The dataset which is used to train the model is also their in the repository named as spam.csv. I have downloaded the 
dataset from Kaggle.
I have used Python for this project, and implemented it on jupyter-notebook.
The code for model preprocessing, model training and testing, is provided in sms-spam-classifier.ipynb file.
And the code for website creation is in the main.py file. I have used Streamlit to write the app for my project. Streamlit is an open-source python framework for building web apps for Machine Learning and Data Science.
Streamlit allows you to write an app the same way you write a python code.
I have also provided the requirements i.e. which python libraries I used for the project. It is in Requirements.txt.
How to use:-
1. For data uploading, preprocessing, training and testing use **sms-spam-classifier.ipynb** file. Dataset file is **spam.csv**.
2. For designing a web app use the code in the file **main.py**.
3. Two pickle files (**model.pkl** & **vectorizer.pkl**) are also available. Pickle is used to convert a model into a byte stream to store it in a file or database. Vectorization is used to speed up the Python code without using loop. Using such a function can help in minimizing the running time of code efficiently.
