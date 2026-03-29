# VITyarthi_CV_Project
A CNN model that uses object detection to detect potential plant diseases.

Plant Disease Detection using YOLOv8

Overview
This project focuses on detecting and classifying plant diseases using a deep learning-based object detection model. The model is trained on the PlantDoc Dataset (Version 4 – Roboflow) and leverages the YOLOv8n architecture for efficient and real-time detection.

Dataset Description
Dataset Name: PlantDoc Dataset (Version 4 – Roboflow)
Source: Roboflow Universe – PlantDoc (Joseph Nelson Workspace)

Description
PlantDoc is a publicly available dataset designed for plant disease detection tasks in computer vision. It was originally developed by researchers from the Indian Institute of Technology.

Key Characteristics
Contains approximately 2,569 real-world images of plant leaves.
Covers 13 plant species with variations in:
Lighting conditions
Backgrounds
Leaf appearances
Includes 30 classes, consisting of both:
Diseased leaves (e.g., Apple scab, Corn rust, Tomato late blight)
Healthy leaves
Total of 8,851 labeled objects (bounding boxes) across all images.

Model Architecture
Architecture Type: CNN-based Object Detection Model
Model Used: YOLOv8n (Ultralytics)

YOLOv8n is a lightweight and fast object detection model suitable for real-time applications with limited computational resources.

Workflow
Dataset collection from Roboflow
Data preprocessing and annotation
Model training using YOLOv8
Evaluation using performance metrics
Result analysis and visualization

Experimental Setup
Environment
Google Colab
Open Notebook
GPU-enabled runtime (nvidia-smi)
Ultralytics YOLOv8 framework
Libraries Used
Roboflow
Ultralytics
