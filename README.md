# SINCERITIES
SINCERITIES is a tool for inferring gene regulatory networks from time-stamped cross-sectional single cell transcriptional expression profiles. In particular, SINCERITIES recovers the causal relationships among genes by analyzing the evolution of the distribution of gene expression levels over time, quantified using distribution distances. We formulated the GRN inference as a regularised linear regression problem with ridge regression penalty function. The MATLAB version of SINCERITIES can be found below. 

## System Requirements
This SINCERITIES toolbox is written for MATLAB. The subroutines in SINCERITIES (version 1.0) have been successfully tested on MATLAB 2015b and 2016a. SINCERITIES requires MATLAB statistics toolbox and three additional third-party MATLAB packages, including

1. [glmnet_matlab](http://web.stanford.edu/~hastie/glmnet_matlab/)
2. [cmtest](https://ch.mathworks.com/matlabcentral/fileexchange/50157-cramer-von-mises-test?focused=3866202&tab=function)
3. [AnDarksamtest](https://ch.mathworks.com/matlabcentral/fileexchange/17451-andarksamtest)

These packages have been included in SINCERITIES distribution file.

SINCERITIES in R is also provided for R users. SINCERITIES-R  have been successfully tested on R version 3.3.1. R packages required: kSamples, glmnet, ppcor, pracma, R.matlab.

## Last Update
Current version: 1.0 (23.11.2016)

## Download and Installation

SINCERITIES (MATLAB version):
