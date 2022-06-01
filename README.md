The Encoder-Decoder model is used to perform neural machine translation. Instead of a
simple recurrent neural network, Long Short-term Memory (LSTM) and Gated Recurrent
Unit (GRU) are used to build four different models. The performance of the four models on
three sizes of the dataset is evaluated using BLEU (BiLingual Evaluation Understudy) score.
The model with GRU as both encoder and decoder is found to be more appropriate for
smaller dataset sizes with fewer translation pairs. The encoder-decoder model with LSTM as
an encoder and GRU as a decoder had performed consistent best for larger dataset sizes with
more translation pairs.
