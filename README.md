# 🎵 Deep Audio Classification Project 🎧

## 📂 Project Overview

Welcome to the Deep Audio Classification Project repository! This project encompasses a deep learning model tailored for audio classification, with a special emphasis on discerning Capuchinbird calls.

## 🗂️ Table of Contents

1. **Import and Install Dependencies** 🛠️
2. **Building a Data Loading Function** 📊
3. **Creating a TensorFlow Dataset** 📦
4. **Determine the Average Length of a Capuchin Call** 📏
5. **Build a Preprocessing Function to Convert to a Spectrogram** 🎶
6. **Creating Training and Testing Partitions** 📑
7. **Build Deep Learning Model** 🧠
8. **Make a Prediction on a Single Clip** 🔍
9. **Build Forest Parsing Functions** 🌳
10. **Making Predictions** 🎯

## 🛠️ 1. Import and Install Dependencies

Before executing the code, ensure all necessary dependencies are installed. You can install them by running the following commands:

```bash
pip install --upgrade pip setuptools
pip install tensorflow matplotlib tensorflow-gpu==2.10.0 tensorflow-io
```

The dataset used in this project is sourced from Kaggle, and you can find it [here](https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing).

## 📊 2. Building a Data Loading Function

This section defines functions for loading and preprocessing audio data, including WAV file loading, resampling, and spectrogram creation.

## 📦 3. Creating a TensorFlow Dataset

Create a TensorFlow dataset from positive and negative audio samples, add labels, and combine them into a unified dataset.

## 📏 4. Determine the Average Length of a Capuchin Call

Perform an analysis to determine the average, minimum, and maximum lengths of Capuchinbird calls in the dataset.

## 🎶 5. Build a Preprocessing Function to Convert to a Spectrogram

Define a preprocessing function to convert audio samples into spectrograms, serving as input to the deep learning model.

## 📑 6. Creating Training and Testing Partitions

Preprocess the dataset and split it into training and testing partitions, preparing it for model training.

## 🧠 7. Build Deep Learning Model

Construct a simple convolutional neural network (CNN) using TensorFlow's Keras API. Compile the model with the Adam optimizer and binary cross-entropy loss.

## 🔍 8. Make a Prediction on a Single Clip

Test the trained model with a single audio clip and visualize the prediction results.

## 🌳 9. Build Forest Parsing Functions

Define additional functions to load and preprocess MP3 files for predicting Capuchinbird calls in a forest setting.

## 🎯 10. Making Predictions

Utilize the trained model to make predictions on a set of forest recordings, presenting results in a dictionary with file names and corresponding predictions.

Feel free to delve into the Jupyter notebook for an in-depth walkthrough of the code. Experiment with different configurations, and if you encounter issues or have questions, please open an issue in the repository. Happy coding!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
