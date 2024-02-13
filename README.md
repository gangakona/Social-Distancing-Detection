# Social_distance_survilience
A social distance surveillance project typically involves using technology to monitor and enforce social distancing guidelines in public spaces. This kind of project aims to ensure public safety during events like pandemics where maintaining a safe physical distance between individuals is crucial to prevent the spread of diseases.
### Camera System:
Deploying a network of cameras to capture video footage in public spaces.
Cameras should be strategically placed to cover a wide area where people gather.
### Computer Vision:
Implementing computer vision algorithms to analyze the video feed.
Object detection algorithms can be used to identify people and track their movements.
Inthis project we have used YOLOV3 Architecture and COCO MODEL Dataset
### YOLOV5 :
You Only Look Once (version 5) is an open-source object detection framework developed by Ultralytics. It's an evolution of the YOLO architecture and is designed to be more user-friendly, flexible, and efficient.

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
