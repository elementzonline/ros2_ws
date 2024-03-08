# Ros2 workspace setup


```
cd ~
git clone ....
```

# Setup VScode

1. Install ros extenstion from Microsoft
2. Install cmake extension


# Setup fish terminal 

```bash
nano ~/.config/fish/config.fish 
```

Add the following content tothe end of the file

```bash
bass source /opt/ros/humble/setup.bash
bass source /home/dhanish/ros_ws/install/setup.bash

```

# Open the ros_ws in vsode

```
cd ~/ros_ws
code .
```


# Test the configuration

```bash
cd ros2_ws
colcon build
```

Open the display.launch.py
Under Run/Debug -> "Python Debugger Launch File"

See if the breakpoint is hit