# Exploratory Data Analysis: Seattle AirBnB Data

### Installation:

This analysis was conducted in a Python 3.6.8 environment, making use of standard libraries in the scientific Python stack (numpy, pandas, matplotlib, sklearn). 

The data used in the project is publicly available on Kaggle: https://www.kaggle.com/airbnb/seattle

### Motivation:
This project is an exploratory data analysis to gain some initial insights into the Airbnb guests and bookings. It makes use of Airbnb data for Seattle exclusively.

The project focuses on the nature and drivers of reviews for Airbnb visits, asks three questions:
- How can we group and categorize review text descriptions in the data set based on sentiment?
- Which neighbourhoods tend to generate disproportionately positive sentiment in reviews?
- Which features are most predictive of positive review scores?

### Structure

This exploration follows the CRISP-DM approach. 

This is done at two levels. First, through the high-level numbered sections of the notebook. These begin by understanding the problems we're trying to solve, understanding our data, and conducting some high-level data preparation.

Secondly, within each of our research questions we follow the data preparation, modelling, and evaluation steps. 

Note that deployment is not considered in this exercise, since it is purely a descriptive exploratory analysis. Note also that business understanding and data understanding are not covered within each of the research questions, since they're covered in a macro fashion at the start of the notebook.

### Summary
We found that there are ways to categorise text descriptions in the reviews, and that the majority of such responses indicate positive sentiment. There was variation by locality, although the differences were relatively small. 

A number of variables seemed predictive of positive review scores on a property, and included: Whether a host is a superhost; Whether a host responds quickly; and the amenities available at a property (e.g. TV, parking).

### Files:
The project contains a Jupyter notebook where the technical work has been conducted. 

The data files reflect those publicly available on Kaggle. 

### Licensing, Authors, Acknowledgements, etc.
The project has been completed by me directly. The raw data is openly available and in the public domain.
