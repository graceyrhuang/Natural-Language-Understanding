# Natural Language Understanding

### 1. Bag of words

[spam_prediction_with_bagofwords.ipynb](https://github.com/ElectronicTomato/Natural-Language-Understanding/blob/master/spam_prediction_with_bagofwords.ipynb) is a simple realization with the bag of word as tokenization method and followed with linear classification. Bags of word is a limited method, since it only taken account of the word appeared in the sentence, neglecting the word order, co-occurrence of word, let alone the semantic meaning of the word. Meanwhile, linear classification is also not an expressive model. Prediction on spam managed to reach 95% despite all those effects. This might have ample to do with the spam prediction itself. Spam prediction samples are not long.  If some specific words, like 'buy', 'sold', etc. appear in the sample, the model is going to be determined as spam. If we replace website address as 'http://XXX', tel-phone number as '(XXX)XXX-XXXX', this model can reach higher accuracy. 

Overall, bag of words if an classic tokenize method, with multinomial Bernoulli probability as mathematical backup, is simple and well enough to support some simple tasks.



### 2. BiLSTM



### 3. What are we talking about when we are talking about BERT

BERT is the game changer in the NLP domain. 