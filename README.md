## 🧠 Project 1: Brain Stroke Severity Detection

### 🎯 Objective
Segment stroke-affected regions from MRI brain images to support early diagnosis and intervention planning.

### 🧪 Methodology
- **Model**: U-Net with Multihead Attention in skip connections.
- **Data Preprocessing**: Image normalization, resizing, augmentation.
- **Loss Function**: Dice Loss + Binary Crossentropy.
- **Evaluation Metrics**: Dice Score, IoU, and segmentation mask visualization.
- **Training Framework**: TensorFlow with GPU acceleration.

### ✅ Performance
- **Test Accuracy**: **99%**
- **Outcome**: Highly precise segmentation masks; attention improved focus on lesion regions.

---

## 🧠 Project 2: Brain Tumor Classification

### 🎯 Objective
Classify MRI images into **Tumor** and **Healthy** categories using a deep CNN model with regional attention enhancement.

### 🧪 Methodology
- **Dataset**: 5000 labeled MRI images (Tumor: 3000, Healthy: 2000).
- **Preprocessing**:
  - Resize to 224x224
  - Label encoding and class balancing using `RandomOverSampler`
- **Model**:
  - Custom ResNet + Area Attention Layer
  - Optimizer: Adam | Loss: Binary Crossentropy
- **Training Setup**: 10 epochs, batch size 16

### ✅ Performance
- **Validation Accuracy**: **87%**
- **Evaluation**: Confusion matrix, classification report, training/validation plots
- **Result**: Attention layer enhanced regional learning and boosted classification accuracy.

---

