# ML Tutorial | Shaastra 2020


## Installation Notes

You can skip all the installation steps if you can use https://colab.research.google.com/ to use these notebooks.

This tutorial requires the following packages:

- Python version 2.6-2.7 or 3.3+
- `numpy` version 1.5 or later: http://www.numpy.org/
- `scipy` version 0.10 or later: http://www.scipy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `scikit-learn` version 0.14 or later: http://scikit-learn.org
- `ipython` version 2.0 or later, with notebook support: http://ipython.org
- `seaborn` version 0.5 or later

The easiest way to get these is to use the [conda](https://store.continuum.io/) environment manager.
I suggest downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).

Once this is installed, the following command will install all required packages in your Python environment:
```
For the current versions of Anaconda (Mar 2018)
 
$ conda create -n skl_tut python=3.4.5 ipywidgets=5.2.2 numpy scipy matplotlib scikit-learn ipython-notebook seaborn pillow

$ activate skl_tut

$ jupyter notebook --notebook-dir='<tutorial folder>'
```

Alternatively, you can download and install the (very large) Anaconda software distribution, found at https://store.continuum.io/.

## Downloading the Tutorial Materials
I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

    git clone https://github.com/14thApostle/ML.git

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  I may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.

This repo was forked over from *Jake VanderPlas*
