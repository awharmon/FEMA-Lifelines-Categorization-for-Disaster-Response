# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 4: FEMA Lifelines Categorization for Disaster Response

## Project Introduction

The  focus of this project was to provide real-world Data Science solutions to a client in the emergency and disaster relief space, NLT Technologies. We applied routine Data Science techniques and procedures to build an inferential framework on our case-study/proof-of-concept. While there were several topics to choose from, our team decided to build an inferential tool that utilized Yelp data to estimate the number of businesses in a given locality and categorize them by lifeline. 

---

## Problem Statement

Prior to and during a disaster, it is important to understand the projected and actual effects of the event on the community, including its economic effects on critical services. To help predict this impact, our clients need a tool to determine the general regionality of critical services estimate the potential effects of an event on each of FEMA’s seven lifelines. 

---

## Table of Contents
The project repository is organized as follows:

 - Datasets
 - Notebooks
     - 01_targeted_web_scraping.ipynb 
     - 02_data_cleaning.ipynb
     - 03_economic_data.ipynb
     - 04_EDA.ipynb
     - 05_yelp_mapping.ipynb
     - twitter-scrapes (unused)
 - Final_Presentation.pdf
 - Executive_Summary.md

---

## Data

Our project required a large amount of data scraping, cleaning, and manipulation. Such cleaning processes included, but are not limited to, concatenating and merging dataframes, creating dummy series, filling and dropping null values, and mapping new values or different data-types across axes. All of the business listing data was sourced through Yelp's Fusion API. Our economic datasets were sourced on the Kaggle, Zillow, and the Splitwise blog. The GIS shapefiles were sourced through the Houston government's open-data site and Harris County Appraisal District's website. A complete list of our source-links can be found below.

 - https://www.yelp.com/developers/documentation/v3/business
 - https://blog.splitwise.com/2013/09/18/the-2010-us-census-population-by-zip-code-totally-free/
 - https://www.kaggle.com/goldenoakresearch/us-household-income-stats-geo-locations
 - https://www.zillow.com/research/data/
 - http://data.houstontx.gov/dataset
 - http://pdata.hcad.org/GIS/

---

## Installation, Required Tools, & Python Libraries

- Jupyter Notebooks
- NumPy
- Pandas
- MatPlotLib
- Seaborn
- Descartes
- Geopandas
- Shapely
- Requests
- Json
- Time
- Itertools

---

## Authors and Acknowledgements
Alex Harmon, Sydney Herndon, Joe Darby, Zoe Nawar