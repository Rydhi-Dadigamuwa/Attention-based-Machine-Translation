# Attention-Based Neural Machine Translation

This project implements a **Neural Machine Translation (NMT)** system using the **Bahdanau-style attention mechanism**. The model is designed to learn alignment between input and output sequences dynamically, leading to improved translation performance and interpretability.



## 📄 Inspired By

> **"Neural Machine Translation by Jointly Learning to Align and Translate"**  
> Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio  
> [arXiv:1409.0473](https://arxiv.org/abs/1409.0473)



## ⚙️ Architecture Overview

The model consists of the following main components:

- **Bidirectional LSTM Encoder:** Processes the input sentence from both directions.
- **Bahdanau Attention Mechanism:** Calculates attention scores between each decoder time step and all encoder time steps.
- **LSTM Decoder:** Generates output tokens using the dynamically computed context vector.

