# Spam

Spam Email Classification with Machine Learning
This project aims to classify emails as either 'Spam' or 'Ham' (not spam) using machine learning techniques. We use a dataset containing SMS messages, where each message is labeled as either spam or ham.
The project is implemented in Python using popular libraries like NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn.

**Code Overview**

Data Loading and Exploration: We load the dataset, explore its shape, examine data types, and perform initial data analysis.

Data Preprocessing: We preprocess the 'Category' column by replacing 'ham' with 1 and 'spam' with 0.

Data Splitting: We split the data into training and testing sets using the train_test_split function.

Text Vectorization: We use TF-IDF vectorization to convert the text messages into numerical features.

Model Training: We train a Logistic Regression classifier on the training data to learn the patterns in the text messages.

Model Evaluation: We evaluate the model's accuracy on both the training and testing sets.

Spam Classification: We demonstrate how to use the trained model to classify new messages as 'Spam' or 'Ham'.

**Conclusion:**
This project provides a simple yet effective approach to classify email messages as spam or ham using machine learning. 
You can use the trained model to enhance your email filtering or spam detection systems.
