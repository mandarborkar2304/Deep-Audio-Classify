# Deep Audio Classification Project

This GitHub repository contains the code for a deep learning model designed for audio classification. The model is trained to classify audio clips into different categories, with a specific focus on identifying Capuchinbird calls.

## Table of Contents
1. Import and Install Dependencies
2. Building a Data Loading Function
3. Creating a TensorFlow Dataset
4. Determine the Average Length of a Capuchin Call
5. Build a Preprocessing Function to Convert to a Spectrogram
6. Creating Training and Testing Partitions
7. Build Deep Learning Model
8. Make a Prediction on a Single Clip
9. Build Forest Parsing Functions
10. Making Predictions

## 1. Import and Install Dependencies
Before running the code, ensure you have the required dependencies installed. You can install them by running the following commands:

```bash
pip install --upgrade pip setuptools
pip install tensorflow matplotlib tensorflow-gpu==2.10.0 tensorflow-io
```

The dataset used for the project is taken from Kaggle and a link to the dataset is attached here.
[DataSet](https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing)

## 2. Building a Data Loading Function
This section defines functions to load and preprocess audio data. It includes loading WAV files, resampling, and creating spectrograms.

## 3. Creating a TensorFlow Dataset
Here, we create a TensorFlow dataset from positive and negative audio samples. Labels are added, and positive and negative samples are combined into a single dataset.

## 4. Determine the Average Length of a Capuchin Call
An analysis is performed to determine the average, minimum, and maximum lengths of Capuchinbird calls in the dataset.

## 5. Build a Preprocessing Function to Convert to a Spectrogram
A preprocessing function is defined to convert audio samples into spectrograms, which will be used as input to the deep learning model.

## 6. Creating Training and Testing Partitions
The dataset is preprocessed and split into training and testing partitions, ready for model training.

## 7. Build Deep Learning Model
A simple convolutional neural network (CNN) is constructed using TensorFlow's Keras API. The model is compiled with the Adam optimizer and binary cross-entropy loss.

## 8. Make a Prediction on a Single Clip
A single audio clip is used to test the trained model, and the prediction results are visualized.

## 9. Build Forest Parsing Functions
Additional functions are defined to load and preprocess MP3 files for predicting Capuchinbird calls in a forest setting.

## 10. Making Predictions
The trained model is used to make predictions on a set of forest recordings, and the results are presented as a dictionary containing file names and corresponding predictions.

Feel free to explore the Jupyter notebook for a detailed walkthrough of the code and experiment with different configurations. If you encounter any issues or have questions, please open an issue in the repository. Happy coding!
