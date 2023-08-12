# Predicting detailed morphologies for Euclid
Finetuning of the Zoobot CNN to emulated Euclid VIS images (created from HST COSMOS images) to automatically predict detailed galaxy morphology. The labels to train Zoobot were volunteer classifications in the Galaxy Zoo: Hubble (GZH) citizen science project. This repository contains the code used in the paper "Euclid preparation. TBD. Predicting detailed morphologies for Euclid".

# Description of the files

## Zoobot_Analysis.ipynb
Calculates the provided metrics and creates the plots of the paper for Zoobot trained on the GZH decision tree.

## Zoobot_for_Euclid.ipynb
The training (finetuning) of Zoobot to the emulated Euclid images (and on the also original HST COSMOS images) and corresponding GZH volunteer labels. The model weights and the predictions on the test set are saved.

## Zoobot_Finetuning_Example_Peculiar.ipynb
The finetuning of the best performing model (trained to emulated Euclid images) to the new task of finding peculiar galaxies and the analyis (calculation of performance metrics).

## Data
This folder contains the code for the creation of the Euclid and original HST galaxy images (first original FITS files, then JPG files) and the label file creation.
