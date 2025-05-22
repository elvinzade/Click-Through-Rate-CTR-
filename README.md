📊 Avazu Click-Through Rate (CTR) Prediction
This repository contains a Jupyter notebook to predict ad click-through rates using the Avazu dataset. It covers data preprocessing, feature engineering, model training with LightGBM, and evaluation using AUC and log loss.

📁 Dataset
To run this notebook, place the Avazu dataset (e.g., train.csv) in the following directory:

/kaggle/input/

This path is the default when running in Kaggle Notebooks. If you are running locally, update the path in the notebook accordingly.

You can download the dataset from the official competition page:
🔗 https://www.kaggle.com/competitions/avazu-ctr-prediction/data

▶️ How to Run
Open ctr_prediction.ipynb.

Ensure the dataset is located in /kaggle/input/.

Run all cells to execute the full pipeline and view results.

All steps, from preprocessing to model evaluation, are included in the notebook.

🧰 Requirements
The notebook is designed to run in the Kaggle environment, which includes all required packages preinstalled:

Python 3.x

pandas

numpy

seaborn

matplotlib

scikit-learn

lightgbm

To run locally, install dependencies using pip:

pip install pandas numpy seaborn matplotlib scikit-learn lightgbm

📌 Features
🔍 Exploratory Data Analysis

⚙️ Feature Engineering

📈 Model Training with LightGBM

🧪 Evaluation using ROC-AUC and Log Loss

🧠 Feature Importance Visualization

📂 Project Structure
.
├── ctr_prediction.ipynb
├── README.md
└── /kaggle/input/
  └── /avazu-ctr-prediction/train.gz (← Place your dataset here)

