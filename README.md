# Presidential-Election-Predictor

Conceptual Complexity is to measure an individual’s ability to project their ability to perceive a different perspective of a certain subject. 
Historically, lt has been seen that it is extraneous and time-consuming to manually score large sets of text. Therefore, there is a demand to 
automate scoring to significantly reduce time and expense. This paper suggests that using modern machine learning algorithms is a better predictor
than traditional methods specifically the efficacy of a presidential speech. 


## Findings
Algorithms | Configuration | Accuracy |
--- | --- | --- | 
Support Vector Machine | kernel="rbf",C=13, gamma='scale',97 Component PCA | 92.32% | 
--- | --- | --- | 
Random Forest| Gini Index| 88.6%| 
--- | --- | --- | 
XG boosting| gamma=0, max_tree_depth=3, n_estimatror=100| 94.1% | 
