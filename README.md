
# IoT-Based NLR and MLR Monitoring System

## Project Overview

This project aims to develop a low-cost IoT-based prototype for monitoring Neutrophil-to-Lymphocyte Ratio (NLR) and Monocyte-to-Lymphocyte Ratio (MLR) using blood-smear images.

The system captures blood sample images using an OV7670 camera connected to an Arduino Uno. Python-based image processing and a trained YOLO model are used to detect and count blood cells.

## Technologies Used

* Arduino Uno
* OV7670 Camera
* Python
* OpenCV
* YOLO
* Java
* OLED Display

## Workflow

1. Prepare the blood smear sample on a glass slide.
2. Capture the image using the OV7670 camera.
3. Transfer the image to the computer.
4. Enhance the image using Python and OpenCV.
5. Detect blood cells using the trained YOLO model.
6. Calculate NLR and MLR.
7. Display the calculated ratios on the OLED.

## Project Objectives

* Develop a low-cost prototype.
* Capture and process blood-smear images.
* Detect neutrophils, lymphocytes, and monocytes.
* Calculate NLR and MLR.
* Display the calculated values.

## Disclaimer

This project is an academic prototype for research and monitoring purposes. It is not a validated medical diagnostic device. Results require clinical validation.
