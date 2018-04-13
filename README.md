# Transient Astrophysics
This repository contains all the material needed for the Transient Astrophysics course held at Gran Sasso Science Institute - [GSSI](http://www.gssi.infn.it/). We provide sample code in Python; you can download the documents and run the code samples in [Jupyter Notebookk](http://jupyter.org/). To install Jupyter Notebook see [here](http://jupyter.org/install.html).


# Installation and initialization

For this tutorial, we will use the [astropy.vo](http://astrofrog-debug.readthedocs.org/en/latest/vo/index.html) astropy subpackage for accessing to the Virtual Observatory (VO) services. The [astropy.utils](http://astrofrog-debug.readthedocs.org/en/latest/utils/) subpackage contains general-purpose utility functions, [astropy.table](http://docs.astropy.org/en/stable/table/) provides functionality for storing and manipulating heterogeneous tables, [numpy](http://www.numpy.org/) for scientific computing with Python, [urlparse](https://docs.python.org/2/library/urlparse.html) is a standard interface to break Uniform Resource Locator (URL) strings up in components (the urlparse module is renamed to urllib.parse in Python 3) and  [future](https://pypi.python.org/pypi/future) for running under Python 2 and Python 3. The last section makes use of [ipywidgets](https://pypi.python.org/pypi/ipywidgets); they are interactive HTML widgets for Jupyter notebooks and the IPython kernel.

# Aladin and TOPCAT 
It is important to have installed beforehand in your laptops the VO-tools to be used in the School.

[ALADIN](http://aladin.u-strasbg.fr/). Download the Aladin.jar file and execute it from a terminal typing

                                $ java -Xmx2048m -jar Aladin.jar
          
[TOPCAT](http://www.star.bris.ac.uk/~mbt/topcat/). Download the topcat-full.jar file and execute it from a terminal typing 

                                $ java -jar topcat-full.jar
