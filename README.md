# 😊 Face Emotion Detection Using Deep Learning

## 📌 Overview
This project implements **Facial Expression Recognition (FER)** using **deep learning models** to detect human emotions from images and real-time video feeds. The goal is to classify facial expressions into six categories: **Happy, Sad, Fear, Surprise, Anger, and Neutral**.

## 🏆 Key Features
- **Real-time face emotion detection** using deep learning.
- **Multiple CNN architectures tested** (AlexNet, InceptionV3, MobileNet, VGG16, Deep CNN).
- **Trained on the FER2013 dataset** with **data augmentation**.
- **Evaluated performance using accuracy & loss metrics**.

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **OpenCV** (for real-time face detection)
- **Streamlit** (for web-based deployment)

## 📂 Dataset
- **Dataset:** [FER2013](https://www.kaggle.com/msambare/fer2013)
- **Training Split:** 75% Training, 12.5% Validation, 12.5% Testing
- **Classes:** Happy, Sad, Fear, Surprise, Anger, Neutral, Disgust (Limited)

## 📊 Model Performance
| Model       | Training Accuracy | Validation Accuracy |
|------------|-----------------|------------------|
| **AlexNet** | 99.28% | 62.81% |
| **AlexNet2** | 81.67% | 66.07% |
| **InceptionV3** | 43.47% | 49.90% |
| **MobileNet** | 67.02% | 38.50% |
| **VGG16** | 99.27% | 41.54% |
| **Deep CNN** | **80.34%** | **68.28%** |

✅ **Best performing models:** **Deep CNN & AlexNet2**.

## 🏗️ Model Architecture
1. **CNN-based Models**
   - Convolutional Layers with **ReLU Activation**
   - Batch Normalization & Dropout (to prevent overfitting)
   - Fully Connected Layers & **Softmax Classifier**
2. **Transfer Learning**
   - Pretrained **AlexNet, InceptionV3, VGG16, MobileNet** models.
   - Fine-tuned for emotion classification.

## 🔍 Methodology
1. **Preprocessing**: Face detection, grayscale conversion, image resizing.
2. **Data Augmentation**: Rotation, flipping, zooming to improve generalization.
3. **Training & Validation**: Multiple CNN models trained & evaluated.
4. **Performance Metrics**: Accuracy, Loss, Confusion Matrix.
5. **Hyperparameter Tuning**: Learning rate, dropout, optimizer selection.

