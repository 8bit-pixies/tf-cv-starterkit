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

Install anaconda or miniconda from here: https://www.continuum.io/downloads
If you are on windows rename `meta_windows_patch.yml` to `meta.yml`

**1 Create your `conda` environment**

```
conda env create -f environment.yml 
```

**2 Activate your environment**

The easiest way is to launch a jupyter notebook and select the correct kernel. 

![screenshot](screenshot.png)

Otherwise you can use:

```
source activate dl-uts
```

Or on Windows:

```
activate dl-uts
```


Troubleshooting
===============

I wish to uninstall the environment!

```
conda env remove -n dl-uts
```

