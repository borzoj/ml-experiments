# ML Experiments

## Prerequisites

1. Install Python 2, pip
2. Install required libraries
```
sudo pip install gcloud tensorflow apache-beam[gcp] numpy pandas matplotlib
```
3. Install Jupyter Notebbok with tensorbvoard
```
sudo pip install ipython[all] jupyter jupyter-tensorboard
sudo jupyter tensorboard enable --system
```

## Installation 

4. Clone the repo and install submodules
```
git clone git@github.com:borzoj/ml-experiments.git
cd ml-experiments
git submodule init
git submodule update
```
