# cpr_office_gazebo

Indoor office simulation world for Gazebo including both completed and under construction version

## Supported Platrofms

### Jackal
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/jackal.jpg" width="20%">

### Husky
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/husky.jpg" width="20%">

### Ridgeback
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/06/ridgeback.jpg" width="20%">

### Dingo
<img src="https://s3.amazonaws.com/assets.clearpathrobotics.com/wp-content/uploads/2019/11/04142259/dingo-menu-1.png" width="20%">

## Completed Launching

```roslaunch cpr_office_gazebo office_world.launch```

Optionally, you can specify a platform using the platform variable:

```roslaunch cpr_office_gazebo office_world.launch platform:=jackal```

## Construction Launching

```roslaunch cpr_office_gazebo office_construction_world.launch```

Optionally, you can specify a platform using the platform variable:

```roslaunch cpr_office_gazebo office_construction_world.launch platform:=jackal```

Supported values for the platform variable are:
* husky (default)
* jackal
* ridgeback
* dingo

The spawn location for the robot can be specified by setting the `x`, `y`, `z`, and `yaw` variables.  The Z value should be set
to be above ground-level; otherwise the robot may fall through the ground plane as the environment renders.

## Features

<img src="img1.png">

<img src="img2.png">

<img src="img3.png">

<img src="img4.png">

<img src="img5.png">

<img src="img6.png">
