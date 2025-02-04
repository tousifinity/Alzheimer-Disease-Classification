# 🧠 Alzheimer Disease Classification with MRI Dataset

This project focuses on **Alzheimer's disease classification** using deep learning models trained on the **Alzheimer MRI dataset**. The models implemented include **MobileNetV2, EfficientNetB2, Xception, VGG16, VGG19, and SqueezeNet**.

---

## 📂 Dataset
The **Alzheimer MRI dataset** contains MRI scans categorized into four stages of Alzheimer's disease. These images are used to train deep learning models to classify and detect Alzheimer's at various severity levels.

🔗 **Dataset Source:** [Alzheimer MRI Disease Classification Dataset](https://www.kaggle.com/datasets/borhanitrash/alzheimer-mri-disease-classification-dataset)

---

## 🧠 Implemented Deep Learning Models
The following models have been used for Alzheimer’s disease classification:

- ✅ **MobileNetV2** – Lightweight and optimized for mobile devices  
- ✅ **EfficientNetB2** – Scalable and high-accuracy model  
- ✅ **Xception** – Advanced convolutional network with depthwise separable convolutions  
- ✅ **VGG16** – Classical deep CNN for image classification  
- ✅ **VGG19** – Extended version of VGG16 with more layers  
- ✅ **SqueezeNet** – Lightweight CNN with fewer parameters  

Each model has been evaluated based on accuracy, loss, and performance metrics.

---

## 🚀 Project Workflow
1. **Data Preprocessing**  
   - Image resizing, normalization, and augmentation  
   - Train-test split for model evaluation  

2. **Model Training**  
   - Implementing Transfer Learning  
   - Fine-tuning models on the Alzheimer MRI dataset  

3. **Evaluation & Metrics**  
   - Accuracy, Loss, Precision, Recall, F1-Score  

4. **Prediction & Deployment**  
   - Making predictions on unseen MRI scans  

---

## 📊 Results & Performance
| Model           | Accuracy (%) |
|----------------|-------------|
| MobileNetV2    | 90.87%       |
| EfficientNetB2 | 98.69%       |
| Xception       | 98.62%       |
| VGG16          | 77.54%       |
| VGG19          | 77.39%       |
| SqueezeNet     | 74.06%       |