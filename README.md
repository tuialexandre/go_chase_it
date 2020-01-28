# go_chase_it
Simulated mobile robot, programmed with C++ ROS nodes to chase white colored balls

## Running Nodes

To launch the robot and the world:

```
roslaunch my_robot world.launch
```

To run the ball_chaser node:

```
roslaunch ball_chaser ball_chaser.launch
```

To visualize the images, subscribe to camera RGB image topic from *RViz* or run the *rqt_image_view* node:


```
rosrun rqt_image_view rqt_image_view

```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
