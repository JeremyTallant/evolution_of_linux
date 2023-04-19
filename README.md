# Exploring the Evolution of Linux
## Description
Version control repositories like CVS, Subversion or Git store rich evolution information about a software project. In this project, we'll be challenged to read in, clean up and visualize a real world Git repository dataset of the Linux kernel. With almost 700k commits and thousands of contributors (find out the exact number in this project ;-) ) there are some little data cleaning and wrangling challenges that we'll encounter. But you'll also gain insights about the development activities over the last 13 years.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. Introduction
2. Reading in the dataset
3. Getting an overview
4. Finding the TOP 10 contributors
5. Wrangling the data
6. Treating wrong timestamps
7. Grouping commits per year
8. Visualizing the history of Linux
9. Conclusion