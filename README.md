# Random-Forest-model
       Food Inspections Evaluation
This is our model for predicting which food establishments are at most risk for the types of violations most likely to spread food-borne illness. Chicago Department of Public Health staff use these predictions to prioritize inspections. During a two month pilot period, we found that that using these predictions meant that inspectors found critical violations much faster.

You can help improve the health of our city by improving this model. This repository contains a training and test set, along with the data used in the current model.

Feel free to clone, fork, send pull requests and to file bugs. Please note that we will need you to agree to our Contributor License Agreement (CLA) in order to be able to use any pull requests.
#Original-Analysis- and -Reports
         In an effort to reduce the public’s exposure to foodborne illness the City of Chicago partnered with Allstate’s Quantitative Research & Analytics department to develop a predictive model to help prioritize the city's food inspection staff. This Github project is a complete working evaluation of the model including the data that was used in the model, the code that was used to produce the statistical results, the evaluation of the validity of the results, and documentation of our methodology.

The model evaluation calculates individualized risk scores for more than ten thousand Chicagoland food establishments using publically available data, most of which is updated nightly on Chicago’s data portal. The sole exception is information about the inspectors.

The evaluation compares two months of Chicago’s Department of Public Health inspections to an alternative data driven approach based on the model. The two month evaluation period is a completely out of sample evaluation based on a model created using test and training data sets from prior time periods.

The reports may be reproduced compiling the knitr documents present in ./REPORTS.
