Text Generation using LSTM
This project demonstrates a simple text generation model using a Long Short-Term Memory (LSTM) neural network. The model is trained on a set of frequently asked questions (FAQs) about IIITs and generates new sentences based on the input text.

Overview
This project tokenizes input text data, creates sequences of tokens, pads them to a consistent length, and uses an LSTM model to predict the next word in the sequence. The model generates text by feeding it a seed word or phrase, and it predicts the next word in the sequence iteratively.

Key Steps:
Tokenization: Convert text into sequences of integer tokens.
Sequence Generation: Create input-output pairs for training where each sequence of words is used to predict the next word.
Padding: Ensure all input sequences have the same length by padding shorter sequences.
LSTM Model: Build and train an LSTM model to predict the next word in a sequence.
Text Generation: Generate new text by predicting the next word based on the current input sequence.
Dataset
The dataset is a collection of FAQs about IIIT Allahabad and lower IIITs. The model uses these FAQs as training data to generate text based on the structure and vocabulary of the input dataset.

