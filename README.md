# Neural Network from Scratch

A complete neural network framework implemented from scratch using NumPy for educational purposes, without using high-level frameworks like TensorFlow or PyTorch.

## Features Implemented

### Core Components
- **Dense Layers**: Fully connected layers with forward/backward propagation
- **Activation Functions**: ReLU, Sigmoid, SoftMax
- **Loss Functions**: Cross-entropy loss
- **Optimizers**: SGD and Adam

### Advanced Features  
- **Dropout Layer**: Regularization to prevent overfitting
- **Batch Normalization**: Training stabilization
- **Early Stopping**: Automatic training termination
- **Model Persistence**: Save/load trained models

### Training Infrastructure
- Complete training loop with validation
- Performance metrics (accuracy, F1-score)
- Visualization (training curves, confusion matrix)
- Automatic hyperparameter experimentation

## Dataset Used
**Fashion-MNIST**: 70,000 grayscale images of clothing items (10 classes)
- T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot
