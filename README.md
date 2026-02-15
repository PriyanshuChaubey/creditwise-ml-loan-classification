Project Description: CreditWise – Loan Approval Prediction

CreditWise is an end-to-end supervised machine learning project designed to predict loan approval outcomes based on applicant financial and demographic information. The goal of this project is to simulate a real-world credit risk assessment problem and apply machine learning techniques to support data-driven decision-making in the lending domain.

The project follows a complete machine learning pipeline, starting from raw data analysis to model evaluation. Initially, Exploratory Data Analysis (EDA) was performed to understand data distributions, correlations between features, and potential risk indicators influencing loan approval decisions. This step helped identify important patterns, class imbalance, and preprocessing requirements.

Feature preprocessing included handling numerical and categorical variables, scaling where necessary, and performing feature engineering to enhance model learning. As part of feature engineering, non-linear transformations were introduced by adding squared terms for key financial indicators such as Debt-to-Income (DTI) Ratio and Credit Score. These transformations help linear models capture non-linear relationships commonly observed in real-world financial risk data.

Multiple supervised classification algorithms were implemented and compared, including:

K-Nearest Neighbors (KNN)

Logistic Regression

Naive Bayes

Each model was trained and evaluated using appropriate performance metrics such as Accuracy, Precision, Recall, and F1-score, ensuring a balanced assessment rather than relying solely on accuracy. After comparison, Logistic Regression achieved the highest accuracy and demonstrated the most balanced performance across evaluation metrics, making it the most suitable model for this classification task.

This project demonstrates practical understanding of:

Supervised machine learning fundamentals

Feature engineering and preprocessing techniques

Model comparison and evaluation strategies

Building reproducible ML workflows

CreditWise was built as part of a structured learning journey and reflects a strong emphasis on applying theoretical concepts to real-world datasets. The project can be further extended by incorporating hyperparameter tuning, cross-validation, model deployment, or explainability techniques.
