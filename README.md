# modelingeditorialslants
## LDA Modeling of Topics Discussed in New Articles


## This notebook applies LDA modeling to a an dataset of 480 news articles shared to Reddit and Twitter

## Topic Modeling is a text analysis method that uses machine learning algorithms to classify the content of a large body of texts—called a corpus—into meaningful topics. 

## The specific technique used here, Latent Dirichlet Allocation (LDA), identifies underlying patterns of co-occurring words within individual texts to extrapolate latent categories across a corpus of texts (i.e., topics).

### In the following case, we are interested in understanding what characteristics of news articles elicit user engagement on social media relying heavily on the GENSIM, NLTK, spaCy, and SKLearn libraries:

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


https://www.jetbrains.com/education/
