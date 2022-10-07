# Internet Security: Using ML to Identify Phishing

### Used a CSV file of over 550,000 data points stating: "URL" and "Label" (label indicated whether a site was good or bad). Used this data to create and compare Logistic Regression and Naive Bayes Model. 

## Method Used
1. Graphing good vs bad links from the dataset
2. Extract tokens from string with regexpteokenizer() method
3. Tokenizing all rows 
4. Using SnowballStemmer to stem all english words
5. Splitting good and bad sites into two different variables
6. Create models
7. Train models and visualize with a Confusion Matrix 
8. Compare Accuracy 


## Results obtained
### When both models are trained form the same dataset, both models are able to reach an accuracy rating of at least 95% with the logistic regression model slightly edging out the competition at 96.6%
