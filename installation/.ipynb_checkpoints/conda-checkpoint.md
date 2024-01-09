# Conda

In this course, you are supposed to do your assignments and projects in python. Therefore, I hope you already have your python 3 installed from your previous courses. 

Conda is a python package manager, which we will be using for this course. This makes managing the python environment and packages easy. If you already have it in your system well and good, if not, please follow [these instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation) to install conda in your system. 

```{note}
Make sure to install conda based on the version of python 3 that you installed.
```
```{attention}
Once you have finished installation, make sure you restart your terminal before trying out the following commands.
```

The following commands confirm that you have conda installed in your system, as it lists the version.

```{attention}
ggeorg02@MacBook-Pro ~ % is my terminal prompt. You want to paste what copy what comes after `%`. Eg, in below example `conda --version`
```

```bash
ggeorg02@MacBook-Pro ~ % conda --version
conda 4.10.3 
```
Check the python version that you have. 

```bash
(base) ggeorg02@MacBook-Pro ~ % python --version        
Python 3.8.5
```

Now let us create an environment that we will be using for this course. We are providing you with a conda environment file which is available here. You can download [this file](https://github.com/ggeorg02/BAIT580/blob/master/bait580env.yml) and create a conda environment for the course and activate it as follows.

```bash
(base) ggeorg02@MacBook-Pro ~ % conda env create -f bait580env.yml
(base) ggeorg02@MacBook-Pro ~ % conda activate bait580env
```

Note that this is not a complete list of the packages we'll be using in the course and there might be a few packages you will be installing using conda install later in the course. But this is a good enough list to get you started.

The above command activates the MBAN environment and will show the following in the terminal. 

```bash
(MBAN) ggeorg02@MacBook-Pro ~ %
```

```{note}
Notice the (base) changed to the (MBAN) once the MBAN environment is activated. 
```

[Here](https://docs.anaconda.com/anaconda/user-guide/tasks/install-packages/#installing-a-conda-package) are instructions on installing any additional packages using conda.

