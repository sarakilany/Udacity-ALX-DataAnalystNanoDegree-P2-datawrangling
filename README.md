# Udacity-ALX-DataAnalystNanoDegree-P2-datawrangling

## Dataset
The data gathering occurred using 3 sources:
1. Directly downloaded Twitter archive data from file twitter_archive_enhanced.csv
2. Tab separated file (image_predictions.tsv) is downloaded using the Requests library. The
file contains tweet image prediction
3. Json data gathered through Twitter API using the Tweepy library (tweet_json.txt)

After combining and cleaning, the data was saved into twitter_archive_master.csv. The final dataset has 1149 records with 25 features.


## Data Wrangling 
The project covers the steps of wrangling and analyzing data from WeRateDogs. WeRateDogs is an account on Twitter that allows users to rate dogs. We will
cover the following steps:
Step 1: Gathering data
Step 2: Assessing data
Step 3: Cleaning data
Step 4: Storing data
Step 5: Analyzing, and visualizing data

## Summary of Findings
1. There are two peak times at 12:00 AM and 16:00 PM or retweets with sum of retweet counts reaching 648884 and 473511 respectively. Additionally, we find that tweets are zero during the period 7:00 AM to 1:00 PM.
2. Golden Retriever has the largest number of tweets (counting the number of tweets for each breed) (66 tweets) followed by Perbroke (38 tweets), and Labrador Retriever (34 tweets) in 2016.
3. For the total number of retweet counts ( summing the retweet_counts of each breed),Golden Retriever breed has the largest number of total retweets counts (221653 tweets) followed by Perbroke (98058 tweets), and Chihuahua (93770 tweets) in 2016.
4. Monday has the largest number of total retweets (sum of retweet_count) (250439) followed by Friday(240056), and Wednesday(211173) in 2016.
5. In 2016, January had the highest number of tweets 98, while in May the number of tweets were the lowest with only 30.







