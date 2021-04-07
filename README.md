# Pytorch

PyTorch is an open source machine learning library based on the Torch library,used for applications such as computer vision and natural language processing, primarily developed by Facebook's AI Research lab (FAIR). It is free and open-source software released under the Modified BSD license. Although the Python interface is more polished and the primary focus of development, PyTorch also has a C++ interface.

A number of pieces of deep learning software are built on top of PyTorch, including Tesla Autopilot, Uber's Pyro, HuggingFace's Transformers, PyTorch Lightning, and Catalyst.

PyTorch provides two high-level features:
Tensor computing (like NumPy) with strong acceleration via graphics processing units (GPU)
Deep neural networks built on a type-based automatic differentiation system

---

**What is PyTorch?**

Let’s understand what PyTorch is and why it has become so popular lately, before diving into it’s implementation.

PyTorch is a Python-based scientific computing package that is similar to NumPy, but with the added power of GPUs. It is also a deep learning framework that provides maximum flexibility and speed during implementing and building deep neural network architectures.

Recently, PyTorch 1.0 was released and it was aimed to assist researchers by addressing four major challenges:

- Extensive reworking
- Time-consuming training
- Python programming language inflexibility
- Slow scale-up

Intrinsically, there are two main characteristics of PyTorch that distinguish it from other deep learning frameworks like Tensorflow:

- Imperative Programming
- Dynamic Computation Graphing


**Imperative Programming**: PyTorch performs computations as it goes through each line of the written code. This is quite similar to how a Python program is executed. This concept is called imperative programming. The biggest advantage of this feature is that your code and programming logic can be debugged on the fly.

**Dynamic Computation Graphing:** PyTorch is referred to as a “defined by run” framework, which means that the computational graph structure (of a neural network architecture) is generated during run time. The main advantage of this property is that it provides a flexible and programmatic runtime interface that facilitates the construction and modification of systems by connecting operations. In PyTorch, a new computational graph is defined at each forward pass. This is in stark contrast to TensorFlow which uses a static graph representation.

PyTorch 1.0 comes with an important feature called torch.jit, a high-level compiler that allows the user to separate the models and code. It also supports efficient model optimization on custom hardware, such as GPUs or TPUs

---

Get started : https://pytorch.org/tutorials/beginner/basics/intro.html <br>
CS230 : https://cs230.stanford.edu/blog/pytorch/
