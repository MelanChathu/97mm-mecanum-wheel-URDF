# 97mm-mecanum-wheel-URDF
 This repository contains the URDF model and RViz2 display launch files for 97mm diameter 9 rollers Mecanum wheels. It is designed for use with ROS 2 (Humble) and can be easily integrated into simulation or visualization workflows.

 This URDF includes a basic model of  ecanum wheels as shown below.
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/5fa8b89e-f9af-4e81-ba7d-94c321aee49a" />

# For Visualization

```bash
# Build the workspace
colcon build --packages-select mecanum_description
```
```bash
# Source the workspace
source install/setup.bash
```
```bash
# Launch URDF in RViz2
ros2 launch mecanum_description display.launch.py
```
# Examples
<img width="1854" height="1053" alt="Screenshot from 2025-07-23 20-24-28" src="https://github.com/user-attachments/assets/f98124d1-8718-480c-93d6-dcba47053679" />

<img width="1854" height="1053" alt="Screenshot from 2025-07-23 20-24-59" src="https://github.com/user-attachments/assets/57edb635-1f0e-43c2-9392-1d368be8ed17" />
