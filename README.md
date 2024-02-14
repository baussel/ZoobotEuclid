## Measuring detailed galaxy morphologies for Euclid with Machine Learning
Fine-tuning of the Zoobot CNN (https://github.com/mwalmsley/zoobot.git) to emulated Euclid VIS images (created from HST COSMOS images) to automatically predict detailed galaxy morphology. The labels to train Zoobot were volunteer classifications in the Galaxy Zoo: Hubble (GZH, Willet et al. 2017, https://doi.org/10.1093/mnras/stw2568) citizen science project. This repository contains the code used in the paper "Euclid preparation. Measuring detailed galaxy morphologies for Euclid with Machine Learning".

## Description of the files

#### Zoobot_Analysis.ipynb
Calculates the provided metrics and creates the plots of the paper for Zoobot trained on emulated Euclid images with labels from GZH.

#### Zoobot_for_Euclid.ipynb
The training (fine-tuning) of Zoobot on the emulated Euclid images (and also on the original HST COSMOS images) and corresponding GZH volunteer labels. The model weights and the predictions on the test set are saved.

#### Zoobot_Finetuning_Example_Peculiar.ipynb
The fine-tuning of the best performing model (trained on emulated Euclid images) to the new task of finding peculiar galaxies and the analyis (calculation of performance metrics).

#### Data
This folder contains the code for the creation of the Euclid and original HST galaxy images (first original FITS files, then JPG files) and the label file creation.
