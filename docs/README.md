# Martina Pepiciello's machine learning portfolio
A collection of machine learning projects in Jupyter Notebooks
\
&nbsp;  


## [Interesting news filter](https://github.com/MartinaPepiciello/MachineLearning/tree/main/NewsFilter)
Browse the BBC News website to extract news that I find interesting, leaving out the ones I'm not interested in. Available for the World section, currently working on expanding the training set and on building one for the Tech and Science sections.
- Scraped over 800 article titles and summaries from the BBC News website using Selenium ([link](https://github.com/MartinaPepiciello/MachineLearning/blob/main/NewsFilter/BBC-build-training.ipynb)).
- Compared performance of different models from Scikit-learn (logistic regression, random forest, gradient boosting tree, support vector classifier, multilayer perceptron) with grid search and cross-validation, and selected the one with the best F1-score ([link](https://github.com/MartinaPepiciello/MachineLearning/blob/main/NewsFilter/BBC-build-model.ipynb)).
- Trained the best performing model and used it to select interesting articles. Then wrote the articles' titles and summaries to an HTML file, also containing links to the full articles ([link](https://github.com/MartinaPepiciello/MachineLearning/blob/main/NewsFilter/BBC-predict.ipynb)).
