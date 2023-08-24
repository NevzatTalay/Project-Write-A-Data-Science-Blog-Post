<h1 align="left">Project: Write a Data Science Blog Post</h1>
<h3 align="left"><a href='https://www.udacity.com/course/data-scientist-nanodegree--nd025'>Udacity Data Scientist Nanodegree Program</a></h3>
Project No: 1

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>
<img src ="resources/Jupyter Notebook sign.svg/"></img>
Use Jupyter Notebook to open file. **Exploring_StackOverflow_2017_Survey_Turkey.ipynb**


Install requires libraries
```
pip install pandas, sikitlearn, seaborn, geopandas
```
Import looks like this
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import math
import os
import seaborn as sns
import geopandas as gpd
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score, confusion_matrix
%matplotlib inline
```


## Project Motivation <a name="motivation"></a>
* Where do global software developer salaries stand, and where does Turkey fit into this picture?
* How do the programmers in Turkey distribute in terms of gender, salary, and work arrangements?
* How Effective Mindsets on Job Satisfaction? Are There Mindset Patterns of Successful Individuals in Turkey?

## Results <a name="results"></a>
These question are the main motivation of the project.

Despite Turkey showing promise in terms of future contributions compared to other countries, it stands out as one of the countries lagging behind globally in terms of average salaries. Additionally, a significant portion of the workforce in Turkey consists of salaried employees, distinguishing it from some other countries.

Similar to worldwide trends, gender distribution in Turkey is not equal. The industry is predominantly male-oriented. Finally, there isn't a significant gender-based wage disparity, but this assessment should be approached cautiously. This is due to the fact that in the examined country, Turkey, non-male orientations have an imbalanced representation in the dataset. It's evident that more data collection is necessary for more robust evaluations.

To have a strong job satisfaction, we expect you to receive the salary you deserve, perceive your job as requiring seriousness, be open to learning new technologies, and enjoy problem-solving. Additionally, being in competition with your colleagues seems to significantly reduce your job satisfaction. On the other hand, setting ambitious goals and having aspirations to change the world appear to enhance your job satisfaction. When all these results are examined, they seem consistent with one another. This is because individuals with such a mindset are anticipated to lead successful and fulfilling lives in the present day.
