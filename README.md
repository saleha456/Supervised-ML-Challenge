# Supervised ML Credit Risk Classification

#### Predicting Credit Risk

This analysis looks at personal loan data to creates machine learning models to classify credit risk levels of given loans. Specifically, it uses Logistic Regression and Random Forest Classifier to determine which model works better with this set of data.  

**Data Cleaning:**

Some initial data cleaning needed to be done, such as converting categories to numeric and adding a missing category for one of the columns.

**Conclusion:**

Initially, before the data was scaled, Random Forest Classifier was performing better than Logistic Regression, but it had a suspicious Training Score of 1.0.  After the data was scaled, Random Forest still had similar results, but Logistic Regression scores improved significantly and the testing score was more than the Random Forest Classifier testing score.  In this case, the Logistic Regression model performed better.

