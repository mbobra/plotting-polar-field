# plotting-polar-field
plotting the polar field (python + d3)

Throughout an 11-year solar cycle, the Sun's [magnetic field flips](http://nbviewer.ipython.org/github/mbobra/plotting-polar-field/blob/master/plot_polarfield_d3.ipynb) and [active regions migrate](http://nbviewer.ipython.org/github/mbobra/plotting-polar-field/blob/master/butterfly.ipynb) from mid to low latitudes. Here is an example that shows the evolution of the magnetic field at the solar surface -- as observed by two different satellites, NASA's [Solar Dynamics Observatory](http://sdo.gsfc.nasa.gov/) and NASA/ESA's [Solar and Heliospheric Observatory](https://sohowww.nascom.nasa.gov/) -- over two solar cycles, or 22 years:

<img src="https://github.com/mbobra/plotting-polar-field/blob/master/butterfly.png" width="100%"></img> 

In these notebooks, you can interactively browse through years of solar magnetic field data using the home, pan, and zoom buttons on the lower left-hand corner of each data visualization; you can also view these visualizations at the [Helioseismic and Magnetic Imager Polar Field website](http://jsoc.stanford.edu/data/hmi/polarfield/).  These notebooks plot data using [mpld3](https://mpld3.github.io/), which is a python interface for [d3](http://d3js.org/).