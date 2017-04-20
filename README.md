# Using Deep Structured Semantic Model for question answering
In http://dl.acm.org/citation.cfm?id=2505665 DSSM was proposed. General idea is finidng a deep vector representation for objects. In my work I try to adapt this idea for question&answering problems. LSTM and triplet loss are being combined for  

The idea of finiding vector representation of data is not new. Encoder-decoder (link!) models and seq2seq (link!) modeling also try to find a latent space. In my work I try to find out if there is way of building a unversal latent space and corresponding set of transformations for different kinds of objects, such that vector from latent space can represent those objects. This idea allows to build different pipelines for any kind of problem with the data.

![pic](https://github.com/Omrigan/QAprediction/raw/master/dream_model.jpg)




## ToDo list
1. Try to train decoder to answer from semantic space
2. Implement GAN for decoder
3. Try decoder to itself
4. Conv
5. Reimplement topics
