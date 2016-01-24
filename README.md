# HackerRank-Xerox-Challenge

The aim of this challenge was to predict the risk of death (mortality) in patients admitted to intensive care units (ICU) within hospitals.

I used a gaussian model. All features (patient's physiological parameters) were converted to binary (0 & 1), by determining whether the value of a feature for any patient lies outside the 2nd standard deviation of the mean of that feature. Then a scikit-learn logistic regression predictor was used to classify patients mortality.

finalScript.ipynb => script which was submitted to the competition.

Xerox_Challenge.ipynb & run_model.ipynb => both are trial scripts.
