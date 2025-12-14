# Deep Learning Project – Mushroom Classification
A deep learning project that classifies mushroom images as edible or poisonous using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. The project demonstrates a complete workflow including data cleaning, preprocessing, model training, and evaluation.

Task: Binary image classification
Input: 256×256 RGB images
Classes: Edible, Poisonous

## Dataset name and structure:
Edible & Poisonous Mushroom Classification (Kaggle) - 2,820 images in total
data/train/{edible,poisonous}
data/val/{edible,poisonous}
data/test/{edible,poisonous}

## Model: CNN
3 convolutional layers (16, 32, 64 filters) with max-pooling and dropout, followed by a dense layer and sigmoid output. Trained using Adam optimizer and binary cross-entropy loss.

## Preprocessing:
Corrupted and invalid images removed, files smaller than 10 KB filtered out, and pixel values normalized to [0,1].

## Evaluation:
Accuracy, precision, recall, confusion matrix, and training/validation learning curves.

## Run:
pip install tensorflow numpy matplotlib pillow scikit-learn
python mushroom_project.py
