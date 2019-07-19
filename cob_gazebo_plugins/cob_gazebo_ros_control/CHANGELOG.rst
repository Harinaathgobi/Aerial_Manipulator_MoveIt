^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_gazebo_ros_control
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.7.2 (2018-01-07)
------------------
* Merge pull request `#34 <https://github.com/ipa320/cob_gazebo_plugins/issues/34>`_ from ipa320/kinetic_release_candidate
  Kinetic release candidate
* Merge pull request `#32 <https://github.com/ipa320/cob_gazebo_plugins/issues/32>`_ from ipa-fxm/kinetic_dev
  [kinetic] updates from indigo_dev
* Merge branch 'indigo_dev' of github.com:ipa320/cob_gazebo_plugins into kinetic_dev
  Conflicts:
  .travis.yml
* Merge pull request `#31 <https://github.com/ipa320/cob_gazebo_plugins/issues/31>`_ from ipa-fxm/update_maintainer
  update maintainer
* update maintainer
* Merge pull request `#28 <https://github.com/ipa320/cob_gazebo_plugins/issues/28>`_ from ipa-fxm/APACHE_license
  use license apache 2.0
* use license apache 2.0
* Contributors: Felix Messmer, ipa-fxm, ipa-uhr-mk

0.7.1 (2017-07-17)
------------------
* fix dependencies
* Contributors: Richard Bormann

0.7.0 (2017-07-17)
------------------
* Merge branch 'indigo_dev' of github.com:ipa320/cob_gazebo_plugins into multi_distro_travis_kinetic
  Conflicts:
  .travis.yml
  README.md
* compile with c++11
* Kinetic and Gazebo > 2, fixed hardware_interface::ControllerInfo API change
* Contributors: Benjamin Maidel, Dinesh Thakur, ipa-fxm

0.6.6 (2017-07-17)
------------------
* add state_valid behavior
* add estop behavior
* manually fix changelog
* Contributors: ipa-fxm

0.6.5 (2016-10-10)
------------------

0.6.4 (2016-04-01)
------------------

0.6.3 (2015-08-25)
------------------
* boost revision
* remove trailing whitespaces
* migration to package format 2
* fix missing dependency
* review dependencies
* Contributors: ipa-fxm

0.6.2 (2015-06-17)
------------------
* using strict_hwi_switch api
* more suitable name for plugin
* beautify CMakeLists
* use hwi_switch api
* proper reset of joint limit interface
* cleanup output
* Contributors: ipa-fxm

0.6.1 (2014-12-12)
------------------
* Update README.md
* Update README.md
* Update README.md
* Update README.md
* Update README.md
* enable joint filtering for multi_hwi_gazebo plugin
* remove support for X_PID control_methods for simplicity (obsolete anyway)
* unify ROS STREAM output
* ignore 'robotSimType'
* Update README.md
* Update README.md
* add README for new plugin
* correctly reset all interfaces in doSwitchHWInterface
* new gazebo_ros_control_plugin supporting multiple hardwareinterfaces and switch on controller_switching
* Contributors: Felix Messmer, ipa-fxm
