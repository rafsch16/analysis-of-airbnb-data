# Analysis of Airbnb Data

### Table of Contents 
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Instructions](#instructions)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation<a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

This project is part of the Udacity course in Data Science. The aim of the project is to freely analyse and discuss Airbnb data from Seattle and Boston by asking 3-5 business questions.

I intended to answer the following questions:
1. Which features of Airbnb properties are the best indicators for lodging price?
2. Does the presence of dogs and cats influence price? 
3. How well can we predict price?

A general discussion of the results can be found in this blog post.

## File Descriptions<a name="files"></a>

The file **'../data/seattle/listings.csv'** contains Airbnb data for Seattle.

The file **'../data/boston/listings.csv'** contains Airbnb data for Boston.

The jupyter notebook file **'../airbnb.ipynb'** contains all of the code for this project.
- Loads the datasets for Boston and Seattle
- Merges the two datasets
- Cleans the data (by creating dummy variables for the categories)
- Splits the data into training and test sets
- Initiates a ridge regresion model
- Trains and tunes the model using 'price' as the response variable
- Analyzes and visualizes aspects of the data related to the business questions

## Instructions<a name="instructions"></a>

Run the cells in the jupyter notebook file.

See the blog post for a general discussion of the results.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
The disaster dataset to train the model was provided by **Figure Eight**. The code for the web app was mostly provided by **Udacity**, only the data visualization part was modified. The rest of the code was written according to guidelines from Udacity.
