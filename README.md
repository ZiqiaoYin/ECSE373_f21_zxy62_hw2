# preparation
## compile
```
  cd catkin_ws/
  source devel/setup.bash
  catkin_make
```
# begin
## without wheel  
```
  cd catkin_ws/src/navvis_decription/launch
  roslaunch display.lauch
```
## with wheel
  cd catkin_ws/src/navvis_decription/launch
  roslaunch display.lauch use_xacro:=true
## control with wheel
```
  cd catkin_ws/src/navvis_decription/launch
  roslaunch display.lauch use_gui:=false
```
## control without wheel
```
  cd catkin_ws/src/navvis_decription/launch
  roslaunch display.lauch use_xacro:=true use_gui:=false
```

