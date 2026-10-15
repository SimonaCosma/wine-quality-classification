Red Wine Quality Classification - University project for the Big Data course

A machine learning project that predicts whether a red wine is good or not, based on its chemical properties measured in the lab.

How it works
1. The dataset has 1,143 red wines, each described by 11 chemical properties and a quality score (3–8) given by experts.
2. Wines with a score of 7 or 8 are labeled as good, the rest as not good.
3. Three models are trained and compared: Logistic Regression, Random Forest and Gradient Boosting.

Gradient Boosting was chosen as the final model. The most important factors for wine quality are alcohol, volatile acidity and sulphates.

Technologies
- Python, Google Colab
- pandas, NumPy, scikit-learn, statsmodels
- Matplotlib, Seaborn

How to run
1. Download the dataset `WineQT.csv` from [Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset).
2. Open the notebook in Google Colab and upload `WineQT.csv`.
3. Run all cells.
