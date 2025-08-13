📄 Project Title
Predicting Salary Based on Experience — Linear Regression (Small Project)

📌 Overview
This project demonstrates the implementation of Simple Linear Regression using scikit-learn to predict salary based on years of experience.
The dataset is small (10 records) and was created for practice purposes to understand regression basics, evaluation metrics, and visualization.

📊 Dataset
Experience (Years)	Salary (₹)
1	15000
2	20000
3	25000
4	30000
5	32000
6	45000
7	55000
8	58000
9	65000
10	75000

Source: Synthetic (self-created)
Size: 10 rows × 2 columns

⚙️ Technologies Used
Python 3

NumPy

Pandas

Matplotlib

scikit-learn

🧠 Steps Performed
Created the dataset manually using Pandas.

Split data into training and testing sets (train_test_split).

Implemented Simple Linear Regression using LinearRegression from scikit-learn.

Evaluated the model using:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Visualized the regression line with Matplotlib.

📈 Results
MSE: 2426166.76

RMSE: 1557.61

R² Score: 0.9952

The regression line fits the data very closely, with R² ≈ 99.5%.

📷 Output Graph

Blue points: Actual data, Red line: Predicted regression line

🚀 How to Run
bash
Copy
Edit
# Clone repository
git clone <your-repo-link>

# Navigate to project folder
cd <project-folder>

# Install dependencies
pip install numpy pandas matplotlib scikit-learn

# Run Jupyter Notebook or Python script
📌 Note
This is a practice project for learning purposes and uses a very small synthetic dataset. In real-world scenarios, larger datasets and feature engineering are needed for robust predictions.
