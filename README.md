# IMDB Classification with GRU + Self-attention

## Overview

This project implements IMDB classification using PyTorch. The model utilizes GRU and self-attention mechanism for improved performance.

## Requirements

- PyTorch
- TorchText

## How to Run

```bash
python train.py
```

## Results

### With self-attention
- Train Loss: 0.134 | Train Acc: 94.97%
- Val. Loss: 0.284 | Val. Acc: 89.95%
- Test Loss: 0.298 | Test Acc: 89.41%

### Without self-attention
- Train Loss: 0.193 | Train Acc: 92.56%
- Val. Loss: 0.358 | Val. Acc: 87.17%
- Test Loss: 0.376 | Test Acc: 86.76%

## Note

- Trained weights for the models are stored in `./weight/weight_w_attention.pth` (with attention) and `./weight/weight.pth` (without attention).
- Attention visualization feature is available by running `python train.py`, with visualized figures stored in `./fig/`.


