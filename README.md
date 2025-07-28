# Multiple Disease Prediction Based on User Symptoms using Machine Learning Algorithms

### About the Project

This project aims to predict the most probable disease based on symptoms entered by the user. It uses various supervised machine learning algorithms like Decision Tree, Random Forest, Naive Bayes, Support Vector Machine, K-Nearest Neighbors, and Logistic Regression to make accurate predictions. The system is designed to assist in early diagnosis and help users take necessary health precautions or consult a doctor on time.

### How It Works

- Users select symptoms from a predefined list.

- Each symptom has a severity weight to help measure its impact.

- The system processes the selected symptoms and maps them to likely diseases using trained ML models.

- All six algorithms make individual predictions, and their results are combined to improve the final accuracy.

- The model with the best performance (Random Forest in most cases) provides the final disease prediction.

- The platform also stores previous predictions for future reference.


### Features

- User Registration and Login

- Admin Panel to manage users

- Symptom input form with top 10 symptoms

- Disease prediction with 95% average accuracy

- Results page showing the predicted illness

- Dataset viewing and model performance display

- Web interface built using Django (Python web framework)


### Machine Learning Algorithms Used

- Decision Tree

- Random Forest

- Naive Bayes (Bernoulli)

- Support Vector Machine (SVM)

- K-Nearest Neighbors (KNN)

- Logistic Regression


### Dataset

The dataset used consists of various diseases and their related symptoms along with their severity. It also includes mappings between symptoms and weights to prioritize them in prediction.

### Technologies Used

- Frontend: HTML, CSS (Bootstrap), JavaScript

- Backend: Python, Django

- ML Libraries: scikit-learn, pandas, numpy

- Database: SQLite (default in Django)

- Visualization: matplotlib


### Why This Project?

Many people ignore symptoms or delay checkups due to a lack of awareness or access to doctors. This tool provides a quick and intelligent way to identify possible diseases and take necessary action early. It can also assist healthcare organizations in improving diagnosis workflows.
