### Deep Learning Recurrent Architectures
 -  [LSTM Network Variants](https://medium.com/jim-fleming/implementing-lstm-a-search-space-odyssey-7d50c3bacf93#.89xd4s9ii) This tutorial has a very nice approach to creating variations of LSTM Networks. A good approach to learning how to code a new network architecture and more importantly a methodical approach to understanding the gates in LSTM
 -  [Empirical Exploration of Recurrent Network Architectures](http://jmlr.org/proceedings/papers/v37/jozefowicz15.pdf)

This was mainly because I wanted to learn the actual implementations of various recurrent neural network architecures and implement them from scratch without using pre defined lstm, gru etc. This is directly a fork of [LSTM Network Variants](https://medium.com/jim-fleming/implementing-lstm-a-search-space-odyssey-7d50c3bacf93#.89xd4s9ii), with the code changes to run on the most recent version of tensorflow. (0.12.0 as of this writing). I will keep this repositiory upto date with the new changes.

Also this repo has more network architectures from here: [Empirical Exploration of Recurrent Network Architectures](http://jmlr.org/proceedings/papers/v37/jozefowicz15.pdf)

The implementations are not optimal, in the sense, that in the actual implementations of the LSTM, GRU and RNN cells the states and input are concatenated before multiplications to reduce the number of matrix multiplications whereas this is directly an implementation of the lstm network that you would see in a textbook.


### Other Tutorials with that are also helpful
 - [RNN Network implementation Tensorflow](https://medium.com/@erikhallstrm/hello-world-rnn-83cd7105b767#.qk7xgwwa4) A series of post on implementing recurrent neural network architectures. A good follow up post would be the next article.
 - [Reinforcement Learning](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0#.tpmlehy2p) A fantastic hands-on tutorial on reinforcement learning using the openAI platform.