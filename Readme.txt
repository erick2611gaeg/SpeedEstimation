Speed Estimation in Video Using Computer Vision Techniques and Neural Networks
This project demonstrates an automated solution for estimating vehicle speed in video sequences using advanced computer vision techniques and neural networks. The goal is to contribute to traffic analysis and monitoring systems by providing a real-time vehicle speed estimation tool.

The project involves processing video frames to detect and estimate the speed of vehicles through supervised learning models, specifically Convolutional Neural Networks (CNNs). The workflow is executed within the provided Jupyter Notebook.

Project Description
This project utilizes computer vision and deep learning techniques to estimate the speed of vehicles from video footage. The key components include:

Data:
This project uses the Vehicle Speed Estimation Dataset (VS13) to train and evaluate the model. 

The dataset includes:
Video Files: 
Footage of vehicles moving at various speeds.
Annotations: Ground truth labels for the actual speed of vehicles in each video.
How to Access the Dataset
Visit the VS13 Dataset page.
Preprocessing
The raw video data needs to be preprocessed into frames before being fed into the model. Instructions for preprocessing are included in the Main_V1.ipynb notebook.+

Modeling: A deep learning model based on CNN is used to estimate the vehicle speed from the video frames.
Environment Setup: All dependencies are listed in the Enviroment.yaml file for easy environment setup.

File Structure
Enviroment.yaml: Contains the environment dependencies and configurations for the project.
Main_V1.ipynb: The main Jupyter Notebook that performs the workflow (data preprocessing, training, and speed estimation).
data/: Put the VS13 data.
models/: are pre-defined in code.

