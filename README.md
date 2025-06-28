# Real-or-Fake-image-classifier

A project to classify real and AI-generated (fake) images using transfer learning.

## 🛠 Tools & Technologies
- Python
- MobileNetV2 (pretrained CNN model)
- Pandas, NumPy, Matplotlib
- ImageDataGenerator for augmentation

## 📌 Project Description
The aim was to build a basic image classification model that can differentiate between real and fake (AI-generated) images.

We used the MobileNetV2 architecture with transfer learning for efficient training. The dataset was loaded, preprocessed, and split using TensorFlow utilities. Performance was evaluated using accuracy metrics, confusion matrix, and loss curves.

## 🧪 Features
- Classifies images as **Real** or **Fake**
- Uses pretrained model (MobileNetV2) with fine-tuning
- Image preprocessing and augmentation for better performance
- Performance visualization using plots and confusion matrix
