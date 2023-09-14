# MOMA - A project in Python

## Overview
This project was designed by Tate to answer a set of questions of the Museum of Modern Art dataset:
1. Which artist in this data set lived the longest?
2. Who are the top 10 artists by the number of artworks?
3. Which artist is created the most artwork by total surface area?
4. Did any artists have artwork acquired during their lifetime?
5. Please review the quality of the data, and present any issues
   
The project uses Python to:
* Read data from the database
* Clean the data, for example: renaming columns, correcting datatypes, altering structure of dataset due to ids in list form
* Answer the above questions through analysis for example: creating calculated columns, joining the datasets, applying conditional logic
* Evaluating the quality of the dataset

## Dataset
The dataset was provided through Tate and stored in a github repo [here](https://github.com/tatedata/data-analyst-interview) as an obsolete interview task from 2018. The database contains two tables: artist and artworks for 130,000 pieces of art in the MOMA collection. 

## Installation
Install all project requirements by running:
```pip install requirements.txt```

## Acknowledgement
* Tate for providing task [resources](https://github.com/tatedata/data-analyst-interview)
* MOMA for providing original source of data on [kaggle](https://www.kaggle.com/datasets/momanyc/museum-collection) 
