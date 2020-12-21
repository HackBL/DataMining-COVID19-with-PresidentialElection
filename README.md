## Introduction
* Sentiment analysis on twitter related to COVID-19 based on presidential election in 2020
* Run Twitter API every day
* Collect all tweets relevant to both Donald Trump and Joe Biden
* Extract data relevant to Covid-19 from tweets above
* Analyze attitudes of Covid-19 


## Features
* Tweets collection
* Diagrams
* WordCloud Implementation


## Instructions
**Install**:
	pip install tweepy
	pip install twitter
	pip install nltk
	pip install pandas
	pip install matplotlib
	pip install emoji
	

	Note*: Before run the program, please install all the packages above in the terminal. However if some errors occur, please also check "pip install <Package name>" since all python programs could run successfully.



**Run & Execute**: Please use original Dataset.csv file to run Main.py

	1. python3 ExtractTweets.py  	--------- Extract tweets data into the CSV file at the current time.

	2. Python3 Main.py		--------- Generate a CSV file with tweets about COVID-19, and start sentiment analysis.


	Note*: The tweets data will be extracted into the CSV file. Since the program can only extract tweets by the current time, if you would like to extract more days data, you probably should run the program every day before starting running the analysis part. All commands should be running in the terminal in the correct directory. 
