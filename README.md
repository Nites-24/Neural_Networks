# **Neural Network for MNIST Classification**
## **Overview**
This project demonstrates the implementation of a basic **neural network** to classify handwritten digits from the MNIST dataset. It introduces key concepts in deep learning, including:
- Neural network architecture (input, hidden, and output layers).
- Loss functions and activation functions.
- Training and evaluating a model using PyTorch.

---

## **Project Details**
- **Framework**: PyTorch
- **Dataset**: MNIST (handwritten digits)
  - 60,000 training images and 10,000 test images.
  - Each image is grayscale with dimensions 28x28.
- **Architecture**:
  - **Input Layer**: 784 neurons (flattened 28x28 image).
  - **Hidden Layers**:
    - Layer 1: 128 neurons with ReLU activation.
    - Layer 2: 64 neurons with ReLU activation.
  - **Output Layer**: 10 neurons with Softmax activation.

---

## **Results**
### **Loss Plot**
The model's loss consistently decreased over 5 epochs, indicating successful training:
![Loss Plot](loss_plot.png)

### **Test Predictions**
Sample predictions from the test set show the model's accuracy:
![Test Predictions](predictions.png)

---

## **How to Run the Code**
### **Requirements**
- Python 3.7+
- PyTorch
- torchvision
- Matplotlib

### **Steps to Run**
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Day_01_Neural_Networks.git
   cd Day_01_Neural_Networks




