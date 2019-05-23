# ros_comm_message_filters_patch
Fedorea GCC bugfix for ros kinetic message filters

Forked from:
    uri: https://github.com/ros-gbp/ros_comm-release.git
    version: release/kinetic/message_filters/1.12.14-0

Bugfix details:
  https://github.com/ros/ros_comm/pull/1685

Temp/test workaround until above pull request is merged into kinetic branch

Sample test rosinstall:

git:
    local-name: ros_comm/message_filters
    uri: https://github.com/ebrand0007/ros_comm_message_filters_patch.git
    version: 1.12.14eb
    #uri: https://github.com/ros-gbp/ros_comm-release.git
    #version: release/kinetic/message_filters/1.12.14-0

