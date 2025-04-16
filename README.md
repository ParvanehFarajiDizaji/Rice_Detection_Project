# Rice_Detection_Project
# Section 1: "MLP - Basic Image Classification"

You will start with a simple image classification task using an MLP. Use Rice dataset and build a model that classifies these images into their respective categories.
The goal of the project will be to build a MLP to classify different types of rice grains based on images. The dataset contains images of rice grains from different classes, and the you will need to preprocess the data, design and implement a MLP, train the model (atleast two model for comparision), and evaluate its performance.


- *Dataset Description:*

    - The dataset consists of images of rice grains from 5 different varieties: Arborio, Basmati, Ipsala, Jasmine, and Karacadag.
    - Each image is labeled with the type of rice grain it represents.
    - Images are in .jpg format and vary in size.

- *Objectives:*
    - Resize all images to a uniform size 32 * 32
    - Normalize pixel values to be in the range [0, 1]
    - Split the dataset into training, validation, and test sets (e.g., 70% train, 15% validation, 15% test) and report accuracy and loss value on each one.
    - Implement a basic feedforward neural network (MLP) using a deep learning framework.
    - Train the model on the training dataset and evaluate its performance on the test set.
    - Plot the training and validation accuracy/loss curves to analyze model performance over epochs.
