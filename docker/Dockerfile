FROM osrf/ros:noetic-desktop

# Get dependencies
RUN apt-get update && apt-get install -y python3-vcstool ros-noetic-pcl-ros ros-noetic-rqt* libproj-dev libglfw3 libglfw3-dev libglm-dev ros-noetic-hector-trajectory-server python3-catkin-tools python3-osrf-pycommon libgflags-dev libgoogle-glog-dev libyaml-cpp-dev git libtool

# Get libcaer
RUN apt-get install -y software-properties-common
RUN add-apt-repository ppa:inivation-ppa/inivation
RUN apt-get update && apt-get install -y libcaer-dev
