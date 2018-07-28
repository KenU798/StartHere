# StartHere
This repository contains the files you need to set up a private ML/AI playground on your laptop or PC

## How to install your playground

1. Install Anaconda on your laptop by following the instructions at this link to Anaconda.com:

    <https://docs.anaconda.com/anaconda/install/>
    
    Please install the latest version (currently the Python 3.6 version). I try to keep all my notebooks updated to run the latest version.
    
2. Verify your installation after install by following the instructions at this link:

    <https://docs.anaconda.com/anaconda/install/verify-install>
    
3. And then run through the quick tutorial on getting started with Anaconda and the Anaconda Navigator:

    <https://conda.io/docs/user-guide/getting-started.html>

2. Download the file: **TF36.yml** by clicking the green **Clone or download** button (above and to the right of the screen) and then clicking on "Download ZIP" in the dropdown menu that appears. This file is used to create a Python 3.6, Tensorflow 1.9 ML/AI environment your Anaconda installation that is the same as mine. All the Jupyter notebooks in my repositories should run in this environment. I've added necessary Python modules like Seaborn, Scikit Learn, etc. so you don't have to.

    You create the TF36 environment, after installing Anaconda on your laptop, by running this command in a terminal window:

    ```conda env create --file TF36.yml```
