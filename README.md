# 项目简介
项目名称：FICO-44  
简介视频：https://www.bilibili.com/video/BV1Yh41147wo/

![主控板](https://github.com/SiyphuS/FICO-44/blob/main/Picture/1.jpg)


***当前版本仍存在较大缺陷，仅供研究用***  
PCB工程 https://oshwhub.com/zhang_sai/44-guan-jie-qu-dong

## 特点：  
* 基于SIMPLE FOC实现的BLDC FOC（无电流环）控制，控制板集成控制、驱动、编码器于一体； 
* **单个关节80元左右的物料成本**
* 采用集成两级行星减速器，减速比达到30；  
* 除轴承、螺钉、螺母外，所有结构件采用3D打印，大大降低成本。  

## 参数
* 额定电压：16V  
* 额定功率：25W  
* 最大扭矩：1N·M（预估，可能误差较大）  
* 最高转速：80RPM  
* 峰值电流：2.5A  

## 缺陷
* **缺少电流环，高负载、快速运动时极易跑飞，导致当前版本可用性较差。正在考虑保持成本不会大幅上升的解决方案**  
* **3D打印行星减速器的齿轮、齿圈时，打印机精度不足导致装配有问题或者运动过程中阻力过大。使用ENDER-3S打印机，PLA耗材，调教打印机到良好状态时成品率较高，摩擦力可接受。**  

## 提示
* 3D打印的模型需要根据自己的打印机型号和状态进行动态调整后输出STL文件打印，涉及过盈配合和齿轮传动
* 电机一定要让商家做成不带限位的，否则...

## 使用说明
LGT8F328P环境搭建指南：https://oshwhub.com/costar/larduino  
