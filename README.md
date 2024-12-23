
# **Real Estate Price Prediction using Decision Tree**

## **Project Description**
This project uses a **decision tree model** to predict real estate prices based on various factors such as crime rate, average number of rooms, distance to employment centers, and more. The dataset provides information on different housing attributes, and the model aims to predict the median value of homes in thousands of dollars.

The decision tree algorithm is employed to learn patterns in the data and predict house prices based on the provided features.

## **Dataset**

The dataset contains multiple features that describe housing characteristics in different areas, along with the target variable, which is the median value of homes (`MEDV`).

| **Feature**               | **Description**                                                                |
|---------------------------|--------------------------------------------------------------------------------|
| `CRIM`                    | Crime rate per capita.                                                        |
| `ZN`                      | Proportion of residential land zoned for large-scale residential areas.       |
| `INDUS`                    | Proportion of non-retail business acres per town.                              |
| `CHAS`                     | Whether the property is adjacent to the Charles River (1 if yes, 0 if no).    |
| `NOX`                      | Nitrogen oxide concentration (parts per 10 million).                          |
| `RM`                       | Average number of rooms per dwelling.                                         |
| `AGE`                      | Proportion of owner-occupied units built before 1940.                         |
| `DIS`                      | Weighted distance to employment centers.                                      |
| `RAD`                      | Index of accessibility to radial highways.                                    |
| `TAX`                      | Property tax rate per $10,000.                                                |
| `PTRATIO`                  | Pupil-teacher ratio by town.                                                  |
| `LSTAT`                    | Percentage of lower status population.                                        |
| `MEDV`                     | Median value of homes (target variable).                                      |

### **Dataset Sample**

| CRIM   | ZN   | INDUS | CHAS | NOX  | RM    | AGE   | DIS   | RAD | TAX | PTRATIO | LSTAT | MEDV |
|--------|------|-------|------|------|-------|-------|-------|-----|-----|--------|-------|------|
| 0.00632 | 18.0 | 2.31  | 0.0  | 0.538 | 6.575 | 65.2  | 4.0900 | 1   | 296 | 15.3   | 4.98  | 24.0 |
| 0.02731 | 0.0  | 7.07  | 0.0  | 0.469 | 6.421 | 78.9  | 4.9671 | 2   | 242 | 17.8   | 9.14  | 21.6 |
| 0.02729 | 0.0  | 7.07  | 0.0  | 0.469 | 7.185 | 61.1  | 4.9671 | 2   | 242 | 17.8   | 4.03  | 34.7 |
| 0.03237 | 0.0  | 2.18  | 0.0  | 0.458 | 6.998 | 45.8  | 6.0622 | 3   | 222 | 18.7   | 2.94  | 33.4 |
| 0.06905 | 0.0  | 2.18  | 0.0  | 0.458 | 7.147 | 54.2  | 6.0622 | 3   | 222 | 18.7   | NaN   | 36.2 |

## **Model Evaluation**

The decision tree model was trained to predict the median house prices (`MEDV`). You can assess the performance of the model with metrics such as accuracy and mean squared error (MSE).

### **Sample Model Results:**

- **Mean Absolute Error (MAE):** X.XX
- **Residual Sum of Squares (MSE):** X.XX
- **R²-Score:** X.XX

(The actual values depend on your model's performance after training and evaluation.)

## **Technologies and Tools Used**
- **Programming Language:** Python  
- **Main Libraries:**  
  - `scikit-learn` for decision tree model implementation.  
  - `pandas` and `NumPy` for data manipulation.  
  - `matplotlib` and `seaborn` for visualizations.  
- **Development Environment:** Jupyter Notebook  

## **How to Use the Project**

1. Clone this repository:  
   ```bash
   git clone https://github.com/SebasKHE/Real-Estate-Price-Prediction-using-Decision-Tree.git
   ```
2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:  
   ```bash
   jupyter notebook notebooks/decision_tree_real_estate.ipynb
   ```
4. Run the cells to train the model and evaluate its performance.

## **Conclusion**
This project demonstrates the application of a **decision tree model** to predict real estate prices based on various housing attributes. By using decision trees, the model identifies the most important features for predicting house prices, allowing us to make informed predictions.

---

