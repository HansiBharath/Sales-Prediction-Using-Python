# Sales Prediction Using Machine Learning

## Overview
Sales prediction is essential for businesses to estimate future sales based on various advertising channels. This project utilizes **Machine Learning** to predict sales based on **TV, Radio, and Newspaper advertisement budgets**.

## Dataset
The dataset contains **200 entries** with the following columns:
- **TV**: Budget spent on TV advertisements.
- **Radio**: Budget spent on radio advertisements.
- **Newspaper**: Budget spent on newspaper advertisements.
- **Sales**: Sales generated.

## Objective
To build a **predictive model** that can accurately estimate sales based on advertising budgets.

## Steps Involved
1. **Data Preprocessing**
   - Loaded dataset using Pandas.
   - Checked for missing values and performed exploratory data analysis (EDA).

2. **Data Visualization**
   - Scatter plots to analyze relationships between sales and advertising budgets.

3. **Model Training**
   - Used **Linear Regression** to train the model.
   - Split the data into training (80%) and testing (20%) sets.

4. **Model Evaluation**
   - Evaluated performance using:
     - **Mean Absolute Error (MAE)**: 1.44
     - **Mean Squared Error (MSE)**: 3.14
     - **Root Mean Squared Error (RMSE)**: 1.77
     - **R² Score**: 0.90 (90% accuracy)

## Results
- **TV and Radio budgets have a strong impact on sales**.
- **Newspaper budget has a weak correlation** with sales.
- The model performs well with **90% accuracy**.

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook / Google Colab**

## Model Saving
The trained model was saved using **joblib** for future predictions.
```python
import joblib
joblib.dump(model, "sales_prediction_model.pkl")
```

## Conclusion
This project successfully builds a **Sales Prediction model** with high accuracy. Businesses can use this model to optimize their advertising budgets.

## Future Improvements
- Try **Polynomial Regression** for better accuracy.
- Include more features like **seasonality, competitor ads, and product discounts**.

## Author
**Your Name**

## References
Dataset: [Provide source if applicable]

