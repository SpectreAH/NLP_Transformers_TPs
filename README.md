# NLP & Transformers TPs

This repository contains a collection of practical assignments (TPs) from the NLP and Transformers course at CY Tech (2026-2027). The work bridges classical Natural Language Processing, deep learning, and Large Language Models, culminating in the construction of a mini Transformer from scratch.

## Overview

The assignments follow a progressive learning path from raw text processing to advanced generative models:

* **TP 1: Machine Learning**
  * Built a complete NLP pipeline on the Tiny Shakespeare dataset.
  * Covered data cleaning, preprocessing, and text representation.
  * Compared multiple classical Machine Learning models and evaluated them using accuracy, precision, recall, F1-score, and confusion matrices.

* **TP 2: Deep Learning**
  * Extended the pipeline on the Tiny Shakespeare dataset.
  * Compared classical ML approaches directly with Deep Learning models (RNNs and LSTMs).

* **TP 3: Prompting & Fine Tuning**
  * Set up an LLM prompting pipeline using `flan-t5-small`.
  * Evaluated generated outputs (zero shot vs. few shot) and fine-tuned `gpt2` directly on the Tiny Shakespeare corpus.

* **TP 4: Mini Transformer**
  * Reconstructed a generative mini-Transformer model step by step.
  * Implemented core components: Data Tokenization, Self-Attention, Layer Normalization, and the Multi-Layer Perceptron (MLP).
  * Assembled the final architecture, evaluated the loss, and generated text.

## Tech Stack
* Python
* PyTorch
* Hugging Face Transformers (LLM prompting & fine tuning)
* Scikit-Learn (Classical ML baselines & evaluation)
