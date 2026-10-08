# SegFormer - Pixel-wise Ambulance Segmentation

## Overview
SegFormer-B0 fine-tuned on the ambulance dataset for pixel-wise semantic segmentation.

## Dataset
- Training: 2001 image-mask pairs
- Validation: 1000 image-mask pairs
- Image size: 256x256
- Classes: 2 (background, ambulance)

## Model
- Base: nvidia/segformer-b0-finetuned-ade-512-512
- Fine-tuned on ambulance dataset
- Parameters: 3,714,796

## Training Results
| Epoch | Train Loss | Val Loss | Mean IoU | Dice | Pixel Acc |
|-------|-----------|----------|----------|------|-----------|
| 1 | 0.510 | 0.214 | 0.834 | 0.926 | 0.912 |
| 2 | 0.419 | 0.192 | 0.851 | 0.936 | 0.923 |
| 3 | 0.383 | 0.185 | 0.853 | 0.938 | 0.925 |
| 4 | 0.328 | 0.176 | 0.862 | 0.942 | 0.929 |
| 5 | 0.292 | 0.175 | 0.864 | 0.943 | 0.930 |

## Final Evaluation (100 validation images)
- Mean IoU: 0.8730
- Mean Dice: 0.9288
- Pixel Accuracy: 0.9268
- Max IoU: 0.9579

## Files
- notebooks/02_segformer_training.ipynb - Training notebook
- results/segformer/ - Training checkpoints
- results/comparison/ - Final comparison with YOLOv8
- models/ - Model config files
