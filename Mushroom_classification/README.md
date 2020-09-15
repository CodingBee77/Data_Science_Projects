**Introduction**

This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled
mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field
Guide to North American Mushrooms (1981). Each species is identified as definitely edible,
definitely poisonous, or of unknown edibility and not recommended. This latter class was combined
with the poisonous one. The Guide clearly states that there is no simple rule for determining the
edibility of a mushroom. Donated to UCI ML 27 April 1987.


**Analyzed problem**

We have given 23 attributes for mushrooms such as : 
cap-shape, cap-surface, cap-color, bruises, odor, gill-attachment, gill-spacing, gill-size, gill-color,
stalk-shape, stalk-root, stalk-surface-above-ring, stalk-surface-below-ring, stalk-color-above-ring,  
stalk-color-below-ring, veil-type, veil-color , ring-number, ring-type, spore-print-color, population,
habitat. 
*Mushrooms are labeled as poisonous or edible.*
It is a challenge to use those features to classify mushrooms into one of the above groups.


**Purpose**

Build mushroom classifier with the high precision and find the most indicative features.


**Selected solution**

Use decision tree classifier to recognize poisonous and edible mushrooms by their attributes.
Use different accuracy metrics and classification report to assess classifier accuracy.
Try to use hyperparameter tuning to check if accuracy will change.


**Results and conclusions**

Due to dataset analyze we found out that around 30% of mushrooms have brown cup color,
 22% - gray and 18% - red.
 
![Images/Mushroom_Cap_color_quantity.png]

