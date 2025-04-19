# Displacement_prediction_Fully-Gouted-Masonry-Walls
This repository features the python code for GUI developed to predict lateral displacement of fully grouted masonry walls under in-plane axial loading.
Here are some tips how we have developed the GUI.
1) Python must be installed.
2) relevant libraries must be installed including, for user ease import following libraries
-------------------------------------------------------------
import tkinter as tk
from tkinter import ttk
from math import pow, sqrt
from PIL import Image, ImageTk
import xgboost as xgb
import numpy as np
from sklearn.model_selection import train_test_split
import pandas as pd
from sklearn.multioutput import MultiOutputRegressor
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import xgboost as xgb
from sklearn.model_selection import train_test_split
from sklearn.model_selection import cross_val_score, KFold
from sklearn.multioutput import MultiOutputRegressor
from sklearn.metrics import mean_squared_error
class RangeInputGUI:
-------------------------------------------------------------

2) Run it in IDEs such as VS code, Jupyter notebook, Anaconda, Spyder, etc.
3) Load code*.

* Make sure to change directory 

Tips to run code.
1) Install all libraries
2) Make sure all files uploaded here are contained in relevant folder
3) Just run the code.
4) Using scroll adjust input values
5) Click on predict under model (click on relevant property to be predicted)
6) See output
7) Clear the values using clear button
8) Change values and repeat the process from 2 to 6
