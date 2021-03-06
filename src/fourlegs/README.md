# fourlegs  

This sample shows a quadruped robot model.  
In this sample, you can find a motionable quadruped model with a plugin "libQuadrupedMotion.so" and a source file as "src/QuadrupedMotion.cc" and "Motion.cc".  
There is a world file as "worlds/fourlegs.world" to show a quadruped robot model.  

## How to run.  
You can run this sample by using a following command.  

    $ roslaunch fourlegs spawn_fourlegs.launch  

Or you can run this sample by using a following command instead of using roslaunch.  

    $ gazebo ~/Samples_Gazebo_ROS/src/fourlegs/worlds/fourlegs.world  
    
You can see an usage for operating the fourlegs robot on the terminal you started this repository.  

## Model and plugin.  
This package uses following model.  

|Model Name|Plugin(Program) Filename(s)|
|---|---|
|[fourlegs](https://github.com/m-shimizu/Samples_Gazebo_ROS/tree/master/models/fourlegs)|QuadrupedMotion.cc<br>Motion.cc|

|Program file|Description|
|---|---|
|QuadrupedMotion.cc|The plugin program.|
|Motion.cc|A program for generating leg motion.|

Date : 2 Feb. 2018
