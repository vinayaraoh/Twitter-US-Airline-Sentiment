<img width="690" alt="image" src="https://github.com/user-attachments/assets/e59b2c1a-c425-471c-99b4-fb4bc552fd23" />

# Twitter-US-Airline-Sentiment

As digital connectivity continues to grow, empowering consumers to openly share their views on brands, companies are leveraging sentiment analysis on social media content to extract insights and inform their branding strategies. In this project, I perform sentiment analysis on travellers' expressing their feelings on Airlines on Twitter. 

I start with some EDA on the dataset. Majority of tweets are negative and customer service tops the list of complaint reasons! Next, to use sentiment analysis to categorize the sentiment as positive, negative, or neutral I first use the VADER bag-of-words approach. Next, I connect to the OpenAI API to get ChatGPT to respond with the sentiment category for each tweet. I compare the results of both approaches to the manual tagging of sentiment in the dataset. The VADER bag-of-words does well for positive tweets but does poorly while categorizing negative/neutral tweets. ChatGPT performs better out of the two approaches. Further, it performs well when the tweet sentiment is clearly positive or negative. On the downside, it tries to forcefit more neutral tweets as either positive or negative.
