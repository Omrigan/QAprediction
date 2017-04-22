# Using Deep Structured Semantic Model for question answering
In http://dl.acm.org/citation.cfm?id=2505665 DSSM was proposed. General idea is findng a deep vector representation for objects. In my work I try to adapt this idea for Russian langague question&answering problems. LSTM and triplet loss are being combined for learning those deep vector representations and finding the nearset answer for given question with respect to given metrics (euclidean in my case).



## Futher exploration


![pic](https://github.com/Omrigan/QAprediction/raw/master/dream_model.jpg)



## ToDo list
1. Try to train decoder to answer from semantic space
2. Implement GAN for decoder
3. Try decoder to itself
4. Conv
5. Reimplement topics
