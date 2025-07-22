# GeoSatellite-Road-Extraction-using-Patch-Based-Deep-Learning
This repository presents a deep learning pipeline for road segmentation from geo-satellite imagery. Leveraging patch-based processing and a custom U-Net architecture(also has a seperate Unet architecture , Unet++ architecture), the model efficiently learns to detect road networks from high-resolution satellite images. Designed to run on Google Colab with integration to Google Drive.
Key Features
->Patchify-Based Preprocessing: Large satellite images are split into smaller, manageable patches using patchify for efficient model training and better generalization.
->Custom U-Net Architecture: A powerful convolutional encoder-decoder network built with Keras layers, optimized for semantic segmentation tasks like road extraction.
->Robust Training Pipeline:
  Scikit-learn-powered data splitting and normalization
->Keras callbacks: EarlyStopping and ModelCheckpoint for stable and early convergence
->Visualization Tools: Compare original, ground truth, and predicted road masks using clear matplotlib outputs.
-> Flexible for Deployment: Adaptable to other binary segmentation tasks (e.g., buildings, rivers, etc.)
Tech Stack
Python, TensorFlow/Keras,OpenCV, NumPy, Patchify,Matplotlib, Scikit-learn
