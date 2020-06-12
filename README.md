# About
This repository contains a notebook with implementations of the VAE, IWAE and the VR-alpha and VR-max algorithms. 
The VR-alpha and VR-max algorithms were introduced in the paper Rényi Divergence Variational Inference [[1]](https://arxiv.org/pdf/1602.02311.pdf). 
The code can be used without any set up by importing the notebook `code.ipynb` into Google Colab. (Simply create a new Google Colab notebook and
choose to import a new notebook from GitHub.) This allows using the implementation
with the MNIST and FashionMNIST datasets which will be automatically downloaded upon first running the code.

# Further context
The implementation is based on the [basic example of a VAE](https://github.com/pytorch/examples/blob/master/vae/main.py) from the PyTorch library.
It was then extended to also support the IWAE and the VR-alpha and the VR-max algorithms.
This implementation was developed for the replication challenge of the 
[Advanced Machine Learning course HT2020](https://www.cs.ox.ac.uk/teaching/internal/courses/2019-2020/advml/material.html).
The code made available here allows rerunning the VAE experiments on the MNIST and FashionMNIST dataset.
It was developed in conjunction with Evan Neill. 

The complete replication of the paper was a group effort by four people. 
We have summarized our experiments and results in this poster:
 ![Renyi Poster](https://github.com/arnegebert/vae-iwae-vralpha/blob/master/poster.jpg)
 

