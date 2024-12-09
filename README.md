# BayesianML-project

**Authors:**
1. Carlos Cuevas Villarmin M1-AI
2. Jose Felipe Espinosa Orjuela M1-AI
3. Javier Alejandro Lopetegui González M1-AI

This repository contains our experiments for the final project of the Bayesian Machine Learning course at **ENS-Paris-Saclay**.

**Title:** [Review of the paper Loss-Calibrated Approximate Inference in Bayesian Neural Networks](https://arxiv.org/abs/1805.03901).

The code in this repository is mainly based on the implementation of the paper's authors available in the github repository [https://github.com/AdamCobb/LCBNN](https://github.com/AdamCobb/LCBNN).

**Instructions for running the code:**

1. Install a miniconda distribution compatible with **python-3.6** version (23.10 recommended). An archive of miniconda distributions for any Operative system is availabe in [miniconda-repo](https://repo.anaconda.com/miniconda/).
2. Create a conda environment using the provided environment **Bayesian.yml**: ```conda env create -f bayesian.yml```
3. Activate environment: ```conda activate bayesian```

**Chest X-rays images classification experiments:**

The code for the experiments with chest X-rays images for claassifications is based on the experiment done in the paper [On Calibrated Model Uncertainty in Deep Learning](https://arxiv.org/abs/2206.07795). The dataset is built from images availables in [covid-dataset](https://github.com/ieee8023/covid-chestxray-dataset) and [kaggle-Chest-X-ray-images](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

The code for this experiments is available in the notebooks [experiments_x_rays_images_convolutional](https://github.com/jlopetegui98/BayesianML-project/blob/main/experiments_x_rays_images_convolutional.ipynb) and [experiments_x_rays_images_simple_model](https://github.com/jlopetegui98/BayesianML-project/blob/main/experiments_x_rays_images_simple_model.ipynb).

**Report**: [Report_BayesianML.pdf](https://github.com/jlopetegui98/BayesianML-project/blob/main/Report_BayesianML.pdf)
