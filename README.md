# Decision_Tree

Implementation of Decision tree from scratch in python.

Fnuctions and classes that my dtree file contains:
1. LeafNode : defines a leaf of the tree. 
2. DecisionNode : defines a decision node.
3. DecisionTree : class that constructs the decision tree. In order to find the best split for tree it uses the bestsplit function (implemented in the dtree file as well; it uses gini/MSE to give the best point for the split)
4. RegressionTree621 and ClassifierTree621: built using DecisionTree. They give the ability to our implementation to work both as a regressor and classifier. Based on being Regressor or classifier fit and prdict behave differently.
