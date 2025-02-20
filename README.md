# Dummy Robot Description Package

## Installation

1. Set up ROS2 environment (recommended Humble distribution)
2. Create workspace and clone repository:
```bash
mkdir -p ~/ros2_ws/src
cd ~/ros2_ws/src
git clone https://github.com/aod321/dummy_robot_description.git
```

## Build Instructions
```bash
cd ~/ros2_ws
colcon build
source install/setup.bash  # Use setup.zsh if using zsh
```

## Usage

### RViz Visualization
```bash
ros2 launch dummy_robot_description display.launch.py
```

### Gazebo Simulation
```bash
ros2 launch dummy_robot_description gazebo.launch.py
```

## Additional Notes
- For Windows/macOS users:  
  Recommended to use Anaconda/Mambaforge with Robostack environment:  
  [Robostack Getting Started Guide](https://robostack.github.io/GettingStarted.html)  
  Install ROS2 Humble distribution for best compatibility

