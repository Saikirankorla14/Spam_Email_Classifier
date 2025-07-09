# Spam_Email_Classifier

Project Overview
This project implements a spam email classifier using Natural Language Processing (NLP) techniques. The goal is to accurately classify emails as spam or not spam. The project utilizes the Enron Spam Dataset, a widely used dataset for training and evaluating spam detection models.
Dataset
The Enron Spam Dataset contains a large number of emails from the Enron Corporation. It includes both spam and ham (non-spam) emails, making it suitable for training supervised learning models. The dataset is pre-labeled, which allows for straightforward evaluation of model accuracy.
Methodology
- Data Cleaning and Preprocessing: Tokenization, stopword removal, stemming/lemmatization.
- Feature Extraction: Using Bag-of-Words or TF-IDF vectorization.
- Model Training: Applied algorithms such as Naive Bayes, SVM, and Logistic Regression.
- Evaluation: Performance measured using accuracy, precision, recall, and F1-score.
Technologies Used
- Python
- Scikit-learn
- NLTK or spaCy for text preprocessing
- Pandas and NumPy for data manipulation
- Matplotlib/Seaborn for visualization
How to Run the Project
1. Clone the repository.
2. Install required packages using pip (e.g., pip install -r requirements.txt).
3. Load and preprocess the Enron dataset.
4. Train the model using the training script.
5. Evaluate the model and test it with new data.
Results
The best-performing model achieved over 95% accuracy in classifying emails as spam or not spam. Precision and recall metrics further validated the model’s effectiveness.
Confusion Matrix:
![confusion_Email](https://github.com/user-attachments/assets/2191619d-2ca3-43b0-89ec-9edda240651e)

Distribution Email Length:
![Distribution_Email](https://github.com/user-attachments/assets/9433b7bb-6969-4997-92e6-f0af2ae5ed8c)

