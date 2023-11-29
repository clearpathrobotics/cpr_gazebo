^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_inspection_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.2.8 (2023-11-29)
------------------

0.2.7 (2023-01-16)
------------------
* Fix a typo in almost every readme, add the new empty world with support for all platforms
* Contributors: Chris Iverach-Brereton

0.2.6 (2023-01-09)
------------------

0.2.5 (2022-12-02)
------------------
* Merge pull request `#19 <https://github.com/clearpathrobotics/cpr_gazebo/issues/19>`_ from mhosmar-cpr/gzweb
  Add Gzweb Support
* add missing newlines
* Add model.config to install target
* Add GZweb support
* Contributors: Chris Iverach-Brereton, Michael Hosmar

0.2.4 (2022-11-29)
------------------
* Adjust the orchard and inspection worlds to use ENU coordinates for the world frame. Fix the robot spawn points, GPS base-station locations, and default camera orientations accordingly
* Update the datum scripts to use the new envars
* Increase the scale of the water table model to match the world
* Add the base station object on the shore of the lake
* Increase the horizontal scale of the world to make the hill proportionally shallower. Re-tag the geotif with updated coordiantes
* Add geotagged tif of the inspection world, move the origin to be vaguely representative of a lake in northern Alberta
* Add the rviz directory to the install targets
* Add a new accessories package with the charge dock and base station. Add view_world.launch files to all relevant packages so you can view the environment without spinning up Gazebo. Add the wireless charge dock and base station to the agriculture world
* Contributors: Chris Iverach-Brereton

0.2.3 (2022-07-27)
------------------
* Merge pull request `#18 <https://github.com/clearpathrobotics/cpr_gazebo/issues/18>`_ from clearpathrobotics/world_position
  Allow changing the world position
* Add world\_{x|y|z|yaw} arguments and rename x|y|z|yaw to robot\_{x|y|z|yaw} so we can reposition the world if desired.
* Contributors: Chris Iverach-Brereton

0.2.2 (2022-07-25)
------------------
* Add the water mesh to the visualization since UUV is disabled. This way the water at least renders, even if it doesn't have any physics
* Contributors: Chris Iverach-Brereton

0.2.1 (2022-05-11)
------------------
* Disable the water physics; UUV does not appear to be released for Noetic yet. Will re-enable later if possible
* Contributors: Chris Iverach-Brereton

0.2.0 (2022-05-11)
------------------
* Re-add the entire pipeline; it looks in a previous revision a good chunk of it was accidentally deleted
* Add boxer, remove moose and heron.
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
