# IsaacSim4.5-Digit

## Issacsim4.5-Digit
我们的项目是基于 [TactSim-IsaacLab](https://github.com/WilliamBonilla62/TactSim-IsaacLab_4_5?tab=readme-ov-file#digit-robot-simulation-in-isaac-lab)

目前上传的代码是对他们的工作进行了扩展。

该模拟场景中有一个配备指尖摄像头的机器人手，它可以在模拟环境中与螺栓等物体进行交互。该模拟旨在从传感器的视角提供视觉反馈。我们添加了深度信息反馈，并且将原来的螺栓可替换成其他物体。

### Requirement
该项目是在Ubuntu 22.04 系统上与 Isaac Lab 4.5 版本上运行。

在运行该项目之前请您确保已经：

按照官方说明完成了 Isaac Lab 4.5 的完整安装：https://isaac-sim.github.io/IsaacLab/main/index.html

仔细阅读并理解了 [TactSim-IsaacLab](https://github.com/yuanqing-ai/TactSim-IsaacLab) 中的设置

### 项目运行

   ```
   conda activate env_isaaclab  虚拟环境名
   cd Issacsim4.5-Digit
   python demo_bolt.py --enable_cameras
   ```
 • 这将启动以下模拟：
 
    一个 Digit 机器人
    
    小球和盒子物体
    
    指尖上的摄像头
    
    使用微分逆运动学的实时 RGB 和深度图和抓取器控制

### 输出展示


###
