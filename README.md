# Final_Project

The purpose of this project was to create a machine learning program that can predict the star rating of Amazon products by using sentiment analysis on corresponding customer reviews. Amazon products can become subject to a low rating for reasons disregarding the product’s performance or quality (such as a poor shipping and handling experience on the consumer’s end or an inaccurate product description). However, tolerance towards these experiences can, of course, vary between customers, and a review that mentions a late delivery can still have the possiblity of a high star rating. So, I wanted to see if there were common words found in reviews with both high and low star ratings and if these words can lower the accuracy score of the model.

Amazon customer review data was obtained from Professor Julian McAuley from UCSD (http://jmcauley.ucsd.edu/data/amazon/), and data from the Music and Instruments product category was used to both train and test the model. Data preprocessing was done through Pandas, in which null values, punctuation, and symbols in reviews were removed. The final dataset was run through Naive Bayes from Python's machine learning classification library.

Overall, accuracy scores on testing data were very low, ranging between 7-10%, and Python's LogicalRegression would probably have been a better model to use.
