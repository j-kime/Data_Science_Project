# Portfolio: Data Science Project

## Summary
I wanted to see if the age of a crab can be predicted based on the features & characteristics of the crab such as height, weight, gender etc. Being able to predict their age based on these features could be used help influence policy on fisheries to ensure a desirable catch can be obtained whilst not significantly impacting genetic diversity of the crab population.

The packages pandas, seaborn, matplotlib and NumPy were used to initially analyse the data and identify outliers (via statistical and visual means). 3.01% of outliers were removed from the dataset and there were no gaps in the data.

A dummy model was created which achieved an accuracy score of 6.03%. Then using the sklearn package, a logistic regression model was used with a train/test split of 70/30% to predict the age. This achieved an accuracy score of 33.33%, outperforming the dummy model.

Looking at the confusion matrix, the model was able to more accuracy predict the age in the range of 7-9 months. Ages greater than 9 months showed a larger variance in the predictions, showing that the model was poor at predicting from this point.

In conclusion, this model provides a good foundation but still requires more data columns such as crab species and sample location to help improve the model’s accuracy.

## Data set graphs pre and post cleaned

<b>Age distribution before cleaning and after cleaning</b>

<img src="/Charts/pre_age.png" alt="pre_Age" width="400"/> <img src="/Charts/post_age.png" alt="pre_Age" width="400"/> 

<b>Sex vs Age Box and Wisker plot before cleaning and after cleaning</b>

<img src="/Charts/pre_sex_vs_age.png" alt="pre_Sex_vs_Age" width="500"/> <img src="/Charts/post_sex_vs_age.png" alt="pre_Sex_vs_Age" width="500"/>

<b>Length vs Age Scatterplot before cleaning and after cleaning</b>

<img src="/Charts/pre_length_vs_age.png" alt="pre_Length_vs_Age" width="500"/> <img src="/Charts/post_length_vs_age.png" alt="pre_Length_vs_Age" width="500"/>

<b>Height vs Age Scatterplot before cleaning and after cleaning</b>

<img src="/Charts/pre_height_vs_age.png" alt="pre_Height_vs_Age" width="500"/> <img src="/Charts/post_height_vs_age.png" alt="pre_Height_vs_Age" width="500"/>

<b>Weight vs Age Scatterplot before cleaning and after cleaning</b>

<img src="/Charts/pre_weight_vs_age.png" alt="pre_Weight_vs_Age" width="500"/> <img src="/Charts/post_weight_vs_age.png" alt="pre_Weight_vs_Age" width="500"/>

## Logistic Regression Confusion Matrix Results

<img src="/Charts/confusion_matrix.png" alt="confusion_matrix"/>
