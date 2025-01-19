# Fully Connected Neural Networks in PyTorch

This repository contains a Jupyter Notebook that serves as a companion to the Medium article titled "Building Fully Connected Neural Networks with PyTorch". The notebook provides a hands-on guide to implementing, training, and evaluating a simple fully connected neural network (FCNN) using the PyTorch library.

## Overview

The notebook covers the following key topics:

1. **Data Collection and Preprocessing**:
   - Download and extract the MNIST dataset.
   - Load and preprocess the data for training and testing.

2. **Custom Dataset Creation**:
   - Implement a custom PyTorch `Dataset` class for the MNIST data.
   - Apply data transformations and augmentations.

3. **Model Architecture**:
   - Define a simple fully connected neural network using PyTorch's `nn.Module`.
   - Explore improvements with batch normalization and dropout layers.

4. **Training and Evaluation**:
   - Implement training loops with modular functions for training epochs and model evaluation.
   - Use techniques like learning rate scheduling and model checkpointing.

5. **Reproducibility**:
   - Set a consistent random seed to ensure reproducibility of results.
   - Compare different model configurations and training strategies.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- PyTorch
- NumPy
- Matplotlib

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ericfflynn/fcnn.git
   cd fcnn
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `Notebook.ipynb` to explore the code and run the cells.

## Usage

- **Data Preparation**: The notebook automatically downloads and prepares the MNIST dataset.
- **Model Training**: Follow the step-by-step instructions to train the FCNN model.
- **Experimentation**: Modify the model architecture, hyperparameters, and training strategies to see their impact on performance.

## Results

- The notebook demonstrates how to achieve high accuracy on the MNIST dataset using a simple FCNN.
- It provides insights into the effects of different model improvements and training techniques.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## Acknowledgments

- The PyTorch community for their excellent documentation and resources.
- The creators of the MNIST dataset.