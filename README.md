<img style = "float: right;" src = "http://www.cabsel.ethz.ch/tools/sincerities/_jcr_content/rightpar/contextinfo/fullwidthimage/image.imageformat.context.473991878.png"> 

SINCERITIES is a tool for inferring gene regulatory networks from time-stamped cross-sectional single cell transcriptional expression profiles. In particular, SINCERITIES recovers the causal relationships among genes by analyzing the evolution of the distribution of gene expression levels over time, quantified using distribution distances. We formulated the GRN inference as a regularised linear regression problem with ridge regression penalty function. The MATLAB version of SINCERITIES can be found below. 

## System Requirements
This SINCERITIES toolbox is written for MATLAB. The subroutines in SINCERITIES (version 2.0) have been successfully tested on MATLAB 2015b and 2016a. SINCERITIES requires MATLAB statistics toolbox and three additional third-party MATLAB packages, including

1. [glmnet_matlab](http://web.stanford.edu/~hastie/glmnet_matlab/)
2. [cmtest](https://ch.mathworks.com/matlabcentral/fileexchange/50157-cramer-von-mises-test?focused=3866202&tab=function)
3. [AnDarksamtest](https://ch.mathworks.com/matlabcentral/fileexchange/17451-andarksamtest)

These packages have been included in SINCERITIES distribution file.

SINCERITIES in R is also provided for R users. SINCERITIES-R  have been successfully tested on R version 3.3.1. R packages required: kSamples, glmnet, ppcor, pracma, R.matlab.

## Last Update
Current version: 2.0 (16.10.2017)

## Download and Installation

SINCERITIES (MATLAB version):    
Download and unzip the [SINCERITIES-Matlab.zip](https://github.com/CABSEL-ICB/SINCERITIES/blob/master/SINCERITIES-Matlab.zip) (ZIP, 13.4 MB) for codes and data.

SINCERITIES-R (R version):     
Download and unzip the [SINCERITIES-R.zip](https://github.com/CABSEL-ICB/SINCERITIES/blob/master/SINCERITIES-R.zip) (ZIP, 11.8 MB) for codes and data

## License
Redistribution and use in source and binary forms, with or without modification, are permitted provided agreeing to the Simplified BSD Style [License](https://github.com/CABSEL-ICB/SINCERITIES/blob/master/Sincerities-license.rtf).

[Read about Simplified BSD Style License](https://opensource.org/licenses/bsd-license.php)

## References
Papili Gao N., Ud-Dean S.M.M., Gandrillon O. and Gunawan R., SINCERITIES: Inferring gene regulatory networks from time-stamped single cell transcriptional expression profiles. Bioinformatics (2017). [Abstract](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btx575/4158033/SINCERITIES-Inferring-gene-regulatory-networks)

## Acknowledgement
This work is supported by funding from Swiss National Science Foundation.
