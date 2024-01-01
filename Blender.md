# Getting started with Python and Blender

The goal here is to install and configure software to script in Python and use Blender to generate animated geometries.
I developed this on my Mac, which should be similar in Linux, and will likely require some modifications in Windows.

The instructions assume that you've got python up and running with VS Code (instructions [here](Python.md)).

## Setting up python in Blender

Blender installs with its own copy of Python and has a build-in text editor and ability to execute Python scripts.
I was unable to run the Blender interpreter within VS Code, but it is possible to use VS Code as a text editor for code that is executed within Blender. 

By default, you cannot install packages in the Blender install of Python. 
So, after installing [Blender](https://www.blender.org/download/), I wanted to be able to install python packages.
I achieved this with the following steps (outlined [here](https://blender.stackexchange.com/questions/218486/how-to-install-python-modules-in-blender?noredirect=1#comment368756_218486)):

1. Enable full permissions to blender's python at the Terminal:

    > sudo chmod ug+rwx "/Volumes/Macintosh HD/Applications/Blender.app/Contents/Resources/3.4/python/bin/python3.10" 

1. Download get-pip.py from [here](https://pip.pypa.io/en/stable/installation/) and move it to the python directory ("/Volumes/Macintosh HD/Applications/Blender.app/Contents/Resources/3.4/python/bin").

1.  Install pip:
    > "/Volumes/Macintosh HD/Applications/Blender.app/Contents/Resources/3.4/python/bin/python3.10" get-pip.py

1. Now, packages (like 'plotly') can be installed like this:

    >"/Volumes/Macintosh HD/Applications/Blender.app/Contents/Resources/3.4/python/bin/python3.10" -m pip install plotly

You can test all of this by importing the package at the command prompt in blender:

> import plotly

## Set up an environment for Blender code

Although the ultimate plan was to execute the python code in Blender, it can be helpful to be able to run snippets of code within VS Code during development. 
I therefore set up an environment for developing Blender code.
At this time, Blender runs python 3.10.

At the terminal:

> conda create -n blender python=3.10

And then activated the environment and installed some useful packages:
> conda activate blender

> conda install numpy pandas ipykernel h5py

Within VS Code, I then made sure to select this interpreter for running the code.



