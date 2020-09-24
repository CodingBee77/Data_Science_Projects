**Introduction**

Describe PEH concept


 
**Purpose**


**Selected solution**

Assumptions: in this classification problem I have to decide if treat this
as a multilabel or multiclass classification. Products are labeled only with
one class (E,P or H) but in fact they can match to more than 1 class so they are not
exclusive. People who create this division on a websites are aware of it,
and make the assumption which I also have used in my project. From now it is
a multiclass classification - to stay consistent with scraped data and do not
overcomplicate this project, especially on an inital state.
*Products are assigned to one of the three classess, based on ingredients list.
Some substance from another class may occur in a product inci but classification
base on a majority vote. It means that even if some protein will occur in emolient
mask but majority of ingredients are emolients it will be classified as
emolient product.*


**Results and conclusions**