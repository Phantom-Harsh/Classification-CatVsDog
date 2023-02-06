# Classification-CatVsDog
**Cats vs Dogs Classification**
The goal of this project is to create a deep learning model to classify whether an image is of a cat or a dog. The dataset used for this project is the cats_vs_dogs dataset from the tensorflow_datasets library.

Prerequisites
tensorflow
tensorflow_datasets
numpy
matplotlib
File Description
multiplication.py : The main script that trains and evaluates the model.
dogs_vs_cats.h5 : The saved weights of the model.
How to run
Install the required packages mentioned in the prerequisites section.
Run the script by executing python multiplication.py in the terminal.
Data Preprocessing
The dataset is split into train, validation, and test sets.
Each image is preprocessed by normalizing the pixel values and resizing it to 160x160x3.
Model Architecture
The model is based on the MobileNetV2 architecture and is trained on the cats_vs_dogs dataset. The base model is fine-tuned and the last few layers are added to make predictions.

Evaluation
The model is evaluated by making predictions on the test set and visualizing the images with their corresponding predictions.



