#Deep Face Detection Model

##Project Overview
This project develops a deep learning-based face detection model aimed at enhancing security measures in office environments. The model is trained on a local dataset of team member images and is designed to accurately recognize and identify individuals for access control purposes.


##Features

Custom dataset creation and preprocessing
Data augmentation using the Albumentations library
Implementation of a CNN model using VGG16 architecture
Face detection and recognition capabilities
High accuracy in classification and localization tasks

##Technologies Used

Python
TensorFlow / Keras
VGG16 (pre-trained model)
Labelme (for data annotation)
Albumentations (for data augmentation)

##Project Structure

Data Collection and Preprocessing
Data Annotation
Data Splitting
Data Augmentation
Model Building and Training
Model Evaluation

##Key Results

100% accuracy on training and validation datasets
96.53% accuracy on the test dataset
89.94% Intersection Over Union (IoU) on the test dataset

##App Deployment
We've deployed a demo version of our face detection model as a web application using Heroku. This allows users to interact with the model and test its capabilities in real time.



##Technical Details
list of technologies used in a project, likely for web development and deployment. Here's a breakdown of the technologies mentioned:

1. Heroku provides the cloud platform and web server for hosting the application.
2. Flask is used as the backend framework, written in Python, to create a RESTful API service.
3. HTML5, CSS3, and JavaScript are used for building the front-end website and user interface.

##Limitations
The demo version may have restrictions on image size and processing time
For optimal performance, use clear, well-lit images of faces
Note: The demo is intended for testing purposes and may not reflect the full capabilities of the model described in this project.


##Acknowledgements
This project was completed as part of the Big Data Capstone Project (BDM 3035) at Lambton College, under the guidance of Professor. Meysam Effati.

For more detailed information, please refer to the full project report.
