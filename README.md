# GP-BO-Clustering Tutorial
This repository contains instructional **Jupyter Notebook** (.ipynb files) for the following machine learning technique:
- Gaussian Process (Focus on Gaussian Process Regression)
- Bayesian Optimization(Pending)
- Clustering (Pending)

And a **Fundamental.ipynb** notebook to cover every necessary math, statistic, and machine learning concepts to learn gaussian process.

The notebooks include **texts, equations, math derivations, and static/interactive visualizations** for most concepts covered.

# Jupyter Notebook Setup Guide

This guide will help you install Python; Jupyter Notebook, the carrier format in this repo; and VS Code, a powerful IDE to run jupyter notebook file.

## Installation Steps

### Step 1️:Install Conda or Miniconda
Anaconda (and its light version miniconda) is a package and environment manager that help manage Python and its dependencies. It comes handy when we need to separate different environments(with different packages) for different tasks. Either Anaconda and Miniconda would work here.

#### Install Conda
Download the installation package and follow guides.
- **[Download Anaconda](https://www.anaconda.com/products/distribution#download-section)** (Full package)
- **[Download Miniconda](https://docs.conda.io/en/latest/miniconda.html)** (Lightweight version)

#### Check Installation
After installation, check installation in terminal:
```bash
conda --version
```
you should see an output like `conda xx.x.xx`.

### Step 2: Install Required Python Libraries
There are some required libraries to run the notebooks in this repo.

#### Check Installed libraries(if you have Python installed already)
Check current installed package list in terminal:
```bash
conda list
```
Look for the following packages:
- numpy
- pandas
- seaborn
- matplotlib
- ipywidgets

#### Install Required libraries
if you have a **fully new** python environment, use conda to install:
```bash
conda install -c conda-forge numpy seaborn pandas ipywidgets matplotlib
```
if you have **existing** environment, check installed libraries, then install the missing ones:
```bash
conda install -c conda-forge numpy
conda install -c conda-forge pandas
...
```

### Step 3: Install Jupyter Notebook
Jupyter Notebook is used to create **interactive notebook documents** that can contain live code, equations, visualizations, media and other computational outputs. 

#### Install
```sh
conda install -c conda-forge jupyter
```

#### Verify Installation
```sh
   jupyter --version
```

### Step 4: Install VS Code and Jupyter Notebook Plugin (Optional)
You don't have to install VS Code to run the notebook. Using original jupyter notebook is sufficient. However, using VS Code could be beneficial in a larger workflow and debugging.

#### VS Code
Visual Studio Code is a streamlined code editor with support for development operations like debugging, task running, and version control. It has a better and friendlier interface in code-editing, running, and debugging than the built-in text editor one would get from their system.

Download VS Code from: [VS Code Download](https://code.visualstudio.com/)

#### Install Jupyter Notebook Plugin
Jupyter Notebook cannot be run in VS Code solely. In order to edit and run a .ipynb file, you need a VS code Plug-In.

1. Open VS Code.
2. Click on the **Extensions** icon in the sidebar (or press `Ctrl+Shift+X`).
3. Search for `Jupyter` and install the **Jupyter** extension.
<div align="center">
  <img src="images/plugin.png" width="60%" />
</div>
4. Restart VS Code if needed.

## Notebook Running Guide
As stated before, jupyter notebook can be run both with the original jupyter notebook interface or VS Code.
### Running With Jupyter Notebook Interface

Open a terminal and start Jupyter Notebook:
```sh
   jupyter notebook
```
A browser tab will open with the Interface showing all the directories on your system. Locate the notebook and double-click to open.

Run a cell by pressing `Shift+Enter`, or click *run->run all cells* to run every cell in order.

### Running Wit In VS Code

Open an existing `.ipynb` file by double clicking the file (if the default method to open the file is set to VS Code), or right-click to open with VS Code.

Run a cell by pressing `Shift+Enter`, or click *run->run all cells* to run every cell in order.