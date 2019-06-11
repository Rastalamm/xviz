# ROS data conversion into XVIZ

This module supports converting ROS bags into XVIZ. The approach taken is to create converters for
each ROS message. The message types can be obtained from the ROS bag and automatic conversion for
message can be setup.

Converting all messages is not generally desired, as it would be expensive and users normally care
about a specific set of core messages plus context specific messages.
