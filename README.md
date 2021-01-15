# README
Here is the readme of the project of Information Visualization. Below you will find a few instructions to execute the notebook I develop to present a visualization about the dataset (https://gricad-gitlab.univ-grenoble-alpes.fr/blanchr/2020-carbon)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all the libraries that we need. Below you'll see the list:

```bash
import csv
import pandas as pd
import os
import collections
import geopandas 
import numpy as np
from descartes import PolygonPatch
from shapely.geometry import LineString, MultiLineString
import matplotlib as mpl
import matplotlib.pyplot as plt
import numpy as np
from matplotlib.widgets import Slider
import mpld3
from mpld3.utils import get_id
from mpld3 import plugins
from ipywidgets import interact, interactive, fixed, interact_manual
import ipywidgets as widgets
```
```bash
##Here is how what you need to do to install them. One by one.
pip install lib
```

## Usage

To visualize the project you'll need to have Jupyter notebook on your computer. (I know there there is others environments as Colab. However, I cannot guarantee that the visualization will work properly in others enviroments as long as I just use it on jupyter)

Then, you need to run it in the decompressed folder.
```bash
jupyter-notebook
```

After that, a web page should open and you may click twice on the Info_vis.ipynb notebook.

There, you will find the code that I did to develop the visualization as well as a lot of markdown cells that are explaining the visualization and can be considered as report.
