GPS
======

This code is a reimplementation of the guided policy search algorithm and LQG-based trajectory optimization, meant to help others understand, reuse, and build upon existing work.

For full documentation, see [rll.berkeley.edu/gps](http://rll.berkeley.edu/gps).

The code base is **a work in progress**. See the [FAQ](http://rll.berkeley.edu/gps/faq.html) for information on planned future additions to the code.

# edit
editor :shumpei wakabayashi

## edit point
- Set mjpro131 as mjpro in /PATH_TO_gps/gps/src/3rdparty
- apt-get install some package for ros-melodic
- Change from PLUGINLIB_DECLARE_CLASS to PLUGINLIB_EXPORT_CLASS written in /PATH_TO_gps/gps/src/gps_agent_pkg/src/pr2plugin.cpp for melodic. See [here](http://wiki.ros.org/pluginlib).