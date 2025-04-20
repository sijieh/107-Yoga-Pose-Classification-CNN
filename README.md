# 🧘‍♀️ Yoga Pose Classification (107 Classes)

This project builds a deep learning model to classify **107 unique yoga poses** from image data using Convolutional Neural Networks (CNNs). Designed for potential deployment in a fitness mobile app, the model helps users identify their yoga poses from real-time images and offers feedback on posture recognition.

---

## 🎯 Project Objective

To train a deep learning image classifier capable of recognizing 107 yoga poses with high accuracy, and optimize it for mobile deployment using model quantization.

---

## 🧰 Technologies Used

- **Frameworks:** TensorFlow, Keras
- **Model Types:** Custom CNN, Transfer Learning
- **Optimization:** Batch Normalization, Dropout, L2 Regularization
- **Training Tools:** EarlyStopping, ReduceLROnPlateau, TensorBoard
- **Deployment Ready:** TensorFlow Lite (TFLite) quantization

---

## 🧪 Workflow Summary

- 📁 Loaded data from 107-class yoga dataset (train/val/test folders)
- 📊 Performed EDA, normalization, and data augmentation
- 🧠 Built and trained a custom CNN with regularization techniques
- 📉 Tracked model convergence and compared architectures using TensorBoard
- 📈 Evaluated with accuracy, F1 score, and confusion matrix
- ⚙️ Quantized the final model using TFLite for mobile deployment

---

## 📊 Model Performance

- Best test accuracy: **~59%**
- F1 score: **~0.58**
- Model quantization reduced size by **~75%** with minimal accuracy loss
