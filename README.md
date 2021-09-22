# Project

The idea behind this project was based when I have recently visited at a house that I used to stay while vacation when I was a kid. Walking in one of the rooms, I saw a height chart drawing on the wall. I've drawn those charts every single time I went there to see my height throughout the time, and after 14 years there I was. So I thought "Back in the day I didn't have a clue how to programming I have to use chalk to do it, why not to use Machine Learning Model to predict the height based on the age?!"

## 🧰 Tools and Libraries 

1. Python
2. Flask
3. Heroku

* Pandas
* Numpy
* Plotly
* Joblib

```
from flask import Flask, render_template, request
import numpy as np
import pandas as pd
from joblib import load
import plotly.express as px
import plotly.graph_objects as go
import uuid
```

## Overview 

To develop the model Pandas, Numpy, Plotly and Joblib is essential. To train the model, I searched for a Database that contains the data needed (Heights and Ages) for training the model.  After I found the Data Frame, I have to clean and transform the data points. To do this, Excel was used for cleaning the data and Python to transform and gather the data. After the transformation, the Data Frame was ready to be used.
For this model Linear Regression is the best way to calculate the input (age) of the user and predict the future value of the output (height). To plot the output the library used to be Plotly.

## The Web App

For demonstration of the web app I used simple HTML code and is hosted in the cloud application platform Heroku. 

Here's the link: https://webapp-height-age.herokuapp.com/

![](/app/static/webapp.png)
