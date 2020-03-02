# Text_Classification_NLP

There are lots of use-cases we can actually explore in this particular domain i.e **NLP**
So let's start with *Text Classification* for the dataset of the BBC news with the 5 categories. 

Here we are focussing on two of the classification algorithms i.e **SVM** and **Naive Bayes**.

For Data preprocessing the following major steps are undertaken: 
- Removing blank rows if any.
- Changing all the text format to lower case. 
- Perform Word tokenisation 
- Removing stopwords 
- Removing non-alphabatic text
- Word lemmatization

## Preparing Dataset for the training 
Lets split the dataset in Train-test split with a ratio of 70%-30%.

## Perform encoding for better understanding of the data by converting the Categorial data into the Numeric one. 

## Perform Word Vectorization which means turning a collection of text documents into numerical feature vectors to get the frequency of each other associated with the particular text statement. 
The approach I considered here is **TF-IDF (Term Frequency - Inverse Document Frequency)** 
The TF-IDF build a vocabulary of words which it has learned from the dataset and it will assign a unique integer number to each of these words.

## Applying Classification algorithms to make the classification
SVM & Naive Bayes 

## Accuracy Measues 
SVM : 98.35329341317365
Naive Bayes : 97.30538922155688

### First step is made, more changes will be made in this repo. 
