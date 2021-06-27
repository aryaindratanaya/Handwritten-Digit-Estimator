# Handwritten-Digit-Estimator
<p align="center">
  <img src="https://www.mathworks.com/help/examples/nnet/win64/TrainABasicConvolutionalNeuralNetworkForClassificationExample_01.png"/>
</p>
A <b>Convolutional Neural Network (CNN)</b> model to estimate handwritten digits implemented using <b>MATLAB</b>.

## Introduction
This project is an implementation of a tutorial from MATLAB which can be accessed [here](https://www.mathworks.com/help/deeplearning/ug/create-simple-deep-learning-network-for-classification.html). To run this project, run the main script, i.e. `HandWrittenDigitEstimator.mlx` in <b>MATLAB</b> (R2021a is recommended). The script used here is a <b>MATLAB Live Script</b> which is useful for teaching purpose as descriptions and sections can be provided along the code.

## The Dataset

The dataset used here comes built-in with <b>MATLAB</b> which can be loaded using the script below:
```
digitDatasetPath = fullfile(matlabroot,'toolbox','nnet','nndemos','nndatasets', ...
    'DigitDataset');
imds = imageDatastore(digitDatasetPath,'IncludeSubfolders',true,'LabelSource', ...
    'foldernames');
```
The above script also can be found in `HandWrittenDigitEstimator.mlx`.

## The Code Structure

The main script (`HandWrittenDigitEstimator.mlx`) is divided into sections to ease the code understandability and enable to run the code by each section. Descriptions and explanations are also provided in each section. There are 7 sections in the main script, namely:
1. Introduction
2. Load the dataset,
3. Define the network architecture,
4. Specify the training options,
5. Train the network,
6. Predict the labels, and
7. Calculate the accuracy.

## Authors
* I Made Arya Indra Tanaya
* Laily Ade Oktaviana
* Dina Puspa Wulandari
