# README

In this project, we experiment with the "AAL598_2018-12-19-2019-02-08" dataset, we first provide
an in depth PCA analysis for this dataset, and then proceed to evaluate the results of SVM, Random
Forest, and perceptron (Linear Regression) on this dataset under 3 different experiment schemes,
Initially we will only look into a single point for our estimation, and gradually increase the number
of consecutive points fed to the model to 3, and then 5. 

The resutls show that for altitude the error decreases as we increase the points, however same could
not be said about the predictions for longitude, and latitude. 

ECEN649_Project_V1 -> results for single input.

ECEN649_Project_V2 -> results for three consecutive inputs.

ECEN649_Project_V3 -> results for five consecutive inputs.

All codes have been provided in jupyter notebook files, in order to run them simply restart the kernel 
and run all.

due to massive number of points on the scatterplot, they are replaced with hexbin plots for ease of 
visualization.

In order to run the codes make sure that the code is in the same location as the dataset. Create an 
instance of the Project class, and run the desired model from the class instance.