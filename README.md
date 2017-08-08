# Project Topic: Webcams, Predictions, and Weather

In this project, several experiments are run to answer the following questions:

Can we point a webcam out a window and use the images to figure out the weather?
What type of weather information can we "reliable" determine?

--------------------------------------------------------------------------------

# Getting started

To be able to run the project on your computer you need to have installed,
Python 3.5 or 3.6 and a few libraries for it. You can install them directly on 
Debian/Ubuntu or download Anaconda which installs them for you.

## In Debian/Ubuntu
```
$ sudo apt-get install python3 python3-dev python3-pip
$ sudo apt-get build-dep python3-scipy python3-matplotlib
$ pip3 install --user scipy matplotlib bokeh pandas statsmodels scikit-learn scikit-image numexpr jupyter
```

## With Anaconda

You can go to the Anaconda download page and get the Python 3.6 installer.
Install according to their instructions.


Next, clone the project repository onto your computer.

```
$ git clone https://csil-git1.cs.surrey.sfu.ca/alizardo/cmpt318-project.git
```

Move into the project folder you just cloned and run:

```
$ jupyter notebook
```

Then, just run the project by opening the "project.ipynb" file.
