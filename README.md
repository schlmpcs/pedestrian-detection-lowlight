# Pedestrian Detection in Low-Light

This project tackles the **Find Person in the Dark** challenge — detecting pedestrians in low-light visible-light images using **YOLOv8**.  
All work is based on the LLVIP dataset (visible subset only).

---

## Model Setup

| Parameter | Value |
|------------|--------|
| Model | YOLOv8n |
| Epochs | 50 |
| Image Size | 640 |
| Batch Size | 16 |
| GPU | RTX 4060 Laptop |
| Train Time | ~87 min |

---

## Results

| Metric | Value |
|:-------|:------:|
| Precision | 0.948 |
| Recall | 0.931 |
| mAP@0.5 | 0.971 |
| mAP@0.5:0.95 | 0.632 |
| Kaggle Score  | **0.06785** |

---

## How to Run
```bash
pip install ultralytics albumentations opencv-python matplotlib
jupyter notebook person_detection.ipynb
