# Traffic-Sign-Sensing

The "Traffic Sign Sensing Using Object Detection with YOLOv8 and NAS-YOLO" project represents a cutting-edge application of computer vision. Additionally, the project has resulted in the creation of a research paper, contributing valuable insights and advancements to the field of traffic sign detection and autonomous driving systems.

<div align="center">
  <img src="assets/logo.svg" width="400" alt="Traffic Sign Sensing Logo" />
</div>


## Motivation 
Traffic signs are of paramount importance in the realm of road transportation. These signs are instrumental in upholding safety and efficiency on our roadways. One of their primary functions is to communicate vital information and regulations, regardless of language barriers, thus ensuring the safety of all road users.
Traffic signs give drivers directions, assisting them in navigating new roads and selecting the best course of travel. Along with providing directions to hospitals, rest stops, petrol stations, and other locations, they also act as informational beacons. Drivers can avoid potential dangers including crossings, curves, and construction zones by paying attention to warning signs.

The primary aim is to harness object detection technology for the critical objective of accident prevention, with a specific emphasis on the application of this technology to traffic signs. The overarching goal of this study is to design, develop, and assess an intelligent system capable of real-time detection and analysis of traffic signs, ultimately leading to a substantial reduction in road accidents and an enhancement of overall road safety.

A fundamental computer vision approach called object detection involves discovering and recognising things of interest in digital pictures or video frames. It is essential to many industries, including industrial automation, driverless vehicles, surveillance systems, and medical imaging. Object detection's main objective is to educate computers to witness and identify objects so they can interpret and react to the visual world much like humans do.
Object detection has made great improvements in accuracy and efficiency thanks to developments in deep learning and the accessibility of big datasets, becoming a core technology in a variety of fields and applications. In the fields of computer vision and artificial intelligence, it continues to inspire innovation and open up new opportunities due to its development potential.
The absence of thorough and easily accessible object detection systems in the context of driving safety emphasises how crucial it is to create and execute such programs. Despite substantial developments in object detection technology, there is still a glaring gap in its general usage for promoting road safety. This gap is especially noticeable in autonomous vehicles, where the lack of widely available, highly accurate object-detecting technologies presents a significant obstacle to the development of fully automated and secure transportation. Furthermore, the lack of effective object identification technology hinders efforts to improve traffic management, accident avoidance, and pedestrian safety in the larger transportation sector. 
This paper uses a dataset that is full of potential and could serve as a basis for showcasing the deployment of road safety applications with high precision and standards.

This paper's contributions are:
1) An object detection approach for identifying different types of traffic signs for safety purposes has been proposed. Comparison between numerous models like YOLO-NAS-l,YOLOv8x,YOLOv8n,YOLOv8s,YOLOv8l and YOLOv8m.
2) The techniques have been applied to four different classes of traffic signs namely traffic lights, Stop signs, Speed Limit signs and crosswalk signs. These signs are essential in order to increase the safety of pedestrians as well as drivers.
3) The paper has implemented a total of 6 object-detection models to achieve the best possible results. 
4) The main goal of this paper is to introduce the importance of high-precision applications of object detection in road safety. Decreasing accidents on the root level and thus increasing the safety of citizens is the underlying purpose of this paper.



## Models

YOLOv8 [Detect](https://docs.ultralytics.com/tasks/detect), [Segment](https://docs.ultralytics.com/tasks/segment) and [Pose](https://docs.ultralytics.com/tasks/pose) models pretrained on the [COCO](https://docs.ultralytics.com/datasets/detect/coco) dataset are available here, as well as YOLOv8 [Classify](https://docs.ultralytics.com/tasks/classify) models pretrained on the [ImageNet](https://docs.ultralytics.com/datasets/classify/imagenet) dataset. [Track](https://docs.ultralytics.com/modes/track) mode is available for all Detect, Segment and Pose models.

<img width="1024" src="https://raw.githubusercontent.com/ultralytics/assets/main/im/banner-tasks.png" alt="Ultralytics YOLO supported tasks">




The new YOLO-NAS delivers state-of-the-art performance with the unparalleled accuracy-speed performance, outperforming other models such as YOLOv5, YOLOv6, YOLOv7 and YOLOv8.

<div align="center">
<img src="assets/yolo_nas_frontier.png" width="400px">
</div>



## Results


<div align="center">



| Model                                                                                | Precision | Recall | mAP50 | mAP50-95 |
| ------------------------------------------------------------------------------------ | --------------------- | -------------------- | ------------------------------ | ----------------------------------- |
| [YOLOv8n](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt) | 97.9                   | 92.8                 | 95.3                           | 82.2                               |                 | 
| [YOLOv8s](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8s.pt) | 98.3                   | 92                   | 94.9                           | 80.6                               |                |
| [YOLOv8m](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8m.pt) | 91.8                   | 91.4                 | 94.3                           | 79                                 |                |
| [YOLOv8l](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8l.pt) | 95.9                   | 87.9                 | 92                             | 76.6                               |                | 
| [YOLOv8x](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8x.pt) | 93                     | 91.6                 | 91.9                           | 76.2                               |                | 
| [YOLONAS-l](https://github.com/Deci-AI/super-gradients/tree/master)                  | NA                     | 97.5                 | 95.7                           | NA                                 |                

</div>


## Basic visualization of Results
<div align="center">
<img src="assets/Results.png" width="400px">
</div>
