# Neural-Network-from-Scratch

A simple feedforward neural network built with just Python and NumPy to classify handwritten digits from the MNIST dataset. No machine learning libraries used.

Features:- 
Manual implementation of ReLU, Softmax, forward/backward pass, and gradient descent
Achieves ~88% test accuracy
Includes one-hot encoding and data preprocessing
Built for learning, not libraries

How to Run
1. Clone the repo  
2. Install dependencies: `pip install numpy pandas matplotlib`  
3. Download `train.csv` from [Kaggle](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv)  

Architecture
Input: 784 nodes (28×28 image)
Hidden: 10 neurons (ReLU)
Output: 10 classes (Softmax)
