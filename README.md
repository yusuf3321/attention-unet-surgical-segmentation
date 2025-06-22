# Attention U-Net for Surgical Instrument Segmentation

This repository contains Jupyter notebooks for real-time segmentation of surgical instruments in laparoscopic videos using the Attention U-Net architecture.

## Files
- `mainproject.ipynb`: Full training pipeline using Attention U-Net
- `splitdataset.ipynb`: Dataset split and preprocessing
- `arxıv test.ipynb`: Exported version for publication testing

## Model
- Architecture: Attention U-Net
- Loss: Binary Cross-Entropy
- Optimizer: Adam (lr=1e-4)
- Epochs: 20
- Real-time FPS: 2.58

## Results
- IoU: 0.8043
- F1-score: 0.8875
- Precision: 0.8118
- Recall: 0.9871

## Author
Yusuf Salık – Independent Researcher

## License
MIT
