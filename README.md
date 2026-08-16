# MNIST NN + LoRA

A simple Neural Network built with PyTorch to classify handwritten digits from the MNIST dataset, with LoRA used for parameter-efficient training.

## Model

- Input: 28 × 28 MNIST image
- Hidden Layer 1: 1000 neurons
- Hidden Layer 2: 2000 neurons
- Output: 10 classes
- Activation: ReLU
- Optimizer: Adam
- Loss: Cross Entropy

## Tech Stack

- Python
- PyTorch
- Torchvision
- LoRA
- MNIST

## Run

```bash
pip install -r requirements.txt
python train.py
