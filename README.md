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
|    |    pathing_package/
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
The "build" folder, "devel" folder, and "CMakeLists.txt" are automatically created when you type "catkin_make" in the root directory of your workspace. These folders are used for compiling your code.

For the template, I have copied the f1tenth_simulator package into the "pathing_package" folder. Note that the name of the folder does not determine the name of the package---look in the package.xml file to see the name of a given package. In the simulator, the simulator.cpp node reads and writes data to topics that simulate the functionality of the lidar and the vesc. While your car is being built, we recommend you familiarize yourself with using the f1tenth_simulator package. This entails launching the package, operating the simulator in RVIZ, and modifying the .cpp node files to implement a simple autonomous algorithm. To do this we recommend you follow the F1TENTH website documentation to write a custom wall follow algorithm, which uses PID control to maintain a constant distance from a wall as the car drives forward.




