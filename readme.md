# @dog_rates  – Twitter Handle Tweets Data Analysis 
This is the analysis of the WeRateDogs twitter page where dogs are introduced and rated. We are going to analyze the general feeling towards dogs, know how this feeling is demonstrated and also have an insight on how the twitter handle is doing over time

 ## Data Wrangling
The data wrangling process has been broken down into three main steps:  
1. Gather 
2. Assess 
3. Clean 
 
### 1. Gather
There are 3 main data sources for this project; 

**I. Excel data in csv format**. 

This is downloadable directly from the project resources and saved locally as a csv file named twitter-archive-enhanced.csv. I have used this file to get all the tweet ids used in the twitter API explained in data source III explained below. 

**II. TSV file format**.

A file url is provided and downloaded using python requests library. I have saved the file locally as image-predictions.tsv. This contains the image predictions from a neural network. 

**III. Twitter API**.

Using the twitter API I have queried all tweets data by tweet id (from step I) in a JSON format and saved into a txt file named tweet_json.txt. The next step is reading this JSON format by looping over the text lines to create a csv file namely twitter_archive_master.csv  
A copy is made for the datasets for use in the next step. 
### 2. Assess 
Assessing in this case includes visually and programmatically looking for both messy and dirty data issues in the 3 datasets gathered. Issues I was looking for include but not limited to data duplication, missing data, wrong data formats and data tidiness The assessment comments have been categorized to Quality issues and Tidiness issues as in the table below. 
 
### 3. Clean
The data cleaning process is broken down into 3 simple steps: 
I. Define – Cleaning steps definition
II. Code – Code to perform the cleaning tasks 
III. Test  - Run the code with no error and achieve clean data as defined

***See ```wrangle_act.pdf``` for step by step data wrangling***

## Exploratory Analysis
The exploratory seeks to answer the following questions,
1.  What is the general feeling towards dogs? 
2.   How is the tweeting trend over time on @dog_rates handle? 
3.   Which is the most and least rated dog breed?  
4.   What are the most mentioned words? 

***See ```act_report.pdf``` for this analysis***
