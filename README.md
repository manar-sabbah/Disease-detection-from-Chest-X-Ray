## Disease Detection from Chest X-Ray using Deep Learning


## 📦 Dataset

- **Source**: [Chest X-Ray Images (Pneumonia) – Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)



## 🛠️ Project Steps

### 1. 📊 Data Exploration

- Visualized random X-ray images from both classes.
- Examined class distribution to confirm dataset imbalance (more PNEUMONIA cases than NORMAL).

### 2. 🧹 Data Preprocessing

- Resized all images to **224x224** for consistency and compatibility with pretrained models.
- Normalized pixel values to the range [0, 1].
- Applied data augmentation on the training set:
  - Random horizontal flips
  - Random rotations
  - Zoom transformations


### 3. 🧠 Model Building

#### ✅ First Model: Custom CNN 


#### ✅ Second Model: Transfer Learning 
  - Pretrained models using `MobileNetV2`
  -

- Frozen base layers + custom classifier head
- Fine-tuned top layers for better performance

### 4. 📈 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**
