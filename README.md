# Language-Translation

Here I am using seq2seq Neural network.

Steps:
Download the dataset for english and french text.
Converted data into dataframe.
Tokenized the sentence to full length as we are not having large dataset.
Padded the sentence to the maximum sentence length available for respective languages.
Used Encoder and Decoder to translate.

<b>Encoder:</b> Encoder help in training the dataset in english and can later the output from the last layer i.e <b>CellState<b> and the <b>output(H)</b> to the decode the data

<b>Decoder:</b> Decoder will take the output from the encoder and will use it to decode and again it'll give an output in 3x3


Here in this we usign multiple LSTM layers.

<img src="model.jpg" alt="Model">
  

