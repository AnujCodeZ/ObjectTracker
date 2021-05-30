# Object Tracking using YOLOv4 and Deep SORT
YOLOv4 is a powerful object detector and Deep SORT is a technique to keep track of object in next frame.

## Demo:
![](demo.gif)

## Installation:
`pip install -m requirements.txt`

## Download pretrained models:
- YOLOv4: https://drive.google.com/open?id=1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT
- YOLOv4-tiny: https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v4_pre/yolov4-tiny.weights

## Run on your own video:
```
$ cd deep-sort/
$ python3 save_model.py
$ python3 object_tracker.py --video <path to video>
```
Check your result video in outputs folder.

If you want to run on your webcam:

`$ python3 object_tracker.py --video 0`
