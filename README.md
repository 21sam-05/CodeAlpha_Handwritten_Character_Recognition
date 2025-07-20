# Handwritten Character Recognition (HCR) using Convolutional Neural Networks (CNN)

## Project Overview

This project demonstrates the implementation of a Convolutional Neural Network (CNN) for Handwritten Character Recognition (HCR). It leverages the **EMNIST (Extended MNIST) dataset**, which includes handwritten digits (0-9), uppercase letters (A-Z), and lowercase letters (a-z), making it a more comprehensive and challenging task than standard MNIST.

The goal of this project is to build, train, and evaluate a robust CNN model capable of accurately classifying a wide range of handwritten characters.

## Features

* **CNN Architecture:** A multi-layered CNN designed for image classification tasks.
* **EMNIST Dataset Integration:** Utilizes the `emnist/byclass` split from `tensorflow_datasets` which provides 62 distinct character classes.
* **Image Preprocessing:** Includes necessary steps like rotation, flipping, normalization, and channel expansion for EMNIST data.
* **Model Training & Evaluation:** Demonstrates the training process, validation, and evaluation metrics (accuracy, loss).
* **Training Visualization:** Plots for training and validation accuracy/loss over epochs.
* **Prediction Examples:** Shows sample predictions on test images with true and predicted labels.
* **Keras & TensorFlow:** Built using the high-level Keras API on top of TensorFlow for easy model development.

## Dataset

The **EMNIST (Extended MNIST)** dataset is used for this project. Specifically, we load the `emnist/byclass` split, which contains:
* 10 digits (0-9)
* 26 uppercase letters (A-Z)
* 26 lowercase letters (a-z)

This results in a total of **62 classes**. The dataset is known for its variability in handwriting styles, making it a good benchmark for HCR.
## Technologies Used

* **Python 3.x**: The core programming language for the project.
* **TensorFlow**: An open-source machine learning framework.
* **Keras**: A high-level API for building and training deep learning models, integrated within TensorFlow.
* **NumPy**: A fundamental package for numerical computing in Python, used for array manipulations.
* **Matplotlib**: A plotting library used for visualizing training history and sample predictions.
* **TensorFlow Datasets (TFDS)**: Used for easily loading and managing the EMNIST dataset.

## Contact 📞✉️

Feel free to reach out if you have any questions or feedback!

* SAMRIDHI SAXENA
* GitHub :  https://github.com/21sam-05
* LinkedIn: https://www.linkedin.com/in/samridhi-saxena-07231a28a/
* E-mail : saxenasamridhi1921@gmail.com

