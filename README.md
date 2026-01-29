# Fashion MNIST Image Classification Using Artificial Neural Network (ANN)

## Overview
This project focuses on classifying fashion product images using an **Artificial Neural Network (ANN)**.  
The model is trained and evaluated on the **Fashion MNIST dataset**, which contains grayscale images of clothing items.

The notebook demonstrates the complete workflow of building a neural network for image classification using deep learning.

---

## Dataset
The **Fashion MNIST dataset** is a standard benchmark dataset consisting of:

- 70,000 grayscale images
- Image size: 28 × 28 pixels
- 10 clothing categories

### Classes
- T-shirt/Top  
- Trouser  
- Pullover  
- Dress  
- Coat  
- Sandal  
- Shirt  
- Sneaker  
- Bag  
- Ankle Boot  

The dataset is divided into:
- 60,000 training images  
- 10,000 testing images  

---

## Model Used
**Artificial Neural Network (ANN)**

### Model Characteristics
- Fully connected (Dense) layers  
- Input layer receives flattened image data  
- Hidden layers learn feature representations  
- Output layer uses softmax activation for multi-class classification  

This model does not use convolutional layers and relies on dense connections for learning patterns.

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab  

---

## Project Workflow
1. Import required libraries  
2. Load Fashion MNIST dataset  
3. Normalize image pixel values  
4. Flatten image data  
5. Build ANN model using Dense layers  
6. Compile the model  
7. Train the model on training data  
8. Evaluate performance on test data  
9. Visualize accuracy and loss  

---

## Results
- The ANN model successfully classifies fashion images into 10 categories  
- Training and validation accuracy are analyzed  
- Loss and accuracy plots help evaluate model performance  

---

## How to Run
1. Open the notebook in Jupyter Notebook or Google Colab  
2. Run all cells sequentially  
3. Required libraries will be imported automatically  
4. Dataset loads directly from Keras  

---

## File Description
- `Fashion_MNIST.ipynb` – Contains the full implementation of the ANN model  

---

## Conclusion
This project demonstrates how an **Artificial Neural Network** can be used for image classification tasks.  
It serves as a beginner-friendly deep learning project for understanding ANN-based image classification.
