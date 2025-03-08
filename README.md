Student Performance Factors Analysis

📌 Project Overview

This project analyzes the factors affecting student performance using a dataset of 6,607 entries with 20 features. The goal is to identify key determinants that influence students' exam scores and build predictive models to estimate performance.

📂 Dataset Information

The dataset contains information on various academic, social, and personal factors, including:

Column Name

Description

Hours_Studied

Number of hours a student studies daily

Attendance

Student attendance record

Parental_Involvement

Level of parental involvement in education (Low/Medium/High)

Access_to_Resources

Availability of learning resources (Yes/No)

Extracurricular_Activities

Participation in extracurricular activities (Yes/No)

Sleep_Hours

Average sleep hours per night

Previous_Scores

Past academic performance

Motivation_Level

Student's motivation level (Low/Medium/High)

Internet_Access

Availability of internet access (Yes/No)

Tutoring_Sessions

Number of tutoring sessions attended

Family_Income

Family's income level (Low/Medium/High)

Teacher_Quality

Perceived quality of teachers (Low/Medium/High)

School_Type

Type of school (Public/Private)

Peer_Influence

Influence of peers on studies (Positive/Negative/Neutral)

Physical_Activity

Hours spent on physical activities per week

Learning_Disabilities

Presence of learning disabilities (Yes/No)

Parental_Education_Level

Highest education level of parents

Distance_from_Home

Distance of school from home (Near/Far)

Gender

Student's gender

Exam_Score

Target variable: Student's exam score

🛠️ Technologies Used

Python for data analysis and modeling

Pandas & NumPy for data processing

Matplotlib & Seaborn for visualization

Scikit-Learn for machine learning

🔍 Key Steps in Analysis

1️⃣ Data Preprocessing

Handling missing values in Teacher_Quality, Parental_Education_Level, and Distance_from_Home.

Encoding categorical variables using One-Hot Encoding & Label Encoding.

Standardizing numerical variables like Hours_Studied, Sleep_Hours, and Physical_Activity.

2️⃣ Exploratory Data Analysis (EDA)

Visualizing correlations between factors like Study Hours, Sleep, Attendance, and Exam Score.

Analyzing distributions of exam scores based on various student attributes.

Boxplots & Histograms to detect outliers in numerical features.

3️⃣ Predictive Modeling

Regression Models to predict exam scores:

Linear Regression

Random Forest Regressor

XGBoost

Classification Models to categorize performance levels:

Decision Tree Classifier

Logistic Regression

Support Vector Machine (SVM)

4️⃣ Model Evaluation

Evaluating performance using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared Score

Confusion Matrix & Accuracy Score (for classification models)

🚀 How to Run the Project

1️⃣ Install Dependencies

pip install pandas numpy scikit-learn matplotlib seaborn xgboost

2️⃣ Run Data Analysis

python data_analysis.py

3️⃣ Train Prediction Model

python train_model.py

📈 Key Findings

Study hours and previous scores are the most influential factors.

Sleep deprivation negatively impacts student performance.

Parental involvement and access to resources significantly boost exam scores.

🔗 Future Improvements

Add deep learning models (ANN, LSTM) for better accuracy.

Improve handling of missing values with advanced imputation techniques.

Deploy the model as a web-based student performance predictor.
