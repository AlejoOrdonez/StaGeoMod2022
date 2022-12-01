# **StaGeoMod2022 week 13 -[Ordination]**

## Objectives of this week.

1. Implement and analyse a Hierarchical Clustering analysis in `R`.  
2. Implement and analyse a PCoA analysis in `R`.  
3. Implement and analyse an NMDS analysis in `R`.


## Some basics on Ordination

rdination or gradient analysis, in multivariate analysis, is a method complementary to data clustering, and used mainly in exploratory data analysis (rather than in hypothesis testing). Ordination orders objects that are characterized by values on multiple variables (multivariate objects) so that similar objects are near each other and dissimilar objects are farther from each other. Such relationships between the objects, on each of several axes (one for each variable), are then characterized numerically and/or graphically. Many ordination techniques exist, including principal components analysis (PCA), non-metric multidimensional scaling (NMDS), correspondence analysis (CA) and its derivatives (detrended CA (DCA), canonical CA (CCA)), Bray–Curtis ordination, and redundancy analysis (RDA), among others. Contemporary developments for ordination focus on machine learning techniques[1] or using statistical models instead.

## Principal component analysis

rincipal component analysis (PCA) is a popular technique for analyzing large datasets containing a high number of dimensions/features per observation, increasing the interpretability of data while preserving the maximum amount of information, and enabling the visualization of multidimensional data. Formally, PCA is a statistical technique for reducing the dimensionality of a dataset. This is accomplished by linearly transforming the data into a new coordinate system where (most of) the variation in the data can be described with fewer dimensions than the initial data. Many studies use the first two principal components in order to plot the data in two dimensions and to visually identify clusters of closely related data points. Principal component analysis has applications in many fields such as population genetics, microbiome studies, and atmospheric science.

## Correspondence analysis

Correspondence analysis (CA) is a multivariate statistical technique proposed by Herman Otto Hartley (Hirschfeld)[2] and later developed by Jean-Paul Benzécri. It is conceptually similar to principal component analysis, but applies to categorical rather than continuous data. In a similar manner to principal component analysis, it provides a means of displaying or summarising a set of data in two-dimensional graphical form. Its aim is to display in a biplot any structure hidden in the multivariate setting of the data table. As such it is a technique from the field of multivariate ordination. Since the variant of CA described here can be applied either with a focus on the rows or on the columns it should in fact be called simple (symmetric) correspondence analysis.

## Multidimensional scaling

Multidimensional scaling (MDS) is a means of visualizing the level of similarity of individual cases of a dataset. MDS is used to translate "information about the pairwise 'distances' among a set of 
n {\textstyle n} objects or individuals" into a configuration of n {\textstyle n} points mapped into an abstract Cartesian space.

More technically, MDS refers to a set of related ordination techniques used in information visualization, in particular to display the information contained in a distance matrix. It is a form of non-linear dimensionality reduction. Given a distance matrix with the distances between each pair of objects in a set, and a chosen number of dimensions, N, an MDS algorithm places each object into N-dimensional space (a lower-dimensional representation) such that the between-object distances are preserved as well as possible. For N = 1, 2, and 3, the resulting points can be visualized on a scatter plot.

*Classical multidimensional scaling* is also known as Principal Coordinates Analysis (PCoA).

*Metric multidimensional scaling (mMDS) *It is a superset of classical MDS that generalizes the optimization procedure to a variety of loss functions and input matrices of known distances with weights and so on. A useful loss function in this context is called stress, which is often minimized using a procedure called stress majorization.

*Non-metric multidimensional scaling (nMDS)* finds both a non-parametric monotonic relationship between the dissimilarities in the item-item matrix and the Euclidean distances between items, and the location of each item in the low-dimensional space. 


