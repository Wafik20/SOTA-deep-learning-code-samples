# SOTA Deep Learning Code Samples

This repository contains **hands-on implementations of influential deep learning papers and architectures**.  
The goal is to build intuition by **implementing core ideas from scratch and visualizing their behavior**.

Each notebook focuses on a specific model family or research idea and includes experiments and visualizations.

---

# Notebooks

## Neural ODEs Unlocked

Notebook:  
https://github.com/Wafik20/SOTA-deep-learning-code-samples/blob/main/Neural_ODEs_Unlocked.ipynb

Paper:  
**Neural Ordinary Differential Equations**  
https://arxiv.org/abs/1806.07366

Summary:

This notebook implements the core ideas from the Neural ODE paper and explores how neural networks can be interpreted as continuous dynamical systems.

Topics covered:

- Residual networks as discretized differential equations
- Continuous-depth models
- ODE solvers in PyTorch using `torchdiffeq`
- Implementing an `ODEBlock`
- Training a Neural ODE classifier on the two-moons dataset
- Visualizing decision boundaries and learned flows

The notebook also walks through the **adjoint method for memory-efficient backpropagation through ODE solvers**.

---

## Visualizing Where Optimal Transport-based Loss Functions Fall Short

Notebook:  
https://github.com/Wafik20/SOTA-deep-learning-code-samples/blob/main/pemdiv_visualization.ipynb

Summary:

This notebook explores limitations of **Optimal Transport based objectives** when used as loss functions for generative modeling.

Topics explored:

- Wasserstein distance behavior in high dimensions
- Sinkhorn divergence
- Visualization of transport couplings
- Empirical examples where OT-based losses fail to capture meaningful structure
- Geometric intuition for why OT losses can produce unintuitive gradients

The goal is to better understand **why OT-based objectives are not always ideal for training neural networks**, despite their attractive theoretical properties.

---

## Generating MNIST Using Diffusion

Notebook:  
https://github.com/Wafik20/SOTA-deep-learning-code-samples/blob/main/Generating_MNIST_Using_Diffusion.ipynb

Related papers:

**Denoising Diffusion Probabilistic Models**  
https://arxiv.org/abs/2006.11239

**Score-Based Generative Modeling through Stochastic Differential Equations**  
https://arxiv.org/abs/2011.13456

Summary:

This notebook implements a minimal diffusion model for generating MNIST digits.

Topics covered:

- Forward diffusion process
- Noise schedules
- Training the denoising network
- Reverse diffusion sampling
- Generating images from pure noise

The notebook focuses on building intuition for how diffusion models generate samples.

---

## Mastering Sequential Models

Notebook:  
https://github.com/Wafik20/SOTA-deep-learning-code-samples/blob/main/mastering_sequential_models.ipynb

Summary:

This notebook explores classical sequence modeling architectures as a foundation for more modern models.

Topics covered:

- Vanilla RNNs
- LSTMs
- GRUs
- Seq2Seq architectures
- Teacher forcing
- Training sequence models in PyTorch

This serves as preparation for implementing more recent sequence models such as **Mamba-style state space models**.

---

# Repository Goals

The purpose of this repository is to:

- Understand modern deep learning models **from first principles**
- Reproduce key ideas from influential papers
- Build **clean minimal implementations**
- Develop intuition through **experiments and visualizations**

---

# License

MIT License
