# Learning-based drone control with (recurrent) neural networks

Use these repositories to train a drone control policy in simulation and deploy it to a real *CrazyFlie 2.1* drone.

Contents:
- **phoenix-drone-simulation** Contains a PyBullet based simulator and a PPO implementation in PyTorch which can be used with recurrent neural networks
- **crazyflie-fw-neural-ctrl** Source code for the execution of neural network based controllers on the *CrazyFlie*'s microcontroller
- **crazyflie-clients-python** Tools for flashing the binary onto the microcontroller and uploading neural network weights to the drone
