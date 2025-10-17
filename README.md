# Transformer101

A single-notebook implementation of a GPT-style Transformer built from scratch using **PyTorch**.

---

## 🧠 Overview

This notebook walks through every component of a mini-GPT model:

- **Tokenization:** character-level  
- **Embeddings:** token + positional encodings  
- **Attention:** multi-head causal self-attention  
- **Feedforward:** MLP with residual connections  
- **Training & Generation:** end-to-end text modeling

---

## 📘 Data

The notebook automatically downloads the **Tiny Shakespeare** dataset from the web and splits it into train and validation sets.

No manual data setup is required.

---

## ⚙️ How to Run

```bash
pip install torch numpy tqdm
jupyter notebook Transformer101.ipynb
