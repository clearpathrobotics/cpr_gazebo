^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_agriculture_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.2.3 (2022-07-27)
------------------
* Merge pull request `#18 <https://github.com/clearpathrobotics/cpr_gazebo/issues/18>`_ from clearpathrobotics/world_position
  Allow changing the world position
* Add world\_{x|y|z|yaw} arguments and rename x|y|z|yaw to robot\_{x|y|z|yaw} so we can reposition the world if desired.
* Contributors: Chris Iverach-Brereton

0.2.2 (2022-07-25)
------------------

0.2.1 (2022-05-11)
------------------

0.2.0 (2022-05-11)
------------------
* Add boxer, remove moose and heron.
* Squashed commit of real-world-coords branch.  Add real-world coordinates to all worlds, including elevation
* Merge pull request `#17 <https://github.com/clearpathrobotics/cpr_gazebo/issues/17>`_ from clearpathrobotics/orchard
  Add the Orchard world, change maintainership since Dave left.
* Update the author and maintainer tags
* Add the orchard world, as well as a top-level README for the repo
* Merge pull request `#6 <https://github.com/clearpathrobotics/cpr_gazebo/issues/6>`_ from clearpathrobotics/RPSW-510
  Physics and Geometry Fixes
* Added default friction to all collisions
* Hard-coded region
* Launch stack (`#5 <https://github.com/clearpathrobotics/cpr_gazebo/issues/5>`_)
  * Added links.  Button formatting still needs work
  * Updated office launches
* Merge pull request `#4 <https://github.com/clearpathrobotics/cpr_gazebo/issues/4>`_ from clearpathrobotics/dingo
  Add Dingo support to the office world
* Fix the launch parameter documentation to include the yaw property. Add the full list of supported platforms to the office world's docs
* Add license files to the docs, add documentation for the race modules
* Add yaw spawn parameters for heron & moose
* Merge branch 'master' of github.com:clearpathrobotics/cpr_gazebo
* Add the ability to specify the robot's initial yaw position
* Merge pull request `#1 <https://github.com/clearpathrobotics/cpr_gazebo/issues/1>`_ from civerachb-cpr/heron
  Add support for the Heron in the Inspection World
* Update the docs to include the additional platforms & launch parameters
* Merge branch 'moose' into heron
* Add clouds & blue sky to the agriculture environment
* Add Moose spawns for the larger outdoor environments, remove Heron from the dependencies for the agriculture world since it doesn't feature water
* Merge branch 'master' into heron
* Docs
* Added environment variables for selecting platform.  Makes AWS setup easier
* Added installs in cmake
* This repo is getting giant.  Added an agricultural world with a solar farm and an open space for area coverage
* Contributors: Chris Iverach-Brereton, Dave Niewinski, Tony Baltovski
