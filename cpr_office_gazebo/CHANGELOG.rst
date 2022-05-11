^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cpr_office_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.0 (2022-05-11)
------------------
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
* Tidy up the office environment to better-distinguish between the construction & complete worlds
* Fix the launch parameter documentation to include the yaw property. Add the full list of supported platforms to the office world's docs
* Add the Dingo launch file to the office world
* Add license files to the docs, add documentation for the race modules
* Merge branch 'master' of github.com:clearpathrobotics/cpr_gazebo
* Add the ability to specify the robot's initial yaw position
* Merge pull request `#1 <https://github.com/clearpathrobotics/cpr_gazebo/issues/1>`_ from civerachb-cpr/heron
  Add support for the Heron in the Inspection World
* Add clouds to the office world
* Merge branch 'master' into heron
* Docs
* Added ridgeback to office world
* Added environment variables for selecting platform.  Makes AWS setup easier
* Added installs in cmake
* A lot more complete
* Renamed gazebo_race_modules to cpr_race_modules.  Added office and inspections worlds.  New worlds still need clutter added
* Contributors: Chris Iverach-Brereton, Dave Niewinski, Tony Baltovski
