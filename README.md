# modelingeditorialslants
# LDA TOPIC MODELING


## This notebook applies LDA modeling to a an dataset of 480 news articles shared to Reddit and Twitter, along with their corresponding comment threads

## The utility of topic modeling methods is their capability to uncover unobserved variables—topics—which shape the meaning of textual documents. 

### In the following case, we are interested in understanding what characteristics of news articles elicit user engagement on social media
using the GENSIM, NLTK, spaCy, and SKLearn libraries:

https://radimrehurek.com/gensim/

https://www.nltk.org

https://scikit-learn.org/stable/

https://spacy.io



# Steps

## 1. Preparing the text for preprocessing
    1a. Spell check
    1b. Expand contractions

## 2. Text preprocessing

     2a. Partition data into testing and training subsets
 
     2b. Tokenization
     
     2c. Stop Word Removal
     
     2d. Lemmatization
     
     2e. Bigrams and Trigrams
     
     2f. Exclude terms in > 99% and < 1% of documents
     
     2g. Generate Corpus and Dictionary
 

## 2. Selecting the number of topics (k)
 
     2a. Computing Model Perplexity


## 3. Model Results

     3a. pyLDAvis visualization to assist with Topic Labeling
     
     3b. Topic Mixtures (Document-Term Matrix)

 
# Helpful Links:

https://medium.com/@lettier/how-does-lda-work-ill-explain-using-emoji-108abf40fa7d

     
https://towardsdatascience.com/light-on-math-machine-learning-intuitive-guide-to-latent-dirichlet-allocation-437c81220158
