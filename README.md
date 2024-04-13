# UCSB F1TENTH Capstone Project 2024-25
## Code Template

This repository serves as a template that shows how your ROS code should be structured. This is an example of a catkin workspace.

This is what your file system should look like on the Jetson:
```
your_workspace_name/  # This folder is called the root of your "catkin workspace"
|    build/
|    |
|    devel/
|    |
|    src/ # contains all your packages
|    |    simulator_package/
|    |    |
|    |    |
|    |    lidar_package/
|    |    |
|    |    |
|    |    vesc_package/
|    |    |
|    |    |
|    |    CMakeLists.txt # compiles your code
```
The "build" folder, "devel" folder, and "CMakeLists.txt" are automatically created when you type "catkin_make" in the directory of your workspace. They are used for compiling your code.
