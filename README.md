# 🧠 Regression Models in Python

This project demonstrates 7 types of regression models using Python and scikit-learn in a Jupyter Notebook. Each model is trained on synthetic data, evaluated using Mean Squared Error (MSE), and saved as a `.pkl` file.

---

## 📊 Models Implemented

1. Linear Regression  
2. Polynomial Regression  
3. Ridge Regression  
4. Lasso Regression  
5. Elastic Net Regression  
6. Decision Tree Regression  
7. Random Forest Regression  

---

## ⚙️ Tech Stack

- Python 3.x  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib  
- Joblib  
- Jupyter Notebook  

---

## 🚀 How to Run

1. **Clone Repo**  
   `git clone https://github.com/your-username/regression-model.git`

2. **Install Dependencies**  
   `pip install numpy pandas scikit-learn matplotlib joblib`

3. **Run Notebook**  
   `jupyter notebook regression_models.ipynb`

Models will be saved in:  
`C:\Users\ranji\OneDrive\Desktop\regression model` (you can change this in the notebook)

---

## 💾 Load a Saved Model

```python
import joblib
model = joblib.load('path/to/model.pkl')
prediction = model.predict([[value]])
