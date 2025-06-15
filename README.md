#  Titanic Dataset - Exploratory Data Analysis (EDA)

This project presents an in-depth Exploratory Data Analysis (EDA) of the Titanic dataset from Kaggle. The goal is to uncover patterns and relationships that influenced survival outcomes.

---

##  Files in This Project

- `Titanic_EDA.ipynb` – Main Jupyter Notebook containing the entire analysis
- `train.csv` – Training dataset
- `test.csv` – Test dataset
- `README.md` – Project documentation

---

##  Dataset Description

- **Source**: [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic)
- **Features** include: `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## Analysis Workflow

1. **Data Overview** – shape, columns, types, missing values
2. **Data Cleaning** – handling missing values and anomalies
3. **Univariate Analysis** – distribution of individual variables
4. **Bivariate Analysis** – relationships with survival
5. **Correlation Heatmap** – numeric feature relationships
6. **Categorical Analysis** – survival based on class, sex, embarkation
7. **Age Binning & Family Size Features** – feature engineering

---

##  Key Insights

- Females had much higher survival rates than males.
- 1st-class passengers had the highest survival probability.
- Children (age < 10) had improved survival chances.
- Port of Embarkation impacted survival rates.
- Passengers traveling alone had a lower survival rate.

---

##  Technologies Used

- Python (Jupyter Notebook)
- `pandas` for data manipulation
- `numpy` for numerical computation
- `matplotlib` and `seaborn` for visualization

---

##  Future Enhancements

- Feature engineering (Title extraction, cabin processing)
- Build predictive ML models (e.g., Logistic Regression, Random Forest)
- Model evaluation and hyperparameter tuning

---

##  Author

**Dhara**  
GitHub: [@Dhara121](https://github.com/Dhara121)

---

## 📄 License

This project is licensed under the MIT License.
