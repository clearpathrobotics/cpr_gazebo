^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_inspection_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.0 (2022-05-11)
------------------
* Re-add the entire pipeline; it looks in a previous revision a good chunk of it was accidentally deleted
* Squashed commit of real-world-coords branch.  Add real-world coordinates to all worlds, including elevation
* Merge pull request `#17 <https://github.com/clearpathrobotics/cpr_gazebo/issues/17>`_ from clearpathrobotics/orchard
  Add the Orchard world, change maintainership since Dave left.
* Update the author and maintainer tags
* Add the orchard world, as well as a top-level README for the repo
* Merge pull request `#6 <https://github.com/clearpathrobotics/cpr_gazebo/issues/6>`_ from clearpathrobotics/RPSW-510
  Physics and Geometry Fixes
* Removed water urdf stuff and bonus water mesh i had accidentally added
* Added default friction to all collisions
* Added blocks to bridge ends for smaller platforms
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
* Add the Heron image to the list of platforms
* Update the readme to include supported platforms, add the water physics & associated image
* Add Moose spawns for the larger outdoor environments, remove Heron from the dependencies for the agriculture world since it doesn't feature water
* Merge branch 'master' into heron
* Fix a typo
* Add a comment to the heron-spawner to explain why it's ignoring the X and Y arguments
* Overhaul the Inspection world so that it uses the water physics from UUV, add the ability to spawn a Heron
* Docs
* Added environment variables for selecting platform.  Makes AWS setup easier
* Added installs in cmake
* A lot more complete
* Renamed gazebo_race_modules to cpr_race_modules.  Added office and inspections worlds.  New worlds still need clutter added
* Contributors: Chris Iverach-Brereton, Dave Niewinski, Tony Baltovski
