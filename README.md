# Weed

This is a repository for a data analytics workshop in python to be conducted in August.
We will be using the price of weed in the US as the dataset to showcase the approach.

The broad analytics steps are listed below. We would showcase **some of them** in this workshop.

1. **Introduction** - “I think, therefore I am”
  - What is data analysis?
  - What type of questions can be answered?
  - Developing a hypothesis drive approach.
  - Making the case.

2. **Acquire** - "Data is the new oil"
  - Download from an internal system
  - Obtained from client, or other 3rd party
  - Extracted from a web-based API
  - Scraped from a website
  - Extracted from a PDF file
  - Gathered manually and recorded

3. **Refine** - "Data is messy"
  - Missing e.g. Check for missing or incomplete data
  - Quality e.g. Check for duplicates, accuracy, unusual data
  - Parse e.g. extract year from date
  - Merge e.g. first and surname for full name
  - Convert e.g. free text to coded value
  - Derive e.g. gender from title
  - Calculate e.g. percentages, proportion
  - Remove e.g. remove redundant data
  - Aggregate e.g. rollup by year, cluster by area
  - Filter e.g. exclude based on location
  - Sample e.g. extract a representative data
  - Summary e.g. show summary stats like mean

4. **Explore** - "I don't know, what I don't know"
  - Why do visual exploration?
  - Understand Data Structure & Types
  - Explore one variable graphs - (Quantitative, Categorical)
  - Explore two variable graphs - (Q & Q, Q & C, C & C)
  - Explore multi variable graphs

5. **Model** - "All models are wrong, Some of them are useful"
  - The power and limits of models
  - Tradeoff between Prediction Accuracy and Model Interpretability
  - Assessing Model Accuracy
  - Regression models (Simple, Multiple)
  - Classification model

6. **Insight** - “The goal is to turn data into insight”
  - Why do we need to communicate insight?
  - Types of communication - Exploration vs. Explanation
  - Explanation: Telling a story with data
  - Exploration: Building an interface for people to find stories
  
## Prerequisites
* Basics of Python. User should know how to write functions; read in a text file(csv, txt, fwf) and parse them; conditional and looping constructs; using standard libraries like os, sys; lists, list comprehension, dictionaries
* It is good to know basics of the following:
    * Numpy
    * Scipy
    * Pandas
    * Matplotlib
    * Seaborn
    * bokeh
    * vincent
    * folium
    * sklearn
    * IPython and IPython notebook - Everything here would be an IPython notebook
* Software Requirements
    * Python 2.7
    * git - so that this repo can be cloned :)  
    * virtualenv
    * Libraries from *requirements.txt*

## Optional
Users could choose to install Anaconda, if they want. If using Anaconda or Enthought, please ensure that all libraries listed in the requirements.txt are installed.

## Setup Guide

####Clone the repository
    $ git clone https://github.com/amitkaps/weed.git

####Create a virtual environment & activate
    $ cd weed
    $ virtualenv env
    $ source env/bin/activate

####Install reqirements from requirements file
    $ pip install -r requirements.txt

####Note: Make sure you have libraries for png & freetype.
Ubuntu users can install the below

    apt-get install libfreetype6-dev
    apt-get install libpng-dev

### Mac users
    brew install freetype
    brew install libpng
