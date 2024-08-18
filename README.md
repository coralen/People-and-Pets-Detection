# People and Pets Recognition
## Overview
The "People and Pets Recognition" project focuses on object detection, specifically tailored for images featuring either people or pets. In this project, we use a pre-trained YOLOv8 model to classify and differentiate between human subjects and pets, which are specifically dogs and cats, in images. The project consists of three main stages:

1. **Train Set Creation**: Preparing and organizing the dataset to include images of people, dogs, and cats for model training.
2. **Model Training**: Training the YOLOv8 model using the prepared dataset.
3. **Model Inference**: Using the trained model to make predictions on new images, identifying whether the subject is a person, a dog, or a cat.

## Instructions for Running the Project
To run this project, follow these steps:

* **Environment**: The project is intended to be run in Google Colab with GPU resources for efficient model training. Note that the project was tested using Colab Pro to bypass daily usage limits.
*  **Storage Requirements**: Ensure that you have at least 2GB of available storage on Google Drive.
* **Google Drive Integration**: Each script includes a connection to Google Drive, assuming you are running the project in Google Colab. Shortly after starting a script, make sure to grant access to Google Drive. Failure to grant access in a timely manner will result in Drive errors and script failures.
* **Path Configuration**: To change the Google Drive path, edit the BASE_PATH variable in the scripts.
