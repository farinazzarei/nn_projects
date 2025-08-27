# Neural Network with Pytorch

In this project, we implemented a simple neural network using the PyTorch library on the Fashion-MNIST dataset. We split
the dataset into training, validation, and test sets, and tuned the number of epochs and hidden layers based on validation
loss and accuracy. Finally, we compared the performance of four different optimizers: Adam, RMSprop, SGD, and Adagrad.
Adam performed better than the others because it adapts the learning rate for each parameter using estimates of first
and second moments of past gradients, which stabilizes and accelerates training


## requirements
[python](https://www.python.org/downloads/)

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install torch
pip install scikit-learn
pip install matplotlib
pip install seaborn
```

## how to run
To run this Jupyter Notebook, you can either open it in Google Colab using the link below or run it locally using Jupyter Notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/farinazzarei/NN_with_torch/blob/main/nn_with_torch.ipynb)

Install Jupyter Notebook (if you don't have it yet):

```bash
pip install notebook
```
clone this repository :
```bash
git https://github.com/farinazzarei/NN_with_torch.git
cd NN_with_torch
```
Launch Jupyter Notebook:
```bash
jupyter notebook
```
open the notebook file in your browser 
