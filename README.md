# PET_additive_classification

Code files for: Small Data Machine Learning: Classification and Prediction of PET Stabilizers using Molecular Descriptors

Manuscript authors: Aaron L. Liu, Rahul Venkatesh, Michael McBride, Elsa Reichmanis, J. Carson Meredith, Martha A. Grover
Code written by: Aaron L. Liu, Rahul Venkatesh


## Contents:

* Unsupervised-Learning-alvaDesc.ipynb: PCA/k-means clustering for alvaDesc descriptors for dataset
* Unsupervised-Learning-MACCS166.ipynb: PCA/k-means clustering for MACCS-166 descriptors for dataset
* feature-selection-via-rdr.ipynb: Classification/feature reduction methodology that guided physicochemical interpretation in the manuscript
* classifier-construction-candidate-predictions.ipynb: Using features found from 'feature-selection-via-rdr.ipynb', constructed/evaluated RF models + made prelim predictions

Data folder contains PET-additive data from ref [20] in manuscript:

*Kato, T. Y., M.;  Ichikawa, Y.;  Ohosugi, M.;  Hijiri, M.;  Tsutsumi, T.; Minami, M. Saturated polyesters stabilized with nitrogen-containing compounds. US3491057A, 1970.*

...as well as descriptor calculations, alvaDesc (alvaDesc 1.0.12, Kode Chemoinformatics) and MACCS-166 (calculated from ChemDes/PaDEL)
