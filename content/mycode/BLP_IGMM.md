---
title: BLP Code
permalink: /BLP_IGMM/
markup: mmark
date: 2019-11-01
---

## BLP IGMM in Matlab
**Blurb**
The following files implement BLP using an Iterated Efficient IV GMM routine for a single market. 
The main file is run, which then calls the other files.

**Files**
- Main : [main_rclogit_igmm.m](/files/code/matlab/blp_igmm/main_rclogit_igmm.m) 
	- Supposes that most data already generated
	- Uses Halton psuedo-uniform draws
- Mean_Value : [meanvalueCM_mix.m](/files/code/matlab/blp_igmm/meanvalueCM_mix.m) 
	- Tries to use SQUAREM but will switch to Contraction Mapping if needed
- GMM_Obj : [gmmobj_rclogit.m](/files/code/matlab/blp_igmm/gmmobj_rclogit.m) 
	- Objective function and gradient are calculated
- GMM_Gradient : [gradient_rclogit.m](/files/code/matlab/blp_igmm/gradient_rclogit.m) 
	- File that calculates GMM gradient using IFT
- GMM_Jacobian : [jacob_rclogit.m](/files/code/matlab/blp_igmm/jacob_rclogit.m) 
	- Called only for calculating standard errors
- Ind_Share : [ind_share.m](/files/code/matlab/blp_igmm/ind_share.m) 
- Mrkt_Share : [mrktshare.m](/files/code/matlab/blp_igmm/mrktshare.m) 
- Idiosyncratic_Value : [psifunc.m](/files/code/matlab/blp_igmm/psifunc.m) 
- Derivative_alpha : [DSDP.m](/files/code/matlab/blp_igmm/DSDP.m) 
- Derivative_sigma : [DSDX_VI.m](/files/code/matlab/blp_igmm/DSDX_VI.m) 
- Derivative_mu : [DSDX_MU.m](/files/code/matlab/blp_igmm/DSDX_MU.m) 

  









