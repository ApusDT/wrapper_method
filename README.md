# Feature Selection
Feature Selection is the process of selecting out the most significant features from a given dataset. 
In many of the cases, Feature Selection can enhance the performance of a machine learning model as well. <br />
There are three types of feature selection mainly
1. Filter method
2. Wrapper method
3. Embedded method
## Filter method
Filter method relies on the general uniqueness of the data to be evaluated and pick feature subset, not including any ml algorithm.
## Wrapper method
Wrapper method needs one machine learning algorithm and uses its performance as evaluation criteria.
## Embedded method
Embedded methods are iterative in a sense that takes care of each iteration of the model training process and carefully extract those features which contribute the most to the training for a particular iteration. 
Regularization methods are the most commonly used embedded methods which penalize a feature given a coefficient threshold.
<br />
*This Repo contains practical implementation of three wrapper methods.*
1. [Step Forward method](https://github.com/tharun-d/wrapper_method/blob/master/1.%20Step%20Forward.ipynb)
2. [Step Bacward method](https://github.com/tharun-d/wrapper_method/blob/master/2.%20Step%20Backward.ipynb)
3. [Exhaustive method](https://github.com/tharun-d/wrapper_method/blob/master/3.%20Exhaustive.ipynb)
<br />
**Click on respective files to know theoretical and practical implementation**
