# Project 5: Making predictions

The clean air act of 1970 was the beginning of the end for asbestos in homebuilding. By 1976, the U.S. Environmental Protection Agency (EPA) was given authority to restrict asbestos in paint. Homes built during and before this period are known to have materials with asbestos https://www.asbestos.com/mesothelioma-lawyer/legislation/ban/.

The state of Colorado has a large portion of their residential dwelling data that is missing the year built, and they would like you to create a predictive model that can classify if a house is built pre 1980. They would also like you to create a model that predicts (regression) the actual age of each home.

Colorado gave you home sales data for the [city of Denver from 2013](https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-real-property-sales-book-2013) on which to train your model. They said all the column names should be descriptive enough for your modeling and that they would like you to use the latest machine learning methods.

## Readings

- [Machine Learning Overview](https://byuistats.github.io/CSE250-Hathaway/course-materials/machine-learning/)
- [A visual introduction to machine learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [Evaluation metrics](https://ranvir.xyz/blog/how-to-evaluate-your-machine-learning-model-like-a-pro-metrics/)
- [Decision tree classification in Python](https://www.datacamp.com/community/tutorials/decision-tree-classification-python)
- [Julia Silge on tidymodels using decision trees](https://juliasilge.com/blog/wind-turbine/)

## Tasks

Complete this project in R and Python as two standalone reports.

- [ ] Create 2-3 charts that evaluate potential relationships between the home variables and before1980.
- [ ] Can you build a classification model (before or after 1980) that has at least 90% accuracy for the state of Colorado to use (explain your model choice and which models you tried)?
- [ ] Will you justify your classification model by detailing the essential features in your model (a chart and a description are a must)?
- [ ] Can you describe the quality of your classification model using 2-3 evaluation metrics? You need to provide an interpretation of each evaluation metric when you provide the value.
