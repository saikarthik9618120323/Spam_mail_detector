# Spam_mail_detector
email spam detection using machine learning techniques.
utilised logistic regression for classification

Here's a sample README for your spam mail detection project using Logistic Regression:

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

## Installation

To run this project, you need to have Python installed along with the required libraries. Follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/spam-mail-detection.git
    cd spam-mail-detection
    ```

2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Place the dataset (`mail_data.csv`) in the root directory.
2. Run the `spam_detection.py` script:
    ```bash
    python spam_detection.py
    ```

The model will split the dataset into training and testing sets, train the Logistic Regression model, and print the evaluation results.

## Model Performance

The Logistic Regression model achieves the following performance:

- **Accuracy**: 98-99% (varies depending on the test/train split).

