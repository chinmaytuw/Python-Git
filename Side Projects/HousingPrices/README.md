# Housing Prices Project

## Competition Description:
- Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

- With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## The approach:
- Exploratory Data Analysis to get a sense of the data.

- Feature engineering: 2.1 We will be creating a few features by the combining the existing features. 2.2 We will also fill in the missing values. All of this will be done using sklearn pipelines.

- Training and Predicting:

  - 3.1 We will perform Grid search cross validation of 5 different algorithms: Ridge Regression, Elastic Net, SVM, XGBoost, GradientBoost. The hyper parameter space for a few algorithms has been thinned down as it the runtime is too high here which is not the case with a local version.

  - 3.2 We will combine the 5 algorithms using a voting regressor and use that to train on the entire dataset and predict on the test set.
