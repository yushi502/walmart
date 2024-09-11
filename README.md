Just some practice in ML, using regression techniques to predict Walmart's weekly sales given a number of other factors.

Initially, I tried to do some data preprocessing to see what kind of distributions the different factors followed - from this, choosing normalisation or standardisation for our data will become more of an informed decision.

Data seemed to not have many outliers, so normalisation felt plausible.
Trial and error with a few different models ended up with an XGBoost having a high R2 score, and a decent RMSE score

Much more to learn!

Update: will consider covariance for the next dataset, as I seemingly haven't considered in this case.
