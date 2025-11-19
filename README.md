# Image-Classification

This project applies deep learning and transfer learning techniques to classify images into 100 categories using a dataset sampled from multiple open image datasets. Since each class contains only ~10 colored images, the focus is on leveraging pretrained models, data augmentation, and hyperparameter tuning to prevent overfitting and improve generalization.

The entire workflow is developed and executed in **Google Colab** using modern pretrained architectures.
---

## Overview

- **Goal:** Develop a high-accuracy image classifier for 100 categories using limited training data.
- **Approach:** Apply transfer learning with pretrained deep learning models, along with data augmentation and hyperparameter tuning to improve generalization.
- **Environment:** Implemented in Google Colab using Python, PyTorch, and TorchVision with GPU acceleration.
- **Deliverables:** Final trained model, performance evaluation, and a Kaggle-formatted submission.csv file, with all results and methodology documented in the project report.

---

## Dataset

The dataset used in this project is the **[Transfer Learning Final Project](https://www.kaggle.com/competitions/ucsc-cse-144-winter-2025-final-project/data)**

The dataset is **not included in this repository** due to size and licensing constraints.

## Dataset Structure

```text
train/
 ├─ 0/
 ├─ 1/
 ...
 ├─ 99/
test/
 ├─ 0.jpg
 ├─ 1.jpg
 ...
 ├─ 999.jpg
sample_submission.csv
```

## Notes

- 100 labeled classes, ~10 images per class
- 1000 unlabeled images for inference
- Images resized to **224×224**
- Class label order **must not change** (label `n` → class `n`)

