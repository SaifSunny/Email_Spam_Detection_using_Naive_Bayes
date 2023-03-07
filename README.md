# Email_Spam_Detection_using_Naive_Bayes

This project uses the Naive Bayes algorithm to classify emails as either spam or not spam (ham) using the spam.csv dataset. The model achieves an accuracy of 98% in detecting spam emails.

# Dataset
The spam.csv dataset contains 5,572 emails labeled as either spam or ham. It has the following two columns:

v1: Label, where "spam" indicates a spam email and "ham" indicates a non-spam (ham) email
v2: Email text

# Requirements
This project requires the following packages:

    Python
    pandas
    numpy
    scikit-learn
    
These can be installed using pip:

    pip install pandas scikit-learn

# Usage
To run the model, simply run the email_spam_detection.py file in a Python environment with the required packages installed. The model will load the dataset, split it into training and testing sets, train the Naive Bayes classifier on the training set, and then evaluate its accuracy on the testing set.

The output will show the accuracy of the model in detecting spam emails.

# Contributing
Contributions are welcome. Please create a pull request with any changes or improvements.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
