# Green+(2020) stellar model

[![DOI](https://zenodo.org/badge/273722238.svg)](https://zenodo.org/badge/latestdoi/273722238)

This repository contains the data-driven model of stellar photometry described in Green+(2020). This model maps from spectroscopic labels (effective temperature, surface gravity and metallicity) to absolute magnitudes. The model also accounts for the effects of dust extinction.

The model is implemented in `Tensorflow 2` and `Keras`. It takes spectroscopic labels *θ* and a reddening *E*, and outputs the absolute magnitude in Gaia *G* band, as well as colors of 12 additional bands (relative to Gaia *G* band). Those bands are Gaia *BP and *RP*; Pan-STARRS 1 g, r, i, z and y; 2MASS *J*, *H* and *Ks*; and WISE *W1* and *W2*.

An included Jupyter notebook shows how to use the model. This notebook can also be run in the cloud on [Google Colab](https://colab.research.google.com/drive/1mfVa38DW8fB957as0kvfehUl38_gvb_l?usp=sharing), without installing any software locally.
