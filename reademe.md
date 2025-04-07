# IAM Handwritten Text Recognizer

A deep learning model for handwritten text recognition using the IAM Words dataset.

## Features

- Word-level recognition
- Custom CNN model
- Automatic dataset handling
- CER and WER evaluation
- TensorBoard logging
- ONNX export

## Installation

```bash
pip install -r requirements.txt
```

## Requirements

- Python 3.10.6
- PyTorch 1.13.1
- TensorBoard 2.10.1
- ONNX 1.12.0
- torchsummaryX

## Usage

```bash
python train.py
```

## Dataset

IAM Words dataset (automatically downloaded during training)

## Hardware Used

- CPU: Intel i7 10th Gen
- GPU: NVIDIA GTX 1650

## Project Files

```
configs.py
model.py
train.py
requirements.txt
README.md
```