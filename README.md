# buMRC_teleop_control
Run these after pulling the most recent updates
```bash
colcon build --symlink-install
source install/setup.bash
ros2 launch teleop_control launch_sim.launch.py
```