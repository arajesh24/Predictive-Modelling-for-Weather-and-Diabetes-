
# Predictive Modelling for Weather and Diabetes

This project delves into the application of various machine learning algorithms to predict weather conditions and diabetes diagnoses. By leveraging datasets pertinent to each domain, we aim to compare model performances and derive insights that can aid in accurate predictions.

## 📁 Project Structure

```
├── Weather_Prediction
│   ├── Bayesian_Algorithm.ipynb                 # Weather prediction using Naive Bayes
│   ├── MLDM_KNN_Model_Weather.ipynb             # Weather prediction using KNN
│   └── Weather_Dataset.csv                      # Dataset for weather prediction
│
├── Diabetes_Prediction
│   ├── Bayesian_Algorithm_Diabetes.ipynb        # Diabetes prediction using Naive Bayes
│   ├── MLDM_KNN_Model_Diabetes.ipynb            # Diabetes prediction using KNN
│   └── Diabetes_Dataset.csv                     # Dataset for diabetes prediction
│
├── README.md                                    # Project documentation
└── LICENSE                                      # License information
```

## 📊 Datasets

### Weather Dataset

- **Source**: [Specify the source or indicate if it's a synthetic dataset]
- **Features**: [List key features, e.g., Temperature, Humidity, Wind Speed]
- **Target**: [Specify the target variable, e.g., Rain (Yes/No)]

### Diabetes Dataset

- **Source**: [Specify the source, e.g., Pima Indians Diabetes Database]
- **Features**: [List key features, e.g., Glucose, BMI, Age]
- **Target**: [Specify the target variable, e.g., Diabetes (Positive/Negative)]

## 🧠 Machine Learning Models

For both weather and diabetes prediction tasks, the following algorithms were employed:

- **Naive Bayes Classifier**: A probabilistic classifier based on Bayes' theorem with strong independence assumptions.
- **K-Nearest Neighbors (KNN)**: A non-parametric method used for classification by comparing the proximity of data points.

## 📈 Model Evaluation

Each model's performance was assessed using the following metrics:

- **Accuracy**: Proportion of correct predictions over total predictions.
- **Precision**: Proportion of true positive predictions over all positive predictions.
- **Recall**: Proportion of true positive predictions over all actual positives.
- **F1 Score**: Harmonic mean of precision and recall.

*Note: Detailed evaluation results, including confusion matrices and ROC curves, are available within the respective Jupyter notebooks.*

## 🛠️ Getting Started

To replicate the analyses:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/arajesh24/Predictive-Modelling-for-Weather-and-Diabetes-.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Predictive-Modelling-for-Weather-and-Diabetes-
   ```
3. **Install required packages**:
   Ensure you have Python 3.x installed. Then, install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the notebooks**:
   Open the Jupyter notebooks in your preferred environment to explore the analyses.

## 📚 References

- [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Weather Dataset Source](#) *(Please specify the actual source)*

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
