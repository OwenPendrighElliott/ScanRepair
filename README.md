# ScanRepair

Repairing bad scans of music and text using a convolutional autoencoder.

[Article](https://www.linkedin.com/pulse/convnet-autoencoder-scan-cleaning-owen-elliott/)

## PrepareData.ipynb

This notebook contains code to prepare the images for training, simply populate the data/pdfs directory with clean PDF pages and then create the data/clean and data/damaged directories and hit run.

## TrainModel.ipynb

This notebook contains the model and the code to train it. There is also a function to clean example images in the test folder which will be written to the examples folder.
