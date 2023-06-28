# iPhone_Trends_on_Sentiments_and_Sales

## Abstract

Apple events are one of the most awaited and talked about events of the year. '#Apple',
'#iPhone', and a few others keep trending at and around the time of apple events. The recent release
of the iPhone 14 and its models have sparked the interest of the general public and critics on social
media. The text analysis of the iPhone 14 and its models will be rather interesting. We wanted to
analyze the Apple company's brand power based on people's opinions and the sales of iPhones.
The tweets are extracted from Twitter for iPhone 14 and iPhone 13 models before and after the
iPhones' were launched at an Apple event. Sentiment analysis and topic modeling are performed
on the extracted tweets to analyze public opinions and the sales data is collected and analyzed. A
comparison is drawn between these two trends to understand the power that the Apple brand has.

## Dataset

The data for this project is collected from Twitter. Twitter is a huge social media
platform where people around the world express their opinions. To understand sentiments
about Apple and iPhones, Twitter is the perfect platform. Tweets about iPhone 13 and 14
models can be extracted using Python's snscrape package. Snscrape is a package that
scrapes data from Social Networking Services. We require four parameters to scrape data
from Twitter. They are the number of tweets, the search term used to extract them, the date
from which they will be extracted, and the date up to which they will be extracted. The
extracted tweets will be in .json format. The Pandas package is used to convert it to a .csv
file.
The tweets are extracted from Twitter in four parts. The search term 'iPhone 13' is
used to extract the first dataset, and these tweets are dated before the release of the iPhone
13. The search term for the second dataset is 'iPhone 13', and the tweets are dated after the
iPhone's release. The third dataset is extracted using the search term "iPhone 14," and the
tweets in this dataset date prior to the release of the iPhone 14. The search term 'iPhone 14'
is used for the fourth dataset, and the tweets are dated after the iPhone's release. Snscrape
is used to extract 20K tweets from Twitter, with 5000 tweets per dataset.

## Analysis

EDA, VADER Sentiment Analysis, BERT - Transformers, Topic Modeling, Sales Data

## Results

In the project, two models of sentiment analysis were performed to analyze the sentiments
as accurately as possible. The BERT sentiment analysis gave better outputs than the VADER
sentiment analysis where some outputs were skewed. From the analysis of both the iPhone models
- 13 and 14, we can conclude that both models received hate before and after their releases. Despite
public opinions and criticisms, the sales of the iPhones have been increasing year after year. We
can conclude that brand images have a greater effect on sales rather than public opinions and
criticisms when it comes to Apple.
