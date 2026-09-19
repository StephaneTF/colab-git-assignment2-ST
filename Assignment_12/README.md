# Assignment 12 – Neural Network and Deep Learning Basics

## CIFAR-10 Image Classification Using a Neural Network

A Google Colab assignment that classifies images into ten categories using a feedforward neural network.

## Dataset and Workflow

- Dataset: CIFAR-10, with 50,000 training and 10,000 test images.
- Normalize pixels to 0–1 and preview optional data augmentation.
- Use two ReLU hidden layers (256 and 128 units) and a Softmax output layer.
- Train with Adam and categorical crossentropy, using separate validation data.
- Evaluate with accuracy, precision, recall, F1-score, and a confusion matrix.
- Discuss digital photo organization as a potential application.

## Results

Test accuracy: **47.65%**. Weighted precision: **47.00%**, recall: **47.65%**, and F1-score: **46.81%**.

Additional architecture, optimizer, and augmentation comparisons remain future work.

## Tools and Usage

Python, TensorFlow/Keras, NumPy, Matplotlib, and scikit-learn. Open the notebook in Google Colab and run the cells in order. CIFAR-10 downloads automatically.
