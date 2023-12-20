# DTU 02465 - Deep Learning project - Group 18.1
## Implementing, understanding and analysis of conditional flow matching

### Introduction:
	
Flow matching is a method for training continuous normalizing flow models. It is a method that circumvents the limitations of diffusion models by adopting a simulation-free approach. This allows for training in a broader range of possibility paths and expand on diffusion. We will be studying two methods of probability density path, diffusion (variance preserving) and optimal transport.

### Problem formulation:
The objective of this project is to compare the performance between Diffusion (Variance preserving) and Optimal Transport (OT) when using flow matching for generating images using the same hyperparameters. This comparison will mainly be done by comparing the Fréchet inception distance (FID), the time used for each model, and how effective they are during some selective steps.  Furthermore, a discussion will also be made upon the used time for each model, and how effective they are during some selective steps.

### Methods:
This project draws inspiration from pioneering works in conditional flow matching and data generation:
- “Flow Matching for Generative Modeling” by Yaron Lipman et al.
- “Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow” by Xingchao Liu et al.
- “Building Normalizing Flows with Stochastic Interpolants” by Michael S. Albergo and Eric Vanden-Eijnden.
- “Improving and Generalizing Flow-Based Generative Models with Minibatch Optimal Transport” by Alexander Tong et al. 

These papers provide a comprehensive understanding of time-varying probability paths, vector fields, and flow matching techniques. The emphasis is on understanding the principles and applications of conditional flow matching for data generation, as detailed in these works.

### References:
- “Flow Matching for Generative Modeling” by Yaron Lipman et al. [Paper](https://openreview.net/forum?id=PqvMRDCJT9t)
- “Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow” by Xingchao Liu et al. [Paper](https://arxiv.org/abs/2209.03003) 
- “Building Normalizing Flows with Stochastic Interpolants” by Michael S. Albergo and Eric Vanden-Eijnden. [Paper](https://openreview.net/forum?id=li7qeBbCR1t)
- “Improving and Generalizing Flow-Based Generative Models with Minibatch Optimal Transport” by Alexander Tong et al.  [Paper](https://arxiv.org/abs/2302.00482)
