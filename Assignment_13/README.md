# Assignment 13 – Generative AI Essentials

An introduction to GPT architecture and a practical text-generation project using a simple LSTM model in Google Colab.

## Dataset

Alice’s Adventures in Wonderland by Lewis Carroll, downloaded from Project Gutenberg.

## Workflow

- Explain GPT architecture, attention, tokenization, and text generation.
- Clean the book text and convert characters into numerical IDs.
- Train an LSTM for 10 epochs to predict the next character from 40-character sequences.
- Generate text from a seed and demonstrate a basic creative writing assistant.
- Wrap generated output for easier reading.

## Tools and Usage

Python, TensorFlow/Keras, NumPy, requests, and textwrap. Open the notebook in Google Colab and run the cells in order. Enter a story starter when prompted, such as `alice walked into the garden and saw`.

## Limitations

The implemented model is an LSTM, not a GPT. Its generated text may contain spelling errors and unclear sentences because it learns from a small dataset and requires human editing.
