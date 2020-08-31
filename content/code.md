---
title: Code
permalink: /code/
markup: mmark
---

## Matlab
**GMM in Matlab**
*Blurb:* this file explains how to perform General Method of Moments in Matlab and calculate White SEs.
  - Main file: [gmm.m](/files/code/matlab/gmm.m)
  - GMM objective: [gmm_obj.m](/files/code/matlab/gmm_obj.m)

**Windmeijer (2019) First-Stage Weighted GMM**
*Blurb:* this two-step procedure uses the residuals from a linear projection of endogenous variable on the instruments to weights the GMM moments $$ E[Z^{\prime} u] $$, allowing for clustering.
  - Main file: [W_gmm_cluster.m](/files/code/matlab/W_gmm_cluster.m)

**BLP (1995) IGMM in Matlab**  
[BLP_IGMM] ( {{< relref "mycode/BLP_IGMM" >}})

## R + Rmarkdown
*Blurb:* this provides a template for using Rmarkdown; assumes necessary packages installed.
  - Rmd file: [howdy.Rmd](/files/code/r/markdown/howdy.Rmd)
  - PDF output: [howdy.pdf](/files/code/r/markdown/howdy.pdf)


## Julia
- [Simulating Multivariate Normal Probabilities](https://nbviewer.jupyter.org/github/clukewatson/juptyernotebooks/blob/master/ec821b_hw3_pt1.ipynb)
- [Probit MLE; Probit Simulated MLE](https://nbviewer.jupyter.org/github/clukewatson/juptyernotebooks/blob/master/ec821b_hw3_pt2.ipynb)
