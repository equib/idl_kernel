#This package is originally from [github.com/lstagner/idl_kernel](https://github.com/lstagner/idl_kernel) and modified to work with Python 3.9. IDL also has an [official Jupyter kernel](https://www.harrisgeospatial.com/docs/IDL_Kernel.html)
#IDL/GDL kernel for IPython/Jupyter

Demo [Notebook](http://nbviewer.ipython.org/github/lstagner/idl_kernel/blob/master/demo.ipynb)

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


