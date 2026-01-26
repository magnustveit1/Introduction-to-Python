# Introduction-to-Python
This tutorial covers basic Python, including NumPy and Pandas libraries to support Civil Engineers and Hydrologists training with fundamental skills in Python.
The .ipynb files in this tutorial have been modified from other, with the original authors referenced the respective readme.md files.

# Getting Started: 
Please fork this repo to your GitHub account.
Next, identify a folder location where you would like to work in a development environment.
Using the command prompt, change your working directory to this folder and git clone https://github.com/USERID/Introduction-to-Python

    git clone https://github.com/USERID/Introduction-to-Python


## Virtual Environment
It is a best practice to create a virtual environment when starting a new project, as a virtual environment essentially creates an isolated working copy of Python for a particular project. 
I.e., each environment can have its own dependencies or even its own Python versions.
Creating a Python virtual environment is useful if you need different versions of Python or packages for different projects.
Lastly, a virtual environment keeps things tidy, makes sure your main Python installation stays healthy and supports reproducible and open science.

    cd Introduction-to-Python
    conda env create -f 310environment.yml
    conda activate p310env

In some cases:

    conda install ipykernel
    python -m ipykernel install --user --name=p310env

## Lets get started!

This repositories consists of three core Python topics:
* [Introduction to Python](./Intro2Python/)
* [NumPy](./NumPy/)
* [Pandas](./Pandas/)

Each section will help new users gain confidence in the fundamentals of Python, and prepare new developers for more complex modules and to start developing their own codebase. 

