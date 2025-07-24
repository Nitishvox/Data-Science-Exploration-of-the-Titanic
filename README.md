# 🛳️ Titanic Survival Prediction
![Titanic Centennial](https://www.usni.org/sites/default/files/styles/hero_image/public/magazine_uploads/images/ProtasioFOMA12.jpg?itok=8aFRMKPz)

A data science project analyzing the Titanic dataset to uncover survival patterns and build predictive models using Python.

---

## Project Overview

This project applies statistical analysis and machine learning to the Titanic passenger dataset. It includes data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling using Logistic Regression and Random Forest.

---

## Files Included

- `train.csv`: Main dataset with passenger details and survival labels.
- `titanic_model.ipynb`: Jupyter Notebook with all code — from EDA to model evaluation.
- `USAGE.md`: Instructions for installing dependencies and running the notebook.
- `README.md`: This project overview file.

---

## 🔍 Tools & Technologies

| Tool           | Purpose                                |
|----------------|----------------------------------------|
| Python         | Core programming language              |
| Pandas         | Data cleaning and manipulation         |
| NumPy          | Numerical computations                 |
| Seaborn        | Statistical data visualization         |
| Matplotlib     | Basic plotting                         |
| Plotly         | Interactive visualization              |
| Scikit-learn   | Machine learning models and evaluation |

---

## 🧪 Models Used

- **Logistic Regression** — baseline classification
- **Random Forest** — ensemble method for improved accuracy
- **Gradient Boosting** — enhanced decision trees

---

## 📊 Highlights

- Handled missing values in `Age`, `Embarked`, and `Cabin`.
- Visualized key survival trends (gender, class, age).
- Achieved ~80% accuracy with Random Forest model.
- Built interactive prediction logic based on custom passenger input.
- Displayed model results with a Plotly heatmap.

---

## How to Run

1. Launch Jupyter Notebook.
2. Open `titanic_model.ipynb`.
3. Run cells in sequence to see analysis and predictions.
4. Use input cells to simulate survival predictions.

---

## Author

**Name:** Nitish M.  
**Role:** Undergraduate Student – Data Science  
**Focus Areas:** Classification, Exploratory Analysis, ML Modeling, Data Storytelling

---

## Future Work

- Hyperparameter tuning and cross-validation
- Advanced feature extraction (e.g., extracting titles from names)
- Deployment as a web app using Streamlit or FastAPI
