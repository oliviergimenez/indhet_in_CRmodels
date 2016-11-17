Capture-recapture models with individual heterogeneity
==================================================

We provide here the code to illustrate CR models with individual heterogeneity, namely CR multistate, random-effect and 
finite-mixture models. These are 3 appendices for a paper in preparation for a special issue that will be published in Oikos.
The paper is entitled: 'Individual heterogeneity and capture-recapture models: what, why and how? ' and is co-authored with Emmanuelle Cam and Jean-Michel Gaillard.

Using the same simulated data, we illustrate three different ways of incorporating individual heterogeneity in capture-recapture models:

A. a Frequentist approach using maximum likelihood methods implemented in MARK called from R using package Rmark:
  + appendix_paper_IHCMR_partA.Rmd: the markdown file that generates the docx and pdf output files
  + appendix_paper_IHCMR_partA.docx: the word output file
  + appendix_paper_IHCMR_partA.pdf: the pdf output file
  + appendix_paper_IHCMR[rmd2r]_partA.R: the R script generated from the markdown file using the function `rmd2rscript` which can be found [here](http://rstudio-pubs-static.s3.amazonaws.com/12734_0a38887f19a34d92b7311a2c9cb15022.html).

B. a Bayesian approach using MCMC methods implemented in JAGS called from R using package R2jags:
  + appendix_paper_IHCMR_partB.Rmd: the markdown file that generates the docx and pdf output files
  + appendix_paper_IHCMR_partB.docx: the word output file
  + appendix_paper_IHCMR_partB.pdf: the pdf output file
  + appendix_paper_IHCMR[rmd2r]_partB.R: the R script generated from the markdown file using the function `rmd2rscript` which can be found [here](http://rstudio-pubs-static.s3.amazonaws.com/12734_0a38887f19a34d92b7311a2c9cb15022.html).
