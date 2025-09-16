# Cat vs Dog Classification

A deep learning project that classifies images as either a **Cat** or a **Dog** using Convolutional Neural Networks (CNNs).

---

## 📖 Overview
This project uses the Kaggle **Cats vs Dogs dataset** and trains a CNN model with TensorFlow/Keras.  
The model learns to identify whether an input image is of a **cat** 🐱 or a **dog** 🐶.

---

## ✨ Features
- Preprocesses images (resizing, normalization).  
- Trains a CNN from scratch using TensorFlow/Keras.  
- Evaluates accuracy on training and validation sets.  
- Predicts unseen images and labels them as Cat or Dog.  
- Visualizes training progress (loss & accuracy plots).  

---

## ⚙️ Project Flow
1. **Data Preparation**  
   - Load and preprocess dataset (resize, normalize).  

2. **Model Building**  
   - Create a CNN with convolution, pooling, and dense layers.  

3. **Training**  
   - Compile the model (Adam optimizer, binary crossentropy).  
   - Train on training data with validation split.  

4. **Evaluation**  
   - Plot training/validation accuracy and loss.  
   - Test model performance.  

5. **Prediction**  
   - Predict new images (cat or dog).  

---

## 🛠️ Requirements
1.python>=3.8
2.tensorflow
3.keras
4.numpy
5.pandas
6.matplotlib
7.seaborn


