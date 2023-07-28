# SAC

The SAC package provides an object that can be integrated into different simulation environments.

___

## Installation

### Install dependencies

```
pip3 install torch
pip3 install numpy
```

### Download the repository

```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/PedroCorcaque/sac.git
```

### Build the package

```
cd ~/catkin_ws/
catkin build
```

___

## To use

The `step` function of the environment must be returns `state`, `reward`, `done` and a empty dict.

- State: the next state of the environment
- Reward: the reward received in the iteration
- Done: a boolean to indicate the end of episode
