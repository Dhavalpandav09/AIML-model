# 📊 Employee Salary Prediction using Linear Regression

This project demonstrates a simple **Linear Regression model** to predict an employee's salary (`Salary_INR`) based on their **time spent at the company** using the `Employee_HR.csv` dataset.

---

## 🔧 Technologies Used

- Python
- pandas
- scikit-learn
- matplotlib
- numpy

---

## 📁 Dataset

- **File**: `Employee_HR.csv`
- **Required Columns**:
  - `time_spent_company`
  - `Salary_INR`

> Make sure the CSV file is placed in the same directory as the script.

---

## 🚀 How It Works

1. Load the dataset using pandas.
2. Build a Linear Regression model to predict `Salary_INR` from `time_spent_company`.
3. Visualize:
   - Histogram of `time_spent_company`
   - Scatter plot of actual vs. predicted salary
4. Evaluate the model using:
   - **MAE** (Mean Absolute Error)
   - **MSE** (Mean Squared Error)
   - **RMSE** (Root Mean Squared Error)
   - **R² Score**

---

## 📈 Evaluation Metrics

After training the model, the script prints:

- 📌 **Mean Absolute Error**
- 📌 **Mean Squared Error**
- 📌 **Root Mean Squared Error**
- 📌 **R² Score (Accuracy)**

---

## 📊 Visualizations

- Histogram showing the distribution of `time_spent_company`
- Scatter plot showing actual vs predicted salary with regression line

---

## 🧪 Example Prediction

You can also make a prediction for a new value.  
The script includes this example:

```python
new_time = 9
predicted_new_score = model.predict([[new_time]])
print(f"Predicted salary for {new_time} years: {predicted_new_score}")
