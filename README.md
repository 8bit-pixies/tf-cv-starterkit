Starter kit for Tensorflow and Opencv. 

This will ensure that a standard environment is installed on everyones machine. 
If you wish to use GPU powered tensorflow, you will need to install the appropriate tensorflow package, either manually or through configuration. 

Overview
========

1.  Create `conda` environment
2.  Install `conda` environment (here)
3.  Each time you work, activate this environment

Setup
=====

Install anaconda or miniconda from here: https://www.continuum.io/downloads or here https://conda.io/miniconda.html

Install miniconda on your machine. Detailed instructions:

*  Linux: http://conda.pydata.org/docs/install/quick.html#linux-miniconda-install
*  Mac: http://conda.pydata.org/docs/install/quick.html#os-x-miniconda-install
*  Windows: http://conda.pydata.org/docs/install/quick.html#windows-miniconda-install

If you are on windows rename `meta_windows_patch.yml` to `meta.yml`

**1 Create your `conda` environment**

```
conda env create -f environment.yml 
```

**2 Activate your environment**

Use (*nix):

```
source activate dl-uts
```

Or on Windows:

```
activate dl-uts
```

**3 (Optional) Run Jupyter Notebook Server**

Once you have activated the environment, you can then run `jupyter notebook` and TensorFlow should now be available for you.


Troubleshooting
===============

I wish to uninstall the environment!

```
conda env remove -n dl-uts
```

