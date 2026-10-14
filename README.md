# Decoder-Only Transformer for Text Generation

A beginner-friendly Generative AI experiment that uses a decoder-only Transformer to perform **next-word prediction and simple text generation**.

## Overview

This project explores how decoder-only Transformer architectures work by training a small model on sample sentences related to Artificial Intelligence, Machine Learning, Python, and Transformers.

The model learns patterns from the provided text and predicts the next word based on the preceding words. It can also generate a short sequence of text by repeatedly predicting and appending the next word.

## Features

- Text tokenization and padding
- Token and positional embeddings
- Decoder-only Transformer architecture
- Masked self-attention
- Next-word prediction
- Autoregressive text generation
- Training using TensorFlow and Keras

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy

## How It Works

1. **Dataset Creation:** Uses sample sentences related to AI, ML, and programming.
2. **Tokenization:** Converts words into numerical token sequences.
3. **Input and Target Preparation:** Shifts token sequences so the model learns to predict subsequent tokens.
4. **Embedding:** Combines token embeddings with positional embeddings to represent words and their positions.
5. **Masked Self-Attention:** Prevents each position from accessing future tokens during prediction.
6. **Transformer Blocks:** Processes the input using masked attention, feed-forward layers, residual connections, and layer normalization.
7. **Model Training:** Trains the model to predict the next token at each position.
8. **Text Generation:** Predicts a word, appends it to the input, and repeats the process to generate text.

## Model Architecture

The model consists of:

- Token and positional embedding layers
- Two decoder-only Transformer blocks
- Multi-head masked self-attention
- Feed-forward neural networks
- Layer normalization and dropout
- Dense output layer with softmax activation

## Installation

Install the required libraries:

```bash
pip install tensorflow numpy
```

## Example

**Starting text:**

```text
i love
```

**Task:** Predict the next word and generate additional words.

The script also tests prompts such as:

- `machine learning`
- `decoder transformer`
- `gpt`
- `students learn`

The generated output depends on the trained model and its small vocabulary.

## Learning Outcomes

Through this experiment, I explored:

- How decoder-only Transformers process text
- The importance of masked self-attention
- How next-token prediction works
- The role of embeddings and positional information
- How autoregressive text generation works
- How Transformer models are trained using TensorFlow and Keras



## Acknowledgement

This project is an educational experiment to understand decoder-only Transformer architectures and the fundamentals of Generative AI. The project is intended primarily for learning and understanding the underlying process rather than building a production-ready language model.

---

**Author:** Bela
