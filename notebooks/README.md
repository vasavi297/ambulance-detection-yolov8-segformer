# YOLOv8 Base Implementation

## Overview
This notebook contains the YOLOv8 base implementation for ambulance detection.

## Status: ✅ COMPLETE

## What's Included
- Dataset loading and preprocessing
- YOLOv8n model training (100 epochs)
- Training metrics and evaluation
- Results saved to results/

## Results Achieved
| Metric | Value |
|--------|-------|
| Precision | 97.6% |
| Recall | 94.9% |
| mAP50 | 97.9% |
| mAP50-95 | 86.3% |
| F1-Score | 96.2% |

## Files
- `01_yolov8_base_implementation.ipynb` - Main notebook
- `../results/` - Training outputs and plots
- `../data/README.md` - Dataset download info

## How to Run
1. Clone this repository
2. Download dataset from Google Drive (link in `data/README.md`)
3. Open `01_yolov8_base_implementation.ipynb` in Google Colab
4. Run all cells

## Next Phase
SegFormer integration is in `feature/segformer` branch.
