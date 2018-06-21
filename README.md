# Creating--Customer-Segments
Unsupervised Learning Project: Creating Customer Segments
Project Description

This is the 4th project for the Machine Learning Engineer Nanodegree. In this project I apply unsupervised learning techniques on product spending data collected for customers of a wholesale distributor to identify customer segments hidden in the data.

Here, I first explore the data to determine if any product categories highly correlate with one another by observing a small subset of the data and also by ploting a scater matrix. Afterwards, I preprocess the data by scaling each product category and then identifying (and removing) unwanted outliers. Then I apply PCA transformations to the data and implement a clustering algorithm (Gaussian Mixture Model)to segment the transformed customer data. Finally, I compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.
Install

This project requires Python 2.7 and the following Python libraries installed:

    NumPy
    Pandas
    matplotlib
    scikit-learn

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.
Code

The main code for this project is located in the customer_segments.ipynb notebook file. Additional supporting code for visualizing the necessary graphs can be found in visuals.py. Additionally, the Report.html file contains a snapshot of the main code in the jupyter notebook with all code cells executed
