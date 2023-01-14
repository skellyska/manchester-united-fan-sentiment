# manchester-united-fan-sentiment
'''This script uses the YouTube Data API to search for videos about Manchester United, and retrieve the comments of those videos. 
It then uses the TextBlob library to analyze the sentiment of each comment. 
The script stores the comments and their sentiment in a list, converts it to a DataFrame and prints the overall sentiment of the comments and the count of comments for each sentiment. 
Additionally, it saves the comments data to a csv file.

This script only retrieves the comments of the first 50 videos that matched the search criteria and the first 100 comments for each video. 
If you want to retrieve more data, increase the maxResults parameter.

It's important to note that the sentiment analysis is based on the TextBlob library which is a simple library for performing basic natural language processing tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, etc. It may not be as accurate as more advanced libraries or models. '''
