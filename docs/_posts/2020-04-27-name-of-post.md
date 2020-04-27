---
layout: post
title:  "Setup and Installation"
date:   2020-04-27 21:28:44 +0100
categories: kotlin
---

This project makes use of `Juypter Notebook` as an interacctive shell to write kotlin code. To get it running use the following steps


### 1. Setup a python virtual environment
First install the virtual environment system `virtualenv` . See instructions [here](https://virtualenv.pypa.io/en/stable/installation.html)


In a new directory start a new virtual environment as follows

`virtualenv .`

To start the virtual environment run the following command in the same directory:

`source bin/activate`

### 2. Install `Juypter Notebook`

Next, install notebook using pip

`pip install jupyterlab`


### 3. Installing kotlin kernel
Juypter supports multiple kernels and has python as the default. To run kotlin in the notebooks, we will need to install a kotlin shell.

`pip install kotlin-jupyter-kernel`

### 4. Starting a new notebook
To start a new notebook use the command:

`juypter notebook`

This will open a new browser window pointing to ` http://localhost:8888/` or similar. You should now see an option to create a new notebook using kotlin shell.
![png]({{ "/assets/images/installation_complete.png" }})

Next, we will create a new notebook and write some kotlin code
