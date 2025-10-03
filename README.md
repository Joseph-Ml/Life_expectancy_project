 Life Expectancy Project

This project explores the factors influencing life expectancy using data science techniques. The analysis integrates statistical methods, exploratory data visualization, feature engineering, and predictive modeling to evaluate and forecast life expectancy outcomes.


## Tools & Libraries Used

* Pandas → Data cleaning & manipulation
* Matplotlib → Visualization
* Seaborn → Statistical data visualization
* SciPy (stats)→ Hypothesis testing
* scikit-learn→ Machine learning & model evaluation


## Data Preprocessing

* Removed null values and handled missing data
* Conducted correlation analysis to identify relationships between features
* Performed feature engineering and train-test split for modeling

---

## Statistical Analysis

* One-Sample T-Test → Tested hypotheses on WHO recommended population means(71)
* Independent Sample T-Test → Compared groups to check for significant differences



## Machine Learning Models

Implemented and evaluated multiple regression models:

* Linear Regression
* Lasso Regression
* Ridge Regression
* Elastic Net Regression

---

## 📈 Model Evaluation Metrics

Performance was measured using:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* R² Score

---

##  Key Insights

* Correlation and regression analyses revealed which features strongly influence life expectancy.
* Linear regression model emerged as the best performing model.
* Statistical testing provided evidence-based validation of observed relationships, particularly between Status groups.

---

## Project Structure

```
├── data/                  # Dataset files  
├── notebooks/             # Jupyter notebooks with EDA & modeling  
├── scripts/               # Python scripts for preprocessing & analysis  
├── results/               # Visualizations, evaluation metrics, reports  
└── README.md              # Project documentation  
```

---

Conclusion

This project demonstrates the application of data science methods in health-related research. It shows how combining EDA, hypothesis testing, and machine learning models can yield meaningful insights into the determinants of life expectancy.
