# **StaGeoMod2022 week 10 -[Classification and Regression Trees]**

## Objectives of this week.

1. Implement and interpret a Classification/Regression Trees analysis in `R`.
2. Implement and analyse a Random Forest analysis in `R`.
3. Implement and analyse a Boosted regression Tress analysis in `R`.


## Supervised Classification (Classification/Regression Trees)

Classification/Regression Trees or Decision tree learning is a supervised learning approach used in statistics, data mining and machine learning. In this formalism, a classification or regression decision tree is used as a predictive model to draw conclusions about a set of observations.

Tree models where the target variable can take a discrete set of values are called classification trees; in these tree structures, leaves represent class labels and branches represent conjunctions of features that lead to those class labels. Decision trees where the target variable can take continuous values (typically real numbers) are called regression trees.

Decision trees are among the most popular machine learning algorithms given their intelligibility and simplicity.

In decision analysis, a decision tree can be used to visually and explicitly represent decisions and decision making. In data mining, a decision tree describes data (but the resulting classification tree can be an input for decision making).


## Random forests

Random forests (RF) or random decision forests is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time. For classification tasks, the output of the random forest is the class selected by most trees. For regression tasks, the mean or average prediction of the individual trees is returned. Random decision forests correct for decision trees' habit of overfitting to their training set.  Random forests generally outperform decision trees, but their accuracy is lower than gradient boosted trees.[citation needed] However, data characteristics can affect their performance.

## Boosted Regression Trees

osted Regression Tree (BRT) models are a combination of two techniques: decision tree algorithms and boosting methods. Like Random Forest models, BRTs repeatedly fit many decision trees to improve the accuracy of the model. One of the differences between these two methods is the way in which the data to build the trees is selected. Both techniques take a random subset of all data for each new tree that is built. All random subsets have the same number of data points, and are selected from the complete dataset. Used data is placed back in the full dataset and can be selected in subsequent trees. While Random Forest models use the bagging method, which means that each occurrence has an equal probability of being selected in subsequent samples, BRTs use the boosting method in which the input data are weighted in subsequent trees. The weights are applied in such a way that data that was poorly modelled by previous trees has a higher probability of being selected in the new tree. This means that after the first tree is fitted the model will take into account the error in the prediction of that tree to fit the next tree, and so on. By taking into account the fit of previous trees that are built, the model continuously tries to improve its accuracy. This sequential approach is unique to boosting. 


Text from:
https://en.wikipedia.org/wiki/Decision_tree_learning
https://en.wikipedia.org/wiki/Random_forest
https://support.bccvl.org.au/support/solutions/articles/6000083202-boosted-regression-tree


