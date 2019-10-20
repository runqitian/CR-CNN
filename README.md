# CR-CNN Implementation 
## Introduction
This model is an implementation of Classification Relatoins by Ranking with Convolutional Neural Network, paper link is https://arxiv.org/abs/1504.06580 <br/>
Word Embedding link is: http://nlp.stanford.edu/data/glove.6B.zip
In the paper, the author used a 400d Embedding, while in this implementation I use a 300d Embedding. Other parameters keep the same.

## Performance
'''
                    precision    recall  f1-score   support

Entity-Destination       0.85      0.90      0.88       292
     Entity-Origin       0.83      0.78      0.81       258
 Content-Container       0.81      0.84      0.82       192
     Message-Topic       0.76      0.94      0.84       261
  Product-Producer       0.73      0.74      0.74       231
 Member-Collection       0.78      0.92      0.84       233
      Cause-Effect       0.91      0.90      0.90       328
 Instrument-Agency       0.71      0.73      0.72       156
   Component-Whole       0.86      0.75      0.80       312

         micro avg       0.81      0.84      0.83      2263
         macro avg       0.80      0.83      0.82      2263
      weighted avg       0.82      0.84      0.83      2263
'''
