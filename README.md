# neural-primitives

> Foundational building blocks, mathematical derivations, and first-principles implementations of classical and neural machine learning algorithms.

This repository serves as a structured engineering log and reference codebase. Implementations and theoretical notes progress systematically from classical statistical learning and optimization primitives to spatial, sequential, and generative deep architectures.

## Repository Structure

```text
neural-primitives/
├── 01-classical-ml/  # Linear/Logistic Regression, SVMs, Decision Trees, K-Means, PCA from scratch
├── 02-ann/           # Multi-Layer Perceptrons, backpropagation, activation functions, initialization
├── 03-cnn/           # 2D/1D convolutions, pooling, receptive fields, residual connections
├── 04-rnn/           # Vanilla RNNs, LSTMs, GRUs, BPTT, vanishing/exploding gradient analysis
├── 05-transformers/  # Scaled dot-product attention, multi-head mechanisms, positional encodings
├── 06-gans/          # Minimax games, DCGAN, Wasserstein loss (WGAN), mode collapse diagnostics
├── notes/            # Mathematical derivations, algorithmic complexity, and paper summaries
└── pyproject.toml    # Dependency and environment lockfile
