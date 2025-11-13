# Assignment-12-Neural-Network-and-Deep-Learning-Basics
Applying neural networks to solve a practical problem in image classification. 

This repository contains the implementation of Assignment 12: Neural Network and Deep Learning Basics.  
The project focuses on building, training, and evaluating a feedforward neural network using the Fashion MNIST dataset.

---

## 📘 Project Overview
The goal of this project is to:
- Load and preprocess the Fashion MNIST dataset  
- Build a neural network using TensorFlow/Keras  
- Train the model and visualize learning curves  
- Evaluate performance using metrics and a confusion matrix  
- Demonstrate a real-world application scenario  
- Provide documentation and a final report  

---

## 🧠 Model Architecture
The neural network includes:
- Dense (256 units, ReLU)  
- Dropout (0.3)  
- Dense (128 units, ReLU)  
- Output Dense (10 units, Softmax)  

Optimizer: **Adam**  
Loss: **Sparse Categorical Crossentropy**  
Metrics: **Accuracy**  

---

## 📂 Files Included
```
├── notebook.ipynb
├── Neural_Network_Report.pdf
├── Neural_Network_Report.docx
├── README.md
```

---

## 📊 Results
Model evaluation included:
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- Training/Validation Loss & Accuracy Curves  

The model performed well on the Fashion MNIST dataset.

---

## 🚀 Real-World Application
A potential use case is:
### **Automated Clothing Classification for Retail Inventory**
This model can:
- Categorize fashion items automatically  
- Reduce manual tagging errors  
- Speed up digital catalog creation  
- Improve search recommendations  

---

## ⚙ Requirements
Install necessary libraries:

```bash
pip install tensorflow numpy pandas matplotlib seaborn
```

---

## 📄 Author
**Raïssa Matho Mekjele**  
Business Intelligence & Data Analytics Student  
Willis College, Ottawa  
2025
