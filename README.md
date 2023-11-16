# Dataset-for-multisensor-track-fusion 
多传感器航迹融合数据集
Dataset for multisensor track fusion

NT=2~NT=10表示传感器个数从2到10变化时的仿真数据
pd=0.2~pd=0.99表示检测概率从0.2到0.99变化时的仿真数据

每一组数据包含一下文件:

plane_set_1.mat: 载机运动轨迹
TargetData_1.mat: 目标运动轨迹
ScenarioData_1.mat~ScenarioData_100.mat：1~100次仿真局部航迹数据
