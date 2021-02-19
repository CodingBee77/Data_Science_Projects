**Introduction**

The MNIST dataset is one of the most popular and investigated datasets in the machine learning world. It consists of 784 features
which corresponds to grayscale of 28x28 pixels matrix and 70 000 images as rows.


**Analyzed problem**

Use different classification models to achieve the most accurate classifier on high dimension dataset. 
Investigate:
- how dimensionality reduction algorithms affect accuracy and learning time
- how dimensionality reduction help to visualize high dimension dataset and make them more understandable
 to the business and client.


**Selected solution**

Random forest classifier and logistic regression models were built and training time and accuracy were checked.
Then a combination of this model with the PCA algorithm was trained.
Randomized PCA in combination with Random forest classifier was tested.

Another part of the project was the visualization part where different dimensionality reduction algorithms such as t-SNE, 
PCA, LLE, MDS, LDA, and combination of PCA with MDS and PCA with LLE were used to visualize
MNIST dataset on 2 dimension space.


**Results and conclusions**

Dimensionality reduction algorithms usually do not improve accuracy because it's always involved with information loss.
They can speed up the training time but it's not a rule. Every case has to be investigated individually and the method
adjusted to the expected results.
In this case, for logistic regression, the training time  of a model has decreased but accuracy both for logistic
regression and random forest regression were lower.
Surprisingly the randomized PCA in combination with RF achieved high accuracy: 91%.
For data visualization t-SNE  algorithm gives the best result, most of the numbers were separated into clusters, looking
really well on a plot.

![](Images_DM/tSNE.PNG)

![](Images_DM/tSNE_numbers.PNG)

Any of other dimensionality reduction algorithm didn't gave comparable results:

- Principal Component Analysis

![](Images_DM/PCA.PNG)

- Locally Linear Embedding

![](Images_DM/LLE.PNG)

- PCA + LLE

![](Images_DM/PCA_LLE.PNG)

- Multi Dimension Scaling (MDS)

![](Images_DM/MDS.PNG)

- PCA + MDS

![](Images_DM/PCA_MDS.PNG)

 - Linear Discriminant Analysis
 
 ![](Images_DM/LDS.PNG)



