# Learning from Learned Hallucination

This repository contains the implementation of [LfLH](https://www.cs.utexas.edu/~xiao/papers/lflh.pdf) adapted for usage in arena-rosnav platform.    
For more information about LfLH refer to information presented by the authors at UTexas [here](https://www.cs.utexas.edu/~xiao/Research/LfH/LfH.html#lflh) or [here](https://github.com/Daffan/nav-competition-icra2022/tree/LfH)


**Please note** LfLH is appropriate for usage on **only** the [Jackal platform](https://clearpathrobotics.com/jackal-small-unmanned-ground-vehicle/).

# Installation

## Activate poetry shell
```bash
cd arena-rosnav # navigate to the arena-rosnav directory
poetry shell
```
## Make sure to source the workspace environment
```bash
cd ../.. # navigate to the catkin_ws directory
source devel/setup.zsh # if you use bash: source devel/setup.bash 
```
## Install Python dependencies
```bash
roscd LfH
pip install -r requirements.txt
```
