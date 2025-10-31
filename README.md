#CIFAR-10 Training with some "well-known" methods

Simple models trained on the CIFAR-10 dataset using PyTorch.

## Usage
```bash
pip install -r requirements.txt
python
>>> import torch
>>> from cnn_model import CNN
>>> model = CNN()
>>> model.load_state_dict(torch.load('cnn_cifar10.pth'))
>>> model.eval()
