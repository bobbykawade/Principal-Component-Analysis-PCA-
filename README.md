# Principal-Component-Analysis-PCA
Done PCA on Food Outlet Marketing Dataset

What is Principal Component Analysis ?

In simple words, PCA is a method of obtaining important variables (in form of components) from a large set of variables available in a data set. It extracts low dimensional set of features by taking a projection of irrelevant dimensions from a high dimensional data set with a motive to capture as much information as possible. With fewer variables obtained while minimising the loss of information, visualization also becomes much more meaningful. PCA is more useful when dealing with 3 or higher dimensional data.
It is always performed on a symmetric correlation or covariance matrix. This means the matrix should be numeric and have standardized data.


Points to Remember for PCA :

PCA is used to overcome features redundancy in a data set.
These features are low dimensional in nature.
These features a.k.a components are a resultant of normalized linear combination of original predictor variables.
These components aim to capture as much information as possible with high explained variance.
The first component has the highest variance followed by second, third and so on.
The components must be uncorrelated (remember orthogonal direction ? ). See above.
Normalizing data becomes extremely important when the predictors are measured in different units.
PCA works best on data set having 3 or higher dimensions. Because, with higher dimensions, it becomes increasingly difficult to make interpretations from the resultant cloud of data.
PCA is applied on a data set with numeric variables.
PCA is a tool which helps to produce better visualizations of high dimensional data.

Reference Link -
https://www.analyticsvidhya.com/blog/2016/03/pca-practical-guide-principal-component-analysis-python/
