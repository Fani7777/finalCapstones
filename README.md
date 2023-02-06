## UsArrests Data Analysis

### Project Description:

The goal of this project is to perform data analysis on the UsArrests dataset, which contains statistics on the arrests made by police departments across the United States.
The analysis focuses on exploring the relationships between different variables in the dataset, as well as performing dimensionality reduction using PCA.
Additionally, the project includes computing and visualizing correlations between the variables.

### Table of Contents:

Exploring the data
Statistics
Check for missing values
Visualizations
Correlation Analysis
Principal Component Analysis (PCA)
Standerdization of data
Clustering and dednograms
Observations

### Installations:

#### For installation the following softwares and packages are required

Python
Jupyter notebook

### Imports:

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
from scipy.cluster.hierarchy import dendrogram, linkage
from sklearn.cluster import AgglomerativeClustering
from sklearn.cluster import KMeans


### Usage
Once the project is installed, you can use it as follows:

Open the Us_Arrests.ipynb file in Jupyter notebook
Run the code by clicking on the "Run All" button.
The code will perform the following actions:

Load the UsArrests dataset and perform any necessary data cleaning and preprocessing.
Clean all of the data
Compute the correlations between the variables in the dataset and visualize the results.
Perform PCA on the dataset and visualize the results.
You can view the results of the analysis in the notebook.

### Screenshots

Correlation analysis screenshot
https://www.dropbox.com/s/w04y6phtsl918pa/Correlation.png?dl=0
![Screenshot (91)](https://user-images.githubusercontent.com/112699952/217005192-df6ec916-63e6-4af0-9e8c-aabc0d33fb43.png)

Code run screenshot
https://www.dropbox.com/s/j41u8p479p51met/Untitled.png?dl=0
![Screenshot (90)](https://user-images.githubusercontent.com/112699952/217005317-f9d9817f-f7a5-4a99-8f0c-ff2b243cf03e.png)


