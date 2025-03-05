# 📊 Assignment 2 - Polynomial Regression & Logistic Regression

##  **Author:** Yazeed Hamdan  
---

##  Overview
This project focuses on:
- **Polynomial Regression** with **degree tuning** and **regularization**.
- **Logistic Regression** with both **linear and quadratic decision boundaries**.
- **Model Evaluation using Mean Squared Error (MSE) & Accuracy Metrics**.
- **3D Visualization of Training, Validation, and Test Sets**.

The dataset is split into:
- **Training Set:** First 120 examples.
- **Validation Set:** Next 40 examples.
- **Test Set:** Last 40 examples.

---

## 📂 Files
- `YazeedHamdan1201133Assignment2.ipynb` - Contains the full **Jupyter Notebook implementation** of the assignment.
- `data.csv` (if applicable) - Dataset used for training and evaluation.

---

## 🚀 Steps Performed

### **📌 Part 1: Data Splitting & 3D Visualization**
- The dataset is **read from a CSV file** and **split into training, validation, and test sets**.
- A **3D scatter plot** visualizes:
  - Feature relationships
  - Distribution of the dataset across three-dimensional space.
- This visualization helps **understand data spread and feature interactions**.

---

### **📌 Part 2: Polynomial Regression Model Selection**
- **Polynomial regression models (degrees 1 to 10) were trained**.
- **Mean Squared Error (MSE) was calculated** on the validation set.
- A **plot of Validation MSE vs. Polynomial Degree** was generated.
- The **optimal model** is selected based on the **lowest validation MSE**.
- **Best Polynomial Degree:**  **2**  
  - Validation MSE at Degree 2: **0.1799**
- The polynomial regression model was **visualized as a 3D surface plot**.

---

### **📌 Part 3: Regularization Parameter Selection**
- Different **regularization values (λ)** were tested: `{0.001, 0.005, 0.01, 0.1, 10}`
- The **log-scale plot** of Validation MSE vs. Regularization parameter was created.
- **Best λ (regularization parameter) chosen:** **0.01** (Lowest MSE).

---

### **📌 Part 4: Logistic Regression with Decision Boundaries**
#### **1️⃣ Linear Decision Boundary**
- **Logistic Regression (Linear)** was trained using `sklearn`'s implementation.
- **Decision boundary was plotted** on a scatterplot of the training set.
- **Training & Testing Accuracy were computed**.

#### **2️⃣ Quadratic Decision Boundary**
- The experiment was **repeated using a quadratic decision boundary**.
- **Comparison of linear vs. quadratic models** in terms of accuracy.

---

## 📊 Visualizations
The following plots were generated:
- **3D Scatter Plot**: Data distribution across training, validation, and test sets.
- **Validation MSE vs. Polynomial Degree**: Helps in selecting the best model.
- **3D Surface Plot**: Shows predictions for the best polynomial model.
- **Log-Scale Plot**: Validation MSE vs. Regularization Parameter.
- **Logistic Regression Decision Boundaries**: Linear vs. Quadratic.

---

## 🛠 Technologies Used
- **Python** 
- **Jupyter Notebook** 
- **pandas** 
- **numpy** 
- **matplotlib** 
- **seaborn** 
- **scikit-learn** 

---

## 📎 How to Run the Code?

### 1️⃣ Install Required Libraries
Ensure you have the required Python libraries installed. If not, run:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```
### 2️⃣ Run the Jupyter Notebook
Launch Jupyter Notebook and open the assignment:

```sh
jupyter notebook YazeedHamdan1201133Assignment2.ipynb
```

## 📫 Contact
For any questions or discussions, feel free to reach out:

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yazedyazedl2020@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/yazeed-hamdan-59b83b281/)  
