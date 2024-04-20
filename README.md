
---

# Neural Network for MNIST Digit Classification

This repository contains code for training and evaluating a neural network model for digit classification using the MNIST dataset.

## Overview

The neural network architecture consists of:
- Input layer: Flatten layer to reshape the input images into a 1D array
- Hidden layers: Two dense layers with ReLU activation functions
- Output layer: Dense layer with softmax activation function for multi-class classification

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits (0-9). Each image is grayscale and has a resolution of 28x28 pixels.

## Requirements

- Python 3
- TensorFlow 2.x
- Matplotlib

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/neural-network-mnist.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the training script:

    ```bash
    python train.py
    ```

4. Evaluate the trained model:

    ```bash
    python evaluate.py
    ```

## Results

Epoch 1/5
844/844 [==============================] - 16s 14ms/step - loss: 0.2974 - accuracy: 0.9145 - val_loss: 0.1333 - val_accuracy: 0.9605
Epoch 2/5
844/844 [==============================] - 10s 11ms/step - loss: 0.1227 - accuracy: 0.9637 - val_loss: 0.1017 - val_accuracy: 0.9710
Epoch 3/5
844/844 [==============================] - 9s 11ms/step - loss: 0.0841 - accuracy: 0.9740 - val_loss: 0.0894 - val_accuracy: 0.9762
Epoch 4/5
844/844 [==============================] - 9s 11ms/step - loss: 0.0622 - accuracy: 0.9812 - val_loss: 0.0786 - val_accuracy: 0.9788
Epoch 5/5
844/844 [==============================] - 10s 11ms/step - loss: 0.0492 - accuracy: 0.9843 - val_loss: 0.0805 - val_accuracy: 0.9798
313/313 [==============================] - 2s 6ms/step - loss: 0.0784 - accuracy: 0.9760
Test accuracy: 0.9760000109672546
1/1 [==============================] - 0s 406ms/step

![0a5b76ad-d3a2-4a92-a5a1-8ee7d98cec50](https://github.com/Priya-M25/Handwritten-Digit-Recognisation/assets/97019927/411292f0-2615-4ec8-8e86-545c0f7b9b69)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

[Your Name](https://github.com/your_username)

## Acknowledgements

- The MNIST dataset is provided by TensorFlow/Keras.
- The neural network architecture is based on examples from TensorFlow documentation and tutorials.

---

Feel free to customize the README file with additional information specific to your project or preferences.
