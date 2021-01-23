# YOLOV3-Object-Detection

### What is Yolov3 ?
YOLOv3 is the latest variant of a popular object detection algorithm YOLO – You Only Look Once. The published model recognizes 80 different objects in images and videos, but most importantly it is super fast and nearly as accurate as Single Shot MultiBox (SSD).
YOLOV3 uses the architecture of darknet53, and then uses many 1x1 and 3x3 convolution kernels to extract features. Tiny-yolov3 reduces the number of convolutional layers, its basic structure has only 7 convolutional layers, and then features are extracted by using a small number of 1x1 and 3x3 convolutional layers.

With YOLO, a single CNN simultaneously predicts multiple bounding boxes and class probabilities for those boxes. YOLO trains on full images and directly optimizes detection performance. This model has a number of benefits over other object detection methods: YOLO is extremely fast.

In this project i used coco dataset 
Coco dataset : “COCO is a large-scale object detection, segmentation, and captioning dataset.” The COCO Dataset. Common Objects in Context (COCO) literally implies that the images in the dataset are everyday objects captured from everyday scenes. This adds some “context” to the objects captured in the scenes.
The COCO dataset is an excellent object detection dataset with 80 classes, 80,000 training images and 40,000 validation images.

All you need is yolov3 weights and config file to download and opencv library implemented
Link for downloading weights and cfg files :
https://pjreddie.com/darknet/yolo/

By using this Notebook you can detect objects from any image for Example :
EX1 
#### Before 
![Image1](Test-images/test2.jpg)

#### After
![Output1](Output-images/savedImage1.jpg)

EX2
#### Before 
![Image1](Test-images/test1.jpg)

#### After
![Output1](Output-images/savedImage2.jpg)


