# Spam_mail_detector
email spam detection using machine learning techniques.
utilised logistic regression for classification

---

# Spam Mail Detection

This project demonstrates how to classify emails as **spam** or **ham** (non-spam) using machine learning. The dataset used contains email messages labeled as either "spam" or "ham", and a Logistic Regression model is used to predict these labels based on the text content.

## Table of Contents
- [Dataset](#dataset)
- [Technologies](#technologies)
- [Steps](#steps)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)

## Dataset
The dataset consists of two columns:
- **Message**: The email content.
- **Category**: The label for each message: either "spam" or "ham" (non-spam).

Example data:
```
Category    | Message
------------|--------------------------------------------------
ham         | Go until jurong point, crazy.. Available only ...
spam        | Free entry in 2 a wkly comp to win FA Cup fina...
```

## Technologies
- Python
- Pandas
- Scikit-learn
- Numpy

## Steps
1. **Data Preprocessing**: Convert the text data into numerical form using `CountVectorizer` (Bag-of-Words model).
2. **Model Training**: Use Logistic Regression to classify emails as spam or ham.
3. **Evaluation**: Check the model's performance using accuracy and other classification metrics.

## Model Performance

The Logistic Regression model achieves the following performance:

- **Accuracy**: 98-99%

