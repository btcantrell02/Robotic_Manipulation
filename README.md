# Robotic_Manipulation

- Individually developed an RL algorithm for controlling a robot to accomplish grasping task.
- Utilized Stable Baslines3 and Pybullet for implementation and simulation.
- Modified environment settings and reward function for optimal performance.
- Prepared a comprehensive report detailing project objectives, methodologies, results, and discussions. 

# Learning Dexterous Robotic Manipulation (Ver 1.0)

This project focuses on developing a reinforcement learning (RL) algorithm to control a robot to accomplish a pick and place task. The project involves setting up a robotic simulation environment, modifying the environment for task-specific requirements, and training an RL model to perform the manipulation task.

## Installation
### Prerequisites
- Python 3.6+
- Virtual environment (recommended)

### Steps

1. Clone the repository:

`git clone https://github.com/btcantrell02/Robotic-Manipulation.git`

`cd Robotic-Manipulation`

2. Set up the virtual environment:

`python -m venv venv`

`source venv/bin/activate # On Windows use venv\Scripts\activate`

3. Install required libraries:

`pip install stable-baselines3 pybullet`

### Usage
1. Test the environment:
`python test.py`

You should see a robot and an object in the environment. Use the top 3 toolbar controls to manipulate the robot arm.

2. Evaluate the model:
`python evaluate.py`

The success rate of the task will be displayed in the terminal
