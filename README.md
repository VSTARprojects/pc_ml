## Deep Learning Model for Pathology Image Classification using Transfer Learning

This Jupyter Notebook provides a deep learning model for classifying pathology images using TensorFlow. The model is designed to work with three different datasets, which need to be organized into training, testing, and validation sets before running the model.

There are three separate components for this project:

1. ML Model: https://github.com/VSTARprojects/pc_ml
2. FrontEnd: https://github.com/VSTARprojects/pc_fe
3. BackEnd: https://github.com/VSTARprojects/pc_dj

### Prerequisites
Before running the notebook, you will need the following:

- A working installation of TensorFlow https://www.tensorflow.org/install
- Download the required datasets. We have used the following:
  - Renal: https://bmirds.github.io/KidneyCancer/
  - Colon: https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images
  - Gastric: https://data.mendeley.com/datasets/thgf23xgy7
- Install Jupyter Notebook https://jupyter.org/install

### Getting Started
- Download the Jupyter Notebook and open it in your preferred notebook environment.
- Organize your datasets into separate directories for training, testing, and validation. The directories should be named train, test, and valid, respectively.
- Within each of these directories, create subdirectories for each class of pathology that you want to classify. For example, "colon_adenocarinoma", "colon_normal", "renal_clearcell" and so on...
- Place the appropriate images in each subdirectory.
- Modify the code in the notebook to point to the correct directories and set any necessary hyperparameters.
- Run the notebook and wait for the model to finish training.

### Note on Datasets
It is important that the datasets are organized correctly in order for the model to work properly. Each image should be in its own file and each file should be named uniquely, preferably with a sequential number.
