# Traffic Signs Detection Using YOLOv8

## Project Overview
This project implements **real-time traffic sign detection** using **YOLOv8**, the latest object detection model from Ultralytics. YOLOv8 leverages deep convolutional neural networks to detect and localize multiple objects in images and videos simultaneously, offering high-speed and accurate performance suitable for real-time applications.

Traffic sign detection is crucial for enhancing **road safety**, **traffic management**, and **urban planning**. By accurately recognizing signs, this system can assist autonomous vehicles in interpreting road conditions, support city planners in monitoring infrastructure, and aid in surveillance applications.

The system can classify multiple types of signs (e.g., stop, yield, speed limits) and draw bounding boxes around them, providing an intuitive visual output for real-time applications.

## Features
- Real-time detection and classification of traffic signs  
- Detection of multiple signs within a single frame  
- High accuracy using **YOLOv8 pre-trained models**  
- Supports **images, video files, and live camera feeds**  
- Customizable for different traffic sign datasets  
- Can be applied in autonomous driving, intelligent traffic systems, and urban planning analysis  

## YOLOv8 Overview
YOLO (You Only Look Once) treats object detection as a single regression problem. Unlike traditional multi-stage pipelines, YOLO predicts bounding boxes and class probabilities **in a single pass**, enabling **fast inference** and real-time performance.

**YOLOv8 highlights:**  
- High detection accuracy with minimal false positives  
- Efficient performance on both CPUs and GPUs  
- Flexible training on custom datasets  
- Supports object detection, classification, and segmentation  

## Methodology
1. **Data Collection:** Gather images of traffic signs from public datasets or custom sources.  
2. **Data Annotation:** Label images with bounding boxes and class labels using tools like **LabelImg**.  
3. **Model Training:** Fine-tune YOLOv8 on the annotated dataset to improve recognition accuracy.  
4. **Testing & Evaluation:** Evaluate the model using metrics like **precision, recall, and mAP**.  
5. **Real-Time Detection:** Deploy the trained model on video streams or camera feeds to detect traffic signs in real-time.  
