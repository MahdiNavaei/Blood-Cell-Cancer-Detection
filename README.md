# Blood Cancer Detection using Deep Learning

This project aims to develop a deep learning model for blood cancer detection using Convolutional Neural Networks (CNNs). The model achieves a high accuracy of over 99% in identifying various types of normal blood cells.

## Dataset

The dataset used for training consists of 17,092 images of normal blood cells. These images were collected from individuals without any hematologic or oncologic diseases, ensuring a diverse and representative dataset for training the model.
Link : https://www.kaggle.com/datasets/mahdinavaei/blood-cancer

## Model Architecture

The deep learning model is built using CNNs, which have proven to be effective in image classification tasks. The architecture of the model includes convolutional layers for feature extraction followed by fully connected layers for classification.

## Training Process

The model was trained on the dataset using a standard training-validation split. The training process involved optimizing the model's parameters to minimize the loss function, thereby improving its accuracy in blood cancer detection.

## Results

The trained model achieved an impressive accuracy of over 99% on the validation set, demonstrating its effectiveness in detecting various types of normal blood cells.

## Usage

To use the trained model for blood cancer detection, simply input an image of a blood cell into the model, and it will predict the cell type with high accuracy.

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
