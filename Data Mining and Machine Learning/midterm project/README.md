The goal was to identify the main factors that produce high ozone levels in an area near Los Angeles.

The dataset contained features such as: week day, pressure, wind speed, humidity, etc.

The target (ozone levels) was binary: either low level, or high level.

Coding was done in R. I've used logistic regression constrained with ElasticNet, and boosted decision trees. Eight different models, with different parameters, were instantiated from each of the two types of base models. Double cross-validation was used to compare model performance and rank them.

The best model was fit to the data, and generated a list of variable importances. This was used to identify the main factors (variables) that produce high ozone levels.
