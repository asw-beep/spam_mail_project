# spam_mail_project

📧 spam_mail_project

A simple yet effective Spam Mail Detection system built using Logistic Regression and TF-IDF Vectorization. This project demonstrates how machine learning can be used to classify SMS messages as either spam or ham (not spam).

🧠 Overview

The aim of this project is to build a predictive model that can accurately classify emails/SMS messages as spam or ham using natural language processing (NLP) techniques. The model is trained on a dataset of labeled messages and utilizes a Logistic Regression classifier.


📁 Dataset

    The dataset used is a CSV file (mail_data.csv) containing 5572 labeled messages.

    Columns:

        Category: ham or spam

        Message: The text content of the message


⚙️ Technologies Used

    Python 🐍

    Pandas 📊

    NumPy 🔢

    Scikit-learn 🤖 (Logistic Regression, TF-IDF, Train/Test Split)

    Jupyter Notebook 📓



    Data Collection and Preprocessing

        Load data using pandas

        Handle null values

        Label encoding: ham = 1, spam = 0

    Feature Extraction

        Convert text data into numerical features using TfidfVectorizer

    Model Training

        Train a LogisticRegression model on the TF-IDF features

    Model Evaluation

        Achieved ~96.68% accuracy on training data

        Achieved ~97.13% accuracy on test data

    Prediction System

        Build a simple system to classify custom input messages as spam or ham


✅ Example

n_mail = ["Meeting tomorrow at 10 AM. Let me know if you're available."]

Output:

Ham mail


🚀 How to Run

    Clone the repository or download the files:

git clone https://github.com/asw-beep/spam_mail_project.git

Navigate to the project directory and run the notebook:

cd spam_mail_project
jupyter notebook

Make sure to have mail_data.csv in the same directory as the notebook.

📌 Requirements

Install required packages using pip:

pip install pandas numpy scikit-learn


<hr>
🙋‍♂️ Author

Aswin (asw-beep)

