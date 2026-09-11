# CA2: NumPy neural network

This project implements feed-forward neural networks and backpropagation manually in NumPy for a cardiovascular dataset classification task.

## Contents

- `notebooks/numpy_neural_network_cardio.ipynb`: preprocessing, train/test split, standardization, forward propagation, loss calculation, backpropagation, and parameter updates.
- `data/CA2_cardio_dataset.csv`: the dataset used by the notebook.

## Results from the project notes

- Initial model: about 72.54% training accuracy and 72.24% test accuracy.
- Three-layer tanh model: about 72.46% training accuracy and 72.03% test accuracy.
- ReLU model with Xavier initialization and Adam-style updates: about 74.04% training accuracy and 72.97% test accuracy.

These numbers are coursework results. They should not be read as evidence for a clinical or production medical model.
