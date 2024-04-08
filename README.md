yolo为视觉部分，检测算法位于\yolo\ultralytics-main\ultralytics-main\ultralytics\D455下的detect.py文件，安装好yolov8相关包与D455i库可以运行（注意文件98行中权重路径使用的是绝对路径，注意改变）。
算法解释：yolov8进行目标检测，对于目标（圆形/椭圆）根据颜色按照一定路径进行搜索，得到八个点并进行拟合得到椭圆中心，最后通过D455可以直接得到椭圆中心三维位置信息

F16model-simulink:核心是\空中加油\F16model-simulink\6dof下f16simulation.slx文件，参考论文为主文件夹下的“无人机自主空中加油对接控制技术研究”参考论文2到3章，对F16进行仿真建模，线性化后使用LQR-PI实施控制并进行仿真
