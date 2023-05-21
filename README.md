This is the 4th great revolution. The AI craze is increasing day-by-day, and I am passionate about innovation and AI. However, not everyone shares the same sentiment. To understand how people feel sentimentally about AI, I decided to perform Sentiment Analysis on their tweets. The biggest challenge was obtaining up-to-date tweet data for analysis. After failing to find an updated dataset, I took matters into my own hands and built my own dataset from scratch.

I used snscrape, a powerful data scraping tool, to collect the tweets. Initially, I attempted to use the Twitter API, but it imposed limitations on the number of tweets I could scrape per month. With snscrape, I was able to gather data from approximately 22,965 tweets. However, the data required extensive preprocessing and exploratory data analysis to make it usable.

I stored the scraped data in an 'output.json' file and utilized the Pandas library to perform data preprocessing. This involved setting the data into proper column names, handling null values, and fixing data types. Once the data was processed, I proceeded with exploratory data analysis.

In the analysis phase, I filtered the dataset to include only tweets with the hashtag 'ArtificialIntelligence'. This reduced the dataset from 22,965 to 6,248 columns. I then eliminated unnecessary columns to focus on the relevant information. Additionally, I addressed null values and refined the data further.

Next, I delved into identifying the languages of the tweets. From the dataset, I found that there were 5,536 tweets in English, 220 tweets with language code 'qme', and 485 tweets in other languages. The languages other than 'en' and 'qme' included: ['in' 'es' 'de' 'it' 'zh' 'ko' 'fr' 'ja' 'und' 'pt' 'da' 'qht' 'ht' 'hi' 'el' 'ro' 'ar' 'lt' 'bn' 'ca' 'ml'].

To streamline the analysis, I decided to focus on the English tweets. I filtered the dataset to retain only the tweets in English. This narrowed down the dataset to 5,536 columns. Subsequently, I exported the cleaned data to a CSV file for further analysis.

With the dataset ready, I proceeded with implementing Sentiment Analysis. For this task, I utilized the NLTK library and the vader_lexicon sentiment analysis tool. I calculated and obtained sentiment scores and compound scores for the tweets.

Afterwards, I counted the sentiments among the 5,536 columns and found that:

Number of people feeling optimistic: 2,632
Number of people feeling negative: 621
Number of people feeling neutral: 2,283

To provide a visual representation of the sentiments, I created a pie chart. From the analysis, I discovered that out of 5,536 users, 47.5% felt positive about artificial intelligence, 11.2% felt negative, and 41.2% expressed a neutral sentiment.

Additionally, I used bar charts and word clouds for further data visualization, which helped to present the data in a more engaging and understandable manner.

Overall, this analysis has provided valuable insights into the sentiment surrounding artificial intelligence. It highlights the diversity of opinions and allows us to understand how people perceive and react to AI. By leveraging advanced tools and conducting thorough analysis, we can gain valuable insights into public sentiment and make informed decisions.

#AI #ArtificialIntelligence #SentimentAnalysis #DataAnalysis #DataVisualization #NLTK #snscrape"
