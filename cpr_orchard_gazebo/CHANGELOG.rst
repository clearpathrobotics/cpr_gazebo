^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_orchard_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
* Move the origin to an orchard in Greece, add the datum script, add top-down tif + geotagged tif images, add the base station model near the origin
* Add axes to the default world view
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
* Add the install directive to the orchard world
* Contributors: Chris Iverach-Brereton

0.2.1 (2022-05-11)
------------------

0.2.0 (2022-05-11)
------------------
* Squashed commit of real-world-coords branch.  Add real-world coordinates to all worlds, including elevation
* Merge pull request `#17 <https://github.com/clearpathrobotics/cpr_gazebo/issues/17>`_ from clearpathrobotics/orchard
  Add the Orchard world, change maintainership since Dave left.
* Update the author and maintainer tags
* Add the orchard world, as well as a top-level README for the repo
* Contributors: Chris Iverach-Brereton, Tony Baltovski
