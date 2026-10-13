# Kalman-Filter

A Kalman filter utilises properties of the normal distribution along with Bayesian statistics to clean
noisy data. It has a predict step where it uses the systems past data to make a guess at where the system should be currently
and an update step where the system uses the fact that a new observation arrives to make determine how much it trusts each measurement.
Bayes rule is super useful here as assuming both measurements are normally distributed we can combine there distributions into one.

This is important for me to understand as previous data I have worked with has had gaps and potentially untrustworthy data.
A Kalman filter can allow you to fix these issues in a measurable way which is important when comparing models and forecasting.
