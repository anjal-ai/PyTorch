# PyTorch Learning

A collection of Jupyter notebooks for learning PyTorch fundamentals and building neural networks.

## Contents

This repository contains the following tutorials:

1. **01_tensor_in_pytorch.ipynb** - Introduction to PyTorch tensors
2. **02_pytorch_autograd.ipynb** - Understanding automatic differentiation
3. **03_pytorch_training_pipeline.ipynb** - Building a basic training pipeline
4. **04_pytorch_nn_module.ipynb** - Working with PyTorch's nn.Module
5. **05_pytorch_training_pipeline_using_nn_module.ipynb** - Training with nn.Module
6. **06_dataset_and_dataloader_demo.ipynb** - Using Dataset and DataLoader
7. **07_ann_fashion_mnist_pytorch.ipynb** - Fashion-MNIST classification with ANN
8. **08_ann_fashion_mnist_pytorch_in_gpu.ipynb** - GPU-accelerated training

## Setup

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/anjal-ai/PyTorch.git
cd PyTorch
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

### Running the Notebooks

You can run the notebooks using Jupyter:

```bash
jupyter notebook
```

Or open them directly in Google Colab using the "Open in Colab" badge at the top of each notebook.

## Requirements

- torch>=2.0.0
- torchvision>=0.15.0
- numpy>=1.24.0
- pandas>=2.0.0
- matplotlib>=3.7.0
- scikit-learn>=1.3.0
- torchinfo>=1.8.0

## GPU Support

Some notebooks (particularly `08_ann_fashion_mnist_pytorch_in_gpu.ipynb`) demonstrate GPU acceleration. You'll need:
- NVIDIA GPU with CUDA support
- Appropriate CUDA toolkit installed
- PyTorch with CUDA support

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Feel free to open issues or submit pull requests if you find any bugs or have suggestions for improvements.
