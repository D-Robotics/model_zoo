# YoLo V5 Python Demo
本示例用于YoLo V5 算法示例展示

## 示例简介
本算法为目标检测算法，模型信息如下：

输入数据类型：NV12/rgb888

输入尺寸：1*3*672*672

输出类别：coco 80类

训练源码：repo连接 or None

量化方案：None 

## 准备工作

### 模型下载 （X3/X5/super）

wget *** x3 / x5

## 输入/输出
输入数据可选项为 `图像` 和 `usb sensor` `mipi sensor` 输入
输出结果可分为`本地保存`和`桌面显示`两种方式


### 运行

```python

python3 yolov5_det_demo.py
            -- input './data/coco.img' /  '/dev/video8' / 'mipi'
            -- output 'result.jgp' / 'hdmi'
```

## 效果展示




