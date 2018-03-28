# Cosine-Similarity-Classifier

I was messing around with cosine similarity as a distance metric, when I decided to try to see if it could capture similarity relationships between MNIST images.  
Much to my surprise, just using cosine similarity to classify MNIST images actually worked to a high degree of accuracy.  I decided to try to turn this into a model, and
I unknowingly created a K-nearest neighbors equivalent that uses cosine similarity instead of other classic distance measures (I had heard of K-NN before but didn't 
actually know how it worked until after I developed the model and looked up what I had built, seeing if there was already anything similar to what I had done :).

I threw all the notebooks I used to create this model into the "Model Development" folder for reference.  The final model, along with its analysis and comparison to 
the K-NN model offered by Scikit-Learn is in the "Cosine-Similarity Model Analysis" notebook.  In the "Cosine-Similarity Model Analysis" notebook, it is found that 
the Cosine-Similarity Model I created is up to two times faster than the Scikit-Learn K-NN model, and slightly more accurate.

I am not in college yet and have noone to ask questions of or speak to about this, so if you have any criticism or comments please email me at samgrassii@protonmail.com.