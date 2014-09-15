#Logistic Regression and SVM
This assignment implements Handwritten Digits Classifier using various types of Logistic Regression and compares its performance. Binary and Multiclass Logistic Regression has been implemented using both Gradient descent and Newton Raphson approach.

Using LibSVM , we have performed classification on the dataset using SVM and compared the performance by tweaking the kernel function and gamma values.

---------------------Content of Code Folder-----------------------

blrObjFunction.m (binary logistic regression)
blrPredict.m
blrNewtonRaphsonLearn.m (binary logistic regression using Newton Raphson method with Hessian Matrix)
mlrObjFunction.m (multi class logistic rgression with gradient descent)
mlrPredict.m (multi cass logistic regression using Newton Raphson method with Hessian Matrix)
mlrNewtonRaphson.m
script.m
params.mat (all result variables)

---------------------Content of params.mat-------------------------

W_blr (weight vector for BLR Gradient Descent)
W_blr_Newton (weight vector for BLR Newton Raphson)
W_mlr (weight vector for MLR Gradient Descent)
W_mlr_Newton (weight vector for MLR Newton Raphson)
model_linear (SVM trained model for Linear Kernel)
model_rbf_1 (SVM trained model for Radial Basis, Gamma value = 1, Other Parameters = default)
model_rbf_default (SVM trained model for Radial Basis, Gamma value = default, Other Parameters = default)
model_rbf_C (SVM trained model for Radial Basis, Gamma value = default, C = 80 (best value))

---------------------Content of Report Folder-------------------------

Report.pdf
Note:

All the observations , comparison and conclusions are based on validation accuracy.
