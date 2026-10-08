# Ambulance Detection Using YOLOv8 + SegFormer

## Project Overview
Real-time ambulance detection from traffic camera feeds using YOLOv8 for detection and SegFormer for pixel-wise semantic segmentation.

## Team Members
- P. Vasavi (23A81A61B4)
- Sk. Jilani (23A81A61C2)
- R. Naga Gowthami (23A81A61B6)
- M. Bharath (23A81A61A3)

## Guide
Mr. P V V Satyanarayana

## Project Status
- [x] Dataset preparation (3000+ images from 10 countries)
- [x] YOLOv8 detection training (100 epochs)
- [x] YOLOv8 evaluation (98% mAP50)
- [x] SegFormer segmentation training (5 epochs)
- [x] SegFormer evaluation (87% IoU)
- [x] Final comparison complete

## Results Summary

### YOLOv8 Detection
| Metric | Value |
|--------|-------|
| Precision | 97.6% |
| Recall | 94.9% |
| mAP50 | 97.9% |
| mAP50-95 | 86.3% |
| F1-Score | 96.2% |

### SegFormer Segmentation
| Metric | Value |
|--------|-------|
| Mean IoU | 87.3% |
| Mean Dice | 92.9% |
| Pixel Accuracy | 92.7% |

## Tech Stack
- Python 3.10+
- PyTorch
- Ultralytics YOLOv8
- HuggingFace Transformers (SegFormer)
- Google Colab

## Folder Structure
- notebooks/ - Training notebooks
- results/ - Training outputs and comparisons
- models/ - Model configuration files
- data/ - Dataset documentation

## Dataset
See data/README.md for the download link.
