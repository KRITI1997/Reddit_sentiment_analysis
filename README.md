# Reddit_sentiment_analysis

# Description:
This project utilizes the Reddit API to scrape data from selected subreddits related to health conditions and clinical trials. It then performs sentiment analysis on the scraped text data and generates personalized messages based on user interests in clinical trials.

# Features:

 # Reddit Data Scraping:

Utilizes the Reddit API to fetch posts and comments from specified health-related subreddits, focusing on clinical trials.
Sentiment Analysis:

Analyzes the sentiment of the scraped text data using OpenAI's language model.
Provides insights into the overall sentiment (positive, negative, neutral) of the discussions related to health conditions and clinical trials.
Personalized Message Generation:

Generates personalized messages tailored to users interested in clinical trials.
Employs OpenAI's language model to create messages based on the content extracted from Reddit posts related to clinical trials.
Workflow:

# Authentication with Reddit API:

Authenticate with Reddit API using PRAW (Python Reddit API Wrapper).
# Data Scraping:

Fetch posts and comments from specified subreddits related to health conditions and clinical trials.
# Sentiment Analysis:

Concatenate post titles, bodies, and comments for each Reddit post.
Perform sentiment analysis on the aggregated text data.
# Personalized Message Generation:

Extract user interests from Reddit posts containing mentions of clinical trials.
Generate personalized messages based on these interests.
# Output:

Display sentiment analysis results indicating the overall sentiment of the discussions.
Present personalized messages tailored to users interested in clinical trials.
# Dependencies:

Python 3.x
PRAW (Python Reddit API Wrapper)
OpenAI API (for sentiment analysis and message generation)
How to Use:

Install Python 3.x and required libraries (PRAW, OpenAI API).
Obtain API credentials for Reddit and OpenAI.
Replace the placeholder credentials in the code with your own.
Run the main() function.
View sentiment analysis results and personalized messages generated by the program.




The main file contains the code where authentication of Reddit through user credentials are done after which comments from subreddits related to 'clinicaltrials' are scrapped through PRAW and then these comments are given to an openai model for sentiment analysis and personalised message generation.


For scrapping the reddit comments, you need a reddit account where you need to create a developer app for this project at https://www.reddit.com/prefs/apps and once the developer credentials are generated we have a client id and client secret which we use in the code to authenticate the reddit account![image](https://github.com/KRITI1997/Reddit_sentiment_analysis/assets/46029875/497d9e64-2f41-41ad-b071-7866c0190576)

For accessing openAI API we need a secret key which we get from our openAI account.
Install the requirements for the code through pip install.
Enter the required credentials in the code and run it.

# Challenges Faced:

I was not able to make the OpenAI API requests as I was running into the 'Quota limit exceeded' error even though my requests and usage was zero.

# Acknowledgments:

Special thanks to the developers of PRAW and OpenAI for their excellent tools and APIs.
This README provides an overview of the project, its features, workflow, dependencies, and instructions for usage. It serves as a guide for developers and users interested in utilizing the Reddit Health Sentiment Analyzer.

