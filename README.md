1. Project Description

Predicts highly-rated drugs based on side effects, medical conditions, and other features using machine learning. The project includes data cleaning, feature engineering, Random Forest modeling, PCA visualization, and SHAP explainability for interpretable insights.

2. Features

Cleans and processes numeric, text, and categorical data

Extracts side effect patterns and flags critical symptoms

Predicts drug ratings using Random Forest

Visualizes important features and PCA clusters

Explains predictions using SHAP

3. Dataset

CSV dataset containing drug information, side effects, ratings, medical conditions, and other relevant features

Example columns: side_effects, related_drugs, rating, medical_condition, drug_classes

4. Installation
pip install shap scikit-learn pandas numpy matplotlib seaborn joblib tqdm

5. Usage

Upload your CSV dataset in Colab or set a path to your file.

Run the notebook cells sequentially to preprocess data, train the model, evaluate performance, and generate SHAP explanations.

The trained pipeline is saved as rf_pipeline_drugs.joblib for future predictions.

6. Evaluation

Classification report (precision, recall, f1-score)

ROC-AUC score

Feature importance plots

PCA visualization of TF-IDF side effect features

7. Explainability

Uses SHAP to identify which features most influence the model predictions, helping interpret the impact of side effects and medical conditions on drug ratings.
