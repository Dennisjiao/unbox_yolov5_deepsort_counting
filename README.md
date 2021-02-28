# yolov5 deepsort 行人 车辆 跟踪 检测 计数

- 实现了 出/入 分别计数。
- 默认是 南/北 方向检测，若要检测不同位置和方向，可在 main.py 文件第13行和21行，修改2个polygon的点。
- 默认检测类别：行人、自行车、小汽车、摩托车、公交车、卡车。
- 检测类别可在 detector.py 文件第60行修改。


### 视频


## 运行环境

- python 3.8+，pip 20+
- pytorch
- Anaconda3包管理器




## 引用

- https://github.com/Sharpiless/Yolov5-deepsort-inference
- https://github.com/ultralytics/yolov5/
- https://github.com/ZQPei/deep_sort_pytorch
