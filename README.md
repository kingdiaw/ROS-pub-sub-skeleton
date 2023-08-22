# ROS Publisher and Subscriber Skeleton
For more detail about the code, you may refer to the tutorial writen by  Muhammad Luqman at
[Wiki: ROS/Tutorials/WritingPublisherSubscriber(python)](http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28python%29)

Furthermore, the message type uses in ros node are various. For more detail about message type, you may refer to [std_msgs](http://wiki.ros.org/std_msgs) and [common_msgs](https://wiki.ros.org/common_msgs) 

If you are researching a functioning ROS node, you wonder what type of message is being used for a particular topic, you can check the message type using the following command:
```
rostopic info <the_topic>
```
for example
```
rostopic info /turtle1/cmd_vel
Type: geometry_msgs/Twist
```

Furthermore, you can also determine the data structure of the relevant message type using the command below:
```
rosmsg show <message-type>
```
for example
```
rosmsg show geometry_msgs/Twist
```
