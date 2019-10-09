# udacity_nd025_term2_project_4-capstone

## What's all about?

That's the final project of my Data Science Nanodegree at Udacity.

I'm analyzing data provided by Starbuck's. Starbuck's gives annonymized personal data of fictional customers, several different offers given to the customers and the transaction- and completion-data.

I'm interessed in predicting the success of this offers to arbitrarly users.

So at the end I give a method to predict which type of offer should be made to a person.

I've documented the whole process at https://medium.com/@dfv.ms/which-offer-should-be-made-9db167b1262c

## Used Libraries
This project uses python and several libraries:
* scikit-learn
* pandas
* numpy
* matplotlib
* seaborn

## Files
### Starbucks_Capstone_notebook.ipynb
contains the Jupyter Notebook with all steps
of data processing and analyzing the data. It also runs the ML-process and
provides a function for offer-prediction.

### data/
portfilio.json, profile.json and transcript.json contain the data given by
Udacity/Starbuck's.

## Results
After analyzing the the transaction-data and personal-data we can identify two
groups of customers: One with a lot of personal data and one with very few.

For both groups a machine learning model is trained. As expected the accuracy
in the first case is better than in the second one.

This model is used in a function to predict which kind of offer has the best
chance of completing for an arbitrarly given person.
