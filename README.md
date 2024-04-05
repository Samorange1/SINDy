# SINDy

Authors: [Aditya Paranjape](https://github.com/adityaaap) and [Madhav Rawal](https://github.com/Samorange1)

Implementation of the SINDy autoencoder for learning dynamics of planar pushing task




https://github.com/Samorange1/SINDy/assets/71136335/41b6d818-f5ad-45f2-aa45-11d34053100a



This repository contains the code for using the SINDy (Sparse Identification of Nonlinear Dynamics) model to accomplish a planar pushing task. The SINDy model is a custom deep autoencoder network designed to discover a reduced coordinate system where the dynamics are sparsely represented. This approach enables simultaneous learning of governing equations and associated coordinate systems, leveraging the strengths of deep neural networks and sparse identification of nonlinear dynamics.

## Introduction

The goal of this project is to apply the SINDy model to a planar pushing task using a manipulator. We collect data of the manipulator's behavior in a simulation environment and pass it through the SINDy Autoencoder to discover the underlying dynamics and predict future states. The SINDy model offers a comprehensive analysis, exploring different hyperparameters, dynamics methods, and a comparison with the Embed to Control (E2C) model.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository:
```
git clone https://github.com/Samorange1/SINDy.git
```

2. Install the necessary dependencies. Make sure you have Python 3.x and pip installed. Then, run the following command: 
```
./install.sh
```
3. Run the demo script to see the trained SINDy model push the block in place with a franka panda manipulator.
```
python demo.py
```


## Documentation

For detailed documentation on the project, including explanations of the SINDy model, data collection process, and training procedure, please refer to the [Project Report](https://github.com/Samorange1/SINDy/blob/main/Project%20Report.pdf) file.

## Acknowledgments

We would like to acknowledge Dr. Dimitry Berenson and Dr. Nima Fazeli for assisting us in this project and the following resources that inspired and assisted in the development of this project:
- [Paper: Sparse Identification of Nonlinear Dynamics for Model-Based Control](https://arxiv.org/abs/1603.00370)





