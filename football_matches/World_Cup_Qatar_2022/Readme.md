# Project Overview

In this project, we'll predict the winner of the FIFA World Cup Quatar 2022. I'll follow Frank Andrade's and Dataquest's code. I'll use what I like the best from both.

**Project Steps**

* Scrape match info using requests, BeautifulSoup, and pandas.  
* Clean the data and get it ready for machine learning using pandas.
* Make predictions about who will win a match using scikit-learn.
* Measure error and improve our predictions.

## Code

You can find the original code for this project (Dataquest's part)[here](https://github.com/dataquestio/project-walkthroughs/tree/master/football_matches).
You can find the original code from Frank Andrade's part [here](https://github.com/ifrankandrade/fifa-world-cup-2022-prediction).

File overview:

* `scraping.ipynb` - a Jupyter notebook that scrapes our data.
* `predictions.ipynb` - a Jupyter notebook that makes predictions.

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * requests
    * BeautifulSoup
    * scikit-learn
    * bs4
    * lxml
    
## Data

We'll be scraping [Wikipedia](https://en.wikipedia.org/wiki/2018_FIFA_World_Cup) (2018 World cup example) to get our data in the first part of this project (`scraping.ipynb`).
