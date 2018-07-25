# Natural Language Processing with Reddit Post Data

## Executive Summary:  
This project aims to take an initial look at user interaction on Reddit. Our goals included scraping data from Reddit's API, developing a binary classification, and building predictive models that facilitate our undertanding of important attributes.

Overall, the best models were able to perform quite well. However, the majority of loss was occuring in False Negatives, meaning the models did quite well to predict low interaction, but had most loss occur when trying to predict high interaction. Further goals of this project include incorporating markdown table print statements into the code, and model refinement via optimization on Recall.

## Data Source:
- [Reddit's API](http://www.reddit.com/hot.json)


## Table of Contents
1. [nlp_env.yml](https://github.com/sonyah-hawaii/natural_language_processing/blob/master/nlp_env.yml)  
_A simple script that you can use as a shortcut to install the necessary packages in a new virtual environment with Anaconda to run this project through._
2. [Data Scraping and Extracting](https://github.com/sonyah-hawaii/natural_language_processing/blob/master/scraping_extracting.ipynb)       
_Includes the process of building a for loop that scrapes thousands of posts, extracts information, and saves the information to a dataframe._
3. [Cleaning, EDA, and Modeling](https://github.com/sonyah-hawaii/natural_language_processing/blob/master/cleaning_modeling.ipynb)
_The dataset and target variable are explored through distribution visualizations and printout, and the binary split for classification output is determined using K-Means clustering. The scraped information is processed using `Count Vectorizer`, passed through a Logistic Regression model. The model is tuned through resampling, and adjustments to hyperparameters for`Count Vectorizer` and `Logistic Regression`._
4. [Modeling 2: Random Forest Regressor](https://github.com/sonyah-hawaii/natural_language_processing/blob/master/Random%20Forest%20Model.ipynb)  
_The same process as the previous notebook, repeated with the Random Forest Regressor from `Scikit-Learn`._


These notebooks includes the following packages and languages:
- `Numpy` and `Pandas`
- `Scikitlearn`
- `requests`, `JSON-C`, and `time`
- `Seaborn` and `Matplotlib`  
- Python, LaTex, and Markdown