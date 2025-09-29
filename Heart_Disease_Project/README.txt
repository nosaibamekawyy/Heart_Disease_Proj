Heart Disease Prediction Project

Overview: This project aims to analyze and predict the likelihood of heart disease based on patient data using machine learning techniques. It explores various algorithms, data preprocessing methods, and evaluation metrics to build an accurate predictive model.

Project Structure: Heart_Disease_Project/ │-- data/ # Dataset(s) used │-- notebooks/ # Jupyter notebooks with analysis │-- src/ # Source code (data preprocessing, models, utils) │-- results/ # Output files, graphs, evaluation results │-- README.md # Project documentation │-- requirements.txt # Dependencies

Requirements: Python 3.x Jupyter Notebook (optional) Required libraries: pip install -r requirements.txt

Typical dependencies: numpy pandas matplotlib / seaborn scikit-learn

Usage

Clone this repository:

git clone https://github.com/nosaibamekawyy/Heart_Disease_Proj.git cd Heart_Disease_Project

Install dependencies:

pip install -r requirements.txt

Run Jupyter notebooks:

jupyter notebook notebooks/

Or execute the main script (if available):

python src/main.py

Models Implemented: Logistic Regression Decision Tree Random Forest Support Vector Machine (SVM) K-Nearest Neighbors (KNN)

Performance is evaluated using:

Accuracy Precision Recall F1-Score ROC-AUC