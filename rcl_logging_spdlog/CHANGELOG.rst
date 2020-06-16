^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rcl_logging_spdlog
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.0 (2020-05-26)
------------------
* Add some preliminary functional tests (`#36 <https://github.com/ros2/rcl_logging/issues/36>`_)
* warn about unused return value for set_logger_level (`#38 <https://github.com/ros2/rcl_logging/issues/38>`_)
* Added features to rcl_logging_spdlog (`#35 <https://github.com/ros2/rcl_logging/issues/35>`_)
* Added public API documentation for log4cxx and spdlog (`#32 <https://github.com/ros2/rcl_logging/issues/32>`_)
* Current state Quality Declaration, Contributing and Readme files (`#29 <https://github.com/ros2/rcl_logging/issues/29>`_)
* Contributors: Alejandro Hernández Cordero, Dirk Thomas, Jorge Perez, Scott K Logan

0.4.0 (2020-04-24)
------------------
* Export targets in addition to include directories / libraries (`#31 <https://github.com/ros2/rcl_logging/issues/31>`_)
* Make spdlog an exec_depend (`#27 <https://github.com/ros2/rcl_logging/issues/27>`_)
* Code style only: wrap after open parenthesis if not in one line (`#24 <https://github.com/ros2/rcl_logging/issues/24>`_)
* Bypass spdlog singleton registry (`#23 <https://github.com/ros2/rcl_logging/issues/23>`_)
* Contributors: Chris Lalancette, Dirk Thomas, Ivan Santiago Paunovic

0.3.3 (2019-10-23)
------------------
* Fix Clang warning about possible uninitialized variable (`#21 <https://github.com/ros2/rcl_logging/issues/21>`_)
* Contributors: Jacob Perron

0.3.2 (2019-10-07)
------------------
* spdlog is a header-only library, so the exported dep isn't needed. (`#19 <https://github.com/ros2/rcl_logging/issues/19>`_)
* Contributors: Chris Lalancette

0.3.1 (2019-10-03)
------------------
* Implement a backend logger using spdlog. (`#17 <https://github.com/ros2/rcl_logging/issues/17>`_)
* Contributors: Chris Lalancette

0.3.0 (2019-09-26)
------------------

0.2.1 (2019-05-08)
------------------

0.2.0 (2019-03-09)
------------------

0.1.0 (2018-12-07)
------------------
