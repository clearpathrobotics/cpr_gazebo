# cpr_agriculture_gazebo

Outdoor agricultural simulation world for Gazebo

## Supported Platrofms

### Husky
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/husky.jpg" width="20%">

[![Launch Stack](launch-stack.png)](
https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-agriculture-gazebo&param_SimWorld=cpr_agriculture_gazebo&param_SimLaunch=agriculture_world.launch&param_RoboticPlatform=husky)

### Jackal
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/jackal.jpg" width="20%">

[![Launch Stack](launch-stack.png)](
https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-agriculture-gazebo&param_SimWorld=cpr_agriculture_gazebo&param_SimLaunch=agriculture_world.launch&param_RoboticPlatform=jackal)

### Warthog
<img src="https://s3.amazonaws.com/assets.clearpathrobotics.com/wp-content/uploads/2016/08/25085714/warthog-menu.jpg" width="20%">

[![Launch Stack](launch-stack.png)](
https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-agriculture-gazebo&param_SimWorld=cpr_agriculture_gazebo&param_SimLaunch=agriculture_world.launch&param_RoboticPlatform=warthog)

### Moose
<img src="https://clearpathrobotics.com/assets/renders/Moose-KS_VR.274/Moose-KS_VR.274/0_9.jpg" width="20%">

[![Launch Stack](launch-stack.png)](
https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-agriculture-gazebo&param_SimWorld=cpr_agriculture_gazebo&param_SimLaunch=agriculture_world.launch&param_RoboticPlatform=moose)

## Launching

```roslaunch cpr_agriculture_gazebo agriculture_world.launch```

Optionally, you can specify a platform using the platform variable:

```roslaunch cpr_agriculture_gazebo agriculture_world.launch platform:=jackal```

Supported values for the platform variable are:
* husky (default)
* jackal
* warthog
* moose

The spawn location for the robot can be specified by setting the `x`, `y`, `z`, and `yaw` variables.  The Z value should be set
to be above ground-level; otherwise the robot may fall through the ground plane as the environment renders.

## Features

This is a large, open outdoor world for Gazebo that has:

### Barn

<img src="img2.png">

### Large area for area-coverage

<img src="img1.png">

### Solar Farm

<img src="img3.png">
