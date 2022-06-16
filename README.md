# MasterThesis
Programming project related to a master thesis from spring 2022. The objective of the project was to develop and test multiple machine learning method for the task of classifying gas leakages from input in the form of audio signals. Three methods have been tested out, including *Clustering, Neural Networks* and *Gradient Boosting*.


## Getting Started

Start by downloading the files in this repository and save them in a folder in an optional location on your computer. 
To run the files in this project the following frameworks and programs needs to be installed on the computer:

* Python version 3.8.5 (or higher)
* Jupyter Notebook or an IDE that can open .ipynb-files
* Anaconda version 4.10.3 or pip version 21.0.1 (or higher)

### Prerequisites

The code requires several libraries to be installed, including:
* numpy
* scipy
* pandas
* os
* csv
* time
* librosa
* matplotlib
* autogluon
* seaborn
* sklearn
* IPython
* pydub
* wave
* sklearn
* mpl_toolkits

For all libraries above, the following code can be used to install them to the project: 

```
$ conda install <library_name>
```

Unless you need the libraries in other projects too, it could be beneficial to create a virtual environment and install the libraries there. 
To create a new virtual environment follow the tutorial in this link: [Link](https://www.geeksforgeeks.org/set-up-virtual-environment-for-python-using-anaconda/)
Each time you want to open the project in for instance Jupyter Notebook, you open the Anaconda prompt and type:

```
$ conda activate <environmentname>
```
The <environmentname> is the name you chose during the prior creation (following the tutorial).
Then you can type the following and open your Notebook which will pop up in a internet window. 
  
```
$ jupyter notebook
```
Then you can scroll down until you find the project-folder that you downloaded.
### Running the project

In order for all code-files to work, they need to be run in the following order.

1. Creating_CSV.ipynb (You can skip running this file as its whole purpose is to create *tube_files.csv* and *vent_files.csv* which is already created for you).
2. Adding_Features.ipynb (You can also skip this as the files *new_features_tube.csv* and *new_features_tube.csv* has already been created for you)
  
The two coding-files above are unnecessary to reproduce as they take much run-time and their output is .csv-files that is already included in the folder named *CSV-files*.
  
