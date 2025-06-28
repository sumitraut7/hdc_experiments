# HDC-MNIST-FHRR-Classification

This repository contains the Jupyter Notebook code for a Hyperdimensional Computing (HDC) experiment focusing on MNIST digit classification. The project specifically implements **Fourier Holographic Reduced Representations (FHRR)** for encoding and explores two distinct learning paradigms:

1.  **Single-Pass Fit:** A highly efficient method for initial class hypervector generation by bundling encoded training data.
2.  **Iterative Learning:** An adaptive approach that refines class hypervectors over multiple epochs by reinforcing correct classifications and correcting misclassifications.

## Project Overview

This project provides a practical example of applying brain-inspired computing principles to a classic machine learning task. It showcases how high-dimensional vectors (hypervectors) can represent and process information for classification.

## Key Features

* Implementation of FHRR encoding for real-valued data (MNIST images).
* Functions for core HDC operations (similarity measurement, basis generation, feature encoding).
* Demonstration of MNIST classification using a single-pass associative memory, ideal for quick initial models.
* An iterative learning loop to incrementally improve model accuracy by adjusting class hypervectors based on classification errors.
* Visualization of classification results, including accuracy plots over epochs and confusion matrices, to assess model performance.

## Getting Started

To run the experiments in this repository:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/HDC-MNIST-FHRR-Classification.git](https://github.com/YourUsername/HDC-MNIST-FHRR-Classification.git)
    cd HDC-MNIST-FHRR-Classification
    ```
    *(Remember to replace `YourUsername` with your actual GitHub username and the repository name if it's different.)*

2.  **Install dependencies:**
    Ensure you have Python installed. You can install the necessary libraries using pip:
    ```bash
    pip install numpy matplotlib scikit-learn torchvision torch
    ```

3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook "MNIST using hypervectors.ipynb"
    ```
    Follow the steps in the notebook to execute the code and reproduce the results.

## Contributing

Feel free to open issues or submit pull requests if you have suggestions, improvements, or bug fixes.
