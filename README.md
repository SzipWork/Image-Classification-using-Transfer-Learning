# Image Classification using Transfer Learning

This project demonstrates image classification using transfer learning on the "Dogs vs. Cats" dataset.

## Dataset
The dataset is downloaded from Kaggle: `salader/dogs-vs-cats`.

## Requirements
Ensure you have the following installed:
- Python
- Jupyter Notebook
- TensorFlow
- Keras
- Kaggle API (for dataset download)

## Setup
1. Place your Kaggle API key (`kaggle.json`) in the working directory.
2. Run the notebook to download and extract the dataset.
3. The dataset will be stored in the `/content` directory.

## Model
- A pre-trained model (likely from TensorFlow's Keras applications) is used for transfer learning.
- The model is fine-tuned for classifying images as either a dog or a cat.

## Usage
- Execute the notebook to train and evaluate the model.
- The model's performance metrics are displayed at the end of the training process.

## Results
- The trained model predicts whether an image contains a dog or a cat with high accuracy.

## Notes
- Modify hyperparameters or try different pre-trained models to improve accuracy.
- Ensure a stable internet connection for downloading datasets and dependencies.

## Author
This project was created as part of an image classification study using transfer learning.

