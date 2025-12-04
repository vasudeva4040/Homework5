# Homework5 Machine Learning    N.Vasudeva Reddy (700782257)
Homework 5 – Transformers, Attention & Ethics

This repository contains the solutions for Homework 5, covering theoretical questions and coding tasks on transformer models, scaled dot-product attention, multi-head attention, and AI ethics.
It includes:

Well-structured written answers

A NumPy implementation of Scaled Dot-Product Attention

A PyTorch implementation of a Transformer Encoder Block

📘 Contents
├── PartA_Theory_Solutions.pdf   # Answers to conceptual questions
├── attention_numpy.py           # Q1: Scaled Dot-Product Attention (NumPy)
├── transformer_encoder.py       # Q2: Transformer Encoder Block (PyTorch)
└── README.md



🧮 Part B – Coding
Q1: Scaled Dot-Product Attention (NumPy)

Located in: attention_numpy.py

Features:

Stable softmax

Computes attention weights

Computes context vectors

Works for batch inputs

Run:

python attention_numpy.py


Expected output:

Attention weights shape: (batch, seq_q, seq_k)
Context shape: (batch, seq_q, d_v)

Q2: Transformer Encoder Block (PyTorch)

Located in: transformer_encoder.py

Implements:

Multi-Head Self-Attention

Layer Normalization

Feed-Forward Network

Residual Connections

Dropout

Run:

python transformer_encoder.py


Expected output:

Output shape: torch.Size([32, 10, 512])
