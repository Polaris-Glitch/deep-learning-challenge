# deep-learning-challenge
Module 21 challenge

Analysis Report:

This model was created to predict whether Alphabet Soup's applicants will be succsessful with their funding.

Through multiple runs of the model, I used a variety of X- variables compared to the Y-variable [is_successful] 
I tried using every column, as well as multiple versions of select columns from 2 features to 20.
Despite trying multiple sets of X-variables, a variety of epochs from 10-100, and creating additional layers with varied neurons, and creating additional bins for a few columns, The highest accuracy score I could achieve was 73%
I went back and looked at each individual column against the y-variable to see if there were any that stood out in performance. There were a couple that I had high hopes to raise the accuracy score, but I continued to get a score between 72% and 73%

If I had more time, I would create a random forest model and a logistic regression model. I would evaluate each individual X- feature against the y-feature like I did in the optimization code and see how the three different models compared before moving forward.