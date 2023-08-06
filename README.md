# Portfolio: Data Science Project

## Summary
I wanted to see if the age of a crab can be predicted based on the features & characteristics of the crab such as height, weight, gender etc. Being able to predict their age based on these features could be used help influence policy on fisheries to ensure a desirable catch can be obtained whilst not significantly impacting genetic diversity of the crab population.

The packages pandas, seaborn, matplotlib and NumPy were used to initially analyse the data and identify outliers (via statistical and visual means). 3.01% of outliers were removed from the dataset and there were no gaps in the data.

A dummy model was created which achieved an accuracy score of 6.03%. Then using the sklearn package, a logistic regression model was used with a train/test split of 70/30% to predict the age. This achieved an accuracy score of 33.33%, outperforming the dummy model.

Looking at the confusion matrix, the model was able to more accuracy predict the age in the range of 7-9 months. Ages greater than 9 months showed a larger variance in the predictions, showing that the model was poor at predicting from this point.

In conclusion, this model provides a good foundation but still requires more data columns such as crab species and sample location to help improve the model’s accuracy.

## Data set graphs pre and post cleaned

![]()
