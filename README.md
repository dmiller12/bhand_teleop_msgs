# Instructions

Add package to catkin_ws/src

To use these messages, add the following to your package:
## Add to package.xml

```xml
<build_depend>bhand_teleop_msgs</build_depend>
<run_depend>bhand_teleop_msgs</run_depend>
```

## Add to CMakeLists.txt

```cmake
find_package(catkin REQUIRED COMPONENTS
  bhand_teleop_msgs
)
```
