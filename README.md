| Supported Targets | ESP32 | 
| ----------------- | ----- |

项目介绍：

此设备是是一个基于BLE（低功耗蓝牙）的HID（人机交互）设备。它基于ESP32芯片开发，集成了手势识别模块PAJ7620, 惯性传感芯片MPU6500还有一个五向按钮，同时带有锂电池管理芯片，可以便携使用。

功能介绍：

1. 飞（空）鼠 Air mouse,  它使用MPU6500的陀螺仪Y， Z轴的角度变化，转化成鼠标的x，y坐标，X轴角度变化转化成滚轮数据，使用五向按钮中的3个映射鼠标的左中右键。

2. 手势控制, 它采集PAJ7600的8个手势可以转化成操作手机的上下左右滑动，手指点击，返回等操作，从而可以手势控制手机。比较典型的应用是短视频软件的隔空操作。

3. 键盘宏命令，设备预置了各种键盘按键和组合键操作，这些操作可以映射到五向按钮或者8种手势上，作为外设服务电脑操作。典型应用如PPT遥控操作，手势控制虚拟桌面或者应用的操作。

4. 功能自定制，设备同时配备了一款Android App，通过app可以实现手势，按钮不同功能的映射，还可以预定制的各种功能模式间自由切换。



