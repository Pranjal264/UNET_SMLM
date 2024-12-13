# UNET_SMLM

<!-- This is the Git repository for the program 'CNN assisted PSF localization (CAPL)' based on the paper [Neural network-assisted localization of clustered point spread functions in single-molecule localization microscopy](https://doi.org/10.1111/jmi.13362). -->

## Setting up

The program was developed in Python 3.10.12 with Tensorflow 2.17.1 on Google colab

- You will need to set up [Fiji](https://imagej.net/software/fiji/downloads) / ImageJ and install the [ThunderSTORM](https://github.com/zitmen/thunderstorm) plugin to create the training datasets.

## Usage

The program is divided into two parts:

1. training_data_generation.ipynb : this notebook generates the training files required to train the model.
2. UNET_SMLM_v1.ipynb : this notebook trains the CNN model

A step-by-step procedure for using each notebook is incorporated into the notebooks.

Thank you,

Pranjal Choudhury
