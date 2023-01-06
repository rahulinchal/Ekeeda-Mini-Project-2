# Ekeeda-Mini-Project-2
Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.¶

Attribute Information:

* Area (A): The area of a bean zone and the number of pixels within its boundaries.
* Perimeter (P): Bean circumference is defined as the length of its border.
* Major axis length (L): The distance between the ends of the longest line that can be drawn from a bean.
* Minor axis length (l): The longest line that can be drawn from the bean while standing perpendicular to the main axis.
* Aspect ratio (K): Defines the relationship between L and l.
* Eccentricity (Ec): Eccentricity of the ellipse having the same moments as the region.
* Convex area (C): Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
* Equivalent diameter (Ed): The diameter of a circle having the same area as a bean seed area.
* Extent (Ex): The ratio of the pixels in the bounding box to the bean area.
* Solidity (S): Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.
* Roundness (R): Calculated with the following formula: (4piA)/(P^2)
* Compactness (CO): Measures the roundness of an object: Ed/L
* ShapeFactor1 (SF1)
* ShapeFactor2 (SF2)
* ShapeFactor3 (SF3)
* ShapeFactor4 (SF4)
* Class (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz and Sira)

Conclusion

* The best fit model is Random forest, Bagging classifier and logistic regression we can tune some models and increase the performance and choose the best fit

Accuracy score for test data is: 0.8998530852105778
LogisticRegression test score is:  0.8998530852105778
Accuracy score for train data is: 0.905531646898289
LogisticRegression train score is:  0.905531646898289
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.9027913809990206
DecisionTreeClassifier test score is:  0.9027913809990206
Accuracy score for train data is: 0.9095203106959169
DecisionTreeClassifier train score is:  0.9095203106959169
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.7321253672869735
KNeighborsClassifier test score is:  0.7321253672869735
Accuracy score for train data is: 0.7594205941009762
KNeighborsClassifier train score is:  0.7594205941009762
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.7708129285014691
GaussianNB test score is:  0.7708129285014691
Accuracy score for train data is: 0.768972394247927
GaussianNB train score is:  0.768972394247927
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.8927522037218414
BaggingClassifier test score is:  0.8927522037218414
Accuracy score for train data is: 0.8922011126272699
BaggingClassifier train score is:  0.8922011126272699
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.7095984329089128
AdaBoostClassifier test score is:  0.7095984329089128
Accuracy score for train data is: 0.7164899758580875
AdaBoostClassifier train score is:  0.7164899758580875
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.92384916748286
GradientBoostingClassifier test score is:  0.92384916748286
Accuracy score for train data is: 0.9997900703264406
GradientBoostingClassifier train score is:  0.9997900703264406
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.873898139079334
RandomForestClassifier test score is:  0.873898139079334
Accuracy score for train data is: 0.8808649102550645
RandomForestClassifier train score is:  0.8808649102550645
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.6224289911851126
Support vector classifier test score is:  0.6224289911851126
Accuracy score for train data is: 0.6239109898184109
Support vector classifier train score is:  0.6239109898184109
---------------------------------------------------------------------------------
Accuracy score for test data is: 0.9248285994123409
XGBClassifier test score is:  0.9248285994123409
Accuracy score for train data is: 1.0
XGBClassifier train score is:  1.0
---------------------------------------------------------------------------------
