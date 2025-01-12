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
- Model
- Buffer
- Experiment
- Visualization

The parameters are generally consistent with the original implementation, so these notebooks can be executed with minimal adjustments to produce results similar to the original setup benchmark (atleast on HalfCheetah-v4)

## Requirements
Requirements are minimal: 

- **Python** `3.8.20` (+ `itertools`, `copy`)
- **Torch** `2.4.1`
- **Scipy** `1.10.1`
- **Gymnasium** `0.29.1`
- **Numpy** `1.24.3`
- **Pillow** `10.4.0`

## Example GIFs (visualized after 250,000 TotalEnvInteracts)
**vpg**
<img src="gifs/vpg.gif" alt="vpg GIF" width="200"/>

**ppo**
<img src="gifs/ppo.gif" alt="ppo GIF" width="200"/>

**dpg**
<img src="gifs/dpg.gif" alt="dpg GIF" width="200"/>

**td3**
<img src="gifs/td3.gif" alt="td3 GIF" width="200"/>

**sac**
<img src="gifs/sac.gif" alt="sac GIF" width="200"/>


| Algorithm | GIF |
|-----------|-----|
| **VPG**   | <img src="gifs/vpg.gif" alt="vpg GIF" width="200"/> |
| **PPO**   | <img src="gifs/ppo.gif" alt="ppo GIF" width="200"/> |
| **DPG**   | <img src="gifs/dpg.gif" alt="dpg GIF" width="200"/> |
| **TD3**   | <img src="gifs/td3.gif" alt="td3 GIF" width="200"/> |
| **SAC**   | <img src="gifs/sac.gif" alt="sac GIF" width="200"/> |
