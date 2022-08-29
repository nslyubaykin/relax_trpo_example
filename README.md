# Example TRPO implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_trpo_example/blob/master/trpo_example.ipynb) of trust region policy optimization (TRPO) with ReLAx.

TRPO actor was trained on HalfCheetah-v2 Mujoco Gym environment for 4m env-steps. 

The graph of average return vs training step is shown below (`batch_size=40000`):

![trpo_training](https://github.com/nslyubaykin/relax_trpo_example/blob/master/trpo_training.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187159100-7e10ec0c-faba-47d3-afcf-e0e64630411f.mp4
