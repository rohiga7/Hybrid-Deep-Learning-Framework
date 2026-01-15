# Hybrid-Deep-Learning-Framework

Node–Edge Temporal Prediction Framework
A deep learning framework for temporal prediction and binary classification on node–edge structured data.
Multiple architectures are implemented and compared, including Transformer-based models, recurrent models, feed-forward baselines, and a hybrid proposed architecture.

🚀 Features

✔ Supports multiple neural architectures
✔ Comparative model benchmarking
✔ Graph-inspired feature attention
✔ Temporal feature handling
✔ Visualization of metric performance
✔ Extensible for future datasets


1. Proposed Model (Graph Attention + BiLSTM + Capsules)

Architecture stages:

Custom Graph Attention layer to enhance feature relevance

Feature reshaping into sequential form

Bidirectional LSTM for temporal modeling

Capsule Network for representation enhancement

Sigmoid output for binary prediction

Designed to fuse structural dependency + temporal modeling.	

2. LSTM Model

Utilizes recurrent memory for sequential feature interpretation

Standard single-layer LSTM

Dense sigmoid output layer

Serves as temporal baseline model.

3. Transformer Encoder Layer (TEL)

Multi-Head Self-Attention for global dependency modeling

Feed-Forward Network with residual connections

Layer Normalization for stable training

Captures feature-to-feature relationships without recurrence.


4. MLP Baseline

Fully connected feedforward topology

No recurrence or attention

Useful for benchmarking
