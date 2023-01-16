# cpr_empty_gazebo

A planar world with minimal features

## Supported Platforms

### Husky
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/husky.jpg" width="20%">

### Jackal
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/jackal.jpg" width="20%">

### Warthog
<img src="https://s3.amazonaws.com/assets.clearpathrobotics.com/wp-content/uploads/2016/08/25085714/warthog-menu.jpg" width="20%">

### Dingo
<img src="https://s3.amazonaws.com/assets.clearpathrobotics.com/wp-content/uploads/2019/11/04142259/dingo-menu-1.png" width="20%">

### Boxer
<img src="https://clearpathrobotics.com/assets/renders/Boxer_VR.283/Boxer_VR.283/0_9.jpg" width="20%">

### Ridgeback
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/06/ridgeback.jpg" width="20%">

## Launching

```roslaunch cpr_empty_gazebo empty_world.launch```

Optionally, you can specify a platform using the platform variable:

```roslaunch cpr_empty_gazebo empty_world.launch platform:=jackal```

Supported values for the platform variable are:
* husky (default)
* jackal
* warthog
* boxer
* dingo
* ridgeback

The spawn location for the robot can be specified by setting the `x`, `y`, `z`, and `yaw` variables.  The Z value should be set
to be above ground-level; otherwise the robot may fall through the ground plane as the environment renders.

## Features

This is an intentionally featureless world.  The ground plane is 1km square with a single Clearpath Robotics base
station located at `(50, 50)`.  There are otherwise no features in the world by design.
