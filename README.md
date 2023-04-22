# PriorCVAE

Demonstration code of the publication ["PriorCVAE: scalable MCMC parameter inference with Bayesian deep generative modelling"](https://arxiv.org/abs/2304.04307), Elizaveta Semenova, Max Cairney-Leeming, Seth Flaxman


## Environment
Create the environment `numpyro10_torch`: 
 
```
conda create -n numpyro10_torch python=3.8.15
conda activate numpyro10_torch
conda install -c conda-forge jax=0.3.25
conda install -c conda-forge numpyro=0.10.1
conda install pytorch=1.12.1 -c pytorch

conda install -c conda-forge matplotlib
conda install -c anaconda Jupyter
conda install -c conda-forge arviz
conda install -c conda-forge dill
conda install -c conda-forge mamba
mamba install -c conda-forge geopandas
conda install -c anaconda seaborn
```

## Google Colab
A [runnable demo](https://colab.research.google.com/drive/1yY6voFH0UdL2uZwDqGJWqS3tHQpB8212?usp=sharing) of the one-dimesiontal GP example comparing PriorVAE, PriorCVAE and GP inference with MCMC is available on Colab. Make sure to keep `trained_models` and `mcmc` folders in the root directory; `trained_models` contains pretrained neural networks (VAEs), and `mcmc` contains MCMC fits of models which are hard to run.


