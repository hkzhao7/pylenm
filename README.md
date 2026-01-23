# PyLEnM

[![PyPI version](https://badge.fury.io/py/pylenm.svg)](https://badge.fury.io/py/pylenm)
[![Documentation Status](https://readthedocs.org/projects/pylenm/badge/?version=latest)](https://pylenm.readthedocs.io/en/latest/?badge=latest)

This package aims to provide machine learning (ML) functions for performing comprehensive soil and groundwater data analysis, and for supporting the establishment of effective long-term monitoring. The package includes unsupervised ML for identifying the spatiotemporal patterns of contaminant concentrations (e.g., PCA, clustering), and supervised ML for evaluating the ability of estimating contaminant concentrations based on in situ measurable parameters, as well as the effectiveness of well configuration to capture contaminant concentration distributions. Currently, the main focus is to analyze historical groundwater datasets and to extract key information such as plume behaviors and controlling (or proxy) variables for contaminant concentrations (Schmidt et al., 2018). This is setting a ground for integrating new technologies such as in situ sensors, geophysics and remote sensing data.

This development is a part of the Advanced Long-Term Monitoring Systems (ALTEMIS) project. In this project, we propose to establish a new paradigm of long-term monitoring based on state-of-the-art technologies – in situ groundwater sensors, geophysics, drone/satellite-based remote sensing, reactive transport modeling, and AI – that will improve effectiveness and robustness, while reducing the overall cost.

The latest package can be downloaded from:
https://pypi.org/project/pylenm/

More information on the project can be found here:
https://altemis.lbl.gov/ai-for-soil-and-groundwater-contamination/

---

## Installation

### (Optional) Create a virtual environment
```bash
conda create --name pylenm_env python=3.8
conda activate pylenm_env
```

If using Anaconda, you may need:
```bash
pip install jupyter
```

### Install PyLEnM

#### Option 1 — Install from PyPI
```bash
pip install pylenm
```

#### Option 2 — Install from source
```bash
git clone https://github.com/hkzhao7/pylenm.git
cd pylenm
pip install .
```

Repository root:
https://github.com/hkzhao7/pylenm/tree/main

---

## Journal Publication

**PyLEnM: A Machine Learning Framework for Long-Term Groundwater Contamination Monitoring Strategies**  
Aurelien O. Meray, Savannah Sturla, Masudur R. Siddiquee, Rebecca Serata, Sebastian Uhlemann, Hansell Gonzalez-Raymat, Miles Denham, Himanshu Upadhyay, Leonel E. Lagos, Carol Eddy-Dilek, and Haruko M. Wainwright  
Environmental Science & Technology, 2022, 56 (9), 5973–5983  
DOI: https://doi.org/10.1021/acs.est.1c07440

---

## Demonstration Notebooks (Recommended)

The following notebooks demonstrate the **current and most complete version of PyLEnM** using sample-based groundwater datasets.  
They are the **default learning resources** for new users.

Notebook directory:
https://github.com/hkzhao7/pylenm/tree/main/notebooks

1. Basics  
2. Unsupervised Learning  
3. Water Table Spatial Estimation & Well Optimization  
4. Tritium Spatial Estimation  
5. Proxy Estimation (Specific Conductivity → Tritium)

Sample data:
https://github.com/hkzhao7/pylenm/tree/main/notebooks/data

---

## pylenm2 (Under Development)

A refactored version of the library, **pylenm2**, is currently under active development.

- Source code:
  https://github.com/hkzhao7/pylenm/tree/main/pylenm2
- Demo notebooks:
  https://github.com/hkzhao7/pylenm/tree/main/notebooks2

Users are welcome to explore pylenm2 and report issues via GitHub.

---

## Contributors

Aurelien Meray  
Haruko Wainwright  
Himanshu Upadhyay  
Masudur Siddiquee  
Savannah Sturla  
Nivedita Patel  
Kay Whiteaker  
Haokai Zhao  

---

## Maintainers

Haokai Zhao  
Satyarth Praveen  
Zexuan Xu  
Aurelien Meray  
Haruko Wainwright
