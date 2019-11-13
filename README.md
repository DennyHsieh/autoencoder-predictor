# Pytorch Predictor with Autoencoder

### Install packages
- Create a virtualenv
```commandline
conda create -n chemtorch python=3.6
```

- Install the packages
```commandline
conda install -c deepchem -c rdkit -c conda-forge -c omnia deepchem=2.1.0
conda install pytorch-cpu torchvision-cpu -c pytorch
```

- If you want to work on Jupyter Notebook
```commandline
conda install nb_conda
```

### Dataset
- MoleculeNet
    - ESOL
    - QM9
- ZINC
