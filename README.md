# student-performance-prediction
“Predicting student grades using Linear Regression and Random Forest with visualization of feature importance.”
---------------------------------------------------------------------------
📊 Dataset
Source: Kaggle - [Math Students Performance Data](https://www.kaggle.com/datasets/adilshamim8/math-students?resource=download)
---------------------------------------------------------------------------
🛠 How to Run
1. Clone the repo: 
  git clone https://github.com/yourusername/student-performance-prediction.git
  cd student-performance-prediction
2. Download the dataset from Kaggle using the link above and place it in the project folder.
3. Install dependencies:
   pip install -r requirements.txt
4. Run the Jupyter Notebook:
   jupyter notebook Student_Performance_Prediction.ipynb
---------------------------------------------------------------------------
⚙️ Technologies Used
Python 3
Pandas, NumPy (data processing)
Scikit-learn (machine learning)
Matplotlib, Seaborn (visualization)
---------------------------------------------------------------------------
🚀 Steps in the Project
Data Loading & Cleaning
Load student performance dataset.
Handle categorical and numerical features.
Exploratory Data Analysis (EDA)
Correlation heatmap of features.
Distribution of grades (G1, G2, G3).
Model Building
Linear Regression
Random Forest Regressor
Evaluation
Mean Squared Error (MSE)
R² Score
Visualization of predicted vs actual grades
Feature Importance
Identify which factors most affect student performance.
---------------------------------------------------------------------------
📈 Results
Linear Regression: Provides a baseline performance.
Random Forest: Outperforms linear regression with higher accuracy.
Key Factors: G1, G2 (previous grades), studytime, absences.
