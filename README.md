# 🧠 Scene Classification: MyCNN vs AlexNet (Transfer Learning)
## 👤 Author
**Ramalah Amir**  

## 📌 Project Overview

This mini project focused on building a deep learning model that classifies images of **natural scenes** into **6 categories** using the [Intel Scene Classification Dataset](https://www.kaggle.com/datasets/nitishabharathi/scene-classification).

The main goal was to:
- Understand how a **scratch-built CNN** performs.
- Compare it to a **pretrained AlexNet** using **transfer learning**.
- Visualize and analyze their performance using **confusion matrices** and **accuracy/loss plots**.

---

## 🛠 Models Used

### 🔸 MyCNN (from scratch)
- Implemented using PyTorch.
- Simple architecture with convolutional layers and pooling.
- Achieved ~**82–83% accuracy** on the test set.
- First time building a CNN from scratch in PyTorch!

### 🔹 AlexNet (Transfer Learning)
- Used pretrained weights from ImageNet.
- Only the **last layer was changed** to fit our 6-class classification task.
- Achieved ~**90–91% accuracy**.
- Much better performance thanks to pretrained features.

Reference used to understand AlexNet:  
📚 [AlexNet PyTorch Notebook by madsendennis](https://github.com/madsendennis/notebooks)

---

## 🧪 Dataset

- **Intel Image Classification Dataset**  
  [Kaggle Link](https://www.kaggle.com/datasets/nitishabharathi/scene-classification)
- 6 classes: `buildings`, `forest`, `glacier`, `mountain`, `sea`, `street`
- Train and test sets were already provided.

---

## 📊 Evaluation & Results

- Plotted **training loss** and **validation accuracy** for both models.
- Generated **confusion matrices** to see class-wise performance.
- Class-wise accuracy:
  - **MyCNN**: Above 80% in all classes ✅
  - **AlexNet**: Above 90% in all classes ✅

---

## 🗂 Pretrained Models

You can download the trained model states here:

- 🔗 [Trained Model States – Google Drive](https://drive.google.com/drive/folders/1jgTKLdn2ZqgwTuHtleWUEU_v2qdCyAIc?usp=sharing)

---

## 🧠 What I Learned

- How to build and train a CNN from scratch using PyTorch.
- How pretrained models like AlexNet can speed up and improve accuracy with limited training.
- How to compare model performance using metrics beyond accuracy.
- Basics of data augmentation, overfitting, and transfer learning.




