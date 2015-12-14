# Discriminant Analysis


[![Build Status](https://travis-ci.org/trthatcher/DiscriminantAnalysis.jl.svg?branch=master)](https://travis-ci.org/trthatcher/DiscriminantAnalysis.jl)
[![Coverage Status](https://coveralls.io/repos/trthatcher/DiscriminantAnalysis.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/trthatcher/DiscriminantAnalysis.jl?branch=master)

#### Summary

**DiscriminantAnalysis.jl** is a Julia package for multiple linear and quadratic 
regularized discriminant analysis (LDA & QDA respectively). LDA and QDA are
distribution-based classifiers that make the (strong) assumption that the 
underlying data follows a multivariate normal distribution. LDA is distinct from
QDA in the assumption about the class variability; LDA assumes that all classes 
have the same variance whereas QDA allows each class to have its own covariance
matrix. This results in LDA being a linear classifier and QDA being a quadratic
classifier.

#### Visualization


#### Documentation

## Getting Started ([example.jl](example/example.jl))


