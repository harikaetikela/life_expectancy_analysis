# life_expectancy_analysis
# Determinants of Life Expectancy: A Machine Learning Analysis

This project explores the socioeconomic and environmental factors that influence global life expectancy using machine learning. Using the World Bank’s World Development Indicators (WDI), the analysis includes data cleaning, feature engineering, model development, and clustering to uncover patterns in global health efficiency.

## Key Features
- Preprocessing: handling missing values, standardization, outlier detection
- Feature selection using F-tests, LASSO, and Random Forest ranking
- Models: OLS, Ridge, LASSO, Elastic Net, Random Forest, SVR (RBF)
- Hyperparameter tuning with 5-fold GridSearchCV
- K-Means clustering on GDP vs. residuals to identify health efficiency groups

## Results
- SVR (RBF) achieved the best generalization performance
- Clustering revealed countries that exceed or fall short of expected life expectancy relative to GDP
- High GDP alone does not guarantee high life expectancy efficiency

## Skills Demonstrated
Python, Pandas, scikit-learn, EDA, feature engineering, model evaluation, clustering, visualization
