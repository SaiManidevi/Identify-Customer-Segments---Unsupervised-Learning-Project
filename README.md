# Identify-Customer-Segments - Unsupervised-Learning-Project
## Table of contents
* [Project Introduction](#project-Introduction)
* [Language & Libraries used](#programming-Language-and-Libraries-used)
* [Project Details](#project-details)

## Project Introduction
In this project, Udacity's Bertelsmann partners - **AZ Direct** and **Arvato Financial Solutions** have provided two datasets one with demographic information about the people 
of Germany, and one with that same information for customers of a mail-order sales company. 

The goal of this project was to look at relationships between demographics features, organize the population into clusters, 
and see how prevalent customers are in each of the segments obtained.

## Programming Language and Libraries used: 
This project uses **Python 3** and is designed to be completed through the Jupyter Notebooks IDE.

The following libraries were used in this project:
* NumPy
* pandas
* Sklearn / scikit-learn
* Matplotlib (for data visualization)
* Seaborn (for data visualization)

## Project Details:
**Unsupervised Learning** techniques are applied on the demographic and spending data for a sample of German households.
Steps performed in this project include:

* **Data Preprocessing** - Handling data with missing values, performing one-hot encoding, re-engineering categorical, binary and ordinal types of data.
* **Feature Transformation** - Dimensionality reduction techniques to identify relationships between variables in the dataset, 
resulting in the creation of a new set of variables that account for those correlations. 
Used **sklearn library** to create objects that implement feature scaling and PCA - dimensionality reduction decisions.
* **Clustering** - Applied clustering techniques (KMeans Clustering) to identify groups in the general demographic data. This was done using sklearn's **kmeans** library.

Finally, compared the distribution of people by clusters for the customer data to that of the general population. 
This resulted in an conclusion (prediction) about which types of people are likely consumers for the mail-order sales company. 
