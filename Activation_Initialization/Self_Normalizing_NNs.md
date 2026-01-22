## Self-Normalizing Neural Networks

Authors: Günter Klambauer, Thomas Unterthiner, Andreas Mayr, Sepp Hochreiter

Link: https://arxiv.org/abs/1706.02515

Notes:

- Addresses a key problem: standard feed-forward neural networks (FNNs) usually do not work well when they are deep, unlike CNNs and RNNs. This is mainly due to unstable activations and gradients.

- Highlights SNNs (Self-normalizing Neural Networks)

- SNNs use a special activation function called SELU (Scaled Exponential Linear Unit) that makes neuron activations automatically converge to zero mean and unit variance, without needing Batch Normalization.
