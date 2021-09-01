# English-DeutschTranslator
The objective is to implement language translation model for converting German to English and vice versa.
For this, the data is a text file (.txt) of English-German sentence pairs.
The actual data contains over 150,000 sentence-pairs.
However, in the source code only 50,000 sentence pairs were used to reduce the training time of the model.


The data is quite unstructured so there are certain things were took care-of before building the model: 
(a) Text Cleaning 
(b) Text to Sequence Conversion 

A Seq2Seq model requires that we convert both the input and the output sentences into integer sequences of fixed length.

Editor: Google Colab
