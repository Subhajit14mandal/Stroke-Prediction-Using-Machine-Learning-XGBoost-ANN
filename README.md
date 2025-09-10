# 🧠 Stroke Prediction using Machine Learning (XGBoost & ANN)

![Project Thumbnail](./Copilot_20250910_125408.png)

This project explores the use of Machine Learning (ML) and Artificial Neural Networks (ANNs) to predict the likelihood of a stroke based on medical and lifestyle factors.
It leverages XGBoost for gradient boosting and ANNs for deep learning, comparing their performance on a structured health dataset.

---

## 📂 Project Structure

`DF3.csv` — dataset containing patient records and stroke-related attributes

`Stroke Prediction using Machine Learning & XGBoost & ANN.ipynb` — main notebook with preprocessing, model training, and evaluation

`README.md` — project documentation (this file)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/stroke-prediction-ml.git
cd stroke-prediction-ml
```

### 2. Install Dependencies

We recommend Python *3.9+*. Install requirements with:
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Start Jupyter Notebook:
```bash
jupyter notebook
```

Open `Stroke Prediction using Machine Learning & XGBoost & ANN.ipynb` and run the cells.
---
## 🧪 Methodology

### 1. Data Preprocessing

- Handle missing values

- Encode categorical features

- Normalize/standardize numeric features

- Handle class imbalance (oversampling/undersampling if needed)

### 2. Models

**Baseline Machine Learning Models**

- Logistic Regression

- Decision Tree Classifier

- Random Forest Classifier

- Support Vector Machine (SVM)

- K-Nearest Neighbors (KNN)

**Ensemble & Boosting Models**

- MaxVoting

- Bagging Classifier

- XGBoost (Extreme Gradient Boosting)

**Deep Learning**

- ANN (Artificial Neural Network) with multiple layers

- Hyperparameter tuning (layers, neurons, activation functions, dropout, etc.)

### 3. Evaluation

- Accuracy

- Precision

- Recall

- F1-score

- ROC-AUC

- Confusion Matrix
  
- Model comparison (XGBoost vs ANN)

---

## 📊 Results

- XGBoost and ANN performances are compared across multiple metrics

- Insights into which features contribute most to stroke prediction

- Observations on class imbalance and strategies to mitigate it

---

## 🤝 Contributing

Contributions are welcome!
To contribute:

```bash
git checkout -b feature/my-feature
# make changes
git commit -m "Add new experiment: tuned ANN architecture"
git push origin feature/my-feature
```

Then open a Pull Request.

---

📜 License

This project is released under the MIT License.

---

## 🎨 Thumbnail Design

The thumbnail combines:
- A **stylized brain** to represent the medical domain.
- An **overlaid graph** symbolizing machine learning insights.
- A **split layout**: one side for XGBoost (tree structure), the other for ANN (neural network).
- A **color palette** of muted teal and vibrant orange-red for contrast and clarity.

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/stroke-prediction-ml.git
cd stroke-prediction-ml
pip install -r requirements.txt


