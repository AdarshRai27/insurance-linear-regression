# insurance-linear-regression
Predicting medical insurance charges using Linear Regression (EDA, Gradient Descent, Regularization)
Overview

This project aims to predict medical insurance charges based on individual attributes such as age, BMI, smoking status, and region using Linear Regression techniques. The project includes end-to-end implementation from data preprocessing to model evaluation and optimization.

Dataset
Dataset: Medical Cost Personal Dataset (Insurance Dataset)
Target Variable: charges
Features:
Age
Sex
BMI
Number of Children
Smoker Status
Region

⚙️Project Workflow
🔹 1. Exploratory Data Analysis (EDA)
Distribution plots and boxplots
Correlation heatmap
Outlier detection using IQR
🔹 2. Data Preprocessing
Handling missing values (none found)
Encoding categorical variables (One-Hot Encoding)
Feature scaling using StandardScaler
🔹 3. Model Building
Simple Linear Regression (using smoker_yes)
Multiple Linear Regression (using all features)
🔹 4. Gradient Descent (From Scratch)
Implemented manually without sklearn
Optimized parameters using iterative updates
Visualized loss convergence
🔹 5. Model Evaluation
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
🔹 6. Advanced Techniques
Polynomial Regression (degree = 2)
Ridge Regression (L2 Regularization)
Lasso Regression (L1 Regularization)

📈 Results
Training R² Score: ~0.62
Testing R² Score: ~0.56
Model shows moderate predictive performance
Smoking status identified as the most significant feature

📊 Key Insights
Smokers incur significantly higher insurance charges
Age and BMI also influence medical costs
Linear Regression captures general trends but struggles with extreme values
Residual analysis shows signs of non-linearity and heteroscedasticity

🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/insurance-linear-regression.git
Navigate to the project folder:
cd insurance-linear-regression
Install dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook:
jupyter notebook
