# CS229-Music-Classification

## Introduction
This repo contains code for our music genre classifiaction project.

## Project Layout
The project contains mainly 3 parts.

1. Preprocessing is done to allows us to represent the music as a 2D array. The code is in "Haojun_Preprocessing.ipynb". The code should be fairly self explanatory.

2. Then we trained a dilated CNN to achieve reasonable performance. The code is in "Haojun_CNN_au.ipynb". Some of the code are changed during iterations and results are not present to simplify the notebook. Feature extraction code is also in the same notebook.

3. The post processing code that runs on SVMs and other classical algorithms can be found in "after_cnn_classic-Copy1.ipynb" as well as other baseline classical algorithm experiments.
