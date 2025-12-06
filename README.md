# House Price Prediction
![House price](https://github.com/TasnimAhmedEee/House-Price-Prediction/blob/master/housing2.jpg)
**Blog**: [analyticalman.com](https://analyticalman.com/house-price-prediction/)
## Introduction
'House Prices: Advanced Regression Techniques' is one of the most engaging Kaggle challenges that helps competitors developing their skills in solving problems using Machine-Learning algorithms. This challenge is all about predicting the sale-price of a house in Ames, Iowa based on the provided information about many key-factors that may have influence on the price of the houses. Therefore, it is a regression problem and the task here is to minimize the error of prediction. Several Machine-Learning algorithms including a DNN(Deep Neural Network) model has been developed and implemented in this kernel using Scikit-learn and low-level APIs of Tensorflow (usage of high-level APIs such as: Contrib or estimator has been avoided to gather in-depth knowledge in develping model-architecture). Stacking and ensembling of many algorithms have also been implemented to achieve better accuracy. A lot of emphasis has been given to feature-engineering. Therefore this section is the largest part of the kernel. The key steps of the kernel are listed below:

1. Importing Libraries and Datasets
2. Dataset Visualization
3. Separating ID Column
4. Removing Outliers
5. Normalizing Label-Column
6. Concatenating Train and Test Datasets
7. Dealing with missing Values
8. Feature Engineering
9. Handling Skewness
10. Recreating Train and Test DB
11. Regressor Models Implementation
12. DNN Implementation
13. Conclusion


## ✨ Key Features

- **Comprehensive Data Preprocessing**: Systematic handling of missing values, outlier detection, and feature normalization
- **Advanced Feature Engineering**: Created 25+ new features including composite metrics, interactions, and temporal features
- **Multiple ML Models**: Implemented Ridge, Lasso, ElasticNet, XGBoost, LightGBM, and Gradient Boosting
- **Deep Learning**: Custom DNN built with TensorFlow's low-level APIs
- **Ensemble Methods**: Stacking and weighted averaging for optimal predictions
- **Box-Cox Transformation**: Reduced feature skewness for improved model performance

## 📁 Dataset

- **Source**: Kaggle - House Prices: Advanced Regression Techniques
- **Training Samples**: 1,460
- **Test Samples**: 1,459
- **Features**: 79 explanatory variables
- **Target**: SalePrice

[Link for the Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) <br>
[Datasets](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

Kaggle challenge of House Prices: Advanced Regression Techniques is solved using ANN models with only low-level APIs of TensorFlow. The predicted test-result scored 0.1190 in Kaggle leaderboard. The current GitHub version is an older one. It will score 0.1234 at kaggle currently. The updated one will be uploaded soon.

Python Dependencies:

    NumPy
    Pandas
    Sklearn
    Tensorflow
    Matplotlib

## 🎯 Methodology

### 1. Data Preprocessing
- Outlier removal (0.55% of data)
- Missing value imputation (34 features)
- Log transformation of target variable

### 2. Feature Engineering
- Created many composite features
- Ordinal encoding of quality ratings
- Polynomial and interaction features
- Age-based temporal features

### 3. Model Training
- Cross-validation with 10 folds
- Hyperparameter tuning via GridSearchCV
- Stacking and ensemble techniques


## Best Performing Models
| Model | RMSLE |
|-------|-------|
| LightGBM | 0.1075 |
| Gradient Boosting | 0.1078 |
| Stacking | 0.1065 |
| **Ensemble** | **0.1058** |

## 📈 Results

- **Final RMSLE**: 0.1058
- **Kaggle Rank**: Top 8%
- **Total Features**: 220+ (after encoding)
- **Best Model**: Weighted Ensemble

## 🔑 Key Learnings

- Feature engineering provided the most significant performance gains
- Tree-based models (XGBoost, LightGBM) excel on tabular data
- Ensemble methods consistently outperform individual models
- Proper data preprocessing is crucial for model success


## Acknowledgments

This project was inspired by several excellent Kaggle kernels:
- [Stacked Regressions: Top 4% on LeaderBoard](https://www.kaggle.com/serigne/stacked-regressions-top-4-on-leaderboard) by Serigne
- [Neural Network Model for House Prices](https://www.kaggle.com/zoupet/neural-network-model-for-house-prices-tensorflow) by Zoupet
- [House Prices](https://github.com/dimitreOliveira/HousePrices) by dimitreOliveira


## 📧 Contact
- **Website**: [analyticalman.com](https://analyticalman.com)
- **GitHub**: [View Project](https://github.com/TasnimAhmedEee/House-Price-Prediction/)

---

⭐ If you found this project helpful, please consider giving it a star!


