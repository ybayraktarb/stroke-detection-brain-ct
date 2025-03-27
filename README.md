# stroke-detection-brain-ct
Deep learning-based stroke detection on brain CT images using CNNs and ensemble models


## Project Overview

This project aims to classify CT slices as either:

- `Normal`
- `Stroke`

The model uses transfer learning and fine-tuning on CNN architectures with advanced metrics and threshold optimization techniques.

---

## Models Implemented

- EfficientNetB0–B4
- EfficientNetV2-S
- ResNet18 / 34 / 50
- VGG13 / VGG16
- DenseNet121
- YOLOv8-M (for object-level classification)
- Weighted Ensemble Model

---

## Evaluation Metrics

- F1-score (macro & weighted)
- Accuracy
- ROC-AUC, PR-AUC
- Confusion Matrix
- Brier Score
- Calibration Curve
- Optimized Classification Thresholds

---

