# Tutorial on Coarse-Grained Molecular Optimization

This repository contains a tutorial on how to use hierarchical coarse-grained models and mutli-level Bayesian optimization for molecular discovery. Although the example system is quite simple, the methods are general and can be applied to more complex systems and larger molecules.

The tutorial is based on the paper [Navigating Chemical Space: Multi-Level Bayesian Optimization with Hierarchical Coarse-Graining](https://doi.org/10.48550/arXiv.2505.04169).

## Setup
To run the tutorial, you first need to clone this repository:

```bash
git clone https://github.com/BereauLab/Molecule-Optimization-w-Hierarchical-Coarse-Graining.git
```

Next, you need to install a few python packages and the molecular dynamics simulation software [GROMACS](https://www.gromacs.org/). See [this page](https://manual.gromacs.org/current/install-guide/index.html) for GROMACS installation instructions. The provided `requirements.txt` file contains the necessary python packages. You can install them using pip:

```bash
pip install -r requirements.txt
```
It is recommended to create a virtual environment, e.g. using [`venv`](https://docs.python.org/3/library/venv.html) or [`uv`](https://docs.astral.sh/uv/).

## Running the Tutorial
To run the tutorial, launch the Jupyter notebook [Tutorial_on_Coarse_Grained_Molecular_Optimization.ipynb](Tutorial_on_Coarse_Grained_Molecular_Optimization.ipynb) in a Jupyter environment. 