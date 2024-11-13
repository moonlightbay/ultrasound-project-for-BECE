# ultrasound-project-for-BECE
## 0 项目整体介绍


## 1 硬件系统搭建
上位机、直流电压源
TX7364EVM 作为脉冲收发
AFE58JD32 AFE
TSW14J50

## 1.1 TX7364 EVM

1.电源和USB连接上位机的条件下，管理员模式打开TX7364-latte
2.左上角文件展开，选择devinit.py脚本，上方Run->buffer，打开交互式GUI，选择TX7364
3.打开Quick Setup页面，开机后单击一次Memory Reset。这是因为上电时，内存不会重置，因此要刷新。等待
4.然后点击Hardware Reset，等待。
5.点击 Load Sample Patterns，会将一组预定义好的模式加载到设备中
6.点击右侧的Reset display，然后点击Start Diagnosis




