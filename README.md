[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/UNT-PHYS-3510-template/Clustering.git)

# K-Means Clustering
This assignment is based on two data files, one referring to a generic set of two variables (clusters.csv), and one generated in your instructor's research lab (protein_environ.csv). The latter contains more than 700 rows of data related to the atoms of a small protein (an insulin mutant, entry 1A7F in the Protein Data Bank). For each atom the file report some properties that are related to how close to the surface of the protein the atom is, as well as the distance from the center of mass of the protein.

Assignment 1: Use the kmeans.ipynb notebook to 
* Perform clustering of the clusters.csv dataset with a variable number of clusters.
* Compute and plot the inertia of the clusters as a function of the number of clusters.
* Compute and plot the silouette of the clusters as a function of the number of clusters. 

Assignment 2: Use the clustering_protein.ipynb notebook to
* Select a subset of features from the dataset and standardize them
* Use k-means to perform a clustering analysis on the atoms. Vary the number of clusters and identify the best model using the strategies and metrics described in the first assignment (if you are unsure between two models, pick the simplest) 
* Plot the positions of the atoms of different clusters in the X-Y plane (for visualization purposes only plot the atoms with Z close to zero)
