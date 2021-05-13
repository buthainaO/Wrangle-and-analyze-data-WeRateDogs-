# Introduction 
This project mainly focuses on the wrangling part of the data analysis. 

# Prerequisites
- Python 
- Numpy 
- Pandas
- Google sheets 
- Json
- Tweepy
- Matplotlib 

# Dataset 
The dataset has been gathered from three different resources with three different formats. 
- The WeRateDogs Twitter archive. This file has been downloaded manually.
- The tweet image prediction. It’s a flat file that has been downloaded programmatically using the Requests library.
- Additional file that contains additional data for the WeRateDogs Twitter archive. Has been downloaded using Tweepy library and Twitter API. For this file we have extracted only the needed columns which are: 'id','favorite_count' and 'retweet_count'.

# Summary 
# - Assessing:
## - Quality issues :
- None instead of NaN
- Wrong name entry
- Retweet and replies doesnt have real ratings
- Wrong column type for tweet_id
- Some predicted names starts with small letter and others with capital letter
- Underscore instead of space
- Wrong rating denominator
- Missing data
- Unused columns
- Timestamp column has two different variables

## - Tidiness issues :
- The columns (doggo, floofer,pupper,puppo) related to the same variable
- The two tables (image_predictions.tsv, tweet-json.txt) related to the same observational units in ‘twitter-archive-enhanced.csv’ table

We have worked through the rest of the project to clean the issues and to analyze the clean dataset. 
