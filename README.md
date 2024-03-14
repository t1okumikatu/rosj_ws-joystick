# rosj_ws-joystick
micro_ros_arduino_twist_subscriber トピック用のジョイスティック　packageです

micro-ros-agentが動作している状態
<img width="764" alt="image" src="https://github.com/t1okumikatu/rosj_ws-joystick/assets/11044177/82ea42a7-bbd3-46bc-8b44-27d1328080fc">

$ cd ~/ros2_ws/src

$ ros2 pkg create --build-type ament_python --node-name joy_translate_node joy_translate

$ cd ~/ros2ws/src/joy_translate/joy_translate

 ros2 run joy_translate joy_translate_node --remap cmd_vel:=/micro_ros_arduino_twist_subscriber

