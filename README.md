# 🧠 Stress Level Detection using Machine Learning

This project focuses on predicting the **stress level** of individuals based on various health and lifestyle-related features like sleep duration, physical activity, heart rate, etc. It utilizes a machine learning model trained on a publicly available dataset to classify stress levels as **Low**, **Medium**, or **High**.



## 📁 Files Included

- `stress-level-detection.ipynb`: Jupyter Notebook with full pipeline (EDA → preprocessing → model training → evaluation).
- `Sleep_health_and_lifestyle_dataset.csv`: Dataset used for training and testing.



## 📊 Dataset Overview

- **Source**: Sleep and lifestyle-related data
- **Features Include**:
  - `Age`, `Gender`, `Occupation`, `Sleep Duration`, `Quality of Sleep`
  - `Physical Activity Level`, `Heart Rate`, `Daily Steps`, `BMI`
  - Target: `Stress Level` (Low / Medium / High)



## 💡 Project Workflow

### 🔹 1. Data Preprocessing
- Handled missing values
- Performed label encoding for categorical data
- Dropped irrelevant columns (`Person ID`, etc.)

### 🔹 2. Exploratory Data Analysis
- Visualizations using **Seaborn** and **Matplotlib**
  - Count plots, heatmaps, distribution plots
- Identified correlations between features and stress level

### 🔹 3. Model Building
- Split dataset using `train_test_split()`
- Trained model: ✅ **Random Forest Classifier**
- Evaluation Metrics:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report


## ✅ Results

- High accuracy achieved in predicting stress level
- Key indicators of stress:
  - Heart Rate
  - Sleep Quality
  - Physical Activity Level



## 🧪 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestClassifier, train_test_split, etc.)



## 📌 How to Run Locally

1. Clone the repository:
   git clone https://github.com/your-username/stress-level-detection.git
   cd stress-level-detection
Install dependencies:
pip install -r requirements.txt
(Or individually: pandas, numpy, matplotlib, seaborn, scikit-learn)

Run the notebook:
jupyter notebook stress-level-detection.ipynb
