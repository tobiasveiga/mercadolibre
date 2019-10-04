# mercadolibre
2nd place solution for the MeLi Challenge 2019

This solution uses three models SGD (scikit-learn), multinomialNB (scikit-learn) and GRU (Keras) trained on both char level and word level, and in two different (but quite similar) datasets.

## Instructions to generate submission 

### Required packages and softwares:
Python3 with the libraries Numpy, Pandas, Scikit-Learn, MatplotLib, Keras, NLTK.
(No other library was used. No pre-trained model was used.)

### Follow the steps:
1) Unpack train, test and sample submission in the root folder with the respective names: train.csv, test.csv, sample_submission.csv

2) Run all notebooks in MeLi_BaseGen/
3) Run all notebooks in MeLi_scripts2/
4) Run all notebooks in MeLi_scripts3/
5) Run the notebook MeLi\_Ensembles/MeLi\_Ensemble_06.ipynb
6) Run the notebook MeLi\_Ensembles/MeLi\_Ensemble_11.ipynb
7) Run the notebook MeLi\_Ensembles/MeLi\_FinalEnsemble.ipynb

The final submission will be in the root folder with the name 'submission_MegaEnsemble02.csv'
:)

PS: Some of these notebooks might require more than 64 GB of memory to run. Each notebook takes about 1 to 2 hours to run copletely in a 4 cores computer.
