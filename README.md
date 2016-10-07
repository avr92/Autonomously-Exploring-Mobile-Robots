# Autonomously-Exploring-Mobile-Robots
Using a SLAM algorithm to localize a mobile robot relative to a unknown 2D map created using a simulated laser range sensors. Plan robot motion so as to minimize the time required to construct the map and locate a stationary target.


Phase 1:
Simulate a sample Map for testing the problem and implement SLAM functionalities in ROS to design a simple human guided approach to assist the bot in constructing maps manually using the values outputted by the depth sensors of the bot. For this project, I will be using a simple pi robot to run the simulations.


Phase 2:
Design a path exploration algorithm for the bot to autonomously construct a 2D map using the depth
sensor readings that are simulated from the pi robot laser scanners.
Specifically, I am designing a hybrid exploration algorithm that uses both probabilistic exploration approach and frontier exploration approach. The Idea is from the fact that eventhough the study shows that Frontier exploration technique has been proven to be very efficient in exploring the map in minimal time duration, study also shows that the probabilistic random exploration technique is capable of canvassing about 50% of the map in very less time duration compared to the Frontier exploration technique. Hence, I would like to implement a trial and error approach to verify the stability of the newly generated algorithm.

Phase 3:
Implement an RRT traversal technique to find a path from a given point to the target location after determining the location of the stationary object.
