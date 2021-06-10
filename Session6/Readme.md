The Encoder Decoder Architecture has been used for the Seq2Seq( Sequenceto sequence Prdeiction).The Long Short-Term Memory (LSTM) neural network fits the requirement to model this type of problem because it can learn long-term dependencies in the data.
![encoder_decoder](https://user-images.githubusercontent.com/70034867/121585067-ca49e680-ca4f-11eb-99da-e6e413fed787.png)


The LSTM encoder-decoder consists of two LSTMs. 
1.The first LSTM, or the encoder, processes an input sequence and generates an encoded state. The encoded state summarizes the information in the input sequence. 2.The second LSTM, or the decoder, uses the encoded state to produce an output sequence. 

****Note that the input and output sequences can have different lengths.

Approach to modeling 
 #the input data will be a sequence of strings in array which will start with <sos> and end with <eos>.
 #preprocessing - >first convert each word to unique token of integer number, then use One-Hot Encoding to represent each word.
 #The Embedding layer will take the input data and output the embedding vector.
 #LSTM Layer, which takes the embedding_dim as the input data and create total 3 outputs – hidden, cell and output Define the number of neurons required in LSTM, which is defined using the hidden dimension.
 #
  

