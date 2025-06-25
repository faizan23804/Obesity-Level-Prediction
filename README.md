Obesity Level Prediction using Machine Learning
This project applies data analysis and machine learning models to predict obesity levels based on physical, lifestyle, and eating habit data. The dataset includes features like BMI, calorie intake, physical activity, water consumption, and family history of obesity.

📁 Dataset
The dataset used is obesity_levels.csv, containing the following:

Input Features: Gender, Age, Height, Weight, family history, physical activity, water intake, etc.

Target: NObeyesdad – the class label representing different levels of obesity (e.g., normal weight, overweight, obesity type I/II/III)

📊 Exploratory Data Analysis
The notebook includes:

Descriptive statistics using .info() and .describe()

Correlation heatmap of features

Feature distribution plots

Boxplots and barplots of each feature grouped by obesity level

🧪 Machine Learning Models
Two Support Vector Classifier (SVC) models are used:

SVC with default kernel (RBF)

SVC with linear kernel

Steps performed:

Train/test split (train_test_split)

Feature scaling (StandardScaler)

Model training and prediction

Evaluation using:

Accuracy score

Confusion matrix

Classification report
