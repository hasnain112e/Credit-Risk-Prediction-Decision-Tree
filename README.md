# Credit-Risk-Prediction-Decision-Tree
A machine learning project to predict credit risk (High Risk / Low Risk) using a Decision Tree Classifier. The project uses the German Credit dataset to train a classification model, evaluates it with accuracy, precision, recall, and F1-score, and visualizes the decision tree for interpretability.
# Credit Risk Prediction - Decision Tree Classifier

## 📌 Project Overview
This project predicts whether a person is a **high-risk** or **low-risk** borrower based on their financial profile using a **Decision Tree Classifier**.  
It uses the **German Credit dataset** and applies supervised learning techniques for binary classification.

## 📊 Dataset
- **File:** GermanData_Credit.csv
- **Features:** Age, Income, LoanAmount, CreditHistory
- **Target:** Defaulted (0 = Low Risk, 1 = High Risk)

## 🚀 Steps Performed
1. Load dataset from CSV
2. Clean and preprocess data (encode categorical variables if needed)
3. Split data into train/test sets (70% train, 30% test)
4. Train **Decision Tree Classifier** (criterion = 'entropy', max_depth = 3)
5. Predict credit risk for test set
6. Evaluate using **Confusion Matrix** and **Classification Report**
7. Visualize decision tree with `plot_tree`

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📈 Output
- **Confusion Matrix** showing classification results
- **Classification Report** with accuracy, precision, recall, and F1-score
- **Decision Tree Diagram** for model interpretability

## 🔧 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/Credit-Risk-Prediction-Decision-Tree.git

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Run the Python script
python credit_risk_decision_tree.py
