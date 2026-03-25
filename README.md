# Students-performance-linear-regression
Student Performance Prediction Using Linear Regression
📌 Project Overview

This project predicts student math scores based on academic and demographic features using Linear Regression.
It helps understand how factors like reading score, writing score, gender, and test preparation influence student performance.

🎯 Objectives
Analyze student performance data
Build a Linear Regression model
Predict math scores based on input features
Evaluate model performance using regression metrics

🧠 Algorithm Used
Linear Regression

📊 Dataset
Dataset Name: StudentsPerformance.csv
Source: Student academic performance dataset
Features Used:
Gender
Test Preparation Course
Reading Score
Writing Score
Target Variable:
Math Score

⚙️ Technologies & Tools
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook

🔄 Project Workflow
Load the dataset
Perform data preprocessing
Convert categorical values into numerical format
Split data into training and testing sets
Train the Linear Regression model
Take user input for prediction
Predict math score
Evaluate the model using R² score

📈 Model Performance
R² Score: ~0.88
The model predicts student performance with good accuracy and low error.

🧪 Sample Input
Gender: Female (1)
Test Preparation Course: Completed (1)
Reading Score: 72
Writing Score: 75

📤 Sample Output
Predicted Math Score: 74.23

📁 Project Structure
Student_Performance_Analysis/
│
├── data/
│   └── StudentsPerformance.csv
├── src/
│   └── student_performance_linear_regression.py
├── notebook/
│   └── mark_linear.ipynb
├── README.md
└── requirements.txt

▶️ How to Run the Project

Install required libraries

pip install -r requirements.txt

Run the Python file

python student_performance_linear_regression.py
Enter student details when prompted

🗣️ Conclusion

This project demonstrates how Linear Regression can be applied to predict student performance effectively.
It serves as a beginner-friendly machine learning project suitable for academic and resume purposes.

📌 Author

Bhuvaneshwari
