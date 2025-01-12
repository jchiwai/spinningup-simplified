# Spinning Up in Deep RL (Simplified)
A streamlined implementation of [Spinning Up](https://spinningup.openai.com/en/latest/) using Pytorch (CPU) that retains the core reinforcement learning algorithms while removing logging functionalities and MPI dependencies. ***Also works on Windows!***

## Algorithms
- Vanilla Policy Gradient
- Proximal Policy Optimization
- Deep Deterministic Policy Gradient
- Twin Delayed Deep Deterministic Policy Gradient
- Soft Actor-Critic

## Usage
Each algorithm is contained within its own Jupyter Notebook. The notebooks are structured as follows:
- Imports
- Helper functions
- Model Classes
- Buffer
- Experiment
- Visualisation

We use mostly the same parameters as the original implementation, so these notebooks can be run with minimal adjustments to yield results comparable to the original setup.

## Requirements
Requirements are minimal: 

- **Python** `3.8.20` (+ `itertools`, `copy`)
- **Torch** `2.4.1`
- **Scipy** `1.10.1`
- **Gymnasium** `0.29.1`
- **Numpy** `1.24.3`
- **Pillow** `10.4.0`

## Example GIFs

