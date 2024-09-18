# car-price-regression-model
A machine learning project focused on predicting car prices using various regression algorithms, including data preprocessing, feature engineering, and model evaluation
<p style="text-align:center">
    <a href="https://skills.network/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkML0101ENSkillsNetwork20718538-2022-01-01">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="200" alt="Skills Network Logo" />
    </a>
</p>

<h1 align="center"><font size="5">Supervised Machine Learning: Regression - Final Assignment</font></h1>

## Project Overview
In this project, I used supervised machine learning techniques to predict car prices. The dataset included multiple features like car make, model, year, mileage, and engine size. I trained and evaluated several regression models to identify the best one in terms of prediction accuracy and interpretability.

### Key Highlights:
- Dataset includes car features such as fuel type, year, engine size, and mileage.
- Multiple regression models used: Simple Linear, Polynomial, Ridge, Lasso, and ElasticNet.
- Ridge Regression performed the best in terms of RMSE, R-squared, and MAE.

## Objectives
The primary objective is to predict car prices using linear regression models and evaluate their performance. The analysis focuses on selecting a model that not only predicts accurately but is also easy to interpret.

## Steps Performed
1. **Data Cleaning:** Handled missing values and outliers, applied transformations for skewed data, and removed non-predictive features.
2. **Feature Engineering:** Created new features to enhance model performance.
3. **Model Training:** Trained five different regression models and performed hyperparameter tuning.
4. **Evaluation:** Assessed models based on RMSE, R-squared, and MAE metrics, with Ridge Regression emerging as the best model.

## Key Insights
- **Linear Relationships:** Simple Linear Regression provided a reasonable baseline.
- **Non-linear Effects:** Polynomial Regression didn’t improve performance and caused overfitting.
- **Regularization:** Ridge Regression balanced bias and variance well, achieving the lowest RMSE and highest R-squared.

## Tools & Libraries
- **Languages:** Python
- **Libraries:** NumPy, pandas, scikit-learn, matplotlib, seaborn

## Next Steps
- **Feature Engineering:** Add interaction terms to capture more complex relationships.
- **Ensemble Methods:** Experiment with Random Forest or Gradient Boosting to improve predictions.
- **More Data:** Collect more diverse data for model enhancement and generalization.

## Conclusion
Ridge Regression was chosen as the final model due to its strong performance in terms of prediction accuracy. This project demonstrated the value of applying different regression techniques and choosing the one that best fits the dataset and problem at hand.

## How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
