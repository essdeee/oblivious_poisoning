# On the Power of Oblivious Poisoning Attacks
In this README, we briefly outline how to run and use the code in our repo for the experiments for *On the Power of Oblivious Poisoning Attacks.*
## Dependencies
To get all the dependencies needed for the project, simply use the ``environment.yml`` file and running:
``conda env create -f environment.yml``

## Files
The main experiment files are the following. Instructions for running the code and reproducing the results are included in each Jupyter notebook.
 - **boston_k_stability.ipynb:** k-stability experiments (Section 4) for the Boston dataset.
 - **PROSTATE_GE_k_stability.ipynb:** k-stability experiments (Section 4) for the Prostate GE dataset.
 - **SMK_k_stability.ipynb:** k-stability experiments (Section 4) for the SMK dataset.
 - **TOX_k_stability.ipynb:** k-stability experiments (Section 4) for the TOX dataset.
 - **synthetic_dataset_k_stability.ipynb:** k-stability experiments (Section 4) for the synthetic dataset. These don't need any data .mat file, just the seeded data generation code in the directory.
 - **classification_experiment.ipynb:** The halfspace experiment for oblivious vs. full-information poisoning for classification (Section F). The data for this is generated within the notebook.

All the data for the project is in the ``./data`` folder (PROSTATE_GE, SMK, TOX). They can also be downloaded here: [http://featureselection.asu.edu/datasets.php](http://featureselection.asu.edu/datasets.php). 

All of the ``.pkl`` files are just the data obtained by our run of the experiments, and are used just for plotting the final graphs. To reproduce these ``.pkl`` files, simply run the Jupyter notebooks for the corresponding experiments.


