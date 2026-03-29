A Machine Learning project that detects whether an SMS message is Spam or Ham (Not Spam) using Natural Language Processing (NLP) and classification algorithms.

📌 Project Overview

Spam messages are a common issue in digital communication. This project aims to automatically classify SMS messages into spam or legitimate categories using text preprocessing, feature extraction, and machine learning models.

The system processes raw SMS text, converts it into meaningful numerical features using TF-IDF Vectorization, and trains classification models to predict message categories accurately.

🎯 Objective

The main objective of this project is to build an intelligent system that can:

Identify spam SMS messages automatically
Reduce unwanted or fraudulent text messages
Improve message filtering using Machine Learning techniques
🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
KaggleHub
Natural Language Processing (NLP)
📂 Dataset

This project uses an SMS Spam Collection Dataset containing labeled messages as:

Spam
Ham

The dataset is used for:

Text preprocessing
Feature extraction
Model training
Performance evaluation
⚙️ Workflow
1. Data Collection
Download dataset using KaggleHub
Load SMS text data into a Pandas DataFrame
2. Data Preprocessing
Remove unnecessary symbols and punctuation
Convert text to lowercase
Clean and normalize SMS content
3. Feature Extraction
Convert text into numerical format using TF-IDF Vectorizer
4. Model Building

The following Machine Learning models are used:

Multinomial Naive Bayes
Logistic Regression
Linear SVM
5. Model Evaluation

Performance is evaluated using:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix
Classification Report
📊 Features
Detects whether an SMS is Spam or Ham
Uses NLP techniques for text processing
Compares multiple Machine Learning models
Evaluates model performance using standard metrics
Visualizes results using confusion matrix and graphs
🚀 Installation

Install the required libraries using:

pip install numpy pandas matplotlib seaborn scikit-learn kagglehub
▶️ How to Run
Clone the repository:
git clone https://github.com/your-username/spam-sms-detection.git
Navigate to the project folder:
cd spam-sms-detection
Run the Python file or Jupyter Notebook:
python spam_sms_detection.py
📈 Output

The model predicts whether a given SMS is:

Spam
Ham

It also displays:

Accuracy scores of different models
Confusion matrix
Classification report
ROC curve (if implemented)
💡 Example Use Cases
SMS spam filtering
Fraud message detection
Mobile communication safety
Text classification applications
📌 Future Enhancements
Deploy as a web application
Build a real-time SMS prediction interface
Improve performance with Deep Learning models
Add support for multilingual spam detection


This project is for educational and learning purposes.
