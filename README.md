# Latin Hypercube Sampling

This repo contains code to sample the parameter space from a model using Latin HyperCube sampling. 

The bounds of each parameter is stored in the `parameters.toml` file. Right now it just has the range from [Sarthou et al. (2005)](https://botany.natur.cuni.cz/algo/soubory/EKOprotist/clanky/Sarthou_et-al_2005_growth-diatoms.pdf) for diatoms. When we start using MARBL will have to think about ranges for small phytoplankton and diazotrophs. 

## Using this code

1. setup the environment: `uv sync`
2. run the `latin-hypercube-sampling.ipynb` notebook


