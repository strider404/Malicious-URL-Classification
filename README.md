# 🛡️ Malicious URL Classification using Machine Learning

## 📖 Overview
* Applies Machine Learning to classify URLs into two categories: benign (safe) and malicious (harmful).
* Utilizes lexical feature analysis for automated detection, bypassing the need for signature-based databases.

## 📊 Dataset
* Total samples: 651,191 URLs.
* Labels: `benign` (0) and `malicious` (1).
* Original Data Source: https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset

## 🔍 Feature Engineering
* Overall URL length (`url_length`).
* Count of dots (`count_dot`).
* Presence of "www" (`count_www`).
* Count of directory levels (`count_directories`).
* Length of the first directory (`first_dir_length`).
* Connection protocol (`http` and `http_secure`).

## 🤖 Model & Results
* Model used: Decision Tree Classifier.
* Data Split: 80% Train - 20% Test.
* Accuracy: 96.15%
* Precision: 96.02%
* Recall: 95.27%
* F1-Score: 95.63%

## 📁 Project Structure
* `notebooks/malicious_url.ipynb`: Main source code (Data Preprocessing, Feature Engineering, and Model Training).
* `models/`: Directory for saved models.
* `data/`: Directory for raw data.
* `requirements.txt`: List of Python dependencies.

## 🚀 Installation & Usage
1. Clone the repository: `git clone https://github.com/strider404/Malicious-URL-Classification.git`
2. Navigate to the directory: `cd Malicious-URL-Classification`
3. Install dependencies: `pip install -r requirements.txt`
4. Open and run `notebooks/DS.ipynb`.
