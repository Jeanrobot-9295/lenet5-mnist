# LeNet-5 on MNIST (PyTorch, macOS MPS)

This repository reproduces the classic LeNet-5 CNN on the MNIST dataset using PyTorch.
It is designed as a step-by-step learning project and runs on macOS (Apple Silicon) with MPS, while also supporting CPU/CUDA.

## Environment
- Python 3.10
- torch 2.2.2
- torchvision 0.17.2
- Jupyter Notebook

## Project Structure
```text
.
├── LICENSE
├── README.md
├── data
│   └── MNIST
├── notebooks
│   ├── 01_setup_check.ipynb
│   ├── 02_mnist_data.ipynb
│   ├── 03_lenet5_model.ipynb
│   ├── 04_one_batch_train.ipynb
│   └── 05_train_one_epoch.ipynb
├── outputs
│   ├── accuracy.png
│   ├── lenet5_mnist.pt
│   └── train_loss.png
└── requirements.txt

```

## Citation (BibTeX)

```bibtex
@article{lecun1998gradient,
  title={Gradient-based learning applied to document recognition},
  author={LeCun, Yann and Bottou, L{\'e}on and Bengio, Yoshua and Haffner, Patrick},
  journal={Proceedings of the IEEE},
  volume={86},
  number={11},
  pages={2278--2324},
  year={1998}
}

```
