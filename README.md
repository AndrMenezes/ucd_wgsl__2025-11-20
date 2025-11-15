## Bayesian nonparametric models for sparse count-compositional data using ensembles of regression trees

Presentation delivered at the Working group of statistical learning at UCD 2025.


> Count-compositional data arises in many fields, including high-throughput 
microbiome sequencing and paleoclimate studies. An important and common goal in 
analysing such data is to understand how covariates are associated to the observed
composition. Existing methods often fail to simultaneously address key challenges
inherent in count-compositional data, such as high-dimensionality, overdispersion,
an excess of zeros, and cross-sample heterogeneity. In this talk, we first present
novel probabilistic portrayals of two multivariate models designed to handle 
zero-inflation in count-compositional data. Then, to address the above concerns,
we leverage one of the models by assigning independent nonparametric Bayesian 
additive regression trees (BART) priors on both its population-level count and 
structural zero probabilities components. We further extend this by adding latent 
random effects to capture more general dependence structures among the categories. 
We develop an efficient MCMC algorithm combining a recent data augmentation scheme 
with established BART sampling routines. We evaluate our proposed models in 
simulation studies and then illustrate their applicability in microbiome and 
paleoclimate studies.
