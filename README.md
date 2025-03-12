# Car Classification using CNNs 🚗

This project focuses on fine-grained car classification using the **Stanford Cars Dataset**, leveraging Convolutional Neural Networks (CNNs) and advanced training techniques to improve model performance.

## 📂 Dataset Overview
- **Total Training Images:** 8144  
- **Total Test Images:** 8040  
- **Unique Classes:** 196 (different car models)  
- **Image Format:** High-resolution RGB images with bounding boxes  
- **Preprocessing:** Cropped and resized to 224x224  
- **Augmentation:**  
  - Random rotations and flips  
  - Color adjustments (brightness, contrast, hue)  

## 🧠 Models & Techniques
We experimented with multiple architectures and optimization strategies:
- **CNN Architectures:**  
  - ResNet-50: **81.71% Test Accuracy**  
  - VGG-16: **55.03% Test Accuracy**  
  - DenseNet-121: **79.08% Test Accuracy**  
  - EfficientNet: **77.1% Test Accuracy**  

- **Optimization Techniques:**  
  - Learning Rate Scheduler: Improved test accuracy to **23.7%** in early experiments  
  - Gradient Clipping: Helped stabilize training and reduced overfitting  
  - Inference-Time Augmentation: Boosted test accuracy to **23.7%**  
  - Feature Extraction + Random Forest: **23.39% Test Accuracy**  

## ⏳ Results & Insights
- **Best Model:** ResNet-50 with **81.71% Test Accuracy**  
- **Training Time:** Between 22-35 minutes per model  
- **Challenges:**  
  - Imbalance in class samples (min: 24, max: 68)  
  - Computational limitations for deeper architectures  
  - Fine-grained classification required careful tuning of augmentation and hyperparameters  

## 🚀 Future Improvements
- Implementing a hierarchical CNN for stage-wise feature extraction  
- Using more powerful GPUs to train larger models  
- Exploring Vision Transformers (ViT) for enhanced performance  

## 📝 Authors
- Eyal Shubeli
- Nadav Toledo  
