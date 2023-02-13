# Supervised Learning
### lkehoe6
#### Luke Kehoe

These are jupyter notebooks and related data for Assignment 1 - Supervised Learning for Spring semester of CS7641 at GaTech
## Installation
These libraries can be installed directly or via a package manager. The instructions below are for doing so via conda on a Linux machine.

Use the package manager [conda](https://docs.anaconda.com/anaconda/install/index.html).

follow the above linked instructions or download the tar from [link](https://www.anaconda.com/products/distribution)
```bash
bash Anaconda-latest-Linux-x86_64.sh
```

```bash
conda install -c intel scikit-learn
conda install -c conda-forge xgboost
conda install -c conda-forge matplotlib
conda install -c anaconda jupyter
```
## Usage

From within the parent folder you can run 
(replace base with your custom created environment if done so)
```bash
conda activate base
jupyter notebook
```
Your browser will open with a jupyter notebook instance from which you can open any of the individual jupyter notebook files and either run the section separately or open up the command pallette and type
```bash
run all cells
```
