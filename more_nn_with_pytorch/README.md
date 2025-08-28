# more Neural Network with Pytorch

In this project, we implemented a neural network using the PyTorch library on the CHEST-MNIST dataset. This dataset is
multi-label with 14 classes. A key challenge is that it is highly imbalanced—some diseases occur very rarely, meaning
most labels are inactive for the majority of patients. We split the dataset into training, validation, and test sets,
and tuned the number of epochs and hidden layers based on validation loss. While the training and validation losses
reached acceptable values, the scikit-learn evaluation metrics did not perform well due to the class imbalance and the
large number of inactive labels.


## requirements
[python](https://www.python.org/downloads/)

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install torch
pip install scikit-learn
pip install matplotlib
pip install medmnist
```

## how to run
To run this Jupyter Notebook, you can either open it in Google Colab using the link below or run it locally using Jupyter Notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/farinazzarei/nn_projects/more_nn_with_torch/blob/main/nn_with_torch.ipynb)

Install Jupyter Notebook (if you don't have it yet):

```bash
pip install notebook
```
clone this repository :
```bash
git clone https://github.com/farinazzarei/nn_projects.git
cd nn_projects/more_nn_with_pytorch
```
Launch Jupyter Notebook:
```bash
jupyter notebook
```
open the notebook file in your browser 
