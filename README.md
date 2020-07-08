# rosdistro

Service Robotics Lab custom debian related scripts:

* **rosdep.yaml**: rosdep lists. Relation between the name of the packages as dependency (package.xml) and the name of the APT debian package.

* **generate_debian_pkgs.sh**: script to generate multiple catkin packages hosted in the same catkin workspace (including the dependencies, which could be also installed instead of to be in the workspace) using Bloom.