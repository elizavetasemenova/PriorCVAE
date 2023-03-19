# PriorCVAE

## Environment
Create the environment `numpyro10_torch`: 
 
```
conda create -n numpyro10_torch_mamba python=3.8.15
conda activate numpyro10_torch_mamba
conda install -c conda-forge mamba
mamba install -c conda-forge jax=0.3.25
mamba install -c conda-forge numpyro=0.10.1
mamba install pytorch=1.12.1 -c pytorch
mamba install -c conda-forge matplotlib
mamba install -c anaconda Jupyter
mamba install -c conda-forge arviz
mamba install -c conda-forge dill
mamba install -c conda-forge geopandas
```
