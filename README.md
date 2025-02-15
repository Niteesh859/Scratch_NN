# NN_scratch

## Overview
NN_scratch is an object-oriented implementation of a neural network from scratch using Python and libraries like NumPy, Pandas, and Random. The model is highly customizable, allowing users to define the number of neurons in each layer using a list.

## Features
- Implements a Multi-Layer Perceptron (MLP) from scratch.
- Allows dynamic input of the number of neurons per layer.
- Supports both **Sigmoid** and **ReLU** activation functions.
- Option to enable or disable **Softmax** layer for the output.
- Displays **loss** and **epoch number** to track learning progress.
- Uses a dataset split of **26,000 for training** and **4,000 for testing**.
- Dataset is **normalized** for better performance.

## Files in Repository
- `classification_data1.csv` & `classification_data2.csv`: Training datasets.
- `classification_test.csv`: Test dataset.
- `NNscratch.ipynb`: Jupyter Notebook containing the neural network implementation and training/testing workflow.

## Code Structure
- The MLP class (Multi-Layer Perceptron) is implemented in an object-oriented manner.
- The number of neurons per layer is dynamically set by passing a list.
- Includes forward and backward propagation.
- Uses **random weight initialization** (to be improved in future updates).
- An older version of the MLP class is commented out in the notebook, while the improved version is actively used.

## Future Improvements
- Implement **regularization** techniques to prevent overfitting.
- Improve **weight initialization** (currently, random initialization is used).
- Optimize performance for large datasets.

---
Feel free to contribute or suggest improvements!
