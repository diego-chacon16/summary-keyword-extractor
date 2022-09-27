# Text Summarization with Sumy

#### What is Sumy?

+ Is a simple library used for extracting summary from HTML pages or plain texts
+ The package also contains simple evaluation framework for text summaries

#### Goal

+ To build an extractive text summarizer highlighting the key points of the article

#### Approach

+ Import libraries and data
+ Create a function to wrap the text and easier to read
+ Build the summarizer and parser using sumy packages
+ Add them to the dataframe
+ Clean the data and remove unwanted or unnecessary character
+ Using keybert, extract keywords from the clean summary

# VADER

### What is VADER?

+ VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. (https://github.com/cjhutto/vaderSentiment)

### How is it scored?

+ The compound score is computed by summing the valence scores of each word in the lexicon, adjusted according to the rules, and then normalized to be between -1 (most extreme negative) and +1 (most extreme positive). This is the most useful metric if you want a single unidimensional measure of sentiment for a given sentence. Calling it a 'normalized, weighted composite score' is accurate. (https://github.com/cjhutto/vaderSentiment)

# Keybert

### What is KeyBERT?
