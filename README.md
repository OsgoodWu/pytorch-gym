# DDPG in bullet Gym using pytorch
## Overview
This is an implementation of Deep Deterministic Policy Gradient (DDPG) in bullet Gym using PyTorch.
## Dependencies
* Python 3.6
* PyTorch 0.3.0
* openAI gym
* pybullet

## Run
* here is a simple example to train CartPole with high efficiency:
> $ python main.py --debug --discrete --env=CartPole-v0 --vis
* **you can using this to understand usage of each argument:**
> $ python main.py --help

* some explanation of important arguments:
> --debug: print the reward and some other information
>
> --discrete: if the actions are discrete rather than continuous
>
> --vis: render each action (but it would slow down your training speed) 
>
> --cuda: train this task using GPU
>
> —test: testing mode
>
> —resume <file pash>: load model from the path

## Contributors

- [MemphiSqrt](https://github.com/MemphiSqrt)
- [hzwer](https://github.com/hzwer)
- [KuribohG](https://github.com/KuribohG)