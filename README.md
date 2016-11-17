Capture-recapture models with individual heterogeneity
==================================================

We provide here the code to illustrate CR models with individual heterogeneity, namely CR multistate, random-effect and 
finite-mixture models. These are 3 appendices for a paper submitted to Oikos for a special issue. The paper is entitled: 'Individual heterogeneity and capture-recapture models: what, why and how? ' and is co-authored with Emmanuelle Cam and Jean-Michel Gaillard.

Using the same simulated data, we illustrate three different ways of incorporating individual heterogeneity in capture-recapture models:

A. a Frequentist approach using *maximum likelihood methods implemented in MARK called from R using package Rmark*:
  + appendix_paper_IHCMR_partA.docx: tutorial in word format
  + appendix_paper_IHCMR_partA.pdf: tutorial in pdf format
  + appendix_paper_IHCMR_partA.Rmd: the markdown file that generates the docx and pdf tutorial files
  + appendix_paper_IHCMR[rmd2r]_partA.R: the R script generated from the markdown file using the function `rmd2rscript` which can be found [here](http://rstudio-pubs-static.s3.amazonaws.com/12734_0a38887f19a34d92b7311a2c9cb15022.html)


B. a Bayesian approach using *MCMC methods implemented in JAGS called from R using package R2jags*:
  + appendix_paper_IHCMR_partB.docx: tutorial in word format
  + appendix_paper_IHCMR_partB.pdf: tutorial in pdf format
  + appendix_paper_IHCMR_partB.Rmd: the markdown file that generates the docx and pdf tutorial files
  + appendix_paper_IHCMR[rmd2r]_partB.R: the R script generated from the markdown file using the function `rmd2rscript` which can be found [here](http://rstudio-pubs-static.s3.amazonaws.com/12734_0a38887f19a34d92b7311a2c9cb15022.html)

C. a Frequentist approach using *maximum likelihood methods implemented in E-SURGE*:
  + appendix_paper_IHCMR_partC.docx: tutorial in word format
  + appendix_paper_IHCMR_partC.pdf: tutorial in pdf format
  + multistate.inp, multistate_cov.inp, random.inp, mixture.inp: a series of datasets that are analysed with E-SURGE in the tutorials
