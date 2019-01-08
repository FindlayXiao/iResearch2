[//]: # (Image References)

[image1]: ./images/preview.png "Sample Output"

# 计算机视觉 - 车辆检测

## 项目概述

在这个notebook中，你将在交通标志识别之后，继续开发可以作为自动驾驶汽车视觉一部分的算法。本项目采用图像HOG特征结合SVM分类器的方法对摄像机画面中的车辆进行探测（Detection）。在本次爱科研科研实训毕业项目中，你也将尝试使用神经网络对画面中的车辆进行探测。

## 效果预览

![Sample Output][image1]

## 项目指南

### 步骤

1. 打开文件夹并激活环境。

 ```bash
cd iResearch2/vehicle_detection
source activate iResearch
```

2. 下载[数据集](https://pan.baidu.com/s/1skQGYy6NrqLpNmHook8UGw)，并将数据集解压到存储库中。

3. 打开 notebook

 ```
jupyter notebook vehicle_detection_svm.ipynb
```

__注意：__ 我们虽然已经实现了一些代码，让你更快地开始工作，你仍需要实现额外的功能来完成项目的要求。
__除非有要求，否则不要修改任何已经包含的代码。__

## 项目提交

当你准备好提交你的项目时，将下列文件整理并压缩成一个文件，以便上传。

- 代码完整可运行的文件 `vehicle_detection_svm.ipynb`，所有的代码块都要执行并展示结果
