Project Title: Venture Funding with Deep Learning

 I created a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successfulusing a  CSV file  containing more than 34,000 organizations that have received funding from Alphabet Soup over the years

Technologies The code is written in Py 3.0. We used Colab to run the program

Installation Guide - must be run in googlecolab - https://colab.research.google.com/

import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
import numpy as np



1.Prepared the Data for Use on a Neural Network Model.

2.Compiled and Evaluate a Binary Classification Model Using a Neural Network

3.Evaluated the model using the test data to determine the model’s loss and accuracy.

4.Saved and export your model to an HDF5 file, and name the file AlphabetSoup.h5.

5.Optimized the Neural Network Model

Contributors In addtion to me the GW Bootcamp TA, LA, and tutors help me create this project

License The Source code is for educational purposes only and should not be used to make any professional recomendations. Feel free to use for any educational needs