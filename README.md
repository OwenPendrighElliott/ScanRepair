# ScanRepair

Repairing bad scans of music and text using a convolutional autoencoder.

[My article in this project](https://www.linkedin.com/pulse/convnet-autoencoder-scan-cleaning-owen-elliott/)

## PrepareData.ipynb

This notebook contains code to prepare the images for training, simply populate the data/pdfs directory with clean PDF pages and then create the data/clean and data/damaged directories and hit run.

## TrainModel.ipynb

This notebook contains the model and the code to train it. There is also a function to clean example images in the test folder, cleaned outputs are written to the examples folder.

## TODOs

Probably not in this repo but some day it would be cool to remove any warping from scans of non flat and badly aligned pages.

## Examples
![Example1](/examples/sidebyside6.png?raw=true)
