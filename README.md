# EYEXA
A Computer Vision and Machine Learning Solution to implement Social Distancing and Mandatory Mask wearing Tracking.



<p align="center">
    <img src="IMAGES/front.gif", width="480">
    <br>
    <sup>Authors <a href="https://www.gineshidalgo.com" target="_blank">Gines Hidalgo</a> (left) and <a href="https://jhugestar.github.io" target="_blank">Hanbyul Joo</a> (right) in front of the <a href="http://domedb.perception.cs.cmu.edu" target="_blank">CMU Panoptic Studio</a></sup>
</p>



### Download The EXE Version of the Software from GOOGLE DRIVE LINK

$ url : https://drive.google.com/drive/folders/15RZ0z6vU0P1gJg6QFXn7WegxYJEnjBdk





### Getting Started
- Clone the repo and cd into the directory
```sh
$ git clone https://github.com/raj713335/EYEXA.git
$ cd EYEXA
```


### Download The YOLOV3 Trained Model From the Following link and Save the file inside ./Model Directory

$ url : https://pjreddie.com/media/files/yolov3.weights





### Install tensorflow and all the other required libraries 

```sh
$ pip install tensorflow
$ pip install EasyTkinter
$ pip install opencv-python
$ pip install keras
$ pip install Pillow
$ pip install imutils
$ pip install numpy
```

### List of Python packages taht are being used in the Application

```sh
from tkinter import *
from tkinter.ttk import Combobox
import csv
import configparser
import tkinter as tk
from PIL import Image, ImageTk
import cv2
from datetime import date, datetime
import math
from tkinter import messagebox
from threading import Thread
import time
import socket
import tkinter.ttk as ttk
from tkinter import filedialog
import subprocess
from datetime import datetime
from home import display
from tensorflow.keras.applications.mobilenet_v2 import preprocess_input
from tensorflow.keras.preprocessing.image import img_to_array
from tensorflow.keras.models import load_model
from imutils.video import VideoStream
import numpy as np
import imutils
import time
import cv2
import os
import math
from main import mainc
from threading import Thread
from video_recorder import start```


### To run the Application


```sh
$ cd EYEXA
$ python EYEXA.py
```



### A Histogram Graph of the mask_detector.model based on mobilenet_v2

![](Model/Model.png)

<p align="center">
    <img src="Model/Model.png", width="480">
    <br>
    <sup>TRAINING of Model mask_detector.model Histogram</sup>
</p>
