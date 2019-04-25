# MAGIC-Imputation
This is a re-implementation of MAGIC algorithm by D Van Dijk et al for single-cell imputation. Takes the two matrices from BeforeImpute (hosted in Before-Imputation repository) for computing the imputed matrix. 
Example code:
library(RcppEigen)
D <- MAGIC(D,M,9)
