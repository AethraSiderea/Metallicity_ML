# Metallicity_ML

Created by Charlie Hughes.

The example_ANN.ipynb code lets you use predict the metallicity (Fe/H) of stars using DES or DECaLS photometry. This code is a fairly simplified version that was designed to be used with minimal tinkering around and a few features available (e.g. nearest neighbor cut). More complicated versions may be uploaded soon, featuring multiple regressors or other datasets.

To create the model using DES, you need the "s5_dr3.1_xdes_dr2.fits" file. "Data/GC_GaiaEDR3_DesDR2.fits" allows you to use the model on DES globular clusters. These two files also have DECaLS versions. All these files are available for download at: https://drive.google.com/drive/folders/1asSvDAGbmoG5GtC3IlSyP7psEiSmY_GG?usp=sharing

Some dependencies that you will need to download include the usual (numpy, astropy, etc), as well as:
- Pandas (Pandas dataframes are how a lot of data is stored -- very useful and fairly easy to use if you already know Numpy arrays)
- Sci-kit learn (for ML tools)
- Tensorflow (for ANN code. probably the largest download)


Soon a random forest regression version of example_ANN will also be uploaded (a RFR is a different type of ML algorithm).
