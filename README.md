## This is the github repo for the group project - 
The project was built as part of the final project of the 8th Semester as part of my BTech CE course. 

## Concept of LSTM - 
LSTM stands for Long Short-Term Memory. It's a recurrent neural network (RNN) architecture designed to handle sequence data, particularly data with long-range dependencies. Unlike traditional RNNs, which struggle with the vanishing gradient problem, LSTMs use specialized "gates" (input, forget, and output gates) to regulate the flow of information through the network. This allows them to effectively learn and remember information over extended periods, making them well-suited for tasks involving sequential patterns.

LSTM's Use in Language Translation:
In language translation, LSTMs are typically employed within an encoder-decoder framework. Here's how they're used:
Encoding:
1. The source language sentence (e.g., French) is fed into an LSTM encoder, word by word.
2. The encoder's LSTM processes the input sequence, updating its internal state to capture the meaning and context of the sentence.
3. The encoder's final hidden state is a compressed, context-rich representation of the entire source sentence.
Decoding:
1. The encoder's final hidden state is passed as the initial hidden state to an LSTM decoder.
2. The decoder's LSTM generates the target language sentence (e.g., English), word by word.
3. At each step, the decoder's LSTM uses its previous hidden state and the previously generated word to predict the next word in the translation.

USTMs in both the encoder and decoder allow the model to capture the complex dependencies between words in the source and target languages.
This allows the model to learn the grammatical structure, semantic meaning, and contextual nuances necessary for accurate translation.
Other Kears functions like Embeddings, Dense were also used. 

## Tools and Technologies used - 
1. Python
2. Juypter Notebook
3. Pandas
4. Keras
5. Matplotlib
   
# Kaggle Notebook - https://www.kaggle.com/code/adityabhambere/machine-translation-fr-en-with-bleu-score

