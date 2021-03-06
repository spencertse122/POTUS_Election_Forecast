# Predicting County Presidential Winners


We have included a data file for training named train_potus_by_county.csv which includes some data about a county
and who won in that county's election. You job is to create a model that correctly predicts who won in that county.


This task should require no more than 3 hours of work and include the following:

1. build_model script: should read train_potus_by_county.csv and then build, train and tune your best predictive model.
The script should save your best model to the filesystem and it should also log data about the expected performance of
the model

2. make_predictions script: should load your saved model generated by the first script, and output a predictions.csv file with your predictions (one prediction per line)

3. model binary: serialized version of your best model from running step 1

4. predictions.csv: one prediction per line that is in the same order as test_potus_by_county.csv

5. performance.ipynb/.ppt/etc.: A file which provides a walkthrough about the expected performance of your model, how you evaluated the best model, should include the software dependencies for your code, any notes about how you chose your model, how you engineered your features, what other options you wanted to explore but didn't have time, any graphs/visualizations


Please only use python and python packages for scripts. 

Do not use additional data from the internet. However you can derive new features from the existing data.

The task will be judged based upon the performance of the model, the quality/clarity of the code, the
methodology of the best feature/model selection, and your explanation of how you tackled the task/considerations you made.
