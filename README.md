<h2>Semantic Data Visualisation of Airbnb listings</h2>

## Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Project Motivation and Content](#project_motivation_and_content)
* [Results](#results)
* [Acknowledgement](#acknowledgement)

<h4>Introduction</h4>

This is a training project. I'd like to answer the question "Can you describe the vibe of Airibn listing using listing user-generated comments?" with my research. The goal of this exercise is to utilise user - generated content to build a short description for each property and to visualise it on a map.

<h4>Technologies</h4>

I used 3.6 and Jupyter Notebooks for this research project.
There are few libraries that are needed to be installed in order to work with the notebook
 - Numpy <br>
 - Pandas<br>
 - Counter (from collections import Counter)<br>
 - NLTK <br>
 - Folium<br>
 - Plotly<br>
<br>

## Setup
To run this project, install the following libraries:

```
import pandas as pd
import numpy as np
from collections import Counter
import datetime as dt
import nltk
from nltk import ngrams
import folium
import plotly.graph_objects as go
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
```

<h4>Project Motivation and Content: </h4>

  I'd like to answer the following questions in my research:<br> <br>
- "Can you describe the vibe of each Boston neighborhood using listing descriptions?"<br>
- "Is there a correlation between a number of reviews and average rating?"<br>
- "What kind of review component correlate most with an overal rating?"<br>

The repository contains only one file - Jupyter notebook covers all the process from data extraction to modelling and visualisation.

<h4>Results</h4>
The main findings can be found in the post accessible <a href='https://olegmonakhov.medium.com/this-is-an-easy-guide-on-how-to-visualise-semantic-data-on-a-map-3b39859c5f58'> here </a>

<h4>Acknowledgement</h4>

This dataset is part of Airbnb Inside, and the original source can be found here http://insideairbnb.com/get-the-data.html.
