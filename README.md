# ADACS - Introduction to computing and data science for astronomers

Held at Curtin University, 13 to 15 November 2017: https://adacs.org.au/index.php/2017/10/10/introduction-to-computing-and-data-science-for-astronomers/


Throughout the workshop we will be using an etherpad (a collaborative online document) to post challenges and
information throughout the workshop. The document also contains a chat where you can ask us 
questions or chat with each other:
https://public.etherpad-mozilla.org/p/adacs-13-11-2017

## Day 1

1. Opening remarks/keynote
    1. Astronomer's toolkit
2. Version Control with git and github
    1. global config
    2. Create and commit to a repository
    3. explore history
    4. check out older versions
    5. collaboration/ pull requests
    6. branching
3. Good coding practices (in Python)
    1. Jupyter Notebooks
    2. Intro to Python
        1. code layout
        2. commenting
        3. packages
        4. Python syntax and data types
    3. Visualisation - The good and the bad

## Day 2

1. Working with pandas DataFrames in python
    1. Loading and exploring data
    2. Diagnostic plots
    3. Cleaning data
    4. Merging data (if time is available, otherwise this can be done in own time)
2. Astronomy examples with AstroPy
    1. Overview 
    2. Working with FITS files and WCS
    3. Using Coorindates
    4. Radio astronomy related tutorial(?) 
3. Virtual Observatories
    1. Inroduction
    2. Data Acquisition (using Topcat, CDS tools and Python)

## Day 3

1. Introduction to ML
    1. Data preparation and exploratory data analysis (review from previous day)
    2. Classification
        1. Model evaluation
        2. Model tuning
        3. reporting
    3. Regression
    4. Clustering
    5. Dimensionality reduction
2. Introduction to Nimbus
3. Q&A session followed by sundowner at the Innovation Central Perth (B216:204)



**Note**:
Tutorials build on each other and assume basic knowledge from previous days is carried forward (e.g., you know the basic data structures and operations and how to write a script/ run jupyter notebooks). 
Where possible training material will be uploaded as an ipython notebook and checked for python 2.7 and 3.X compatability.

## Downloading only the folder of the training you attended

If you want to download a specific folder (e.g. Day 1) instead of cloning the entire repository you can use svn to checkout a subdirectory of this repository by running the following command in your shell:

`svn checkout https://github.com/r-lange/ADACS-obs-workshop/trunk/Day1`

**Note**: you simply need to change the url of the folder by replacing `tree/master` with `trunk`


