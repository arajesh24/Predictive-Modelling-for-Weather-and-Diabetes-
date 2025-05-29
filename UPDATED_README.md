
# Predictive Modelling for Weather and Diabetes

This project explores the use of machine learning techniques—**Decision Tree** and **Multi-Layer Perceptron (MLP)**—to predict outcomes on two distinct datasets: weather conditions and diabetes diagnosis.

## 📁 Project Structure
```
├── Weather_Prediction
│   ├── Weather_DecisionTree.ipynb           # Weather prediction using Decision Tree
│   ├── Weather_MLP.ipynb                    # Weather prediction using MLP
│
├── Diabetes_Prediction
│   ├── Diabetes_DecisionTree.ipynb          # Diabetes prediction using Decision Tree
│   ├── Diabetes_MLP.ipynb                   # Diabetes prediction using MLP
```

## 🎯 Objective
To compare and evaluate two classification models (Decision Tree and MLP) across weather and medical datasets, focusing on prediction accuracy, model complexity, and generalizability.

## 🧪 Models Used
- **Decision Tree Classifier**
- **Multi-Layer Perceptron (MLP)**

Each model was applied to:

- 🌦️ **Weather Data**: Predicting rainy vs. non-rainy days
- 🩺 **Diabetes Data**: Predicting the likelihood of diabetes diagnosis

## ⚙️ Tools & Technologies
- Python 3.x
- Jupyter Notebooks
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## 📊 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- ROC Curve (where applicable)

## 📝 Summary of Results
| Dataset   | Model         | Accuracy (approx) |
|-----------|----------------|------------------|
| Weather   | Decision Tree  | 80–90%           |
| Weather   | MLP            | 85–92%           |
| Diabetes  | Decision Tree  | 75–85%           |
| Diabetes  | MLP            | 80–90%           |

## 🧠 Key Learnings
- Decision Trees are interpretable and effective for quick predictions.
- MLPs provide higher accuracy but require more computational resources.
- Feature scaling and data preprocessing were crucial for MLP performance.

## 🚀 Setup Instructions

### 1. Download the Repository
- Click the "Download" button on the repository page.
- Select **Download ZIP**.
- Extract the downloaded ZIP file to your desired location.

### 2. Running the Project
- Open your terminal or Anaconda prompt.
- Launch Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
- In the Jupyter interface, navigate to the project directory.
- Open and run the notebook files.

### 3. Troubleshooting
- Ensure Jupyter Notebook is installed.
- Check if you're in the correct directory.
- Verify that all required Python packages are installed.
- Modify file paths in the notebook if needed.

## 👨‍💻 Author
Rajesh A  
MSc Data Science  
[GitHub Profile](https://github.com/arajesh24)
