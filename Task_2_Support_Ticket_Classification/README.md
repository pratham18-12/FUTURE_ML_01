# Support Ticket Classification & Prioritization

## Project Overview

This project is a Machine Learning and NLP-based Support Ticket Classification and Prioritization system developed as part of **Future Interns - Machine Learning Task 2 (2026)**.

The system analyzes customer support tickets and automatically predicts:

- Ticket Category
- Ticket Priority

This helps support teams organize tickets, identify important issues, and respond faster.

---

## Objective

The goal of this project is to build a Machine Learning system that can:

- Read customer support ticket text
- Automatically classify tickets into categories
- Predict ticket priority levels
- Help businesses improve support operations

---

## Dataset

The project uses the **Customer Support Ticket Dataset**.

The dataset contains support ticket information such as:

- Ticket Subject
- Ticket Description
- Ticket Type
- Ticket Priority

The ticket subject and description are combined and used as input for the Machine Learning models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Regular Expressions (Regex)
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib
- Jupyter Notebook
- VS Code

---

## NLP Preprocessing

The following text preprocessing steps were performed:

- Converted text to lowercase
- Removed punctuation and special characters
- Removed unnecessary spaces
- Combined Ticket Subject and Ticket Description
- Converted text into numerical features using TF-IDF

---

## Machine Learning Models

Two classification models were created:

### 1. Ticket Category Classification

The model predicts the category or type of the support ticket.

### 2. Ticket Priority Classification

The model predicts the priority level of the support ticket.

Possible priority levels include:

- High
- Medium
- Low

The project uses **Logistic Regression** as the classification algorithm.

---

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Sample Prediction

The system can analyze a support ticket such as:

> "I was charged twice for my subscription payment"

And automatically predict:

- Ticket Category
- Ticket Priority

This can help support teams route tickets to the correct department and handle urgent issues faster.

---

## Visualizations

The project includes:

1. Category Classification Confusion Matrix
2. Priority Classification Confusion Matrix

---

## Business Value

This system can help businesses:

- Automatically organize incoming support tickets
- Reduce manual ticket sorting
- Identify urgent customer issues faster
- Improve response time
- Reduce support backlog
- Improve customer satisfaction

This makes the project useful for SaaS companies, service platforms, and internal IT support teams.

---

## Project Structure

```text
Task_2_Support_Ticket_Classification
│
├── data
│   └── customer_support_tickets.csv
│
├── notebooks
│   └── support_ticket_classification.ipynb
│
├── images
│   ├── category_confusion_matrix.png
│   └── priority_confusion_matrix.png
│
└── README.md




Author

Pratham Singh

Future Interns - Machine Learning Internship (2026)