# 🚀 Semantic Segmentation using DINOv2

## 📌 Project Overview
This repository contains a semantic segmentation model built using a pretrained DINOv2 Vision Transformer backbone and a custom CNN decoder head.

The model performs pixel-wise classification into 10 semantic classes.

---

## 🏗️ Model Architecture

- **Backbone:** DINOv2 (dinov2_vits14)
- **Decoder:** Custom CNN Head
- **Input Resolution:** 252 × 448
- **Output Classes:** 10
- **Framework:** PyTorch

---

## ⚙️ Key Features

- Pretrained Vision Transformer backbone
- Multi-layer convolution decoder
- End-to-end training pipeline
- Optimized inference workflow

---

## 📊 Validation Performance

| Metric | Score |
|--------|--------|
| IoU | **0.4442** |


---

## 🖼️ Sample Prediction
<img width="1003" height="505" alt="Screenshot 2026-02-28 012141" src="https://github.com/user-attachments/assets/442ca6da-a460-43de-9edc-a9dbfe894c26" />

---

## ▶️ How to Run

```bash
python train_segmentation.py
python generate_submissions.py
python evaluate_variants.py
```

---

## 📌 Tech Stack

- Python
- PyTorch
- OpenCV
- NumPy
