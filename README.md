# hybridVAE.jl

This repository contains all the scripts written in Julia programming language for master's thesis. MIL data sets, that were used, are also included 
in the first four files, i.e., Fox, Musk1, Musk2, and Tiger. The following is a simple description of the individual scripts.


### CV_MIL.jl
performs CV either discriminatively, or via hybrid approach

###  poly_reg_hybrid.jl
performs exercise for improvement of polynomial regression via generative regularization

### my_vae.jl
performs the simple experiment for generating data 

### hybridVAE_nmoons.jl
tests the hybrid VAE aprroach for synthetic nmoons data

### hybridVAE_MIL.jl
computes AUC-ROC for MIL using hybridVAE

### hybrid_vs_discr_MIL.jl
computes AUC-ROC for MIL using hybrid or discriminative method

### NCE_binary_gauss.jl
estimates the 1D gaussian distribution using noise contrastive esimation

### NCE_binary_gauss2D.jl
estimates the 2D gaussian distribution using noise contrastive esimation
