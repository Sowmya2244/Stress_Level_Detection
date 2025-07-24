🧠 Stress Level Detection using Machine Learning
This project focuses on predicting the stress level of individuals based on various health and lifestyle-related features like sleep duration, physical activity, heart rate, etc. It utilizes a machine learning model trained on a publicly available dataset to classify stress levels as low, medium, or high.

📂 Project Structure
stress-level-detection.ipynb: Jupyter notebook containing the full code pipeline — data preprocessing, visualization, model training, evaluation, and prediction.
Sleep_health_and_lifestyle_dataset.csv: Dataset used to train and test the model. Contains multiple lifestyle features relevant to stress prediction.

📊 Dataset Overview
Source: Kaggle

Attributes:
Age, Gender, Sleep Duration, Quality of Sleep
Physical Activity Level, Stress Level
Heart Rate, Daily Steps, Occupation, etc.

🔍 Problem Statement
To build a machine learning model that predicts the stress level (Low/Medium/High) of a person based on various sleep and health-related inputs.

🧪 Machine Learning Workflow
Data Cleaning:
Handling missing values
Encoding categorical variables

Exploratory Data Analysis (EDA):
Correlation heatmaps
Distribution plots
Box plots and count plots

Feature Selection:
Label encoding
Selecting most relevant features
Model Training & Evaluation:

Trained models: Logistic Regression, Random Forest, Decision Tree, etc.

Evaluation using accuracy, confusion matrix, classification report

✅ Results
Achieved high accuracy in classifying stress levels.

Identified key stress indicators like:
Sleep quality
Physical activity
Heart rate
Work type

📌 Requirements
1) Install the required Python libraries:
pip install pandas numpy matplotlib seaborn scikit-learn
🚀 How to Run
1) Clone the repo:
git clone https://github.com/your-username/stress-level-detection.git
cd stress-level-detection

2) Run the Jupyter Notebook:
jupyter notebook stress-level-detection.ipynb
