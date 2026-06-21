# GeoSnap: Land Use Classification using Multispectral Satellite Imagery

## Overview

GeoSnap is a deep learning project that classifies land-use categories from Sentinel-2 multispectral satellite imagery.

The project uses all 13 Sentinel-2 spectral bands and a ResNet18-based neural network trained on the EuroSAT dataset.

## Dataset

* EuroSAT RGB
* EuroSAT Multispectral
* 10 land-use classes
* 13 spectral bands

Classes:

* AnnualCrop
* Forest
* HerbaceousVegetation
* Highway
* Industrial
* Pasture
* PermanentCrop
* Residential
* River
* SeaLake

## Model

* ResNet18
* Modified first convolution layer for 13 channels
* CrossEntropyLoss
* Adam Optimizer

## Results

Validation Accuracy: 91.70%

Generated Outputs:

* Accuracy Curve
* Loss Curve
* Confusion Matrix
* Classification Report

## Folder Structure

data/
models/
notebooks/
results/
src/

## Author

Kartik Singh
IIT Dharwad
Mechanical Engineering
