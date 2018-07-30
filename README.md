# deeplearning-dsba
_Some works and assessments done within my MSc DSBA 2017-2018_

Course website: https://www.labri.fr/perso/vlepetit/deep_learning_mva.php

- Assessment 1: simple image classification and
regression in Keras

- Assessment 2: on Natural Language Processing.
    - Monolingual word,
    - sentence em- beddings,
    - multilingual word embeddings
    - sentence classification with Bag-of-Vectors (BoV) and LSTMs

- Assessment 3: deep reinforcement learning techniques on a simple game

# Launchable via binder (WIP: To be fixed ...)
(it's just a try. Notebooks cannot be fully run because of some missing dependencies and files)

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/barralf/deeplearning-dsba/master?urlpath=lab) : online Conda environment

Access this Binder at the following URL:
https://mybinder.org/v2/gh/barralf/deeplearning-dsba/master?urlpath=lab

## Notes: Conda environment with environment.yml
This Binder-compatible repo works thanks to: 
- its ![Binder URL](https://mybinder.org/v2/gh/barralf/deeplearning-dsba/master?urlpath=lab) rooting from this repo
- its `environment.yml` file 

The `environment.yml` file lists all Python libraries on which the notebook
depends, specified as though they were created using the following `conda` commands:
```
source activate example-environment
conda env export > environment.yml
```
Note that the only libraries available will be the ones specified in
the `environment.yml`, so be sure the file includes everything needed! ;)
