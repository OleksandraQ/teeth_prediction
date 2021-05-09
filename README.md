# teeth_prediction

Relevant Code for manuscript: "Rapid tooth evolution engendered by hierarchical hard dental tissue changes", Jennifer Knaus, et al.

All predictions with neural networks and importance analysis of elements in the paper was done in Python 2.7.15 with PyTorch v 1.0.1. 

Additional support libraries were in the following versions:

1. Numpy 1.13.3
2. Matplotlib 2.2.2
3. Sklearn 0.19.1

All data necessary to produce the results are in the folder *Data*. Jupyter notebook for predicting hardness is named *predicting_hardness.ipynb*; for elastic modulus is *predicting_elastic_modulus.ipynb*. The plots shown at the Extended Data Figure 9 can be reproduced using the same notebooks. 

Please note, that for all predictions ensembles of independent neural networks were used, those networks are not provided here and should be generated during the analysis. Your results might have a slight variations due to new NNs, you will generate (if you want to use the same ensemble as was used for producing published results, please contact the authors). All individual predictions of those networks will be saved, so running the full analysis routine can be time and storage-space consuming.
