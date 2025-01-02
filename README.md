##SMS Spam Detection System Using Natural Language Processing (NLP)
This project demonstrates the development of an SMS spam detection system utilizing Natural Language Processing (NLP) techniques. The system classifies SMS messages as either 'ham' (non-spam) or 'spam' based on their content.

##Table of Contents
Introduction
Dataset
Data Preprocessing
Exploratory Data Analysis (EDA)
Model Building
Evaluation
Deployment
Conclusion
Introduction
The proliferation of unsolicited SMS messages, commonly known as spam, has become a significant concern. This project aims to develop a machine learning model that can accurately distinguish between spam and non-spam SMS messages using NLP techniques.

##Dataset
The dataset used in this project is the SMS Spam Collection Dataset, which contains 5,572 SMS messages labeled as 'ham' or 'spam'. Each entry includes a label and the corresponding text message.

##Data Preprocessing
The preprocessing steps include:

Loading the Data: The dataset is loaded into a pandas DataFrame.
Cleaning the Data: Unnecessary columns are dropped, and the remaining columns are renamed for clarity.
Encoding Labels: The 'ham' and 'spam' labels are converted to binary values (0 and 1) using label encoding.
Handling Missing Values: Any missing values are addressed appropriately.
Removing Duplicates: Duplicate entries are removed to ensure data integrity.
Exploratory Data Analysis (EDA)
EDA is performed to understand the distribution of the data:

Class Distribution: A pie chart is generated to visualize the proportion of 'ham' and 'spam' messages.
Text Analysis: The number of characters, words, and sentences in each message is analyzed to identify patterns.
Model Building
The following machine learning algorithms are implemented to classify SMS messages:

Logistic Regression: A statistical model used for binary classification.
Naive Bayes: A probabilistic classifier based on Bayes' theorem.
Support Vector Machine (SVM): A supervised learning model for classification tasks.
Random Forest: An ensemble learning method for classification.
Stochastic Gradient Descent (SGD): An optimization algorithm for training machine learning models.
Gradient Boosting: An ensemble technique that builds models sequentially.
Each model is trained on the preprocessed data, and hyperparameters are tuned to optimize performance.

##Evaluation
The models are evaluated using metrics such as accuracy, precision, recall, and F1-score. Confusion matrices are generated to visualize the performance of each model.

##Deployment
The best-performing model is deployed using Streamlit, allowing users to input SMS messages and receive real-time predictions on whether the message is 'ham' or 'spam'.

##Conclusion
This project successfully demonstrates the application of NLP techniques in building an SMS spam detection system. The developed model can effectively classify SMS messages, contributing to the reduction of spam-related issues.
