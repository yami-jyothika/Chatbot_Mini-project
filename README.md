# Chatbot_Mini-project
simple chatbot using python
A chatbot is a computer program that stimulates and processes
human conversation. It allows humans to interact with digital
devices as if they were communicating with a real person.
The pattern matches group of texts is utilized by the bots and it
so it produces an appropriate response to customers. Finding the
way to convert the user's speech or text into structured data. It is
used to get relevant answers for the customers.
By this project we are reducing searching time for assessing
health condition. When users have health-related questions, they
can quickly get answers from the chatbot, reducing the need to
browse the internet for information.
This chatbot is available around the clock to provide users with
access to information and support whenever they need it.

#Introduction:
Before consulting a doctor, this healthcare chatbot provides basic information about the illness and the respective precautions to be taken.
Healthcare chatbots provide helpful information instantly. The people can connect to this chatbot and can get a appropriate precautions to be taken.

#Problems in existing System:
The chatbot's medical knowledge is not up to date and aligned with the latest medical research and guidelines.

#Proposed System:
The chatbot will have the ability to personalize responses based on the users provided Symptoms.
The chatbot will assist users in understanding their symptoms and potential diagnoses and suggests some possible Precautions to be taken.

#Objective:
The users can access the chatbot's assistance at any time, bridging the gap between office hours and urgent health inquiries.
This technology aims to provide quick and accurate responses.

#Project Domain:
A healthcare chatbot typically involves elements of artificial intelligence (AI).

#Methodology:
The chatbot starts working the moment a user types in input, or a query that they want answer to.
Chatbot collects such textual input and analyses it.  
Chatbot matches the intent with the dataset to fetch relevant information.
The chatbot produces a response which is then communicated to the user.

#Implementation:
Import the necessary libraries
Load JSON intent data
Tokenize the pattern into words using NLTK's word_tokenize function.
Perform lemmatization on each word, converting it to lowercase.
Use the 'pickle' library to serialize and save the 'words' and 'classes' lists to 'texts.pkl' and 'labels.pkl' binary files.
Randomly shuffle the 'training' data to ensure that the order of data does not impact training.
Fit the model with training data ('train_x' and 'train_y') for a specified number of epochs and batch size.
Save the trained model as 'model.h5’.
The html file index.html is connected to the training.py file using the flask framework.

#Future Scope:
Advanced Diagnosis and Symptom Assessment
Medication Management
Health and Fitness Tracking
Appointment Scheduling
Multi-lingual capabilities
