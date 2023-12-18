.. code:: ipython3

    import xarray as xr
    import matplotlib.pyplot as plt
    import seawater
    import numpy as np
    import pandas as pd
    import cartopy.crs as ccrs
    from cartopy.feature import NaturalEarthFeature
    from mpl_toolkits.basemap import Basemap
    import matplotlib.ticker as mticker
    from cartopy.mpl.gridliner import LONGITUDE_FORMATTER, LATITUDE_FORMATTER
    import matplotlib.dates as mdates
    import datetime as dt
    import pylab
    from matplotlib.dates import YearLocator, MonthLocator, DateFormatter
    import matplotlib.ticker as ticker
    from mpl_toolkits.axes_grid1 import make_axes_locatable
    from mpl_toolkits.axes_grid1.axes_divider import make_axes_area_auto_adjustable
    import matplotlib as mpl
    import matplotlib.transforms as mtransforms
    from matplotlib.patches import Circle
    from matplotlib.offsetbox import (TextArea, DrawingArea, OffsetImage,
                                      AnnotationBbox)
    from mpl_toolkits.axes_grid1.inset_locator import zoomed_inset_axes, mark_inset
    from mpl_toolkits.axes_grid1.anchored_artists import AnchoredSizeBar
    from matplotlib.offsetbox import OffsetImage,AnchoredOffsetbox
    import matplotlib.image as image


.. parsed-literal::

    /home/lenovo/miniconda3/envs/envplot/lib/python3.10/site-packages/scipy/__init__.py:155: UserWarning: A NumPy version >=1.18.5 and <1.25.0 is required for this version of SciPy (detected version 1.25.2
      warnings.warn(f"A NumPy version >={np_minversion} and <{np_maxversion}"


.. code:: ipython3

    !python --version


.. parsed-literal::

    Python 3.10.12


