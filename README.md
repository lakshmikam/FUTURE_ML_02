This project focuses on building a Natural Language Processing (NLP) system to automatically classify customer support tickets and assign priority levels. The objective is to simulate real-world automation used by SaaS companies and IT support teams to reduce manual ticket sorting and improve response efficiency.

The system processes raw ticket text, converts it into numerical features, and applies machine learning models for classification.

Problem Statement

Customer support teams often receive a high volume of tickets daily. Manual categorization and prioritization can be time-consuming, inconsistent, and prone to delay.

This project aims to automate:

Ticket category classification (e.g., Billing, Technical Issue, Account)

Priority assignment (High, Medium, Low)

Structured evaluation of model performance

The system demonstrates how NLP can support operational decision-making in business environments.

Dataset

Dataset Used: Customer Support Ticket Dataset

Kaggle Link:
https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset

The dataset contains:

Ticket Description

Ticket Type (Category)

Ticket Priority

Additional structured ticket metadata

The Ticket Description column was used as the primary text input for modeling.

Methodology

The project follows a structured NLP pipeline:

Text Preprocessing
Ticket descriptions were cleaned by converting text to lowercase, removing punctuation, and normalizing content.

Feature Extraction
Text data was transformed into numerical vectors using TF-IDF vectorization from Scikit-learn.

Model Development
Logistic Regression models were trained separately for:

Ticket category classification

Ticket priority prediction

Model Evaluation
Performance was evaluated using accuracy, precision, recall, and classification reports to assess prediction quality.

Results

The classification models were able to automatically categorize support tickets and assign priority levels with reasonable baseline accuracy. The results demonstrate the effectiveness of TF-IDF-based feature extraction combined with classical machine learning algorithms for operational NLP tasks.

The system provides a structured framework for automating support workflows and reducing manual processing time.

Future Improvements

Potential improvements include:

Hyperparameter tuning

Using advanced NLP models (e.g., transformer-based embeddings)

Handling class imbalance

Deploying the system as a web-based ticket dashboard
