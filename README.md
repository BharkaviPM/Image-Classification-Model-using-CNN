# Image-Classification-Model-using-CNN
Using ML and Python

---

**INTERN ID:** CT04DK897  
**DOMAIN:** MACHINE LEARNING  
**DURATION:** 4 WEEKS (30th APR - 30th MAY)  
**MENTOR:** NEELA SANTHOSH  

---

## **Motivation**

The motivation behind this project is to gain hands-on experience with deep learning models, particularly **Convolutional Neural Networks (CNNs)**. This task involves building a multiclass image classification model to predict one of four classes: **Chair**, **Kitchen**, **Knife**, and **Saucepan**. The project provides practical insight into how CNNs learn spatial hierarchies and perform well on visual data, using a robust architecture like **AlexNet** for accurate classification.

---

## **Tools and Technologies**

- **Python:** Core programming language  
- **PyTorch:** Deep learning framework for model building and training  
- **Matplotlib:** Plotting and visualizations  
- **Pandas & NumPy:** Data handling and numerical operations  
- **PIL:** Image preprocessing  
- **VS Code:** Development environment  

---

## **Dataset**

The dataset consists of **5200 labeled training images** and **1267 test images** across 4 categories:  
- **Chair**  
- **Kitchen**  
- **Knife**  
- **Saucepan**  

Each class in the training set contains **1300 images**. The dataset was preprocessed and stored in `.npy` format for efficient loading.

---

## **Model Architecture**

The model uses the **AlexNet** architecture:  
- 5 Convolutional Layers  
- 3 Fully Connected Layers  
- Dropout (0.5) for regularization  
- ReLU activation functions  
- Total Parameters: ~60 million  

---

## **Implementation Steps**

1. **Data Preparation**  
   - Load `.npy` data files  
   - Normalize and preprocess images  
   - Split into train, validation, and test sets  

2. **Model Definition**  
   - Build CNN using PyTorch with AlexNet architecture  

3. **Training Loop**  
   - Train for multiple epochs  
   - Log training and validation loss  

4. **Evaluation**  
   - Plot Accuracy, Loss, and AUC on validation data  
   - Generate predictions for test data  

5. **Visualization**  
   - Display predicted class labels on sample test images  

---

## **Conclusion**

This project successfully implements a CNN-based multiclass image classifier using PyTorch. With an architecture inspired by **AlexNet**, the model achieves promising accuracy (~87%) after just a few epochs. The visualization of predictions and performance metrics demonstrates the model's ability to generalize and effectively distinguish between object categories. This forms a strong base for further experimentation in deep learning and computer vision.

---

## **Output**

---

