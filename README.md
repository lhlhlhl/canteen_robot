# 基于ROS2实现的送餐机器人


## 1.介绍


## 2.安装运行

### 2.1 下载编译


```
git clone https://github.com/lhlhlhl/canteen_robot.git
cd canteen_robot
rosdep install --from-paths src -y
colcon build
```

### 2.2 运行测试

#### 在RVIZ中显示机器人模型

```
source install/setup.bash
ros2 launch fishbot_description display_rviz2.launch.py
```


```
source install/setup.bash
ros2 launch fishbot_description gazebo.launch.py
```
