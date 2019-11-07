
# Ontario Climate Data Portal (OCDP)
![ocdp](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pics/ocdp.PNG)

>
* Sample python programs for reading, plotting and exporting data from OCDP. 
* Datasets include ensemble means at provincial, region, municipal and grid resolution.
* Variables include basic variables: temperature, maximum temperature, minimum temperature and precipitation; 38 extreme indices
* Bias corrected daily data products from LAMPS and CORDEX


## Used packages
```python
import pandas as pd  
import numpy as np
import matplotlib.pyplot as plt 
import geopandas as gpd   #create maps
from shapely.geometry import Polygon  #create maps
from geopandas import GeoSeries  # create maps
import requests          # download file from website to local machine
import h5py              # read matlab data in v7.3 format
import scipy.io as sio   # read matlab data file
```

## Packages installation
* [Anaconda](https://www.anaconda.com/distribution/): Anaconda includes many popular python packages

* [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html): If Anaconda is installed, Jupyter Notebook should have been installed

* [GeoPandas](http://geopandas.org/install.html): It's better use conda to install this package,it will be difficult to install with pip
```bash
conda install geopandas
conda install h5py
```

## Programs list:
### Maps section (grids)
* [Extract-data_map_basicVariables.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-data_map_basicVariables.ipynb)
* [Extract-data_map_indices.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-data_map_indices.ipynb)
### Time series section (province, regional and municipal)
* [Extract-data_timeseries.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-data_timeseries.ipynb)
### Data section
* [Extract-data_data_Historical.ipynb](Extract-data_data_Historical.ipynb)
* [Extract-data_data_Future_EnsembleMean_Province.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-data_data_Future_EnsembleMean_Province.ipynb)
* [Extract-data_data_Future_EnsembleMean_Regions.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-data_data_Future_EnsembleMean_Regions.ipynb)
* [Extract-data_data_Future_EnsembleMean_Municipalities.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-data_data_Future_EnsembleMean_Municipalities.ipynb)
* [Extract-data_data_Future_EnsembleMean_Grids.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-data_data_Future_EnsembleMean_Grids.ipynb)
* [Extract-Data_Database_Future_Grids_Daily_singlemodel.ipynb](https://github.com/ziwangdeng/ocdp.yorku.ca/blob/master/ocdpData/pythonCode/Extract-Data_Database_Future_Grids_Daily_singlemodel.ipynb)

## License
[MIT](https://choosealicense.com/licenses/mit/)
