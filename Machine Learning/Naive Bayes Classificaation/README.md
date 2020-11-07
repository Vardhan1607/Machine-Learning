# Text Analysis with Naive Bayes
1) Sentence classification: 
<br/>
Consider the files traindata.csv and testdata.csv. In these files, each row contains a sentence which belongs to one of 4 categories (science, sports, business, covid crisis). Learn a Naive Bayes classifier to predict the category of each sentence, based on the words in it (neglecting stop words). Use the training set to estimate the prior distribution over the class labels and class-conditional probabilities, i.e. the probability of each word occurring in a sentence having a particular class label. For each test sentence, your output should be the posterior distribution over the labels.
<br/>
i) Constructing the vocabulary without stop-words
<br/>
ii) Calculating the prior distribution of the labels
<br/>
iii) Calculating the class-conditional probabilities of each word in the vocabulary, for each topic
<br/>
iv) For each test sentence, creating the posterior distribution over the labels
<br/>
2) Sentence Completion
<br/>
Consider the datasets "40.csv" and "10.csv". In each sentence of "10.csv", the last word is not provided. The task is to predict it based on the remaining words in the sentence. Build your vocabulary from "40.csv" (except stop words). Assume that the missing words are part of this vocabulary. Consider this as a classification problem, where each word in the vocabulary may be considered as a class label. Use the Naive Bayes classifier to make probabilistic estimates of the missing words.
<br/>
i) Creating the vocabulary without stop-words 
<br/>
ii) Estimating the prior probabilities of all "labels", i.e. words in vocabulary 
<br/>
iii) Estimating the class-conditional probabilities of all words 
<br/>
iv) In each test sentence, calculating the most likely word in the missing position along with probability [2 marks]
