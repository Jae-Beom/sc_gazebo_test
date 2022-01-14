email: jae-beom@kakao.com

# sc_gazebo_test
gazebo: slider-crank

## SliderCrank URDF model check

### Rviz launch (open loop)   
  roslaunch sc_description sc_rviz.launch

### Gazebo launch (closed loop)   
  roslaunch sc_gazebo sc_world.launch

#### Joint control:   
1st revolute joint, use '/SliderCrank/joint_position_controller/command' Topic   
  rosrun rqt_gui rqt_gui
