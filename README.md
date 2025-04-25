## Overview

This workspace is built around the [OCS2](https://github.com/leggedrobotics/ocs2) framework, which provides tools for optimal control and simulation. It includes additional packages for terrain mapping, robotic simulation, and visualization.

## Installation

### Prerequisites
- ROS1
- CMake (>= 3.5)
- Python 3.x
- GPU with CUDA (for elevation mapping)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ocs2_ws.git
   cd ocs2_ws
   ```
2. Install dependencies:
   ```bash
   rosdep install --from-paths src --ignore-src -r -y
   ```
3. Build the workspace:
   ```bash
   catkin build
   ```
4. Source the workspace:
   ```bash
   source devel/setup.bash
   ```
For execution instructions please refer to https://github.com/atecup/atec2025_hardware_design
