# Handwritten Digit Classification using TensorFlow and MNIST

This project demonstrates a deep learning model built using TensorFlow and Keras to classify handwritten digits from the MNIST dataset. It follows the complete machine learning workflow, including data preprocessing, model building, training, evaluation, and result visualization.

## Overview

- Dataset: MNIST (60,000 training and 10,000 testing images of digits 0–9)
- Framework: TensorFlow 2.x with Keras
- Task: Multi-class classification
- Model: Fully connected feedforward neural network

## Model Architecture

- Input Layer: 28x28 grayscale image (flattened to 784)
- Hidden Layer: Dense layer with 512 units and ReLU activation
- Output Layer: Dense layer with 10 units and softmax activation
- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam
- Metric: Accuracy
- Callback: EarlyStopping (training stops at 98% accuracy)

## Getting Started

1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

2. Install dependencies

```
pip install tensorflow matplotlib seaborn
```

3. Run the notebook

Open the file `Handwritten_Digit_classification_using_tf_and_mnist_datset.ipynb` using Jupyter Notebook or Google Colab.

## Results

- Achieves over 98% accuracy within a few epochs
- Includes confusion matrix and sample prediction visualization
- Plots training history for loss and accuracy

## Files

- `Handwritten_Digit_classification_using_tf_and_mnist_datset.ipynb`: Main notebook
- `README.md`: Project documentation

## Requirements

- Python 3.7+
- TensorFlow 2.x
- Matplotlib
- Seaborn

## License

This project is licensed under the MIT License.

