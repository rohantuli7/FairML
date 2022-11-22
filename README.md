# FairML

This project addresses the bias present in Machine Learning algorithms. Existing algorithms using preprocessing, in-processing and post-processing have been used. These algorithms are also paired and tested in an emsemble architecture.

This project uses the following algorithms for experimentation:
1. [Disparate Impact Remover (pre-processing)](https://arxiv.org/abs/1412.3756)
2. [Exponentiated Gradient Reduction (in-processing)](https://proceedings.mlr.press/v80/agarwal18a.html)
3. [Equalized odds (post-processing)](https://arxiv.org/abs/2006.04292)


The data following datasets have been used for analysis:
1. [German dataset](https://aif360.readthedocs.io/en/latest/modules/generated/aif360.datasets.GermanDataset.html)
2. [Adult dataset](https://aif360.readthedocs.io/en/latest/modules/generated/aif360.datasets.AdultDataset.html)
