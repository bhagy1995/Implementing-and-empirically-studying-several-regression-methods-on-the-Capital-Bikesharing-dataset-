# Implementing-and-empirically-studying-several-regression-methods-on-the-Capital-Bikesharing-dataset-

The core data set is related to the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in http://capitalbikeshare.com/system-data. Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions, precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors. The summary of the project:

- Implemented Ordinary Least Squares regression and locally weighted regression algorithms from scratch, analysed the effect of different values of local reweighting parameter on R2 score of the locally weighted regression model.

-Implemented Poisson model from scratch, solved the maximum likelihood estimate using autograd function for 50 iterations, obtained a d2 tweedie score of 0.095 on test set .

-Reported the final weights for all models, thereby obtained the most significant and least significant features.
