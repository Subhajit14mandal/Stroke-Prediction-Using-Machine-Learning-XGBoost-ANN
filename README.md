# 🧠 Stroke Prediction using Machine Learning (XGBoost & ANN)

This project explores the use of Machine Learning (ML) and Artificial Neural Networks (ANNs) to predict the likelihood of a stroke based on medical and lifestyle factors.
It leverages XGBoost for gradient boosting and ANNs for deep learning, comparing their performance on a structured health dataset.

📂 Project Structure

DF3.csv — dataset containing patient records and stroke-related attributes

Stroke Prediction using Machine Learning & XGBoost & ANN.ipynb — main notebook with preprocessing, model training, and evaluation

README.md — project documentation (this file)

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/stroke-prediction-ml.git
cd stroke-prediction-ml

2. Install Dependencies

We recommend Python 3.9+. Install requirements with:

pip install -r requirements.txt

3. Run the Notebook

Start Jupyter Notebook:

jupyter notebook


Open Stroke Prediction using Machine Learning & XGBoost & ANN.ipynb and run the cells.

🧪 Methodology

Data Preprocessing

Handle missing values

Encode categorical features

Normalize/standardize numeric features

Handle class imbalance (oversampling/undersampling if needed)

Models

XGBoost — Gradient Boosting framework for structured data

ANN (Artificial Neural Network) — Deep learning model to capture complex relationships

Evaluation

Accuracy, Precision, Recall, F1-score, ROC-AUC

Model comparison (XGBoost vs ANN)

📊 Results

XGBoost and ANN performances are compared across multiple metrics

Insights into which features contribute most to stroke prediction

Observations on class imbalance and strategies to mitigate it

🤝 Contributing

Contributions are welcome!
To contribute:

git checkout -b feature/my-feature
# make changes
git commit -m "Add new experiment: tuned ANN architecture"
git push origin feature/my-feature


Then open a Pull Request.

📜 License


This project is released under the MIT License.
