# fast_ai_introduction_to_random_forests
Fast.ai Introduction to Random Forests

## What is a Random Forest

Random forest is a universal machine learning technique.

* It can predict something that can be of any kind — it could be a category (classification), a continuous variable (regression).
* It can predict with columns of any kind — pixels, zip codes, revenues, etc (i.e. both structured and unstructured data).
* It does not generally overfit too badly, and it is very easy to stop it from overfitting.
* You do not need a separate validation set in general. It can tell you how well it generalizes even if you only have one dataset.
* It has few, if any, statistical assumptions. It does not assume that your data is normally distributed, the relationship is linear, or you have specified interactions.
* It requires very few pieces of feature engineering. For many different types of situation, you do not have to take the log of the data or multiply interactions together.


## Notes on the lecture

Curse of dimensionality
“Curse of dimensionality” → theoreticians don’t like many dimensions (aka columns), but in practical use the more information the better because you don’t know what might be.

No free lunch theorem → In theory, no one type of model will work well for any kind of data set, which true for random data sets

Jeremy’s “free lunch theorem” → in practice, random forest is the best model for most data b/c most data is not random. A random-forest decision tree works for almost every structured-data problem.

Q: if we have too many dimensions/fields won’t we run into co-linearity problems?
Random forests have almost no co-linearity problems
