# [Return to Home](https://chase4eck.github.io/workshop-/)

## Nieves Question + Response
Q: Nieves et a. use the random forest machine learning method to predict what value globally?  Describe in detail how random forest works.  What is a dasymmetric population allocation? Which geospatial covariates proved to be the most important when predicting global values of where humans reside?

A:

  The Random Forest model is a machine learning method. It uses the idea of combining "weak learners" to create a "strong learner". The upside to using this method is the lack of needed specifications. This method can be used for a very generalized study, such as Nieve's focus on covariates' relationship to population density. The RF model took census data and covariate data as the input. Then, this data was used to create error margins and to begin to grow these "trees". 1/3 of the data remains outside of this tree, and is considered the "out of bag" data (OOB). This is used to develop these error margins, and to properly weight the data for more accurate and precise data points. The object of this model is to create a gridded population map displaying the densities. Nieves used this model to predict the global population densities, which would help to determine the importance of covariates. When it comes to the ranking of these covariates, the most important were urban extents, climate, elevation and slope, and environmental capabilities.
  
  Dasymmetric population allocation is used in this instance with the provided census data. Though Nieves was aware of the inaccuracy of census data, he was able to create new boundaries in order to create more accurate data points. 
