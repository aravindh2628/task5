🧠 Task 5: Decision Trees and Random Forests

This project focuses on building machine learning models (Decision Tree and Random Forest) to classify heart disease presence using the Heart Disease dataset.

📌 Objective

Learn and apply tree-based models for classification & regression using:

Decision Tree Classifier

Random Forest Classifier

🛠️ Tools Used

Python

Scikit-learn

Seaborn & Matplotlib

Graphviz (for tree visualization)

📁 Dataset

Heart Disease Dataset

Make sure to place the dataset as heart.csv in your project directory.

🔍 How It Works

Data Loading: Load heart.csv into a pandas DataFrame.

Preprocessing: Separate features and target, split into training/testing sets.

Modeling:

Train a Decision Tree model and visualize it using Graphviz.

Train a Random Forest and compare accuracy.

Evaluation:

Accuracy and classification report for both models.

Feature importance plotted.

5-fold Cross-validation to assess performance stability.

📊 Visual Outputs

Decision tree visualization (via Graphviz)

Feature importance plot (Random Forest)

🚀 How to Run

Clone the repository

Install required packages:

bash

pip install -r requirements.txt

Make sure Graphviz is installed:

bash

sudo apt-get install graphviz   # (Linux)

Run the notebook:

nginx


jupyter notebook TASK_5.ipynb

📚 What You'll Learn

How Decision Trees work

Benefits of Random Forests over single trees

How to prevent overfitting

Visualizing model decision logic

Importance of each feature

