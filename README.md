# LeNet-5 on MNIST (PyTorch, macOS MPS)

This repository reproduces the classic LeNet-5 CNN on the MNIST dataset using PyTorch.
It is designed as a step-by-step learning project and runs on macOS (Apple Silicon) with MPS, while also supporting CPU/CUDA.

## Environment
- Python 3.10
- torch 2.2.2
- torchvision 0.17.2
- Jupyter Notebook

## Project Structure
- `notebooks/`
 - `04_one_batch_train.ipynb`: one-batch training sanity check (forward → loss → backward → step)
 - `05_train_one_epoch.ipynb`: full training loop, evaluation, and result plots
- `outputs/`
  - `train_loss.png`
  - `accuracy.png`
  - `lenet5_mnist.pt` (optional saved weights)

