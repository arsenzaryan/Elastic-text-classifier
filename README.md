##Method
The search functionality of Elasticsearch can be modified a bit to act
 as a text classifier. For that, all the data with its labels should be loaded
 to a separate index. Then, for a given query, all the hits that match it can be parsed 
 and their statistics aggregated to obtain prediction probabilities.
 
 
 ##Code
 The jupyter notebook defines all the functions needed to implement the 
'Elasticsearch Text Classifier'. It also demonstrates an actual realization of the idea 
for a toy data.

## Comparison with NLP classifiers
Of course, Elasticsearch isn't supposed to replace machine learning techniques for text 
classification (Fasttext, Bert, etc), 
but in some use-cases it may show satisfactory results without 
much engineering effort 
  