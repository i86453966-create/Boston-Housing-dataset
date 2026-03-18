# Boston-Housing-dataset
```markdown
# 🏠 Boston Housing Price Prediction

## 📝 Description
This project aims to predict the median housing prices in different areas of Boston using the Boston Housing dataset. 📊

## 📚 Data Source
Data is used from the `HousingData.csv` file, which contains 14 attributes for houses in Boston. 📁

## 🧹 Data Preprocessing
Data preprocessing was performed as follows:
*   **Handling Missing Values**: Missing values in the following columns were filled with the column's mean: ✨
    *   `CRIM` (Crime Rate)
    *   `ZN` (Residential Land Zone)
    *   `INDUS` (Non-Retail Business Proportion)
    *   `CHAS` (Charles River Proximity dummy variable)
    *   `AGE` (Proportion of Owner-Occupied Units Built Prior to 1940)
    *   `LSTAT` (Percentage of Lower Status Population)
*   **Encoding Categorical Variables**: The `CHAS` column was transformed using one-hot encoding to handle categorical values. 🏷️

## 🧠 Model Used
A **Gradient Boosting Regressor** model was used to predict housing prices. 📈

## 🎯 Model Results
After training and evaluating the model, the results were as follows: ✅
*   **Coefficient of Determination (R2 Score)**: 0.8960
*   **Root Mean Squared Error (RMSE)**: 2.7616

These results indicate that the model has good predictive capability. 🌟

## 💾 Saving the Model
The trained model was saved to `Boston housing dataset.pkl` using the `joblib` library for later reuse. 📦

## 🛠️ Requirements
*   `pandas`
*   `scikit-learn`
*   `numpy`
*   `joblib`

## 🚀 How to Run
1.  Make sure the `HousingData.csv` file is in the same directory or update the path in the code. 📂
2.  Install the required libraries:
    ```bash
    pip install pandas scikit-learn numpy joblib
    ```
3.  Run the code in the Jupyter Notebook or Colab to prepare the data, train, evaluate, and save the model. ▶️
4.  You can load the saved model `Boston housing dataset.pkl` and use it to predict new house prices. 🔮

```
