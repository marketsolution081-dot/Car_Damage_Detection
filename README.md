# 🚘 Car Damage Detection using YOLO11

## 1. Project Title
**Car Damage Detection using Computer Vision and YOLO11**

## 2. Project Overview
This project is a Computer Vision based **Car Damage Detection** system. 
The system uses a custom annotated dataset and the **YOLO11n** object detection model to detect damaged areas of cars in images and videos. 
A simple **Gradio interface** is also included for image-based car damage detection.

## 3. Problem Statement
Car damage inspection is usually performed manually. This can take time and may not always be consistent. 
The goal of this project is to build an automatic Computer Vision system that can detect car damage from images and videos using object detection.

## 4. Objective
The main objectives of this project are:
* Use a custom Computer Vision dataset.
* Annotate car damage objects.
* Train a YOLO11 object detection model.
* Evaluate the trained model.
* Detect damage in test images.
* Detect damage in videos.
* Create a simple Gradio application.

## 5. Dataset
A custom annotated **Car Damage Detection** dataset is used in this project.
* **Dataset Link:** [Roboflow Dataset](https://universe.roboflow.com/capstone-nh0nc/car-damage-detection-t0g92/dataset/4)
* The dataset is prepared in YOLO format and contains training, validation, and test data.

## 6. Model
The project uses:
* **Model:** YOLO11n
* **Task:** Object Detection
* **Epochs:** 10
* **Batch Size:** 32
* **Dataset:** Custom annotated Car Damage Detection dataset

## 7. Tools and Technologies
* Python
* Google Colab / Jupyter Notebook
* Ultralytics YOLO
* YOLO11
* Matplotlib
* Pillow
* Gradio
* Roboflow

## 8. Project Pipeline
The complete project pipeline is:
1. Import required libraries.
2. Load the dataset ZIP file.
3. Extract the dataset.
4. Install Ultralytics.
5. Load the YOLO11n model.
6. Train the model for 10 epochs.
7. Validate the trained model.
8. Calculate evaluation metrics.
9. Display training results.
10. Display confusion matrix.
11. Display Precision-Recall curve.
12. Test the model on an image.
13. Test the model on a video.
14. Create a Gradio application.

## 9. Training
The YOLO11n model is trained using the custom dataset. 
 
