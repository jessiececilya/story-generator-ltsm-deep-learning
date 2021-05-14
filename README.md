# story-generator-ltsm-deep-learning
Story generator using Deep learning- LTSM model trained on Microsoft Open Research Dataset "Hippocorpus"

Deep Learning is found in every application we use from Chatbots, Face recognition etc. 

In this project I have built a deep learning model that could write a short story. Microsoft’s Research Open Data repository has been a boon for this project of mine. 
I have used the dataset “Hippocorpus” which is a collection of 6854 dairy like short stories to train the model. I have generated ngram sequences to 
predict nth word using n-1 words. The n-gram sequences were padded to ensure all the input sequences are of uniform length

LSTM in its core, preserves information from inputs that has passed through it using the hidden state. I have used Bidirectional LSTM, so that model trains the 
data based on the past and future input sequences to ensure there exists a flow in the story that is generated. 

Learn about LSTM here: https://colah.github.io/posts/2015-08-Understanding-LSTMs/#:~:text=Long%20Short%20Term%20Memory%20networks,many%20people%20in%20following%20work.

