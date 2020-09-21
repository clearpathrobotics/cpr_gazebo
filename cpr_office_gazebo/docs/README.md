# cpr_office_gazebo

Indoor office simulation world for Gazebo including both completed and under-construction versions

## Supported Platrofms

### Jackal
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/jackal.jpg" width="20%">

Office | Office Construction
------ | -------------------
<a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_world.launch&param_RoboticPlatform=jackal"><img src="launch-stack.png"></a> | <a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-construction-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_construction_world.launch&param_RoboticPlatform=jackal"><img src="launch-stack.png"></a>

### Husky
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/husky.jpg" width="20%">

Office | Office Construction
------ | -------------------
<a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_world.launch&param_RoboticPlatform=husky"><img src="launch-stack.png"></a> | <a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-construction-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_construction_world.launch&param_RoboticPlatform=husky"><img src="launch-stack.png"></a>

### Ridgeback
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/06/ridgeback.jpg" width="20%">

Office | Office Construction
------ | -------------------
<a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_world.launch&param_RoboticPlatform=ridgeback"><img src="launch-stack.png"></a> | <a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-construction-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_construction_world.launch&param_RoboticPlatform=ridgeback"><img src="launch-stack.png"></a>

### Dingo
<img src="https://s3.amazonaws.com/assets.clearpathrobotics.com/wp-content/uploads/2019/11/04142259/dingo-menu-1.png" width="20%">

Office | Office Construction
------ | -------------------
<a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_world.launch&param_RoboticPlatform=dingo"><img src="launch-stack.png"></a> | <a href="https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?region=us-east-2&templateURL=https://cpr-gazebo-public.s3.us-east-2.amazonaws.com/CPR-Kinetic-Simulation-Stack.yaml&stackName=cpr-office-construction-gazebo&param_SimWorld=cpr_office_gazebo&param_SimLaunch=office_construction_world.launch&param_RoboticPlatform=dingo"><img src="launch-stack.png"></a>

## Complete Launching

```roslaunch cpr_office_gazebo office_world.launch```

Optionally, you can specify a platform using the platform variable:

```roslaunch cpr_office_gazebo office_world.launch platform:=jackal```

Supported values for the platform variable are:
* husky (default)
* jackal
* ridgeback
* dingo

The spawn location for the robot can be specified by setting the `x`, `y`, `z`, and `yaw` variables.  The Z value should be set
to be above ground-level; otherwise the robot may fall through the ground plane as the environment renders.

## Features of the complete office world

### Large, open areas
<img src="img6.png">

### Narrow hallways
<img src="img4.png">

### Meeting rooms & offices
<img src="img5.png">

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

## Features of the construction world

### Incomplete walls
<img src="img2.png">

### Different ground textures
<img src="img3.png">

### Construction-oriented debris & obstacles
<img src="img1.png">
