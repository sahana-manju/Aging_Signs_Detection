# Aging Signs Detection App

## Overview

The **Aging Signs Detection** app uses advanced machine learning models to detect aging signs such as **puffy eyes**, **wrinkles**, and **dark spots** from an image. This app integrates two powerful models:

- **EfficientNet B5**: Used to detect puffy eyes.
- **EfficientDet D0**: Used for detecting wrinkles and dark spots.

This project was developed as part of an internship, and our team won the **Best Approach** award for our work.

## Features

- **Puffy Eye Detection**: Utilizes EfficientNet B5 to identify and highlight puffy eyes in images.
- **Wrinkle and Dark Spot Detection**: Leverages the EfficientDet object detection model to locate and highlight wrinkles and dark spots.
  
## Dataset

The dataset was collected from various online sources by the team to train the models. The dataset contains annotated images of faces with aging signs to help the models learn to recognize puffy eyes, wrinkles, and dark spots effectively.

## Model Training

- The models were trained for **4 hours** using **TPU** for enhanced performance.
- EfficientNet B5 was specifically trained to detect features of puffy eyes.
- EfficientDet was used to detect wrinkles and dark spots, offering accurate object detection on the facial features.

## Installation and Setup

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- Other dependencies as specified in the requirements.txt

### Steps to Run the App

1. Clone the Repository
2. Please run the integrated_app_deployment.ipynb file to run the app 

