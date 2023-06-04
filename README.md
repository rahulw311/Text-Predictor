# Text-Predictor

This is a project on a text predictor that is designed using Markov Chains.

The objective of this project was that given an input sequence, we try to predict the next word, based on the probability matrix created using the input corpus. The project is based on the Markov assumption-

Given a certain number of previous states, the predicted state is independent of all the other states that come before it.

These are some advantages of employing Markov Chains for text generation compared to other method:
1. Simple and easy to implement
2. Lower computation time

However the disadvantages of using Markov Chains to build text generator:
1. The generated text is as good as the input corpus (garbage in garbage out)

The Gutenberg corpus which is a part of NLTK was used as the input corpus for training the model. 3 classic Shakespeare books were used for training- Hamlet, Macbeth and Julius Caesar.
