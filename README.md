# Cosine-Similarity-Classifier

An implementation of a parsimonious K-NN model that yeilds a sizeable performance boost over standard K-NN algorithms from 
Scikit-Learn.

I placed all the notebooks I used to create this model into the "Model Development" folder for my reference.  
The final model, along with its analysis and comparison to the K-NN model offered by Scikit-Learn is in the 
"Cosine-Similarity Model Analysis" notebook. 

## Model Development

Realizing the potential of cosine similarity as a distance metric, I decided to try and see if it could capture 
the relationships between MNIST images.  Much to my surprise, just using cosine similarity to classify MNIST 
images actually worked to a high degree of accuracy.  I decided to try to turn this into a model, and unknowingly created 
a K-nearest neighbors equivalent that uses cosine similarity rather than more common distance metrics (I had heard of 
K-NN before but didn't actually know how it worked until after I developed the model, and found the description 
of this model to be exaclty the same as K-NN :).

Unfortunately, I am not in college yet, so I generally have no-one to ask questions of or talk to about these
kinds of problems, and carefully worded questions on forums also tend to lack in helpful replies.  If you have any
criticism or comments of the model, I would greatly appreciate your feedback.  Feel free to email me at 
samgrassii@protonmail.com.
