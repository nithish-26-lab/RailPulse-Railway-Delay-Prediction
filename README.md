# 🚆 RailPulse – Railway Delay Prediction and Intelligence System

**A Machine Learning project developed as part of INT234 – Predictive Analytics.**

RailPulse is a machine learning-based project that analyses railway data, identifies train arrival delay patterns, predicts arrival delays, and classifies trains into different delay categories using supervised machine learning algorithms.

## 📌 1. Project Overview

Railway delays can affect passenger experience, train schedules, and railway operations. RailPulse explores historical railway data to understand delay patterns and applies machine learning techniques to predict arrival delays.

The project covers data preprocessing, exploratory data analysis, feature engineering, regression, classification, and model evaluation.

## 🎯 2. Project Objectives

- Analyse railway arrival delay patterns.
- Perform data cleaning and preprocessing.
- Identify important patterns and relationships in railway data.
- Predict arrival delay minutes using regression models.
- Classify railway delays into different categories.
- Compare multiple machine learning algorithms.
- Evaluate model performance using different metrics.

## 📂 3. Dataset Information

**Dataset:** Indian Railways Runs

**Source:** [Hugging Face – Indian Railways Runs](https://huggingface.co/datasets/jananisrik/indian-railways-runs)

- Dataset records used: 10,000
- Data format: CSV
- Target variable: `delay_arrival_min`

The dataset contains information such as:
- Train number and train name
- Train type
- Station code
- Scheduled arrival time
- Arrival delay
- Distance travelled
- Latitude and longitude

### Delay Classification

For this project, arrival delays are divided into three categories:

| Delay Duration | Category |
|---|---|
| 15 minutes or less | On-Time |
| 16–60 minutes | Moderate |
| More than 60 minutes | Major |

*Note: These are project-defined thresholds, not official Indian Railways classifications.*

## 🛠️ 4. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning |
| JupyterLab | Development environment |

## 🔍 5. Data Analysis and Visualization

Exploratory Data Analysis (EDA) was performed to understand railway arrival delay patterns and relationships between different variables.

**Visualizations included:**

1. Arrival Delay Distribution
2. Delay Category Distribution
3. Average Delay by Month
4. Correlation Heatmap
5. Actual vs Predicted Delay
6. Regression Model Comparison
7. Classification Model Comparison
8. Confusion Matrix

## 📸 6. Project Visualizations

The following visualizations demonstrate the analysis and model performance.

### Arrival Delay Distribution
![Arrival Delay Distribution](images/delay_distribution.png)

### Delay Category Distribution
![Delay Category Distribution](images/delay_categories.png)

### Average Delay by Month
![Average Delay by Month](images/monthly_delay.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

### Actual vs Predicted Delay
![Actual vs Predicted](images/actual_vs_predicted.png)

### Regression Model Comparison
![Regression Comparison](images/regression_comparison.png)

### Classification Model Comparison
![Classification Comparison](images/classification_comparison.png)

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

## 🤖 7. Machine Learning Algorithms

### Regression Models

Used to predict railway arrival delay in minutes.

- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression

### Classification Models

Used to classify railway arrival delays.

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

## 📊 8. Model Evaluation Metrics

**Regression Metrics:**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

**Classification Metrics:**
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## 📁 9. Project Structure

```text
RailPulse-Railway-Delay-Prediction/
│
├── images/
│   ├── delay_distribution.png
│   ├── delay_categories.png
│   ├── monthly_delay.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   ├── regression_comparison.png
│   ├── classification_comparison.png
│   └── confusion_matrix.png
│
├── railway_dataset_10000.csv
├── RailPulse.ipynb
├── railpulse_regression_results.csv
├── railpulse_classification_results.csv
└── README.md
```

## ⚙️ 10. Installation and Execution

**Step 1: Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/RailPulse-Railway-Delay-Prediction.git
```

**Step 2: Navigate to the project folder**

```bash
cd RailPulse-Railway-Delay-Prediction
```

**Step 3: Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyterlab
```

**Step 4: Launch JupyterLab**

```bash
jupyter lab
```

Open `RailPulse.ipynb` and execute the notebook cells sequentially.

Ensure the dataset CSV file is available in the project directory.

## 💡 11. Key Learning Outcomes

- Practical experience in data preprocessing and EDA.
- Understanding regression and classification algorithms.
- Applying feature engineering techniques.
- Evaluating models using multiple performance metrics.
- Comparing machine learning algorithms.
- Understanding chronological train-test splitting.
- Applying predictive analytics to railway data.

## 🚀 12. Future Enhancements

- Integrate real-time railway data.
- Explore advanced machine learning algorithms.
- Improve prediction performance through hyperparameter tuning.
- Develop an interactive dashboard using Streamlit.
- Extend analysis to route-level and station-level delay patterns.

## 👨‍💻 13. Project Information

| Detail | Information |
|---|---|
| Project Name | RailPulse |
| Project Title | Railway Delay Prediction and Intelligence System |
| Course | INT234 – Predictive Analytics |
| Domain | Data Science and Machine Learning |
| Programming Language | Python |
| Development Environment | JupyterLab |

---

⭐ If you find this project interesting, feel free to explore the repository!

*Built as part of my learning journey in Predictive Analytics and Machine Learning.*
