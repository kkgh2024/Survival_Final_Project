🏥 Patient Survival Prediction Using Machine Learning
📍 Problem Statement

Hospitals often rely on historical clinical data but struggle to identify the most influential factors affecting patient survival outcomes. Without reliable predictive insights, it becomes challenging to optimize treatment strategies and allocate resources effectively.

🎯 Objective

The objective of this project is to develop a machine learning–based predictive model capable of estimating the likelihood of a patient surviving one year post-treatment. The model is designed to support clinical decision-making by highlighting key survival predictors derived from historical patient data.

📊 Data Description

Patient demographic information

Medical history and clinical indicators

Treatment-related variables

Target variable: One-year survival outcome

The dataset required extensive preprocessing to ensure reliability and consistency for modeling.

🧠 Methodology
Data Preparation

Handled missing values using median and mode imputation

Removed ambiguous or non-informative responses (e.g., “Cannot say” for smoking status)

Detected and treated outliers using z-score analysis

Model Development

Multiple supervised machine learning models were trained and evaluated:

Logistic Regression

Decision Trees

Random Forest

Gradient Boosting

AdaBoost

Support Vector Machine (SVM)

Hyperparameter Optimization

Applied GridSearchCV to systematically tune model hyperparameters and improve performance

Evaluated models using accuracy and cross-validation metrics

AutoML Benchmarking

Leveraged PyCaret AutoML to benchmark manual model development against automated pipelines

Ensured model robustness and validated algorithm selection efficiency

📈 Key Results

Gradient Boosting emerged as the best-performing model

Achieved ~80% prediction accuracy on unseen data

AutoML benchmarking confirmed the consistency and reliability of the selected model

💡 Business & Clinical Impact

This predictive model enables healthcare providers to:

Identify high-risk patients earlier in the treatment process

Support personalized care planning

Improve resource allocation and follow-up strategies

Enhance data-driven clinical decision-making

The solution demonstrates how machine learning can be effectively applied to real-world healthcare challenges to improve patient outcomes.

🛠 Tools & Technologies

Python (Pandas, NumPy, scikit-learn)

Machine Learning Models: Gradient Boosting, Random Forest, SVM

AutoML: PyCaret

Model Optimization: GridSearchCV

Data Analysis & Visualization: Matplotlib, Seaborn

📦 Deliverables

End-to-end Jupyter Notebook (data preparation, modeling, evaluation)

Optimized machine learning model

Performance comparison across multiple algorithms

7️⃣ Resume-Ready Bullet Point (Very Important)
