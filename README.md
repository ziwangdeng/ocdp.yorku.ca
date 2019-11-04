# Ontario Climate Data Portal (OCDP)
>
* Read, plot and export data from OCDP using Python programs. 
* Datasets include ensemble means at provincial, region, municipal and grid resolution.
* Variables include basic variables: temperature, maximum temperature, minimum temperature and precipitation; 38 extreme indices
---

## Packages installation
### [Download and install Anaconda](https://www.anaconda.com/distribution/)

### [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html)

### [GeoPandas](http://geopandas.org/install.html)
```bash
conda install geopandas

```
## usage
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import geopandas as gpd
from shapely.geometry import Polygon
from geopandas import GeoSeries
```

## License
[MIT](https://choosealicense.com/licenses/mit/
