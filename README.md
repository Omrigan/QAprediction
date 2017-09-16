# Unified sentence embedding \\ for question answering

[Poster](https://github.com/Omrigan/QAprediction/blob/master/unified-sentence-embedding.pdf)

In [this paper](http://dl.acm.org/citation.cfm?id=2505665) Deep Structured Semantic Model was proposed. General idea is finding a deep vector representation for logically binded objects.  In my work I try to adapt this idea for Russian-language question&answering problem. LSTM and triplet loss are being combined for learning two separate mappings for questions and answers and then finding the nearest answer for given question with respect to given metric (euclidean in this case).

## Futher exploration


![pic](https://github.com/Omrigan/QAprediction/raw/master/dream_model.jpg)



## ToDo list
1. Try to train decoder to answer from semantic space
2. Implement GAN for decoder
3. Try decoder to itself
4. Conv
5. Reimplement topics
