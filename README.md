# Mixture-Net: Low-rank deep image prior inspired by mixture models for spectral image recovery
This repository provides the Python source codes related to the paper "Mixture-Net: Low-rank deep image prior inspired by mixture models for spectral image recovery"
https://doi.org/10.1016/j.sigpro.2023.109296
[![DOI:10.1109/TCI.2021.3122285](https://zenodo.org/badge/DOI/10.1016/j.sigpro.2023.109296.svg)](https://doi.org/10.1016/j.sigpro.2023.109296)
[![arxiv.org](https://img.shields.io/badge/cs.CV-arXiv%3A2211.02973-B31B1B.svg)](https://arxiv.org/pdf/2211.02973.pdf)
# Installation
https://arxiv.org/pdf/2211.02973.pdf
List of libraries required to execute the code.:
- python = 3.7.7
- Tensorflow = 2.2
- Keras = 2.4.3
- numpy
- scipy
- matplotlib
- h5py = 2.10
- opencv = 4.10
- poppy = 0.91

All of them can be installed via `conda` (`anaconda`), e.g.
```
conda install jupyter
```
or using pip install and the required file.

# Data
This work uses the following three datasets. Please download the datasets and store them it correctly in the corresponding dataset folder:

- *Toy from CAVE dataset*: Provided in the `Data_set/` folder. Available in https://www.cs.columbia.edu/CAVE/databases/multispectral/. Accessed: 20-Nov-2020
- *Pavia dataset*: Provided in the `Data_set/` folder. Available in http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes\#Pavia_Centre_and_University. Accessed: 22-Oct-2020

## Structure of directories

| Directory  | Description  |
| :--------: | :----------- | 
| `Data_set` | Folder that contains the datasets. | 
