# Reddit_sentiment_analysis

The main file contains the code where authentication of Reddit through user credentials are done after which comments from subreddits related to 'clinicaltrials' are scrapped through PRAW and then these comments are given to an openai model for sentiment analysis and personalised message generation.


For scrapping the reddit comments, you need a reddit account where you need to create a developer app for this project at https://www.reddit.com/prefs/apps and once the developer credentials are generated we have a client id and client secret which we use in the code to authenticate the reddit account![image](https://github.com/KRITI1997/Reddit_sentiment_analysis/assets/46029875/497d9e64-2f41-41ad-b071-7866c0190576)

For accessing openAI API we need a secret key which we get from our openAI account.
Install the requirements for the code through pip install.
Enter the required credentials in the code and run it.


