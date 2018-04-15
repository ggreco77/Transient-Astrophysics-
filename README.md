# Transient Astrophysics
This repository contains all the material needed for the Transient Astrophysics course held at Gran Sasso Science Institute - [GSSI](http://www.gssi.infn.it/). We provide sample code in Python; you can download the documents and run the code samples in [Jupyter Notebookk](http://jupyter.org/). To install Jupyter Notebook see [here](http://jupyter.org/install.html).


# Installation and initialization

We will need to install a few third-party Python packages to run the example code in this tutorial. They are:


[healpy](https://healpy.readthedocs.org/en/latest/) for reading the probability sky map files, [mocpy](https://github.com/tboch/mocpy) for parsing and manipulating MOCs, [astropy](http://www.astropy.org/)  package contains key functionality and common tools needed for performing astronomy and astrophysics with Python, [astropy.samp](http://astrofrog-debug.readthedocs.org/en/latest/vo/index.html) is a Python implementation of the SAMP (Simple Application Messaging Protocol) messaging system, [astroquery](https://astroquery.readthedocs.io/en/latest/) for querying astronomical web forms and databases, [scipy](https://www.scipy.org/) and [numpy](http://www.numpy.org/) for scientific computing with Python, the  2D plotting library [matplotlib](https://matplotlib.org/) and [GWsky](https://github.com/ggreco77/GWsky) for tiling a skymap in field of views (only for Python 2.7.x). The tutorials make use of [ipywidgets](https://pypi.python.org/pypi/ipywidgets); they are interactive HTML widgets for Jupyter notebooks and the IPython kernel and [ipyaladin](https://github.com/cds-astro/ipyaladin) enabling interactive sky visualization in IPython notebooks.

# Aladin and TOPCAT 
It is important to have installed beforehand in your laptops the VO-tools to be used in the School.

[ALADIN](http://aladin.u-strasbg.fr/). Download the Aladin.jar file and execute it from a terminal typing

                                $ java -Xmx2048m -jar Aladin.jar
          
[TOPCAT](http://www.star.bris.ac.uk/~mbt/topcat/). Download the topcat-full.jar file and execute it from a terminal typing 

                                $ java -jar topcat-full.jar
