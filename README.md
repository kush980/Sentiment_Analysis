# Sentimental Analysis

Sentiment analysis is the area which deals with judgments, responses as well as feelings, which is generated from texts, being extensively used in fields like data mining, web mining, and social media analytics because sentiments are the most essential characteristics to judge the human behavior. Sentiment analysis works on discovering opinions, classify the attitude they convey, and ultimately categorize them division-wise. Finding the appropriate dataset is a very important concern while dealing with sentiment analysis. Sentiment analysis can be functional for reviewing products for business, to ascertain the high and lows of stock markets to understand the mentality of people reading news Sentiment analysis is done basically because not every review that is received gives a direct “good” or a “bad” notion. Though sentiment analysis is very much helpful, the enhancement of the analysis depends on the amount of training data that has been fed into the machine. Generally there are different ways of classifying sentiments, the Machine learning approach and the lexicon-based approach being famous. When the Machine Learning approach is considered, it can be further categorized into supervised and unsupervised learning. While supervised learning can be defined as the process of learning from already known data to generate initially a model and further predict target class for the particular data, unsupervised learning can be defined as the process of learning from unlabeled to discriminate the provided input data.In the above project we will use supervised learning and will divide the reviews given to the restaurant into two parts "good" or "bad".

## Package:

The project has been made using **nltk** package and the functions or classes inside it.

### The text has been cleaned using stopwords from the nltk package and is filtered to not removing "negative" words like no,not,neither..etc .

### The cleaned texts has been stored into the corpus and from that all the words has been stored into a bag of words from where we train our model. The best accuracy i was able to obtain was 80% .
