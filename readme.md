# 📊 ElevateLabs - Task 3: Linear Regression

**Author:** Rohith S D  
**Repository:** [Rohith0750/ElevateLabs](https://github.com/Rohith0750/ElevateLabs)  

---

## 🎯 Objective
This project implements **Linear Regression** with `scikit-learn`.  
It covers:
- Loading and preprocessing `Housing.csv`
- Training and testing a regression model
- Evaluating model performance with MAE, MSE, R²
- Plotting regression fits and interpreting coefficients

---

## 🧠 What You'll Learn
✅ Train/test splits with `scikit-learn`  
✅ Fit a `LinearRegression` model  
✅ Assess model with MAE, MSE, R²  
✅ Encode categorical variables  
✅ Plot actual vs. predicted prices  

---

## 🛠️ Tech Stack
| Badge |
|--------|
| ![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) |
| ![Pandas](https://img.shields.io/badge/Pandas-Dataframe-150458?logo=pandas) |
| ![NumPy](https://img.shields.io/badge/NumPy-Arrays-013243?logo=numpy) |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting-11557C?logo=plotly) |
| ![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikit-learn) |

---

## 📂 Dataset
| Column             | Description                                |
|--------------------|--------------------------------------------|
| price              | Target — price of the house               |
| area               | Total area of the house                    |
| bedrooms          | Number of bedrooms                         |
| bathrooms         | Number of bathrooms                        |
| stories            | Number of stories                         |
| mainroad           | Whether on the main road                 |
| guestroom          | Whether the house has a guestroom         |
| basement           | Whether the house has a basement          |
| hotwaterheating    | Hot water heating available?             |
| airconditioning    | Air conditioning installed?               |
| parking            | Number of parking spots                  |
| prefarea           | Preferred area?                          |
| furnishingstatus   | Furnishing status                        |

---

## 🚀 Steps Implemented
1. Load data with `pd.read_csv()`
2. Convert categorical columns into dummy variables
3. Split into training & testing sets
4. Fit a `LinearRegression` model
5. Evaluate using MAE, MSE, R²
6. Interpret coefficients
7. Visualize area vs price regression fit

---

## 📈 Sample Output
MAE: 526312.45
MSE: 1.23e+12
R² Score: 0.89

=== Coefficients ===
Intercept: 1234567.89
area: 2123.45
bedrooms: -51234.56


---

## 🎯 Interview Prep
| Question                                          | Answer                                                                 |
|----------------------------------------------------|-------------------------------------------------------------------------|
| What assumptions does linear regression make?     | Linearity, independence of errors, homoscedasticity, no multicollinearity, errors normally distributed. |
| What is the R² score and its significance?         | Proportion of variance explained by the model — closer to 1 is better. |
| MAE vs MSE — when to prefer one?                    | MAE is robust to outliers; MSE penalizes larger errors more.          |
| What is multicollinearity?                         | High correlation between independent variables.                        |
| Difference between simple and multiple regression? | 1 feature vs multiple features.                                        |
| Can linear regression be used for classification?  | No — use logistic regression for classification tasks.                 |

---

## 🧑‍💻 Author
**Rohith S D** — [GitHub Profile](https://github.com/Rohith0750)

---

## 📜 License
This project is licensed under the MIT License.

---

# 💡 _Happy Coding & Learning!_
