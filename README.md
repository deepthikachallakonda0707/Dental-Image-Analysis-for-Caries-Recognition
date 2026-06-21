# Dental-Image-Analysis-for-Caries-Recognition

## Overview
This project focuses on the automated detection of dental caries (tooth decay) from dental X-ray images using deep learning techniques. The objective is to assist dentists in early diagnosis by providing a fast and accurate computer-aided detection system.
The model is developed using YOLOv8 object detection and trained on annotated dental X-ray images to identify and localize carious regions.

## Features
* Automated dental caries detection from X-ray images
* YOLOv8-based object detection model
* Detection and localization of caries regions
* Evaluation using standard object detection metrics
* Sample predictions and training results included

## Technologies Used
* Python
* YOLOv8 (Ultralytics)
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook
  
## Installation

'''bash
git clone https://github.com/deepthikachallakonda0707/Dental-Image-Analysis-for-Caries-Recognition.git
cd Dental-Image-Analysis-for-Caries-Recognition
pip install -r requirements.txt

## Dataset
The dataset consists of annotated dental X-ray images collected from Roboflow.

Dataset Structure:
* Train
* Validation
* Test

Classes:
* Caries

## Project Structure
Dental-Image-Analysis-for-Caries-Recognition/
├── Code.ipynb
├── dataset/
├── test_images/
├── results/
├── README.md
└── requirements.txt

## Model
The project uses YOLOv8 for object detection.

Training Pipeline:
1. Data Collection and Annotation
2. Data Preprocessing
3. YOLOv8 Model Training
4. Model Evaluation
5. Prediction on New Images

## Results
The trained model successfully detects dental caries in X-ray images and demonstrates the effectiveness of deep learning for dental image analysis.
Sample prediction results and evaluation metrics are available in the `results` folder.


## Future Improvements
* Increase dataset size for improved generalization
* Deploy as a web application
* Support detection of additional dental abnormalities
* Improve model performance using advanced augmentation techniques

## Author
Deepthika Challakonda
