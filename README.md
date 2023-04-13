# Logistic-Regression-with-SMOTE-and-Random-Forest-with-Hyperparameter-Tuning

**Note**: To run the .ipynb file, make user to change the dataset path to suit your system.

The dataset can be found here: [dataset](https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education)

This notebook is about a classifcation task using 2 models, `Logistic Regression` and `Random Forest`. I performed the `Logistic Regression` classifier using `SMOTE` which is an over sampling method. For the `Random Forest` Classifier I did a hyperparameter tuning to find the best parameters for the model. The parameters included are `min_samples_split`, `max_depth`, and `n_estimators`. In finding the best model, I used `f1 score` as a metric.

The models are from `scikit-learn` library. I also use some other common libraries for machine learning task.
