# sepsis_predict
A project to predict the likelihood of patient developing sepsis, given a set of training data.

The following is a list of the files:

- *Explanation_of_method.pdf*: Explains the method used to wrangle the data, train the algorithm, and predict the results for the given test data.
- *data_challenge_final.ipynb*: The python code (in Jupyter notebook) that does all of the above.
- *Predicted_outcomes.csv*: The predicted outcomes for the test data (for which results were not provided). Each row contains the id number for the given patient, the predicted outcome which is binary (1 for "will develop sepsis", 0 for "will not develop sepsis"), and a predicted probability where P(will develop sepsis) $\in [0,1]$.

The algorithm resulted in an AUC of $0.899$ and a BER of $0.199$.
