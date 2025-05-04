# classification-challenge
# 📧 Classification Challenge: Spam Email Detector

In this project, we take on the role of a Machine Learning Engineer at an Internet Service Provider (ISP). The objective is to build a system that can automatically detect and filter out spam emails from customers' inboxes.

We’ll use **supervised machine learning** to create and evaluate two different classification models:
- **Logistic Regression**
- **Random Forest Classifier**

## 🧠 Objective

Build, train, and evaluate two classification models using a dataset of emails, each labeled as either **spam (1)** or **not spam (0)**. Then determine which model performs better at accurately identifying spam emails.

### 🔹 1. Data Preparation
- Load the dataset into a Pandas DataFrame.
- Define `X` (features) and `y` (labels from the `"spam"` column).
- Check the balance of spam vs. not spam using `value_counts()`.
- Split the data into training and testing sets using `train_test_split`.

### 🔹 2. Feature Scaling
- Use `StandardScaler` to normalize feature data.
- Fit the scaler to training data and transform both training and testing features.

### 🔹 3. Logistic Regression Model
- Initialize logistic regression with `random_state=1`.
- Train the model on the scaled training data.
- Predict on the test set.
- Evaluate accuracy with `accuracy_score`.

### 🔹 4. Random Forest Classifier
- Initialize random forest classifier with `random_state=1`.
- Train the model on the scaled training data.
- Predict on the test set.
- Evaluate accuracy with `accuracy_score`.

### 🔹 5. Evaluation
- Compare the accuracy scores of both models.
- Determine which model performs better at identifying spam.
- Reflect on the initial prediction made before training.


## 🧠 Final Thoughts

- Which model performed better?
- How did that compare to the initial prediction?

These conclusions are addressed in the final markdown cell of the notebook.