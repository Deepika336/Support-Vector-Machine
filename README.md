Project Topic : Classification of human cells into benign or malignant.


Reference : DLithe  

Project done under the guidance of : DLite

Done by: M.Deepika                 Usn:4nm18cs084
Batch 2



To build and train a model of human cell records using SVM and classify cells to whether the samples are benign or malignant. SVM works by mapping data to a high-dimensional feature space so that data points can be categorized even when data are not otherwise linearly separable.A seperator between the categories is found,then data is transformed in such a way that the seperator could be drawn as a hyperplane.

What is Support Vector Machine?
“Support Vector Machine” (SVM) is a supervised machine learning algorithm which can be used for both classification or regression challenges. However,  it is mostly used in classification problems. In the SVM algorithm, we plot each data item as a point in n-dimensional space (where n is number of features you have) with the value of each feature being the value of a particular coordinate. Then, we perform classification by finding the hyper-plane that differentiates the two classes very well.

Support Vectors are simply the co-ordinates of individual observation. The SVM classifier is a frontier which best segregates the two classes (hyper-plane/ line).

 Important parameters having higher impact on model performance are “kernel”, “gamma” and “C”.
 
 kernel:  Here, we have various options available with kernel like, “linear”, “rbf”,”poly” and others (default value is “rbf”).  Here “rbf” and “poly” are useful for non-linear hyper-plane.
 
 gamma: Kernel coefficient for ‘rbf’, ‘poly’ and ‘sigmoid’. Higher the value of gamma, will try to exact fit the as per training data set i.e. generalization error and cause over-fitting problem.
 
 C: Penalty parameter C of the error term. It also controls the trade-off between smooth decision boundaries and classifying the training points correctly.
 
 
