# Demand-Forecasting
# Shelter Demand
How many people need a shelter?
Predicting the future is always difficult. In this
interesting case study, we use Facebook Prophet to
predict the daily Demand for Shelter in New York City.
As well, we will learn about Cross-validation and
Parameter Tuning in Time Series

- Prepare dataframe : Facebook Prophet has a lot of quirks.
The Date variable must be called ds and
the time-series has to be y. Additionally,
the date must be in the format yyyymm-dd

- Training and test set : In Time-Series, the training and test
set follows a different structure, given
that information without context does
not have value. Additionally, the test
set should have the same number of
days as a real-life forecast.

- Create model and assess accuracy : Build the Facebook Prophet model,
while adding the regressors. Next,
build the future data frame to
perform the forecast. In the end,
assess the accuracy of the model.

- Visualize the output : Facebook Prophet has very cool built-in
visualization functions. Use them! As a
visual learner myself, I like to see
pretty graphs to know what the model
tells me.

- Perform parameter tuning : Do the Parameter Tuning while
performing cross-validation
