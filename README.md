[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AnaSliwinska/The-Brain-Tumor-Detection/)

## **The Brain Tumor Detection**

**Dataset:** https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

**Annotation tool:** Make Sense AI

**The target of project:** the detection object on Brain MRI Imagies and comparision of version  YOLO models

YOLO (You Only Look Once) is a popular object detection algorithm that has revolutionized the field of computer vision. One of the main advantages of YOLO is its fast inference speed, which allows it to process images in real time. Additionally, YOLO has a simple architecture and requires minimal training data, making it easy to implement and adapt to new tasks.

YOLO is a single-shot detector that uses a fully convolutional neural network (CNN) to process an image. YOLO proposes using an end-to-end neural network that makes predictions of bounding boxes and class probabilities all at once. The YOLO algorithm takes an image as input and then uses a simple deep convolutional neural network to detect objects in the image.

YOLO v5 is the fifth version of the YOLO object detection algorithm introduced in 2020 by the same team that developed the original YOLO algorithm as an open-source project and is maintained by Ultralytics. YOLO v5 uses a more complex architecture called EfficientDet, based on the EfficientNet network architecture. 

yolov5: https://github.com/ultralytics/yolov5

YOLOv8 is the latest version of the YOLO  object detection algorithm introduced in 2023. In YOLOv8, there are five different models [YOLOv8n, YOLOv8s, YOLOv8m, YOLOv8l, YOLOv8x] available for each category of detection, segmentation, and classification. YOLOv8n is the smallest and fastest model, while YOLOv8 Extra Large (YOLOv8x) is the slowest.

yolov8: https://github.com/ultralytics/ultralytics



**Results:** The experimental results and analysis are presented below for Yolov5  model:

![image-20240219134702292](/home/ania/Ania/DS/001_new_project/github/09_BRAIN_TUMOR_DETECTION/img/image-20240219134702292.png)

The experimental results and analysis are presented below for Yolov8  model:

![image-20240219134638120](/home/ania/Ania/DS/001_new_project/github/09_BRAIN_TUMOR_DETECTION/img/image-20240219134638120.png)

**Outcomes:** Below you can see examples with predict object and without object.

![image16](/home/ania/Ania/DS/001_new_project/github/09_BRAIN_TUMOR_DETECTION/img/image16.jpg)



![image13](/home/ania/Ania/DS/001_new_project/github/09_BRAIN_TUMOR_DETECTION/img/image13.jpg)



**Conclusions:** In this case, the YOLOv8 model is better than the YOLOv5 model, but the metrics are very similar. The precision is the same for the 0 class, and the recall is the same for the 1 class.
