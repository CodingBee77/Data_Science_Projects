**Introduction**

Purpose of this project is to built multiclassifier to classifiy hair products according to PEH balance.
Model has to base on INCI ingredients with labels: P, E, H (protein, emolient, humectant).
There is few websites with such division.

 
**Purpose**

A built classifier for hair product which has a high accuracy.

**Selected solution**

Assumptions: in this classification problem I have to decide if treat this
as a multilabel or multiclass classification. Products are labeled only with
one class (E,P or H) but in fact they can match to more than 1 class so they are not
exclusive. People who create this division on a websites are aware of it,
and make the assumption which I also have used in my project. From now it is
a multiclass classification - to stay consistent with scraped data and do not
overcomplicate this project, especially on an initial state.
*Products are assigned to one of the three classes, based on ingredients list.
Some substance from another class may occur in a product inci but classification
base on a majority vote. It means that even if some protein will occur in emolient
mask, but the majority of ingredients are emollients it will be classified as
emollient product.*


**Results and conclusions**

I've built several multiclass classifiers : KNeighboursClassifier,
Decision Tree Classifier, SVC with a linear kernel, Gaussian Naive Bayes Classifier,
Random Forest Classifier and one neural network (MLP classifier).
Some of them achieve almost 70% accuracy which is a good score for a fist shot.

Models have to be further tested.






