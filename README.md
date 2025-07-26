# GeoSatellite Road Extraction using Patch-Based Deep Learning

This repository presents a deep learning pipeline for road segmentation from geo-satellite imagery. Leveraging patch-based processing and custom U-Net architectures (including U-Net, a separate variant, and U-Net++), the model efficiently detects road networks from high-resolution satellite images.

Designed to run seamlessly on Google Colab with Google Drive integration for data handling.

---

## Key Features

- **Patchify-Based Preprocessing**  
  Large satellite images are split into smaller, manageable patches using `patchify` for efficient training and improved generalization.

- **Custom U-Net Architectures**  
  Includes multiple encoder-decoder models (U-Net, U-Net++, custom variants) built with `TensorFlow/Keras` optimized for semantic segmentation.

- **Robust Training Pipeline**  
  - Data splitting and normalization powered by `scikit-learn`  
  - Integrated callbacks like `EarlyStopping` and `ModelCheckpoint` for stability and convergence

- **Visualization Tools**  
  Compare original images, ground truth, and predicted masks using clean `matplotlib` visualizations.

- **Adaptable Architecture**  
  Easily extendable to other binary segmentation tasks such as buildings, water bodies, etc.

---

## Tech Stack

- **Language:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** OpenCV, NumPy, Scikit-learn, Matplotlib, Patchify

---
