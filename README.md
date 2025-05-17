# 🧠 Deep Learning from Scratch – Karpathy Zero to Hero

This repository is my **comprehensive implementation and notes** while learning deep learning from scratch based on **Andrej Karpathy’s [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLpB0WlhQNRL5uW5rKzjQu1XRy-7P_g5sB)** playlist and associated projects like [`micrograd`](https://github.com/karpathy/micrograd) and [`makemore`](https://github.com/karpathy/makemore).

> 🎓 My goal is to build neural networks from first principles, document the entire journey with notes and notebooks, and understand how modern deep learning models (like GPT) work under the hood.

---

## 📚 Contents

```bash
deeplearning-zero-to-hero/
│
├── 00_micrograd/              # Micrograd reimplementation
│   ├── engine.py              # Autograd engine
│   ├── nn.py                  # MLP
│   ├── micrograd_notes.md     # Conceptual notes
│   └── micrograd_colab.ipynb  # Colab notebook
│
├── 01_bigram/                 # Bigram character-level LM
│   ├── bigram.py
│   ├── bigram_notes.md
│   └── bigram_colab.ipynb
│
├── 02_makemore/               # makemore-style name generation
│   ├── model.py
│   ├── train.py
│   ├── makemore_notes.md
│   └── makemore_colab.ipynb
│
├── 03_attention/              # Self-attention, transformer blocks
│   ├── attention.py
│   ├── transformer.py
│   ├── attention_notes.md
│   └── attention_colab.ipynb
│
├── 04_gpt/                    # Final GPT-style model
│   ├── gpt.py
│   ├── tokenizer.py
│   ├── gpt_notes.md
│   └── gpt_colab.ipynb
│
├── 05_experiments/            # Personal extensions and tweaks
│   ├── new_dataset.py
│   └── my_experiments.ipynb
│
├── utils/                     # Shared utilities
│   ├── tokenizer.py
│   └── helpers.py
│
├── assets/                    # Images, diagrams
│
├── requirements.txt
└── README.md
