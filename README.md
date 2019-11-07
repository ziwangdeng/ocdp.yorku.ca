# Ontario Climate Data Portal (OCDP)

>
* Sample python programs for reading, plotting and exporting data from OCDP. 
* Datasets include ensemble means at provincial, region, municipal and grid resolution.
* Variables include basic variables: temperature, maximum temperature, minimum temperature and precipitation; 38 extreme indices


## Used packages
```python
import pandas as pd  
import numpy as np
import matplotlib.pyplot as plt 
import geopandas as gpd   #create maps
from shapely.geometry import Polygon  #create maps
from geopandas import GeoSeries  # create maps
import requests          # download file from website to local machine
import h5py              # for read matlab data in v7.3 format
import scipy.io as sio   # for read matlab data file
```

## Packages installation
* [Anaconda](https://www.anaconda.com/distribution/): Anaconda includes many popular python packages

* [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html): If Anaconda is installed, Jupyter Notebook should have been installed

* [GeoPandas](http://geopandas.org/install.html): It's better use conda to install this package,it will be difficult to install with pip
```bash
conda install geopandas
conda install h5py
```

## Program list:
* *Extract-data_map_basicVariables.ipynb*

## License
[MIT](https://choosealicense.com/licenses/mit/)
