email: jae-beom@kakao.com

# sc_gazebo_test
gazebo: slider-crank

## SliderCrank URDF model check

### Rviz launch (see open loop)   
<pre><code>roslaunch sc_description sc_rviz.launch
</code></pre>

### Gazebo launch (see closed loop)  
<pre><code>roslaunch sc_gazebo sc_world.launch
</code></pre>

#### Joint control:   
1st revolute joint, use '/SliderCrank/joint_position_controller/command' Topic   
<pre><code>rosrun rqt_gui rqt_gui
</code></pre>
