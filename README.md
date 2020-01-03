# ASHRAE---Great-Energy-Predictor-III

*libraries used during this project:

import numpy as np
import pandas as pd 
import seaborn as sns
import matplotlib.pyplot as plt
import matplotlib.pyplot as pyplot
import gc
from sklearn.preprocessing import LabelEncoder
import math
import warnings
from keras.models import Sequential
from keras.layers import Dense, Dropout, Activation, Flatten
from keras.layers import Conv2D, MaxPooling2D,ZeroPadding2D
from keras.models import Sequential
from keras.layers import Dense
from keras.models import Model, load_model
from keras.layers import Input, Dropout, Dense, Embedding, SpatialDropout1D, concatenate, BatchNormalization, Flatten
from keras.preprocessing.sequence import pad_sequences
from keras.preprocessing import text, sequence
from keras.callbacks import Callback
from keras import backend as K
from keras.models import Model
from keras.losses import mean_squared_error as mse_loss

from keras import optimizers
from keras.optimizers import RMSprop, Adam
from keras.callbacks import EarlyStopping, ModelCheckpoint, ReduceLROnPlateau


*Project goal:
How much energy will a building consume?

*Data description:
The dataset includes three years of hourly meter readings from over one thousand buildings at several different sites around the world.

-Files:  train.csv,building_meta.csv,weather_[train/test].csv,test.csv,sample_submission.csv


      
