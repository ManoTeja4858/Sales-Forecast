# Sales Forecast for Store

This project demonstrates a complete end-to-end pipeline for store sales forecasting, including data cleaning, multiple machine learning models, and result evaluation. The goal was to identify the best-performing model for sales prediction. All work was conducted using **Google Colab**.

---

## 📂 Project Structure
1. **Data Cleaning** (`data_cleaning.ipynb`): Preprocessing and cleaning the dataset for modeling.
2. **Regression Models** (`regression_model.ipynb`): Implementation of traditional regression techniques.
3. **Amira Model** (`amira_model.ipynb`): A custom Amira model for advanced forecasting.
4. **Results** (`results.ipynb`): Evaluation and comparison of all models with detailed results.

---

## 🧠 Machine Learning Models
Five different machine learning models were implemented and compared:
1. **Linear Regression**: A baseline model.
2. **Random Forest**: A robust ensemble model.
3. **XGBoost**: Gradient-boosted trees for improved performance.
4. **LSTM**: A deep learning model for sequential data.
5. **Amira Model**: A custom-designed model for sales forecasting.

---

## 🔬 Methodology
1. **Data Cleaning**: 
    - Handled missing values, outliers, and inconsistencies in the dataset.
    - Feature engineering to create additional useful predictors.
2. **Model Implementation**:
    - Trained and tuned each of the five models using grid search or hyperparameter optimization.
3. **Model Evaluation**:
    - Models were evaluated using metrics such as MAE, RMSE, and R².
    - Comparative analysis was performed to determine the best model.

---

## 📊 Results
| Model              | MAE   | RMSE  | R²    |
|--------------------|-------|-------|-------|
| Linear Regression  | 12433.0   | 16221.04  | 0.991  |
| Random Forest      | 15572.5   | 18514.83  | 0.988  |
| XGBoost            | 19914.83  | 25920.43  | 0.978  |
| LSTM               | 9547.92   | 12738.86  | 0.994  |
| Amira Model        | 11265.34  | 14959.89  | 0.984  |

The **best-performing model** was **LSTM**, achieving the lowest error metrics.

---

## 🚀 Key Insights
- Model comparison revealed that LSTM was most effective due to lowest RMSE, MAE, and highest R² value.
- Data preprocessing significantly improved the overall model performance.
- Ensemble models like XGBoost and Random Forest provided better results than traditional regression methods.

---

## 📂 Files in Repository
- `data_cleaning.ipynb`: Notebook for preprocessing and feature engineering.
- `regression_model.ipynb`: Linear regression implementation.
- `amira_model.ipynb`: Custom Amira model implementation.
- `results.ipynb`: Evaluation and visualization of results.
- `README.md`: Project documentation (this file).

---

## 🔧 Requirements
This project was executed entirely in **Google Colab**. To replicate the results:
1. Open the `.ipynb` files in Google Colab.
2. Ensure the following libraries are available in the Colab environment:
    - pandas
    - numpy
    - scikit-learn
    - matplotlib
    - seaborn
    - tensorflow/keras (for LSTM)
    - XGBoost

---

Feel free to explore the code and share your feedback!
