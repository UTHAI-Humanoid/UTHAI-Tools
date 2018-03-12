# UTHAI-Tools [sketch-lib]
เป็นเครื่องมือสำหรับเอาไว้วาดรูปเฟรม

**ใช้ได้แค่บน Ubuntu เท่านั้น**

## Example
![](https://github.com/UTHAI-Humanoid/UTHAI-Tools/blob/master/sketch-lib/basic-shapes.png?raw=true)

![](https://github.com/UTHAI-Humanoid/UTHAI-Tools/blob/master/sketch-lib/test_robot.png?raw=true)

![](https://github.com/UTHAI-Humanoid/UTHAI-Tools/blob/master/sketch-lib/uthai_kinematics.png?raw=true)

## How to use
1. Clone Repository
    ```
    $ cd ~/catkin_ws/src
    $ git clone https://github.com/UTHAI-Humanoid/UTHAI-Tools.git
    ```

1. Edit kinematics.sk file
    ```
    $ gedit uthai_kinematics.sk
    ```

1. Build sk to png
    ```
    $ ./sk2png uthai_kinetics.sk
    ```
    จะได้ไฟล์รูปภาพ .png มา



