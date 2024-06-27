Evolution of Transformers is from 
RNN --> LSTM (or GRU) --> Transformers 

Challenges with RNN --> Slow Computation, Vanishing or exploding Gradient, loss of long term context or short term 
Challenges with LSTM (GRU) --> Computational complexity, Long training times, Limited interpretability


Words sequence is taken --> Embedding is done and we get 512 dimension vector 

Embedding are added to Positional encoding , which are fixed values basing on position calculated by 
![image](https://github.com/rajeunoia/GenAIStudy/assets/26647401/ad29c22f-bee8-462b-9b5a-ec3682314245)
sin and cosing values help in showing the position and we will understand it better when we run through an example. 
positional encoding explained in detail in this link, https://machinelearningmastery.com/a-gentle-introduction-to-positional-encoding-in-transformer-models-part-1/

Continue from here , https://youtu.be/bCz4OMemCcA?t=1728
