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

1. Creating_CSV.ipynb (Creates *tube_files.csv* and *vent_files.csv*)
2. Adding_Features.ipynb (Creates *new_features_tube.csv* and *new_features_tube.csv*)
  
The two coding-files above are unnecessary to reproduce as they take much run-time and their output is .csv-files that is already included in the folder named *CSV-files*. You can therefor skip running these and jump right to the next code-files.
  
3. KMeans.ipynb
4. AutoML.ipynb
  
The two coding-files above requires action by the user in order to run the machine learning models several times on different input-datasets. For the KMeans.csv-file the user needs to define which three audio features the method shall use as input each time. The section of the code that needs editing/action by the user is marked with blue comments.
  
The three other files does not produce results for the thesis but has been used to analyze and plot audio features, and display sound waves. 
  
5. Feature_Extraction.ipynb
6. Feature_MFCC.ipynb
7. Filters.ipynb
  
## Contact
  
Marianne Pettersen
LinkedIn: [Link](https://www.linkedin.com/in/mpett/)
Email: [Link] mariannepettersen123@gmail.com
