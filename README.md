# **Day 01: Neural Network for MNIST Classification**

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

## **Code and Notebook**
The implementation of the neural network is available in the Jupyter Notebook file:  
[Neural_Networks.ipynb](./Neural_Networks.ipynb).
You can open this notebook in **Google Colab** for interactive execution.

---

## **Results**
The notebook contains visualizations, including:
- **Loss Plot**: Displays the reduction in loss over training epochs.
- **Test Predictions**: Visualizes sample predictions from the test set.

These visualizations can be dynamically generated by running the notebook.

---

## **How to Run the Notebook**
### **Steps to Open in Google Colab**
1. Go to [Google Colab](https://colab.research.google.com/).
2. Click on **File > Open Notebook**.
3. Choose the **GitHub tab** and paste the repository URL:

4. Open the `neural_network_mnist.ipynb` file and start running the cells.

### **Learning Outcomes**
- Learned the basics of neural networks and their components.  
- Implemented and trained a simple neural network using PyTorch.  
- Visualized model performance through loss plots and predictions.  

---

### **Future Improvements**
- Incorporate a Convolutional Neural Network (CNN) for better accuracy.  
- Experiment with hyperparameter tuning (e.g., learning rate, batch size).  
- Apply data augmentation to improve generalization.  


### **Contributors**
Teja Gopal Reddy Vaka - Aspiring to become a top 1% AI professional.
