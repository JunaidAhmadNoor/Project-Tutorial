# Solving Long-Range Dependencies: RNNs vs. Self-Attention

## Project Overview

This repository contains a comprehensive tutorial exploring the long-range dependency problem in sequence modeling. It provides a comparative analysis between traditional Recurrent Neural Networks (RNNs/LSTMs) and the modern Transformer self-attention mechanism.

### Key Learning Objectives

- Understanding the vanishing gradient problem in RNNs.
- The architectural shift from `O(n)` sequential processing to `O(1)` path lengths in self-attention.
- Hands-on implementation of a Copy Task to benchmark model performance.
- Visualizing attention heads to interpret how models "focus" on distant tokens.

## Requirements & Installation

This project is built using Python 3.x and PyTorch. To run the Jupyter Notebook, ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

## How to Use

### Clone the Repository

```bash
git clone https://github.com/JunaidAhmadNoor/ML-Tutorial.git
```

### Run the Tutorial

Open `ML_Tutorial.ipynb` in Jupyter Notebook or Google Colab.


## Accessibility

This project was designed with inclusivity in mind:

- **Colorblind friendly:** All plots use the `cividis` or specific high-contrast palettes to ensure they are readable by users with color vision deficiencies.
- **Readable code:** Follows PEP 8 standards with descriptive variable names.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

