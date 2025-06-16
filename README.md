# 🔥 Transformer From Scratch in PyTorch

This project implements a minimal **Decoder-Only Transformer** using PyTorch and PyTorch Lightning. The goal is to demystify the internals of attention mechanisms and position encoding by building a simple, end-to-end language generation model from scratch.

## 🚀 Features

- Minimal Transformer Decoder architecture
- Custom Attention and Positional Encoding modules
- Token-level training with dummy input/label pairs
- Generation using greedy decoding
- Integration with PyTorch Lightning for training

---

## 🧠 Model Architecture

- **Embedding Layer**: Converts token IDs to dense vectors
- **Positional Encoding**: Adds positional information to embeddings
- **Self-Attention**: Custom-built scaled dot-product attention
- **Feedforward Layer**: Maps hidden vectors to token vocabulary logits
- **Loss**: Cross-entropy on next-token prediction

---

## 📦 Dependencies

Install with:

```bash
pip install torch lightning
