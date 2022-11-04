# IDL/GDL kernel for IPython/Jupyter

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/equib/idl_kernel/HEAD?labpath=demo.ipynb)


Demo: [Notebook](notebooks/demo_gdl.ipynb) on [Binder](https://mybinder.org/v2/gh/equib/idl_kernel/HEAD?labpath=demo.ipynb).

This package is originally from [github.com/lstagner/idl_kernel](https://github.com/lstagner/idl_kernel) and modified to work with Python 3.9. This repository also makes use of [GDL](https://github.com/gnudatalanguage/gdl) to run IDL/GDL codes in Jupyter lab. This requires the following component:

* `apt.txt` for apt-installing the gnudatalanguage (gdl) component.

The current version was found to work with pexpect 4.6, jupyter 4.4, and jupyter-notebook 5.7. IDL also has an [official Jupyter kernel](https://www.harrisgeospatial.com/docs/IDL_Kernel.html).


To install:

This requires IPython >3.0 and Pexpect 3.3

```
python setup.py install --prefix=~/.local
```

This should make an IDL directory containing the kernelspec in the ~/.ipython/kernels directory.

To run:
``` 
ipython console --kernel IDL 
```
or
```
ipython qtconsole --kernel IDL
```
or 
```
jupyter notebook 
#Select kernel from dropdown menu
```
