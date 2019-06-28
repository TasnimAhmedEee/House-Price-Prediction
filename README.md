# House Price Prediction

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

Kaggle challenge of House Prices: Advanced Regression Techniques is solved using ANN models with only low-level APIs of TensorFlow. The predicted test-result scored 0.1190 in Kaggle leaderboard. The current GitHub version is an older one. It will score 0.1234 at kaggle currently. The updated one will be uploaded soon.

Link for the Kaggle competition: https://www.kaggle.com/c/house-prices-advanced-regression-techniques <br>
Datasets: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

Python Dependencies:

    NumPy
    Pandas
    Sklearn
    Tensorflow
    Matplotlib


# Point to be noted
<p>
1. I highly focused on the feature-engineering section and manually engineered each and every feature to gather in-depth knowledge and minimize computational complexity. Therefore the section became very descriptive at the end.<br><br>

2. While writing this notebook, I was inspired from several Kaggle kernels. These kernels are listed here:<br>
a. https://www.kaggle.com/serigne/stacked-regressions-top-4-on-leaderboard<br>
b. https://www.kaggle.com/zoupet/neural-network-model-for-house-prices-tensorflow<br>
c. https://github.com/dimitreOliveira/HousePrices
<br><br>

3. The DNN section was implemented using only low-level APIs of TensorFlow.<br><br>

--Thanks a lot for viewing<br><br></p>


N.B.: Jupyter-notebook files are large and may not be displayed properly in GitHub Use the online Notebook viewer: https://nbviewer.jupyter.org/ to view the notebooks

