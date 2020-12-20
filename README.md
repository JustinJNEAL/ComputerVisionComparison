# ComputerVisionComparison
In this project, I compare the results of using SVMs and Neural Networks in the field of Computer Vision

## Overview
I used two datasets in the project, which can be found in the Dataset header. The Animals-10 dataset was used to train the model, while the Cats dataset was used to test the model. The confusion matrices from each model can be found in the ***plots*** directory.

## Software Dependencies
* Jupyter-Lab / Jupyter Notebook - `pip install jupyterlab` / `pip install notebook`
* Keras-Tuner - `pip install keras-tuner`
* Matplotlib - `pip install matplotlib`
* Numpy - `pip install numpy`
* Seaborn - `pip install seaborn`
* Scikit-Image - `pip install scikit-image`
* Scikit-Learn - `pip install scikit-learn`
* TensorFlow - `pip install tensorflow`

## Datasets
* [Animals-10](https://www.kaggle.com/alessiocorrado99/animals10)
* [Cats](https://www.kaggle.com/crawford/cat-dataset)

**Note:** these datasets will not work with the code out of the box. Some minor modifications will need to be made. These include changing directory names, removing non-image files, and moving some files into one directory.