# Dental Classification for KYC

This project focuses on automating dental image classification to improve Know Your Customer (KYC) verification processes using advanced Machine Learning techniques.  
By leveraging deep learning models, dental records can be quickly and accurately categorized, reducing manual verification time and human error.

---

## 🔥 Problem Statement
In traditional KYC processes, dental image analysis is time-consuming, subjective, and prone to inconsistencies.  
The goal is to automate dental classification for faster, more reliable KYC verification and healthcare diagnostics.

---

## 🚀 Solution Overview
- Developed an end-to-end machine learning pipeline using **YOLOv9** object detection.
- Enhanced the classification precision by **20%** through **data augmentation** and **hyperparameter tuning**.
- Automated detection and categorization of dental images into predefined classes with improved accuracy.

---

## 🛠 Tech Stack
- **Programming Language**: Python
- **Frameworks**: PyTorch, OpenCV
- **Model**: YOLOv9 (You Only Look Once - Version 9)
- **Tools Used**: Google Colab / Jupyter Notebook, TensorBoard for visualization

---

## 🧠 Approach
1. **Dataset Collection**:
   - Collected dental X-ray images and clinical photographs.
   - Organized into multiple categories: normal, cavities, braces, missing teeth, etc.

2. **Data Preprocessing**:
   - Image resizing, normalization, and annotation.
   - Augmented dataset with rotations, flips, contrast adjustments to expand training set.

3. **Model Training**:
   - Initialized YOLOv9 model with pre-trained weights.
   - Fine-tuned the model on custom dental dataset.
   - Hyperparameters tuned: learning rate, batch size, IoU threshold, confidence threshold.

4. **Evaluation**:
   - Achieved improved mAP (mean Average Precision) score.
   - 20% improvement in classification precision compared to base model.

5. **Deployment Plan**:
   - Exported trained model to ONNX format for integration into real-time KYC systems.
   - API-based model inference for easy scaling.

---

## 📈 Results
- **Detection Accuracy**: Improved significantly through model tuning.
- **Classification Precision**: +20% after optimizations.
- **Inference Speed**: Real-time dental classification possible (< 100ms per image).

---

## 🚀 Future Enhancements
- Integrate the model into mobile/web-based KYC verification apps.
- Expand dataset for better generalization across age groups and dental conditions.
- Add real-time anomaly detection (missing teeth, infections, implants).

---

## 🤝 Contributions
- Designed and trained YOLOv9 custom model for dental classification.
- Implemented end-to-end ML workflow from preprocessing to evaluation.
- Documented the solution for scalability and integration.

---

## 📬 Contact
For any queries or collaboration opportunities:  
📧 **rjoe67580@gmail.com**  
📍 Chennai, Tamil Nadu, India

---
