# CountyExercisePredictions
I put together this series of notebooks as an example machine learning problem in Python. The purpose is to predict the level of physical inactivity in a county based on other measurements on health, etc. Currently, I make no effort to address the correlation-causation issue. That is, the model can include variables that are likely to depend at least partly on the "outcome" measure (e.g. obesity).

# Notebooks
### (1) ExploreCountyData
Import data, look at distributions of individual columns, and save for future use.

### (2) BuildRegressionModels
Use data from previous step to predict inactivity by county. Use holdout cross-validation for simplicity.  

#### Altervative: ModelsWithKFoldValidation
This version uses k-fold CV instead of holdout CV. It should give more reliable validation performance but is less straightforward. In practice, the holdout validation set has enough samples (~600) that model performance doesn't seem to vary much across the folds.


# Data source
All data files and documentation were obtained from County Health Rankings & Roadmaps at http://www.countyhealthrankings.org/.
