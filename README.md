# YOLO-Object-Detection
YOLO : Real-Time Object Detection

This repository  implement a object detection application using YOLO model from darknet with dnn module of OpenCV


# Download and Usage

```
$ git clone https://github.com/Taysssir/YOLO-Object-Detection.git
$ cd YOLO-Object-Detection
$ pip install -r requirements.txt

```

Download weights of the model into YOLO-Object-Detection/cfg/
```
wget https://pjreddie.com/media/files/yolov3.weights
```

* input image: 
```
python object_detection_yolo.py --label=cfg/coco.names --cfg=cfg/yolov3.cfg --model=cfg/yolov3.weights --image=face1.jpg
```

* input video: 
``` 
python object_detection_yolo.py --label=cfg/coco.names --cfg=cfg/yolov3-.cfg --model=cfg/yolov3.weights --video=Walk.mp4
```

* Webcam: 
``` 
python object_detection_yolo.py --label=cfg/coco.names --cfg=cfg/yolov3.cfg --model=cfg/yolov3.weights
```
