# pytorch YOLO-v1

I write this code for the purpose of learning. 

All the code and comments are in yolo_v1.ipynb.

### 1. Dependency
1. pytorch 1.2
2. torchvision
3. numpy
4. matplotlib
5. tqdm

### 2. A list of recommend readings:
- [YOLO original paper](https://arxiv.org/pdf/1506.02640.pdf) (recommended)
- [Object detection methods](http://slazebni.cs.illinois.edu/fall18/lec09_detection.pdf) (Slides)
- [Great post about YOLO](https://medium.com/adventures-with-deep-learning/yolo-v1-part-1-cfb47135f81f) on Medium
- [Differences between YOLO, YOLOv2 and YOLOv3
](https://medium.com/@jonathan_hui/real-time-object-detection-with-yolo-yolov2-28b1b93e2088)
- [Great explanation of the Yolo Loss function](https://stats.stackexchange.com/questions/287486/yolo-loss-function-explanation)

We adopt a variant of YOLO, which:
1. Use pretrained ResNet50 classifier as detector backbone. The pretrained model is offered in `torchvision.models`.
