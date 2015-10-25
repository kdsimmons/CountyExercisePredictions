# CountyExercisePredictions
I put together this series of notebooks as an example machine learning problem in Python. The purpose is to predict the level of physical inactivity in a county based on other measurements on health, etc. Currently, I make no effort to address the correlation-causation issue. That is, the model can include variables that are likely to depend at least partly on the "outcome" measure (e.g. obesity).

# Notebooks
### (1) ExploreCountyData
Import data, look at distributions of individual columns, and save for future use.

### (2) BuildRegressionModel
Use data from previous step to predict counties with low inactivity.

# Data source
All data files and documentation were obtained from County Health Rankings & Roadmaps at http://www.countyhealthrankings.org/.
