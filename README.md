🏥 Health Score Prediction - Regression Project
This project uses a synthetic health dataset to predict an individual's health score based on various lifestyle and physiological factors using Linear Regression.
📁 Dataset Description
The dataset includes the following features:

Column	Description
Age	Age of the individual (in years)
BMI	Body Mass Index
Exercise_Frequency	Number of times the person exercises per week
Diet_Quality	Quality of diet (on a scale of 1–5)
Sleep_Hours	Average hours of sleep per day
Smoking_Status	Smoking status (0 = Non-smoker, 1 = Smoker)
Alcohol_Consumption	Units of alcohol consumed per week
Health_Score	Overall health score (target variable)

🧠 Problem Statement
Build a regression model that predicts the Health_Score using other health-related indicators. The goal is to:
Analyze patterns between lifestyle choices and health outcomes
Use Linear Regression to predict health scores
Evaluate model performance

⚙️ Tech Stack
Python
Pandas & NumPy – data handling
Seaborn & Matplotlib – visualization
Scikit-learn – model building, training, evaluation

🔍 EDA Highlights
Checked for nulls, duplicates, data types
Detected and handled outliers using IQR
Explored relationships between features and health score via scatter plots and boxplots

📊 Model Performance
Model: Linear Regression
Metric	Value
MSE	30.29
R² Score	0.8376

