English → Hindi Neural Machine Translation using Transformers

A complete implementation of an Encoder-Decoder Transformer for English-to-Hindi Neural Machine Translation built entirely from scratch in PyTorch.

The goal of this project is to understand how modern sequence-to-sequence transformers work internally by implementing every major component instead of relying on high-level libraries. From data preprocessing and tokenizer training to multi-head attention, positional encodings, cross-attention, autoregressive decoding, and training, every part of the translation pipeline is built manually.

The model is trained on the IITB English-Hindi Parallel Corpus using separately trained SentencePiece tokenizers for English and Hindi. The project follows the architecture introduced in the paper "Attention Is All You Need", while keeping the implementation educational, modular, and easy to understand.

Features
🧠 Transformer implemented completely from scratch in PyTorch
🌍 English → Hindi Neural Machine Translation
📝 Custom SentencePiece tokenizers for both languages
🔤 Learned token embeddings with sinusoidal positional encodings
🎯 Multi-Head Self Attention implementation
🔄 Encoder-Decoder Cross Attention
📚 Teacher Forcing during training
🚀 Autoregressive inference for translation generation
🎭 Padding masks and causal masks implemented manually
📦 Efficient bucketed batching for faster training
💾 Checkpointing and mixed-precision training support for Google Colab
Project Structure
Data preprocessing and corpus filtering
SentencePiece tokenizer training
Dataset and DataLoader pipeline
Transformer Encoder
Transformer Decoder
Multi-Head Attention
Positional Encoding
Training Pipeline
Inference Pipeline
Model Evaluation
Tech Stack
Python
PyTorch
SentencePiece
HuggingFace Datasets
Google Colab (T4 GPU)
Learning Objectives

This project was built primarily to gain a deep understanding of:

Transformer architecture
Self Attention and Cross Attention
Sequence-to-Sequence Learning
Neural Machine Translation
Teacher Forcing
Autoregressive Decoding
Attention Masking
Tokenization using SentencePiece
Efficient NLP data pipelines
Training large deep learning models from scratch
Future Improvements
Beam Search decoding
BLEU score evaluation
Label smoothing
Learning rate warmup scheduler
Mixed precision optimization
Bidirectional translation (English ↔ Hindi)
Larger Transformer variants
ONNX / TorchScript model export
Simple web interface for live translation
