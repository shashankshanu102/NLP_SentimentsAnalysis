# NLP_SentimentsAnalysis
**Problem Statement:** Find what are the most Customer customer concern areas and also find Sentiments of the people's.


**Introduction**
**What is Sentiment Analysis?**
Techopedia defines sentiment analysis as follows:
- Sentiment analysis is a type of data mining that measures the inclination of people’s opinions through natural language processing (NLP), computational linguistics and text analysis, which are used to extract and analyze subjective information from the Web — mostly social media and similar sources. The analyzed data quantifies the general public’s sentiments or reactions toward certain products, people or ideas and reveal the contextual polarity of the information. Sentiment analysis is also known as opinion mining.
There are two broad approaches to sentiment analysis.
Pure statistics:
-These kinds of algorithms treat texts as Bags of Words (BOW), where the order of words and as such context is ignored. The original text is filtered down to only the words that are thought to carry sentiment. For this blog, I will be attempting this approach. Such models make no use of understanding of a certain language and only uses statistical measures to classify a text.
A mix of statistics and linguistics:
-These algorithms attempt to incorporate grammar principles, various natural language processing techniques and statistics to train the machine to truly ‘understand’ the language.

Sentiment analysis can also be broadly categorized into two kinds, based on the type of output the analysis generates.
-1) Categorical/Polarity— Was that bit of text “positive”, “neutral” or “negative?” In this process, you are trying to label a piece of text as either positive or negative or neutral.
-2) Scalar/Degree — Give a score on a predefined scale that ranges from highly positive to highly negative. For example, the figure below shows an analysis of of sentiment based on tweets about various election candidates. In this instance the sentiment is being measured in a scalar form.

**Data Description:**
- The data was scrapped from Amazon and saved into Dataframe.
- Its consists of 14675 customer's reviews.

**Some of the steps performed are as follows:**

- 1.	Text Cleaning:
 - i) Normalizing case
 - ii) Tokenization
 - iii) Removal of stopwords and punctuations
 - iv) Stemmimg and Lemmatization
      
- 2.	Plot a bigram bar graph on the top words 25 stopwords
- 3.	Find customer concern areas - the top 25 bigrams which includes the below negative words indicating the customer concern areas
 'poor', 'waste', 'bad', 'defective', 'disgusting', 'untrusty', 'worst', 'horrible', 'unexpectedly', 'slow'
- 4.	Plot a bar graph for the top 25 customer concern areas
- 5.	Plot a bar graph for the top 25 customer concern areas?

**Conclusion:**

The age of getting meaningful insights from social media data has now arrived with the advance in technology. Companies have been 
leveraging the power of data lately, but to get the deepest of the information, you have to leverage the power of AI, Deep learning and 
intelligent classifiers like Sentiment Analysis. 
