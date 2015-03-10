# prabhat1081_print_squares
Practice assignment of ROS 

The assignment contains three ROS nodes as follows : 
1. numbers : Publishes numbers fron 1 to "topic_nunbers" at 1Hz frequency
2. squares : Subscribes to "topic_numbers" and publishes the squares of the numbers to "topic_squares"
3. print : Subscribes to both "topic_numbers" and "topic_squares" and prints using ROS_INFO


