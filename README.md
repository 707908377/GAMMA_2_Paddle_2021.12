# 标题：飞桨常规赛：黄斑中央凹定位（GAMMA挑战赛任务二） - 12月第3名方案

本项目为2021.12参赛作品，最终得分8.53045

Python版本：python 3.7

框架版本：PaddlePaddle 2.0.2

本项目AI Studio地址：https://aistudio.baidu.com/aistudio/projectdetail/3369894?contributionType=1
从中可以获得更加详细的介绍和可一键复现的飞桨算法代码
![image](https://user-images.githubusercontent.com/95835850/150354750-0b22bc41-33ed-4e5b-80ea-5b9e6ab5319f.png)

## 提交时所使用的checkpoint
最终比赛提交的结果中，checkpoints使用的是/home/aistudio/best_model_0.0124/路径下的model.pdparams

## 参数配置
根据GPU显存大小将批次大小(Batch size)设定为32

将迭代轮数设定为3000，初始学习率设定为0.0001

本案例使用adam优化器

经测试以上参数设定可以达到较好的结果

## 总结与展望
尝试其他优化器

进一步调整学习率及超参数，考虑一些学习率调整策略

尝试更深层的网络模型
