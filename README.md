# Social Distancing Detection
A social distance surveillance project typically involves using technology to monitor and enforce social distancing guidelines in public spaces. This kind of project aims to ensure public safety during events like pandemics where maintaining a safe physical distance between individuals is crucial to prevent the spread of diseases. The pre-trained YOLOv3 weights, enabling rapid deployment without the need for extensive training. The COCO model dataset further enriches the system's capabilities by imparting a comprehensive understanding of object classes relevant to diverse public environments.This integration facilitates accurate identification of individuals in crowded scenarios, enabling precise measurement of the spatial separation between them.

### Camera System:
Deploying a network of cameras to capture video footage in public spaces.
Cameras should be strategically placed to cover a wide area where people gather.
### Computer Vision:
Implementing computer vision algorithms to analyze the video feed.
Object detection algorithms can be used to identify people and track their movements.
Inthis project we have used YOLOV3 Architecture and COCO MODEL Dataset
### YOLOV3 :
You Only Look Once (version 3) is an open-source object detection framework developed by Ultralytics. It's an evolution of the YOLO architecture and is designed to be more user-friendly, flexible, and efficient.

train the model: python train.py --img-size 640 --batch-size 16 --epochs 50 --data your_data.yaml --weights yolov5s.pt


--img-size: Input image size during training.

--batch-size: Batch size.

--epochs: Number of training epochs.

--data: Path to your dataset configuration file.

--weights: Path to pre-trained weights file (optional).
### Social Distancing Detection:
Developing algorithms to detect and measure the distance between individuals in the video feed.
Using techniques such as image processing, deep learning, or other computer vision approaches.
### Alert System:
Implementing an alert system to notify authorities or individuals when social distancing violations are detected.
Alerts can be sent via SMS, email, or other communication channels.

## Technologies used
Python

YOLOv3 ( Efficient Deep learning technology used for object detection)
## YOLOv3 Architecture
![yolo v3 architecture](https://github.com/gangakona/Social-Distancing-Detection/assets/110378442/123141d3-5cfe-4dd8-863e-fd7911e7f2f7)
