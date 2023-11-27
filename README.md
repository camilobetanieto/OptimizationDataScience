# Optimization for Data Science
The homework and the final project that were conducted as part of the Optimization for Data Science course I took during my master's degree. 

Both the homework and the final project tackle convex optimization problems. The homework required to solve a semi-supervised learning problem, while the final project consisted in solving the optimization problem related to soft-margin Support Vector Machines (SVM). 

## Homework 1:
Implementation of the Gradient Method and two Block Coordinate Gradient Descent methods (Randomized BCGD and Gauss-Southwell BCGD, both with one-dimensional blocks) to solve semi-supervised learning problems on both synthetic and real datasets. All methods used a fixed step-size, while the two BCGD methods also employed exact line search. Finally, the performance of all the methods was evaluated.

## Final project:
Implementation and analysis of the Frank-Wolfe algorithm and some of its variants (the Away-steps Frank Wolfe and the Pairwise Frank-Wolfe), for training a soft-margin Support Vector Machine (SVM) on three real datasets for classification. In this case, all methods employed the Armijo Rule to compute the step size, while the standard Frank-Wolfe also used a diminishing step-size. Lastly, the performance of all methods was tested and compared.
