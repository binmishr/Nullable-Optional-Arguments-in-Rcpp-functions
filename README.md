# Nullable-Optional-Arguments-in-Rcpp-functions

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

Introduction

Often we need to have optional arguments in R of Rcpp functions with default values. Sometimes,
the default value for the optional parameters is set to be NULL. Rcpp provides the Nullable <>
to set default value as to be R_NilValue (equivalent of NULL in Rcpp). 
TAs seen from quite a few posts, the key step in using Rcpp::Nullable<> is
to cast it to the underlying type first (i.e., instantiation) after checking that the input is not
NULL.
