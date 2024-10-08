## About

![Python 3.9.7](https://img.shields.io/badge/python-3.9.7-green.svg?style=plastic) ![scikit-learn 1.2.2](https://img.shields.io/badge/scikit--learn-1.2.2-green)

The code for reproducing the experimental results of the paper: "[SRPM-ST: Sequential Retraining and Pseudo-labeling in Mini-batches for Self-Training](https://www.sciencedirect.com/science/article/pii/S0925231224011147)".

## Requirements

This code has been developed under `Python 3.9.7` and `scikit-learn 1.2.2` on `Windows 10`.

To install required libraries:

```shell
pip install -r requirements.txt
```

## Datasets in the paper

Datasets are collected from OpenML(https://openml.org/) website.

## Used datasets and models

Datasets: mnist, usps, skin, har, churn, texture, wine, kdd

Models: LDA, LRR, LSVM, KNN, RF

## Usage

```shell
python main.py --data mnist --model LDA --training_size 0.01 --test_size 0.1 --Is 0,1,2,3,4,5,6 --output result.png --njobs 1
```

## Results with std.

The results with std. can be found in the file " Figure_with_std.pdf "

https://github.com/Azamat-Mukhamediya/SRPM-ST/blob/main/Figure_with_std.pdf


## Citation

```
@article{MukhamediyaSRPMST,
title = {SRPM-ST: Sequential retraining and pseudo-labeling in mini-batches for self-training},
author = {Azamat Mukhamediya and Amin Zollanvari},
journal = {Neurocomputing},
volume = {605},
pages = {128343},
year = {2024},
issn = {0925-2312},
doi = {https://doi.org/10.1016/j.neucom.2024.128343},
url = {https://www.sciencedirect.com/science/article/pii/S0925231224011147}
}
```

